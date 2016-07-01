#### Test 757892680c366d1_thali09_samsung-SM-A300FU Logs


```
--------- beginning of system
07-01 12:08:21.723  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
--------- beginning of main
07-01 12:08:21.793   333   333 I ServiceManager: Waiting for service AtCmdFwd...
07-01 12:08:22.023  1016  1094 V AlarmManager: waitForAlarm result :4
07-01 12:08:22.103  1016  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-01 12:08:22.103  1016  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-01 12:08:22.103  1016  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-01 12:08:22.103  1016  1536 D BatteryService: stay LED for fully charged
07-01 12:08:22.103  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-01 12:08:22.103  1016  1016 I MotionRecognitionService: Plugged
07-01 12:08:22.103  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
07-01 12:08:22.113  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-01 12:08:22.113  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-01 12:08:22.113  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-01 12:08:22.113  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:08:22.123  3365  3365 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:08:22.123  3365  3477 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:08:22.133  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:08:22.133  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:08:22.133  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:08:22.513  6909  6909 D AndroidRuntime: 
07-01 12:08:22.513  6909  6909 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:08:22.523  6909  6909 D AndroidRuntime: CheckJNI is OFF
07-01 12:08:22.523  6909  6909 D AndroidRuntime: readGMSProperty: start
07-01 12:08:22.523  6909  6909 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:08:22.523  6909  6909 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 12:08:22.523  6909  6909 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 12:08:22.523  6909  6909 D AndroidRuntime: readGMSProperty: end
07-01 12:08:22.523  6909  6909 D AndroidRuntime: addProductProperty: start
07-01 12:08:22.643  6909  6909 E AffinityControl: AffinityControl: registerfunction enter
07-01 12:08:22.663  6909  6909 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 12:08:22.673  1016  1220 E PersonaManagerService: inState():  stateMachine is null !!
07-01 12:08:22.673  1016  1220 I PersonaManagerService: PersonaId don't exist
07-01 12:08:22.673  1016  1220 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 12:08:22.683  1016  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:22.693  1016  1220 W ActivityManager: mDVFSHelper.acquire()
07-01 12:08:22.693  1016  1220 D FocusedStackFrame: Set to : 0
07-01 12:08:22.703  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 12:08:22.703  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-01 12:08:22.703  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:22.703  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:22.703  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:22.703  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:22.713  6920  6920 E Zygote  : MountEmulatedStorage()
07-01 12:08:22.713  6920  6920 E Zygote  : v2
07-01 12:08:22.713  1016  1220 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6920 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:08:22.723  1016  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 12:08:22.723  1016  1220 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:22.723  6920  6920 I libpersona: KNOX_SDCARD checking this for 10170
07-01 12:08:22.723  1016  1220 D InputDispatcher: Focused application set to: xxxx
07-01 12:08:22.723  6920  6920 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:22.723  1016  1220 D InputDispatcher: Focus left window: 1473
07-01 12:08:22.723  6920  6920 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:22.723  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 12:08:22.723  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 12:08:22.723  6909  6909 D AndroidRuntime: Shutting down VM
07-01 12:08:22.723   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-01 12:08:22.723  6920  6920 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:22.723  6920  6920 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 12:08:22.743  6920  6920 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:22.743  6920  6920 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:22.753  1016  3423 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-01 12:08:22.753  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:22.753  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:22.753  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 12:08:22.763  1016  3423 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:08:22.773  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-01 12:08:22.793   333   333 I ServiceManager: Waiting for service AtCmdFwd...
07-01 12:08:22.803   259  1096 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-01 12:08:22.813   259   437 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-01 12:08:22.813  1473  1473 D Launcher: onTrimMemory. Level: 20
07-01 12:08:22.813  1473  1473 V ActivityThread: updateVisibility : ActivityRecord{29538e37 token=android.os.BinderProxy@3633678f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 12:08:22.883  6920  6920 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 12:08:22.893  6920  6920 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7073-7074)
07-01 12:08:22.893  6920  6920 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:22.913  6920  6920 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b02c00a}
07-01 12:08:22.923  6920  6920 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:22.923  6920  6920 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:08:22.923  6909  6909 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-01 12:08:22.953  6920  6920 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:08:22.963  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:22.963  6920  6920 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 12:08:22.983  6920  6920 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-01 12:08:22.983  6920  6920 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-01 12:08:22.983  6920  6920 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-01 12:08:22.993  6920  6920 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-01 12:08:22.993  6920  6920 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 12:08:22.993  6920  6920 I Adreno-EGL: Build Date: 04/06/15 Mon
07-01 12:08:22.993  6920  6920 I Adreno-EGL: Local Branch: 
07-01 12:08:22.993  6920  6920 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-01 12:08:22.993  6920  6920 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-01 12:08:22.993  6920  6920 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-01 12:08:23.193  6920  6947 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-01 12:08:23.243  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:23.253  6920  6920 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 12:08:23.263  6920  6920 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 12:08:23.263  6920  6920 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-01 12:08:23.263  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{4f0316f u0 com.test.thalitest/.MainActivity t44}
07-01 12:08:23.273  6920  6920 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-01 12:08:23.283  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:23.283  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:23.353  6920  6960 D OpenGLRenderer: Render dirty regions requested: true
07-01 12:08:23.363  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 12:08:23.363  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 12:08:23.363  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 12:08:23.363  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 12:08:23.363  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 12:08:23.423  1016  1220 I ActivityManager: Killing 6097:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
07-01 12:08:23.423  6920  6920 V ActivityThread: updateVisibility : ActivityRecord{ff8ef9d token=android.os.BinderProxy@3be71647 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-01 12:08:23.433  6920  6920 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 12:08:23.433  6920  6920 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 12:08:23.433   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-01 12:08:23.443  1016  1134 D InputDispatcher: Focus entered window: 6920
07-01 12:08:23.453  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:23.453  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:23.453  6920  6920 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-01 12:08:23.453  6920  6960 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 12:08:23.453  6920  6960 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-01 12:08:23.453  6920  6960 D OpenGLRenderer: Enabling debug mode 0
07-01 12:08:23.473  1016  1476 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-01 12:08:23.483  1174  1174 I StatusBar: Icon Only
07-01 12:08:23.483  1174  1174 D PanelView: There is/are notification(s) 
07-01 12:08:23.483  6920  6920 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3be71647 time:127665
07-01 12:08:23.483  6920  6920 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-01 12:08:23.493  1016  1046 I ActivityManager: Displayed Component not be shown by security: +727ms (total +12s126ms)
07-01 12:08:23.493  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4f0316f u0 com.test.thalitest/.MainActivity t44} time:127676
07-01 12:08:23.493  1016  1046 W ActivityManager: mDVFSHelper.release()
07-01 12:08:23.503   259   444 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-01 12:08:23.503   259  1096 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-01 12:08:23.533  1016  6963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-01 12:08:23.543  1856  1856 I SamsungIME: getCurrentCandidateView
07-01 12:08:23.563  6920  6920 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6920
,07-01 12:08:23.703  1856  1856 D SamsungIME: Dismiss ExpandCandiate
,07-01 12:08:23.793   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:08:23.803   295   295 E SMD     : DCD OFF,
,07-01 12:08:23.803  6920  6920 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 12:08:23.863  1856  1856 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 12:08:23.893  6920  6964 D jxcore_app_log: JniHelper::setJavaVM(0xb72342f0), pthread_self() = -1216808624
,07-01 12:08:23.903  1856  1856 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 12:08:23.903  6920  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3319fa0d added. We now have 1 listener(s)
,07-01 12:08:23.913  1856  1856 I SamsungIME: KeybaordView init() : load resources
,07-01 12:08:23.913  6920  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-01 12:08:23.913  6920  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-01 12:08:23.913  6920  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 12:08:23.923  6920  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:08:23.923  6920  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@345c7f10 added. We now have 1 listener(s)
,07-01 12:08:23.923  6920  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:08:23.933  6920  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-01 12:08:23.933  6920  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 12:08:23.933  6920  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 12:08:23.933  6920  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 12:08:23.933  6920  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 12:08:23.933  6920  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 12:08:23.933  1856  1856 I SamsungIME: getCurrentKeyboard
07-01 12:08:23.933  1856  1856 I SamsungIME: getTextKeyboard
,07-01 12:08:23.943  6920  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:23.943  6920  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:08:23.943  6920  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:08:23.943  6920  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 12:08:23.943  6920  6964 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 12:08:23.943  6920  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:23.953  6920  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:23.973  1856  1856 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-01 12:08:23.983  6920  6920 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 12:08:24.553  6920  6971 W jxcore-log: Initializing JXcore engine
07-01 12:08:24.553  6920  6971 W jxcore-log: JXcore engine is ready
,07-01 12:08:24.603  2007  2007 E audit   : type=1400 msg=audit(1467367704.603:205): avc:  denied  { ioctl } for  pid=6971 comm="Thread-1253" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-01 12:08:24.603  2007  2007 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:24.603  2007  2007 E audit   : type=1300 msg=audit(1467367704.603:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dc008f8 items=0 ppid=311 ppcomm=main pid=6971 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1253" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-01 12:08:24.603  2007  2007 E audit   : type=1320 msg=audit(1467367704.603:205): 
,07-01 12:08:24.613  6920  6971 W jxcore-log: Starting JXcore engine
,07-01 12:08:24.713  6920  6971 W jxcore-log: Platform android
07-01 12:08:24.713  6920  6971 W jxcore-log: 
07-01 12:08:24.713  6920  6971 W jxcore-log: Process ARCH arm
07-01 12:08:24.713  6920  6971 W jxcore-log: 
,07-01 12:08:24.793   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-01 12:08:24.923  6920  6971 I jxcore-log: JXcore Cordova bridge is ready!
07-01 12:08:24.923  6920  6971 I jxcore-log: 
,07-01 12:08:24.923  6920  6971 W jxcore-log: JXcore engine is started
,07-01 12:08:24.923  6920  6964 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 12:08:24.923  6920  6920 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 12:08:24.933  6920  6971 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-01 12:08:24.933  6920  6971 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 12:08:24.943  6920  6920 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-01 12:08:24.943  6920  6920 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 12:08:24.943  1016  1468 D FocusedStackFrame: Set to : 0
07-01 12:08:24.943  1016  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:24.943  1016  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 12:08:24.943  1016  1468 D InputDispatcher: Focused application set to: xxxx
07-01 12:08:24.943  1016  1468 D InputDispatcher: Focus left window: 6920
07-01 12:08:24.953  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:24.953  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:24.953  1016  1468 I ActivityManager: Killing 6509:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-01 12:08:24.963  6920  6920 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-01 12:08:24.963  6920  6920 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-01 12:08:24.963  6920  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 12:08:24.963  6920  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:24.963  6920  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:24.963  6920  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 12:08:24.963  6920  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3319fa0d removed from the list
07-01 12:08:24.963  6920  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:24.963  6920  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@345c7f10 removed from the list
07-01 12:08:24.963  6920  6920 D io.jxcore.node.ConnectivityMonitor: stop
,07-01 12:08:24.963  6920  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-01 12:08:24.963  6920  6920 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-01 12:08:24.973   259  6262 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-01 12:08:24.983   259   444 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-01 12:08:24.983  1016  3423 W ActivityManager: mDVFSHelper.acquire()
,07-01 12:08:24.993  1016  3423 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-01 12:08:25.013  1473  1473 D Launcher: onRestart, Launcher: 722784982
,07-01 12:08:25.013  1473  1473 D Launcher: onStart, Launcher: 722784982
,07-01 12:08:25.013  1473  1473 D Launcher.HomeView: onStart
07-01 12:08:25.013  1473  1473 D Launcher: onResume, Launcher: 722784982
,07-01 12:08:25.013  1016  1029 D SettingsProvider: name = kids_home_mode
07-01 12:08:25.013  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-01 12:08:25.013  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:08:25.013  1016  1029 D SettingsProvider: selectionArgs: false
07-01 12:08:25.013  1016  1029 D SettingsProvider: selectionArgs: 10006
07-01 12:08:25.013  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:08:25.013  1016  1029 D SettingsProvider: ret = -1
07-01 12:08:25.013  1473  1473 D Launcher.HomeView: onResume
,07-01 12:08:25.023  1473  1473 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-01 12:08:25.023  1473  1473 D MenuAppsGridFragment: onResume
,07-01 12:08:25.033  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.033  1473  1473 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 12:08:25.033  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.033  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-01 12:08:25.033  1473  1473 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 12:08:25.033  1016  1220 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
07-01 12:08:25.033  1016  1220 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-01 12:08:25.033  1016  1220 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.033  1016  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.033  1016  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-01 12:08:25.033  1016  1220 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-01 12:08:25.043  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.043  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.043  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.043  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.063  6977  6977 E Zygote  : MountEmulatedStorage()
07-01 12:08:25.063  6977  6977 E Zygote  : v2
07-01 12:08:25.063  6977  6977 I libpersona: KNOX_SDCARD checking this for 10039
07-01 12:08:25.063  6977  6977 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.073  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.073  1016  1220 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6977 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-01 12:08:25.073  1016  1134 D ActivityManager: handle home activity for 0,
07-01 12:08:25.073  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 12:08:25.073  1016  1134 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-01 12:08:25.073  1016  1134 D KnoxTimeoutHandler: post home show event for user 0
07-01 12:08:25.073  1016  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 12:08:25.073  1016  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 12:08:25.073  1016  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 12:08:25.073  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-01 12:08:25.073  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-01 12:08:25.073  1473  1473 D Launcher.HomeView: onPause
07-01 12:08:25.073  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 12:08:25.073  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:25.073  1473  1473 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-01 12:08:25.083  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.083  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.083  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.083  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 12:08:25.083  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.083  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.083  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-01 12:08:25.083  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,07-01 12:08:25.093  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.093  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.093  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.093  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.103  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6992 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,07-01 12:08:25.103  6992  6992 E Zygote  : MountEmulatedStorage()
07-01 12:08:25.103  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-01 12:08:25.103  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.103  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.103  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 12:08:25.113  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.113  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.113  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.113  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.113  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.113  6992  6992 I libpersona: KNOX_SDCARD checking this for 10089
07-01 12:08:25.113  6977  6977 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:25.113  6992  6992 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.113  6992  6992 E Zygote  : v2
,07-01 12:08:25.113  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.113  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:25.123  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.123  7000  7000 E Zygote  : MountEmulatedStorage(),
07-01 12:08:25.123  7000  7000 I libpersona: KNOX_SDCARD checking this for 10139
07-01 12:08:25.123  7000  7000 E Zygote  : v2
,07-01 12:08:25.123  7000  7000 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.123  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7000 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:25.133  7000  7000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.133  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.133  6992  6992 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:25.143  7000  7000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:25.143  7000  7000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-01 12:08:25.153  6977  6977 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 12:08:25.163   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-01 12:08:25.163  1016  1535 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.163  1016  1535 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1473, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-01 12:08:25.163  1016  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.163  1016  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 12:08:25.163  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 12:08:25.163  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.163  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.163  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-01 12:08:25.163  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 12:08:25.173  2602  2602 D Recents_RecreateReceiver: onReceive by home
,07-01 12:08:25.173  7000  7000 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.173  1016  1474 D InputDispatcher: Focus entered window: 1473
,07-01 12:08:25.173  7000  7000 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.173  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:25.173  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:25.173  1473  1473 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-01 12:08:25.183  6992  6992 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:08:25.183  6992  6992 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-01 12:08:25.183  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.183  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-01 12:08:25.183  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.183  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-01 12:08:25.193  1473  1473 V ActivityThread: updateVisibility : ActivityRecord{29538e37 token=android.os.BinderProxy@3633678f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-01 12:08:25.193  1473  1473 D Launcher.HomeView: onStop
07-01 12:08:25.193  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.193  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.193  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.193  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.193  1016  1472 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-01 12:08:25.193  1016  7023 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:08:25.203  7025  7025 E Zygote  : MountEmulatedStorage(),
07-01 12:08:25.203  7025  7025 E Zygote  : v2,
07-01 12:08:25.203  1174  1174 I StatusBar: Icon Only
07-01 12:08:25.203  1174  1174 D PanelView: There is/are notification(s) 
07-01 12:08:25.203  7025  7025 I libpersona: KNOX_SDCARD checking this for 10084
07-01 12:08:25.203  7025  7025 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.213  7025  7025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-01 12:08:25.213  7025  7025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:25.213  6920  6920 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-01 12:08:25.213  1856  1856 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-01 12:08:25.213  7025  7025 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.223  1016  1134 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7025 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-01 12:08:25.233  1473  1473 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3633678f time:129416
,07-01 12:08:25.233  6973  6973 D AndroidRuntime: 
07-01 12:08:25.233  6973  6973 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-01 12:08:25.243  6973  6973 D AndroidRuntime: CheckJNI is OFF
,07-01 12:08:25.243  6973  6973 D AndroidRuntime: readGMSProperty: start
07-01 12:08:25.243  6973  6973 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:08:25.243  6973  6973 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 12:08:25.243  6973  6973 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 12:08:25.243  6973  6973 D AndroidRuntime: readGMSProperty: end
07-01 12:08:25.243  6973  6973 D AndroidRuntime: addProductProperty: start
,07-01 12:08:25.243  7025  7025 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:25.253  7025  7025 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.253  7000  7000 V TaskCloserActivity: TaskCloserActivity enter()
,07-01 12:08:25.253  7000  7000 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-01 12:08:25.263  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.263  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.263  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
07-01 12:08:25.263  1016  1472 I ActivityManager: Killing 6521:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-01 12:08:25.263  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29d89aa3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:129449
07-01 12:08:25.263  1016  1046 W ActivityManager: mDVFSHelper.release()
,07-01 12:08:25.283  7025  7025 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:25.283  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-01 12:08:25.303  1016  3905 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.303  1016  3905 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-01 12:08:25.303  1016  3905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.303  1016  3905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-01 12:08:25.303  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.303  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.303  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.303  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.323  7050  7050 E Zygote  : MountEmulatedStorage(),
,07-01 12:08:25.323  7050  7050 E Zygote  : v2
,07-01 12:08:25.323  7050  7050 I libpersona: KNOX_SDCARD checking this for 10135
07-01 12:08:25.323  7050  7050 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.323  1016  3905 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7050 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-01 12:08:25.323  1016  3905 I ActivityManager: Killing 6499:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
07-01 12:08:25.323  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:25.323  1016  3905 I ActivityManager: Killing 6565:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-01 12:08:25.333  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:25.333  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.353  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:25.353  7050  7050 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.363  6977  6977 D NearbySource: Nearby Source Create!
,07-01 12:08:25.363  6977  6977 D NearbyContext: Nearby Context Create!
,07-01 12:08:25.363  1016  3908 D PersonaManager: isKioskContainerExistOnDevice,
,07-01 12:08:25.373  7050  7050 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-01 12:08:25.373  7050  7050 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-01 12:08:25.373  7050  7050 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 12:08:25.373  7050  7050 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-01 12:08:25.373  7050  7050 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 12:08:25.373  6973  6973 E AffinityControl: AffinityControl: registerfunction enter
,07-01 12:08:25.403   258   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-01 12:08:25.403   258   523 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:08:25.403  6977  6977 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-01 12:08:25.403  6973  6973 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-01 12:08:25.403  6977  6977 D SLinkSource: Samsung link source created
,07-01 12:08:25.413  1016  1472 I ActivityManager: Killing 6547:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,07-01 12:08:25.423  1016  1476 D PackageManager: START PACKAGE DELETE: observer{204878933}
07-01 12:08:25.423  1016  1476 D PackageManager: pkg{<packageName>}
07-01 12:08:25.423  1016  1476 D PackageManager: user{0}
07-01 12:08:25.423  1016  1476 D PackageManager: caller{2000}
07-01 12:08:25.423  1016  1476 D PackageManager: flags{2}
,07-01 12:08:25.423  1016  1476 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-01 12:08:25.423  1016  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 12:08:25.423  1016  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-01 12:08:25.423  1016  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:08:25.423  1016  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:08:25.423  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 12:08:25.423  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-01 12:08:25.423  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-01 12:08:25.423  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 12:08:25.423  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-01 12:08:25.423  1016  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-01 12:08:25.443  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-01 12:08:25.443  1016  1041 I ActivityManager: Killing 6920:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-01 12:08:25.513  1016  1055 W PackageSettings: Skipping PackageSetting{12e94e35 com.example.hello/10168} due to missing metadata
,07-01 12:08:25.553  1016  1468 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:08:25.553  1016  3905 W ActivityManager: Spurious death for ProcessRecord{5c45e6a 6920:com.test.thalitest/u0a170}, curProc for 6920: null
,07-01 12:08:25.573  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
07-01 12:08:25.583  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-01 12:08:25.613  1016  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:08:25.623  6977  6977 D GalleryCacheReady: Receive : home resume
,07-01 12:08:25.643  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 12:08:25.643  2028  2194 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 12:08:25.653  1856  1856 E SamsungIME: mOCRHelper is null
,07-01 12:08:25.653  2754  2754 I art     : Explicit concurrent mark sweep GC freed 24233(1313KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 987us total 59.397ms
,07-01 12:08:25.663  1439  1439 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:08:25.663  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-01 12:08:25.663  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:08:25.663  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
,07-01 12:08:25.663  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
07-01 12:08:25.663  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-01 12:08:25.673  1016  1122 V NetworkStats: performPollLocked() took 7ms
07-01 12:08:25.673  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:08:25.683  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,07-01 12:08:25.683  1016  3905 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.683  1016  3905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.683  1016  3905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-01 12:08:25.693  1431  1431 D RegisteredServicesCache: empty dynamic service
,07-01 12:08:25.703  6977  7067 D ContactProvider: getAllContactInfoList Start
,07-01 12:08:25.713  1431  1431 D RegisteredComponentCache: Collect Tech packages for Knox
,07-01 12:08:25.723  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,07-01 12:08:25.743  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:08:25.743  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:08:25.753  6432  6432 D Mms/UIEventReceiver: ui event
,07-01 12:08:25.753  1016  1476 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-01 12:08:25.763  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.763  1016  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 12:08:25.763  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-01 12:08:25.773  4872  4872 I art     : Explicit concurrent mark sweep GC freed 20332(1283KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 12MB/16MB, paused 1.248ms total 164.992ms
,07-01 12:08:25.773  6788  6788 I art     : Explicit concurrent mark sweep GC freed 593(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 713us total 174.551ms
,07-01 12:08:25.793  7000  7000 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-01 12:08:25.803  6977  7067 D ContactProvider: getAllContactInfoList End
,07-01 12:08:25.803  6977  7067 I syncContacts: thread: 1238, sync time = 362
,07-01 12:08:25.813  1016  1016 I art     : Explicit concurrent mark sweep GC freed 40771(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.046ms total 227.567ms
,07-01 12:08:25.813  1016  1055 I art     : WaitForGcToComplete blocked for 214.974ms for cause Explicit
,07-01 12:08:25.823  1016  3423 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-01 12:08:25.823  1016  3423 D SecContentProvider2: mCursor = null
,07-01 12:08:25.823  2702  2702 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 01 12:08:25 GMT+02:00 2016
,07-01 12:08:25.843  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
07-01 12:08:25.843  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-01 12:08:25.843  1016  1040 W TextServicesManagerService: no available spell checker services found
,07-01 12:08:25.843  1016  3908 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-01 12:08:25.843  1016  3908 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-01 12:08:25.843  1016  3908 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.843  1016  3908 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 12:08:25.853  1016  3908 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-01 12:08:25.853  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:25.863  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:25.863  2702  2702 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-01 12:08:25.863  1016  1535 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-01 12:08:25.863  1016  1535 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-01 12:08:25.863  1016  1535 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-01 12:08:25.873  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.873  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.873  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.873  1016  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.873  2702  2702 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-01 12:08:25.873  2702  2702 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 12:08:25.873  2702  2702 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-01 12:08:25.883  7071  7071 E Zygote  : MountEmulatedStorage(),
,07-01 12:08:25.883  7071  7071 E Zygote  : v2
07-01 12:08:25.883  7071  7071 I libpersona: KNOX_SDCARD checking this for 10090
07-01 12:08:25.883  7071  7071 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.883  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-01 12:08:25.883  1016  1535 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7071 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-01 12:08:25.893  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:25.893  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,07-01 12:08:25.893  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.893  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-01 12:08:25.893  6432  6432 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-01 12:08:25.893  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.893  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.893  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.893  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.903  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-01 12:08:25.903  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-01 12:08:25.903  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:25.903  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-01 12:08:25.903  7080  7080 E Zygote  : MountEmulatedStorage()
07-01 12:08:25.903  7080  7080 E Zygote  : v2
07-01 12:08:25.903  7080  7080 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:08:25.903  7080  7080 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.903  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.913  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:25.913  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-01 12:08:25.913  1016  1472 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-01 12:08:25.913  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-01 12:08:25.913  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.913  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,07-01 12:08:25.913  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-01 12:08:25.923  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-01 12:08:25.923  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-01 12:08:25.923  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-01 12:08:25.923  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.923  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.923  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-01 12:08:25.923  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:25.933  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,07-01 12:08:25.933  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-01 12:08:25.933  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.933  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.933  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.933  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.933  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-01 12:08:25.953  6432  7091 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-01 12:08:25.953  7098  7098 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:08:25.953  7098  7098 E Zygote  : MountEmulatedStorage()
07-01 12:08:25.953  7098  7098 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.953  7098  7098 E Zygote  : v2
,07-01 12:08:25.953  7098  7098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:25.953  6432  7091 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-01 12:08:25.953  7098  7098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:25.953  7098  7098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.973  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7098 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 12:08:25.983  1016  1220 I TactileAssist: enable value -1
07-01 12:08:25.983  1016  1220 I TactileAssist: internal enable value -1
07-01 12:08:25.983  1016  1220 I TactileAssist: intensity value -1
07-01 12:08:25.983  1016  1220 I TactileAssist: saveAppList value true
,07-01 12:08:25.983  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:25.983   311   311 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 21.300ms
07-01 12:08:25.983  7071  7071 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.003  1016  1220 I TactileAssist: List of disabled apps :
,07-01 12:08:26.003   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 17.128ms
,07-01 12:08:26.003  7098  7098 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.003  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.003  7080  7080 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.013  7098  7098 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.013  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-01 12:08:26.023   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.443ms
,07-01 12:08:26.033  2702  7070 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-01 12:08:26.033  2702  7070 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-01 12:08:26.053  2702  2702 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-01 12:08:26.063  6767  6767 D Compatibility: onReceive() it will make start service
,07-01 12:08:26.063  1016  3910 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-01 12:08:26.063  1016  3910 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-01 12:08:26.063  1016  3910 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.063  1016  3910 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:26.063  1016  3910 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-01 12:08:26.063  7071  7071 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-01 12:08:26.063  7071  7071 D elm:15121: ELMEngine.ELMEngine( context ).
,07-01 12:08:26.073  1016  1055 I art     : Explicit concurrent mark sweep GC freed 10371(517KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.544ms total 251.025ms
,07-01 12:08:26.073  7071  7071 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-01 12:08:26.073  7098  7098 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-01 12:08:26.073  1016  1028 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-01 12:08:26.073  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.073  1016  3423 D SecContentProvider2: uri = -1 selection = getSealedState
07-01 12:08:26.073  1016  3423 D SecContentProvider2: mCursor = null
,07-01 12:08:26.073  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.073  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:26.073  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-01 12:08:26.083  7098  7098 I PopupuiReceiver_KNOX: getSealedState : true
,07-01 12:08:26.083  6767  7117 D Compatibility: onHandleIntent()
07-01 12:08:26.083  1016  1220 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-01 12:08:26.083  1016  1220 D SecContentProvider2: mCursor = null
,07-01 12:08:26.083  6767  7117 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
07-01 12:08:26.083  7098  7098 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,07-01 12:08:26.083  1016  1535 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
07-01 12:08:26.083  1016  1535 D SecContentProvider2: mCursor = null
07-01 12:08:26.083  7098  7098 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-01 12:08:26.083  7098  7098 D PopupuiReceiver: Action package removed
,07-01 12:08:26.083  7071  7071 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-01 12:08:26.083  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-01 12:08:26.083  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.083  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.083  6767  7117 D Compatibility: found: 2
07-01 12:08:26.083  6767  7117 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-01 12:08:26.083  6767  7117 D Compatibility: skipping ResolveInfo{29df46f1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-01 12:08:26.083  6767  7117 D Compatibility: considering ResolveInfo{2b14d2d6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-01 12:08:26.083  6767  7117 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
07-01 12:08:26.083  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-01 12:08:26.083  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-01 12:08:26.083  6767  7117 D Compatibility: enabling receiver ResolveInfo{179f2957 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-01 12:08:26.083  7071  7071 D elm:15121: ElmAgentService : onCreate()
,07-01 12:08:26.093  7071  7118 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-01 12:08:26.093  7071  7118 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-01 12:08:26.093  6767  7117 D Compatibility: enabling receiver ResolveInfo{1da74c44 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-01 12:08:26.093  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-01 12:08:26.093  7071  7118 D elm:15121: MDMBridge.getInstance()
07-01 12:08:26.093  7071  7118 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-01 12:08:26.093  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 12:08:26.093  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.093  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.093  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.103  7080  7080 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-01 12:08:26.103  6767  7117 D Compatibility: enabling receiver ResolveInfo{1a10612d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-01 12:08:26.103  7071  7118 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-01 12:08:26.103  6788  7119 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 12:08:26.113  6767  7117 D Compatibility: enabling receiver ResolveInfo{2c634662 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-01 12:08:26.113  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-01 12:08:26.113  7120  7120 E Zygote  : MountEmulatedStorage()
,07-01 12:08:26.113  7120  7120 I libpersona: KNOX_SDCARD checking this for 10145
07-01 12:08:26.113  7120  7120 E Zygote  : v2
07-01 12:08:26.113  7120  7120 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.113  7120  7120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:26.113  1016  1474 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7120 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:26.113  7120  7120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.113  1016  1468 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-01 12:08:26.113  1016  1468 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
07-01 12:08:26.123  1016  1468 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.123  1016  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 12:08:26.123  1016  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-01 12:08:26.123  7120  7120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.123  6767  7117 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-01 12:08:26.133  2866  2866 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-01 12:08:26.133  2866  2866 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 12:08:26.133  2866  2866 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-01 12:08:26.133  2866  2866 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:08:26.133  2866  2866 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 12:08:26.133  2866  2866 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:26.133  2866  2866 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:26.133  2866  2866 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 12:08:26.133  2866  2866 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-01 12:08:26.133  1016  1220 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-01 12:08:26.133  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.143  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.143  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.143  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.143  1016  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.153  1016  1055 D PackageManager: delete codoeFile: ,
,07-01 12:08:26.163  7120  7120 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-01 12:08:26.163  7120  7120 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.163  7137  7137 E Zygote  : MountEmulatedStorage()
07-01 12:08:26.163  7137  7137 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:08:26.163  7137  7137 E Zygote  : v2
07-01 12:08:26.163  7137  7137 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.163  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.163  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.173  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.173  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.173  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-01 12:08:26.173  1016  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
07-01 12:08:26.173  1016  1055 D PackageManager: result of delete: 1{204878933}
07-01 12:08:26.173  1016  1220 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 12:08:26.183  6973  6973 D AndroidRuntime: Shutting down VM
,07-01 12:08:26.193  7071  7071 D elm:15121: ElmAgentService : onDestroy().
,07-01 12:08:26.193  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-01 12:08:26.193  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-01 12:08:26.193  1016  1055 D PackageManager: userId{-1}
07-01 12:08:26.193  1016  1055 D PackageManager: andCode{true}
,07-01 12:08:26.203  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.203  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.203  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.203  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.203  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.203  7137  7137 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.203  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.203  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 12:08:26.203  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:26.203  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:26.213  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.213  7152  7152 E Zygote  : MountEmulatedStorage()
,07-01 12:08:26.213  7152  7152 E Zygote  : v2
07-01 12:08:26.213  7152  7152 I libpersona: KNOX_SDCARD checking this for 10055
07-01 12:08:26.213  7152  7152 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.213  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.213  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:26.213  1016  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7152 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-01 12:08:26.223  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.223  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.233  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-01 12:08:26.243  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-01 12:08:26.243  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-01 12:08:26.243  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-01 12:08:26.243  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-01 12:08:26.243  1016  3564 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-01 12:08:26.253  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-01 12:08:26.253  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.253  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
07-01 12:08:26.253  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.253  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.263  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.263  7152  7152 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:26.263  1016  1469 I ActivityManager: Killing 6601:com.samsung.helphub/1000 (adj 15): empty #21
,07-01 12:08:26.263  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
,07-01 12:08:26.263  1016  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-01 12:08:26.263  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.263  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.263  1016  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.263  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-01 12:08:26.263  7137  7137 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:26.273  7120  7120 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-01 12:08:26.273  7120  7120 D ThemeInfoUtil: isCurrentFestival = false
,07-01 12:08:26.283  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.283  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.283  1016  3910 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:08:26.283  1016  3910 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.283  1016  3910 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.283  1016  3910 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.283  1016  3910 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-01 12:08:26.283  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.283  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
07-01 12:08:26.283  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.293  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.293  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.293  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.293  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.293  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.293  7137  7137 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-01 12:08:26.293  1016  3909 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-01 12:08:26.293  1016  3909 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-01 12:08:26.303  7168  7168 E Zygote  : MountEmulatedStorage(),
07-01 12:08:26.303  7168  7168 E Zygote  : v2
07-01 12:08:26.303  7168  7168 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:08:26.303  7168  7168 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.303  7168  7168 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.303  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-01 12:08:26.303  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-01 12:08:26.313  1016  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.313  1016  1220 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:26.313  1016  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.313  1016  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 12:08:26.313  7168  7168 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.313  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-01 12:08:26.313  1016  3909 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:08:26.313  7168  7168 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:08:26.313  1016  3909 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-01 12:08:26.313  1016  3909 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.313  1016  3909 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.313  1016  3909 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 12:08:26.313  1016  3905 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
07-01 12:08:26.313  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.313  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.313  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.313  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.323  7152  7152 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-01 12:08:26.333  7177  7177 E Zygote  : MountEmulatedStorage(),
07-01 12:08:26.333  7177  7177 I libpersona: KNOX_SDCARD checking this for 10148
07-01 12:08:26.333  7177  7177 E Zygote  : v2
07-01 12:08:26.333  7177  7177 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.333  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.333  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:26.333  1016  3905 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7177 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-01 12:08:26.333  1016  3905 I ActivityManager: Killing 6617:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-01 12:08:26.333  1016  3905 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
07-01 12:08:26.343  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:08:26.343  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.343  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.343  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.343  1016  3905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.353  7168  7168 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.353  7196  7196 E Zygote  : MountEmulatedStorage()
07-01 12:08:26.353  7196  7196 E Zygote  : v2
07-01 12:08:26.353  7196  7196 I libpersona: KNOX_SDCARD checking this for 10087
07-01 12:08:26.353  7196  7196 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.353  7168  7168 D ActivityThread: Added TimaKeyStore provider,
07-01 12:08:26.353  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.363  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-01 12:08:26.363  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,07-01 12:08:26.363  1016  3905 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7196 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:26.363  7152  7152 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-01 12:08:26.363  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.373  7152  7152 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-01 12:08:26.373  7152  7152 D UserAnalysis: Create SecureDbHelper
07-01 12:08:26.373  7177  7177 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.373  1016  3905 I ActivityManager: Killing 6583:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-01 12:08:26.383  1016  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:08:26.383  1016  1468 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.383  7152  7152 D IntelligenceServiceApplication: onCreate()
,07-01 12:08:26.383  7152  7152 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-01 12:08:26.393  1016  1468 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.393  1016  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.393  1016  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-01 12:08:26.393  6973  6973 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-01 12:08:26.403  1016  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,07-01 12:08:26.403  1016  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.403  1016  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.403  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.403  1016  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.403  1016  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.403  7196  7196 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.403  7152  7152 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-01 12:08:26.413  7214  7214 E Zygote  : MountEmulatedStorage()
07-01 12:08:26.413  7214  7214 I libpersona: KNOX_SDCARD checking this for 1000
,07-01 12:08:26.413  7214  7214 E Zygote  : v2
07-01 12:08:26.413  7214  7214 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.423  1016  1472 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-01 12:08:26.423  7214  7214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.423  1016  1472 I ActivityManager: Killing 6679:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-01 12:08:26.423  7214  7214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.423  7168  7168 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-01 12:08:26.423  7168  7168 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-01 12:08:26.423  7168  7168 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-01 12:08:26.423  7214  7214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.433  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-01 12:08:26.433  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-01 12:08:26.453  7214  7214 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-01 12:08:26.453  7214  7214 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.453  7168  7168 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-01 12:08:26.453  7168  7168 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 12:08:26.463  7177  7177 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,07-01 12:08:26.463  7168  7168 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 12:08:26.463  7168  7168 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-01 12:08:26.463  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-01 12:08:26.463  1016  3908 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,07-01 12:08:26.473  1016  3908 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.473  1016  3908 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.473  1016  3908 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.473  1016  3908 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.473  6788  7119 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 366 ms] updated apps [took 366 ms] 
,07-01 12:08:26.473  7214  7214 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:26.483  7231  7231 E Zygote  : MountEmulatedStorage(),
07-01 12:08:26.493  7231  7231 E Zygote  : v2
07-01 12:08:26.493  7231  7231 I libpersona: KNOX_SDCARD checking this for 10029
07-01 12:08:26.493  7231  7231 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.493  1016  3908 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7231 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,07-01 12:08:26.493  1016  1468 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-01 12:08:26.493  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.493  1016  1468 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.493  1016  1468 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.493  1016  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:26.493  1016  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
07-01 12:08:26.493  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:26.503  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
07-01 12:08:26.503  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,07-01 12:08:26.503  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.503  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.503  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.503  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.513  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
07-01 12:08:26.513  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,07-01 12:08:26.513  7214  7214 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/sm.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
07-01 12:08:26.523  7247  7247 I libpersona: KNOX_SDCARD checking this for 10152
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-01 12:08:26.523  7247  7247 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
07-01 12:08:26.523  7247  7247 E Zygote  : MountEmulatedStorage()
07-01 12:08:26.523  7247  7247 E Zygote  : v2
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-01 12:08:26.523  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
07-01 12:08:26.523  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
07-01 12:08:26.533  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.533  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:08:26.533  1016  1029 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7247 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-01 12:08:26.533  1016  1029 I ActivityManager: Killing 6698:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
07-01 12:08:26.543  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.543  7231  7231 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:26.553  7152  7152 D BluetoothAdapter: cancelDiscovery
07-01 12:08:26.563  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.563  7247  7247 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:26.563  7214  7214 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
07-01 12:08:26.563  4872  7213 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-01 12:08:26.563  4872  7213 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-01 12:08:26.563  3365  3374 D BluetoothAdapterProperties: mDiscovering is false
07-01 12:08:26.563  3365  3374 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,07-01 12:08:26.563  7152  7152 D BluetoothAdapter: cancelDiscovery = true
07-01 12:08:26.563  7152  7152 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
07-01 12:08:26.573  1016  1472 I ActivityManager: Killing 6732:com.wsomacp/u0a23 (adj 15): empty #21
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 12:08:26.573  7214  7214 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 12:08:26.573  7196  7196 E PhotosPlugin: Loading PhotosPlugin
07-01 12:08:26.573  1016  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
07-01 12:08:26.573  1016  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-01 12:08:26.573  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-01 12:08:26.583  7152  7152 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-01 12:08:26.583  7214  7214 D AndroidRuntime: Shutting down VM
07-01 12:08:26.583  7214  7214 E AndroidRuntime: FATAL EXCEPTION: main
07-01 12:08:26.583  7214  7214 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7214
07-01 12:08:26.583  7214  7214 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-01 12:08:26.583  7214  7214 E AndroidRuntime: 	... 9 more
07-01 12:08:26.583  1016  1476 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.583  1016  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.583  1016  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-01 12:08:26.583  7152  7152 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 12:08:26.583  7152  7152 E UserAnalysis: It failed to get the database for dump_log
07-01 12:08:26.583  7152  7152 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-01 12:08:26.583  7152  7152 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-01 12:08:26.583  7152  7152 E UserAnalysis: It failed to get the database for dump_log
07-01 12:08:26.583  1016  3908 I ActivityManager: Killing 6807:com.google.android.partnersetup/u0a14 (adj 15): empty #21
07-01 12:08:26.593  1016  1469 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
07-01 12:08:26.593  7214  7256 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-01 12:08:26.603  7214  7256 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
,07-01 12:08:26.613  1016  7263 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop179.tmp: open failed: EROFS (Read-only file system)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:26.613  1016  7263 E DropBoxManagerService: 	... 5 more
07-01 12:08:26.613  7247  7247 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-01 12:08:26.613  7247  7247 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10

```
