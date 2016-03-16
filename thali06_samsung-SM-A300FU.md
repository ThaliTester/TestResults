#### Test 63008475d624ed8_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system,
03-16 12:23:31.122  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
03-16 12:23:31.332  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:23:31.332  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:23:31.332  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:23:31.332  1017  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:23:31.332  1017  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:23:31.332  1017  1476 D BatteryService: stay LED for fully charged
03-16 12:23:31.332  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 12:23:31.332  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:23:31.332  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 12:23:31.342  1017  1017 I MotionRecognitionService: Plugged
03-16 12:23:31.342  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:23:31.342  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:23:31.342  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
03-16 12:23:31.352  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:31.352  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:31.352  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:31.352  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:23:31.352  1176  1176 D SViewCoverView: level :100 plugged : 2
03-16 12:23:31.402  6049  6049 D AndroidRuntime: 
03-16 12:23:31.402  6049  6049 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 12:23:31.412  6049  6049 D AndroidRuntime: CheckJNI is OFF
03-16 12:23:31.412  6049  6049 D AndroidRuntime: readGMSProperty: start
03-16 12:23:31.412  6049  6049 D AndroidRuntime: readGMSProperty: already setted!!
03-16 12:23:31.412  6049  6049 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 12:23:31.412  6049  6049 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 12:23:31.412  6049  6049 D AndroidRuntime: readGMSProperty: end
03-16 12:23:31.412  6049  6049 D AndroidRuntime: addProductProperty: start
03-16 12:23:31.552  6049  6049 E AffinityControl: AffinityControl: registerfunction enter
03-16 12:23:31.572  6049  6049 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 12:23:31.582  1017  3983 E PersonaManagerService: inState():  stateMachine is null !!
03-16 12:23:31.592  1017  3983 I PersonaManagerService: PersonaId don't exist
03-16 12:23:31.592  1017  3983 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 12:23:31.592  1017  3983 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:23:31.602  1017  3983 W ActivityManager: mDVFSHelper.acquire()
03-16 12:23:31.612  1017  3983 D FocusedStackFrame: Set to : 0
03-16 12:23:31.622  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 12:23:31.622  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:31.622  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:31.622  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:31.622  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:31.622  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 12:23:31.632  1017  3983 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 12:23:31.632  1017  3983 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6061 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 12:23:31.632  6061  6061 E Zygote  : MountEmulatedStorage()
03-16 12:23:31.632  6061  6061 I libpersona: KNOX_SDCARD checking this for 10167
03-16 12:23:31.632  6061  6061 E Zygote  : v2
03-16 12:23:31.632  6061  6061 I libpersona: KNOX_SDCARD not a persona
03-16 12:23:31.632  1017  3983 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:23:31.632  1017  3983 D InputDispatcher: Focused application set to: xxxx
03-16 12:23:31.632  1017  3983 D InputDispatcher: Focus left window: 1482
03-16 12:23:31.632  6049  6049 D AndroidRuntime: Shutting down VM
03-16 12:23:31.632  6061  6061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:23:31.642  6061  6061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:23:31.642  6061  6061 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 12:23:31.642  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 12:23:31.642  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 12:23:31.642   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-16 12:23:31.662  6061  6061 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:23:31.662  6061  6061 D ActivityThread: Added TimaKeyStore provider
03-16 12:23:31.662  1017  1481 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 12:23:31.662  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 12:23:31.672  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:23:31.672  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:23:31.682  1017  1481 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:23:31.692  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 12:23:31.722   259  1039 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-16 12:23:31.722   259   444 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-16 12:23:31.722  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{2be48407 token=android.os.BinderProxy@38663014 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 12:23:31.722  1482  1482 D Launcher: onTrimMemory. Level: 20
03-16 12:23:31.792  6061  6061 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-16 12:23:31.802  6061  6061 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7336-7337)
03-16 12:23:31.802  6061  6061 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 12:23:31.832  6061  6061 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1717933c}
03-16 12:23:31.832  6061  6061 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 12:23:31.832  6061  6061 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 12:23:31.842  6049  6049 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 12:23:31.862  6061  6061 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 12:23:31.862  6061  6061 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:23:31.862  6061  6061 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 12:23:31.882  6061  6061 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 12:23:31.882  6061  6061 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 12:23:31.882  6061  6061 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 12:23:31.882  6061  6061 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 12:23:31.882  6061  6061 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 12:23:31.882  6061  6061 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 12:23:31.882  6061  6061 I Adreno-EGL: Local Branch: 
03-16 12:23:31.882  6061  6061 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 12:23:31.882  6061  6061 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 12:23:31.882  6061  6061 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 12:23:32.082   290   290 E SMD     : DCD OFF
,03-16 12:23:32.122  6061  6061 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:23:32.132  6061  6061 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 12:23:32.142  6061  6061 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-16 12:23:32.142  6061  6061 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 12:23:32.142  6061  6061 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 12:23:32.152  6061  6061 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:23:32.152  6061  6061 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:23:32.182  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2432a514 u0 com.test.thalitest/.MainActivity t23}
,03-16 12:23:32.202  6061  6103 D OpenGLRenderer: Render dirty regions requested: true
,03-16 12:23:32.212  1017  3666 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-16 12:23:32.212  1017  3666 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:23:32.212  1017  3666 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:23:32.212  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:23:32.212  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 12:23:32.252  6061  6090 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 12:23:32.252  6061  6061 V ActivityThread: updateVisibility : ActivityRecord{2a19404 token=android.os.BinderProxy@33fe6496 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-16 12:23:32.262  6061  6061 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-16 12:23:32.262  6061  6061 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 12:23:32.272   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-16 12:23:32.292  1017  1030 D InputDispatcher: Focus entered window: 6061
,03-16 12:23:32.292  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:23:32.292  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 12:23:32.292  6061  6061 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 12:23:32.292  6061  6103 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 12:23:32.302  6061  6103 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-16 12:23:32.302  6061  6103 D OpenGLRenderer: Enabling debug mode 0
,03-16 12:23:32.342  1017  3836 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 12:23:32.352  1176  1176 I StatusBar: Icon Only
,03-16 12:23:32.352  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:23:32.352  1017  6105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:23:32.362  1017  1048 I ActivityManager: Displayed Component not be shown by security: +681ms (total +1m41s208ms)
,03-16 12:23:32.362  1017  1048 W ActivityManager: mDVFSHelper.release()
,03-16 12:23:32.362  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2432a514 u0 com.test.thalitest/.MainActivity t23} time:217897
,03-16 12:23:32.372  6061  6061 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 12:23:32.372  6061  6061 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33fe6496 time:217903
03-16 12:23:32.372   259  1039 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,03-16 12:23:32.372   259  1039 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,03-16 12:23:32.412  1841  1841 I SamsungIME: getCurrentCandidateView
,03-16 12:23:32.442  1841  1841 D SamsungIME: Dismiss ExpandCandiate
,03-16 12:23:32.482  1841  1841 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 12:23:32.522  1841  1841 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 12:23:32.542  1841  1841 I SamsungIME: KeybaordView init() : load resources
,03-16 12:23:32.552  6061  6061 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6061
,03-16 12:23:32.572  1841  1841 I SamsungIME: getCurrentKeyboard
03-16 12:23:32.572  1841  1841 I SamsungIME: getTextKeyboard
,03-16 12:23:32.612  1841  1841 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 12:23:32.612  1017  1050 I PowerManagerService: [PWL] Off : 140s ago
,03-16 12:23:32.702  6061  6061 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-16 12:23:32.822  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:23:32.892  6061  6107 D jxcore_app_log: JniHelper::setJavaVM(0xb7245448), pthread_self() = -1216712728
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 12:23:32.912  6061  6107 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a2ac5d added. We now have 1 listener(s)
03-16 12:23:32.912  6061  6107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
03-16 12:23:32.912  6061  6107 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 12:23:32.912  6061  6107 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 12:23:32.912  6061  6107 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 12:23:32.922  6061  6107 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0551a0 added. We now have 1 listener(s)
03-16 12:23:32.922  6061  6107 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-16 12:23:32.932  6061  6107 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-16 12:23:32.932  6061  6107 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 12:23:32.942  6061  6107 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 12:23:32.942  6061  6107 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 12:23:32.942  6061  6107 D io.jxcore.node.ConnectivityMonitor: start: OK
03-16 12:23:32.942  6061  6061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 12:23:32.952  6061  6061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 12:23:32.972  6061  6061 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-16 12:23:33.492  6061  6114 W jxcore-log: Initializing JXcore engine
03-16 12:23:33.492  6061  6114 W jxcore-log: JXcore engine is ready
03-16 12:23:33.542  1890  1890 E audit   : type=1400 msg=audit(1458127413.542:205): avc:  denied  { ioctl } for  pid=6114 comm="Thread-1049" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 12:23:33.542  1890  1890 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 12:23:33.542  1890  1890 E audit   : type=1300 msg=audit(1458127413.542:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9edfb8f8 items=0 ppid=305 ppcomm=main pid=6114 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1049" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 12:23:33.552  1890  1890 E audit   : type=1320 msg=audit(1458127413.542:205): 
03-16 12:23:33.562  6061  6114 W jxcore-log: Starting JXcore engine
03-16 12:23:33.662  6061  6114 W jxcore-log: Platform android
03-16 12:23:33.662  6061  6114 W jxcore-log: 
03-16 12:23:33.662  6061  6114 W jxcore-log: Process ARCH arm
03-16 12:23:33.662  6061  6114 W jxcore-log: 
03-16 12:23:33.862  6061  6114 I jxcore-log: JXcore Cordova bridge is ready!
03-16 12:23:33.862  6061  6114 I jxcore-log: 
03-16 12:23:33.862  6061  6114 W jxcore-log: JXcore engine is started
03-16 12:23:33.872  6061  6107 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-16 12:23:33.872  6061  6114 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 12:23:33.872  6061  6114 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-16 12:23:33.882  6061  6061 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
03-16 12:23:33.882  1017  1481 D FocusedStackFrame: Set to : 0
03-16 12:23:33.882  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:23:33.882  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 12:23:33.882  1017  1481 D InputDispatcher: Focused application set to: xxxx
03-16 12:23:33.892  1017  1481 D InputDispatcher: Focus left window: 6061
03-16 12:23:33.892  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:23:33.892  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:23:33.892  1017  1481 I ActivityManager: Killing 5181:com.google.android.gm/u0a99 (adj 15): empty #31
03-16 12:23:33.902  6061  6107 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
03-16 12:23:33.912   259   446 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
03-16 12:23:33.912   259   444 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
03-16 12:23:33.912  1017  1476 W ActivityManager: mDVFSHelper.acquire()
03-16 12:23:33.922  1017  1476 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 12:23:33.922  6061  6061 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@15e2b159 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:23:33.922  6061  6061 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@15e2b159 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 12:23:33.922  6061  6061 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2764d11e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:23:33.922  6061  6061 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2764d11e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:23:33.922  6061  6061 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 12:23:33.942  1482  1482 D Launcher: onRestart, Launcher: 790319435
03-16 12:23:33.942  1482  1482 D Launcher: onStart, Launcher: 790319435
03-16 12:23:33.942  1482  1482 D Launcher.HomeView: onStart
03-16 12:23:33.942  1482  1482 D Launcher: onResume, Launcher: 790319435
03-16 12:23:33.942  1017  1029 D SettingsProvider: name = kids_home_mode
03-16 12:23:33.942  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:23:33.942  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:23:33.942  1017  1029 D SettingsProvider: selectionArgs: false
03-16 12:23:33.942  1017  1029 D SettingsProvider: selectionArgs: 10006
03-16 12:23:33.942  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:23:33.942  1017  1029 D SettingsProvider: ret = -1
03-16 12:23:33.942  1482  1482 D Launcher.HomeView: onResume
03-16 12:23:33.952  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 12:23:33.952  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.952  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.952  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
03-16 12:23:33.952  1482  1482 D MenuAppsGridFragment: onResume
03-16 12:23:33.962  1017  3666 D ActivityManager: handle home activity for 0
03-16 12:23:33.962  1017  3666 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 12:23:33.962  1017  3666 D KnoxTimeoutHandler: post home show event for user 0
03-16 12:23:33.962  1017  3666 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 12:23:33.962  1017  3666 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:23:33.962  1017  3666 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:23:33.962  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 12:23:33.962  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 12:23:33.962  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 12:23:33.962  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:23:33.962  1017  1715 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-16 12:23:33.962  1017  1715 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
03-16 12:23:33.962  1482  1482 D Launcher.HomeView: onPause
03-16 12:23:33.962  1017  1715 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.962  1017  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.962  1017  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
03-16 12:23:33.962  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 12:23:33.962  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.962  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.962  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 12:23:33.962  4969  4969 D GalleryCacheReady: Receive : home resume
03-16 12:23:33.972  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.972  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.972  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
03-16 12:23:33.972  2535  2535 D Recents_RecreateReceiver: onReceive by home
03-16 12:23:33.972  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.972  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.972  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
03-16 12:23:33.982   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
03-16 12:23:33.982  1017  1715 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.982  1017  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.982  1017  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
03-16 12:23:33.982  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 12:23:33.982  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 12:23:33.992  5590  5590 D Mms/UIEventReceiver: ui event
03-16 12:23:33.992  1017  1029 D InputDispatcher: Focus entered window: 1482
03-16 12:23:33.992  1017  1715 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:33.992  1017  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:33.992  1017  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
03-16 12:23:33.992  5924  5924 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
03-16 12:23:33.992  1017  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:33.992  1017  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:33.992  1017  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:33.992  1017  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:23:33.992  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:23:33.992  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:23:33.992  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 12:23:34.002  6118  6118 E Zygote  : MountEmulatedStorage()
03-16 12:23:34.002  6118  6118 E Zygote  : v2
03-16 12:23:34.002  6118  6118 I libpersona: KNOX_SDCARD checking this for 10135
03-16 12:23:34.002  6118  6118 I libpersona: KNOX_SDCARD not a persona
03-16 12:23:34.002  6118  6118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:23:34.002  1017  3666 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 12:23:34.002  6118  6118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:23:34.012  1017  1715 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6118 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-16 12:23:34.012  1017  6123 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 12:23:34.012  6061  6061 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 12:23:34.012  1841  1841 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-16 12:23:34.012  6118  6118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:23:34.012  1017  1715 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:34.012  1017  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:34.012  1017  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 12:23:34.012  1017  1715 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1482, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-16 12:23:34.022  1017  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_5181/cgroup.procs: No such file or directory
03-16 12:23:34.022  1017  1476 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:23:34.022  1176  1176 I StatusBar: Icon Only
03-16 12:23:34.022  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:23:34.032  1017  1715 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:23:34.032  1017  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:34.032  1017  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
03-16 12:23:34.042  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{2be48407 token=android.os.BinderProxy@38663014 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 12:23:34.042  1482  1482 D Launcher.HomeView: onStop
03-16 12:23:34.042  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38663014 time:219574
03-16 12:23:34.052  1017  1048 W ActivityManager: mDVFSHelper.release()
03-16 12:23:34.052  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{362744b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:219582
03-16 12:23:34.062  6118  6118 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:23:34.062  6118  6118 D ActivityThread: Added TimaKeyStore provider
,03-16 12:23:34.072  6118  6118 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-16 12:23:34.072  6118  6118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:23:34.072  6118  6118 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 12:23:34.072  6118  6118 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 12:23:34.072  6118  6118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:23:34.102  1017  3666 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 12:23:34.112  1017  3666 I ActivityManager: Killing 4204:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-16 12:23:34.112  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:23:34.112  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:23:34.112  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 12:23:34.112  5924  5924 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-16 12:23:34.202  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 12:23:34.222  1017  1042 W libprocessgroup: failed to open /acct/uid_10032/pid_4204/cgroup.procs: No such file or directory
,03-16 12:23:35.082   290   290 E SMD     : DCD OFF
,03-16 12:23:38.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:23:38.082   290   290 E SMD     : DCD OFF
,03-16 12:23:39.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:40.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:41.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:41.082   290   290 E SMD     : DCD OFF
,03-16 12:23:41.392  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:23:41.392  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:23:41.392  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:23:41.392  1017  1029 D BatteryService: stay LED for fully charged
,03-16 12:23:41.392  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:23:41.392  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:23:41.392  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:23:41.402  1017  1017 I MotionRecognitionService: Plugged
03-16 12:23:41.402  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:23:41.402  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:23:41.402  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:23:41.412  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:23:41.412  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:23:41.422  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:23:41.422  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:41.422  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:23:41.422  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:23:41.422  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:23:41.632  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-16 12:23:42.042   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:23:42.732  1017  1327 E Watchdog: !@Sync 7
,03-16 12:23:42.842  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:23:43.042   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 12:23:44.082   290   290 E SMD     : DCD OFF
,03-16 12:23:47.082   290   290 E SMD     : DCD OFF
,03-16 12:23:48.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:49.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:50.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:50.092   290   290 E SMD     : DCD OFF
,03-16 12:23:51.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:23:51.122  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:23:51.452  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:23:51.452  1017  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:23:51.452  1017  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:23:51.452  1017  1481 D BatteryService: stay LED for fully charged
,03-16 12:23:51.452  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:23:51.452  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:23:51.452  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:23:51.462  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:23:51.462  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:23:51.462  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:23:51.462  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:23:51.472  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:23:51.472  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:23:51.482  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:23:51.482  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:51.482  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:23:51.482  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:23:51.482  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:23:52.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:23:52.862  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:23:53.052   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-16 12:23:53.092   290   290 E SMD     : DCD OFF
,03-16 12:23:56.092   290   290 E SMD     : DCD OFF
,03-16 12:23:59.092   290   290 E SMD     : DCD OFF
,03-16 12:23:59.992  1017  1097 V AlarmManager: waitForAlarm result :8,
,03-16 12:24:01.502  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:02.092   290   290 E SMD     : DCD OFF,
,03-16 12:24:02.902  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:24:03.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:04.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:05.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:05.092   290   290 E SMD     : DCD OFF
,03-16 12:24:06.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:07.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:24:08.052   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-16 12:24:08.092   290   290 E SMD     : DCD OFF,
,03-16 12:24:11.102   290   290 E SMD     : DCD OFF
,03-16 12:24:11.122  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:24:11.582  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:12.632  1017  1050 I PowerManagerService: [PWL] Off : 180s ago,
,03-16 12:24:12.732  1017  1327 E Watchdog: !@Sync 8
,03-16 12:24:12.942  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:24:14.102   290   290 E SMD     : DCD OFF
,03-16 12:24:17.102   290   290 E SMD     : DCD OFF,
,03-16 12:24:20.102   290   290 E SMD     : DCD OFF
,03-16 12:24:21.642  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:22.982  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:24:23.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:23.102   290   290 E SMD     : DCD OFF
,03-16 12:24:24.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:25.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:26.052   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:26.102   290   290 E SMD     : DCD OFF
,03-16 12:24:27.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:28.062   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-16 12:24:29.112   290   290 E SMD     : DCD OFF
,03-16 12:24:31.122  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:24:31.702  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:32.112   290   290 E SMD     : DCD OFF,
,03-16 12:24:33.022  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:24:35.112   290   290 E SMD     : DCD OFF
,03-16 12:24:38.112   290   290 E SMD     : DCD OFF
,03-16 12:24:41.112   290   290 E SMD     : DCD OFF
,03-16 12:24:41.772  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:41.832  1017  1097 V AlarmManager: waitForAlarm result :4,
,03-16 12:24:41.842  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 12:24:41.842  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:24:41.852  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-16 12:24:41.852  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 12:24:41.862  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:24:41.862  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:24:41.862  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:24:41.892  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:24:41.902  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:24:41.902  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:24:41.912  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 12:24:41.932  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:24:42.062  5952  6165 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 12:24:42.232  1017  1481 I art     : Explicit concurrent mark sweep GC freed 53193(3MB) AllocSpace objects, 76(1221KB) LOS objects, 33% free, 23MB/35MB, paused 2.374ms total 165.761ms
,03-16 12:24:42.262  5952  6167 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 12:24:42.272  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:24:42.272  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.272  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.302  1017  3983 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:24:42.302  1017  3983 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.302  1017  3983 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.322  1679  4008 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:24:42.322  1679  4008 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 12:24:42.322  1679  4008 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:24:42.322  1679  4008 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:24:42.322  1679  4008 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:24:42.332  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:24:42.332  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.332  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.362  1017  3835 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 12:24:42.362  1017  3835 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 12:24:42.362  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:24:42.372  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 12:24:42.372  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:24:42.372  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:24:42.372  1176  1176 I PhoneStatusBar: Icon Only
03-16 12:24:42.372  1176  1176 I StatusBar: Icon Only
03-16 12:24:42.372  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:24:42.372  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:24:42.382  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:24:42.382  1176  1176 I PhoneStatusBar: Icon Only
03-16 12:24:42.382  1176  1176 I StatusBar: Icon Only
03-16 12:24:42.382  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:24:42.382  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:24:42.382  1017  3666 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:24:42.382  1017  3666 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.382  1017  3666 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.392  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:24:42.392  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.392  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.412  1679  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:24:42.412  1679  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 12:24:42.412  1679  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:24:42.412  1679  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:24:42.422  1679  3976 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:24:42.422  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:24:42.422  1017  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:24:42.422  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:24:42.442  5952  6167 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 12:24:42.442  5952  6165 E BooksSync: Soft error
03-16 12:24:42.442  5952  6165 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:24:42.442  5952  6165 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-16 12:24:42.442  5952  6165 E BooksSync: Sync error
03-16 12:24:42.442  5952  6165 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:24:42.442  5952  6165 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 12:24:42.442  5952  6165 I BooksSync: Finished books sync
,03-16 12:24:42.452  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 12:24:42.452  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 287368, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 12:24:42.522  1017  3983 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 12:24:42.522  1017  3983 D SecContentProvider2: mCursor = null
,03-16 12:24:42.732  1017  1327 E Watchdog: !@Sync 9
,03-16 12:24:43.032  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:24:44.112   290   290 E SMD     : DCD OFF
,03-16 12:24:47.112   290   290 E SMD     : DCD OFF,
,03-16 12:24:48.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:49.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:24:50.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:24:50.122   290   290 E SMD     : DCD OFF
,03-16 12:24:51.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:24:51.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:24:51.832  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:24:52.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:24:53.062   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-16 12:24:53.072  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:24:53.122   290   290 E SMD     : DCD OFF,
,03-16 12:24:56.122   290   290 E SMD     : DCD OFF
,03-16 12:24:57.652  1017  1050 I PowerManagerService: [PWL] Off : 225s ago,
,03-16 12:24:59.122   290   290 E SMD     : DCD OFF
,03-16 12:24:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:25:01.892  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:25:02.122   290   290 E SMD     : DCD OFF,
,03-16 12:25:03.112  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:05.122   290   290 E SMD     : DCD OFF
,03-16 12:25:08.122   290   290 E SMD     : DCD OFF,
,03-16 12:25:09.802  1017  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
03-16 12:25:09.802  1017  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-16 12:25:09.802  1017  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 12:25:09.812  1017  1088 I TLC_TIMA_PKM_initialize: initializing...,
03-16 12:25:09.812  1017  1088 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-16 12:25:09.812  1017  1088 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
03-16 12:25:09.812  1017  1088 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-16 12:25:09.812  1017  1088 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
03-16 12:25:09.812  1017  1088 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
03-16 12:25:09.812  1017  1088 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040,
,03-16 12:25:09.812  1017  1088 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
03-16 12:25:09.812  1017  1088 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
03-16 12:25:09.812  1017  1088 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 12:25:09.842  1017  1088 D QSEECOMAPI: : Loaded image: APP id = 11
,03-16 12:25:09.852  1017  1088 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,03-16 12:25:09.862  1017  1088 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-16 12:25:11.132   290   290 E SMD     : DCD OFF
,03-16 12:25:11.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:25:11.802  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 12:25:11.802  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 12:25:11.812  1017  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:25:11.812  1017  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:25:11.952  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:25:11.952  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:25:11.952  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:25:11.962  1017  1030 D BatteryService: stay LED for fully charged
03-16 12:25:11.962  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:25:11.962  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:25:11.962  1017  1017 I MotionRecognitionService: Plugged
03-16 12:25:11.962  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:25:11.962  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:25:11.962  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 12:25:11.962  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-16 12:25:11.972  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:25:11.972  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:25:11.982  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:25:11.982  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:25:11.992  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:25:11.992  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:25:11.992  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:25:12.062  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:25:12.062  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-16 12:25:12.062  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:25:12.072  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 12:25:12.072  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 12:25:12.082  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:25:12.082  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:25:12.082  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:25:12.102  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:25:12.122  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:25:12.122  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:25:12.142  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,03-16 12:25:12.162  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:25:12.732  1017  1327 E Watchdog: !@Sync 10
,03-16 12:25:13.132  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:14.132   290   290 E SMD     : DCD OFF
,03-16 12:25:17.132   290   290 E SMD     : DCD OFF
,03-16 12:25:18.062   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-16 12:25:18.062   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 12:25:20.132   290   290 E SMD     : DCD OFF,
,03-16 12:25:22.022  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:25:22.022  1017  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:25:22.022  1017  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:25:22.022  1017  1476 D BatteryService: stay LED for fully charged
03-16 12:25:22.022  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:25:22.022  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:25:22.022  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:25:22.022  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:25:22.022  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:25:22.032  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:25:22.032  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:25:22.042  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:25:22.042  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:25:22.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:25:22.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:25:22.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:25:22.052  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:25:22.052  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:25:23.132   290   290 E SMD     : DCD OFF
,03-16 12:25:23.142  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:26.132   290   290 E SMD     : DCD OFF
,03-16 12:25:29.142   290   290 E SMD     : DCD OFF
,03-16 12:25:31.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:25:32.082  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:25:32.142   290   290 E SMD     : DCD OFF,
,03-16 12:25:33.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:33.182  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:34.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:35.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:35.142   290   290 E SMD     : DCD OFF
,03-16 12:25:36.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:37.062   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:38.062   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 12:25:38.142   290   290 E SMD     : DCD OFF,
,03-16 12:25:41.142   290   290 E SMD     : DCD OFF
,03-16 12:25:42.142  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:25:42.732  1017  1327 E Watchdog: !@Sync 11
,03-16 12:25:43.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:43.202  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:44.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:44.142   290   290 E SMD     : DCD OFF
,03-16 12:25:45.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:46.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:47.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:25:47.142   290   290 E SMD     : DCD OFF
,03-16 12:25:47.672  1017  1050 I PowerManagerService: [PWL] Off : 275s ago
,03-16 12:25:48.072   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-16 12:25:50.112  1679  1679 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:25:50.122  1017  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:25:50.122  1017  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:25:50.122  1017  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:25:50.142  1017  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:25:50.142  1017  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:25:50.142  1017  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:25:50.152   290   290 E SMD     : DCD OFF
,03-16 12:25:50.162  1679  4008 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-16 12:25:50.162  1679  4008 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 12:25:50.162  1679  4008 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:25:50.162  1679  4008 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:25:50.162  1679  4008 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:25:50.172  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:25:50.172  1017  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:25:50.172  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:25:50.192  1017  1472 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 12:25:50.192  1017  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-16 12:25:50.202  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:25:50.202  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 12:25:50.202  1679  4008 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-16 12:25:50.202  1679  4008 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:461)
,03-16 12:25:50.202  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:25:50.202  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:25:50.202  1176  1176 I PhoneStatusBar: Icon Only
03-16 12:25:50.202  1176  1176 I StatusBar: Icon Only
03-16 12:25:50.202  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:25:50.202  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
03-16 12:25:50.202  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:25:50.202  1176  1176 I PhoneStatusBar: Icon Only
,03-16 12:25:50.202  1176  1176 I StatusBar: Icon Only
03-16 12:25:50.212  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:25:50.212  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
03-16 12:25:50.212  5333  5366 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-16 12:25:50.212  5333  5366 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-16 12:25:50.212  5333  5366 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
03-16 12:25:50.212  5333  5366 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-16 12:25:50.212  5333  5366 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
03-16 12:25:50.212  5333  5366 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-16 12:25:50.212  5333  5366 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:461)
,03-16 12:25:50.232  5333  5366 W System  : Ignoring header User-Agent because its value was null.
,03-16 12:25:50.242  5333  5366 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-16 12:25:50.242  5333  5366 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-16 12:25:50.242  5333  5366 I System.out: (HTTPLog)-Static: isShipBuild true
03-16 12:25:50.242  5333  5366 I System.out: (HTTPLog)-Thread-908-989470720: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 12:25:50.242  5333  5366 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-16 12:25:50.242   279  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:25:50.242   279  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,03-16 12:25:50.252  5333  5366 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-16 12:25:50.282  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 12:25:51.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:25:52.202  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:25:52.202  1017  3666 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:25:52.202  1017  3666 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:25:52.202  1017  3666 D BatteryService: stay LED for fully charged
03-16 12:25:52.202  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:25:52.202  1017  1017 I MotionRecognitionService: Plugged,
03-16 12:25:52.202  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:25:52.212  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:25:52.212  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:25:52.212  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 12:25:52.212  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:25:52.232  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:25:52.232  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:25:52.232  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:25:52.232  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:25:52.232  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:25:52.232  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:25:52.232  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:25:53.152   290   290 E SMD     : DCD OFF,
,03-16 12:25:53.212  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:25:56.152   290   290 E SMD     : DCD OFF,
,03-16 12:25:58.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:25:59.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:25:59.152   290   290 E SMD     : DCD OFF
,03-16 12:25:59.992  1017  1097 V AlarmManager: waitForAlarm result :8,
,03-16 12:26:00.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:26:01.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:26:02.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:26:02.152   290   290 E SMD     : DCD OFF,
,03-16 12:26:02.262  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:26:02.262  1017  3835 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:26:02.262  1017  3835 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:26:02.262  1017  3835 D BatteryService: stay LED for fully charged
03-16 12:26:02.262  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:26:02.272  1017  1017 I MotionRecognitionService: Plugged
03-16 12:26:02.272  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:26:02.272  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:26:02.272  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:26:02.272  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:26:02.272  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:26:02.282  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:26:02.282  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:26:02.292  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:26:02.292  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:26:02.292  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:26:02.292  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:26:02.292  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:26:03.072   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 12:26:03.232  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:05.152   290   290 E SMD     : DCD OFF,
,03-16 12:26:08.152   290   290 E SMD     : DCD OFF,
,03-16 12:26:11.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:26:11.162   290   290 E SMD     : DCD OFF
,03-16 12:26:12.332  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 12:26:12.332  1017  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:26:12.332  1017  3836 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:26:12.332  1017  3836 D BatteryService: stay LED for fully charged
03-16 12:26:12.332  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 12:26:12.342  1017  1017 I MotionRecognitionService: Plugged
03-16 12:26:12.342  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
03-16 12:26:12.342  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:26:12.342  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:26:12.342  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 12:26:12.342  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-16 12:26:12.352  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:26:12.352  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:26:12.362  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:26:12.362  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:26:12.362  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:26:12.362  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:26:12.362  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:26:12.732  1017  1327 E Watchdog: !@Sync 12
,03-16 12:26:13.242  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:14.162   290   290 E SMD     : DCD OFF
,03-16 12:26:17.162   290   290 E SMD     : DCD OFF,
,03-16 12:26:18.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:19.072   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:20.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:20.162   290   290 E SMD     : DCD OFF
,03-16 12:26:21.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:22.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:22.392  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:26:23.082   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-16 12:26:23.162   290   290 E SMD     : DCD OFF
,03-16 12:26:23.262  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:26.162   290   290 E SMD     : DCD OFF
,03-16 12:26:29.172   290   290 E SMD     : DCD OFF
,03-16 12:26:31.132  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:26:32.172   290   290 E SMD     : DCD OFF
,03-16 12:26:32.462  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:26:32.462  1017  3666 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:26:32.462  1017  3666 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:26:32.462  1017  3666 D BatteryService: stay LED for fully charged
03-16 12:26:32.462  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:26:32.462  1017  1017 I MotionRecognitionService: Plugged
03-16 12:26:32.462  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:26:32.462  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:26:32.462  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:26:32.472  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:26:32.472  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:26:32.482  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:26:32.482  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:26:32.492  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:26:32.492  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:26:32.492  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:26:32.492  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:26:32.492  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:26:33.282  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:35.172   290   290 E SMD     : DCD OFF,
,03-16 12:26:38.172   290   290 E SMD     : DCD OFF,
,03-16 12:26:41.172   290   290 E SMD     : DCD OFF,
,03-16 12:26:42.522  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:26:42.682  1017  1050 I PowerManagerService: [PWL] Off : 330s ago
,03-16 12:26:42.742  1017  1327 E Watchdog: !@Sync 13
,03-16 12:26:43.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:43.322  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:44.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:44.182   290   290 E SMD     : DCD OFF,
,03-16 12:26:45.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:46.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:47.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:26:47.182   290   290 E SMD     : DCD OFF,
,03-16 12:26:48.082   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-16 12:26:50.182   290   290 E SMD     : DCD OFF,
,03-16 12:26:51.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:26:52.582  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:26:53.182   290   290 E SMD     : DCD OFF
,03-16 12:26:53.332  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:26:56.182   290   290 E SMD     : DCD OFF,
,03-16 12:26:59.192   290   290 E SMD     : DCD OFF,
,03-16 12:27:02.192   290   290 E SMD     : DCD OFF,
,03-16 12:27:02.642  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:27:03.372  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:27:05.192   290   290 E SMD     : DCD OFF,
,03-16 12:27:08.192   290   290 E SMD     : DCD OFF,
,03-16 12:27:11.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:27:11.192   290   290 E SMD     : DCD OFF,
,03-16 12:27:12.702  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:27:12.742  1017  1327 E Watchdog: !@Sync 14
,03-16 12:27:13.082   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-16 12:27:13.082   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 12:27:13.412  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:27:14.202   290   290 E SMD     : DCD OFF
,03-16 12:27:17.202   290   290 E SMD     : DCD OFF
,03-16 12:27:20.202   290   290 E SMD     : DCD OFF
,03-16 12:27:22.772  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:27:23.202   290   290 E SMD     : DCD OFF
,03-16 12:27:23.432  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:27:26.202   290   290 E SMD     : DCD OFF
,03-16 12:27:29.202   290   290 E SMD     : DCD OFF
,03-16 12:27:31.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:27:32.212   290   290 E SMD     : DCD OFF
,03-16 12:27:32.832  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:27:33.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:33.442  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:27:34.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:35.082   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:35.212   290   290 E SMD     : DCD OFF
,03-16 12:27:36.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:37.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:38.092   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 12:27:38.212   290   290 E SMD     : DCD OFF
,03-16 12:27:41.212   290   290 E SMD     : DCD OFF
,03-16 12:27:42.692  1017  1050 I PowerManagerService: [PWL] Off : 390s ago
,03-16 12:27:42.742  1017  1327 E Watchdog: !@Sync 15,
,03-16 12:27:42.892  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:27:42.892  1017  1715 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:27:42.892  1017  1715 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:27:42.892  1017  1715 D BatteryService: stay LED for fully charged
03-16 12:27:42.892  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:27:42.902  1017  1017 I MotionRecognitionService: Plugged,
03-16 12:27:42.902  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:27:42.902  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:27:42.902  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 12:27:42.902  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:27:42.902  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:27:42.912  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:27:42.912  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:27:42.922  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:27:42.922  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:27:42.922  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:27:42.922  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:27:42.922  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:27:43.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:43.462  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:27:44.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:44.212   290   290 E SMD     : DCD OFF
,03-16 12:27:45.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:27:46.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:47.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:47.212   290   290 E SMD     : DCD OFF
,03-16 12:27:48.092   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-16 12:27:50.222   290   290 E SMD     : DCD OFF
,03-16 12:27:51.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:27:52.952  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:27:53.222   290   290 E SMD     : DCD OFF
,03-16 12:27:53.502  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:27:56.222   290   290 E SMD     : DCD OFF
,03-16 12:27:58.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:59.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:27:59.222   290   290 E SMD     : DCD OFF
,03-16 12:28:00.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:01.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:01.132   313   313 I bootchecker: bootchecker wake up!!
,03-16 12:28:02.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:02.222   290   290 E SMD     : DCD OFF,
,03-16 12:28:03.012  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:28:03.022  1017  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-16 12:28:03.022  1017  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:28:03.022  1017  1216 D BatteryService: stay LED for fully charged
,03-16 12:28:03.022  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:28:03.022  1017  1017 I MotionRecognitionService: Plugged,
03-16 12:28:03.022  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:28:03.022  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:28:03.022  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:28:03.022  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:28:03.022  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:28:03.042  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:28:03.042  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:28:03.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:28:03.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:28:03.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:28:03.052  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:28:03.052  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:28:03.092   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-16 12:28:03.522  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:05.222   290   290 E SMD     : DCD OFF
,03-16 12:28:08.222   290   290 E SMD     : DCD OFF,
,03-16 12:28:11.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-16 12:28:11.232   290   290 E SMD     : DCD OFF,
,03-16 12:28:12.742  1017  1327 E Watchdog: !@Sync 16
,03-16 12:28:13.082  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:28:13.082  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:28:13.082  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:28:13.082  1017  1029 D BatteryService: stay LED for fully charged
03-16 12:28:13.082  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:28:13.082  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:28:13.082  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:28:13.092  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:28:13.092  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:28:13.092  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:28:13.092  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:28:13.102  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:28:13.102  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:28:13.112  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:28:13.112  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:28:13.112  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:28:13.112  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:28:13.112  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:28:13.542  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:14.232   290   290 E SMD     : DCD OFF
,03-16 12:28:17.232   290   290 E SMD     : DCD OFF
,03-16 12:28:18.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:19.092   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:20.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:20.232   290   290 E SMD     : DCD OFF
,03-16 12:28:21.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:22.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 12:28:23.102   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-16 12:28:23.142  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:28:23.232   290   290 E SMD     : DCD OFF
,03-16 12:28:23.552  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:26.232   290   290 E SMD     : DCD OFF
,03-16 12:28:29.242   290   290 E SMD     : DCD OFF
,03-16 12:28:31.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:28:32.242   290   290 E SMD     : DCD OFF
,03-16 12:28:33.202  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:28:33.572  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:35.242   290   290 E SMD     : DCD OFF
,03-16 12:28:38.242   290   290 E SMD     : DCD OFF
,03-16 12:28:41.242   290   290 E SMD     : DCD OFF
,03-16 12:28:42.742  1017  1327 E Watchdog: !@Sync 17
,03-16 12:28:43.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:43.272  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:28:43.592  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:44.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:44.242   290   290 E SMD     : DCD OFF
,03-16 12:28:45.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:46.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:47.102   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:28:47.242   290   290 E SMD     : DCD OFF
,03-16 12:28:47.692  1017  1050 I PowerManagerService: [PWL] Off : 455s ago
,03-16 12:28:48.102   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-16 12:28:50.252   290   290 E SMD     : DCD OFF
,03-16 12:28:51.142  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:28:53.252   290   290 E SMD     : DCD OFF
,03-16 12:28:53.332  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:28:53.612  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:28:56.252   290   290 E SMD     : DCD OFF
,03-16 12:28:59.252   290   290 E SMD     : DCD OFF
,03-16 12:28:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:28:59.992  1017  1097 V AlarmManager: No more alarm at this time.nowELAPSED=545524 batch.start=549539
,03-16 12:29:02.252   290   290 E SMD     : DCD OFF
,03-16 12:29:03.392  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:29:03.652  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:29:04.002  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:29:04.012  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 12:29:04.012  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:29:04.022  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 12:29:04.022  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1,
,03-16 12:29:04.032  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-16 12:29:04.032  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:29:04.032  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:29:04.052  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:29:04.072  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:29:04.072  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:29:04.082  5952  6277 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 12:29:04.092  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 12:29:04.102  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:29:04.122  5952  6278 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 12:29:04.122  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.122  1017  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.122  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.142  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.142  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.142  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.152  1679  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:29:04.152  1679  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-16 12:29:04.162  1679  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:29:04.162  1679  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:29:04.162  1679  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:29:04.162  1017  3983 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.172  1017  3983 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.172  1017  3983 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.192  1017  3983 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 12:29:04.192  1017  3983 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 12:29:04.192  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:29:04.202  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 12:29:04.202  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:29:04.202  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:29:04.202  1176  1176 I PhoneStatusBar: Icon Only
,03-16 12:29:04.202  1176  1176 I StatusBar: Icon Only
03-16 12:29:04.202  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:29:04.202  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:29:04.212  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.212  1017  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.212  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.212  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:29:04.212  1176  1176 I PhoneStatusBar: Icon Only
,03-16 12:29:04.212  1176  1176 I StatusBar: Icon Only
03-16 12:29:04.212  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:29:04.212  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:29:04.222  1017  1745 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.232  1017  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.232  1017  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.252  1679  1695 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:29:04.252  1679  1695 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 12:29:04.252  1679  1695 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:29:04.252  1679  1695 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:29:04.252  1679  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:29:04.262  1017  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:29:04.262  1017  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:29:04.262  1017  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:29:04.272  5952  6278 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 12:29:04.272  5952  6277 E BooksSync: Soft error
03-16 12:29:04.272  5952  6277 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:29:04.272  5952  6277 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-16 12:29:04.272  5952  6277 E BooksSync: Sync error
03-16 12:29:04.272  5952  6277 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:29:04.272  5952  6277 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-16 12:29:04.282  5952  6277 I BooksSync: Finished books sync
,03-16 12:29:04.282  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 12:29:04.282  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 549539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 12:29:04.342  1017  3836 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 12:29:04.342  1017  3836 D SecContentProvider2: mCursor = null
,03-16 12:29:05.252   290   290 E SMD     : DCD OFF
,03-16 12:29:08.252   290   290 E SMD     : DCD OFF
,03-16 12:29:11.152  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:29:11.262   290   290 E SMD     : DCD OFF
,03-16 12:29:12.742  1017  1327 E Watchdog: !@Sync 18
,03-16 12:29:13.102   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-16 12:29:13.102   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 12:29:13.462  1017  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:29:13.692  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:29:14.262   290   290 E SMD     : DCD OFF
,03-16 12:29:17.262   290   290 E SMD     : DCD OFF
,03-16 12:29:20.262   290   290 E SMD     : DCD OFF
,03-16 12:29:23.262   290   290 E SMD     : DCD OFF,
,03-16 12:29:23.522  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:29:23.522  1017  1753 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:29:23.522  1017  1753 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:29:23.522  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 12:29:23.522  1017  1753 D BatteryService: stay LED for fully charged
,03-16 12:29:23.522  1017  1017 I MotionRecognitionService: Plugged
03-16 12:29:23.522  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:29:23.532  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:29:23.532  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:29:23.532  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:29:23.532  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:29:23.542  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:29:23.542  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:29:23.552  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:29:23.552  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:29:23.552  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:29:23.552  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:29:23.552  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:29:23.712  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:29:26.262   290   290 E SMD     : DCD OFF
,03-16 12:29:29.272   290   290 E SMD     : DCD OFF,
,03-16 12:29:31.152  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:29:32.272   290   290 E SMD     : DCD OFF
,03-16 12:29:33.582  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:29:33.582  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:29:33.582  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:29:33.582  1017  1030 D BatteryService: stay LED for fully charged
03-16 12:29:33.582  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:29:33.592  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:29:33.592  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:29:33.592  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:29:33.592  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:29:33.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:29:33.602  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:29:33.602  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:29:33.612  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:29:33.612  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:29:33.622  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:29:33.622  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:29:33.622  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:29:33.622  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:29:33.722  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:29:34.072  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:29:35.272   290   290 E SMD     : DCD OFF
,03-16 12:29:38.102   316   316 I Atfwd_Daemon: Stop the daemon....,
,03-16 12:29:38.272   290   290 E SMD     : DCD OFF,
,03-16 12:29:41.272   290   290 E SMD     : DCD OFF
,03-16 12:29:42.742  1017  1327 E Watchdog: !@Sync 19
,03-16 12:29:43.652  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:29:43.742  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:29:44.272   290   290 E SMD     : DCD OFF
,03-16 12:29:47.272   290   290 E SMD     : DCD OFF
,03-16 12:29:50.282   290   290 E SMD     : DCD OFF
,03-16 12:29:51.152  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:29:53.282   290   290 E SMD     : DCD OFF
,03-16 12:29:53.712  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:29:53.782  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:29:56.282   290   290 E SMD     : DCD OFF
,03-16 12:29:57.692  1017  1050 I PowerManagerService: [PWL] Off : 525s ago
,03-16 12:29:59.282   290   290 E SMD     : DCD OFF
,03-16 12:29:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:30:02.282   290   290 E SMD     : DCD OFF
,03-16 12:30:03.772  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:30:03.822  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:30:05.282   290   290 E SMD     : DCD OFF
,03-16 12:30:08.292   290   290 E SMD     : DCD OFF
,03-16 12:30:09.802  1017  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 12:30:09.802  1017  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-16 12:30:09.802  1017  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 12:30:10.642  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 12:30:10.642  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 12:30:10.652  1017  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:30:10.652  1017  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:30:11.152  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:30:11.292   290   290 E SMD     : DCD OFF
,03-16 12:30:12.742  1017  1327 E Watchdog: !@Sync 20,
,03-16 12:30:13.842  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:30:13.862  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:30:14.292   290   290 E SMD     : DCD OFF
,03-16 12:30:17.292   290   290 E SMD     : DCD OFF,
,03-16 12:30:20.292   290   290 E SMD     : DCD OFF
,03-16 12:30:23.292   290   290 E SMD     : DCD OFF
,03-16 12:30:23.902  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:30:23.902  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:30:26.292   290   290 E SMD     : DCD OFF
,03-16 12:30:29.302   290   290 E SMD     : DCD OFF
,03-16 12:30:31.152  1017  2827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:30:32.302   290   290 E SMD     : DCD OFF,
,03-16 12:30:33.912  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:30:33.972  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:30:33.972  1017  3835 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:30:33.972  1017  3835 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:30:33.972  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:30:33.972  1017  3835 D BatteryService: stay LED for fully charged
,03-16 12:30:33.972  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:30:33.972  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:30:33.972  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:30:33.972  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:30:33.982  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:30:33.982  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:30:33.992  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:30:33.992  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:30:34.002  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:30:34.002  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:30:34.002  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:30:34.002  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:30:34.002  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:30:35.302   290   290 E SMD     : DCD OFF
,03-16 12:30:38.302   290   290 E SMD     : DCD OFF
,03-16 12:30:41.302   290   290 E SMD     : DCD OFF
,03-16 12:30:42.742  1017  1327 E Watchdog: !@Sync 21
,03-16 12:30:43.952  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:30:44.032  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:30:44.032  1017  1575 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:30:44.032  1017  1575 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:30:44.032  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 12:30:44.032  1017  1575 D BatteryService: stay LED for fully charged
,03-16 12:30:44.032  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:30:44.032  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:30:44.042  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:30:44.042  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:30:44.042  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:30:44.042  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:30:44.052  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:30:44.052  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:30:44.052  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:30:44.072  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:30:44.072  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:30:44.072  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:30:44.072  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:30:44.302   290   290 E SMD     : DCD OFF
,03-16 12:30:47.302   290   290 E SMD     : DCD OFF,
,03-16 12:30:50.312   290   290 E SMD     : DCD OFF
,03-16 12:30:53.312   290   290 E SMD     : DCD OFF
,03-16 12:30:53.972  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:30:54.092  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:30:56.312   290   290 E SMD     : DCD OFF
,03-16 12:30:59.312   290   290 E SMD     : DCD OFF
,03-16 12:31:02.312   290   290 E SMD     : DCD OFF,
,03-16 12:31:03.992  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:04.162  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:31:05.312   290   290 E SMD     : DCD OFF
,03-16 12:31:08.322   290   290 E SMD     : DCD OFF
,03-16 12:31:11.322   290   290 E SMD     : DCD OFF
,03-16 12:31:12.722  1017  1050 I PowerManagerService: [PWL] Off : 600s ago,
,03-16 12:31:12.742  1017  1327 E Watchdog: !@Sync 22
,03-16 12:31:14.002  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:14.222  1017  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:31:14.322   290   290 E SMD     : DCD OFF,
,03-16 12:31:17.322   290   290 E SMD     : DCD OFF,
,03-16 12:31:20.322   290   290 E SMD     : DCD OFF
,03-16 12:31:23.322   290   290 E SMD     : DCD OFF
,03-16 12:31:24.022  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:24.292  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:31:26.322   290   290 E SMD     : DCD OFF,
,03-16 12:31:29.332   290   290 E SMD     : DCD OFF
,03-16 12:31:32.332   290   290 E SMD     : DCD OFF,
,03-16 12:31:34.042  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:34.352  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:31:34.352  1017  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:31:34.352  1017  1472 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:31:34.352  1017  1472 D BatteryService: stay LED for fully charged
03-16 12:31:34.352  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:31:34.352  1017  1017 I MotionRecognitionService: Plugged
03-16 12:31:34.352  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:31:34.362  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 12:31:34.362  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:31:34.362  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:31:34.362  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:31:34.372  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:31:34.372  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:31:34.382  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:31:34.382  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:31:34.382  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:31:34.382  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:31:34.382  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:31:35.332   290   290 E SMD     : DCD OFF
,03-16 12:31:38.332   290   290 E SMD     : DCD OFF
,03-16 12:31:41.332   290   290 E SMD     : DCD OFF
,03-16 12:31:42.752  1017  1327 E Watchdog: !@Sync 23
,03-16 12:31:44.062  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:44.332   290   290 E SMD     : DCD OFF
,03-16 12:31:44.412  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:31:44.412  1017  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:31:44.412  1017  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 12:31:44.412  1017  1216 D BatteryService: stay LED for fully charged
03-16 12:31:44.412  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:31:44.412  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:31:44.412  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:31:44.422  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:31:44.422  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:31:44.422  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:31:44.422  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:31:44.422  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:31:44.432  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:31:44.432  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:31:44.442  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:31:44.442  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:31:44.442  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:31:44.442  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:31:47.342   290   290 E SMD     : DCD OFF,
,03-16 12:31:50.342   290   290 E SMD     : DCD OFF
,03-16 12:31:53.342   290   290 E SMD     : DCD OFF,
,03-16 12:31:54.082  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:31:54.472  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:31:56.342   290   290 E SMD     : DCD OFF
,03-16 12:31:59.342   290   290 E SMD     : DCD OFF
,03-16 12:32:02.342   290   290 E SMD     : DCD OFF,
,03-16 12:32:04.092  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:32:04.532  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:32:05.342   290   290 E SMD     : DCD OFF
,03-16 12:32:08.352   290   290 E SMD     : DCD OFF
,03-16 12:32:11.352   290   290 E SMD     : DCD OFF
,03-16 12:32:12.752  1017  1327 E Watchdog: !@Sync 24
,03-16 12:32:14.112  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:32:14.352   290   290 E SMD     : DCD OFF
,03-16 12:32:14.592  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:32:17.352   290   290 E SMD     : DCD OFF,
,03-16 12:32:20.352   290   290 E SMD     : DCD OFF
,03-16 12:32:23.352   290   290 E SMD     : DCD OFF,
,03-16 12:32:24.152  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:32:24.652  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:32:24.652  1017  3835 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:32:24.652  1017  3835 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:32:24.652  1017  3835 D BatteryService: stay LED for fully charged
03-16 12:32:24.652  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:32:24.662  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:32:24.662  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:32:24.662  1017  1017 I MotionRecognitionService: Plugged
03-16 12:32:24.662  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:32:24.662  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:32:24.662  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:32:24.672  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:32:24.672  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:32:24.682  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:24.682  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:24.682  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:24.682  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:32:24.682  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:32:26.362   290   290 E SMD     : DCD OFF
,03-16 12:32:29.362   290   290 E SMD     : DCD OFF
,03-16 12:32:32.362   290   290 E SMD     : DCD OFF,
,03-16 12:32:32.722  1017  1050 I PowerManagerService: [PWL] Off : 680s ago
,03-16 12:32:34.202  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:32:34.722  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:32:34.722  1017  1575 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:32:34.722  1017  1575 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:32:34.722  1017  1575 D BatteryService: stay LED for fully charged
03-16 12:32:34.722  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:32:34.722  1017  1017 I MotionRecognitionService: Plugged,
03-16 12:32:34.722  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:32:34.722  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:32:34.722  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:32:34.732  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:32:34.732  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:32:34.742  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:32:34.742  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:32:34.752  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 12:32:34.752  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:34.752  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:34.752  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:32:34.752  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:32:35.362   290   290 E SMD     : DCD OFF
,03-16 12:32:38.362   290   290 E SMD     : DCD OFF
,03-16 12:32:41.362   290   290 E SMD     : DCD OFF
,03-16 12:32:42.752  1017  1327 E Watchdog: !@Sync 25
,03-16 12:32:44.212  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:32:44.372   290   290 E SMD     : DCD OFF
,03-16 12:32:44.782  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:32:44.782  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:32:44.782  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:32:44.782  1017  1029 D BatteryService: stay LED for fully charged
03-16 12:32:44.782  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:32:44.782  1017  1017 I MotionRecognitionService: Plugged,
03-16 12:32:44.782  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:32:44.782  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:32:44.792  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:32:44.792  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:32:44.792  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:32:44.802  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 12:32:44.802  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:32:44.812  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:32:44.812  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:32:44.812  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:32:44.812  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:32:44.812  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:32:47.372   290   290 E SMD     : DCD OFF,
,03-16 12:32:50.372   290   290 E SMD     : DCD OFF
,03-16 12:32:53.372   290   290 E SMD     : DCD OFF,
,03-16 12:32:54.252  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:32:54.842  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:32:56.372   290   290 E SMD     : DCD OFF
,03-16 12:32:59.372   290   290 E SMD     : DCD OFF
,03-16 12:33:02.382   290   290 E SMD     : DCD OFF
,03-16 12:33:04.292  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:33:04.902  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:33:05.382   290   290 E SMD     : DCD OFF
,03-16 12:33:08.382   290   290 E SMD     : DCD OFF
,03-16 12:33:11.382   290   290 E SMD     : DCD OFF
,03-16 12:33:12.752  1017  1327 E Watchdog: !@Sync 26
,03-16 12:33:14.312  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:33:14.382   290   290 E SMD     : DCD OFF
,03-16 12:33:14.962  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:33:17.382   290   290 E SMD     : DCD OFF,
,03-16 12:33:20.382   290   290 E SMD     : DCD OFF,
,03-16 12:33:23.392   290   290 E SMD     : DCD OFF
,03-16 12:33:24.352  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:33:25.022  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:33:26.392   290   290 E SMD     : DCD OFF
,03-16 12:33:29.392   290   290 E SMD     : DCD OFF
,03-16 12:33:32.392   290   290 E SMD     : DCD OFF,
,03-16 12:33:34.372  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:33:35.092  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:33:35.392   290   290 E SMD     : DCD OFF
,03-16 12:33:38.402   290   290 E SMD     : DCD OFF
,03-16 12:33:41.402   290   290 E SMD     : DCD OFF
,03-16 12:33:42.752  1017  1327 E Watchdog: !@Sync 27
,03-16 12:33:44.402   290   290 E SMD     : DCD OFF
,03-16 12:33:44.412  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:33:45.152  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:33:47.402   290   290 E SMD     : DCD OFF
,03-16 12:33:50.402   290   290 E SMD     : DCD OFF
,03-16 12:33:53.402   290   290 E SMD     : DCD OFF
,03-16 12:33:54.442  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:33:55.212  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:33:56.402   290   290 E SMD     : DCD OFF
,03-16 12:33:57.772  1017  1050 I PowerManagerService: [PWL] Off : 765s ago
,03-16 12:33:59.412   290   290 E SMD     : DCD OFF,
,03-16 12:34:02.412   290   290 E SMD     : DCD OFF
,03-16 12:34:04.462  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:34:05.282  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:34:05.412   290   290 E SMD     : DCD OFF
,03-16 12:34:08.412   290   290 E SMD     : DCD OFF
,03-16 12:34:11.412   290   290 E SMD     : DCD OFF
,03-16 12:34:12.752  1017  1327 E Watchdog: !@Sync 28,
,03-16 12:34:14.412   290   290 E SMD     : DCD OFF
,03-16 12:34:14.492  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:34:15.342  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:34:17.422   290   290 E SMD     : DCD OFF
,03-16 12:34:20.422   290   290 E SMD     : DCD OFF
,03-16 12:34:23.422   290   290 E SMD     : DCD OFF,
,03-16 12:34:24.512  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:34:25.412  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:34:26.422   290   290 E SMD     : DCD OFF
,03-16 12:34:29.422   290   290 E SMD     : DCD OFF
,03-16 12:34:32.422   290   290 E SMD     : DCD OFF
,03-16 12:34:34.522  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:34:35.422   290   290 E SMD     : DCD OFF
,03-16 12:34:35.472  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:34:38.432   290   290 E SMD     : DCD OFF
,03-16 12:34:41.432   290   290 E SMD     : DCD OFF
,03-16 12:34:42.752  1017  1327 E Watchdog: !@Sync 29,
,03-16 12:34:44.432   290   290 E SMD     : DCD OFF
,03-16 12:34:44.542  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:34:45.532  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:34:47.432   290   290 E SMD     : DCD OFF
,03-16 12:34:50.432   290   290 E SMD     : DCD OFF
,03-16 12:34:53.432   290   290 E SMD     : DCD OFF,
,03-16 12:34:54.582  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:34:55.592  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:34:56.432   290   290 E SMD     : DCD OFF
,03-16 12:34:59.442   290   290 E SMD     : DCD OFF
,03-16 12:35:02.442   290   290 E SMD     : DCD OFF
,03-16 12:35:04.602  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:05.442   290   290 E SMD     : DCD OFF
,03-16 12:35:05.652  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:35:08.442   290   290 E SMD     : DCD OFF
,03-16 12:35:09.802  1017  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
03-16 12:35:09.802  1017  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-16 12:35:09.802  1017  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 12:35:11.442   290   290 E SMD     : DCD OFF
,03-16 12:35:11.752  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 12:35:11.752  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 12:35:11.752  1017  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:35:11.762  1017  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:35:12.752  1017  1327 E Watchdog: !@Sync 30,
,03-16 12:35:14.442   290   290 E SMD     : DCD OFF
,03-16 12:35:14.622  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:15.712  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:35:17.452   290   290 E SMD     : DCD OFF
,03-16 12:35:20.452   290   290 E SMD     : DCD OFF
,03-16 12:35:23.452   290   290 E SMD     : DCD OFF,
,03-16 12:35:23.812  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:35:23.812  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-16 12:35:23.812  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:35:23.832  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 12:35:23.832  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 12:35:23.842  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:35:23.842  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:35:23.842  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:35:23.872  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:35:23.882  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:35:23.882  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:35:23.882  1679  2628 D GCM     : Message class com.google.f.a.a.i
,03-16 12:35:23.892  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 12:35:23.912  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:35:24.662  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:25.782  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:35:26.452   290   290 E SMD     : DCD OFF
,03-16 12:35:27.772  1017  1050 I PowerManagerService: [PWL] Off : 855s ago,
,03-16 12:35:29.452   290   290 E SMD     : DCD OFF
,03-16 12:35:32.452   290   290 E SMD     : DCD OFF
,03-16 12:35:34.712  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:35.452   290   290 E SMD     : DCD OFF,
,03-16 12:35:35.842  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:35:38.462   290   290 E SMD     : DCD OFF
,03-16 12:35:41.462   290   290 E SMD     : DCD OFF
,03-16 12:35:42.752  1017  1327 E Watchdog: !@Sync 31,
,03-16 12:35:44.462   290   290 E SMD     : DCD OFF
,03-16 12:35:44.722  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:45.902  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:35:47.462   290   290 E SMD     : DCD OFF
,03-16 12:35:50.462   290   290 E SMD     : DCD OFF
,03-16 12:35:53.462   290   290 E SMD     : DCD OFF,
,03-16 12:35:54.742  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:35:55.972  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:35:56.472   290   290 E SMD     : DCD OFF
,03-16 12:35:59.472   290   290 E SMD     : DCD OFF
,03-16 12:35:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:36:02.472   290   290 E SMD     : DCD OFF
,03-16 12:36:04.762  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:36:05.472   290   290 E SMD     : DCD OFF
,03-16 12:36:06.032  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:36:08.472   290   290 E SMD     : DCD OFF
,03-16 12:36:11.472   290   290 E SMD     : DCD OFF
,03-16 12:36:12.752  1017  1327 E Watchdog: !@Sync 32
,03-16 12:36:14.482   290   290 E SMD     : DCD OFF,
,03-16 12:36:14.802  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:36:16.102  1017  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:36:17.482   290   290 E SMD     : DCD OFF
,03-16 12:36:20.482   290   290 E SMD     : DCD OFF,
,03-16 12:36:23.482   290   290 E SMD     : DCD OFF
,03-16 12:36:24.822  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:36:26.162  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:36:26.482   290   290 E SMD     : DCD OFF
,03-16 12:36:29.482   290   290 E SMD     : DCD OFF
,03-16 12:36:32.482   290   290 E SMD     : DCD OFF
,03-16 12:36:34.862  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:36:35.492   290   290 E SMD     : DCD OFF
,03-16 12:36:36.222  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:36:38.492   290   290 E SMD     : DCD OFF
,03-16 12:36:41.492   290   290 E SMD     : DCD OFF
,03-16 12:36:42.752  1017  1327 E Watchdog: !@Sync 33
,03-16 12:36:44.492   290   290 E SMD     : DCD OFF
,03-16 12:36:44.902  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:36:46.292  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:36:47.492   290   290 E SMD     : DCD OFF
,03-16 12:36:50.492   290   290 E SMD     : DCD OFF
,03-16 12:36:53.502   290   290 E SMD     : DCD OFF
,03-16 12:36:54.942  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:36:56.352  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:36:56.502   290   290 E SMD     : DCD OFF
,03-16 12:36:59.502   290   290 E SMD     : DCD OFF
,03-16 12:37:02.502   290   290 E SMD     : DCD OFF
,03-16 12:37:02.872  1017  1050 I PowerManagerService: [PWL] Off : 951s ago,
,03-16 12:37:04.962  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:05.502   290   290 E SMD     : DCD OFF
,03-16 12:37:06.412  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:37:08.502   290   290 E SMD     : DCD OFF
,03-16 12:37:11.502   290   290 E SMD     : DCD OFF
,03-16 12:37:12.762  1017  1327 E Watchdog: !@Sync 34
,03-16 12:37:14.512   290   290 E SMD     : DCD OFF
,03-16 12:37:14.972  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:16.482  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:37:17.512   290   290 E SMD     : DCD OFF
,03-16 12:37:20.512   290   290 E SMD     : DCD OFF
,03-16 12:37:23.512   290   290 E SMD     : DCD OFF
,03-16 12:37:25.022  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:26.512   290   290 E SMD     : DCD OFF,
,03-16 12:37:26.542  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:37:29.512   290   290 E SMD     : DCD OFF
,03-16 12:37:32.522   290   290 E SMD     : DCD OFF
,03-16 12:37:35.062  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:35.522   290   290 E SMD     : DCD OFF,
,03-16 12:37:36.602  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:37:38.522   290   290 E SMD     : DCD OFF
,03-16 12:37:41.522   290   290 E SMD     : DCD OFF
,03-16 12:37:42.762  1017  1327 E Watchdog: !@Sync 35
,03-16 12:37:44.522   290   290 E SMD     : DCD OFF
,03-16 12:37:45.112  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:46.672  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:37:47.382  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:37:47.392  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-16 12:37:47.392  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:37:47.402  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 12:37:47.402  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 12:37:47.412  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:37:47.412  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:37:47.412  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:37:47.432  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:37:47.442  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:37:47.442  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:37:47.452  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 12:37:47.462  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:37:47.522   290   290 E SMD     : DCD OFF
,03-16 12:37:47.902  5952  6491 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 12:37:47.922  5952  6492 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 12:37:47.922  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:47.922  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:47.922  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:37:47.942  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:47.942  1017  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:47.942  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:37:47.952  1679  2139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:37:47.952  1679  2139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-16 12:37:47.952  1679  2139 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:37:47.952  1679  2139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:37:47.962  1679  2139 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:37:47.962  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:47.962  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:47.962  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:37:47.972  1017  3666 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 12:37:47.972  1017  3666 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 12:37:47.982  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:37:47.982  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 12:37:47.982  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:37:47.982  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:37:47.982  1176  1176 I PhoneStatusBar: Icon Only
03-16 12:37:47.982  1176  1176 I StatusBar: Icon Only
03-16 12:37:47.982  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:37:47.982  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:37:47.982  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:37:47.982  1176  1176 I PhoneStatusBar: Icon Only
03-16 12:37:47.982  1176  1176 I StatusBar: Icon Only
03-16 12:37:47.982  1176  1176 D PanelView: There is/are notification(s) 
03-16 12:37:47.982  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:37:47.992  1017  3835 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:47.992  1017  3835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:47.992  1017  3835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 12:37:48.002  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:48.002  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:48.002  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:37:48.022  1679  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 12:37:48.022  1679  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-16 12:37:48.022  1679  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 12:37:48.022  1679  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 12:37:48.022  1679  3976 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:37:48.032  1017  1745 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:37:48.032  1017  1745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:37:48.032  1017  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 12:37:48.042  5952  6492 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 12:37:48.042  5952  6491 E BooksSync: Soft error
03-16 12:37:48.042  5952  6491 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:37:48.042  5952  6491 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 12:37:48.042  5952  6491 E BooksSync: Sync error
03-16 12:37:48.042  5952  6491 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 12:37:48.042  5952  6491 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 12:37:48.042  5952  6491 I BooksSync: Finished books sync
,03-16 12:37:48.042  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1072919, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 12:37:48.062  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 12:37:48.082  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 12:37:48.082  1017  1030 D SecContentProvider2: mCursor = null
,03-16 12:37:50.522   290   290 E SMD     : DCD OFF
,03-16 12:37:53.532   290   290 E SMD     : DCD OFF,
,03-16 12:37:55.132  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:37:56.532   290   290 E SMD     : DCD OFF
,03-16 12:37:56.732  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:37:59.532   290   290 E SMD     : DCD OFF
,03-16 12:37:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:38:02.532   290   290 E SMD     : DCD OFF
,03-16 12:38:05.172  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:38:05.532   290   290 E SMD     : DCD OFF
,03-16 12:38:06.792  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:38:08.532   290   290 E SMD     : DCD OFF,
,03-16 12:38:11.542   290   290 E SMD     : DCD OFF
,03-16 12:38:12.762  1017  1327 E Watchdog: !@Sync 36
,03-16 12:38:14.542   290   290 E SMD     : DCD OFF,
,03-16 12:38:15.202  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:38:16.862  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:38:17.542   290   290 E SMD     : DCD OFF
,03-16 12:38:17.902  1017  1097 V AlarmManager: waitForAlarm result :4
,03-16 12:38:17.902  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 12:38:17.902  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 12:38:17.912  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 12:38:17.912  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 12:38:17.922  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:38:17.922  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 12:38:17.922  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 12:38:17.942  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:38:17.962  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:38:17.962  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:38:17.972  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 12:38:17.992  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 12:38:20.542   290   290 E SMD     : DCD OFF,
,03-16 12:38:23.542   290   290 E SMD     : DCD OFF
,03-16 12:38:25.252  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:38:26.542   290   290 E SMD     : DCD OFF
,03-16 12:38:26.922  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:38:29.542   290   290 E SMD     : DCD OFF
,03-16 12:38:32.552   290   290 E SMD     : DCD OFF
,03-16 12:38:35.302  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:38:35.552   290   290 E SMD     : DCD OFF
,03-16 12:38:36.982  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:38:36.982  1017  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-16 12:38:36.982  1017  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:38:36.982  1017  1481 D BatteryService: stay LED for fully charged
,03-16 12:38:36.982  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:38:36.992  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:38:36.992  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:38:36.992  1017  1017 I MotionRecognitionService: Plugged
03-16 12:38:36.992  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:38:36.992  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:38:36.992  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:38:37.002  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:38:37.002  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:38:37.012  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:37.022  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:37.022  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:38:37.022  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:38:37.022  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:38:38.552   290   290 E SMD     : DCD OFF
,03-16 12:38:41.552   290   290 E SMD     : DCD OFF,
,03-16 12:38:42.762  1017  1327 E Watchdog: !@Sync 37
,03-16 12:38:42.872  1017  1050 I PowerManagerService: [PWL] Off : 1051s ago
,03-16 12:38:44.552   290   290 E SMD     : DCD OFF
,03-16 12:38:45.342  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:38:47.042  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:38:47.042  1017  3666 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:38:47.042  1017  3666 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:38:47.042  1017  3666 D BatteryService: stay LED for fully charged
03-16 12:38:47.042  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:38:47.042  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:38:47.042  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-16 12:38:47.052  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:38:47.052  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:38:47.052  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:38:47.052  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:38:47.052  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:38:47.052  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:38:47.072  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:47.072  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:47.072  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:47.072  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:38:47.072  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:38:47.552   290   290 E SMD     : DCD OFF
,03-16 12:38:50.562   290   290 E SMD     : DCD OFF
,03-16 12:38:53.562   290   290 E SMD     : DCD OFF
,03-16 12:38:55.382  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:38:56.562   290   290 E SMD     : DCD OFF
,03-16 12:38:57.102  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:38:57.102  1017  1715 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:38:57.102  1017  1715 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:38:57.102  1017  1715 D BatteryService: stay LED for fully charged
03-16 12:38:57.102  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:38:57.102  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:38:57.102  1017  1017 I MotionRecognitionService: Plugged
03-16 12:38:57.102  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:38:57.102  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:38:57.112  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:38:57.112  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:38:57.112  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:38:57.122  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:38:57.132  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:57.132  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:38:57.132  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:38:57.132  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:38:57.132  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:38:59.562   290   290 E SMD     : DCD OFF,
,03-16 12:38:59.992  1017  1097 V AlarmManager: waitForAlarm result :8
,03-16 12:39:02.562   290   290 E SMD     : DCD OFF
,03-16 12:39:05.432  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:39:05.562   290   290 E SMD     : DCD OFF,
,03-16 12:39:07.162  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:39:08.562   290   290 E SMD     : DCD OFF,
,03-16 12:39:11.572   290   290 E SMD     : DCD OFF
,03-16 12:39:12.762  1017  1327 E Watchdog: !@Sync 38
,03-16 12:39:14.572   290   290 E SMD     : DCD OFF,
,03-16 12:39:15.482  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:39:17.222  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:39:17.572   290   290 E SMD     : DCD OFF,
,03-16 12:39:20.572   290   290 E SMD     : DCD OFF
,03-16 12:39:23.572   290   290 E SMD     : DCD OFF
,03-16 12:39:25.532  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:39:26.572   290   290 E SMD     : DCD OFF
,03-16 12:39:27.282  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:39:29.582   290   290 E SMD     : DCD OFF
,03-16 12:39:32.582   290   290 E SMD     : DCD OFF,
,03-16 12:39:35.582  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:39:35.582   290   290 E SMD     : DCD OFF
,03-16 12:39:37.352  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:39:38.582   290   290 E SMD     : DCD OFF
,03-16 12:39:41.582   290   290 E SMD     : DCD OFF
,03-16 12:39:42.762  1017  1327 E Watchdog: !@Sync 39,
,03-16 12:39:44.582   290   290 E SMD     : DCD OFF,
,03-16 12:39:45.622  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:39:47.412  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:39:47.582   290   290 E SMD     : DCD OFF,
,03-16 12:39:50.592   290   290 E SMD     : DCD OFF
,03-16 12:39:53.592   290   290 E SMD     : DCD OFF
,03-16 12:39:55.672  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:39:56.592   290   290 E SMD     : DCD OFF
,03-16 12:39:57.482  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:39:59.592   290   290 E SMD     : DCD OFF
,03-16 12:40:02.592   290   290 E SMD     : DCD OFF
,03-16 12:40:05.592   290   290 E SMD     : DCD OFF
,03-16 12:40:05.682  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:40:07.542  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:40:08.602   290   290 E SMD     : DCD OFF,
,03-16 12:40:09.802  1017  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 12:40:09.802  1017  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-16 12:40:09.802  1017  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 12:40:10.422  1017  1042 I UsageStatsService: User[0] Flushing usage stats to disk
,03-16 12:40:10.462  1017  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,03-16 12:40:10.462  1017  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1458128410468
,03-16 12:40:10.462  1017  1103 I ApplicationPolicy: updateDataUsageMap
,03-16 12:40:10.632  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 12:40:10.632  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 12:40:10.642  1017  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:40:10.642  1017  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:40:10.782  1017  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-16 12:40:10.782  1017  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-16 12:40:10.812  1017  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458128410817
,03-16 12:40:11.602   290   290 E SMD     : DCD OFF
,03-16 12:40:12.762  1017  1327 E Watchdog: !@Sync 40,
,03-16 12:40:14.602   290   290 E SMD     : DCD OFF,
,03-16 12:40:15.732  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:40:17.602   290   290 E SMD     : DCD OFF
,03-16 12:40:17.612  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:40:20.602   290   290 E SMD     : DCD OFF
,03-16 12:40:23.602   290   290 E SMD     : DCD OFF
,03-16 12:40:25.752  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:40:26.602   290   290 E SMD     : DCD OFF
,03-16 12:40:27.672  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:40:27.892  1017  1050 I PowerManagerService: [PWL] Off : 1156s ago,
,03-16 12:40:29.612   290   290 E SMD     : DCD OFF
,03-16 12:40:32.612   290   290 E SMD     : DCD OFF
,03-16 12:40:35.612   290   290 E SMD     : DCD OFF
,03-16 12:40:35.802  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:40:37.732  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:40:38.612   290   290 E SMD     : DCD OFF
,03-16 12:40:41.612   290   290 E SMD     : DCD OFF
,03-16 12:40:42.762  1017  1327 E Watchdog: !@Sync 41
,03-16 12:40:44.612   290   290 E SMD     : DCD OFF,
,03-16 12:40:45.812  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:40:47.622   290   290 E SMD     : DCD OFF
,03-16 12:40:47.802  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:40:50.622   290   290 E SMD     : DCD OFF
,03-16 12:40:53.622   290   290 E SMD     : DCD OFF,
,03-16 12:40:55.832  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:40:56.622   290   290 E SMD     : DCD OFF,
,03-16 12:40:57.872  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:40:59.622   290   290 E SMD     : DCD OFF,
,03-16 12:41:02.622   290   290 E SMD     : DCD OFF
,03-16 12:41:05.632   290   290 E SMD     : DCD OFF
,03-16 12:41:05.842  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:07.932  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:41:08.632   290   290 E SMD     : DCD OFF
,03-16 12:41:11.632   290   290 E SMD     : DCD OFF
,03-16 12:41:12.762  1017  1327 E Watchdog: !@Sync 42
,03-16 12:41:14.632   290   290 E SMD     : DCD OFF
,03-16 12:41:15.862  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:17.632   290   290 E SMD     : DCD OFF,
,03-16 12:41:17.992  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:41:20.632   290   290 E SMD     : DCD OFF
,03-16 12:41:23.642   290   290 E SMD     : DCD OFF
,03-16 12:41:25.882  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:26.642   290   290 E SMD     : DCD OFF
,03-16 12:41:28.052  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:41:29.642   290   290 E SMD     : DCD OFF
,03-16 12:41:32.642   290   290 E SMD     : DCD OFF
,03-16 12:41:35.642   290   290 E SMD     : DCD OFF,
,03-16 12:41:35.902  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:38.112  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:41:38.642   290   290 E SMD     : DCD OFF
,03-16 12:41:41.642   290   290 E SMD     : DCD OFF
,03-16 12:41:42.762  1017  1327 E Watchdog: !@Sync 43
,03-16 12:41:44.652   290   290 E SMD     : DCD OFF
,03-16 12:41:45.922  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:47.652   290   290 E SMD     : DCD OFF,
,03-16 12:41:48.182  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:41:50.652   290   290 E SMD     : DCD OFF
,03-16 12:41:53.652   290   290 E SMD     : DCD OFF,
,03-16 12:41:55.942  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:41:56.652   290   290 E SMD     : DCD OFF
,03-16 12:41:58.242  1017  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:41:59.652   290   290 E SMD     : DCD OFF
,03-16 12:42:02.662   290   290 E SMD     : DCD OFF
,03-16 12:42:05.662   290   290 E SMD     : DCD OFF,
,03-16 12:42:05.952  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:42:08.302  1017  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:42:08.662   290   290 E SMD     : DCD OFF
,03-16 12:42:11.662   290   290 E SMD     : DCD OFF,
,03-16 12:42:12.772  1017  1327 E Watchdog: !@Sync 44
,03-16 12:42:14.662   290   290 E SMD     : DCD OFF
,03-16 12:42:15.972  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:42:17.662   290   290 E SMD     : DCD OFF,
,03-16 12:42:17.992  1017  1050 I PowerManagerService: [PWL] Off : 1266s ago,
,03-16 12:42:18.372  1017  3835 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:42:20.672   290   290 E SMD     : DCD OFF
,03-16 12:42:23.672   290   290 E SMD     : DCD OFF
,03-16 12:42:25.992  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:42:26.672   290   290 E SMD     : DCD OFF
,03-16 12:42:28.432  1017  1715 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:42:29.672   290   290 E SMD     : DCD OFF
,03-16 12:42:32.672   290   290 E SMD     : DCD OFF
,03-16 12:42:35.672   290   290 E SMD     : DCD OFF
,03-16 12:42:36.042  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:42:38.502  1017  1753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:42:38.672   290   290 E SMD     : DCD OFF
,03-16 12:42:41.682   290   290 E SMD     : DCD OFF,
,03-16 12:42:42.772  1017  1327 E Watchdog: !@Sync 45
,03-16 12:42:44.682   290   290 E SMD     : DCD OFF,
,03-16 12:42:46.092  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:42:47.682   290   290 E SMD     : DCD OFF
,03-16 12:42:48.562  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:42:50.682   290   290 E SMD     : DCD OFF,
,03-16 12:42:53.682   290   290 E SMD     : DCD OFF
,03-16 12:42:56.112  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:42:56.682   290   290 E SMD     : DCD OFF
,03-16 12:42:58.622  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:42:59.692   290   290 E SMD     : DCD OFF
,03-16 12:43:02.692   290   290 E SMD     : DCD OFF,
,03-16 12:43:05.692   290   290 E SMD     : DCD OFF,
,03-16 12:43:06.122  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:08.692  1017  3666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:43:08.692   290   290 E SMD     : DCD OFF
,03-16 12:43:11.692   290   290 E SMD     : DCD OFF,
,03-16 12:43:12.772  1017  1327 E Watchdog: !@Sync 46
,03-16 12:43:14.692   290   290 E SMD     : DCD OFF,
,03-16 12:43:16.142  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:17.702   290   290 E SMD     : DCD OFF
,03-16 12:43:18.752  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:43:20.702   290   290 E SMD     : DCD OFF
,03-16 12:43:23.702   290   290 E SMD     : DCD OFF
,03-16 12:43:26.162  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:26.702   290   290 E SMD     : DCD OFF
,03-16 12:43:28.812  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:43:29.702   290   290 E SMD     : DCD OFF
,03-16 12:43:32.702   290   290 E SMD     : DCD OFF
,03-16 12:43:35.702   290   290 E SMD     : DCD OFF
,03-16 12:43:36.212  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:38.712   290   290 E SMD     : DCD OFF
,03-16 12:43:38.882  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:43:41.712   290   290 E SMD     : DCD OFF
,03-16 12:43:42.772  1017  1327 E Watchdog: !@Sync 47
,03-16 12:43:44.712   290   290 E SMD     : DCD OFF
,03-16 12:43:46.242  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:47.712   290   290 E SMD     : DCD OFF
,03-16 12:43:48.942  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:43:50.712   290   290 E SMD     : DCD OFF,
,03-16 12:43:53.712   290   290 E SMD     : DCD OFF,
,03-16 12:43:56.262  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:43:56.712   290   290 E SMD     : DCD OFF
,03-16 12:43:59.002  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:43:59.722   290   290 E SMD     : DCD OFF
,03-16 12:44:02.722   290   290 E SMD     : DCD OFF
,03-16 12:44:05.722   290   290 E SMD     : DCD OFF
,03-16 12:44:06.272  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:44:08.722   290   290 E SMD     : DCD OFF
,03-16 12:44:09.062  1017  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:11.722   290   290 E SMD     : DCD OFF
,03-16 12:44:12.772  1017  1327 E Watchdog: !@Sync 48
,03-16 12:44:13.092  1017  1050 I PowerManagerService: [PWL] Off : 1381s ago
,03-16 12:44:14.722   290   290 E SMD     : DCD OFF,
,03-16 12:44:16.292  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:44:17.732   290   290 E SMD     : DCD OFF
,03-16 12:44:19.122  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:20.732   290   290 E SMD     : DCD OFF
,03-16 12:44:23.732   290   290 E SMD     : DCD OFF,
,03-16 12:44:26.312  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:44:26.732   290   290 E SMD     : DCD OFF,
,03-16 12:44:29.182  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:29.732   290   290 E SMD     : DCD OFF
,03-16 12:44:32.732   290   290 E SMD     : DCD OFF
,03-16 12:44:35.742   290   290 E SMD     : DCD OFF
,03-16 12:44:36.322  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:44:38.742   290   290 E SMD     : DCD OFF
,03-16 12:44:39.252  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:41.742   290   290 E SMD     : DCD OFF
,03-16 12:44:42.772  1017  1327 E Watchdog: !@Sync 49
,03-16 12:44:44.742   290   290 E SMD     : DCD OFF
,03-16 12:44:46.372  1017  2769 D SSRM:n  : SIOP:: AP = 260,
,03-16 12:44:47.742   290   290 E SMD     : DCD OFF
,03-16 12:44:49.302  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:50.742   290   290 E SMD     : DCD OFF
,03-16 12:44:53.742   290   290 E SMD     : DCD OFF
,03-16 12:44:56.392  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:44:56.752   290   290 E SMD     : DCD OFF
,03-16 12:44:59.372  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:44:59.752   290   290 E SMD     : DCD OFF
,03-16 12:45:02.752   290   290 E SMD     : DCD OFF
,03-16 12:45:05.752   290   290 E SMD     : DCD OFF
,03-16 12:45:06.402  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:08.752   290   290 E SMD     : DCD OFF,
,03-16 12:45:09.432  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:45:09.802  1017  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 12:45:09.802  1017  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-16 12:45:09.802  1017  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 12:45:11.752  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 12:45:11.752  1017  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 12:45:11.752   290   290 E SMD     : DCD OFF,
03-16 12:45:11.762  1017  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:45:11.762  1017  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 12:45:12.772  1017  1327 E Watchdog: !@Sync 50
,03-16 12:45:14.762   290   290 E SMD     : DCD OFF
,03-16 12:45:16.462  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:17.762   290   290 E SMD     : DCD OFF
,03-16 12:45:19.492  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:45:20.762   290   290 E SMD     : DCD OFF
,03-16 12:45:23.762   290   290 E SMD     : DCD OFF
,03-16 12:45:26.472  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:26.762   290   290 E SMD     : DCD OFF
,03-16 12:45:29.552  1017  1571 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:45:29.762   290   290 E SMD     : DCD OFF,
,03-16 12:45:32.762   290   290 E SMD     : DCD OFF
,03-16 12:45:35.772   290   290 E SMD     : DCD OFF
,03-16 12:45:36.492  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:38.772   290   290 E SMD     : DCD OFF
,03-16 12:45:39.612  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:45:39.612  1017  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:45:39.612  1017  1472 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:45:39.612  1017  1472 D BatteryService: stay LED for fully charged
03-16 12:45:39.612  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:45:39.612  1017  1017 I MotionRecognitionService: Plugged
,03-16 12:45:39.612  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:45:39.612  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 12:45:39.612  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:45:39.612  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 12:45:39.622  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-16 12:45:39.622  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:45:39.622  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:45:39.642  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:45:39.642  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:45:39.642  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:45:39.642  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 12:45:39.642  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:45:41.772   290   290 E SMD     : DCD OFF
,03-16 12:45:42.772  1017  1327 E Watchdog: !@Sync 51,
,03-16 12:45:44.772   290   290 E SMD     : DCD OFF,
,03-16 12:45:46.542  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:47.772   290   290 E SMD     : DCD OFF
,03-16 12:45:49.672  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:45:49.672  1017  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:45:49.672  1017  3836 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:45:49.672  1017  3836 D BatteryService: stay LED for fully charged
03-16 12:45:49.672  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:45:49.672  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:45:49.672  1017  1017 I MotionRecognitionService: Plugged
03-16 12:45:49.672  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:45:49.672  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:45:49.682  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 12:45:49.682  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:45:49.692  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 12:45:49.692  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:45:49.702  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:45:49.702  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:45:49.702  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:45:49.702  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:45:49.702  1176  1176 D SViewCoverView: level :100 plugged : 2
,03-16 12:45:50.772   290   290 E SMD     : DCD OFF
,03-16 12:45:53.782   290   290 E SMD     : DCD OFF
,03-16 12:45:56.562  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:45:56.782   290   290 E SMD     : DCD OFF
,03-16 12:45:59.742  1017  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:45:59.782   290   290 E SMD     : DCD OFF,
,03-16 12:46:02.782   290   290 E SMD     : DCD OFF
,03-16 12:46:05.782   290   290 E SMD     : DCD OFF
,03-16 12:46:06.612  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:08.782   290   290 E SMD     : DCD OFF
,03-16 12:46:09.802  1017  3983 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:46:11.792   290   290 E SMD     : DCD OFF
,03-16 12:46:12.782  1017  1327 E Watchdog: !@Sync 52,
,03-16 12:46:13.112  1017  1050 I PowerManagerService: [PWL] Off : 1501s ago,
,03-16 12:46:14.792   290   290 E SMD     : DCD OFF
,03-16 12:46:16.632  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:17.792   290   290 E SMD     : DCD OFF,
,03-16 12:46:19.862  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:46:20.792   290   290 E SMD     : DCD OFF,
,03-16 12:46:23.792   290   290 E SMD     : DCD OFF,
,03-16 12:46:26.642  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:26.792   290   290 E SMD     : DCD OFF
,03-16 12:46:29.792   290   290 E SMD     : DCD OFF
,03-16 12:46:29.922  1017  1575 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:46:32.802   290   290 E SMD     : DCD OFF,
,03-16 12:46:35.802   290   290 E SMD     : DCD OFF
,03-16 12:46:36.662  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:38.802   290   290 E SMD     : DCD OFF,
,03-16 12:46:39.982  1017  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 12:46:41.802   290   290 E SMD     : DCD OFF
,03-16 12:46:42.782  1017  1327 E Watchdog: !@Sync 53,
,03-16 12:46:44.802   290   290 E SMD     : DCD OFF
,03-16 12:46:46.682  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:47.802   290   290 E SMD     : DCD OFF,
,03-16 12:46:50.042  1017  1745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:46:50.812   290   290 E SMD     : DCD OFF
,03-16 12:46:53.812   290   290 E SMD     : DCD OFF
,03-16 12:46:56.702  1017  2769 D SSRM:n  : SIOP:: AP = 260
,03-16 12:46:56.812   290   290 E SMD     : DCD OFF
,03-16 12:46:59.812   290   290 E SMD     : DCD OFF
,03-16 12:47:00.102  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:47:02.812   290   290 E SMD     : DCD OFF,
,TIME-OUT KILL (timeout was 1400000ms),03-16 12:47:04.402  6720  6720 D AndroidRuntime: 
03-16 12:47:04.402  6720  6720 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 12:47:04.402  6720  6720 D AndroidRuntime: CheckJNI is OFF
03-16 12:47:04.402  6720  6720 D AndroidRuntime: readGMSProperty: start
03-16 12:47:04.402  6720  6720 D AndroidRuntime: readGMSProperty: already setted!!
03-16 12:47:04.402  6720  6720 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 12:47:04.402  6720  6720 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 12:47:04.402  6720  6720 D AndroidRuntime: readGMSProperty: end
03-16 12:47:04.402  6720  6720 D AndroidRuntime: addProductProperty: start
03-16 12:47:04.612  6720  6720 E AffinityControl: AffinityControl: registerfunction enter
03-16 12:47:04.632  6720  6720 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-16 12:47:04.652  1017  3836 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-16 12:47:04.652  1017  3836 D PackageManager: START PACKAGE DELETE: observer{818404091}
03-16 12:47:04.652  1017  3836 D PackageManager: pkg{<packageName>}
03-16 12:47:04.652  1017  3836 D PackageManager: user{0}
03-16 12:47:04.652  1017  3836 D PackageManager: caller{2000}
03-16 12:47:04.652  1017  3836 D PackageManager: flags{2}
03-16 12:47:04.652  1017  3836 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-16 12:47:04.652  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 12:47:04.652  1017  3836 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 12:47:04.652  1017  3836 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 12:47:04.652  1017  3836 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 12:47:04.652  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 12:47:04.652  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-16 12:47:04.652  1017  1056 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-16 12:47:04.652  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
03-16 12:47:04.652  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-16 12:47:04.672  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-16 12:47:04.672  1017  1043 I ActivityManager: Killing 6061:com.test.thalitest/u0a167 (adj 15): stop com.test.thalitest cause uninstall pkg
03-16 12:47:04.732  1017  1056 W PackageSettings: Skipping PackageSetting{280979a5 com.example.hello/10346} due to missing metadata
03-16 12:47:04.762  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
03-16 12:47:04.792  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-16 12:47:04.832  4028  4028 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 795us total 36.952ms
03-16 12:47:04.842  5221  5221 I art     : Explicit concurrent mark sweep GC freed 11582(830KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 828us total 52.477ms
03-16 12:47:04.852  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-16 12:47:04.862  1806  2070 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-16 12:47:04.872  1841  1841 E SamsungIME: mOCRHelper is null
03-16 12:47:04.902  3611  3611 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 12:47:04 GMT+01:00 2016
03-16 12:47:04.912  1017  3983 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:04.912  1017  3983 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:04.912  1017  3983 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-16 12:47:04.922  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-16 12:47:04.922  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 12:47:04.922  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
03-16 12:47:04.922  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
03-16 12:47:04.922  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
03-16 12:47:04.942  1017  1124 V NetworkStats: performPollLocked() took 19ms
03-16 12:47:04.942  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 12:47:04.942  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 12:47:04.942  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 12:47:04.952  3611  3611 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-16 12:47:04.952  1017  1753 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-16 12:47:04.952  1017  1753 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-16 12:47:04.952  1017  1753 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-16 12:47:04.952  1017  1753 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
03-16 12:47:04.952  1017  1753 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:04.952  1017  1753 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:04.952  1017  1753 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:04.952  1017  1753 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:04.972  6733  6733 E Zygote  : MountEmulatedStorage()
03-16 12:47:04.972  6733  6733 E Zygote  : v2
03-16 12:47:04.972  6733  6733 I libpersona: KNOX_SDCARD checking this for 10090
03-16 12:47:04.972  6733  6733 I libpersona: KNOX_SDCARD not a persona
03-16 12:47:04.972  3611  3611 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-16 12:47:04.972  6733  6733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:47:04.972  3611  3611 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-16 12:47:04.972  6733  6733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:47:04.972  6733  6733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:47:04.982  1017  1753 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6733 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-16 12:47:04.992  3611  3611 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-16 12:47:04.992  1017  3836 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 12:47:04.992  1017  3836 D SecContentProvider2: mCursor = null
03-16 12:47:05.002  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-16 12:47:05.002  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
03-16 12:47:05.022  1017  1017 I art     : Explicit concurrent mark sweep GC freed 45585(5MB) AllocSpace objects, 226(3MB) LOS objects, 33% free, 23MB/35MB, paused 3.008ms total 225.779ms
03-16 12:47:05.022  1017  1056 I art     : WaitForGcToComplete blocked for 130.295ms for cause Explicit
03-16 12:47:05.022  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
03-16 12:47:05.032  6733  6733 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:47:05.032  6733  6733 D ActivityThread: Added TimaKeyStore provider
03-16 12:47:05.042  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
03-16 12:47:05.062  1442  1442 D RegisteredServicesCache: empty dynamic service
03-16 12:47:05.082  1017  1017 D RCPManagerService: PackageReceiver onReceive()
03-16 12:47:05.082  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-16 12:47:05.082  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.092  6733  6733 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-16 12:47:05.092  6733  6733 D elm:15121: ELMEngine.ELMEngine( context ).
03-16 12:47:05.092  6733  6733 D elm:15121: MDMBridge.setEnterpriseBridge()
03-16 12:47:05.092  1017  1745 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.092  1017  1745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.092  1017  1745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-16 12:47:05.102  6733  6733 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-16 12:47:05.112  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
03-16 12:47:05.112  6733  6733 D elm:15121: ElmAgentService : onCreate()
03-16 12:47:05.112  6733  6748 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-16 12:47:05.112  6733  6748 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-16 12:47:05.112  6733  6748 D elm:15121: MDMBridge.getInstance()
03-16 12:47:05.112  6733  6748 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-16 12:47:05.112  6733  6748 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-16 12:47:05.122  3611  6732 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-16 12:47:05.132  3611  6732 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
03-16 12:47:05.132  3611  3611 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
03-16 12:47:05.142  6733  6733 D elm:15121: ElmAgentService : onDestroy().
03-16 12:47:05.152  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 12:47:05.152  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 12:47:05.162  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 12:47:05.162  1017  1160 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 12:47:05.162  1017  2769 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-16 12:47:05.162  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 12:47:05.212  5638  5638 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 12:47:05.212  5638  5638 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 12:47:05.212  5638  5638 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 12:47:05.212  5638  5638 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.222  5709  5709 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-16 12:47:05.232  5709  5709 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
03-16 12:47:05.242  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.242  1017  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.242  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
03-16 12:47:05.252  1017  1056 I art     : Explicit concurrent mark sweep GC freed 11988(653KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.146ms total 220.053ms
03-16 12:47:05.262  4969  4969 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
03-16 12:47:05.302  5590  5590 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.302  1017  3666 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.302  1017  3666 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.302  1017  3666 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-16 12:47:05.302  1017  1056 D PackageManager: delete codoeFile: 
03-16 12:47:05.312  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-16 12:47:05.312  1017  1056 I AASA_removePackage: UID=10167 Target=com.test.thalitest
03-16 12:47:05.312  1017  1056 D PackageManager: result of delete: 1{818404091}
03-16 12:47:05.312  1017  1571 I TactileAssist: enable value -1
03-16 12:47:05.312  1017  1571 I TactileAssist: internal enable value -1
03-16 12:47:05.312  1017  1571 I TactileAssist: intensity value -1
03-16 12:47:05.312  1017  1571 I TactileAssist: saveAppList value true
03-16 12:47:05.312  5590  6751 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-16 12:47:05.312  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-16 12:47:05.312  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-16 12:47:05.312  5590  6751 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-16 12:47:05.322  1017  1571 I TactileAssist: List of disabled apps :
03-16 12:47:05.322  1017  1042 W TextServicesManagerService: no available spell checker services found
03-16 12:47:05.322  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.332  6720  6720 D AndroidRuntime: Shutting down VM
03-16 12:47:05.332  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.332  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 12:47:05.332  1017  1056 D PackageManager: userId{-1}
03-16 12:47:05.332  1017  1056 D PackageManager: andCode{true}
03-16 12:47:05.342  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.342  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.352  5810  5810 D Compatibility: onReceive() it will make start service
03-16 12:47:05.352  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.352  1017  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.352  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
03-16 12:47:05.362  5810  6753 D Compatibility: onHandleIntent()
03-16 12:47:05.362  5810  6753 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-16 12:47:05.362  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.362  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.362  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.362  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.362  5810  6753 D Compatibility: found: 2
03-16 12:47:05.362  5810  6753 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 12:47:05.362  5810  6753 D Compatibility: skipping ResolveInfo{204e28c5 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-16 12:47:05.362  5810  6753 D Compatibility: considering ResolveInfo{1f11921a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-16 12:47:05.362  5810  6753 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 12:47:05.362  5810  6753 D Compatibility: enabling receiver ResolveInfo{2f1b514b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-16 12:47:05.372  6754  6754 E Zygote  : MountEmulatedStorage()
03-16 12:47:05.372  6754  6754 I libpersona: KNOX_SDCARD checking this for 10055
03-16 12:47:05.372  6754  6754 E Zygote  : v2
03-16 12:47:05.372  6754  6754 I libpersona: KNOX_SDCARD not a persona
03-16 12:47:05.372  5810  6753 D Compatibility: enabling receiver ResolveInfo{c68a728 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 12:47:05.372  1017  1472 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6754 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-16 12:47:05.372  6754  6754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:47:05.372  6754  6754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:47:05.382  6754  6754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:47:05.382  5810  6753 D Compatibility: enabling receiver ResolveInfo{1c6d8c41 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-16 12:47:05.382  5810  6753 D Compatibility: enabling receiver ResolveInfo{36a6b5e6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 12:47:05.392  5810  6753 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
03-16 12:47:05.392  1017  3666 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.392  1017  3666 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.392  1017  3666 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
03-16 12:47:05.402  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:47:05.402  6754  6754 D ActivityThread: Added TimaKeyStore provider
03-16 12:47:05.432  6754  6754 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-16 12:47:05.442  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-16 12:47:05.442  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.442  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.442  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.442  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:47:05.442  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:47:05.442  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:47:05.452  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.462  6754  6754 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-16 12:47:05.462  6754  6754 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 12:47:05.462  6754  6754 D UserAnalysis: Create SecureDbHelper
03-16 12:47:05.462  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.462  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.472  6754  6754 D IntelligenceServiceApplication: onCreate()
03-16 12:47:05.472  6754  6754 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
03-16 12:47:05.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 12:47:05.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 12:47:05.482  6754  6754 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 12:47:05.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 12:47:05.482  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 12:47:05.482  5828  5828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-16 12:47:05.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 12:47:05.482  1017  3983 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.482  1017  3983 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.482  1017  3983 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-16 12:47:05.492  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 12:47:05.492  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-16 12:47:05.492  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-16 12:47:05.492  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.492  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.492  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.492  1017  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.512  6771  6771 E Zygote  : MountEmulatedStorage()
03-16 12:47:05.512  6771  6771 E Zygote  : v2
03-16 12:47:05.512  6771  6771 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:47:05.512  6771  6771 I libpersona: KNOX_SDCARD not a persona
03-16 12:47:05.512  6771  6771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:47:05.512  1017  1472 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6771 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:47:05.512  6771  6771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:47:05.512  6771  6771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:47:05.522  1017  1571 I ActivityManager: Killing 5163:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
03-16 12:47:05.532  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
03-16 12:47:05.532  6771  6771 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:47:05.532  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
03-16 12:47:05.532  6771  6771 D ActivityThread: Added TimaKeyStore provider
03-16 12:47:05.542  6720  6720 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 12:47:05.542  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-16 12:47:05.552  6771  6771 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
03-16 12:47:05.552  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
03-16 12:47:05.562  6754  6754 D BluetoothAdapter: cancelDiscovery
03-16 12:47:05.562  2656  2666 D BluetoothAdapterProperties: mDiscovering is false
03-16 12:47:05.562  2656  2666 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
03-16 12:47:05.562  6754  6754 D BluetoothAdapter: cancelDiscovery = true
03-16 12:47:05.562  6754  6754 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
03-16 12:47:05.562  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 12:47:05.562  6754  6754 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 12:47:05.572  6771  6771 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-16 12:47:05.582  1017  1745 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-16 12:47:05.582  1017  1745 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-16 12:47:05.592  5847  5847 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
03-16 12:47:05.592  5847  5847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
03-16 12:47:05.592  1017  3836 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:47:05.592  1017  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:47:05.592  1017  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
03-16 12:47:05.602  5847  5847 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
03-16 12:47:05.612  5847  6787 I FilterInstaller: FilterPackageService : ACTION_REMOVED
03-16 12:47:05.612  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.612  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.612  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.612  1017  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.612  5847  6787 D FilterUnInstaller: before removeFromFS
03-16 12:47:05.632  6788  6788 E Zygote  : MountEmulatedStorage()
03-16 12:47:05.632  6788  6788 E Zygote  : v2
03-16 12:47:05.632  6788  6788 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:47:05.632  6788  6788 I libpersona: KNOX_SDCARD not a persona
03-16 12:47:05.632  6788  6788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:47:05.632  6788  6788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:47:05.632  1017  3983 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:47:05.632  6788  6788 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:47:05.642  1017  1042 W libprocessgroup: failed to open /acct/uid_10032/pid_5163/cgroup.procs: No such file or directory
03-16 12:47:05.642  1017  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.642  1017  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.642  1017  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.642  1017  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:47:05.662   305   305 I art     : Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 24.397ms
03-16 12:47:05.662  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:47:05.662  6788  6788 D ActivityThread: Added TimaKeyStore provider
03-16 12:47:05.662  6754  6754 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-16 12:47:05.662  6754  6754 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: Error inserting timestamp=1458128825487 message=Predictor: service is stopped by Application.onCreate
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 12:47:05.672  6754  6754 E UserAnalysis: It failed to insert to dump_log table
03-16 12:47:05.672  6754  6754 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-16 12:47:05.672  6754  6754 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: Error inserting timestamp=1458128825571 message=Predictor: service stopped by removePlaceCategories()
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 12:47:05.672  6754  6754 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 12:47:05.672  6754  6754 E UserAnalysis: It failed to insert to dump_log table

```
