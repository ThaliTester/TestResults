#### Test 50388019b27d54e_thali06_samsung-SM-A300FU Logs


```--------- beginning of system
11-17 18:21:07.716  1019  1513 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
11-17 18:21:07.716  1019  1513 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
11-17 18:21:07.716  1019  1513 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
11-17 18:21:07.716  1019  1513 D BatteryService: stay LED for fully charged
11-17 18:21:07.716  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
11-17 18:21:07.716  1019  1019 I MotionRecognitionService: Plugged
11-17 18:21:07.716  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
11-17 18:21:07.726  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:21:07.726  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
11-17 18:21:07.726  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
11-17 18:21:07.726  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
11-17 18:21:07.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:07.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:07.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:07.756  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
11-17 18:21:07.756  1179  1179 D SViewCoverView: level :100 plugged : 2
,11-17 18:21:09.746   290   290 E SMD     : DCD OFF
11-17 18:21:09.846  5286  5286 D AndroidRuntime: 
11-17 18:21:09.846  5286  5286 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:21:09.846  5286  5286 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:09.846  5286  5286 D AndroidRuntime: readGMSProperty: start
11-17 18:21:09.846  5286  5286 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:21:09.846  5286  5286 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:21:09.846  5286  5286 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:21:09.846  5286  5286 D AndroidRuntime: readGMSProperty: end
11-17 18:21:09.846  5286  5286 D AndroidRuntime: addProductProperty: start
11-17 18:21:10.006  5286  5286 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:21:10.026  5286  5286 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:21:10.046  1019  1220 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:21:10.046  1019  1220 I PersonaManagerService: PersonaId don't exist
11-17 18:21:10.046  1019  1220 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:21:10.046  1019  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:21:10.056  1019  1220 W ActivityManager: mDVFSHelper.acquire()
11-17 18:21:10.066  1019  1220 D FocusedStackFrame: Set to : 0
11-17 18:21:10.066  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:21:10.066  1019  1049 D PhoneWindow: *FMB* installDecor flags : 25362712
11-17 18:21:10.066  1019  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:10.066  1019  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:10.066  1019  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:10.066  1019  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:10.086  5298  5298 E Zygote  : MountEmulatedStorage()
11-17 18:21:10.086  5298  5298 E Zygote  : v2
11-17 18:21:10.086  5298  5298 I libpersona: KNOX_SDCARD checking this for 10345
11-17 18:21:10.086  5298  5298 I libpersona: KNOX_SDCARD not a persona
11-17 18:21:10.086  5298  5298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:21:10.086  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:21:10.086  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:21:10.086   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, iello
11-17 18:21:10.086  5298  5298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:21:10.086  5298  5298 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:21:10.096  1019  1220 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5298 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:21:10.096  1019  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
11-17 18:21:10.096  1019  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:21:10.106  5298  5298 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:10.106  5298  5298 D ActivityThread: Added TimaKeyStore provider
11-17 18:21:10.116  1019  1220 D InputDispatcher: Focused application set to: xxxx
11-17 18:21:10.116  1019  1220 D InputDispatcher: Focus left window: 1475
11-17 18:21:10.116  1019  1690 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:21:10.116  1019  1019 V ActivityManager: Display changed displayId=0
11-17 18:21:10.116  5286  5286 D AndroidRuntime: Shutting down VM
11-17 18:21:10.126  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:21:10.136  1019  1690 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:21:10.146  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
11-17 18:21:10.156  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:21:10.156  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:21:10.176   259   450 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
11-17 18:21:10.176   259   447 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
11-17 18:21:10.176  1475  1475 V ActivityThread: updateVisibility : ActivityRecord{107ee2b4 token=android.os.BinderProxy@3a5574f7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:21:10.176  1475  1475 D Launcher: onTrimMemory. Level: 20
11-17 18:21:10.236  5298  5298 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
11-17 18:21:10.246  5298  5298 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8632-8634)
11-17 18:21:10.246  5298  5298 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:10.276  5298  5298 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fb2a3de}
11-17 18:21:10.276  5298  5298 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:10.276  5298  5298 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:21:10.296  5298  5298 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:21:10.296  5298  5298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:10.306  5298  5298 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:21:10.306  5298  5315 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:21:10.316  5298  5298 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:21:10.316  5298  5298 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:21:10.316  5298  5298 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:21:10.326  5298  5298 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
11-17 18:21:10.326  5298  5298 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
11-17 18:21:10.326  5298  5298 I Adreno-EGL: Build Date: 04/06/15 Mon
11-17 18:21:10.326  5298  5298 I Adreno-EGL: Local Branch: 
11-17 18:21:10.326  5298  5298 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
11-17 18:21:10.326  5298  5298 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
11-17 18:21:10.326  5298  5298 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
11-17 18:21:10.326  5286  5286 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:21:10.386  5298  5326 D BluetoothAdapter: 962130296: getState() :  mService = null. Returning STATE_OFF
,11-17 18:21:10.536  5298  5298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:21:10.546  5298  5298 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 18:21:10.556  5298  5298 D PhoneWindow: *FMB* installDecor mIsFloating : false
,11-17 18:21:10.556  5298  5298 D PhoneWindow: *FMB* installDecor flags : 8456448
,11-17 18:21:10.566  5298  5298 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,11-17 18:21:10.566  5298  5298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:21:10.566  5298  5298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:21:10.646  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{6dc31cc u0 com.example.hello/.MainActivity t19}
,11-17 18:21:10.716  5298  5337 D OpenGLRenderer: Render dirty regions requested: true
,11-17 18:21:10.716  1019  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,11-17 18:21:10.716  1019  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:21:10.716  1019  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
11-17 18:21:10.716  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:21:10.716  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!,
,11-17 18:21:10.726  5298  5324 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
11-17 18:21:10.726  5298  5298 V ActivityThread: updateVisibility : ActivityRecord{11a7a8a8 token=android.os.BinderProxy@1f59579a {com.example.hello/com.example.hello.MainActivity}} show : true
,11-17 18:21:10.736  5298  5298 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,11-17 18:21:10.736  5298  5298 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,11-17 18:21:10.746   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,11-17 18:21:10.766  1019  1079 D InputDispatcher: Focus entered window: 5298
,11-17 18:21:10.766  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,11-17 18:21:10.766  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,11-17 18:21:10.766  5298  5298 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,11-17 18:21:10.766  5298  5337 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 18:21:10.766  5298  5337 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
11-17 18:21:10.766  5298  5337 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:21:10.786  1019  1220 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,11-17 18:21:10.786  1179  1179 I StatusBar: Icon Only,
11-17 18:21:10.786  1179  1179 D PanelView: There is/are notification(s) 
,11-17 18:21:10.796  1019  5339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:21:10.806  5298  5298 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
11-17 18:21:10.806  5298  5298 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f59579a time:89193
11-17 18:21:10.806  1765  1765 I SamsungIME: getCurrentCandidateView
,11-17 18:21:10.836  1019  1049 I ActivityManager: Displayed Component not be shown by security: +698ms (total +771ms)
,11-17 18:21:10.836  1019  1049 W ActivityManager: mDVFSHelper.release()
11-17 18:21:10.836  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6dc31cc u0 com.example.hello/.MainActivity t19} time:89229
,11-17 18:21:10.866   259   447 I SurfaceFlinger: id=11 Removed iello (7/9)
,11-17 18:21:10.866   259  1100 I SurfaceFlinger: id=11 Removed iello (-2/9)
,11-17 18:21:10.886  1765  1765 D SamsungIME: Dismiss ExpandCandiate
,11-17 18:21:10.916  1765  1765 I SamsungIME: getDebugLevel  : 0x4f4c
,11-17 18:21:10.966  1765  1765 I SamsungIME: getDebugLevel  : 0x4f4c
,11-17 18:21:10.986  1765  1765 I SamsungIME: KeybaordView init() : load resources
,11-17 18:21:10.986  5298  5298 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5298
,11-17 18:21:11.016  1765  1765 I SamsungIME: getCurrentKeyboard
11-17 18:21:11.016  1765  1765 I SamsungIME: getTextKeyboard
,11-17 18:21:11.026  5298  5298 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:21:11.026  1019  2590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:21:11.046  1765  1765 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,11-17 18:21:11.116  5298  5298 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:21:11.136  5298  5344 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,11-17 18:21:11.246  5298  5340 D jxcore_app_log: JniHelper::setJavaVM(0xb8aa7448), pthread_self() = -1191187304
,11-17 18:21:11.246  5298  5340 D JX-Cordova: jxcore cordova android initializing
,11-17 18:21:11.286  5298  5298 W jxcore-log: Initializing JXcore engine
11-17 18:21:11.286  5298  5298 W jxcore-log: JXcore engine is ready
,11-17 18:21:11.296  5298  5298 W jxcore-log: Starting JXcore engine
,11-17 18:21:11.356  1784  1784 E audit   : type=1400 msg=audit(1447780871.356:203): avc:  denied  { ioctl } for  pid=5298 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-17 18:21:11.356  1784  1784 E audit   :  SEPF_SM-A300FU_5.0.2_0027
,11-17 18:21:11.356  1784  1784 E audit   : type=1300 msg=audit(1447780871.356:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bea36d58 items=0 ppid=308 ppcomm=main pid=5298 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
11-17 18:21:11.356  1784  1784 E audit   : type=1320 msg=audit(1447780871.356:203): 
,11-17 18:21:11.476  5298  5298 W jxcore-log: Platform android
11-17 18:21:11.476  5298  5298 W jxcore-log: 
11-17 18:21:11.476  5298  5298 W jxcore-log: Process ARCH arm
11-17 18:21:11.476  5298  5298 W jxcore-log: 
,11-17 18:21:11.526  5298  5298 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:21:11.526  5298  5298 I jxcore-log: 
,11-17 18:21:11.526  5298  5298 W jxcore-log: JXcore engine is started
,11-17 18:21:11.566  5298  5298 E jxcore-log: >> samsung-SM-A300FU
11-17 18:21:11.566  5298  5298 E jxcore-log: 
,11-17 18:21:11.566  5298  5298 I jxcore-log: Total memory 1451114496
11-17 18:21:11.566  5298  5298 I jxcore-log: 
,11-17 18:21:11.566  5298  5298 I jxcore-log: Free memory 26705920
11-17 18:21:11.566  5298  5298 I jxcore-log: 
11-17 18:21:11.566  5298  5298 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:21:11.566  5298  5298 I jxcore-log: 
11-17 18:21:11.566  5298  5298 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:21:11.566  5298  5298 I jxcore-log: 
,11-17 18:21:11.566  5298  5298 I jxcore-log: userPath [ 'www' ]
11-17 18:21:11.566  5298  5298 I jxcore-log: 
,11-17 18:21:11.576  5298  5298 I jxcore-log: Size 540 960
11-17 18:21:11.576  5298  5298 I jxcore-log: 
,11-17 18:21:11.576  5298  5298 I jxcore-log: Screen Brightness 160
11-17 18:21:11.576  5298  5298 I jxcore-log: 
,11-17 18:21:11.576  5298  5298 E jxcore-log: Dummy Error Log.
11-17 18:21:11.576  5298  5298 E jxcore-log: 
,11-17 18:21:12.096  5298  5298 I jxcore-log: getBuffer is called!!!!
11-17 18:21:12.096  5298  5298 I jxcore-log: 
,11-17 18:21:12.746   290   290 E SMD     : DCD OFF
,11-17 18:21:13.336  1019  2578 D SSRM:n  : SIOP:: AP = 310
,11-17 18:21:15.746   290   290 E SMD     : DCD OFF
,11-17 18:21:16.026  1019  2590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:21:16.586  5298  5298 D BluetoothAdapter: disable()
,11-17 18:21:16.596  1019  1220 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:21:16.596  1019  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:21:16.596  1019  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,11-17 18:21:16.606  1019  1514 D SecContentProvider2: mCursor = null
,11-17 18:21:16.606  1019  1514 D WifiService: setWifiEnabled: false pid=5298, uid=10345
,11-17 18:21:16.606  1019  1514 D SettingsProvider: name = wifi_on
,11-17 18:21:16.606  5298  5298 I jxcore-log: ****TEST TOOK:  5054  ms ****
11-17 18:21:16.606  5298  5298 I jxcore-log: 
,11-17 18:21:16.616  5298  5298 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:21:16.616  5298  5298 I jxcore-log: 
,11-17 18:21:16.896  5349  5349 D AndroidRuntime: ,
11-17 18:21:16.896  5349  5349 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:21:16.896  5349  5349 D AndroidRuntime: CheckJNI is OFF,
11-17 18:21:16.896  5349  5349 D AndroidRuntime: readGMSProperty: start
11-17 18:21:16.896  5349  5349 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:21:16.896  5349  5349 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:21:16.896  5349  5349 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:21:16.896  5349  5349 D AndroidRuntime: readGMSProperty: end
11-17 18:21:16.896  5349  5349 D AndroidRuntime: addProductProperty: start
,11-17 18:21:17.026  5349  5349 E AffinityControl: AffinityControl: registerfunction enter,
,11-17 18:21:17.046  5349  5349 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,11-17 18:21:17.056  1019  3369 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,11-17 18:21:17.056  1019  3369 D PackageManager: START PACKAGE DELETE: observer{139891030}
11-17 18:21:17.056  1019  3369 D PackageManager: pkg{<packageName>}
11-17 18:21:17.056  1019  3369 D PackageManager: user{0}
11-17 18:21:17.056  1019  3369 D PackageManager: caller{2000}
11-17 18:21:17.056  1019  3369 D PackageManager: flags{3}
11-17 18:21:17.056  1019  3369 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:21:17.056  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,11-17 18:21:17.056  1019  3369 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
11-17 18:21:17.056  1019  3369 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:21:17.056  1019  3369 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:21:17.056  1019  1057 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
11-17 18:21:17.056  1019  1057 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
,11-17 18:21:17.066  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled,
11-17 18:21:17.066  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,11-17 18:21:17.066  1019  1057 D PackageManager: !@killApplicatoin: 10345, uninstall pkg,
,11-17 18:21:17.076  1019  1044 I ActivityManager: Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,11-17 18:21:17.076  1019  1044 I ActivityManager: Killing 5298:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,11-17 18:21:17.146  1019  1057 W PackageSettings: Skipping PackageSetting{2593e16 com.test.thalitest/10338} due to missing metadata
,11-17 18:21:17.176  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{6dc31cc u0 com.example.hello/.MainActivity t19}
,11-17 18:21:17.186  1019  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,11-17 18:21:17.196  1019  1101 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
,11-17 18:21:17.196  1019  1101 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,11-17 18:21:17.196  1019  1044 D InputDispatcher: Focus left window: 5298
,11-17 18:21:17.196  1019  1044 W InputDispatcher: Attempted to unregister already unregistered input channel
,11-17 18:21:17.206   259   450 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,11-17 18:21:17.216   259  1100 I SurfaceFlinger: id=12 Removed NainActivit (-2/8),
,11-17 18:21:17.216  1019  1044 D InputDispatcher: Focused application released,
,11-17 18:21:17.226  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:21:17.226  1019  1079 W WindowManager: Failed looking up window
11-17 18:21:17.226  1019  1079 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@39563239 does not exist
11-17 18:21:17.226  1019  1079 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
11-17 18:21:17.226  1019  1079 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
11-17 18:21:17.226  1019  1079 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
11-17 18:21:17.226  1019  1079 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
11-17 18:21:17.226  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:21:17.226  1019  1079 I WindowState: WIN DEATH: null
,11-17 18:21:17.226  1019  1057 I ActivityManager: Force stopping com.example.hello appid=10345 user=0: pkg removed
,11-17 18:21:17.256  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,11-17 18:21:17.266  3700  3700 I art     : Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 787us total 27.439ms
,11-17 18:21:17.286  1019  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:21:17.286  4155  4155 I art     : Explicit concurrent mark sweep GC freed 9971(666KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 1.074ms total 52.535ms
,11-17 18:21:17.296  1765  1765 E SamsungIME: mOCRHelper is null
,11-17 18:21:17.296  1648  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:21:17.336  3437  3437 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:21:17 GMT+01:00 2015
,11-17 18:21:17.336  1019  1513 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:21:17.336  1019  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.336  1019  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,11-17 18:21:17.356  3437  3437 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,11-17 18:21:17.356  1019  1690 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,11-17 18:21:17.356  1019  1690 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
11-17 18:21:17.356  1019  1690 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
11-17 18:21:17.356  1019  1690 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,11-17 18:21:17.356  1019  1690 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.356  1019  1690 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.356  1019  1690 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.356  1019  1690 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.376  5363  5363 E Zygote  : MountEmulatedStorage(),
11-17 18:21:17.376  5363  5363 E Zygote  : v2
11-17 18:21:17.376  5363  5363 I libpersona: KNOX_SDCARD checking this for 10090
11-17 18:21:17.376  5363  5363 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:17.376  1019  1690 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5363 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,11-17 18:21:17.376  5363  5363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:21:17.376  5363  5363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,11-17 18:21:17.376  5363  5363 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,11-17 18:21:17.406  3437  3437 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,11-17 18:21:17.406  1019  1220 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,11-17 18:21:17.416  1019  1220 D SecContentProvider2: mCursor = null
,11-17 18:21:17.416  1437  1437 D RegisteredServicesCache: empty dynamic service
,11-17 18:21:17.416  5363  5363 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:21:17.416  5363  5363 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:17.416  3437  3437 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,11-17 18:21:17.426  1019  1019 I art     : Explicit concurrent mark sweep GC freed 19349(1512KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 4.995ms total 171.403ms
,11-17 18:21:17.426  1019  1057 I art     : WaitForGcToComplete blocked for 118.358ms for cause Explicit
,11-17 18:21:17.426  3437  3437 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
11-17 18:21:17.446  3437  5362 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
11-17 18:21:17.446  3437  5362 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,11-17 18:21:17.446  3437  5362 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,11-17 18:21:17.446  3437  5362 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,11-17 18:21:17.476  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,11-17 18:21:17.476  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,11-17 18:21:17.476  5363  5363 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,11-17 18:21:17.476  5363  5363 D elm:15121: ELMEngine.ELMEngine( context ).
,11-17 18:21:17.476  5363  5363 D elm:15121: MDMBridge.setEnterpriseBridge()
,11-17 18:21:17.476  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,11-17 18:21:17.486  1019  1079 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:21:17.486  1019  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.486  1019  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,11-17 18:21:17.486  5363  5363 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,11-17 18:21:17.496  5363  5363 D elm:15121: ElmAgentService : onCreate()
,11-17 18:21:17.496  5363  5378 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,11-17 18:21:17.496  5363  5378 D elm:15121: MainReceiver.listeningToPackageRemoved()
,11-17 18:21:17.496  5363  5378 D elm:15121: MDMBridge.getInstance()
11-17 18:21:17.496  5363  5378 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:21:17.496  5363  5378 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:21:17.516  5363  5363 D elm:15121: ElmAgentService : onDestroy().
,11-17 18:21:17.516  1019  1690 I ActivityManager: Killing 4285:com.google.android.music:main/u0a108 (adj 15): empty #31
,11-17 18:21:17.526  3437  5362 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,11-17 18:21:17.526  3437  3437 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,11-17 18:21:17.566  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:17.566  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: uID is 10345
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:21:17.566  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
,11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: uID is 10345
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:21:17.566  1019  1161 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,11-17 18:21:17.566  1019  2578 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,11-17 18:21:17.566  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:21:17.616  1019  1057 I art     : Explicit concurrent mark sweep GC freed 8369(454KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.354ms total 185.134ms
,11-17 18:21:17.616  5045  5045 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
11-17 18:21:17.616  5045  5045 I PCWCLIENTTRACE_PushUtil: sales region : global
11-17 18:21:17.616  5045  5045 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
11-17 18:21:17.616  5045  5045 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,11-17 18:21:17.626  5165  5165 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,11-17 18:21:17.626  5165  5165 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,11-17 18:21:17.636  1019  1057 D PackageManager: delete codoeFile: 
,11-17 18:21:17.636  1019  3807 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:21:17.636  1019  3807 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.636  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
11-17 18:21:17.636  1019  1057 I AASA_removePackage: UID=10345 Target=com.example.hello
,11-17 18:21:17.636  1019  3807 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
11-17 18:21:17.636  1019  1057 D PackageManager: result of delete: 1{139891030}
,11-17 18:21:17.646  5349  5349 D AndroidRuntime: Shutting down VM
,11-17 18:21:17.656  4352  4352 I PackagesMonitor: PackagesMonitor onReceive :com.example.hello
,11-17 18:21:17.706  4213  4213 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:21:17.706  1019  1690 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:21:17.706  1019  1690 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.706  1019  1690 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,11-17 18:21:17.706  1019  1079 I TactileAssist: enable value -1
11-17 18:21:17.706  1019  1079 I TactileAssist: internal enable value -1
11-17 18:21:17.706  1019  1079 I TactileAssist: intensity value -1
11-17 18:21:17.706  1019  1079 I TactileAssist: saveAppList value true
,11-17 18:21:17.716  4213  5381 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
11-17 18:21:17.716  4213  5381 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,11-17 18:21:17.716  1019  1079 I TactileAssist: List of disabled apps :
,11-17 18:21:17.736  5064  5064 D Compatibility: onReceive() it will make start service
,11-17 18:21:17.736  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:21:17.736  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.736  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,11-17 18:21:17.746  1019  1301 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:21:17.746  1019  1301 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.746  1019  1301 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,11-17 18:21:17.746  5064  5382 D Compatibility: onHandleIntent()
,11-17 18:21:17.746  1019  3808 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.746  1019  3808 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.746  1019  3808 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.746  1019  3808 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.766  5064  5382 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,11-17 18:21:17.766  5383  5383 E Zygote  : MountEmulatedStorage()
11-17 18:21:17.766  5383  5383 E Zygote  : v2
11-17 18:21:17.766  5383  5383 I libpersona: KNOX_SDCARD checking this for 10055
11-17 18:21:17.766  5383  5383 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:17.766  5383  5383 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:21:17.766  5064  5382 D Compatibility: found: 2
11-17 18:21:17.766  5064  5382 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:21:17.766  5064  5382 D Compatibility: skipping ResolveInfo{2bc11fea com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:21:17.766  5064  5382 D Compatibility: considering ResolveInfo{11f012db com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
11-17 18:21:17.766  5064  5382 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:21:17.766  5383  5383 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:21:17.766  5383  5383 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:21:17.766  5064  5382 D Compatibility: enabling receiver ResolveInfo{3958f178 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
11-17 18:21:17.766  1019  3808 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5383 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,11-17 18:21:17.786  5064  5382 D Compatibility: enabling receiver ResolveInfo{3f419051 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:21:17.786  1019  1690 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,11-17 18:21:17.786  1019  1690 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
11-17 18:21:17.786  1019  1690 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
11-17 18:21:17.786  1019  1690 D BatteryService: stay LED for fully charged
11-17 18:21:17.786  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,11-17 18:21:17.786  5383  5383 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:17.786  1019  1019 I MotionRecognitionService: Plugged
11-17 18:21:17.786  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,11-17 18:21:17.786  5383  5383 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:17.796  5064  5382 D Compatibility: enabling receiver ResolveInfo{188950b6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:21:17.796  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,11-17 18:21:17.796  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
11-17 18:21:17.796  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,11-17 18:21:17.796  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
11-17 18:21:17.796  5064  5382 D Compatibility: enabling receiver ResolveInfo{2bd301b7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:21:17.806  5064  5382 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,11-17 18:21:17.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,11-17 18:21:17.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,11-17 18:21:17.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:21:17.816  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,11-17 18:21:17.826  1179  1179 D SViewCoverView: level :100 plugged : 2
,11-17 18:21:17.836  5383  5383 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,11-17 18:21:17.856  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
11-17 18:21:17.856  1019  1043 W TextServicesManagerService: no available spell checker services found
11-17 18:21:17.856  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,11-17 18:21:17.856  5349  5349 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:21:17.856  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.866  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.866  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,11-17 18:21:17.866  5383  5383 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,11-17 18:21:17.866  5383  5383 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
11-17 18:21:17.866  5383  5383 D UserAnalysis: Create SecureDbHelper
,11-17 18:21:17.866  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.876  5383  5383 D IntelligenceServiceApplication: onCreate()
,11-17 18:21:17.876  5383  5383 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,11-17 18:21:17.876  4423  4423 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:21:17.886  5383  5383 D IntelligenceServiceApplication: no applications having user consent for prediction
,11-17 18:21:17.886  1019  1483 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:21:17.886  1019  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.886  1019  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,11-17 18:21:17.886  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,11-17 18:21:17.886  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.886  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.886  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.886  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:17.896  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,11-17 18:21:17.906  5400  5400 E Zygote  : MountEmulatedStorage(),
11-17 18:21:17.906  5400  5400 E Zygote  : v2
11-17 18:21:17.906  5400  5400 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:17.906  5400  5400 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:17.906  5400  5400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
11-17 18:21:17.906  1019  1514 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:21:17.906  5400  5400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:21:17.906  5400  5400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:17.906  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
11-17 18:21:17.906  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,11-17 18:21:17.916  1019  1683 I ActivityManager: Killing 4860:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false,
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
11-17 18:21:17.916  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,11-17 18:21:17.926  5383  5383 D BluetoothAdapter: 428606035: getState() :  mService = null. Returning STATE_OFF
,11-17 18:21:17.926  5383  5383 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,11-17 18:21:17.936  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,11-17 18:21:17.936  5383  5383 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,11-17 18:21:17.936  5400  5400 D TimaKeyStoreProvider: TimaSignature is unavailable,
,11-17 18:21:17.946  5400  5400 D ActivityThread: Added TimaKeyStore provider
,11-17 18:21:17.956  5400  5400 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:21:17.956  5383  5383 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
,11-17 18:21:17.966  5383  5383 E SQLiteDatabase: Error inserting timestamp=1447780877943 message=Predictor: service stopped by removePlaceCategories()
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:21:17.966  5383  5383 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,11-17 18:21:17.966  5383  5383 E UserAnalysis: It failed to insert to dump_log table
,11-17 18:21:17.976  5400  5400 D RCPManager:  in createShortcut() for packageName: com.example.hello userId0
,11-17 18:21:17.976  1019  1479 D RCPManagerService:  in createShortcut() for packageName: com.example.hello userId0,
11-17 18:21:17.976  1019  1479 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,11-17 18:21:17.976  5115  5115 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,11-17 18:21:17.976  5115  5115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:21:17.976  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,11-17 18:21:17.986  1019  3808 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:21:17.986  1019  3808 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:21:17.986  1019  3808 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,11-17 18:21:17.986  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.986  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.986  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.986  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:21:17.986  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:17.986  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:21:17.986  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:17.996  1019  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.996  1019  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.996  1019  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.996  1019  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:17.996  5115  5115 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
11-17 18:21:17.996  5115  5416 I FilterInstaller: FilterPackageService : ACTION_REMOVED
11-17 18:21:17.996  5115  5416 D FilterUnInstaller: before removeFromFS
,11-17 18:21:18.006  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
11-17 18:21:18.006  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:18.016  5417  5417 E Zygote  : MountEmulatedStorage()
11-17 18:21:18.016  5417  5417 E Zygote  : v2
11-17 18:21:18.016  5417  5417 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:21:18.016  5417  5417 I libpersona: KNOX_SDCARD not a persona
11-17 18:21:18.016  1019  1513 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:21:18.016  5417  5417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:21:18.016  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:18.016  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:21:18.016  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
11-17 18:21:18.016  1019  3369 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:18.016  1019  3369 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:18.016  1019  3369 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:21:18.016  1019  3369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:21:18.016  5417  5417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:21:18.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:21:18.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
11-17 18:21:18.026  5417  5417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:18.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
11-17 18:21:18.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:21:18.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:21:18.036  5429  5429 E Zygote  : MountEmulatedStorage()
11-17 18:21:18.036  5429  5429 E Zygote  : v2
11-17 18:21:18.036  5429  5429 I libpersona: KNOX_SDCARD checking this for 10095
11-17 18:21:18.036  5429  5429 I libpersona: KNOX_SDCARD not a persona
,11-17 18:21:18.036  1019  3369 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5429 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
11-17 18:21:18.036  5429  5429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:21:18.036  1019  1043 D UsbSettingsManager: clearDefaults: com.example.hello
,11-17 18:21:18.036  1019  1043 I CrashAnrDetector: onPackageRemoved : com.example.hello
,11-17 18:21:18.036  1019  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_4285/cgroup.procs: No such file or directory
11-17 18:21:18.036  5429  5429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:21:18.036  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4860/cgroup.procs: No such file or directory
,11-17 18:21:18.036  5429  5429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:21:18.046  5417  5417 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:21:18.046  5417  5417 D ActivityThread: Added TimaKeyStore provider
```
