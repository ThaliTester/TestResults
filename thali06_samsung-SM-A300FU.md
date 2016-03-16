#### Test 62509094c3ee53f_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
03-16 10:41:28.812  1022  2724 D SSRM:n  : SIOP:: AP = 260
,--------- beginning of main
03-16 10:41:29.152  6242  6242 D AndroidRuntime: 
03-16 10:41:29.152  6242  6242 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 10:41:29.162  6242  6242 D AndroidRuntime: CheckJNI is OFF
03-16 10:41:29.162  6242  6242 D AndroidRuntime: readGMSProperty: start
03-16 10:41:29.162  6242  6242 D AndroidRuntime: readGMSProperty: already setted!!
03-16 10:41:29.162  6242  6242 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 10:41:29.162  6242  6242 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 10:41:29.162  6242  6242 D AndroidRuntime: readGMSProperty: end
03-16 10:41:29.162  6242  6242 D AndroidRuntime: addProductProperty: start
03-16 10:41:29.192  1022  1035 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 10:41:29.192  1022  1035 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 10:41:29.192  1022  1035 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 10:41:29.192  1022  1035 D BatteryService: stay LED for fully charged
03-16 10:41:29.192  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 10:41:29.202  1022  1022 I MotionRecognitionService: Plugged
03-16 10:41:29.202  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 10:41:29.202  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 10:41:29.202  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 10:41:29.202  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 10:41:29.202  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
03-16 10:41:29.212  2629  2629 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 10:41:29.212  2629  2720 D HeadsetStateMachine: Disconnected process message: 10
03-16 10:41:29.222  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 10:41:29.222  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 10:41:29.222  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 10:41:29.222  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 10:41:29.222  1178  1178 D SViewCoverView: level :100 plugged : 2
03-16 10:41:29.302  6242  6242 E AffinityControl: AffinityControl: registerfunction enter
03-16 10:41:29.322  6242  6242 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 10:41:29.332  1022  1544 E PersonaManagerService: inState():  stateMachine is null !!
03-16 10:41:29.332  1022  1544 I PersonaManagerService: PersonaId don't exist
03-16 10:41:29.332  1022  1544 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 10:41:29.342  1022  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 10:41:29.352  1022  1544 W ActivityManager: mDVFSHelper.acquire()
03-16 10:41:29.352  1022  1544 D FocusedStackFrame: Set to : 0
03-16 10:41:29.362  1022  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:29.362  1022  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:29.362  1022  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:29.362  1022  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:29.372  1022  1053 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 10:41:29.372  1022  1053 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 10:41:29.372  6254  6254 E Zygote  : MountEmulatedStorage()
03-16 10:41:29.372  6254  6254 E Zygote  : v2
03-16 10:41:29.372  6254  6254 I libpersona: KNOX_SDCARD checking this for 10167
03-16 10:41:29.372  6254  6254 I libpersona: KNOX_SDCARD not a persona
03-16 10:41:29.372  6254  6254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 10:41:29.372  1022  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 10:41:29.372  1022  1544 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6254 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 10:41:29.372  1022  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 10:41:29.372  1022  1544 D InputDispatcher: Focused application set to: xxxx
03-16 10:41:29.372  1022  1544 D InputDispatcher: Focus left window: 1483
03-16 10:41:29.382  6242  6242 D AndroidRuntime: Shutting down VM
03-16 10:41:29.382  6254  6254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 10:41:29.382  6254  6254 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 10:41:29.382  1022  1053 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 10:41:29.382  1022  1053 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 10:41:29.382   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-16 10:41:29.402   325   325 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 25.190ms
03-16 10:41:29.402  6254  6254 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 10:41:29.402  6254  6254 D ActivityThread: Added TimaKeyStore provider
03-16 10:41:29.412  1022  3360 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 10:41:29.412  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 10:41:29.412  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 10:41:29.412  1022  1022 V ActivityManager: Display changed displayId=0
03-16 10:41:29.422  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 10:41:29.422   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 18.227ms
03-16 10:41:29.432  1022  3360 D PersonaManager: isKioskContainerExistOnDevice
03-16 10:41:29.442   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 630us total 16.765ms
03-16 10:41:29.452  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 10:41:29.472   259   455 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-16 10:41:29.472   259  1020 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-16 10:41:29.472  1483  1483 D Launcher: onTrimMemory. Level: 20
03-16 10:41:29.472  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{3774a2fc token=android.os.BinderProxy@340c4dba {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 10:41:29.542  6254  6254 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-16 10:41:29.562  6254  6254 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7171-7173)
03-16 10:41:29.562  6254  6254 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 10:41:29.582  6254  6254 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37777822}
03-16 10:41:29.582  6254  6254 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 10:41:29.582  6254  6254 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 10:41:29.592  6242  6242 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 10:41:29.602   303   303 E SMD     : DCD OFF
03-16 10:41:29.612  6254  6254 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 10:41:29.612  6254  6254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:41:29.612  6254  6254 E SysUtils: ApplicationContext is null in ApplicationStatus
03-16 10:41:29.632  6254  6254 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-16 10:41:29.632  6254  6254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 10:41:29.642  6254  6254 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 10:41:29.642  6254  6254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 10:41:29.642  6254  6254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 10:41:29.642  6254  6254 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 10:41:29.642  6254  6254 I Adreno-EGL: Local Branch: 
03-16 10:41:29.642  6254  6254 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 10:41:29.642  6254  6254 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 10:41:29.642  6254  6254 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 10:41:29.852  6254  6254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:41:29.862  6254  6254 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-16 10:41:29.872  6254  6254 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 10:41:29.872  6254  6254 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-16 10:41:29.872  6254  6254 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-16 10:41:29.882  6254  6254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:41:29.882  6254  6254 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 10:41:29.942  1022  1048 W ActivityManager: Activity pause timeout for ActivityRecord{2eff0fd1 u0 com.test.thalitest/.MainActivity t23}
03-16 10:41:29.962  6254  6295 D OpenGLRenderer: Render dirty regions requested: true
03-16 10:41:29.962  1022  3359 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 10:41:29.962  1022  3359 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 10:41:29.972  1022  3359 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 10:41:29.972  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 10:41:29.972  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 10:41:30.002  6254  6282 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-16 10:41:30.002  6254  6254 V ActivityThread: updateVisibility : ActivityRecord{c69a52a token=android.os.BinderProxy@14980bcc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-16 10:41:30.002  6254  6254 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 10:41:30.002  6254  6254 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 10:41:30.022   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
03-16 10:41:30.032  1022  1217 D InputDispatcher: Focus entered window: 6254
03-16 10:41:30.042  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 10:41:30.042  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 10:41:30.042  6254  6254 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 10:41:30.042  6254  6295 I OpenGLRenderer: Initialized EGL, version 1.4
03-16 10:41:30.042  6254  6295 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 10:41:30.052  6254  6295 D OpenGLRenderer: Enabling debug mode 0
03-16 10:41:30.072  1022  1369 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 10:41:30.072  1178  1178 I StatusBar: Icon Only
03-16 10:41:30.072  1178  1178 D PanelView: There is/are notification(s) 
03-16 10:41:30.082  1022  1053 I ActivityManager: Displayed Component not be shown by security: +649ms (total +1m42s180ms)
03-16 10:41:30.092  1022  1053 W ActivityManager: mDVFSHelper.release()
03-16 10:41:30.092  1022  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2eff0fd1 u0 com.test.thalitest/.MainActivity t23} time:217700
03-16 10:41:30.092  1022  6297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 10:41:30.092  6254  6254 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 10:41:30.092  6254  6254 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14980bcc time:217705
03-16 10:41:30.092   259  1020 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
03-16 10:41:30.092   259   452 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
03-16 10:41:30.102  1877  1877 I SamsungIME: getCurrentCandidateView
03-16 10:41:30.162  1877  1877 D SamsungIME: Dismiss ExpandCandiate
03-16 10:41:30.192  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 10:41:30.252  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 10:41:30.262  6254  6254 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6254
03-16 10:41:30.262  1877  1877 I SamsungIME: KeybaordView init() : load resources
03-16 10:41:30.292  1877  1877 I SamsungIME: getCurrentKeyboard
03-16 10:41:30.292  1877  1877 I SamsungIME: getTextKeyboard
03-16 10:41:30.312  1877  1877 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
03-16 10:41:30.392  6254  6254 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 10:41:30.592  6254  6298 D jxcore_app_log: JniHelper::setJavaVM(0xb7e2a448), pthread_self() = -1204232416
,03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-16 10:41:30.602  6254  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12d9350b added. We now have 1 listener(s)
,03-16 10:41:30.602  6254  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-16 10:41:30.602  6254  6298 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 10:41:30.612  6254  6298 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 10:41:30.612  6254  6298 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-16 10:41:30.612  6254  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23e9bca6 added. We now have 1 listener(s)
,03-16 10:41:30.612  6254  6298 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 10:41:30.622  6254  6298 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
,03-16 10:41:30.622  6254  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 10:41:30.622  6254  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 10:41:30.622  6254  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 10:41:30.622  6254  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2,
,03-16 10:41:30.622  6254  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 10:41:30.632  6254  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 10:41:30.632  6254  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 10:41:30.632  6254  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 10:41:30.632  6254  6298 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 10:41:30.632  6254  6254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 10:41:30.642  6254  6254 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 10:41:30.662  6254  6254 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 10:41:31.132  6254  6305 W jxcore-log: Initializing JXcore engine
03-16 10:41:31.132  6254  6305 W jxcore-log: JXcore engine is ready
,03-16 10:41:31.192  1871  1871 E audit   : type=1400 msg=audit(1458121291.192:205): avc:  denied  { ioctl } for  pid=6305 comm="Thread-1074" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-16 10:41:31.192  1871  1871 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 10:41:31.192  1871  1871 E audit   : type=1300 msg=audit(1458121291.192:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9ee428b8 items=0 ppid=325 ppcomm=main pid=6305 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1074" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 10:41:31.192  1871  1871 E audit   : type=1320 msg=audit(1458121291.192:205): 
,03-16 10:41:31.202  6254  6305 W jxcore-log: Starting JXcore engine
,03-16 10:41:31.302  6254  6305 W jxcore-log: Platform android
03-16 10:41:31.302  6254  6305 W jxcore-log: 
,03-16 10:41:31.302  6254  6305 W jxcore-log: Process ARCH arm
03-16 10:41:31.302  6254  6305 W jxcore-log: 
,03-16 10:41:31.512  6254  6305 I jxcore-log: JXcore Cordova bridge is ready!
03-16 10:41:31.512  6254  6305 I jxcore-log: 
,03-16 10:41:31.512  6254  6305 W jxcore-log: JXcore engine is started
,03-16 10:41:31.522  6254  6298 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 10:41:31.522  6254  6254 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 10:41:31.532  6254  6305 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 10:41:31.532  6254  6305 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 10:41:31.532  6254  6254 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 10:41:31.542  6254  6254 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 10:41:31.542  1022  1217 D FocusedStackFrame: Set to : 0
03-16 10:41:31.542  1022  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 10:41:31.542  1022  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 10:41:31.542  1022  1217 D InputDispatcher: Focused application set to: xxxx
03-16 10:41:31.542  1022  1217 D InputDispatcher: Focus left window: 6254
03-16 10:41:31.542  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 10:41:31.542  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 10:41:31.552  1022  1217 I ActivityManager: Killing 4225:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-16 10:41:31.572   259   452 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,03-16 10:41:31.572   259   455 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-16 10:41:31.582  1022  1544 W ActivityManager: mDVFSHelper.acquire()
,03-16 10:41:31.592  1022  1544 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 10:41:31.602  6254  6254 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@106416e7 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:41:31.602  6254  6254 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@106416e7 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 10:41:31.602  6254  6254 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@17425294 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:41:31.602  6254  6254 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@17425294 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:31.602  6254  6254 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 10:41:31.612  1483  1483 D Launcher: onRestart, Launcher: 55513065
,03-16 10:41:31.612  1483  1483 D Launcher: onStart, Launcher: 55513065
03-16 10:41:31.612  1483  1483 D Launcher.HomeView: onStart
,03-16 10:41:31.612  1483  1483 D Launcher: onResume, Launcher: 55513065
,03-16 10:41:31.612  1022  1472 D SettingsProvider: name = kids_home_mode
03-16 10:41:31.612  1022  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 10:41:31.612  1022  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 10:41:31.612  1022  1472 D SettingsProvider: selectionArgs: false
03-16 10:41:31.612  1022  1472 D SettingsProvider: selectionArgs: 10006
03-16 10:41:31.612  1022  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 10:41:31.612  1022  1472 D SettingsProvider: ret = -1
,03-16 10:41:31.612  1483  1483 D Launcher.HomeView: onResume
,03-16 10:41:31.622  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 10:41:31.622  1483  1483 D MenuAppsGridFragment: onResume
,03-16 10:41:31.622  1022  1048 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.622  1022  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.622  1022  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-16 10:41:31.622  1022  3358 D ActivityManager: handle home activity for 0
,03-16 10:41:31.622  1022  3358 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 10:41:31.622  1022  3358 D KnoxTimeoutHandler: post home show event for user 0
03-16 10:41:31.622  1022  3358 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 10:41:31.622  1022  3358 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 10:41:31.622  1022  3358 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-16 10:41:31.622  1022  1022 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 10:41:31.632  1022  1022 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 10:41:31.632  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 10:41:31.632  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 10:41:31.632  1483  1483 D Launcher.HomeView: onPause
,03-16 10:41:31.632  1022  1547 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-16 10:41:31.632  1022  1547 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
03-16 10:41:31.632  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 10:41:31.632  1022  1547 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:31.632  1022  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 10:41:31.632  1022  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-16 10:41:31.642  1022  1048 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:31.642  1022  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.642  1022  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-16 10:41:31.642  5042  5042 D GalleryCacheReady: Receive : home resume
,03-16 10:41:31.642  1022  1048 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.642  1022  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.642  1022  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-16 10:41:31.652  2537  2537 D Recents_RecreateReceiver: onReceive by home
03-16 10:41:31.652  1022  1048 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:31.652  1022  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.652  1022  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 10:41:31.662  6082  6082 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-16 10:41:31.662   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,03-16 10:41:31.662  1022  1547 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.662  1022  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.662  1022  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-16 10:41:31.662  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 10:41:31.662  5705  5705 D Mms/UIEventReceiver: ui event
03-16 10:41:31.662  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 10:41:31.662  1022  1547 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.662  1022  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.662  1022  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-16 10:41:31.672  1022  1484 D InputDispatcher: Focus entered window: 1483
03-16 10:41:31.672  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 10:41:31.672  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 10:41:31.672  1483  1483 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 10:41:31.672  1022  1547 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.672  1022  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.672  1022  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
03-16 10:41:31.672  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{3774a2fc token=android.os.BinderProxy@340c4dba {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 10:41:31.672  1483  1483 D Launcher.HomeView: onStop
,03-16 10:41:31.682  1022  1469 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 10:41:31.682  1022  6310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 10:41:31.682  6254  6254 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 10:41:31.682  1877  1877 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-16 10:41:31.692  1022  1547 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:31.692  1022  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.692  1022  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 10:41:31.692  1022  1547 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1483, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,03-16 10:41:31.692  1022  1035 D PersonaManager: isKioskContainerExistOnDevice
,03-16 10:41:31.692  1178  1178 I StatusBar: Icon Only
03-16 10:41:31.692  1178  1178 D PanelView: There is/are notification(s) 
,03-16 10:41:31.702  1022  1547 I splitIntent: Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,03-16 10:41:31.712  1022  1048 W ActivityManager: userId = 0, bbcId = -10000,
03-16 10:41:31.712  1022  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:31.712  1022  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 10:41:31.712  6082  6082 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-16 10:41:31.722  1483  1483 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@340c4dba time:219331
,03-16 10:41:31.742  1022  1053 W ActivityManager: mDVFSHelper.release()
,03-16 10:41:31.742  1022  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3119387a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:219355
,03-16 10:41:31.772  1022  1047 W libprocessgroup: failed to open /acct/uid_10032/pid_4225/cgroup.procs: No such file or directory
,03-16 10:41:31.832  6307  6307 D AndroidRuntime: 
03-16 10:41:31.832  6307  6307 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 10:41:31.842  6307  6307 D AndroidRuntime: CheckJNI is OFF
,03-16 10:41:31.842  6307  6307 D AndroidRuntime: readGMSProperty: start
03-16 10:41:31.842  6307  6307 D AndroidRuntime: readGMSProperty: already setted!!
03-16 10:41:31.842  6307  6307 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 10:41:31.842  6307  6307 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 10:41:31.842  6307  6307 D AndroidRuntime: readGMSProperty: end
03-16 10:41:31.842  6307  6307 D AndroidRuntime: addProductProperty: start
,03-16 10:41:31.862  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 10:41:31.972  6307  6307 E AffinityControl: AffinityControl: registerfunction enter,
,03-16 10:41:31.992  6307  6307 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,03-16 10:41:32.012  1022  1472 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-16 10:41:32.012  1022  1472 D PackageManager: START PACKAGE DELETE: observer{47431845},
03-16 10:41:32.012  1022  1472 D PackageManager: pkg{<packageName>}
03-16 10:41:32.012  1022  1472 D PackageManager: user{0}
03-16 10:41:32.012  1022  1472 D PackageManager: caller{2000}
03-16 10:41:32.012  1022  1472 D PackageManager: flags{2}
03-16 10:41:32.012  1022  1472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-16 10:41:32.012  1022  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 10:41:32.012  1022  1472 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 10:41:32.012  1022  1472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 10:41:32.012  1022  1472 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 10:41:32.012  1022  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 10:41:32.012  1022  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
03-16 10:41:32.012  1022  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
03-16 10:41:32.012  1022  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-16 10:41:32.012  1022  1061 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-16 10:41:32.032  1022  1048 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-16 10:41:32.032  1022  1048 I ActivityManager: Killing 6254:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-16 10:41:32.102  1022  1061 W PackageSettings: Skipping PackageSetting{3c5e24ef com.example.hello/10346} due to missing metadata
,03-16 10:41:32.132  1022  1547 W ActivityManager: Spurious death for ProcessRecord{1d797c7a 6254:com.test.thalitest/u0a167}, curProc for 6254: null
,03-16 10:41:32.142  1022  1061 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-16 10:41:32.182  1022  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-16 10:41:32.192  6041  6041 I art     : Explicit concurrent mark sweep GC freed 385(26KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 936us total 39.485ms
,03-16 10:41:32.192  4151  4151 I art     : Explicit concurrent mark sweep GC freed 18712(1058KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 934us total 39.712ms
,03-16 10:41:32.212  1022  1105 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 10:41:32.222  1877  1877 E SamsungIME: mOCRHelper is null
,03-16 10:41:32.242  1786  2094 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 10:41:32.252  3730  3730 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 10:41:32 GMT+01:00 2016
,03-16 10:41:32.252  1022  3360 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.252  1022  3360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 10:41:32.252  1022  3360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 10:41:32.272  1022  1047 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-16 10:41:32.272  1022  1047 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-16 10:41:32.272  1022  1047 W TextServicesManagerService: no available spell checker services found
,03-16 10:41:32.282  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.282  1022  1132 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-16 10:41:32.282  1022  1132 V NetworkStats: performPollLocked(flags=0x3)
03-16 10:41:32.282  1022  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 10:41:32.282  3730  3730 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 10:41:32.292  1022  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-16 10:41:32.292  1022  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-16 10:41:32.292  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.292  1022  1132 V NetworkStats: performPollLocked() took 9ms
03-16 10:41:32.292  1022  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 10:41:32.302  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.302  3730  3730 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 10:41:32.302  1022  1034 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,03-16 10:41:32.302  1022  1034 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,03-16 10:41:32.302  1022  1034 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-16 10:41:32.302  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 10:41:32.302  1022  1034 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-16 10:41:32.302  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.302  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.302  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.302  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 10:41:32.322  6324  6324 E Zygote  : MountEmulatedStorage(),
03-16 10:41:32.322  6324  6324 E Zygote  : v2
03-16 10:41:32.322  6324  6324 I libpersona: KNOX_SDCARD checking this for 10090
03-16 10:41:32.322  6324  6324 I libpersona: KNOX_SDCARD not a persona
,03-16 10:41:32.322  6324  6324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 10:41:32.322  6324  6324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 10:41:32.322  1022  1034 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6324 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-16 10:41:32.322  6324  6324 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 10:41:32.352  3730  3730 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 10:41:32.362  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 10:41:32.362  1022  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 10:41:32.362  1022  1217 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 10:41:32.362  1022  1217 D SecContentProvider2: mCursor = null
,03-16 10:41:32.362  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 10:41:32.362  6324  6324 D ActivityThread: Added TimaKeyStore provider
,03-16 10:41:32.372  3730  3730 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 10:41:32.382  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 10:41:32.392  1022  1022 I art     : Explicit concurrent mark sweep GC freed 40530(2MB) AllocSpace objects, 25(404KB) LOS objects, 33% free, 24MB/36MB, paused 4.163ms total 238.975ms
,03-16 10:41:32.392  1022  1061 I art     : WaitForGcToComplete blocked for 141.029ms for cause Explicit
,03-16 10:41:32.392  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-16 10:41:32.392  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-16 10:41:32.402  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-16 10:41:32.432  6324  6324 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 10:41:32.432  1442  1442 D RegisteredServicesCache: empty dynamic service
03-16 10:41:32.432  6324  6324 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 10:41:32.432  6324  6324 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 10:41:32.432  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.432  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:32.432  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 10:41:32.452  6324  6324 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-16 10:41:32.462  6324  6324 D elm:15121: ElmAgentService : onCreate()
,03-16 10:41:32.462  6324  6339 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-16 10:41:32.462  6324  6339 D elm:15121: MainReceiver.listeningToPackageRemoved()
,03-16 10:41:32.462  6324  6339 D elm:15121: MDMBridge.getInstance()
03-16 10:41:32.462  6324  6339 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 10:41:32.462  6324  6339 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 10:41:32.482  1022  1047 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-16 10:41:32.482  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-16 10:41:32.482  6324  6324 D elm:15121: ElmAgentService : onDestroy().
,03-16 10:41:32.482  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.492  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.492  3730  6323 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-16 10:41:32.492  3730  6323 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-16 10:41:32.502  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 10:41:32.502  3730  3730 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 10:41:32.502  1022  1047 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 10:41:32.502  1022  1047 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 10:41:32.502  1022  1047 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 10:41:32.512  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.522  1022  1022 D RCPManagerService: PackageReceiver onReceive()
,03-16 10:41:32.532  1022  1022 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-16 10:41:32.532  1022  1022 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.552  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.562  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.562  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 10:41:32.562  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 10:41:32.572  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.582  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.582  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 10:41:32.582  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.582  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 10:41:32.592  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 10:41:32.592  1022  1047 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-16 10:41:32.592  1022  1061 I art     : Explicit concurrent mark sweep GC freed 12944(672KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 4.481ms total 199.932ms
,03-16 10:41:32.592  1022  1047 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-16 10:41:32.612   303   303 E SMD     : DCD OFF
,03-16 10:41:32.642  1022  1022 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-16 10:41:32.642  1022  1022 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.642  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.642  1022  1022 V EnterpriseBillingPolicy: uID is 10167
03-16 10:41:32.642  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
,03-16 10:41:32.642  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 10:41:32.652  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: uID is 10167
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 10:41:32.652  1022  1164 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 10:41:32.652  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 10:41:32.652  1022  2724 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-16 10:41:32.662  1022  1061 D PackageManager: delete codoeFile: 
,03-16 10:41:32.662  1022  1061 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-16 10:41:32.662  1022  1061 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-16 10:41:32.662  1022  1061 D PackageManager: result of delete: 1{47431845}
,03-16 10:41:32.662  5753  5753 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 10:41:32.672  5753  5753 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 10:41:32.672  5753  5753 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 10:41:32.672  5753  5753 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.672  6307  6307 D AndroidRuntime: Shutting down VM
,03-16 10:41:32.682  5825  5825 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-16 10:41:32.682  5825  5825 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-16 10:41:32.682  1022  1484 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.682  1022  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:32.682  1022  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-16 10:41:32.702  5042  5042 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-16 10:41:32.752  1022  1545 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.752  1022  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:32.752  1022  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-16 10:41:32.772  5705  5705 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.772  1022  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.772  1022  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 10:41:32.772  1022  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-16 10:41:32.782  1022  1035 I TactileAssist: enable value -1
,03-16 10:41:32.782  1022  1035 I TactileAssist: internal enable value -1
03-16 10:41:32.782  1022  1035 I TactileAssist: intensity value -1
03-16 10:41:32.782  1022  1035 I TactileAssist: saveAppList value true
,03-16 10:41:32.782  5705  6342 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,03-16 10:41:32.782  5705  6342 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,03-16 10:41:32.792  1022  1035 I TactileAssist: List of disabled apps :
,03-16 10:41:32.802  5932  5932 D Compatibility: onReceive() it will make start service
,03-16 10:41:32.802  1022  1486 W ActivityManager: userId = 0, bbcId = -10000
,03-16 10:41:32.802  1022  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:32.812  1022  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-16 10:41:32.812  1022  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 10:41:32.812  1022  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.812  1022  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 10:41:32.812  1022  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 10:41:32.822  5932  6343 D Compatibility: onHandleIntent()
,03-16 10:41:32.822  5932  6343 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,03-16 10:41:32.822  5932  6343 D Compatibility: found: 2
,03-16 10:41:32.822  5932  6343 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-16 10:41:32.822  5932  6343 D Compatibility: skipping ResolveInfo{10c4b2b3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-16 10:41:32.822  5932  6343 D Compatibility: considering ResolveInfo{3ba4d070 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,03-16 10:41:32.822  5932  6343 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-16 10:41:32.822  5932  6343 D Compatibility: enabling receiver ResolveInfo{34f0fe9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-16 10:41:32.822  6344  6344 E Zygote  : MountEmulatedStorage()
,03-16 10:41:32.822  6344  6344 E Zygote  : v2
03-16 10:41:32.822  6344  6344 I libpersona: KNOX_SDCARD checking this for 10055
03-16 10:41:32.822  6344  6344 I libpersona: KNOX_SDCARD not a persona
,03-16 10:41:32.832  6344  6344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 10:41:32.832  1022  1484 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6344 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-16 10:41:32.832  6344  6344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 10:41:32.832  6344  6344 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 10:41:32.832  5932  6343 D Compatibility: enabling receiver ResolveInfo{36b8f46e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-16 10:41:32.842  5932  6343 D Compatibility: enabling receiver ResolveInfo{224dc70f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,03-16 10:41:32.842  5932  6343 D Compatibility: enabling receiver ResolveInfo{125e839c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-16 10:41:32.852  5932  6343 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-16 10:41:32.852  6344  6344 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 10:41:32.852  6344  6344 D ActivityThread: Added TimaKeyStore provider
,03-16 10:41:32.882  6307  6307 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-16 10:41:32.902  6344  6344 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 10:41:32.902  1022  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 10:41:32.902  1022  1061 D PackageManager: userId{-1}
03-16 10:41:32.902  1022  1061 D PackageManager: andCode{true}
,03-16 10:41:32.942  6344  6344 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-16 10:41:32.942  6344  6344 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 10:41:32.942  6344  6344 D UserAnalysis: Create SecureDbHelper
,03-16 10:41:32.952  6344  6344 D IntelligenceServiceApplication: onCreate()
,03-16 10:41:32.952  6344  6344 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-16 10:41:32.962  5950  5950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-16 10:41:32.962  1022  3360 W ActivityManager: userId = 0, bbcId = -10000
03-16 10:41:32.962  1022  3360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 10:41:32.962  1022  3360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-16 10:41:32.972  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.972  6344  6344 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 10:41:32.972  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.972  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 10:41:32.972  1022  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 10:41:32.992  5950  6362 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30),
,03-16 10:41:33.002  6363  6363 E Zygote  : MountEmulatedStorage()
,03-16 10:41:33.002  6363  6363 E Zygote  : v2
03-16 10:41:33.002  6363  6363 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 10:41:33.002  6363  6363 I libpersona: KNOX_SDCARD not a persona
03-16 10:41:33.002  1022  1486 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6363 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-16 10:41:33.002  6363  6363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:33.002  5950  6362 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 10:41:33.002  5950  6362 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 10:41:33.012  1022  1484 I ActivityManager: Killing 5278:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 10:41:33.002  5950  6362 W System.err: 	at com.samsung.android.app.assis,tantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-16 10:41:33.002  5950  6362 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:33.002  5950  6362 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 10:41:33.012  6344  6344 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 10:41:33.022  6363  6363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 10:41:33.022  6363  6363 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 10:41:33.032  6344  6344 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 10:41:33.032  6344  6344 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 10:41:33.042  6344  6344 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 10:41:33.042  6344  6344 D AndroidRuntime: Shutting down VM
03-16 10:41:33.042  6344  6344 E AndroidRuntime: FATAL EXCEPTION: main
03-16 10:41:33.042  6344  6344 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6344
03-16 10:41:33.042  6344  6344 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 10:41:33.042  6344  6344 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 10:41:33.042  1022  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,03-16 10:41:33.052  6363  6363 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 10:41:33.052  6363  6363 D ActivityThread: Added TimaKeyStore provider
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: Can't write: system_app_crash
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop175.tmp: open failed: EROFS (Read-only file system)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-16 10:41:33.052  1022  6379 E DropBoxManagerService: 	... 5 more
03-16 10:41:33.062  6344  6344 I Process : Sending signal. PID: 6344 SIG: 9
03-16 10:41:33.082  6363  6363 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.

```
