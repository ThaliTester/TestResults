#### Test 7578926851a8f91_thali01_samsung-SM-A300FU Logs


```
--------- beginning of system
06-30 12:51:48.835  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
06-30 12:51:49.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...
06-30 12:51:49.705   297   297 E SMD     : DCD OFF
,06-30 12:51:50.055  5969  5969 D AndroidRuntime: 
06-30 12:51:50.055  5969  5969 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 12:51:50.055  5969  5969 D AndroidRuntime: CheckJNI is OFF
06-30 12:51:50.055  5969  5969 D AndroidRuntime: readGMSProperty: start
06-30 12:51:50.055  5969  5969 D AndroidRuntime: readGMSProperty: already setted!!
06-30 12:51:50.055  5969  5969 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 12:51:50.055  5969  5969 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 12:51:50.055  5969  5969 D AndroidRuntime: readGMSProperty: end
06-30 12:51:50.055  5969  5969 D AndroidRuntime: addProductProperty: start
06-30 12:51:50.185  5969  5969 E AffinityControl: AffinityControl: registerfunction enter
06-30 12:51:50.205  5969  5969 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:51:50.215  1014  1120 E PersonaManagerService: inState():  stateMachine is null !!
06-30 12:51:50.215  1014  1120 I PersonaManagerService: PersonaId don't exist
06-30 12:51:50.215  1014  1120 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 12:51:50.225  1014  1120 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 12:51:50.235  1014  1120 W ActivityManager: mDVFSHelper.acquire()
06-30 12:51:50.245  1014  1120 D FocusedStackFrame: Set to : 0
06-30 12:51:50.255  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-30 12:51:50.255  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-30 12:51:50.255  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:50.255  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:50.255  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:50.255  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:50.265  1014  1120 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-30 12:51:50.265  1014  1120 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5980 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:51:50.265  1014  1120 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 12:51:50.265  5980  5980 I libpersona: KNOX_SDCARD checking this for 10151
06-30 12:51:50.265  1014  1120 D InputDispatcher: Focused application set to: xxxx
06-30 12:51:50.265  5980  5980 I libpersona: KNOX_SDCARD not a persona
06-30 12:51:50.265  1014  1120 D InputDispatcher: Focus left window: 1481
06-30 12:51:50.265  5980  5980 E Zygote  : MountEmulatedStorage()
06-30 12:51:50.265  5980  5980 E Zygote  : v2
06-30 12:51:50.265  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-30 12:51:50.265  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-30 12:51:50.265  5980  5980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:51:50.275   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
06-30 12:51:50.275  5980  5980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:51:50.275  5980  5980 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 12:51:50.275  5969  5969 D AndroidRuntime: Shutting down VM
06-30 12:51:50.295  5980  5980 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:51:50.295  5980  5980 D ActivityThread: Added TimaKeyStore provider
06-30 12:51:50.295  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 12:51:50.295  1014  3079 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-30 12:51:50.295  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:51:50.295  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 12:51:50.315  1014  3079 D PersonaManager: isKioskContainerExistOnDevice
06-30 12:51:50.375  1014  1393 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:51:50.375   258  1094 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
06-30 12:51:50.375  1014  1393 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:51:50.375  1014  1393 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:51:50.375  1014  1393 D BatteryService: stay LED for fully charged
06-30 12:51:50.375  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:51:50.375   258   422 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
06-30 12:51:50.375  1014  1014 I MotionRecognitionService: Plugged
06-30 12:51:50.375  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:51:50.375  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:51:50.375  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:51:50.385  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:51:50.385  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{222a31c3 token=android.os.BinderProxy@273f0e9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 12:51:50.385  1481  1481 D Launcher: onTrimMemory. Level: 20
06-30 12:51:50.385  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 12:51:50.385  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:50.385  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:50.405  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:50.445  5980  5980 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 12:51:50.455  5980  5980 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6342-6344)
06-30 12:51:50.455  5980  5980 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:50.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...
06-30 12:51:50.475  5980  5980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a3d3d47}
06-30 12:51:50.475  5980  5980 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:50.475  5980  5980 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:51:50.485  5969  5969 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-30 12:51:50.505  5980  5980 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:51:50.515  5980  5980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.515  5980  5980 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 12:51:50.525  5980  6000 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
06-30 12:51:50.535  5980  5980 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 12:51:50.535  5980  5980 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 12:51:50.535  5980  5980 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
06-30 12:51:50.545  5980  5980 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 12:51:50.545  5980  5980 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 12:51:50.545  5980  5980 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 12:51:50.545  5980  5980 I Adreno-EGL: Local Branch: 
06-30 12:51:50.545  5980  5980 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 12:51:50.545  5980  5980 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 12:51:50.545  5980  5980 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
06-30 12:51:50.665  5980  6009 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
06-30 12:51:50.715  5980  5980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.725  5980  5980 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:51:50.735  5980  5980 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-30 12:51:50.735  5980  5980 D PhoneWindow: *FMB* installDecor flags : -2139027200
06-30 12:51:50.735  5980  5980 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 12:51:50.745  5980  5980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.745  5980  5980 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.785  5980  6022 D OpenGLRenderer: Render dirty regions requested: true
06-30 12:51:50.795  1014  1496 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 12:51:50.795  1014  1496 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 12:51:50.795  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
06-30 12:51:50.795  1014  1496 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 12:51:50.795  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 12:51:50.805  5980  5980 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-30 12:51:50.805  5980  5980 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-30 12:51:50.805   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
06-30 12:51:50.825  1014  3078 D InputDispatcher: Focus entered window: 5980
06-30 12:51:50.825  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 12:51:50.825  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:51:50.825  5980  5980 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-30 12:51:50.825  5980  6022 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:51:50.835  5980  6022 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
06-30 12:51:50.835  5980  6022 D OpenGLRenderer: Enabling debug mode 0
06-30 12:51:50.845  5980  5980 V ActivityThread: updateVisibility : ActivityRecord{2da6570e token=android.os.BinderProxy@10c48a10 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 12:51:50.885  1014  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 12:51:50.885  1014  6025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 12:51:50.895  1172  1172 I StatusBar: Icon Only
06-30 12:51:50.895  1172  1172 D PanelView: There is/are notification(s) 
06-30 12:51:50.905  5980  5980 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 12:51:50.905  5980  5980 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10c48a10 time:116791
06-30 12:51:50.905  1014  1044 I ActivityManager: Displayed Component not be shown by security: +591ms (total +9s629ms)
06-30 12:51:50.905  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{238453b6 u0 com.test.thalitest/.MainActivity t81} time:116797
06-30 12:51:50.905  1014  1044 W ActivityManager: mDVFSHelper.release()
06-30 12:51:50.925   258   426 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
06-30 12:51:50.925   258   422 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
06-30 12:51:50.935  1795  1795 I SamsungIME: getCurrentCandidateView
06-30 12:51:50.975  5980  5980 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5980
06-30 12:51:51.035  1795  1795 D SamsungIME: Dismiss ExpandCandiate
06-30 12:51:51.105  5980  5980 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:51:51.185  1795  1795 I SamsungIME: getDebugLevel  : 0x4f4c
,06-30 12:51:51.205  5980  6027 D jxcore_app_log: JniHelper::setJavaVM(0xb72362f0), pthread_self() = -1217021600
,06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:51:51.215  5980  6027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18dc9fbe added. We now have 1 listener(s)
,06-30 12:51:51.215  5980  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,06-30 12:51:51.225  5980  6027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,06-30 12:51:51.225  5980  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 12:51:51.225  5980  6027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 12:51:51.225  1795  1795 I SamsungIME: getDebugLevel  : 0x4f4c
,06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:51:51.225  5980  6027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a135 added. We now have 1 listener(s)
06-30 12:51:51.225  5980  6027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 12:51:51.235  5980  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 12:51:51.235  5980  6027 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 12:51:51.235  5980  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 12:51:51.235  5980  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 12:51:51.235  5980  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:51:51.235  5980  6027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 12:51:51.235  5980  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 12:51:51.245  5980  6027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,06-30 12:51:51.245  5980  6027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:51:51.245  5980  6027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 12:51:51.245  5980  6027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 12:51:51.245  5980  6027 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 12:51:51.245  5980  6027 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 12:51:51.245  1795  1795 I SamsungIME: KeybaordView init() : load resources
,06-30 12:51:51.285  5980  5980 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,06-30 12:51:51.285  1795  1795 I SamsungIME: getCurrentKeyboard
06-30 12:51:51.285  1795  1795 I SamsungIME: getTextKeyboard
,06-30 12:51:51.305  1795  1795 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-30 12:51:51.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:51.765  5980  6033 W jxcore-log: Initializing JXcore engine
06-30 12:51:51.765  5980  6033 W jxcore-log: JXcore engine is ready
,06-30 12:51:51.825  1936  1936 E audit   : type=1400 msg=audit(1467283911.825:203): avc:  denied  { ioctl } for  pid=6033 comm="Thread-1090" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-30 12:51:51.825  1936  1936 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:51:51.825  1936  1936 E audit   : type=1300 msg=audit(1467283911.825:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f7028f8 items=0 ppid=317 ppcomm=main pid=6033 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1090" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 12:51:51.825  1936  1936 E audit   : type=1320 msg=audit(1467283911.825:203): 
,06-30 12:51:51.835  5980  6033 W jxcore-log: Starting JXcore engine
,06-30 12:51:51.945  5980  6033 W jxcore-log: Platform android
06-30 12:51:51.945  5980  6033 W jxcore-log: 
06-30 12:51:51.945  5980  6033 W jxcore-log: Process ARCH arm
06-30 12:51:51.945  5980  6033 W jxcore-log: 
,06-30 12:51:52.145  5980  6033 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:51:52.145  5980  6033 I jxcore-log: 
,06-30 12:51:52.145  5980  6033 W jxcore-log: JXcore engine is started
,06-30 12:51:52.155  5980  6027 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:51:52.155  5980  5980 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,06-30 12:51:52.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:51:52.695   297   297 E SMD     : DCD OFF,
,06-30 12:51:53.465   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-30 12:51:55.705   297   297 E SMD     : DCD OFF,
,06-30 12:51:56.375  1014  2720 D SSRM:n  : SIOP:: AP = 320
,06-30 12:51:58.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:51:58.705   297   297 E SMD     : DCD OFF,
,06-30 12:51:59.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:51:59.985  1014  1092 V AlarmManager: waitForAlarm result :8,
,06-30 12:52:00.305  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,06-30 12:52:00.435  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:00.435  1014  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:52:00.435  1014  1220 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:00.435  1014  1220 D BatteryService: stay LED for fully charged
06-30 12:52:00.435  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:00.435  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:52:00.435  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:00.435  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:00.435  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:00.445  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:52:00.445  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:00.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:00.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:00.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:00.465  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:01.225  1014  1046 I PowerManagerService: [PWL] Off : 75s ago
,06-30 12:52:01.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:01.705   297   297 E SMD     : DCD OFF,
,06-30 12:52:02.465   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:52:03.465   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,06-30 12:52:04.695  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
06-30 12:52:04.695  5980  6033 I jxcore-log: 
,06-30 12:52:04.695  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
06-30 12:52:04.695  5980  6033 I jxcore-log: 
,06-30 12:52:04.695  5980  6033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved",
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:04.695  5980  6033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:52:04.695  5980  6033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:04.695  5980  6033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 12:52:04.705  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 12:52:04.705  5980  6033 I jxcore-log: 
,06-30 12:52:04.705  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 12:52:04.705  5980  6033 I jxcore-log: 
,06-30 12:52:04.705   297   297 E SMD     : DCD OFF,
,06-30 12:52:05.135  5980  6033 I jxcore-log: Unit Test app is loaded,
06-30 12:52:05.135  5980  6033 I jxcore-log: 
,06-30 12:52:05.145  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
06-30 12:52:05.145  5980  6033 I jxcore-log: 
,06-30 12:52:05.155  5980  5980 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 12:52:05.155  1014  1391 D SecContentProvider: uri = 18 selection = isWifiEnabled
06-30 12:52:05.155  1014  1391 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
06-30 12:52:05.155  1014  1391 D SecContentProvider2: mCursor = null
,06-30 12:52:05.165  1014  1391 D WifiService: setWifiEnabled: true pid=5980, uid=10151
,06-30 12:52:05.165  1014  1391 W ActivityManager: Permission Denial: getCurrentUser() from pid=5980, uid=10151 requires android.permission.INTERACT_ACROSS_USERS
,06-30 12:52:05.165  1014  1391 W WifiService: Failed getting userId using ActivityManagerNative
06-30 12:52:05.165  1014  1391 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5980, uid=10151 requires android.permission.INTERACT_ACROSS_USERS
06-30 12:52:05.165  1014  1391 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23908)
06-30 12:52:05.165  1014  1391 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
06-30 12:52:05.165  1014  1391 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
06-30 12:52:05.165  1014  1391 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
06-30 12:52:05.165  1014  1391 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,06-30 12:52:05.165  1014  1391 D SettingsProvider: name = wifi_on
,06-30 12:52:05.175  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,06-30 12:52:05.175  1014  1393 I WifiService: disconnect: pid=5980, uid=10151
,06-30 12:52:05.175  5980  6033 D BluetoothAdapter: enable()
,06-30 12:52:05.235  1014  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=5980, uid=10151 requires android.permission.INTERACT_ACROSS_USERS,
,06-30 12:52:05.245  1014  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5980, uid=10151 requires android.permission.INTERACT_ACROSS_USERS
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23908)
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
06-30 12:52:05.245  1014  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
06-30 12:52:05.245  1014  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
06-30 12:52:05.245  1014  1480 D SettingsProvider: name = bluetooth_on
06-30 12:52:05.245  1014  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,06-30 12:52:05.245  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
06-30 12:52:05.245  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
06-30 12:52:05.245  5980  6033 I jxcore-log: My device name is: samsung-SM-A300FU
06-30 12:52:05.245  5980  6033 I jxcore-log: 
06-30 12:52:05.255  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,06-30 12:52:05.255  5980  6033 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 12:52:05.255  5980  6033 I jxcore-log: 
,06-30 12:52:05.265  2641  2697 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,06-30 12:52:05.265  2641  2697 D BluetoothAdapterProperties: Setting state to 11
06-30 12:52:05.265  2641  2697 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
06-30 12:52:05.265  2641  2697 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 12:52:05.265  2641  2697 D BluetoothAdapterService: updateAdapterState state is 11
,06-30 12:52:05.265  2641  2697 D BluetoothAdapterService: Autoconnection is available 
06-30 12:52:05.265  2641  2697 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
06-30 12:52:05.265  2641  2697 D BtConfig.SecureMode: isSecureModeOn:false
06-30 12:52:05.265  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
06-30 12:52:05.265  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,06-30 12:52:05.265  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 12:52:05.265  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
06-30 12:52:05.265  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,06-30 12:52:05.275  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
06-30 12:52:05.275  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,06-30 12:52:05.275  2641  2697 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
06-30 12:52:05.275  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,06-30 12:52:05.285  2641  2697 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
06-30 12:52:05.285  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 12:52:05.285  2641  2697 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,06-30 12:52:05.285  2641  2697 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
06-30 12:52:05.285  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
06-30 12:52:05.285  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
06-30 12:52:05.285  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,06-30 12:52:05.285  1795  1795 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 12:52:05.285  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,06-30 12:52:05.295  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
06-30 12:52:05.295  1172  1172 D BluetoothTile:  getBluetoothState : 11
,06-30 12:52:05.295  1014  3078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.295  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.295  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.295  1014  3078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.295  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,06-30 12:52:05.305  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
06-30 12:52:05.305  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.305  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.305  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.305  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.305  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
06-30 12:52:05.305  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,06-30 12:52:05.305  1014  3079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.305  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.305  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.305  1014  3079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.305  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
06-30 12:52:05.305  1172  1686 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 12:52:05.305  1172  1686 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
06-30 12:52:05.305  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
06-30 12:52:05.305  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,06-30 12:52:05.315  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 12:52:05.315  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.315  2641  2641 D HeadsetService: Received start request. Starting profile...
06-30 12:52:05.315  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.315  2641  2641 D HeadsetService: start()
06-30 12:52:05.315  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.315  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.315  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,06-30 12:52:05.315  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
06-30 12:52:05.315  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,06-30 12:52:05.315  2641  2641 I BluetoothHeadsetServiceJni: classInitNative: succeeds
06-30 12:52:05.315  1014  1519 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.315  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.315  2641  2641 D HeadsetStateMachine: make
,06-30 12:52:05.315  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.325  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.325  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.325  1014  1393 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,06-30 12:52:05.325  1014  1120 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
06-30 12:52:05.325  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
06-30 12:52:05.325  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
06-30 12:52:05.325  2641  2697 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
06-30 12:52:05.325  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,06-30 12:52:05.325  1014  3078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.335  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.335  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.335  1014  3078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.335  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.335  2641  2641 E HeadsetStateMachine: # of Max HF connection is 2
,06-30 12:52:05.335  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
06-30 12:52:05.335  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
06-30 12:52:05.335  2641  2697 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
06-30 12:52:05.335  1622  1622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 12:52:05.335  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.335  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.335  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.335  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.335  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
06-30 12:52:05.345  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
06-30 12:52:05.345  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
06-30 12:52:05.345  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
06-30 12:52:05.345  2641  2697 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
06-30 12:52:05.345  2641  2697 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
06-30 12:52:05.345  2641  2697 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,06-30 12:52:05.345  1014  1220 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
06-30 12:52:05.345  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
06-30 12:52:05.345  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.345  1014  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.345  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
06-30 12:52:05.345  4264  4264 D BluetoothNotiBroadcastReceiver: onReceive
06-30 12:52:05.355  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
06-30 12:52:05.355  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
06-30 12:52:05.355  1014  3078 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
06-30 12:52:05.355  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
06-30 12:52:05.355  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.355  1014  3078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.355  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
06-30 12:52:05.355  2641  2641 I bluedroid: get_profile_interface handsfree
06-30 12:52:05.375  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
06-30 12:52:05.375  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.375  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.375  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.375  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:05.385  6054  6054 E Zygote  : MountEmulatedStorage()
06-30 12:52:05.385  6054  6054 I libpersona: KNOX_SDCARD checking this for 10055
06-30 12:52:05.385  6054  6054 E Zygote  : v2
06-30 12:52:05.385  6054  6054 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:05.385  1014  1519 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6054 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
06-30 12:52:05.395  6054  6054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:05.405  6054  6054 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:05.405  6054  6054 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 12:52:05.405  2641  2641 I DualScoManager: Instantiating Dual Sco Manager
06-30 12:52:05.405  2641  2641 I DualScoManager: Set HeadsetServiceHelper
06-30 12:52:05.405  2641  2641 D BluetoothAtMessage: createCMTIContentObservers
06-30 12:52:05.415  1014  1496 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
06-30 12:52:05.415  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:05.415  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:05.415  1014  1496 D SettingsProvider: selectionArgs: false
06-30 12:52:05.415  1014  1496 D SettingsProvider: selectionArgs: 1002
06-30 12:52:05.415  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:05.415  1014  1496 D SettingsProvider: ret = -1
,06-30 12:52:05.415  1014  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,06-30 12:52:05.425  2641  6053 D HeadsetStateMachine: Enter Disconnected: -2
,06-30 12:52:05.425  2641  2641 D HeadsetService: mStartError = false
06-30 12:52:05.425  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.425  2641  6053 D HeadsetStateMachine: Clear mHeadsetBrsf
06-30 12:52:05.425  2641  6053 D HeadsetStateMachine: map size, before remove : 0
06-30 12:52:05.425  2641  6053 D HeadsetStateMachine: map size, after remove: 0
,06-30 12:52:05.425  1014  1014 D BluetoothA2dp: Proxy object connected
,06-30 12:52:05.435  2641  2641 D A2dpService: Received start request. Starting profile...
06-30 12:52:05.435  2641  2641 D A2dpService: start()
,06-30 12:52:05.435  6054  6054 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:05.435  6054  6054 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:05.435  2641  2641 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,06-30 12:52:05.435  2641  2641 I bluedroid: get_profile_interface avrcp
,06-30 12:52:05.435  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:05.445  2641  2641 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,06-30 12:52:05.465  2641  2641 I Avrcp   :  Updating now playing list upon AVRCP Start
,06-30 12:52:05.465  2641  2641 I BluetoothA2dpServiceJni: classInitNative: succeeds
,06-30 12:52:05.465  2641  2641 D A2dpStateMachine: make
,06-30 12:52:05.465  2641  6069 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,06-30 12:52:05.485  2641  6069 D BluetoothMediaBrowser: no now playing list
,06-30 12:52:05.485  2641  6069 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,06-30 12:52:05.485  2641  2641 I bluedroid: get_profile_interface a2dp
,06-30 12:52:05.485  2641  6071 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
06-30 12:52:05.485  2641  2641 E bt-btif : warning : media task started media_task_refcnt 1 
,06-30 12:52:05.485  2641  2641 D A2dpService: mStartError = false
,06-30 12:52:05.495  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.495  2641  2641 I BluetoothHidServiceJni: classInitNative: succeeds
,06-30 12:52:05.495  2641  6070 D A2dpStateMachine: Enter Disconnected: -2
,06-30 12:52:05.495  2641  2641 D HidService: Received start request. Starting profile...
,06-30 12:52:05.495  2641  2641 D HidService: start()
06-30 12:52:05.495  2641  2641 I bluedroid: get_profile_interface hidhost
06-30 12:52:05.495  2641  2641 D HidService: setHidService(): set to: null
06-30 12:52:05.495  2641  2641 D HidService: mStartError = false
,06-30 12:52:05.495  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.495  2641  2641 I BluetoothHealthServiceJni: classInitNative: succeeds
,06-30 12:52:05.505  2641  2641 D HealthService: Received start request. Starting profile...
,06-30 12:52:05.505  2641  2641 D HealthService: start()
,06-30 12:52:05.505  2641  2641 I bluedroid: get_profile_interface health
,06-30 12:52:05.505  2641  2641 D HealthService: mStartError = false
06-30 12:52:05.505  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.505  2641  2641 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,06-30 12:52:05.515  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,06-30 12:52:05.515  2641  2641 D PanService: Received start request. Starting profile...
06-30 12:52:05.515  2641  2641 D PanService: start()
,06-30 12:52:05.515  2641  2641 D BluetoothPanServiceJni: initializeNative(L110): pan
06-30 12:52:05.515  2641  2641 I bluedroid: get_profile_interface pan
,06-30 12:52:05.515  2641  2641 D PanService: mStartError = false
,06-30 12:52:05.515  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.525  2641  2641 D BluetoothMapService: Received start request. Starting profile...
,06-30 12:52:05.525  2641  2641 D BluetoothMapService: start()
,06-30 12:52:05.525  2641  2641 D BluetoothMapService: mStartError = false
,06-30 12:52:05.525  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.525  2641  2641 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,06-30 12:52:05.535  2641  2641 D SapService: Received start request. Starting profile...
,06-30 12:52:05.535  2641  2641 D SapService: start()
06-30 12:52:05.535  2641  2641 D BluetoothSAPServiceJni: initializeNative(L209): sap
06-30 12:52:05.535  2641  2641 I bluedroid: get_profile_interface sap
06-30 12:52:05.535  2641  2641 D SapService: mStartError = false
06-30 12:52:05.535  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:05.535  2641  2641 D HeadsetStateMachine: Proxy object connected
,06-30 12:52:05.535  2641  2641 D HeadsetStateMachine: Try to query the phonestate on bind
,06-30 12:52:05.535  1428  1450 I Telecom : BluetoothPhoneService: queryPhoneState
,06-30 12:52:05.535  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,06-30 12:52:05.535  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
06-30 12:52:05.545  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
06-30 12:52:05.545  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,06-30 12:52:05.565  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,06-30 12:52:05.575  1428  1428 W BluetoothHeadset: Proxy not attached to service
,06-30 12:52:05.575  1428  1450 I Telecom : BluetoothPhoneService: Result of Message : true
,06-30 12:52:05.575  2641  2641 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,06-30 12:52:05.575  2641  2641 D HeadsetPhoneState: sendDeviceDataStateChanged
06-30 12:52:05.575  2641  6053 D HeadsetStateMachine: Disconnected process message: 11
,06-30 12:52:05.575  2641  6053 D HeadsetStateMachine: Disconnected process message: 18
06-30 12:52:05.575  2641  2641 D HeadsetPhoneState: Signal level : previous=0 curr=4
06-30 12:52:05.575  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,06-30 12:52:05.575  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:52:05.575  2641  2641 D BluetoothA2dp: Proxy object connected
06-30 12:52:05.575  2641  2641 D BluetoothAdapterService: Bluetooth A2dp source service connected
06-30 12:52:05.575  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:05.575  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
06-30 12:52:05.575  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
06-30 12:52:05.575  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
06-30 12:52:05.575  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,06-30 12:52:05.575  2641  6053 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
06-30 12:52:05.575  2641  6053 D HeadsetStateMachine: Disconnected process message: 11
,06-30 12:52:05.585  1014  1026 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,06-30 12:52:05.585  6054  6054 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,06-30 12:52:05.585  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:05.585  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.585  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:05.585  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:05.605  6081  6081 E Zygote  : MountEmulatedStorage(),
06-30 12:52:05.605  6081  6081 E Zygote  : v2
06-30 12:52:05.605  6081  6081 I libpersona: KNOX_SDCARD checking this for 10141
06-30 12:52:05.605  6081  6081 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:05.605  6081  6081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:05.605  6081  6081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:05.605  6081  6081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 12:52:05.615  1014  1026 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6081 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,06-30 12:52:05.615  6054  6054 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,06-30 12:52:05.625  6054  6054 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-30 12:52:05.625  6054  6054 D UserAnalysis: Create SecureDbHelper
,06-30 12:52:05.625  6054  6054 D IntelligenceServiceApplication: onCreate()
,06-30 12:52:05.625  6081  6081 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:05.635  6081  6081 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:05.635  1014  1519 I ActivityManager: Killing 5600:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,06-30 12:52:05.645  6054  6054 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-30 12:52:05.655  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-30 12:52:05.655  6054  6054 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-30 12:52:05.655  6081  6081 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-30 12:52:05.655  6081  6081 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:05.655  6081  6081 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:05.655  6081  6081 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:52:05.665  6054  6054 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-30 12:52:05.715  1014  1041 D Tethering: interfaceAdded wlan0
,06-30 12:52:05.725  1014  1480 D RCPManagerService: exchangeData() failure , invalid userId,
,06-30 12:52:05.735  1014  1128 E Tethering: No numeric data
,06-30 12:52:05.735  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 12:52:05.745   281   949 I WifiHW  : wifi_change_fw_path(): fwpath = sta
06-30 12:52:05.745   281   949 D SoftapController: Softap fwReload - Ok
,06-30 12:52:05.745  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,06-30 12:52:05.745  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
06-30 12:52:05.745  1014  3078 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 12:52:05.745  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,06-30 12:52:05.745  1014  1122 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:05.745  1014  1128 D Tethering: clearTetheredNotification()
06-30 12:52:05.745  1014  1128 D Tethering: InitialState.processMessage what=4
,06-30 12:52:05.745  1014  1128 E Tethering: No numeric data
,06-30 12:52:05.755  1014  1041 D Tethering: interfaceAdded p2p0
06-30 12:52:05.755  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,06-30 12:52:05.755  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
06-30 12:52:05.755  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,06-30 12:52:05.755   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:05.755  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
06-30 12:52:05.755   281   945 D Netd    : getNetworkForDns: using netid 0 for uid 1000
06-30 12:52:05.755   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:05.755   281   945 D Netd    : getNetworkForDns: using netid 0 for uid 1000
06-30 12:52:05.755  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
06-30 12:52:05.755  1014  1128 D Tethering: clearTetheredNotification()
06-30 12:52:05.755  1014  1122 D NtpTrustedTime: forceRefresh Fail.
06-30 12:52:05.765  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,06-30 12:52:05.765  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,06-30 12:52:05.765  1172  1172 D HotspotTile: updateTetherState():false, false
,06-30 12:52:05.765  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
06-30 12:52:05.765  1172  1172 D HotspotTile: updateTetherState():false, false
,06-30 12:52:05.765  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,06-30 12:52:05.765   281   949 D CommandListener: Setting iface cfg
06-30 12:52:05.765   281   949 D CommandListener: Trying to bring down wlan0
,06-30 12:52:05.765  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
06-30 12:52:05.765   281   949 D CommandListener: Clearing all IP addresses on wlan0
,06-30 12:52:05.775  1014  1122 V NetworkStats: performPollLocked() took 13ms
,06-30 12:52:05.775  1014  1123 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:05.775  1014  1122 D NtpTrustedTime: forceRefresh() from cache miss
06-30 12:52:05.775  1014  1122 D NtpTrustedTime: forceRefresh Fail.
,06-30 12:52:05.775  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,06-30 12:52:05.775  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
06-30 12:52:05.775  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
06-30 12:52:05.775  1014  1123 D NtpTrustedTime: forceRefresh Fail.
,06-30 12:52:05.775  1014  1122 V NetworkStats: performPollLocked() took 3ms
,06-30 12:52:05.785  1014  1123 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:05.785  1014  1123 D NtpTrustedTime: forceRefresh Fail.
,06-30 12:52:05.805  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,06-30 12:52:05.805  2641  2641 E BluetoothAdapterService(977091911): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,06-30 12:52:05.805  2641  2697 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
06-30 12:52:05.805  2641  2697 I bluedroid: enable
,06-30 12:52:05.815  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,06-30 12:52:05.815  2641  2700 E bt-btif : Calling BTA_HhEnable
,06-30 12:52:05.815  2641  2700 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,06-30 12:52:05.815  2641  2700 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,06-30 12:52:05.815  2641  2700 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,06-30 12:52:05.815  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.815  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.815  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:05.815  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:05.815  2641  2700 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,06-30 12:52:05.815  2641  2700 E BluetoothServiceJni: populateRssiValuesNative
06-30 12:52:05.815  2641  2700 I bluedroid: getModelRssiValues
,06-30 12:52:05.815  2641  2700 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,06-30 12:52:05.815  2641  2700 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,06-30 12:52:05.825  6105  6105 E Zygote  : MountEmulatedStorage()
06-30 12:52:05.825  6105  6105 I libpersona: KNOX_SDCARD checking this for 10105
06-30 12:52:05.825  6105  6105 E Zygote  : v2
06-30 12:52:05.825  6105  6105 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:05.835  6105  6105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:05.835  1014  1479 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6105 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-30 12:52:05.835  6105  6105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:05.835  2641  2700 D BluetoothAdapterProperties: Name is: Galaxy A3
06-30 12:52:05.835  6105  6105 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-30 12:52:05.835  1014  1014 D SettingsProvider: name = bluetooth_name
06-30 12:52:05.835  1014  1519 I ActivityManager: Killing 5616:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,06-30 12:52:05.845  2641  2700 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-30 12:52:05.845  2641  2700 D BluetoothAdapterProperties: Scan Mode:20
06-30 12:52:05.845  2641  2700 D BluetoothAdapterProperties: Discoverable Timeout:120
06-30 12:52:05.845  2641  2700 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
06-30 12:52:05.845  2641  2700 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
06-30 12:52:05.845  2641  2700 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
06-30 12:52:05.845  2641  2700 E bt-btif : btif_sock_init: !radio_req && !rfc_init
06-30 12:52:05.845  2641  2700 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,06-30 12:52:05.845  5980  5980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 12:52:05.845  2641  2700 D IOP_DB_BT: db_open: db_open : handle 3028447248l, read 13894 bytes onto local cache
06-30 12:52:05.845  2641  2700 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,06-30 12:52:05.845  2641  2700 D IOP_DB_BT: db_query: result 1
06-30 12:52:05.845  2641  2700 I         : iop_db_open: iop_db_open status 0
,06-30 12:52:05.845  2641  2700 D bte_conf: Device ID record 1 : primary
,06-30 12:52:05.845  2641  2700 D bte_conf:   vendorId            = 0075
,06-30 12:52:05.855  2641  2700 D bte_conf:   vendorIdSource      = 0001
06-30 12:52:05.855  2641  2700 D bte_conf:   product             = 0100
06-30 12:52:05.855  2641  2700 D bte_conf:   version             = 0200
06-30 12:52:05.855  2641  2700 D bte_conf:   clientExecutableURL = 
06-30 12:52:05.855  2641  2700 D bte_conf:   serviceDescription  = 
06-30 12:52:05.855  2641  2700 D bte_conf:   documentationURL    = 
06-30 12:52:05.855  2641  2700 D bte_conf: bte_load_did_conf no section named DID2.
,06-30 12:52:05.855  2641  2700 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
06-30 12:52:05.855  2641  2700 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,06-30 12:52:05.855  2641  2697 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
06-30 12:52:05.855  2641  2697 D BluetoothAdapterProperties: ScanMode =  20
06-30 12:52:05.855  2641  2697 D BluetoothAdapterProperties: State =  11
06-30 12:52:05.855  1014  3079 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,06-30 12:52:05.855  2641  2697 D BluetoothAdapterProperties: Setting state to 12
06-30 12:52:05.855  2641  2697 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,06-30 12:52:05.855  6105  6105 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:05.855  6105  6105 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:05.855  2641  2700 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,06-30 12:52:05.865  2641  2700 D BluetoothAdapterProperties: Scan Mode:21
06-30 12:52:05.865  2641  2700 D BluetoothAdapterProperties: Discoverable Timeout:120
,06-30 12:52:05.865  1014  1496 D SettingsProvider: name = bluetooth_a2dp_sink_mode
06-30 12:52:05.865  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:05.865  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:05.865  1014  1496 D SettingsProvider: selectionArgs: false
06-30 12:52:05.865  1014  1496 D SettingsProvider: selectionArgs: 1002
06-30 12:52:05.865  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:05.865  1014  1496 D SettingsProvider: ret = -1
,06-30 12:52:05.865  1014  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,06-30 12:52:05.865  5980  5980 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,06-30 12:52:05.865  2641  2697 D BluetoothAdapterService: Bluetooth PBAP supproted is true
06-30 12:52:05.865  2641  2697 D BluetoothAdapterService: updateAdapterState state is 12
,06-30 12:52:05.875  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:05.875  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.875  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:05.875  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 12:52:05.875  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:05.885  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 12:52:05.885  1172  1924 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-30 12:52:05.885  2641  2697 D BluetoothAdapterService: Autoconnection is available 
,06-30 12:52:05.885  2641  2697 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
06-30 12:52:05.885  2641  2697 D BluetoothAdapterService: starting service from this receiver
,06-30 12:52:05.885  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,06-30 12:52:05.885  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,06-30 12:52:05.885  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,06-30 12:52:05.885  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:05.885  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:05.885  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:05.895  1172  1924 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
06-30 12:52:05.895  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,06-30 12:52:05.895  2641  2697 I BluetoothAdapterState: Entering On State from state = 11
,06-30 12:52:05.905  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 12:52:05.905  5980  5994 D BluetoothAdapter: onBluetoothStateChange: up=true
06-30 12:52:05.905  5980  5994 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-30 12:52:05.905  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
06-30 12:52:05.905  2641  2651 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-30 12:52:05.905  2641  2651 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-30 12:52:05.905  2641  2641 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,06-30 12:52:05.915  5980  5980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,06-30 12:52:05.925  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
06-30 12:52:05.925  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-30 12:52:05.925  1597  1614 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-30 12:52:05.925  1597  1614 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-30 12:52:05.925  2641  2651 D BluetoothA2dp: onBluetoothStateChange: up=true
,06-30 12:52:05.925  1428  1450 D BluetoothAdapter: onBluetoothStateChange: up=true
,06-30 12:52:05.925  1428  1450 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
06-30 12:52:05.925  1439  1715 D BluetoothAdapter: onBluetoothStateChange: up=true
06-30 12:52:05.925  1439  1715 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-30 12:52:05.935  1457  5756 D BluetoothAdapter: onBluetoothStateChange: up=true,
06-30 12:52:05.935  1457  5756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,06-30 12:52:05.935  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt,
06-30 12:52:05.935  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,06-30 12:52:05.935  1014  1496 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 12:52:05.945  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,06-30 12:52:05.945  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
06-30 12:52:05.945  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
06-30 12:52:05.945  1172  1172 D BluetoothTile:  onBluetoothStateChange:,
,06-30 12:52:05.945  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@16a135, true
,06-30 12:52:05.955  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,06-30 12:52:05.955  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
06-30 12:52:05.955  1172  1172 D BluetoothTile:  getBluetoothState : 12
,06-30 12:52:05.955  1428  1428 D BluetoothHeadset: registerMessageListener
,06-30 12:52:05.955  2641  2641 I BluetoothPbapService: Handler(): got msg=1
,06-30 12:52:05.965  2641  2651 D HeadsetService: registerMessageListener
,06-30 12:52:05.965  1795  1795 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,06-30 12:52:05.965  1014  1393 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 12:52:05.965  1172  1686 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 12:52:05.965  2641  2651 D HeadsetService: registerMessageListener
06-30 12:52:05.965  2641  6053 D HeadsetStateMachine: Disconnected process message: 70
06-30 12:52:05.965  2641  6053 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@30de5070
,06-30 12:52:05.975  1014  3079 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,06-30 12:52:05.975  6121  6121 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
06-30 12:52:05.975  6121  6121 I wpa_supplicant: Successfully initialized wpa_supplicant
,06-30 12:52:05.975  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
06-30 12:52:05.975  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,06-30 12:52:05.975  1014  1120 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
06-30 12:52:05.975  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,06-30 12:52:05.975  1172  1686 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 12:52:05.985  6121  6121 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,06-30 12:52:05.995  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,06-30 12:52:05.995  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,06-30 12:52:05.995  2641  6125 V BluetoothPbapService: PBAP Service initSocket try: 0,
06-30 12:52:05.995  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
06-30 12:52:05.995  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,06-30 12:52:05.995  1172  1686 D BluetoothTile:  handleUpdatestate:false name:null
,06-30 12:52:06.015  6121  6121 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,06-30 12:52:06.015  2641  6127 D BluetoothMapMasInstance: set MAP SDP message type : 1
,06-30 12:52:06.015  4264  4264 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 12:52:06.025  1014  1519 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 12:52:06.025  2641  6053 D HeadsetStateMachine: Disconnected process message: 9
,06-30 12:52:06.025  2641  6053 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
06-30 12:52:06.025  5980  5980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:52:06.025   398   398 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 6121
06-30 12:52:06.025   398   398 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
06-30 12:52:06.025  6121  6121 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
06-30 12:52:06.025  6121  6121 I wpa_supplicant: ssSupport state is = 1
06-30 12:52:06.025  6121  6121 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
06-30 12:52:06.025  6121  6121 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 12:52:06.025   398   398 I SecureStorage: [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 6121
06-30 12:52:06.025   398   398 I SecureStorage: [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
06-30 12:52:06.025  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
06-30 12:52:06.025  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
06-30 12:52:06.025  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
06-30 12:52:06.035  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 12:52:06.025  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.035  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.035  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.035  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.035  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 12:52:06.035  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,06-30 12:52:06.035  1172  1686 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,06-30 12:52:06.035  1172  1172 D HotspotTile: onReceive : 2, 0
,06-30 12:52:06.035   288   732 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,06-30 12:52:06.035   288   732 V voice   : voice_set_parameters: enter: A2dpSuspended=false
06-30 12:52:06.035   288   732 V voice   : voice_set_parameters: exit with code(-2)
,06-30 12:52:06.035   288   732 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
06-30 12:52:06.035   288   732 V msm8974_platform: platform_set_parameters: exit with code(-2)
06-30 12:52:06.035   288   732 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,06-30 12:52:06.035   288   732 V audio_hw_primary: adev_set_parameters: exit
,06-30 12:52:06.045  2641  6125 D BluetoothSocket: bindListen(): myUserId = 0
,06-30 12:52:06.045  2641  6125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 12:52:06.045  2641  6053 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,06-30 12:52:06.045  2641  6125 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,06-30 12:52:06.045  2641  6125 D BluetoothSocket: bindListen(), new LocalSocket 
,06-30 12:52:06.055  2641  6125 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,06-30 12:52:06.055  2641  6125 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ca8fe9
,06-30 12:52:06.055  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 12:52:06.055  2641  6125 D BluetoothSocket: channel: 19
,06-30 12:52:06.055  2641  6125 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,06-30 12:52:06.055  2641  6127 D BluetoothSocket: bindListen(): myUserId = 0
,06-30 12:52:06.055  2641  6127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 12:52:06.065  2641  6127 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,06-30 12:52:06.065  2641  6127 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 12:52:06.065  2641  6127 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 12:52:06.065  2641  6127 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@224e746e
06-30 12:52:06.065  2641  6127 D BluetoothSocket: channel: 5
,06-30 12:52:06.085  1014  1480 I art     : Explicit concurrent mark sweep GC freed 38141(2MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 22MB/33MB, paused 3.481ms total 205.975ms,
,06-30 12:52:06.105  5758  5771 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,06-30 12:52:06.115  5758  6129 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
06-30 12:52:06.115  5758  6129 D BadgeProvider: sendNotify, [notify] : null
06-30 12:52:06.115  5758  6129 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
06-30 12:52:06.115  5758  6129 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-30 12:52:06.115  5758  6129 D BadgeProvider: update, [UpdateCount] : 1
,06-30 12:52:06.125  1481  1481 D Launcher.Model: reloadBadges entered.
,06-30 12:52:06.265   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,06-30 12:52:06.275  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)Processing data has been completed
,06-30 12:52:06.275  6121  6121 I wpa_supplicant: Ctrl_iface: loading cred from phone
06-30 12:52:06.275  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,06-30 12:52:06.295  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
,06-30 12:52:06.295   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6121
06-30 12:52:06.295   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
06-30 12:52:06.295  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
06-30 12:52:06.295  6121  6121 I wpa_supplicant: ssSupport state is = 1
,06-30 12:52:06.305  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,06-30 12:52:06.305  6121  6121 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 12:52:06.305  6121  6121 E wpa_supplicant: SIM READ ERROR
06-30 12:52:06.305  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 12:52:06.305  6121  6121 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 12:52:06.305  6121  6121 E wpa_supplicant: SIM READ ERROR
06-30 12:52:06.305  6121  6121 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 12:52:06.305  6121  6121 I wpa_supplicant: wpa_default_ap_write_once
06-30 12:52:06.305  6121  6121 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 12:52:06.305  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 12:52:06.305  6121  6121 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
06-30 12:52:06.305  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 12:52:06.305  6121  6121 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,06-30 12:52:06.305  6121  6121 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,06-30 12:52:06.305  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,06-30 12:52:06.305  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,06-30 12:52:06.305  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,06-30 12:52:06.385  6121  6121 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,06-30 12:52:06.395  1014  2720 D SSRM:n  : SIOP:: AP = 330
,06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=287 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=277 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.k.a(PG:2107)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.k.c(PG:1187)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.k.b(PG:14147)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.k.c(PG:583)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.v.a(PG:1206)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.y.a(PG:2233)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.e.b(PG:170)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.r.e.b(PG:13188)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.435  1014  1393 I ActivityManager: Killing 5663:com.sec.pcw.device/1000 (adj 15): empty #21
06-30 12:52:06.435  6105  6105 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.File.doAccess(File.java:283)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.io.File.exists(File.java:363)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 12:52:06.435  6105  6105 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 12:52:06.465  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
06-30 12:52:06.465  1014  3079 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
06-30 12:52:06.465  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
06-30 12:52:06.465  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.465  1014  3079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.465  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
06-30 12:52:06.465  1622  1622 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
06-30 12:52:06.485  6121  6121 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
06-30 12:52:06.485  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,06-30 12:52:06.495  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
06-30 12:52:06.495  1014  1391 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
06-30 12:52:06.495  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
06-30 12:52:06.505  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
06-30 12:52:06.505  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
06-30 12:52:06.505   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6121
06-30 12:52:06.505   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
06-30 12:52:06.505  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
06-30 12:52:06.505  6121  6121 I wpa_supplicant: ssSupport state is = 1
06-30 12:52:06.505  6121  6121 I wpa_supplicant: Ctrl_iface: loading cred from phone
06-30 12:52:06.505  4264  4264 D LocalBluetoothProfileManager: Adding local A2DP profile
06-30 12:52:06.505  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
06-30 12:52:06.515  4264  4264 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
06-30 12:52:06.515  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)This device supports Secure Storage
06-30 12:52:06.515  1014  1391 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
06-30 12:52:06.515  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
06-30 12:52:06.515   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6121
06-30 12:52:06.525   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
06-30 12:52:06.525  6121  6121 I SecureStorage: [INFO]: SPID(0x00000001)SS Daemon is running
06-30 12:52:06.525  6121  6121 I wpa_supplicant: ssSupport state is = 1
06-30 12:52:06.525  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 12:52:06.525  6121  6121 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 12:52:06.525  6121  6121 E wpa_supplicant: SIM READ ERROR
06-30 12:52:06.525  6121  6121 I wpa_supplicant: wpa_default_ap_write_once
06-30 12:52:06.525  6121  6121 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
06-30 12:52:06.525  6121  6121 I wpa_supplicant: rfkill: Cannot open RFKILL control device
06-30 12:52:06.525  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.525  1014  1391 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.525  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
06-30 12:52:06.525  4264  4264 D LocalBluetoothProfileManager: Adding local HEADSET profile
06-30 12:52:06.525  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
06-30 12:52:06.525  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
06-30 12:52:06.525  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
06-30 12:52:06.525  4264  4264 E BluetoothHeadset: BTStateChangeCB is registed
06-30 12:52:06.525  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
06-30 12:52:06.525  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
06-30 12:52:06.525  4264  4264 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
06-30 12:52:06.535  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
06-30 12:52:06.535  1014  1026 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
06-30 12:52:06.535  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,06-30 12:52:06.535  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:06.535  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 12:52:06.535  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.535  4264  4264 E BluetoothHeadset: BluetoothHeadset service is binded
,06-30 12:52:06.545  4264  4264 D BluetoothMap: Create BluetoothMap proxy object
,06-30 12:52:06.545  1014  1391 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,06-30 12:52:06.545  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.545  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:06.545  1014  1391 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.545  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.555  1014  1519 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
06-30 12:52:06.555  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.555  6105  6130 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
06-30 12:52:06.555  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.555  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.555  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.555  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,06-30 12:52:06.555  1014  1120 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,06-30 12:52:06.555  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.565  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:06.565  1014  1120 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 12:52:06.565  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.565  4264  4264 D Bluetoothsap: bindService called to Bluetooth SAP Service
,06-30 12:52:06.565  1014  1391 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
06-30 12:52:06.565  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.565  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.565  1014  1391 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.565  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.575  1014  1220 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,06-30 12:52:06.575  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.575  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.575  1014  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.575  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,06-30 12:52:06.575  4264  4264 D LocalBluetoothProfileManager: PANU : true
,06-30 12:52:06.575  4264  4264 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
06-30 12:52:06.575  4264  4264 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,06-30 12:52:06.585  6121  6121 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
06-30 12:52:06.585  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,06-30 12:52:06.585  4264  4264 D DockEventReceiver: finishStartingService: stopping service
,06-30 12:52:06.585  4264  4264 D BluetoothNotiBroadcastReceiver: onReceive
,06-30 12:52:06.585  4264  4264 D BluetoothA2dp: Proxy object connected
06-30 12:52:06.585  4264  4264 D A2dpProfile: Bluetooth service connected
,06-30 12:52:06.585  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:06.585  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.585  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:06.585  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:06.595  4264  4264 D HeadsetProfile: Bluetooth service connected
,06-30 12:52:06.595  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,06-30 12:52:06.595  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,06-30 12:52:06.595  4264  4264 D BluetoothMap: Proxy object connected
06-30 12:52:06.595  4264  4264 D MapProfile: Bluetooth service connected
,06-30 12:52:06.595  4264  4264 D BluetoothMap: getConnectedDevices()
,06-30 12:52:06.605  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a3d3d47
,06-30 12:52:06.605  2641  2641 D BtConfig.SecureMode: isSecureModeOn:false
,06-30 12:52:06.605  1014  1519 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
06-30 12:52:06.605  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,06-30 12:52:06.605  4264  4264 D BluetoothPbap: Proxy object connected
06-30 12:52:06.605  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:06.605  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.605  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
06-30 12:52:06.605  4264  4264 D PbapServerProfile: Bluetooth service connected
06-30 12:52:06.605  4264  4264 D Bluetoothsap: BluetoothSAP Proxy object connected
06-30 12:52:06.605  4264  4264 D SapProfile: Bluetooth service connected
06-30 12:52:06.605  4264  4264 D Bluetoothsap: getConnectedDevices()
,06-30 12:52:06.615  4264  4264 D BluetoothInputDevice: Proxy object connected,
06-30 12:52:06.615  4264  4264 D HidProfile: Bluetooth service connected
,06-30 12:52:06.625  4264  4264 D BluetoothPan: BluetoothPAN Proxy object connected
06-30 12:52:06.625  4264  4264 D PanProfile: Bluetooth service connected
,06-30 12:52:06.625  1014  1120 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,06-30 12:52:06.625  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,06-30 12:52:06.625  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:06.625  1014  1120 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.625  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,06-30 12:52:06.635  3823  3823 I Hs20UtilService: Starting #2
,06-30 12:52:06.635  1014  1393 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,06-30 12:52:06.635  3823  3843 I Hs20UtilService: Message received 5011
,06-30 12:52:06.635  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:06.635  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:06.635  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:06.635  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.635  6121  6121 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
06-30 12:52:06.635  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
06-30 12:52:06.635  6121  6121 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 12:52:06.645  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,06-30 12:52:06.645  6146  6146 E Zygote  : MountEmulatedStorage()
06-30 12:52:06.645  6146  6146 E Zygote  : v2
06-30 12:52:06.645  6146  6146 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:06.645  6146  6146 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:06.655  6146  6146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:06.655  6146  6146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:06.655  6146  6146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 12:52:06.655  1014  1393 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6146 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 12:52:06.655  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,06-30 12:52:06.665  6121  6121 I wpa_supplicant: HOTSPOT20_ENABLE called
06-30 12:52:06.665  6121  6121 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
06-30 12:52:06.665  6121  6121 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
06-30 12:52:06.665  6121  6121 E wpa_supplicant: SIM READ ERROR
06-30 12:52:06.665  6121  6121 I wpa_supplicant: Blacklist: Clear (all) 
,06-30 12:52:06.665  1014  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,06-30 12:52:06.675  2641  6160 D BluetoothSocket: bindListen(): myUserId = 0
06-30 12:52:06.675  2641  6160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,06-30 12:52:06.675  6121  6121 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,06-30 12:52:06.675  2641  6160 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
06-30 12:52:06.675  2641  6160 D BluetoothSocket: bindListen(), new LocalSocket 
06-30 12:52:06.675  2641  6160 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
06-30 12:52:06.675  2641  6160 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@287bd88
06-30 12:52:06.675  2641  6160 D BluetoothSocket: channel: 12
06-30 12:52:06.675  2641  6160 I BtOppRfcommListener: Accept thread started.
,06-30 12:52:06.685  6121  6121 I wpa_supplicant: Skip scan - bUseNetwork false
,06-30 12:52:06.685  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
06-30 12:52:06.685  6146  6146 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:06.685  6146  6146 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:06.705  1014  1125 E WifiConfigStore: Not a HS20
,06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 12:52:06.705  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.705  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.705  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:06.705  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 12:52:06.705  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
06-30 12:52:06.705  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
06-30 12:52:06.705  1172  1686 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
06-30 12:52:06.705  1172  1172 D HotspotTile: onReceive : 3, 0
,06-30 12:52:06.705  4264  4264 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,06-30 12:52:06.715  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
06-30 12:52:06.715  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,06-30 12:52:06.715  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:06.715  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 12:52:06.715  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,06-30 12:52:06.725  5980  5980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,06-30 12:52:06.725  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
06-30 12:52:06.725  6121  6121 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
06-30 12:52:06.725  6121  6121 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,06-30 12:52:06.725  6121  6121 I wpa_supplicant: reset timer : RESET_TIMER 0
06-30 12:52:06.725  6121  6121 I wpa_supplicant: P2P: Current p2p state = IDLE
06-30 12:52:06.725  6121  6121 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
06-30 12:52:06.725  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
06-30 12:52:06.725  6121  6121 I wpa_supplicant: First Scan Start
06-30 12:52:06.725  6121  6121 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,06-30 12:52:06.725  1014  1125 D WifiNative-wlan0: Setting external_sim to 1,
,06-30 12:52:06.725  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
06-30 12:52:06.725  1014  1125 I WifiNative-HAL: startHal
06-30 12:52:06.725  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9f49088c
06-30 12:52:06.725  1014  1125 I WifiNative-HAL: Could not start hal
,06-30 12:52:06.735  1014  1125 E WifiNative-wlan0: do suspend true,
,06-30 12:52:06.735  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
06-30 12:52:06.735  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
06-30 12:52:06.735  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
06-30 12:52:06.735  1014  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
06-30 12:52:06.735  1014  1149 I WifiNative-HAL: startHal
06-30 12:52:06.735  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e4509bc
06-30 12:52:06.735  1014  1149 I WifiNative-HAL: Could not start hal
06-30 12:52:06.735  1014  1149 E WifiScanningService: could not start HAL
,06-30 12:52:06.745   281   949 D CommandListener: Setting iface cfg
06-30 12:52:06.745   281   949 D CommandListener: Trying to bring up p2p0
,06-30 12:52:06.745  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,06-30 12:52:06.745  1014  1014 D RttService: SCAN_AVAILABLE : 3
06-30 12:52:06.745  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,06-30 12:52:06.745  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
06-30 12:52:06.745  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
06-30 12:52:06.745  1014  1125 E WifiNative-wlan0: invaild command id : 215
,06-30 12:52:06.745  1014  1124 D WifiP2pService: P2pEnablingState
,06-30 12:52:06.745  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,06-30 12:52:06.745  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-30 12:52:06.745  1014  1124 D WifiP2pService: P2p socket connection successful
06-30 12:52:06.745  6121  6121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
06-30 12:52:06.745  1014  1124 D WifiP2pService: P2pEnabledState
,06-30 12:52:06.745  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,06-30 12:52:06.755  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
06-30 12:52:06.755  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
06-30 12:52:06.755  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,06-30 12:52:06.755  1014  1044 D WifiDisplayController: disconnect
06-30 12:52:06.755  6121  6121 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
06-30 12:52:06.755  1014  1044 D WifiDisplayController: updateConnection
06-30 12:52:06.755  1014  1125 E WifiStateMachine: Failed to set frequency band 0
06-30 12:52:06.755  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,06-30 12:52:06.755  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 12:52:06.755  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:06.755  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
06-30 12:52:06.755  1014  1125 D SecContentProvider2: mCursor = null
06-30 12:52:06.755  1014  3079 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
06-30 12:52:06.755  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
06-30 12:52:06.755  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:06.755  1014  1125 D SecContentProvider2: mCursor = null
06-30 12:52:06.755  1014  1124 D WifiP2pService: create mNetworkAgent
,06-30 12:52:06.775  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,06-30 12:52:06.775  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 12:52:06.775  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:52:06.775  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 12:52:06.775  6146  6146 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 12:52:06.775  6146  6146 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 12:52:06.775  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,06-30 12:52:06.775  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,06-30 12:52:06.785  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,06-30 12:52:06.785  1014  1127 E ConnectivityService: updateNetworkInfo()
,06-30 12:52:06.785  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 12:52:06.785  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,06-30 12:52:06.785  1014  1026 I ActivityManager: Killing 5700:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,06-30 12:52:06.795  1014  1124 D WifiP2pService: DeviceAddress: 0a:75:42
,06-30 12:52:06.795  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  secondary type: null
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  wps: 0
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  grpcapab: 0
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  devcapab: 0
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  status: 3
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  wfdInfo: null
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  groupownerAddress: null
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  GOdeviceName: null
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  interfaceAddress: 
06-30 12:52:06.795  1014  1044 D WifiDisplayController:  SConnectInfo : null
,06-30 12:52:06.795  1014  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
06-30 12:52:06.795  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,06-30 12:52:06.795  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:06.795  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:06.795  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,06-30 12:52:06.805  3823  3823 I Hs20UtilService: Starting #3
,06-30 12:52:06.805  3823  3843 I Hs20UtilService: Message received 5011
,06-30 12:52:06.805  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
06-30 12:52:06.805  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
06-30 12:52:06.805  1014  1125 E WifiNative-wlan0: invaild command id : 215
,06-30 12:52:06.805  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,06-30 12:52:06.805  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 12:52:06.805  6146  6146 D SecurityLogAgent: StateMachine : Current State = 1
06-30 12:52:06.805  6146  6146 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 12:52:06.815  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,06-30 12:52:06.815  1014  1124 D WifiP2pService: InactiveState
,06-30 12:52:06.815  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,06-30 12:52:06.815  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-30 12:52:06.825  6121  6121 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,06-30 12:52:06.825  1014  1127 E ConnectivityService: updateNetworkInfo()
,06-30 12:52:06.825  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,06-30 12:52:06.825  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,06-30 12:52:06.825  4264  4264 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,06-30 12:52:06.835  4264  4264 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 12:52:06.835  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 12:52:06.835  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,06-30 12:52:06.835  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,06-30 12:52:06.835  4264  4264 I NearbySettings: MountReceiver.onReceive - Set preference state off
,06-30 12:52:06.835  4264  4318 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 12:52:06.835  1014  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,06-30 12:52:06.835  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.835  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.835  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.835  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.855  6170  6170 E Zygote  : MountEmulatedStorage()
06-30 12:52:06.855  6170  6170 I libpersona: KNOX_SDCARD checking this for 10064
06-30 12:52:06.855  6170  6170 E Zygote  : v2
06-30 12:52:06.855  6170  6170 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:06.855  6170  6170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:06.855  1014  1496 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6170 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:52:06.855  6170  6170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:06.855  6170  6170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 12:52:06.875  6170  6170 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:06.875  6170  6170 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:06.895  6170  6170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:52:06.905  6170  6170 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 12:52:06.905  6170  6170 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,06-30 12:52:06.935  6170  6170 D FileShare-Client: Outbound.stopDelayTimer - 
,06-30 12:52:06.945  1014  3078 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,06-30 12:52:06.945  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.945  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.945  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.945  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:06.955  1014  3078 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6185 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
06-30 12:52:06.955  6185  6185 E Zygote  : MountEmulatedStorage()
,06-30 12:52:06.955  6185  6185 I libpersona: KNOX_SDCARD checking this for 10065
06-30 12:52:06.955  6185  6185 E Zygote  : v2
,06-30 12:52:06.955  6185  6185 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:06.955  6185  6185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:06.965  1014  3078 I ActivityManager: Killing 5685:com.android.mms/u0a41 (adj 15): empty #21,
,06-30 12:52:06.965  6185  6185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:06.965  6185  6185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:06.985  6185  6185 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:06.985  6185  6185 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:07.015  6185  6185 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,06-30 12:52:07.015  1014  1519 I ActivityManager: Killing 5758:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,06-30 12:52:07.045  1014  1220 D CountryDetector: No listener is left
,06-30 12:52:07.705   297   297 E SMD     : DCD OFF
,06-30 12:52:08.065  6121  6121 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,06-30 12:52:08.065  6121  6121 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
06-30 12:52:08.065  6121  6121 I wpa_supplicant: Trying to associate with SSID '517273716330627261'
06-30 12:52:08.065  6121  6121 I wpa_supplicant: Trying to associate with  '0bra'
06-30 12:52:08.065  6121  6121 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
06-30 12:52:08.065  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=517273716330627261,
06-30 12:52:08.065  1014  6145 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'Qrsqc0bra'
06-30 12:52:08.065  1014  1125 I WifiNative-HAL: startHal,
06-30 12:52:08.065  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9f4908ac
06-30 12:52:08.065  1014  1125 I WifiNative-HAL: Could not start hal,
,06-30 12:52:08.075  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:08.075  1014  1125 D SecContentProvider2: mCursor = null
,06-30 12:52:08.165  6121  6121 E wpa_supplicant: Cmd 35605 not handled
,06-30 12:52:08.165  6121  6121 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
06-30 12:52:08.165  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=517273716330627261
,06-30 12:52:08.165  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
06-30 12:52:08.165  6121  6121 I wpa_supplicant: Associated with 84.CE.70
06-30 12:52:08.165  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
06-30 12:52:08.165  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
06-30 12:52:08.165  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
06-30 12:52:08.165  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,06-30 12:52:08.165  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,06-30 12:52:08.175  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,06-30 12:52:08.175  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 12:52:08.175  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:08.175  1014  1125 D SecContentProvider2: mCursor = null
,06-30 12:52:08.175  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 12:52:08.175  1014  1128 E Tethering: No numeric data
,06-30 12:52:08.175  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,06-30 12:52:08.175  1014  1122 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:08.175   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:08.175   281   945 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 12:52:08.175  1014  1128 D Tethering: clearTetheredNotification()
,06-30 12:52:08.185  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
06-30 12:52:08.185  1172  1172 D HotspotTile: updateTetherState():false, false
,06-30 12:52:08.185   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:08.185   281   945 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 12:52:08.185  1014  1122 D NtpTrustedTime: forceRefresh Fail.
,06-30 12:52:08.185  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,06-30 12:52:08.185  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,06-30 12:52:08.185  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,06-30 12:52:08.185  1014  1122 V NetworkStats: performPollLocked() took 5ms
,06-30 12:52:08.185  1014  1123 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:08.185  1014  1123 D NtpTrustedTime: forceRefresh Fail.
,06-30 12:52:08.215  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:08.215  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-STARTED EAP authentication started
,06-30 12:52:08.245  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:08.245  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-PROPOSED-METHOD vendor=0 method=17 -> NAK
,06-30 12:52:08.285  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:08.285  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-PROPOSED-METHOD vendor=0 method=25
,06-30 12:52:08.285  6121  6121 W wpa_supplicant: set_parms secpkcs11 ENGINE: Engine ID : NULL
,06-30 12:52:08.285  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-METHOD EAP vendor 0 method 25 (PEAP) selected
,06-30 12:52:08.335  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:08.385  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:08.425  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:08.425  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-PEER-CERT depth=1 subject='/C=US/ST=Wisconsin/O=Rockwell Automation/OU=Rockwell Automation'
06-30 12:52:08.425  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-PEER-CERT depth=1 subject='/C=US/ST=Wisconsin/O=Rockwell Automation/OU=Rockwell Automation'
,06-30 12:52:08.425  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-PEER-CERT depth=0 subject='/CN=eunlamtacs098.emea.home.ra-int.com'
,06-30 12:52:08.495  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:08.535  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:08.575  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:08.825  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:10.435  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:10.485  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 12:52:10.485  6121  6121 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-SUCCESS EAP authentication completed successfully
,06-30 12:52:10.485  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:10.485  6121  6121 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
06-30 12:52:10.485  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=84.CE.70 SSID=517273716330627261
,06-30 12:52:10.485  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:10.485  1014  1125 D SecContentProvider2: mCursor = null
,06-30 12:52:10.495  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:10.495  1014  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:52:10.495  1014  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:10.495  1014  1480 D BatteryService: stay LED for fully charged
06-30 12:52:10.495  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:10.495  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:52:10.495  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:10.505  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:10.505  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:52:10.505  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:52:10.505  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:10.515  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:10.515  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:10.525  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 12:52:10.525  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 12:52:10.525  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,06-30 12:52:10.525  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=84.CE.70 SSID=517273716330627261
06-30 12:52:10.525  6121  6121 I wpa_supplicant: wlan0: WPA: Key negotiation completed with 84:b2:61:1a:ce:70 [PTK=CCMP GTK=CCMP]
06-30 12:52:10.525  6121  6121 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-30 12:52:10.525  6121  6121 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to 84.CE.70 completed (auth) [id=0 id_str=]
,06-30 12:52:10.525  6121  6121 I wpa_supplicant: Blacklist: Clear (temp) 
06-30 12:52:10.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:10.525  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=84.CE.70 SSID=517273716330627261
06-30 12:52:10.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:10.525  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 12:52:10.525  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
06-30 12:52:10.525  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 12:52:10.525  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:10.535  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,06-30 12:52:10.535  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,06-30 12:52:10.545  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "Qrsqc0bra", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,06-30 12:52:10.545  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
06-30 12:52:10.545  1014  1127 E ConnectivityService: updateNetworkInfo()
06-30 12:52:10.545  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,06-30 12:52:10.545  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "Qrsqc0bra"WPA_EAP to any
,06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 12:52:10.555  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 12:52:10.555  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
06-30 12:52:10.555  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:10.555  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
06-30 12:52:10.555  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.555  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.555  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:10.555  3823  3823 I Hs20UtilService: Starting #4
06-30 12:52:10.555  3823  3843 I Hs20UtilService: Message received 5007
,06-30 12:52:10.555  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "Qrsqc0bra"WPA_EAP to any
,06-30 12:52:10.565  4264  4264 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 12:52:10.565  4264  4264 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 12:52:10.565  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,06-30 12:52:10.565  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
06-30 12:52:10.565  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
06-30 12:52:10.565  4264  4264 I NearbySettings: MountReceiver.onReceive - Set preference state off
06-30 12:52:10.565  4264  4318 V NearbySettings: MountReceiver.mPrefHandler - 7002
,06-30 12:52:10.565   281   949 D CommandListener: Setting iface cfg
,06-30 12:52:10.575  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 1
,06-30 12:52:10.575  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
06-30 12:52:10.575  1014  1125 D SecContentProvider2: mCursor = null
,06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 12:52:10.585  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,06-30 12:52:10.585  1014  1125 E WifiNative-wlan0: do suspend false
,06-30 12:52:10.585  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 12:52:10.585  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,06-30 12:52:10.585  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.585  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:10.585  1014  1125 D SecContentProvider2: mCursor = null
,06-30 12:52:10.645  6121  6121 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,06-30 12:52:10.705   297   297 E SMD     : DCD OFF
,06-30 12:52:10.805  6207  6207 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 12:52:10.815  6207  6207 I dhcpcd  : version 5.5.6 starting,
,06-30 12:52:10.815  6207  6207 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,06-30 12:52:10.865  6207  6207 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,06-30 12:52:10.865  6207  6207 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
06-30 12:52:10.865  6207  6207 I dhcpcd  : if(wlan0) info get Success. (MAC : 84.CE.70),
06-30 12:52:10.865  6207  6207 I dhcpcd  : bssid match
06-30 12:52:10.865  6207  6207 I dhcpcd  : wlan0: rebinding lease of 10.76.13.33
,06-30 12:52:10.935  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 12:52:10.935  5980  6033 I jxcore-log: 
,06-30 12:52:10.935  6207  6207 I dhcpcd  : wlan0: acknowledged 10.76.13.33 from 131.200.201.74
,06-30 12:52:11.025  6207  6207 I dhcpcd  : wlan0: leased 10.76.13.33 for 3600 seconds
,06-30 12:52:11.205  1014  1125 E WifiNative-wlan0: do suspend true,
,06-30 12:52:11.225  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
,06-30 12:52:11.225  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 12:52:11.235  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:11.235  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 12:52:11.235  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 12:52:11.235  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.235  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.245  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
06-30 12:52:11.245  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.245  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"Qrsqc0bra"WPA_EAP
06-30 12:52:11.245  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,06-30 12:52:11.245  1014  1127 E ConnectivityService: updateNetworkInfo()
,06-30 12:52:11.245  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,06-30 12:52:11.245  1014  1127 D ConnectivityService: Adding iface wlan0 to network 502
,06-30 12:52:11.255  1014  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
06-30 12:52:11.255  1014  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 12:52:11.255  1014  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 12:52:11.255  1014  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 12:52:11.255  1014  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 12:52:11.275  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 12:52:11.275  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.275  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.275  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
06-30 12:52:11.275  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.275  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,06-30 12:52:11.275  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:11.275  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,06-30 12:52:11.285  3823  3823 I Hs20UtilService: Starting #5
,06-30 12:52:11.285  3823  3843 I Hs20UtilService: Message received 5007
06-30 12:52:11.285  4264  4264 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 12:52:11.285  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,06-30 12:52:11.285  1014  1127 D ConnectivityService: Adding Route [10.76.12.0/22 -> 0.0.0.0 wlan0] to network 502
,06-30 12:52:11.285  4264  4264 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 12:52:11.285  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 10.76.12.1 wlan0] to network. 502
,06-30 12:52:11.295  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
,06-30 12:52:11.295  1014  1127 D ConnectivityService: Setting Dns servers for network 502 to [/131.200.201.74, /131.200.78.74, /131.200.48.74, /131.200.16.74]
,06-30 12:52:11.295  1014  1127 D ConnectivityService: LTETest block dns file not exists
,06-30 12:52:11.295  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 12:52:11.305  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.305  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.305  1014  1220 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
06-30 12:52:11.305  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,06-30 12:52:11.305  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.305  1014  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:11.305  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,06-30 12:52:11.305  3823  3823 I Hs20UtilService: Starting #6
,06-30 12:52:11.315  1014  1127 E ConnectivityService: updateNetworkInfo()
,06-30 12:52:11.315  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 12:52:11.315  1014  1127 E ConnectivityService: updateNetworkInfo()
06-30 12:52:11.315  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
06-30 12:52:11.315  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
06-30 12:52:11.315  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
06-30 12:52:11.315  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
06-30 12:52:11.315  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-30 12:52:11.315  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
06-30 12:52:11.315  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "Qrsqc0bra"
,06-30 12:52:11.315  1014  1125 E WifiStateMachine: Did not find remoteAddress {10.76.12.1} in /proc/net/arp
,06-30 12:52:11.315  1014  1125 E WifiStateMachine: Did not find remoteAddress {10.76.12.1} in /proc/net/arp
,06-30 12:52:11.325  3823  3843 I Hs20UtilService: Message received 5007
,06-30 12:52:11.325  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
06-30 12:52:11.325  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
06-30 12:52:11.335  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,06-30 12:52:11.335  1014  1127 D ConnectivityService:    accepting network in place of null
,06-30 12:52:11.335  1014  1127 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
06-30 12:52:11.335  1014  6205 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
06-30 12:52:11.335  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-30 12:52:11.335  1014  6205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:52:11.335  1014  6205 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:52:11.335  1014  6205 I System.out: (HTTPLog)-Thread-167-1065906009: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:52:11.335  1014  6205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:52:11.335  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
06-30 12:52:11.335  1457  1457 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 12:52:11.335  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,06-30 12:52:11.345  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 12:52:11.345  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 12:52:11.345  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.345   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:11.345   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,06-30 12:52:11.345  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "Qrsqc0bra", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,06-30 12:52:11.345  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
06-30 12:52:11.345  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,06-30 12:52:11.345  4264  4264 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 12:52:11.355  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.355  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.355  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.355  4264  4264 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,06-30 12:52:11.355  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED,
,06-30 12:52:11.355  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "Qrsqc0bra", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,06-30 12:52:11.355  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
06-30 12:52:11.355  1014  1122 V NetworkStats: updateIfacesLocked()
06-30 12:52:11.355  1014  1128 D Tethering: MasterInitialState.processMessage what=3
06-30 12:52:11.355  1014  1122 V NetworkStats: performPollLocked(flags=0x1),
06-30 12:52:11.355  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
06-30 12:52:11.355  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
06-30 12:52:11.355  4264  4264 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
06-30 12:52:11.355  4264  4264 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 12:52:11.355  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
06-30 12:52:11.355  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
06-30 12:52:11.355  1014  1123 D NtpTrustedTime: forceRefresh() from cache miss
,06-30 12:52:11.355  1014  1122 V NetworkStats: performPollLocked() took 3ms
,06-30 12:52:11.365  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 12:52:11.365   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:11.365   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,06-30 12:52:11.365  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
,06-30 12:52:11.365  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,06-30 12:52:11.365  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 12:52:11.365  1172  1172 D StatusBar.NetworkController: updateDataNetType()
,06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:11.375  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 12:52:11.375  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.375  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,06-30 12:52:11.385  1014  1519 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,06-30 12:52:11.385  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,06-30 12:52:11.385  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:11.385  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 12:52:11.385  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,06-30 12:52:11.385  3823  3823 I Hs20UtilService: Starting #7
,06-30 12:52:11.385  3823  3843 I Hs20UtilService: Message received 5007
,06-30 12:52:11.395  4264  4264 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,06-30 12:52:11.395  4264  4264 I NearbySettings: MountReceiver.onReceive - Keep current state
,06-30 12:52:11.395  1014  1496 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,06-30 12:52:11.405  1014  1220 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,06-30 12:52:11.405  1014  1220 D SecContentProvider2: mCursor = null
,06-30 12:52:11.405  1014  1519 D SecContentProvider2: uri = 15 selection = getToastGravity
,06-30 12:52:11.405  1014  1519 D SecContentProvider2: mCursor = null
,06-30 12:52:11.415  1014  3078 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,06-30 12:52:11.415  1014  3078 D SecContentProvider2: mCursor = null
,06-30 12:52:11.415  1014  3079 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,06-30 12:52:11.415  1014  3079 D SecContentProvider2: mCursor = null
,06-30 12:52:11.415  1014  1027 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,06-30 12:52:11.415  1014  1027 D SecContentProvider2: mCursor = null
,06-30 12:52:11.425  1014  1393 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,06-30 12:52:11.425  1014  1393 D SecContentProvider2: mCursor = null
,06-30 12:52:11.455   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,06-30 12:52:11.455  1014  1519 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,06-30 12:52:11.465  1014  6205 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:11.465  1172  1172 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-30 12:52:11.485  1014  1123 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1467283930925 mCachedNtpElapsedRealtime : 137374 mCachedNtpCertainty : 27
,06-30 12:52:11.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 12:52:11.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 12:52:11.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 12:52:11.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 12:52:11.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 12:52:11.495  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
06-30 12:52:11.495  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,06-30 12:52:11.525  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 12:52:11.525  5980  6033 I jxcore-log: 
,06-30 12:52:11.555  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 12:52:11.555  5980  6033 I jxcore-log: 
,06-30 12:52:11.565  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 12:52:11.565  5980  6033 I jxcore-log: 
,06-30 12:52:11.575  6121  6121 E wpa_supplicant: IAPP Type:40, Func Type: 1
06-30 12:52:11.575  6121  6121 E wpa_supplicant: UnSupported IAPP Type 64
,06-30 12:52:11.585  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 12:52:11.585  5980  6033 I jxcore-log: 
,06-30 12:52:11.585  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 12:52:11.585  5980  6033 I jxcore-log: 
,06-30 12:52:11.605  1014  1304 E Watchdog: !@Sync 4
,06-30 12:52:11.765  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 30 Jun 2016 10:52:11 GMT], X-Android-Received-Millis=[1467283931774], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467283931648]}
,06-30 12:52:11.765  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,06-30 12:52:11.765  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,06-30 12:52:11.765  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
,06-30 12:52:11.765  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,06-30 12:52:11.765  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-30 12:52:11.765  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,06-30 12:52:11.765  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,06-30 12:52:11.765  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: updateDataNetType()
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,06-30 12:52:11.775  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,06-30 12:52:11.775  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 12:52:11.775  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
,06-30 12:52:11.785  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.785  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.785  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 12:52:11.785  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 12:52:11.855  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:11.855  2641  2698 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,06-30 12:52:11.865  1014  1369 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 12:52:11.865  1014  1369 D AlarmManagerService: Setting time of day to sec=1467283931
06-30 12:52:11.865  1014  1369 D AlarmManagerService: Trying to open a file
,06-30 12:52:11.865  1014  1369 D AlarmManagerService: File Open Success
,06-30 12:52:11.865  1014  1369 D AlarmManagerService: File Close Success
,06-30 12:52:11.302  1014  1092 V AlarmManager: waitForAlarm result :65536
,06-30 12:52:11.865  1014  1369 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
06-30 12:52:11.302  1014  1369 W AlarmManagerService: Unable to set rtc to 1467283931: Invalid argument
,06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:1a:ce:70
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:52:11.311  5980  5980 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 12:52:11.311  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,06-30 12:52:11.311  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:11.311  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.311  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.311  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.311  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.311  5980  5980 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 84:b2:61:1a:ce:70
,06-30 12:52:11.321  6248  6248 E Zygote  : MountEmulatedStorage(),
06-30 12:52:11.321  6248  6248 I libpersona: KNOX_SDCARD checking this for 1000
,06-30 12:52:11.321  6248  6248 E Zygote  : v2
,06-30 12:52:11.321  6248  6248 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:11.331  6248  6248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:11.331  1014  1039 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 12:52:11.331  6248  6248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:11.331  1014  1014 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1467283931340
,06-30 12:52:11.331  6248  6248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:11.341  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
06-30 12:52:11.341  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:52:11.341  1014  1014 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,06-30 12:52:11.341  1014  1014 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,06-30 12:52:11.341  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:52:11.351  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:52:11.351  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 12:52:11.351  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,06-30 12:52:11.361  1014  1014 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 12:52:11.361  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.361  1014  1092 V AlarmManager: waitForAlarm result :4
06-30 12:52:11.361  1014  1092 V AlarmManager: No more alarm at this time.nowELAPSED=137825 batch.start=162303
06-30 12:52:11.361  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.371  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.371  1014  1014 I DrmEventService:  no response from SecureClock 
,06-30 12:52:11.371  1014  1519 D SettingsProvider: name = lockscreen_zoom_panning_effect
,06-30 12:52:11.371  1014  1519 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:11.371  1014  1519 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:11.371  1014  1519 D SettingsProvider: selectionArgs: false
06-30 12:52:11.371  1014  1519 D SettingsProvider: selectionArgs: 10049
06-30 12:52:11.371  1014  1519 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:11.371  1014  1519 D SettingsProvider: ret = -1
,06-30 12:52:11.371  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,06-30 12:52:11.371  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,06-30 12:52:11.371  6248  6248 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:11.381  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,06-30 12:52:11.381  1172  1172 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
06-30 12:52:11.381  6248  6248 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.381  1172  1172 D KeyguardEffectViewController: isPreloadedWallpaper=true
06-30 12:52:11.381  1172  1172 I GeometricMosaic_Keyguard: update
,06-30 12:52:11.391  1172  1172 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,06-30 12:52:11.401  1014  1038 E GpsLocationProvider: No APN found to select.
,06-30 12:52:11.411  6248  6248 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-30 12:52:11.411  6248  6248 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-30 12:52:11.411  6248  6248 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,06-30 12:52:11.421  1014  3078 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 12:52:11.421  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,06-30 12:52:11.421  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:11.421  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:11.421  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.441  1014  1391 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:11.451  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:11.451  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.451  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.461  6248  6248 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 12:52:11.461  6248  6248 I PCWCLIENTTRACE_PushUtil: sales region : global
,06-30 12:52:11.461  6248  6248 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 12:52:11.461  6248  6248 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:11.461  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:11.471  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:11.471  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:11.471  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.471  1014  1480 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=9, mSplitNum[1]=19, mSplitNum[2]=28, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=36
,06-30 12:52:11.471  1014  1480 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,06-30 12:52:11.471  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,06-30 12:52:11.481  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.481  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.481  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.481  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.491  1172  1172 I KeyguardEffectViewUtil: set current wallpaper info,
06-30 12:52:11.491  1014  1519 D SettingsProvider: name = keyguard_current_wallpaper_type
06-30 12:52:11.491  1014  1519 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:11.491  1014  1519 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,06-30 12:52:11.491  1014  1519 D SettingsProvider: selectionArgs: false
06-30 12:52:11.491  1014  1519 D SettingsProvider: selectionArgs: 10049
06-30 12:52:11.491  1014  1519 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:11.491  6266  6266 I libpersona: KNOX_SDCARD checking this for 10108
,06-30 12:52:11.491  1014  1519 D SettingsProvider: ret = -1
06-30 12:52:11.491  6266  6266 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:11.491  1014  1026 D SettingsProvider: name = keyguard_current_wallpaper_file_path
06-30 12:52:11.491  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:11.491  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:11.491  1014  1026 D SettingsProvider: selectionArgs: false
06-30 12:52:11.491  1014  1026 D SettingsProvider: selectionArgs: 10049
06-30 12:52:11.491  6266  6266 E Zygote  : MountEmulatedStorage(),
06-30 12:52:11.491  6266  6266 E Zygote  : v2
06-30 12:52:11.491  6266  6266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:11.491  1014  1480 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6266 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 12:52:11.491  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:11.491  1014  1026 D SettingsProvider: ret = -1
06-30 12:52:11.491  1014  1027 D SettingsProvider: name = keyguard_current_wallpaper_res_id
06-30 12:52:11.491  1014  1393 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-30 12:52:11.491  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:11.491  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:11.491  1014  1027 D SettingsProvider: selectionArgs: false
06-30 12:52:11.491  1014  1027 D SettingsProvider: selectionArgs: 10049
06-30 12:52:11.491  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:11.491  1014  1027 D SettingsProvider: ret = -1
06-30 12:52:11.491  6266  6266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:11.501  6266  6266 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:11.501  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.501  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.501  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,06-30 12:52:11.511  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,06-30 12:52:11.511  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.511  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.511  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.511  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.521  6266  6266 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-30 12:52:11.521  6266  6266 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.541   317   317 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 45.210ms
,06-30 12:52:11.551   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.162ms
,06-30 12:52:11.561  1172  1645 D TEST    : run!!!
,06-30 12:52:11.571   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.215ms
,06-30 12:52:11.581  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
06-30 12:52:11.581  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:52:11.581  1172  1645 I GeometricMosaic_Renderer: setBackgroundBitmap
,06-30 12:52:11.581  6281  6281 E Zygote  : MountEmulatedStorage(),
,06-30 12:52:11.581  6281  6281 E Zygote  : v2
06-30 12:52:11.581  6281  6281 I libpersona: KNOX_SDCARD checking this for 10031
06-30 12:52:11.581  6281  6281 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:11.591  6281  6281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:11.591  1014  1039 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6281 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,06-30 12:52:11.591  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,06-30 12:52:11.591  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,06-30 12:52:11.591  6281  6281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:11.591  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.591  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.591  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.591  6281  6281 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:11.601  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate,
,06-30 12:52:11.601  6292  6292 E Zygote  : MountEmulatedStorage()
,06-30 12:52:11.601  6292  6292 I libpersona: KNOX_SDCARD checking this for 10110
06-30 12:52:11.601  6292  6292 E Zygote  : v2
06-30 12:52:11.601  6292  6292 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:11.601  6292  6292 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:11.601  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:52:11.601  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:52:11.611  6292  6292 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:11.611  6292  6292 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-30 12:52:11.611  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.611  1014  1039 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6292 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
06-30 12:52:11.611  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.611  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
06-30 12:52:11.611  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.611  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
06-30 12:52:11.611  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
06-30 12:52:11.621  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:11.621  1622  1622 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
06-30 12:52:11.621  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
06-30 12:52:11.621  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.621  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.621  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.631  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 12:52:11.631  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:52:11.631  6281  6281 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:11.641  6281  6281 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.651  6292  6292 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:11.651  6292  6292 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.711  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.721  1729  6311 I CheckinService: Checking schedule, now: 1467283931726 next: 1467064928669
06-30 12:52:11.721  1729  6311 I CheckinService: active receiver: enabled
,06-30 12:52:11.721  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.731  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:11.741  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,06-30 12:52:11.761  1729  6311 I CheckinService: Preparing to send checkin request
06-30 12:52:11.761  1729  6311 I EventLogService: Accumulating logs since 1467283170164
,06-30 12:52:11.771  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:11.771  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.771  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.771  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.781  1014  1026 I ActivityManager: Killing 5775:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,06-30 12:52:11.801  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-30 12:52:11.801  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.801  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.801  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:11.801  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:11.811  3174  6319 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 12:52:11.811  3174  6319 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,06-30 12:52:11.811  3174  6319 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,06-30 12:52:11.811  3174  6319 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,06-30 12:52:11.811  3174  6319 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok,
,06-30 12:52:11.821  3174  3282 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,06-30 12:52:11.821  3174  3282 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,06-30 12:52:11.821  6321  6321 E Zygote  : MountEmulatedStorage(),
,06-30 12:52:11.831  3174  3282 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 12:52:11.831  6321  6321 E Zygote  : v2,
06-30 12:52:11.831  1014  1027 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6321 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 12:52:11.831  6321  6321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:11.831  6321  6321 I libpersona: KNOX_SDCARD checking this for 10032
06-30 12:52:11.831  6321  6321 I libpersona: KNOX_SDCARD not a persona,
,06-30 12:52:11.831  6321  6321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:11.831  3174  3282 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 9
06-30 12:52:11.831  6321  6321 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-30 12:52:11.831  3174  3282 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 9
,06-30 12:52:11.841  3174  3282 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 9
,06-30 12:52:11.861  6266  6266 I MusicStore: Database version: 108
,06-30 12:52:11.881  6321  6321 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:11.881  6321  6321 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:11.891  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,06-30 12:52:11.901  1014  1391 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
06-30 12:52:11.901  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,06-30 12:52:11.901  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.901  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.901  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:11.911  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,06-30 12:52:11.911  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 12:52:11.911  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:11.911  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:11.911  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.911  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.931  1729  1729 I iu.Environment: update battery state; isPlugged? true*
,06-30 12:52:11.931  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,06-30 12:52:11.931  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,06-30 12:52:11.931  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,06-30 12:52:11.941  3174  3283 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,06-30 12:52:11.941  1729  1729 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,06-30 12:52:11.951  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,06-30 12:52:11.951  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,06-30 12:52:11.961  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:11.971  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,06-30 12:52:11.971  3174  3283 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 12:52:11.971  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:11.971  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:11.971  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:11.971  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,06-30 12:52:11.971  3174  3283 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,06-30 12:52:11.981  1729  1729 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
06-30 12:52:11.981  1729  1729 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 12:52:11.981  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 12:52:11.981  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/06/30/19:55:06
06-30 12:52:11.981  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 7571434 is smaller than the required version 8400000
,06-30 12:52:11.981   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:11.981   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:11.991  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/06/30/12:52:11
,06-30 12:52:11.991  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,06-30 12:52:11.991  3174  3282 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,06-30 12:52:11.991  3174  3283 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,06-30 12:52:11.991  3174  3283 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,06-30 12:52:11.991  3174  3283 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,06-30 12:52:11.991  3174  3283 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,06-30 12:52:12.001  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jun 30 12:52:12 GMT+02:00 2016
,06-30 12:52:12.001  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,06-30 12:52:12.001  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.001  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.001  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:12.001  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-30 12:52:12.011  3174  3283 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,06-30 12:52:12.021  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,06-30 12:52:12.021  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,06-30 12:52:12.041  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,06-30 12:52:12.041  1014  3079 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-30 12:52:12.041  3845  3845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 12:52:12.041  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
06-30 12:52:12.041  3845  3845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
06-30 12:52:12.041  3845  6349 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
06-30 12:52:12.041  3845  6349 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
06-30 12:52:12.041  6321  6351 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 12:52:12.041  6321  6351 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 12:52:12.051  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:12.051  1014  3079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:12.051  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,06-30 12:52:12.061  6321  6321 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,06-30 12:52:12.061  3174  3282 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,06-30 12:52:12.061  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,06-30 12:52:12.071  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.071  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.071  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.071  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.081  3845  6349 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,06-30 12:52:12.081  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0,
,06-30 12:52:12.081  6321  6351 D SPPClientService: PushLog.txt file is not deleted.
,06-30 12:52:12.081  6321  6351 D SPPClientService: PushLog.txt file is not deleted.
06-30 12:52:12.081  6321  6351 D SPPClientService: ============PushLog. stop!
,06-30 12:52:12.081  6358  6358 E Zygote  : MountEmulatedStorage()
06-30 12:52:12.091  6358  6358 E Zygote  : v2
06-30 12:52:12.091  6358  6358 I libpersona: KNOX_SDCARD checking this for 10036
06-30 12:52:12.091  6358  6358 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:12.091  6358  6358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:12.091  1014  1027 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=6358 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 12:52:12.091  3845  6349 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
06-30 12:52:12.091  1014  1027 I ActivityManager: Killing 5582:com.google.android.apps.plus/u0a117 (adj 15): empty #21
06-30 12:52:12.091  6358  6358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:12.101  6358  6358 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 12:52:12.121  6358  6358 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:12.121  6358  6358 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:12.121  3845  6349 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,06-30 12:52:12.131  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,06-30 12:52:12.171  3845  6349 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,06-30 12:52:12.181  3845  6349 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,06-30 12:52:12.191  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,06-30 12:52:12.191  1014  1479 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:52:12.191  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.191  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:12.191  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:12.191  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:12.201  6266  6266 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:52:12.201  6266  6266 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:12.221  1729  6311 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 12:52:12.271  1729  6311 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,06-30 12:52:12.271  6266  6266 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,06-30 12:52:12.281  6358  6358 I SA      : [SSP] onCreated
,06-30 12:52:12.281  3174  3282 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,06-30 12:52:12.291  3174  3282 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,06-30 12:52:12.311  1014  1120 I art     : Explicit concurrent mark sweep GC freed 56753(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/34MB, paused 3.034ms total 170.152ms
,06-30 12:52:12.321  6358  6358 I SA      : [TPM] There is no property file
,06-30 12:52:12.321  6358  6358 I SA      : [SCU] isHaveSA() - false
,06-30 12:52:12.321  6358  6358 I SA      : [TPM] getModelProperty : null
06-30 12:52:12.321  6358  6358 I SA      : [TPM] getCSCProperty : null
,06-30 12:52:12.331  6358  6358 I SA      : [DM] FLOATING AMOLED FEATURE: true
06-30 12:52:12.331  6358  6358 I SA      : [DM] PRODUCT AMOLED FEATURE: false
06-30 12:52:12.331  6358  6358 I SA      : [DM] TFT FEATURE: false
,06-30 12:52:12.331  6358  6358 I SA      : [DM] init START
,06-30 12:52:12.341  6266  6266 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 12:52:12.341  6266  6266 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22ef2ea3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-30 12:52:12.341  6266  6266 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 12:52:12.341  6266  6266 D AndroidMusic: GMSCore installation verified
,06-30 12:52:12.351  6358  6358 I SA      : [DM] This device is not a Vodafone
,06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,06-30 12:52:12.361  1014  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 12:52:12.361  6358  6358 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-30 12:52:12.361  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
06-30 12:52:12.361  6358  6358 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,06-30 12:52:12.371  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.371  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.371  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,06-30 12:52:12.371  6358  6358 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,06-30 12:52:12.381  6358  6358 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,06-30 12:52:12.391  6358  6358 I SA      : [SCU] isHaveSA() - false
06-30 12:52:12.391  6358  6358 I SA      : support phone number id : false
06-30 12:52:12.391  6358  6358 I SA      : [DM] Supports Ref Jpn : true
,06-30 12:52:12.391  6358  6358 I SA      : [DM] init END
,06-30 12:52:12.391  6358  6358 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOJ5 PSS = 4.497050696380942  ]
,06-30 12:52:12.391  6358  6358 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "Qrsqc0bra", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
06-30 12:52:12.391  6358  6358 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,06-30 12:52:12.401  6266  6266 I ConfigStore: Config Database version: 1,
,06-30 12:52:12.411  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,06-30 12:52:12.421  6358  6358 I SA      : [SLFUCHKMGR] constructor called
,06-30 12:52:12.421   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 12:52:12.421   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.431  6292  6380 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 12:52:12.431  6358  6358 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,06-30 12:52:12.431  6358  6358 I SA      : [OR] == isSIMCardReady false ==
,06-30 12:52:12.441  6358  6358 I SA      : [SCU] == networkStateCheck == true
,06-30 12:52:12.441  3174  3283 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,06-30 12:52:12.441  6358  6358 I SA      : [DM] getCountryCodeFromCSC : PL
,06-30 12:52:12.441  6358  6358 I SA      : isChinaCountryCode : false
,06-30 12:52:12.441  6358  6358 I SA      : [SCU] is ChinestModel Data Restricted   : false
06-30 12:52:12.441  6358  6358 I SA      : [OR] == networkStateCheck true ==
,06-30 12:52:12.451   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 12:52:12.451   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.451  6292  6380 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 12:52:12.461  6358  6358 I SA      : [OR] GetMyCountryZoneTask
,06-30 12:52:12.461  6358  6358 I SA      : [OR] onReceive END
,06-30 12:52:12.461  1014  3079 I ActivityManager: Killing 5802:com.wsomacp/u0a23 (adj 15): empty #21
,06-30 12:52:12.471  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:12.471   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 12:52:12.471   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.471  6266  6266 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 12:52:12.471  1014  1479 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,06-30 12:52:12.471  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.481  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.481  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:12.481  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,06-30 12:52:12.481   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 12:52:12.481   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.481  6266  6266 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 12:52:12.491  6358  6384 I SA      : [SRS] prepareGetMyCountryZone
,06-30 12:52:12.491  1707  1707 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,06-30 12:52:12.491   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
06-30 12:52:12.491   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.491  6266  6266 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,06-30 12:52:12.491   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
06-30 12:52:12.491   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.501  6292  6385 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,06-30 12:52:12.501  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
06-30 12:52:12.501  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.501  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:12.501  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.501  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.501  1748  1757 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,06-30 12:52:12.501  1014  1391 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,06-30 12:52:12.501  1014  1391 D SecContentProvider2: mCursor = null
,06-30 12:52:12.501   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
06-30 12:52:12.501   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:12.511  6292  6385 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,06-30 12:52:12.511  1707  1707 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,06-30 12:52:12.511  1707  1707 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
06-30 12:52:12.511  1707  1707 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
06-30 12:52:12.511  1707  1707 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,06-30 12:52:12.521  1707  1707 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,06-30 12:52:12.521  1707  1707 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,06-30 12:52:12.521  1014  3078 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,06-30 12:52:12.521  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.521  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.521  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.521  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.531  6389  6389 E Zygote  : MountEmulatedStorage(),
06-30 12:52:12.531  6389  6389 E Zygote  : v2
06-30 12:52:12.531  6389  6389 I libpersona: KNOX_SDCARD checking this for 10077
06-30 12:52:12.531  6389  6389 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:12.531  6389  6389 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:12.541  6358  6384 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
06-30 12:52:12.541  6389  6389 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:12.541  6358  6384 I SA      : [SSP] query invoked,
,06-30 12:52:12.541  6389  6389 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,06-30 12:52:12.541  1014  3078 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6389 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:52:12.551  1622  6373 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 12:52:12.561  6389  6389 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:12.561  6389  6389 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:12.561  1014  1480 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 12:52:12.561  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,06-30 12:52:12.571  1014  1480 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:12.571  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.571  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.591  6358  6384 I SA      : [TPMU] GetMccFromDB : null
06-30 12:52:12.591  6358  6384 I SA      : [SCU] getMccFromPreferece mcc = 316
06-30 12:52:12.591  6358  6384 I SA      : [TPM] isNoProxy(default) : true
,06-30 12:52:12.601  6358  6384 E File    : fail readDirectory() errno=2
,06-30 12:52:12.611  1014  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 12:52:12.621  1014  3078 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 12:52:12.621  1014  3079 I AudioService: getStreamVolume 3 index 70
,06-30 12:52:12.631  6266  6266 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,06-30 12:52:12.701  6266  6266 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,06-30 12:52:12.721  1622  6405 D GCM     : Connected
,06-30 12:52:12.731  6266  6266 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 12:52:12.781  1014  1519 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 12:52:12.781  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,06-30 12:52:12.791  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.791  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.791  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.791  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 12:52:12.791  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.791  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.791  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.791  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.801  1014  1480 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
06-30 12:52:12.801  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.801  1622  6405 D GCM     : Message class com.google.f.a.a.p
,06-30 12:52:12.801  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:12.801  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.801  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.811  1014  1393 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 12:52:12.831  6266  6266 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,06-30 12:52:12.831  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,06-30 12:52:12.831  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.831  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.831  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.831  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.841  6423  6423 E Zygote  : MountEmulatedStorage()
,06-30 12:52:12.851  6423  6423 E Zygote  : v2
06-30 12:52:12.851  6423  6423 I libpersona: KNOX_SDCARD checking this for 10001
06-30 12:52:12.851  6423  6423 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:12.851  6423  6423 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:12.851  6423  6423 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 12:52:12.851  6423  6423 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 12:52:12.851  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6423 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-30 12:52:12.881  6423  6423 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:12.881  6423  6423 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:12.891  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,06-30 12:52:12.891  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,06-30 12:52:12.901  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.901  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.901  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,06-30 12:52:12.901   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:12.901  6266  6266 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:52:12.901  6266  6266 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:12.921  6266  6266 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,06-30 12:52:12.921  6292  6292 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,06-30 12:52:12.921  1014  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,06-30 12:52:12.921  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,06-30 12:52:12.931  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:12.931  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.931  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,06-30 12:52:12.931  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:12.931  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:12.931  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:12.931  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,06-30 12:52:12.941  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,06-30 12:52:12.941  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.941  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.941  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:12.941  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:12.951  6292  6292 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9413-9415)
,06-30 12:52:12.951  6292  6292 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 12:52:12.961  6440  6440 E Zygote  : MountEmulatedStorage()
,06-30 12:52:12.961  6440  6440 E Zygote  : v2
06-30 12:52:12.961  6440  6440 I libpersona: KNOX_SDCARD checking this for 10102
06-30 12:52:12.961  6440  6440 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:12.961  6440  6440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:12.961  1014  1519 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6440 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 12:52:12.961  6440  6440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:12.961  6440  6440 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:12.961  1014  1519 I ActivityManager: Killing 5818:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,06-30 12:52:12.981  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:12.991  6440  6440 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:13.011  6440  6440 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 12:52:13.011  1014  1393 I ActivityManager: Killing 5834:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,06-30 12:52:13.051  6292  6292 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5f6d51e}
,06-30 12:52:13.051  6292  6292 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 12:52:13.051  6292  6292 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:52:13.051  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,06-30 12:52:13.051  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.051  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.051  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.051  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.071  1014  1519 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
06-30 12:52:13.071  1014  1519 I ActivityManager: Killing 5849:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,06-30 12:52:13.071  6459  6459 E Zygote  : MountEmulatedStorage(),
06-30 12:52:13.071  1014  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-30 12:52:13.081  6459  6459 E Zygote  : v2
06-30 12:52:13.081  6459  6459 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:13.081  6459  6459 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:13.081  6459  6459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:13.081  6459  6459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 12:52:13.081  1014  1519 W ActivityManager: userId = 0, bbcId = -10000,
,06-30 12:52:13.081  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:13.081  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.081  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:13.081  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.081  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.091  6292  6292 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:52:13.081  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,06-30 12:52:13.091  6292  6292 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:52:13.091  6292  6292 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 12:52:13.091  6459  6459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:13.121  6476  6476 E Zygote  : MountEmulatedStorage(),
06-30 12:52:13.121  6476  6476 I libpersona: KNOX_SDCARD checking this for 10011,
06-30 12:52:13.121  6476  6476 E Zygote  : v2,
06-30 12:52:13.121  6476  6476 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:13.121  6476  6476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:13.121  6476  6476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:13.121  6476  6476 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:13.131  6459  6459 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:13.131  6459  6459 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:13.131  1014  1519 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6476 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,06-30 12:52:13.131   297   297 E SMD     : DCD OFF
,06-30 12:52:13.141  6292  6292 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 12:52:13.141  6292  6292 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
06-30 12:52:13.141  6292  6292 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,06-30 12:52:13.151  6292  6292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 12:52:13.151  6292  6292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 12:52:13.151  6292  6292 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 12:52:13.151  6292  6292 I Adreno-EGL: Local Branch: 
06-30 12:52:13.151  6292  6292 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 12:52:13.151  6292  6292 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 12:52:13.151  6292  6292 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-30 12:52:13.161  6476  6476 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:13.161  6476  6476 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:13.181  6476  6476 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 12:52:13.181  6476  6476 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:13.221  6476  6476 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:52:13.221  6476  6476 I MultiDex: install
06-30 12:52:13.221  6476  6476 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:52:13.231  6476  6476 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 12:52:13.241  6459  6459 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,06-30 12:52:13.291  6292  6292 I NSApplication: Starting up...
06-30 12:52:13.291  6292  6505 W AudioManagerAndroid: Requires BLUETOOTH permission
,06-30 12:52:13.301  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,06-30 12:52:13.311  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.311  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.311  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.311  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.331  6510  6510 E Zygote  : MountEmulatedStorage()
,06-30 12:52:13.331  6510  6510 E Zygote  : v2
06-30 12:52:13.331  6510  6510 I libpersona: KNOX_SDCARD checking this for 10117
06-30 12:52:13.331  6510  6510 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:13.331  6510  6510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:13.331  6510  6510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:13.331  6510  6510 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-30 12:52:13.331  1014  1480 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6510 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:52:13.331  1014  1480 I ActivityManager: Killing 5865:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,06-30 12:52:13.361  6510  6510 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:13.371  6510  6510 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:13.421  6510  6510 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 12:52:13.431  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,06-30 12:52:13.431  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 12:52:13.431  6440  6529 I Babel   : MmsConfig: mnc/mcc: 0/0
06-30 12:52:13.431  6440  6529 I Babel   : MmsConfig.loadMmsSettings
06-30 12:52:13.431  6440  6529 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
06-30 12:52:13.431  6440  6529 I Babel   : MmsConfig.loadFromDatabase
,06-30 12:52:13.441  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 12:52:13.441  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 12:52:13.441  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 12:52:13.461  6440  6529 E Babel   : canonicalizeMccMnc: invalid mccmnc 
06-30 12:52:13.461  6440  6529 I Babel   : MmsConfig.loadFromResources
,06-30 12:52:13.471  6440  6529 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
06-30 12:52:13.471  6440  6529 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,06-30 12:52:13.491   288   704 D WVCdm   : Instantiating CDM.
,06-30 12:52:13.501   288   732 I WVCdm   : CdmEngine::OpenSession
,06-30 12:52:13.501  1014  1480 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,06-30 12:52:13.501   288   732 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,06-30 12:52:13.501  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,06-30 12:52:13.501  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:13.501  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:13.511  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,06-30 12:52:13.511  6440  6440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 12:52:13.541   288   732 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-30 12:52:13.551  1014  1120 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:52:13.551  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,06-30 12:52:13.551  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:13.551  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:13.551  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:13.561  6476  6492 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 12:52:13.561  6459  6459 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,06-30 12:52:13.571   288   732 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,06-30 12:52:13.581  6476  6492 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
06-30 12:52:13.581  6476  6492 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:52:13.581  6476  6492 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:52:13.581  6476  6492 I System.out: (HTTPLog)-Thread-1149-695245406: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:52:13.581  6476  6492 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:13.581   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:13.581   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:13.591  6459  6459 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,06-30 12:52:13.601  6459  6459 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:13.601  6440  6440 I Babel_StickerModule: App launched.
06-30 12:52:13.601  6440  6440 I Babel_StickerModule: Trying first logged in account.
,06-30 12:52:13.611  6459  6459 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
06-30 12:52:13.611  6459  6459 I DIAGMON_AGENT: ./extraInfo: "Qrsqc0bra"
,06-30 12:52:13.611  6459  6459 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
06-30 12:52:13.611  6440  6440 W Babel_StickerModule: Unable to load, account not configured.
,06-30 12:52:13.631   288   732 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 12:52:13.631  6476  6492 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:13.631   288   288 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,06-30 12:52:13.641   288   288 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,06-30 12:52:13.641   288   288 I WVCdm   : CdmEngine::GenerateKeyRequest
,06-30 12:52:13.641   288   288 D WVCdm   : PrepareKeyRequest: nonce=1387900858
,06-30 12:52:13.651   288   732 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,06-30 12:52:13.651   288   732 W QCamera2Factory: getCameraInfo: X
,06-30 12:52:13.681   288   704 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,06-30 12:52:13.681   288   704 W QCamera2Factory: getCameraInfo: X
,06-30 12:52:13.751  1014  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,06-30 12:52:13.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:13.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:13.761  6440  6440 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
06-30 12:52:13.771  6538  6538 I libpersona: KNOX_SDCARD checking this for 10008
,06-30 12:52:13.761  6440  6440 W AudioCapabilities: Unsupported mime audio/evrc
06-30 12:52:13.771  6538  6538 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:13.761  6440  6440 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 12:52:13.771  6538  6538 E Zygote  : MountEmulatedStorage()
06-30 12:52:13.771  6538  6538 E Zygote  : v2
06-30 12:52:13.771  6538  6538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:13.771  6538  6538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:13.771  6538  6538 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 12:52:13.771  6440  6440 W AudioCapabilities: Unsupported mime audio/mpeg-L1,
,06-30 12:52:13.781  1014  1027 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6538 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-30 12:52:13.791  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable,
,06-30 12:52:13.791  6538  6538 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:13.801  6440  6440 W AudioCapabilities: Unsupported mime audio/mpeg-L2,
,06-30 12:52:13.811   317   317 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 3.373ms total 35.379ms,
,06-30 12:52:13.821  6440  6440 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,06-30 12:52:13.821  6440  6440 W AudioCapabilities: Unsupported mime audio/x-ima
,06-30 12:52:13.831  6440  6440 W AudioCapabilities: Unsupported mime audio/qcelp
,06-30 12:52:13.831  6440  6440 W AudioCapabilities: Unsupported mime audio/evrc,
,06-30 12:52:13.851   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 19.402ms,
,06-30 12:52:13.861   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 17.318ms,
,06-30 12:52:13.881  6440  6440 W VideoCapabilities: Unsupported mime video/wvc1
,06-30 12:52:13.881  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-30 12:52:13.901   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:13.901  6440  6440 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,06-30 12:52:13.901  6440  6440 W VideoCapabilities: Unsupported mime video/wvc1
,06-30 12:52:13.921  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,06-30 12:52:13.931  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,06-30 12:52:13.941  6440  6440 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,06-30 12:52:13.951  6440  6440 W VideoCapabilities: Unsupported mime video/mp43
,06-30 12:52:13.951  6440  6440 W VideoCapabilities: Unsupported mime video/sorenson
,06-30 12:52:13.981  6440  6440 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,06-30 12:52:14.021  6440  6440 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,06-30 12:52:14.041  1014  1220 I ActivityManager: Killing 5640:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,06-30 12:52:14.051  6538  6538 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,06-30 12:52:14.061  6538  6538 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,06-30 12:52:14.061  6538  6538 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,06-30 12:52:14.071  6538  6538 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,06-30 12:52:14.071  1014  1496 I ActivityManager: Killing 5889:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,06-30 12:52:14.091  1014  1519 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,06-30 12:52:14.091  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,06-30 12:52:14.091  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:14.091  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:14.091  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,06-30 12:52:14.111  1014  1391 I ActivityManager: Killing 5913:com.google.android.gms:car/u0a11 (adj 15): empty #21
,06-30 12:52:14.171  1014  1519 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,06-30 12:52:14.281  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,06-30 12:52:14.281  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.281  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.281  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.281  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.291  1014  1480 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6560 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,06-30 12:52:14.291  6560  6560 E Zygote  : MountEmulatedStorage(),
06-30 12:52:14.291  1014  1480 I ActivityManager: Killing 5930:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,06-30 12:52:14.301  6560  6560 E Zygote  : v2
06-30 12:52:14.301  6560  6560 I libpersona: KNOX_SDCARD checking this for 10121
06-30 12:52:14.301  6560  6560 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:14.301  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:14.311  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:14.311  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:14.331  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:14.331  6560  6560 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:14.341  6560  6560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:14.341  6560  6560 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:52:14.341  6560  6560 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 12:52:14.361   258  1095 I SurfaceFlinger: id=13 Removed Uoast (8/9),
06-30 12:52:14.361   258   422 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,06-30 12:52:14.371  1014  3078 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 140834,
,06-30 12:52:14.371  1014  3078 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,06-30 12:52:14.371  1014  3078 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10049}) (elapsedTime=3490)
,06-30 12:52:14.391  6560  6560 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,06-30 12:52:14.391  6560  6560 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,06-30 12:52:14.401  6560  6560 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,06-30 12:52:14.411  1014  1391 D RCPManagerService: exchangeData() failure , invalid userId
,06-30 12:52:14.421  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 12:52:14.421  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 12:52:14.421  6146  6146 D SecurityLogAgent: StateMachine : Current State = 1
,06-30 12:52:14.431  6146  6146 D SecurityLogAgent: StateMachine : Changed Current State = 1
,06-30 12:52:14.431  1014  3079 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,06-30 12:52:14.431  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.431  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.431  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.431  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.451  6575  6575 E Zygote  : MountEmulatedStorage()
06-30 12:52:14.451  6575  6575 E Zygote  : v2
06-30 12:52:14.451  6575  6575 I libpersona: KNOX_SDCARD checking this for 10009
06-30 12:52:14.451  6575  6575 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:14.451  6575  6575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:14.451  6575  6575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:14.451  6575  6575 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-30 12:52:14.451  1014  3079 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6575 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 12:52:14.461  1014  3079 I ActivityManager: Killing 5390:com.android.defcontainer/u0a3 (adj 15): empty #21
,06-30 12:52:14.471  6207  6207 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 12:52:14.491  6575  6575 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:14.491  6575  6575 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:14.511  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 12:52:14.511  5980  6033 I jxcore-log: 
,06-30 12:52:14.521  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 12:52:14.521  5980  6033 I jxcore-log: 
,06-30 12:52:14.541  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 12:52:14.541  5980  6033 I jxcore-log: 
,06-30 12:52:14.571  6575  6575 D WaitQueueForNetworkActivate: notifyNetworkActivated
,06-30 12:52:14.811  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 12:52:14.811  5980  6033 I jxcore-log: 
,06-30 12:52:14.851  6596  6596 I dex2oat : ----------------------------------------------------
,06-30 12:52:14.851  6596  6596 I dex2oat : <SS>: S T A R T I N G . . .
06-30 12:52:14.851  6596  6596 I dex2oat : <SS>: Zip is absent. Canceled.
,06-30 12:52:14.851  6596  6596 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-30 12:52:14.851  1014  1391 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,06-30 12:52:14.851  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,06-30 12:52:14.861  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:14.861  1014  1391 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
06-30 12:52:14.861  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,06-30 12:52:14.871  1014  1519 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,06-30 12:52:14.871  1014  1014 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,06-30 12:52:14.871  1014  1014 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,06-30 12:52:14.881  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,06-30 12:52:14.881  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.881  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.881  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.881  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.881  6575  6575 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,06-30 12:52:14.881  6575  6575 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,06-30 12:52:14.891  6538  6538 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...,
,06-30 12:52:14.891  6575  6575 D InitializeManagerStateMachine: execute::IDLE:EXECUTE,
06-30 12:52:14.891  6575  6575 D InitializeManagerStateMachine: exit::IDLE
06-30 12:52:14.891  6575  6575 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,06-30 12:52:14.901  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Jun 30 12:52:14 GMT+02:00 2016,
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: exit::NETWORK_CHECK
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK,
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
06-30 12:52:14.901  6575  6575 D InitializeManagerStateMachine: entry::SUCCESS
06-30 12:52:14.901  6575  6575 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess,
,06-30 12:52:14.901   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:52:14.901  1014  1039 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6601 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-30 12:52:14.911  6601  6601 E Zygote  : MountEmulatedStorage()
06-30 12:52:14.911  6601  6601 E Zygote  : v2
06-30 12:52:14.911  6601  6601 I libpersona: KNOX_SDCARD checking this for 10081
06-30 12:52:14.911  6601  6601 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:14.911  6601  6601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:14.911  6601  6601 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:14.921  6601  6601 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 12:52:14.921  1014  1479 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
06-30 12:52:14.921  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State = 1
06-30 12:52:14.921  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
06-30 12:52:14.921  6146  6146 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
06-30 12:52:14.921  6146  6146 D SecurityLogAgent: StateMachine : Current State = 1
06-30 12:52:14.921  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:14.921  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:14.921  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-30 12:52:14.941  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
06-30 12:52:14.941  6358  6358 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
06-30 12:52:14.941  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,06-30 12:52:14.951  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.951  6596  6596 I dex2oat : dex2oat took 97.364ms (threads: 4)
,06-30 12:52:14.951  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:14.951  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.951  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:14.951  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 12:52:14.951  5980  6033 I jxcore-log: 
,06-30 12:52:14.961  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
06-30 12:52:14.961  3845  3845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 12:52:14.961  3845  3845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
06-30 12:52:14.971  3845  6613 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
06-30 12:52:14.971  6601  6601 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:14.971  6601  6601 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:14.971  3845  6613 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,06-30 12:52:14.971  6617  6617 E Zygote  : MountEmulatedStorage()
06-30 12:52:14.971  6617  6617 E Zygote  : v2
06-30 12:52:14.971  6617  6617 I libpersona: KNOX_SDCARD checking this for 10153
06-30 12:52:14.971  6617  6617 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:14.971  3845  6613 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Thu Jun 30 12:52:14 GMT+02:00 2016
,06-30 12:52:14.971  6617  6617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:14.971  1014  1027 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6617 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,06-30 12:52:14.981  6617  6617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:14.981  6617  6617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:14.991  6476  6492 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 12:52:14.991  6476  6492 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 12:52:14.991  6476  6492 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 12:52:14.991  6476  6492 I Adreno-EGL: Local Branch: 
06-30 12:52:14.991  6476  6492 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 12:52:14.991  6476  6492 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 12:52:14.991  6476  6492 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-30 12:52:15.011  3845  6613 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,06-30 12:52:15.021  6617  6617 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:15.021  6617  6617 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:15.041  6575  6575 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,06-30 12:52:15.051  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,06-30 12:52:15.051  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 12:52:15.051  5980  6033 I jxcore-log: 
,06-30 12:52:15.061  6538  6538 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,06-30 12:52:15.061  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 12:52:15.061  5980  6033 I jxcore-log: 
,06-30 12:52:15.071  1014  1977 V SAMP_SPCM_test: CSC File load.. 
,06-30 12:52:15.081  6476  6492 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 12:52:15.081  6476  6492 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 12:52:15.081  6476  6492 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 12:52:15.081  6476  6492 I Adreno-EGL: Local Branch: 
06-30 12:52:15.081  6476  6492 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 12:52:15.081  6476  6492 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 12:52:15.081  6476  6492 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,06-30 12:52:15.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,06-30 12:52:15.091  6575  6575 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
06-30 12:52:15.091  6575  6575 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,06-30 12:52:15.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,06-30 12:52:15.111  6575  6575 D InitializeManagerStateMachine: exit::SUCCESS
,06-30 12:52:15.111  6575  6575 D InitializeManagerStateMachine: entry::IDLE
,06-30 12:52:15.121  6476  6492 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 12:52:15.121  6476  6492 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 12:52:15.121  6476  6492 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 12:52:15.121  6476  6492 I Adreno-EGL: Local Branch: 
06-30 12:52:15.121  6476  6492 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 12:52:15.121  6476  6492 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 12:52:15.121  6476  6492 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,06-30 12:52:15.131  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,06-30 12:52:15.141  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,06-30 12:52:15.141  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,06-30 12:52:15.141  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
06-30 12:52:15.141  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,06-30 12:52:15.141  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
06-30 12:52:15.151  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,06-30 12:52:15.161  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,06-30 12:52:15.161  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:15.161  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,06-30 12:52:15.161  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:15.161  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:15.161  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:15.171  1014  1027 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,06-30 12:52:15.171  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,06-30 12:52:15.171  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:15.171  1014  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,06-30 12:52:15.171  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,06-30 12:52:15.171   285   285 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 3036
06-30 12:52:15.171   285   285 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 3036
,06-30 12:52:15.181   285   520 D WVMDrmPlugIn: WVMDrmPlugin::onGetSupportInfo : 0
,06-30 12:52:15.181  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,06-30 12:52:15.181  6617  6617 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:15.181   288   704 I WVCdm   : CdmEngine::OpenSession
,06-30 12:52:15.181  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.181  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.181  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.181  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.201  6636  6636 E Zygote  : MountEmulatedStorage()
06-30 12:52:15.201  6636  6636 E Zygote  : v2
06-30 12:52:15.201  6636  6636 I libpersona: KNOX_SDCARD checking this for 10041
06-30 12:52:15.201  6636  6636 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:15.201  6636  6636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:15.201  6636  6636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:15.201  6636  6636 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 12:52:15.211  1014  1480 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6636 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,06-30 12:52:15.211  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.211  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.211  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.211  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.251  6652  6652 E Zygote  : MountEmulatedStorage()
,06-30 12:52:15.251  6652  6652 E Zygote  : v2
06-30 12:52:15.251  6652  6652 I libpersona: KNOX_SDCARD checking this for 10011
06-30 12:52:15.251  6652  6652 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:15.251  6652  6652 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
06-30 12:52:15.251  6636  6636 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:15.251  1014  1039 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6652 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
06-30 12:52:15.251  6636  6636 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:15.261  6652  6652 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 12:52:15.261  6652  6652 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:15.271  1014  1977 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,06-30 12:52:15.271  1014  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.271  1014  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.271  1014  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.271  1014  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.291  6662  6662 E Zygote  : MountEmulatedStorage(),
06-30 12:52:15.291  6662  6662 E Zygote  : v2
,06-30 12:52:15.291  6662  6662 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:15.291  6662  6662 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:15.301  6662  6662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:15.301  6662  6662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:15.301  1014  1977 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6662 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
06-30 12:52:15.301  6652  6652 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:15.301  6636  6636 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,06-30 12:52:15.301  6652  6652 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:15.301  6636  6636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:15.301  6636  6636 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:15.301  6636  6636 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
06-30 12:52:15.311  6636  6636 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,06-30 12:52:15.311  6662  6662 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 12:52:15.321  1014  1393 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,06-30 12:52:15.321  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.321  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.321  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:15.321  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:15.341  6682  6682 E Zygote  : MountEmulatedStorage(),
06-30 12:52:15.341  6682  6682 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:15.341  6682  6682 E Zygote  : v2
06-30 12:52:15.341  6682  6682 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:15.341  6682  6682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:15.351  1014  1393 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
06-30 12:52:15.351  6682  6682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:15.351  6682  6682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 12:52:15.361  6662  6662 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:15.361  6662  6662 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:15.371   288   732 I WVCdm   : CdmEngine::CloseSession
,06-30 12:52:15.371  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:15.371  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,06-30 12:52:15.381  6652  6652 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:52:15.381  6652  6652 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:15.381  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:15.381  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
06-30 12:52:15.391  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:15.401  1014  1391 I ActivityManager: Killing 5406:com.android.vending/u0a26 (adj 15): empty #21
,06-30 12:52:15.401  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:15.401  6682  6682 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:15.411  6662  6662 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:15.421  3174  3282 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,06-30 12:52:15.431  6601  6601 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
06-30 12:52:15.431  6601  6601 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:52:15.431  6601  6601 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:15.431  6601  6601 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:15.431  6601  6601 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,06-30 12:52:15.451   288   704 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 12:52:15.451   288   288 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 12:52:15.451   288   288 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 12:52:15.451   288   288 I WVCdm   : CdmEngine::GenerateKeyRequest
,06-30 12:52:15.461   288   288 D WVCdm   : PrepareKeyRequest: nonce=1105056392
,06-30 12:52:15.481  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,06-30 12:52:15.491  6652  6652 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:52:15.491  6652  6652 I MultiDex: install
06-30 12:52:15.491  6652  6652 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:52:15.501  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 12:52:15.501  5980  6033 I jxcore-log: 
,06-30 12:52:15.511  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,06-30 12:52:15.511  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,06-30 12:52:15.511  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,06-30 12:52:15.511  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,06-30 12:52:15.511  3174  3282 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,06-30 12:52:15.531  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 12:52:15.531  5980  6033 I jxcore-log: 
,06-30 12:52:15.541  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 12:52:15.541  5980  6033 I jxcore-log: 
,06-30 12:52:15.541  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 12:52:15.541  5980  6033 I jxcore-log: 
,06-30 12:52:15.551  1014  1519 I ActivityManager: Killing 6054:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,06-30 12:52:15.561  3174  3282 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,06-30 12:52:15.571  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 12:52:15.571  5980  6033 I jxcore-log: 
,06-30 12:52:15.581  3174  3282 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,06-30 12:52:15.591  1014  1027 I art     : Explicit concurrent mark sweep GC freed 29467(1663KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 3.149ms total 165.450ms
,06-30 12:52:15.611  6636  6636 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,06-30 12:52:15.611  1014  1977 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,06-30 12:52:15.621  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 12:52:15.621  5980  6033 I jxcore-log: 
,06-30 12:52:15.621  1014  1014 I ActivityManager: Killing 6105:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,06-30 12:52:15.631  3174  3282 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,06-30 12:52:15.651  6652  6652 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 12:52:15.661  1014  1496 I ActivityManager: Killing 6170:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,06-30 12:52:15.671  1014  1479 D SettingsProvider: name = next_alarm_formatted
,06-30 12:52:15.671  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:15.671  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:15.671  1014  1479 D SettingsProvider: selectionArgs: false
,06-30 12:52:15.671  1014  1479 D SettingsProvider: selectionArgs: 10081
,06-30 12:52:15.681  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:15.681  1014  1479 D SettingsProvider: ret = -1
,06-30 12:52:15.691  6682  6682 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1467283935693
,06-30 12:52:15.691  6682  6682 D         : TimeServiceNative: User Time to be set is 1467283935693
06-30 12:52:15.691  6682  6682 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,06-30 12:52:15.691  6682  6682 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
06-30 12:52:15.691  6682  6682 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1467283935693
,06-30 12:52:15.691   334   419 D QC-time-services: Daemon: Connection accepted:time_genoff
,06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1467283935693
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1467283935693, operation = 0
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/26/70 4:35:43
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:Value read from RTC seconds = 31034143000
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:new time 1467283935693 
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon: delta 1436249792693 genoff 1436249792693 
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249792693 to memory
06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:Opening File: /data/time/ats_2
,06-30 12:52:15.691   334  6701 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-30 12:52:15.701  6682  6682 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,06-30 12:52:15.711   334  6701 D QC-time-services: Updating the TOD offset
06-30 12:52:15.711   334  6701 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249792693 to memory
06-30 12:52:15.711   334  6701 D QC-time-services: Daemon:Opening File: /data/time/ats_1
06-30 12:52:15.711   334  6701 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,06-30 12:52:15.721   334  6701 E QC-time-services: Daemon:Update to modem bit set
06-30 12:52:15.721   334  6701 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
06-30 12:52:15.721   334  6701 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120284992693
,06-30 12:52:15.721  6682  6682 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,06-30 12:52:15.721   334   413 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
06-30 12:52:15.721   334   419 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,06-30 12:52:15.721  1014  1480 I ActivityManager: Killing 6185:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,06-30 12:52:15.751  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,06-30 12:52:15.751  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
06-30 12:52:15.751  1748  1748 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 12:52:15.751  1748  1748 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 12:52:15.761  1748  1748 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 12:52:15.761  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 12:52:15.761  5980  6033 I jxcore-log: 
,06-30 12:52:15.761  1748  1748 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,06-30 12:52:15.761  1748  1748 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 12:52:15.761  1748  1748 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
06-30 12:52:15.761  1748  1748 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 12:52:15.761  1748  1748 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 12:52:15.761  1748  1748 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,06-30 12:52:15.761  1748  1748 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,06-30 12:52:15.771  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 12:52:15.771  5980  6033 I jxcore-log: 
,06-30 12:52:15.781  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,06-30 12:52:15.801  5980  6033 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 12:52:15.801  5980  6033 I jxcore-log: 
,06-30 12:52:15.821  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
06-30 12:52:15.821  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
06-30 12:52:15.821  1748  1748 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,06-30 12:52:15.821  1748  1748 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,06-30 12:52:15.821  5980  6033 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,06-30 12:52:15.831  5980  6033 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
06-30 12:52:15.831  5980  6033 I jxcore-log: 
,06-30 12:52:15.841  1748  1748 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,06-30 12:52:15.841  1014  2720 D SSRM:n  : SIOP:: AP = 390
,06-30 12:52:15.851  1748  1748 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,06-30 12:52:15.851  1748  1748 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,06-30 12:52:15.901   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:15.911  6601  6601 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 224.504ms
,06-30 12:52:15.921  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
06-30 12:52:15.921  5980  6033 I jxcore-log: 
,06-30 12:52:15.921  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 12:52:15.921  5980  6033 I jxcore-log: 
,06-30 12:52:15.931  5980  6033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"84:b2:61:1a:ce:70"}
06-30 12:52:15.931  5980  6033 I jxcore-log: 
,06-30 12:52:15.941  6358  6384 I SA      : [RC New] Execute method=[GET] start
,06-30 12:52:15.981  6636  6636 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 258.577ms
,06-30 12:52:16.001  6358  6384 I SA      : [RC New] Security=[true]
,06-30 12:52:16.001  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,06-30 12:52:16.001  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):isSBSettingEnabled false
,06-30 12:52:16.001  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):isShipBuild true
,06-30 12:52:16.001  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:16.001  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:16.011   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:16.011   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,06-30 12:52:16.021  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-30 12:52:16.021  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.021  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.021  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.021  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.031  6703  6703 E Zygote  : MountEmulatedStorage()
06-30 12:52:16.031  6703  6703 E Zygote  : v2
,06-30 12:52:16.031  6703  6703 I libpersona: KNOX_SDCARD checking this for 10090
06-30 12:52:16.031  6703  6703 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:16.031  6703  6703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:16.031  1014  1027 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6703 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
06-30 12:52:16.031  6703  6703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:16.031  1014  1027 I ActivityManager: Killing 6248:com.sec.pcw.device/1000 (adj 15): empty #21
06-30 12:52:16.031  6703  6703 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:16.061  6703  6703 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.061  6703  6703 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.071  6636  6718 D Mms/ArtClassLoader: init before art
,06-30 12:52:16.071  6636  6636 D Mms/TelephonyPermission: start operation mode monitor
,06-30 12:52:16.091  6636  6636 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 12:52:16.091  6636  6636 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
06-30 12:52:16.091  6636  6636 D Mms/TelephonyPermission: isDefault true
,06-30 12:52:16.091  6636  6636 D Mms/MmsApp: onCreate() com.android.mms
,06-30 12:52:16.101  6703  6703 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,06-30 12:52:16.101  6703  6703 D elm:15121: ELMEngine.ELMEngine( context ).
,06-30 12:52:16.101  6703  6703 D elm:15121: MDMBridge.setEnterpriseBridge()
,06-30 12:52:16.101  1014  1480 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 12:52:16.101  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.101  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.101  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:16.101  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-30 12:52:16.101  6703  6703 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,06-30 12:52:16.111  1014  3078 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,06-30 12:52:16.111  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.111  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.111  6703  6703 D elm:15121: ElmAgentService : onCreate()
06-30 12:52:16.111  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.111  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.121  6703  6719 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,06-30 12:52:16.121  6703  6719 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,06-30 12:52:16.121  6703  6703 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
06-30 12:52:16.121  6703  6703 D elm:15121: ModuleBase.ModifySetAlarm()
06-30 12:52:16.121  6703  6703 D elm:15121: MDMBridge.getInstance()
06-30 12:52:16.121  6703  6703 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-30 12:52:16.121  6721  6721 E Zygote  : MountEmulatedStorage()
,06-30 12:52:16.121  6721  6721 E Zygote  : v2
06-30 12:52:16.121  6721  6721 I libpersona: KNOX_SDCARD checking this for 10130
06-30 12:52:16.121  6721  6721 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:16.131  1014  3078 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6721 uid=10130 gids={50130, 9997} abi=armeabi-v7a
06-30 12:52:16.131  6721  6721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:16.131  6721  6721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:16.131  6721  6721 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
06-30 12:52:16.131  6703  6703 D elm:15121: ElmAgentService : onDestroy().
,06-30 12:52:16.131  1014  1393 I ActivityManager: Killing 6281:com.sec.android.soagent/u0a31 (adj 15): empty #21
,06-30 12:52:16.141   297   297 E SMD     : DCD OFF,
,06-30 12:52:16.161  6636  6636 D Mms/MmsApp: [start]    initCountryIso consume time = 551.56052,
,06-30 12:52:16.171  6721  6721 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-30 12:52:16.171  1014  1519 D CountryDetector: The first listener is added
06-30 12:52:16.171  6721  6721 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.181  6636  6636 D Mms/MmsApp: [end]    initCountryIso consume time = 15.996406
,06-30 12:52:16.181  6636  6636 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.463959
,06-30 12:52:16.191  6636  6636 D Mms/MmsConfig: before partial update
,06-30 12:52:16.191  6721  6721 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:16.191  6721  6721 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 12:52:16.201  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,06-30 12:52:16.201  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.201  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.201  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.201  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.211  6636  6636 D Mms/MmsConfig: Load Resize quality : 80
,06-30 12:52:16.211  6636  6636 D EasySignUpManager_1.0.1: serviceId : 1, features : -1,
06-30 12:52:16.211  6636  6636 D EasySignUpManager_1.0.1: isAuth is false
06-30 12:52:16.211  6636  6636 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,06-30 12:52:16.221  1014  1519 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6738 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-30 12:52:16.221  1014  1519 I ActivityManager: Killing 6292:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,06-30 12:52:16.231  6738  6738 E Zygote  : MountEmulatedStorage(),
06-30 12:52:16.231  6738  6738 E Zygote  : v2
06-30 12:52:16.231  6738  6738 I libpersona: KNOX_SDCARD checking this for 10131
06-30 12:52:16.231  6738  6738 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:16.231  6738  6738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:16.231  6738  6738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 12:52:16.241  1457  5756 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6636
,06-30 12:52:16.241  6738  6738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
06-30 12:52:16.241  1457  5756 D TP/MmsSmsProvider: match 2117:Elapsed time : 3.210 ms
,06-30 12:52:16.251   317   317 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 27.930ms
,06-30 12:52:16.271  6738  6738 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.271   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 17.241ms
,06-30 12:52:16.271  6738  6738 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.281  6636  6636 D EasySignUpManager_1.0.1: isAuth is false
,06-30 12:52:16.281  6636  6636 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,06-30 12:52:16.291   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 658us total 17.126ms
,06-30 12:52:16.291  6636  6636 E CscParser: mps_code.dat does not exist
06-30 12:52:16.291  6636  6636 E CscParser: customer_path =/system/csc/customer.xml
06-30 12:52:16.291  6636  6636 E CscParser: fileName + /system/csc/customer.xml,
,06-30 12:52:16.291  6738  6738 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:52:16.291  6738  6738 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:16.291  6738  6738 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:16.301  6636  6636 E CscParser: mps_code.dat does not exist
06-30 12:52:16.301  6636  6636 E CscParser: customer_path =/system/csc/customer.xml
06-30 12:52:16.301  6636  6636 E CscParser: fileName + /system/csc/customer.xml
,06-30 12:52:16.311  6636  6636 D CscParser: getInstance fileName =/system/csc/customer.xml
,06-30 12:52:16.321  6636  6636 D Mms/MmsConfig:  enable multiwindow = false
,06-30 12:52:16.331  6636  6636 E Mms/MessageUtils: setCountryDetector : update country detector info 
06-30 12:52:16.331  6636  6636 E Mms/MessageUtils: updateCountryIso : update country iso info 
,06-30 12:52:16.331  6636  6636 D Mms/MmsConfig: [end]    init() consume time = 155.7625
,06-30 12:52:16.331  6636  6636 D Mms/Contact: [start]    init() consume time = 0.69901
,06-30 12:52:16.341  1748  2070 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 12:52:16.341  1014  3078 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
06-30 12:52:16.341  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.341  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.341  1014  3078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-30 12:52:16.351  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:16.361  1457  5756 D TP/MmsSmsProvider: query,matched:13, calling pid = 6636
,06-30 12:52:16.361  6636  6636 D Mms/Contact: [end]    init consume time = 27.951823
,06-30 12:52:16.361  1457  5756 D TP/MmsSmsProvider: match 13:Elapsed time : 2.006 ms
,06-30 12:52:16.371  1014  1393 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 12:52:16.371  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.371  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.371  1014  1393 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:16.371  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:16.371  6636  6760 D Mms/DraftCache: [start]    rebuildCache consume time = 14.144115
,06-30 12:52:16.381  1457  1472 D TP/MmsSmsProvider: query,matched:12, calling pid = 6636
,06-30 12:52:16.381  1457  1472 D TP/MmsSmsProvider: match 12:Elapsed time : 1.444 ms
,06-30 12:52:16.381  6636  6636 D Mms/MethodReflector: getSubId is called
06-30 12:52:16.381  6636  6636 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,06-30 12:52:16.381  6636  6636 D Mms/MethodReflector: getTelephonyProperty is called
,06-30 12:52:16.381  1014  1393 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
06-30 12:52:16.381  6636  6636 D Mms/DownloadManager: roaming -> false (slotId = 0)
,06-30 12:52:16.381  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
06-30 12:52:16.381  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.381  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.381  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.381  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.391  6636  6636 D Mms/DownloadManager: auto download without roaming -> true
06-30 12:52:16.391  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
06-30 12:52:16.391  6636  6636 D Mms/MethodReflector: getSubId is called
,06-30 12:52:16.401  6636  6636 D Mms/MethodReflector: getDefaultSmsSubId is called
,06-30 12:52:16.401  6636  6636 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
06-30 12:52:16.401  6636  6636 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
06-30 12:52:16.401  6636  6636 D Mms/MethodReflector: getTelephonyProperty is called
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: roaming -> false (slotId = 1)
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: auto download without roaming -> true
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: auto download during roaming secondary -> false
06-30 12:52:16.401  6636  6636 D Mms/DownloadManager: mAutoDownload ------> true
,06-30 12:52:16.401  6763  6763 E Zygote  : MountEmulatedStorage()
06-30 12:52:16.401  6763  6763 E Zygote  : v2
06-30 12:52:16.401  6763  6763 I libpersona: KNOX_SDCARD checking this for 10037
06-30 12:52:16.401  6763  6763 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:16.401  6763  6763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:16.411  1014  1393 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6763 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:52:16.411  6763  6763 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:16.411  6763  6763 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,06-30 12:52:16.411  6636  6760 D Mms/DraftCache: [end]    rebuildCache consume time = 34.82526
,06-30 12:52:16.421  6763  6763 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.431  6763  6763 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.441  6763  6763 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 12:52:16.451  6636  6718 D Mms/ArtClassLoader: init [DONE] art
,06-30 12:52:16.461  6636  6636 D ComposerPerformance: 1467283936465 ms / [DONE] Composer constructor
,06-30 12:52:16.461  6763  6763 I CalendarProvider2: CalendarProvider2.onCreate() called
,06-30 12:52:16.471  6636  6636 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,06-30 12:52:16.471  6636  6636 I Mms/ReservationManager: ReservationManager()
,06-30 12:52:16.471  6636  6636 I Mms/ReservationManager: resetAfterConnected()
06-30 12:52:16.471  6636  6778 D Mms/Conversation: [start]    init() consume time = 63.177969
,06-30 12:52:16.471  1457  1472 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,06-30 12:52:16.481  1457  1472 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
06-30 12:52:16.481  1457  1472 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,06-30 12:52:16.481  1457  1472 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,06-30 12:52:16.481  1457  1665 D TP/MmsSmsProvider: query,matched:7, calling pid = 6636
,06-30 12:52:16.481  1457  1665 D TP/MmsSmsProvider: match 7:Elapsed time : 3.289 ms
,06-30 12:52:16.481  6636  6636 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,06-30 12:52:16.491  6636  6636 D Mms/MmsApp: [end]    onCreate() consume time = 14.370416
,06-30 12:52:16.491  1457  1472 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,06-30 12:52:16.491  1457  1472 D TP/MmsSmsProvider: need read changed broadcast:false
,06-30 12:52:16.491  6636  6778 D Mms/Conversation: [end]    init consume time = 2.336094
,06-30 12:52:16.491  6636  6778 D Mms/MessagingNotification: [start]    init() consume time = 0.575677
06-30 12:52:16.491  6636  6636 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,06-30 12:52:16.491  6636  6636 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,06-30 12:52:16.491  1014  3079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,06-30 12:52:16.491  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.491  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.491  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.491  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.501  6636  6636 D Mms/MethodReflector: getSubId is called
,06-30 12:52:16.511  6636  6636 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1,
,06-30 12:52:16.511  6636  6636 D Mms/MethodReflector: getTelephonyProperty is called
06-30 12:52:16.511  6636  6636 D Mms/DownloadManager: roaming -> false (slotId = 0)
,06-30 12:52:16.511  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
06-30 12:52:16.511  6636  6636 D Mms/DownloadManager: auto download without roaming -> true
06-30 12:52:16.511  6636  6636 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
06-30 12:52:16.511  6636  6636 D Mms/DownloadManager: mAutoDownload ------> true
,06-30 12:52:16.511  1014  3079 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6780 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 12:52:16.511  1014  3079 I ActivityManager: Killing 6389:com.android.chrome/u0a77 (adj 15): empty #21
,06-30 12:52:16.511  6780  6780 E Zygote  : MountEmulatedStorage()
06-30 12:52:16.511  6780  6780 E Zygote  : v2
06-30 12:52:16.511  6780  6780 I libpersona: KNOX_SDCARD checking this for 10058
06-30 12:52:16.511  6780  6780 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:16.511  6780  6780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:16.521  6780  6780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:16.521  6780  6780 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:16.521  6636  6778 D Mms/MessagingNotification: [end]    init consume time = 29.933334
,06-30 12:52:16.521  1457  1475 D TP/MmsSmsProvider: query,matched:0, calling pid = 6636
,06-30 12:52:16.531  1457  1475 V TP/MmsSmsProvider: getSimpleConversations entered.
,06-30 12:52:16.531  1457  1475 D TP/MmsSmsProvider: match 0:Elapsed time : 2.456 ms
,06-30 12:52:16.531  6780  6780 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.531  6780  6780 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.541  6636  6786 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 16.330312
,06-30 12:52:16.541  1457  1472 D TP/MmsSmsProvider: query,matched:400, calling pid = 6636
,06-30 12:52:16.551  6636  6786 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 14.545937
,06-30 12:52:16.551  6636  6788 D Mms/Synchronizer: [start]    doSync consume time = 0.511407
,06-30 12:52:16.551  1457  1475 D TP/MmsSmsProvider: update, matched:300, calling pid = 6636
06-30 12:52:16.551  1457  1475 V TP/MmsSmsProvider: syncDBData start
,06-30 12:52:16.551  1457  1475 V TP/MmsSmsProvider: syncDBData sms end
,06-30 12:52:16.551  1457  1475 V TP/MmsSmsProvider: syncDBData mms end
,06-30 12:52:16.551  1457  1475 V TP/MmsSmsProvider: syncDBData end
06-30 12:52:16.551  1014  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,06-30 12:52:16.561  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.561  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.561  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.561  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.571  6798  6798 E Zygote  : MountEmulatedStorage(),
06-30 12:52:16.571  6798  6798 E Zygote  : v2
06-30 12:52:16.571  6798  6798 I libpersona: KNOX_SDCARD checking this for 10068
06-30 12:52:16.571  6798  6798 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:16.571  6798  6798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:16.571  1014  1027 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6798 uid=10068 gids={50068, 9997} abi=armeabi-v7a
06-30 12:52:16.571  6798  6798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:16.581  6798  6798 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
06-30 12:52:16.581  6636  6788 D Mms/Synchronizer: [end]    doSync consume time = 24.869635
,06-30 12:52:16.591  6798  6798 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.591  6798  6798 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.601  1014  1519 I ActivityManager: Killing 6266:com.google.android.music:main/u0a108 (adj 15): empty #21
,06-30 12:52:16.611  6798  6798 D BadgeProvider: onCreate
,06-30 12:52:16.611  6798  6798 D BadgeProvider: DatabaseHelper
,06-30 12:52:16.621  1014  1519 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
06-30 12:52:16.621  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.621  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.621  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:16.621  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,06-30 12:52:16.631  6780  6780 I ExternalOEMControlProvider: onCreate
,06-30 12:52:16.641  6780  6815 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,06-30 12:52:16.651  6636  6778 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,06-30 12:52:16.651  1457  1472 D TP/SmsProvider: query,matched:26, calling pid = 6636
,06-30 12:52:16.651  1457  1472 D TP/SmsProvider: match 26:Elapsed time : 1.873 ms
,06-30 12:52:16.651  1014  1120 I ActivityManager: Killing 6423:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,06-30 12:52:16.661  1707  1707 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,06-30 12:52:16.671  1707  1707 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,06-30 12:52:16.671  1014  1519 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,06-30 12:52:16.681  1457  1665 D TP/MmsSmsProvider: query,matched:6, calling pid = 6636
,06-30 12:52:16.681  1457  1665 D TP/MmsSmsProvider: match 6:Elapsed time : 1.380 ms
,06-30 12:52:16.691  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.691  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.691  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 12:52:16.701  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.701  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.701  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 12:52:16.711  1014  1393 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,06-30 12:52:16.711  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.711  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.711  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.711  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.721  6817  6817 E Zygote  : MountEmulatedStorage()
06-30 12:52:16.721  6817  6817 E Zygote  : v2
,06-30 12:52:16.721  6817  6817 I libpersona: KNOX_SDCARD checking this for 10023
06-30 12:52:16.721  6817  6817 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:16.721  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:16.731  1014  1393 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6817 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,06-30 12:52:16.731  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:16.731  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:16.751  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.751  6817  6817 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.751  1014  3079 I ActivityManager: Killing 6459:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,06-30 12:52:16.781  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.781  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.781  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.791  1014  3079 I ActivityManager: Killing 6510:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,06-30 12:52:16.791  1014  1519 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:16.791  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.791  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.791  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.791  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.791  1014  1496 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,06-30 12:52:16.791  1622  2547 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 12:52:16.791  1014  1496 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
06-30 12:52:16.791  1014  1496 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
06-30 12:52:16.791  1014  1496 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,06-30 12:52:16.791  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.791  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.791  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.801  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.801  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.801  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:16.801  6358  6384 I SA      : [RC New] [v2liruge] api execute + 803
,06-30 12:52:16.801  6358  6384 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,06-30 12:52:16.811  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.811  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:16.811  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.811  1622  1622 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 12:52:16.811  6358  6384 I System.out: AsyncTask #1 calls detatch()
,06-30 12:52:16.811  6817  6817 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,06-30 12:52:16.821  6358  6384 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,06-30 12:52:16.821  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.821  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.821  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.821  6358  6384 I SA      : [OCP] update openData : EU
,06-30 12:52:16.821  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.821  6358  6384 I SA      : [TPMU] getNetworkMcc : 260
06-30 12:52:16.821  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:16.821  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.831  6358  6384 I SA      : [SRS] prepareGetMyCountryZone
,06-30 12:52:16.841  1729  1729 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 12:52:16.841  1014  1120 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:16.841  6636  6778 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,06-30 12:52:16.841  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.841  6358  6384 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
06-30 12:52:16.841  6358  6384 I SA      : [SSP] query invoked
,06-30 12:52:16.841  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.841  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.841  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.841  6358  6384 I SA      : [TPMU] GetMccFromDB : null
06-30 12:52:16.841  6358  6384 I SA      : [SCU] getMccFromPreferece mcc = 316
06-30 12:52:16.841  6358  6384 I SA      : [TPM] isNoProxy(default) : true
06-30 12:52:16.841  6358  6384 I SA      : [RC New] Execute method=[GET] start
,06-30 12:52:16.841  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.841  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.841  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.851  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.851  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.851  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.851  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.851  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.851  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,06-30 12:52:16.861  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
06-30 12:52:16.861  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.861  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,06-30 12:52:16.861  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,06-30 12:52:16.871  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,06-30 12:52:16.871  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,06-30 12:52:16.871  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,06-30 12:52:16.871  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,06-30 12:52:16.871  6817  6817 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,06-30 12:52:16.871  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.871  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.871  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.881  1014  1391 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:16.881  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.881  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.881  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.881  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.881  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.881  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:16.881  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:16.891  6358  6384 I SA      : [RC New] Security=[true],
06-30 12:52:16.891  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:16.891  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):isShipBuild true
06-30 12:52:16.891  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:16.891  6358  6384 I System.out: Thread-1130(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:16.891  6832  6832 E Zygote  : MountEmulatedStorage(),
,06-30 12:52:16.901  6832  6832 E Zygote  : v2
06-30 12:52:16.901  6832  6832 I libpersona: KNOX_SDCARD checking this for 10011
06-30 12:52:16.901  6832  6832 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:16.901  6832  6832 I libpersona: KNOX_SDCARD not a persona,
,06-30 12:52:16.901  6832  6832 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:16.901  6832  6832 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:16.901  1014  1391 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6832 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,06-30 12:52:16.901  1014  3078 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:16.901   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:16.901  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.901  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.901  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.911  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.911  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.911  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.911  1014  1393 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:16.911  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,06-30 12:52:16.911  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.911  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.911  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.911  1729  6840 D LocationInitializer: Restart initialization of location
,06-30 12:52:16.921  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.921  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.921  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.931  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.931  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.931  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.931  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 12:52:16.931  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.931  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.931  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.931  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.931  1014  1120 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
06-30 12:52:16.931  1014  1120 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
06-30 12:52:16.931  1622  3617 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 12:52:16.931  1014  1120 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
06-30 12:52:16.931  1014  1120 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,06-30 12:52:16.931  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.931  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.931  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.941  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.941  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.941  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.951  6832  6832 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:16.951  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:16.951  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.951  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:16.951  6832  6832 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:16.951  1622  1622 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 12:52:16.961  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.961  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:16.961  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.961  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.961  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.961  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.971  1729  1729 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 12:52:16.971  1014  3078 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:16.971  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,06-30 12:52:16.971  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.971  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:16.971  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.981  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.981  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.981  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,06-30 12:52:16.981  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.981  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.981  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.981  6832  6832 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:52:16.981  6832  6832 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:16.991  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.991  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.991  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:16.991  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:16.991  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:16.991  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.001  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.001  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.001  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.001  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:17.001  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.001  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.001  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.011  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.011  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.011  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.011  6832  6832 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:52:17.011  6832  6832 I MultiDex: install
06-30 12:52:17.011  6832  6832 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:52:17.011  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.011  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.011  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.021  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:17.021  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,06-30 12:52:17.021  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.021  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.021  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.021  1729  6848 D LocationInitializer: Restart initialization of location
,06-30 12:52:17.021  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.021  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.021  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.031  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:17.031  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.031  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.031  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.031  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.041  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.041  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.041  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.041  1014  3079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:17.041  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.041  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.041  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.041  6832  6832 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-30 12:52:17.041  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:17.041  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.051  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.051  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.051  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.051  1014  3079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:17.051  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.051  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.051  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.071  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.071  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.071  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.071  1014  1519 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:17.071  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.081   288   732 I WVCdm   : CdmEngine::CloseSession
,06-30 12:52:17.081  6832  6832 D WearableService: callingUid 10011, callindPid: 6832
,06-30 12:52:17.081  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.081   288   732 I WVCdm   : L3 Terminate.
06-30 12:52:17.081  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.081  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.091  1622  4513 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,06-30 12:52:17.091  1014  1393 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
06-30 12:52:17.091  1014  1393 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
06-30 12:52:17.091  1014  1393 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
06-30 12:52:17.091  1014  1393 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,06-30 12:52:17.111  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.111  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.111  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.111  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.111  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.111  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.121  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.121  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.121  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.131  1597  2419 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 12:52:17.131  1622  1622 I art     : Explicit concurrent mark sweep GC freed 11703(651KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/11MB, paused 1ms total 44.587ms
,06-30 12:52:17.141  1622  1622 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 12:52:17.141  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.141  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.141  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.151  1597  2419 E MDM     : [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 12:52:17.151  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.151  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.151  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.151  1729  1729 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 12:52:17.151  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:17.151  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.151  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.151  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.151  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.161  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.161  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.161  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.161  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.161  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:17.171  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.171  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.171  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.171  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.181  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.181  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.181  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.191  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.191  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.191  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:17.191  1597  2549 E MDM     : [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 12:52:17.191  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:17.191  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.191  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.191  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.201  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.201  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.201  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.201  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:17.201  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,06-30 12:52:17.201  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.201  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.201  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.201  1729  6855 D LocationInitializer: Restart initialization of location
,06-30 12:52:17.211  1014  1391 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:17.211  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:17.211  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.211  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.211  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.211  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.261  1729  6311 I CheckinRequestBuilder: Classify the device as Phone.
,06-30 12:52:17.261  1729  6311 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-30 12:52:17.271  1014  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:17.271  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.271  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.271  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.281  1014  1519 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 12:52:17.281  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.281  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.281  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:17.281  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:17.431  1729  6311 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:17.441   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:17.441   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:17.481  1729  6311 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:17.631  6763  6763 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,06-30 12:52:17.631  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.631  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.631  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,06-30 12:52:17.641  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.641  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.641  1014  1393 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.641  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,06-30 12:52:17.641  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.641  1014  3079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.641  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:17.651  1014  1027 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
06-30 12:52:17.651  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,06-30 12:52:17.651  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:17.651  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.651  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:17.661  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.661  1014  3078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.661  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:17.661  1014  1519 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,06-30 12:52:17.661  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
06-30 12:52:17.671  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:17.671  1014  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 12:52:17.671  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,06-30 12:52:17.681  1014  3078 I ActivityManager: Killing 6560:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,06-30 12:52:17.801  1729  6311 I CheckinTask: Sending checkin request (10630 bytes)
,06-30 12:52:17.901   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:52:18.011  1729  6311 I CheckinResponseProcessor: From server: 10 gservices updates and 7 deletes
,06-30 12:52:18.181  1014  3078 D SettingsProvider: name = notification_sound_set
,06-30 12:52:18.181  1014  3078 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.191  1014  3078 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.191  1014  3078 D SettingsProvider: selectionArgs: false
06-30 12:52:18.191  1014  3078 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.191  1014  3078 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.191  1014  3078 D SettingsProvider: ret = -1
,06-30 12:52:18.191  1014  1393 D SettingsProvider: name = ringtone_set
,06-30 12:52:18.191  1014  1393 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.191  1014  1393 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.191  1014  1393 D SettingsProvider: selectionArgs: false
06-30 12:52:18.191  1014  1393 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.191  1014  1393 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.191  1014  1393 D SettingsProvider: ret = -1
,06-30 12:52:18.201  1014  1480 D SettingsProvider: name = alarm_alert_set
,06-30 12:52:18.201  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.201  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.201  1014  1480 D SettingsProvider: selectionArgs: false
06-30 12:52:18.201  1014  1480 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.201  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:18.201  1014  1480 D SettingsProvider: ret = -1
,06-30 12:52:18.201  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,06-30 12:52:18.211  1014  1120 D SettingsProvider: name = lockscreen.options
06-30 12:52:18.211  1014  1120 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.211  1014  1120 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.211  1014  1120 D SettingsProvider: selectionArgs: false
06-30 12:52:18.211  1014  1120 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.211  1014  1120 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.211  1014  1120 D SettingsProvider: ret = -1
,06-30 12:52:18.211  1014  1393 D SettingsProvider: name = serial_blacklist
06-30 12:52:18.211  1014  1393 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.211  1014  1393 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.211  1014  1393 D SettingsProvider: selectionArgs: false
06-30 12:52:18.211  1014  1393 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.211  1014  1393 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.211  1014  1393 D SettingsProvider: ret = -1
,06-30 12:52:18.211  1014  1027 D SettingsProvider: name = facelock_liveliness_recognition_threshold
06-30 12:52:18.211  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.211  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.211  1014  1027 D SettingsProvider: selectionArgs: false
06-30 12:52:18.211  1014  1027 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.211  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.211  1014  1027 D SettingsProvider: ret = -1
,06-30 12:52:18.211  1014  1480 D SettingsProvider: name = config_update_certificate
06-30 12:52:18.211  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
06-30 12:52:18.211  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.211  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,06-30 12:52:18.211  1014  1480 D SettingsProvider: selectionArgs: false
06-30 12:52:18.211  1014  1480 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.211  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.211  1014  1480 D SettingsProvider: ret = -1
,06-30 12:52:18.221  1014  1027 D SettingsProvider: name = pubkey_blacklist
06-30 12:52:18.221  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.221  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.221  1014  1027 D SettingsProvider: selectionArgs: false
06-30 12:52:18.221  1014  1027 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.221  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.221  1014  1027 D SettingsProvider: ret = -1
,06-30 12:52:18.221  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,06-30 12:52:18.221  1014  6862 I CertBlacklister: Certificate blacklist changed, updating...
,06-30 12:52:18.231  1014  3078 D SettingsProvider: name = dropbox:data_app_crash
06-30 12:52:18.231  1014  3078 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.231  1014  3078 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  3078 D SettingsProvider: selectionArgs: false
06-30 12:52:18.231  1014  3078 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.231  1014  3078 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.231  1014  3078 D SettingsProvider: ret = -1
,06-30 12:52:18.231  1014  1120 D SettingsProvider: name = facelock_max_center_movement
06-30 12:52:18.231  1014  1120 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.231  1014  1120 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  1120 D SettingsProvider: selectionArgs: false
06-30 12:52:18.231  1014  1120 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.231  1014  1120 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:18.231  1014  1120 D SettingsProvider: ret = -1
06-30 12:52:18.231  1014  1519 D SettingsProvider: name = send_action_app_error
06-30 12:52:18.231  1014  1519 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.231  1014  1519 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  1519 D SettingsProvider: selectionArgs: false
06-30 12:52:18.231  1014  1519 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.231  1014  1519 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.231  1014  1519 D SettingsProvider: ret = -1
,06-30 12:52:18.231  1014  1496 D SettingsProvider: name = facelock_detection_threshold
06-30 12:52:18.231  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.231  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  1496 D SettingsProvider: selectionArgs: false
06-30 12:52:18.231  1014  1496 D SettingsProvider: selectionArgs: 10011
,06-30 12:52:18.231  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.231  1014  1496 D SettingsProvider: ret = -1
06-30 12:52:18.231  1014  1220 D SettingsProvider: name = dropbox:data_app_anr
06-30 12:52:18.231  1014  1220 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.231  1014  1220 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  1220 D SettingsProvider: selectionArgs: false
,06-30 12:52:18.231  1014  1220 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.231  1014  1220 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.231  1014  1220 D SettingsProvider: ret = -1
06-30 12:52:18.231  1014  1480 D SettingsProvider: name = web_autofill_query_url
06-30 12:52:18.231  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,06-30 12:52:18.231  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.231  1014  1480 D SettingsProvider: selectionArgs: false
06-30 12:52:18.231  1014  1480 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.231  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.231  1014  1480 D SettingsProvider: ret = -1
,06-30 12:52:18.231  1014  1393 D SettingsProvider: name = ssl_session_cache
,06-30 12:52:18.231  1014  1393 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.241  1014  1393 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.241  1014  1393 D SettingsProvider: selectionArgs: false
06-30 12:52:18.241  1014  1393 D SettingsProvider: selectionArgs: 10011
,06-30 12:52:18.241  1014  6862 I CertBlacklister: Certificate blacklist updated
,06-30 12:52:18.241  1014  1393 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.241  1014  1393 D SettingsProvider: ret = -1
,06-30 12:52:18.241  1014  1479 D SettingsProvider: name = print_service_search_uri
,06-30 12:52:18.241  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.241  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.241  1014  1479 D SettingsProvider: selectionArgs: false
06-30 12:52:18.241  1014  1479 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.241  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 12:52:18.241  1014  1479 D SettingsProvider: ret = -1
,06-30 12:52:18.241  1014  3079 D SettingsProvider: name = masterLocationPackagePrefixBlacklist
06-30 12:52:18.241  1014  3079 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.241  1014  3079 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.241  1014  3079 D SettingsProvider: selectionArgs: false
06-30 12:52:18.241  1014  3079 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.241  1014  3079 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.241  1014  3079 D SettingsProvider: ret = -1
,06-30 12:52:18.241  1014  1391 D SettingsProvider: name = masterLocationPackagePrefixWhitelist
06-30 12:52:18.241  1014  1391 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.241  1014  1391 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.241  1014  1391 D SettingsProvider: selectionArgs: false
06-30 12:52:18.241  1014  1391 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.241  1014  1391 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.241  1014  1391 D SettingsProvider: ret = -1
,06-30 12:52:18.241  1014  1026 D SettingsProvider: name = dropbox:data_app_wtf
06-30 12:52:18.241  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.241  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.241  1014  1026 D SettingsProvider: selectionArgs: false
06-30 12:52:18.241  1014  1026 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.241  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.241  1014  1026 D SettingsProvider: ret = -1
06-30 12:52:18.251  1014  1027 D SettingsProvider: name = sms_short_codes_metadata_url
06-30 12:52:18.251  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.251  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.251  1014  1027 D SettingsProvider: selectionArgs: false
06-30 12:52:18.251  1014  1027 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.251  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.251  1014  1027 D SettingsProvider: ret = -1
06-30 12:52:18.251  1014  1027 D SettingsProvider: name = cert_pin_metadata_url
06-30 12:52:18.251  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.251  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.251  1014  1027 D SettingsProvider: selectionArgs: false
06-30 12:52:18.251  1014  1027 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.251  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.251  1014  1027 D SettingsProvider: ret = -1
06-30 12:52:18.251  1014  1120 D SettingsProvider: name = send_action_app_error
06-30 12:52:18.251  1014  1120 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.251  1014  1120 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.251  1014  1120 D SettingsProvider: selectionArgs: false
06-30 12:52:18.251  1014  1120 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.251  1014  1120 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.251  1014  1120 D SettingsProvider: ret = -1
06-30 12:52:18.251  1014  1519 D SettingsProvider: name = cert_pin_content_url
06-30 12:52:18.251  1014  1519 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.251  1014  1519 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.251  1014  1519 D SettingsProvider: selectionArgs: false
06-30 12:52:18.251  1014  1519 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.251  1014  1519 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.251  1014  1519 D SettingsProvider: ret = -1
06-30 12:52:18.251  1014  1496 D SettingsProvider: name = sms_short_codes_content_url
06-30 12:52:18.251  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 12:52:18.251  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 12:52:18.251  1014  1496 D SettingsProvider: selectionArgs: false
06-30 12:52:18.251  1014  1496 D SettingsProvider: selectionArgs: 10011
06-30 12:52:18.251  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
06-30 12:52:18.251  1014  1496 D SettingsProvider: ret = -1
06-30 12:52:18.261  1622  2016 I GservicesProvider: main difference update completed
06-30 12:52:18.261  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.261  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.261  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
06-30 12:52:18.271  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.271  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.RefreshEnabledStateService; callingUser = 0; userId(target) = 0
06-30 12:52:18.271  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.271  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.271  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:18.271  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.271  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.PlayLogMonitorIntervalService; callingUser = 0; userId(target) = 0
06-30 12:52:18.271  1729  6311 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
06-30 12:52:18.271  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.271  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.271  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:18.281  1014  1479 I splitIntent: intent=com.google.gservices.intent.action.GSERVICES_CHANGED will be not split. because same process=com.google.android.gms is in other queue. index=1
06-30 12:52:18.281  1014  1479 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
06-30 12:52:18.281  1014  1479 I splitIntent: other index=10, name=com.google.android.gms com.google.android.gms.ads.config.GServicesChangedReceiver
06-30 12:52:18.281  1014  1479 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.gservices.intent.action.GSERVICES_CHANGED !! do not split it!!
06-30 12:52:18.281  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.281  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.281  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
06-30 12:52:18.291  1014  1519 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.291  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
06-30 12:52:18.301  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.301  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.301  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:18.301  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.301  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.301  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.321  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.321  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.321  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.331  1729  1729 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,06-30 12:52:18.331  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.331  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.331  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.331  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.331  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.341  1729  1729 D SystemUpdateService: onCreate
,06-30 12:52:18.341  1014  1496 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:18.341  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.341  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.341  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
06-30 12:52:18.351  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 12:52:18.351  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.351  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.351  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.351  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.351  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.351  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.351  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.371  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.371  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.371  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.371  1622  2408 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,06-30 12:52:18.381  1729  1729 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,06-30 12:52:18.381  1729  6866 I SystemUpdateService: cancelUpdate (empty URL)
06-30 12:52:18.381  1729  6866 I SystemUpdateService: active receiver: disabled
,06-30 12:52:18.391  1729  1729 I OcrUtils: Updating ocr activity enabled=false
,06-30 12:52:18.391  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.391  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.391  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.401  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.401  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.401  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.401  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.401  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.411  1729  1729 D SystemUpdateService: onDestroy
,06-30 12:52:18.411  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.411  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.411  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.411  1597  1597 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
06-30 12:52:18.411  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:18.411  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.411  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
06-30 12:52:18.411  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.411  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.421  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.421  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.421  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.441  1014  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:18.441  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.441  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.441  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.441  1597  1597 I GCoreUlr: DispatchingService.onCreate()
,06-30 12:52:18.471  6207  6207 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 12:52:18.481  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.481  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.481  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.491  6636  6636 I Mms/MmsApp:  start initViewCache mms
,06-30 12:52:18.491  6636  6636 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1913.23802
06-30 12:52:18.491  6636  6636 D Mms/ComposeMessageFragment: fillCache, easy = false
,06-30 12:52:18.551  1597  6869 I art     : Explicit concurrent mark sweep GC freed 18151(935KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 7MB/12MB, paused 1.020ms total 53.061ms
,06-30 12:52:18.571  1014  1120 I art     : Explicit concurrent mark sweep GC freed 26621(1416KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 2.604ms total 142.631ms
,06-30 12:52:18.601  6636  6636 D AbsListView: Get MotionRecognitionManager
,06-30 12:52:18.611  1014  1027 D MotionRecognitionService:  ssp status : false
,06-30 12:52:18.611  1597  6869 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,06-30 12:52:18.611  6636  6636 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 123.178542
,06-30 12:52:18.641  1729  6311 I CheckinRequestBuilder: Classify the device as Phone.
,06-30 12:52:18.641  1729  6311 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,06-30 12:52:18.701  1622  1675 I art     : Explicit concurrent mark sweep GC freed 12935(599KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/11MB, paused 991us total 47.447ms
,06-30 12:52:18.701  6636  6636 D Mms/BubbleViewCache: fillCache bubble = 1
,06-30 12:52:18.751  1597  6869 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,06-30 12:52:18.761  1597  6869 I GCoreUlr: Unbound from all location providers
,06-30 12:52:18.771  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.771  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.771  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.781  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:18.781  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 12:52:18.781  1597  1597 I GCoreUlr: DispatchingService.onDestroy()
,06-30 12:52:18.781  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.781  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.781  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.781  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.781  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.781  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.781  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:18.781  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.791  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.791  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.791  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.791  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:18.791  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.801  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.801  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.801  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.801  1597  1597 I GCoreUlr: Unbound from all location providers
,06-30 12:52:18.801  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.811  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.811  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.811  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.811  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.811  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.811  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.821  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.821  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:18.821  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.831  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.831  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.831  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.831  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.841  1014  1519 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:18.841  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.841  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.841  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.841  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:18.841  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.841  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:18.841  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
06-30 12:52:18.841  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.partnersetup
06-30 12:52:18.841  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:18.841  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:18.841  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:18.841  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,06-30 12:52:18.851  6877  6877 E Zygote  : MountEmulatedStorage()
,06-30 12:52:18.861  6877  6877 E Zygote  : v2
06-30 12:52:18.861  6877  6877 I libpersona: KNOX_SDCARD checking this for 10014
06-30 12:52:18.861  6877  6877 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:18.861  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:18.861  1014  1480 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6877 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a,
06-30 12:52:18.861  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:18.861  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,06-30 12:52:18.881  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:18.881  6877  6877 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:18.881  1729  6311 I art     : Explicit concurrent mark sweep GC freed 16451(855KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 9MB/15MB, paused 1.122ms total 58.658ms
,06-30 12:52:18.901  1729  6311 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,06-30 12:52:18.921  1729  6311 I CheckinService: Checking schedule, now: 1467283938925 next: 1467863144909
,06-30 12:52:18.921  1729  6311 I CheckinService: active receiver: disabled
,06-30 12:52:18.931  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
06-30 12:52:18.931  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.951  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.951  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:18.951  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,06-30 12:52:18.951  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 12:52:18.951  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.951  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.951  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.951  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,06-30 12:52:18.961  1014  1393 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
06-30 12:52:18.961  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.961  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.961  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.961  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,06-30 12:52:18.961  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 12:52:18.961  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,06-30 12:52:18.961  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.961  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.961  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,06-30 12:52:18.961  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,06-30 12:52:18.961  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.LauncherConfigService; callingUser = 0; userId(target) = 0
06-30 12:52:18.961  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:18.961  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.961  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,06-30 12:52:18.971  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:18.971  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:18.971  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,06-30 12:52:18.971  1729  6892 I CheckinService: Checking schedule, now: 1467283938981 next: 1467863144909
,06-30 12:52:18.971  1729  6892 I CheckinService: active receiver: disabled
,06-30 12:52:19.001  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.001  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.001  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.googlequicksearchbox
06-30 12:52:19.001  1014  1120 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,06-30 12:52:19.001  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.001  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.001  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.001  1014  1120 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:19.011  6901  6901 E Zygote  : MountEmulatedStorage()
06-30 12:52:19.011  6901  6901 I libpersona: KNOX_SDCARD checking this for 10052
06-30 12:52:19.011  6901  6901 E Zygote  : v2
06-30 12:52:19.011  6901  6901 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:19.011  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:19.011  1014  1120 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6901 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,06-30 12:52:19.021  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:19.021  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:19.031  6358  6384 I SA      : [RC New] [v2liruge] api execute + 2141
06-30 12:52:19.031  6358  6384 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,06-30 12:52:19.031  6358  6384 I System.out: AsyncTask #1 calls detatch()
06-30 12:52:19.031  6358  6384 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,06-30 12:52:19.051  6358  6384 I SA      : [OCP] update openData : EU
,06-30 12:52:19.061  6358  6384 I SA      : [TPMU] getNetworkMcc : 260
,06-30 12:52:19.061  6358  6384 I SA      : [RC New] executeRequest [v2liruge] end. 2215
06-30 12:52:19.061  6358  6384 I SA      : [RC New] Execute end
06-30 12:52:19.061  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:19.061  6358  6384 I SA      : [RC New] executeRequest [v2liruge] end. 3119
06-30 12:52:19.061  6358  6384 I SA      : [RC New] Execute end
06-30 12:52:19.061  6901  6901 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:19.061  6358  6358 I SA      : [OR] GetMyCountryZoneTask mcc = null
06-30 12:52:19.061  6358  6358 I SA      : [OR] GetMyCountryZoneTask Fail
,06-30 12:52:19.141   297   297 E SMD     : DCD OFF
,06-30 12:52:19.151  1014  1220 I ActivityManager: Killing 6081:com.android.email/u0a141 (adj 15): empty #21
,06-30 12:52:19.301  1014  1027 D LocationManagerService: getProviders()=[passive, gps]
,06-30 12:52:19.351  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:19.351  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.351  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
06-30 12:52:19.351  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,06-30 12:52:19.351  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:19.351  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.351  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.351  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:19.371  6925  6925 E Zygote  : MountEmulatedStorage()
06-30 12:52:19.371  6925  6925 E Zygote  : v2
06-30 12:52:19.371  6925  6925 I libpersona: KNOX_SDCARD checking this for 10082
06-30 12:52:19.371  6925  6925 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:19.371  6925  6925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:19.371  1014  1479 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6925 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
06-30 12:52:19.371  6925  6925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:19.371  1014  1479 I ActivityManager: Killing 6575:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
06-30 12:52:19.381  6925  6925 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:19.401  6925  6925 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:19.401  6925  6925 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:19.411  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-30 12:52:19.411  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,06-30 12:52:19.411  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.411  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:19.411  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-30 12:52:19.431  6901  6943 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,06-30 12:52:19.441  6901  6944 I GservicesUpdateTask: Updating Gservices keys
,06-30 12:52:19.451  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.451  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.451  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,06-30 12:52:19.461  6925  6925 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 12:52:19.461  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:19.461  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.461  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,06-30 12:52:19.471  6901  6944 I GStaticConfiguration: #getNewConfigurationUrl [pref=2016_04_08_14_33_37, gservice=2016_06_27_18_09_34]
,06-30 12:52:19.481  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.481  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.481  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,06-30 12:52:19.481  6925  6925 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION,
,06-30 12:52:19.491  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:19.491  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:19.491  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,06-30 12:52:19.491  6925  6925 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 12:52:19.491  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.491  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.491  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,06-30 12:52:19.501  6925  6925 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,06-30 12:52:19.501  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.501  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.501  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.apps.plus
06-30 12:52:19.501  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,06-30 12:52:19.501  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.501  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.501  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:19.501  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:19.521  6958  6958 E Zygote  : MountEmulatedStorage()
,06-30 12:52:19.521  6958  6958 E Zygote  : v2
06-30 12:52:19.521  6958  6958 I libpersona: KNOX_SDCARD checking this for 10117
06-30 12:52:19.521  6958  6958 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:19.521  6958  6958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 12:52:19.521  6958  6958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:19.521  1014  1519 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=6958 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:52:19.521  6958  6958 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:19.541  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:19.541  6958  6958 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:19.571  6958  6958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 12:52:19.591  6901  6944 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:52:19.661   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:19.661   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,06-30 12:52:19.861  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.861  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:19.861  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:19.861  1014  1220 I ActivityManager: Killing 6146:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,06-30 12:52:19.881  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:19.881  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.881  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:19.901  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.901  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.901  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:19.901  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:19.901  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:19.901  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:19.901  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:19.901  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:19.911  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.911  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.911  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:19.941  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:19.941  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.941  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:19.941  1622  2540 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,06-30 12:52:19.941  1729  1729 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
06-30 12:52:19.941  1729  1729 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
06-30 12:52:19.941  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,06-30 12:52:19.941  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 7571434 is smaller than the required version 8400000
,06-30 12:52:19.951  1014  1519 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:19.951  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:19.951  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,06-30 12:52:19.981  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:19.981  1014  1120 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:52:19.981  1014  1120 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:19.981  1014  1120 D BatteryService: stay LED for fully charged
06-30 12:52:19.981  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:19.981  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:52:19.991  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:19.991  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:19.991  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:19.991  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:52:19.991  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:20.011  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:20.011  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:20.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:20.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:20.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:20.231  1014  1026 I ActivityManager: Killing 6538:com.sec.android.fotaclient/u0a8 (adj 15): empty #21,
,06-30 12:52:22.141   297   297 E SMD     : DCD OFF
,06-30 12:52:22.201  1014  1120 I ActivityManager: Killing 6358:com.osp.app.signin/u0a36 (adj 15): empty #21
,06-30 12:52:22.251  1014  3079 I ActivityManager: Killing 6601:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,06-30 12:52:22.481  6207  6207 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 12:52:22.481  6207  6207 I dhcpcd  : wlan0: no IPv6 Routers available
,06-30 12:52:23.721  1014  1120 I ActivityManager: Killing 6617:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,06-30 12:52:24.821  1014  1519 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,06-30 12:52:24.821  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0,
,06-30 12:52:24.821  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:24.821  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:24.821  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,06-30 12:52:24.841  6958  6988 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,06-30 12:52:25.141   297   297 E SMD     : DCD OFF,
,06-30 12:52:25.861  1014  2720 D SSRM:n  : SIOP:: AP = 340
,06-30 12:52:27.311   285   520 D WVMDrmPlugIn: WVMDrmPlugin::onTerminate : 3036
,06-30 12:52:28.141   297   297 E SMD     : DCD OFF
,06-30 12:52:28.251  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:28.951  1014  1054 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,06-30 12:52:28.991  1014  1054 D PackageManager: [MSG] WRITE_SETTINGS
,06-30 12:52:29.001  3680  3680 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,06-30 12:52:29.001  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 12:52:29.111  1014  1014 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,06-30 12:52:29.111  3276  3276 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,06-30 12:52:29.131  1014  1220 I splitIntent: intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,06-30 12:52:29.131  1014  1220 I splitIntent: base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
06-30 12:52:29.131  1014  1220 I splitIntent: other index=10, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
06-30 12:52:29.131  1014  1220 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,06-30 12:52:29.131  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,06-30 12:52:29.141  1439  1439 D RegisteredServicesCache: empty dynamic service
,06-30 12:52:29.151  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,06-30 12:52:29.151  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,06-30 12:52:29.171  1014  1120 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,06-30 12:52:29.171  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,06-30 12:52:29.181  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:29.181  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,06-30 12:52:29.181  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
06-30 12:52:29.181  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.191  6440  6440 I Babel   : Creating RTCS
,06-30 12:52:29.201  1014  1391 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 12:52:29.201  1014  1391 D SecContentProvider2: mCursor = null
,06-30 12:52:29.211  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.231  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.241  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.271  6440  6440 I Babel   : Destroying RTCS
,06-30 12:52:29.321  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,06-30 12:52:29.331  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.331  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.331  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.341  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,06-30 12:52:29.341  1014  1014 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 12:52:29.341  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.341  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.341  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:29.341  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.351  1014  1014 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 12:52:29.351  1014  1014 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
06-30 12:52:29.351  1014  1014 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,06-30 12:52:29.351  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.351  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 12:52:29.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 12:52:29.361  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:29.361  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,06-30 12:52:29.361  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.361  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.361  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 12:52:29.361  1014  1391 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
06-30 12:52:29.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 12:52:29.371  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.371  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.371  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.371  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:29.371  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 12:52:29.371  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 12:52:29.371  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:52:29.371  1729  7004 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,06-30 12:52:29.381  7005  7005 E Zygote  : MountEmulatedStorage()
,06-30 12:52:29.381  7005  7005 E Zygote  : v2
06-30 12:52:29.381  1014  1391 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7005 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 12:52:29.381  7005  7005 I libpersona: KNOX_SDCARD checking this for 10026
06-30 12:52:29.381  7005  7005 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:29.381  7005  7005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:29.391  7005  7005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:29.391  1729  7004 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
06-30 12:52:29.391  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:52:29.391  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 12:52:29.391  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.391  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.391  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:29.391  7005  7005 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:29.391  1014  1014 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,06-30 12:52:29.391  1014  1014 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d380d8d
,06-30 12:52:29.391  1014  1038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,06-30 12:52:29.401  1014  1038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,06-30 12:52:29.401  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:29.401  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 12:52:29.401  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.401  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.401  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.411  1014  1038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,06-30 12:52:29.411  7005  7005 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:29.411  1014  1038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,06-30 12:52:29.411  7005  7005 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:29.421  1597  1597 V GmsNetworkLocationProvi: DISABLE
,06-30 12:52:29.421  1597  1597 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,06-30 12:52:29.421  1729  3769 I Icing   : updateResources: need to parse f{com.google.android.gms}
,06-30 12:52:29.431  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:29.431  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:29.431  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.431  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.441  1014  1038 D LocationProviderProxy: applying state to connected service
,06-30 12:52:29.451  1014  1038 D LocationProviderProxy: applying state to connected service
,06-30 12:52:29.451  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 12:52:29.451  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.451  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.451  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.501  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.501  1622  2016 I art     : Explicit concurrent mark sweep GC freed 6187(277KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/11MB, paused 903us total 38.593ms
,06-30 12:52:29.561  7005  7005 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,06-30 12:52:29.571  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.621  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.631  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.631  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.641  7005  7005 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,06-30 12:52:29.671  1014  1480 I art     : Explicit concurrent mark sweep GC freed 38940(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 22MB/34MB, paused 2.623ms total 161.358ms
,06-30 12:52:29.671  1014  1519 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:29.681  1014  1519 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:29.681  1014  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.681  1014  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.691  7005  7005 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 12:52:29.691  7005  7005 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,06-30 12:52:29.721  7005  7005 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,06-30 12:52:29.721  7005  7005 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,06-30 12:52:29.751  1014  1393 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:29.751  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:29.751  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.751  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.751  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,06-30 12:52:29.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:29.771  7046  7046 E Zygote  : MountEmulatedStorage()
,06-30 12:52:29.771  7046  7046 I libpersona: KNOX_SDCARD checking this for 10029
06-30 12:52:29.771  7046  7046 E Zygote  : v2
06-30 12:52:29.771  7046  7046 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:29.771  7046  7046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:29.771  1014  1027 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7046 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,06-30 12:52:29.771  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:29.771  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.771  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:29.771  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,06-30 12:52:29.771  7046  7046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:29.781  7046  7046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:29.781  7005  7005 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,06-30 12:52:29.781  1014  3079 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending,
06-30 12:52:29.781  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:29.781  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
06-30 12:52:29.781  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
06-30 12:52:29.781  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,06-30 12:52:29.791   317   317 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 23.176ms
,06-30 12:52:29.811  7046  7046 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:52:29.811  7046  7046 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:29.811   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.523ms
,06-30 12:52:29.811  7005  7005 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,06-30 12:52:29.831   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.723ms
,06-30 12:52:29.861  1014  3078 I ActivityManager: Killing 6321:com.sec.spp.push/u0a32 (adj 15): empty #21
,06-30 12:52:29.861  7046  7063 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,06-30 12:52:29.861  1014  3078 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,06-30 12:52:29.861  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.861  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.861  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:29.861  1014  3078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:29.891  1014  3078 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7067 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-30 12:52:29.891  7067  7067 E Zygote  : MountEmulatedStorage()
06-30 12:52:29.891  7067  7067 E Zygote  : v2
06-30 12:52:29.891  7067  7067 I libpersona: KNOX_SDCARD checking this for 10039
06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
06-30 12:52:29.891  7067  7067 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,06-30 12:52:29.891  7067  7067 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:29.891  7067  7067 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 12:52:29.891  7067  7067 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:29.891  7046  7063 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
06-30 12:52:29.901  7046  7063 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
06-30 12:52:29.901  7046  7063 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.901  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.901  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.901  7046  7063 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 12:52:29.911  7067  7067 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:29.911  7067  7067 D ActivityThread: Added TimaKeyStore provider
06-30 12:52:29.911  7046  7063 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.911  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.911  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:29.921  7046  7063 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
06-30 12:52:29.921  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.921  7046  7063 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 12:52:29.931  7046  7063 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:52:29.931  7067  7067 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:52:29.941  7067  7067 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.941  7046  7063 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:52:29.951  7005  7005 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,06-30 12:52:29.951  7046  7063 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
06-30 12:52:29.951  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.951  7046  7063 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 12:52:29.951  7046  7063 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:52:29.951  6652  6661 I CAR.SERVICE: listener not found in list
,06-30 12:52:29.971  7046  7063 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-30 12:52:29.971  7046  7063 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:52:29.971  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.971  7046  7063 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:52:29.981  7046  7063 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,06-30 12:52:29.991  7046  7063 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
06-30 12:52:29.991  7046  7063 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
06-30 12:52:29.991  7046  7063 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:52:29.991  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:52:29.991  7046  7063 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:52:30.001  7046  7063 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,06-30 12:52:30.001  7046  7063 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:30.011  7046  7063 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,06-30 12:52:30.041  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:30.041  1014  1391 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,06-30 12:52:30.041  1014  1391 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:30.041  1014  1391 D BatteryService: stay LED for fully charged
,06-30 12:52:30.041  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:30.041  1014  1014 I MotionRecognitionService: Plugged,
06-30 12:52:30.041  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:30.051  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:30.051  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:52:30.051  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:52:30.051  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:30.061  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:30.061  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:30.071  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:30.071  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:30.071  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:30.081  7067  7067 D NearbySource: Nearby Source Create!
,06-30 12:52:30.081  7067  7067 D NearbyContext: Nearby Context Create!
,06-30 12:52:30.121   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
06-30 12:52:30.121   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:30.121  7067  7067 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,06-30 12:52:30.121  7067  7067 D SLinkSource: Samsung link source created
,06-30 12:52:30.161  7067  7086 D ContactProvider: getAllContactInfoList Start
,06-30 12:52:30.171  1014  1120 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 12:52:30.171  1014  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 12:52:30.181  7067  7067 I PackagesMonitor: PackagesMonitor onReceive :com.google.android.gms
,06-30 12:52:30.191  7067  7086 D ContactProvider: getAllContactInfoList End
,06-30 12:52:30.191  7067  7086 I syncContacts: thread: 1278, sync time = 40
,06-30 12:52:30.221  1014  1393 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-30 12:52:30.221  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-30 12:52:30.221  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:30.221  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:30.221  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-30 12:52:30.231  1014  3079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,06-30 12:52:30.241  6901  7088 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,06-30 12:52:30.241  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.241  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.241  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.241  1014  3079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:30.251  7089  7089 E Zygote  : MountEmulatedStorage(),
06-30 12:52:30.251  7089  7089 E Zygote  : v2
06-30 12:52:30.251  7089  7089 I libpersona: KNOX_SDCARD checking this for 10065
06-30 12:52:30.251  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 12:52:30.251  7089  7089 I libpersona: KNOX_SDCARD not a persona
,06-30 12:52:30.251  1014  3079 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7089 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:52:30.261  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:30.261  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,06-30 12:52:30.291  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:30.291  7089  7089 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:30.321  7089  7089 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,06-30 12:52:30.331  1014  1393 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,06-30 12:52:30.331  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.331  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:30.331  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.331  1014  1393 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:30.341  6901  7088 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 101 ms] updated apps [took 101 ms] 
,06-30 12:52:30.351  7104  7104 E Zygote  : MountEmulatedStorage(),
06-30 12:52:30.351  7104  7104 E Zygote  : v2
06-30 12:52:30.351  7104  7104 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:30.351  7104  7104 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:30.351  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:30.351  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:30.351  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 12:52:30.351  1014  1393 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 12:52:30.361  1014  1393 I ActivityManager: Killing 6636:com.android.mms/u0a41 (adj 15): empty #21
,06-30 12:52:30.361  1014  1496 I ActivityManager: Killing 6682:com.qualcomm.timeservice/1000 (adj 15): empty #21
,06-30 12:52:30.391  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:30.391  7104  7104 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:30.401  7104  7104 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:52:30.421  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,06-30 12:52:30.431  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0,
06-30 12:52:30.431  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:30.431  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:30.431  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:30.451  1014  1026 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 12:52:30.451  1014  1026 I ActivityManager: Killing 6703:com.sec.esdk.elm/u0a90 (adj 15): empty #21
06-30 12:52:30.451  7119  7119 E Zygote  : MountEmulatedStorage()
06-30 12:52:30.451  7119  7119 E Zygote  : v2
06-30 12:52:30.451  7119  7119 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:52:30.451  7119  7119 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:30.451  7119  7119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:30.451  7119  7119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 12:52:30.451  7119  7119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:52:30.471  7119  7119 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:30.481  7119  7119 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:30.501  1014  3079 D CountryDetector: No listener is left
,06-30 12:52:30.521  7119  7119 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,06-30 12:52:30.521  1014  1120 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
06-30 12:52:30.521  1014  1120 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,06-30 12:52:30.531  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:30.531  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:30.531  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,06-30 12:52:30.541  1014  1393 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
06-30 12:52:30.541  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,06-30 12:52:30.541  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:30.541  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:30.541  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,06-30 12:52:30.551  1014  3079 I ActivityManager: Killing 6780:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,06-30 12:52:30.651  1014  1046 I PowerManagerService: [PWL] Off : 105s ago
,06-30 12:52:31.141   297   297 E SMD     : DCD OFF
,06-30 12:52:32.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:33.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:34.151   297   297 E SMD     : DCD OFF
,06-30 12:52:34.471  1014  1393 I ActivityManager: Killing 6798:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,06-30 12:52:34.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:35.881  1014  2720 D SSRM:n  : SIOP:: AP = 330
,06-30 12:52:35.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:36.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:37.151   297   297 E SMD     : DCD OFF
,06-30 12:52:37.911   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:52:40.111  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:52:40.111  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:52:40.111  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:40.111  1014  1026 D BatteryService: stay LED for fully charged
06-30 12:52:40.111  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:40.121  1014  1014 I MotionRecognitionService: Plugged
06-30 12:52:40.121  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:40.121  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:40.121  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:40.121  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:52:40.121  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:40.141  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:40.141  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:40.151  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:40.151  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:40.151  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:40.151   297   297 E SMD     : DCD OFF
,06-30 12:52:41.031  1014  1304 E Watchdog: !@Sync 5
,06-30 12:52:43.151   297   297 E SMD     : DCD OFF
,06-30 12:52:45.891  1014  2720 D SSRM:n  : SIOP:: AP = 310
,06-30 12:52:46.151   297   297 E SMD     : DCD OFF
,06-30 12:52:48.251  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:49.151   297   297 E SMD     : DCD OFF
,06-30 12:52:49.881  1014  1092 V AlarmManager: waitForAlarm result :4
,06-30 12:52:49.891  1014  1092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetService; callingUser = 0; userId(target) = 0
,06-30 12:52:49.941  1014  3078 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:49.941  1014  3078 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,06-30 12:52:49.951  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:49.951  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:49.951  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:49.951  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:49.951  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
06-30 12:52:49.951  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:49.961  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:49.961  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.001  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:50.001  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetLaunchService; callingUser = 0; userId(target) = 0
,06-30 12:52:50.001  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.001  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.001  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.011  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:50.011  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:50.011  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:52:50.011  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:52:50.021  7152  7152 E Zygote  : MountEmulatedStorage()
06-30 12:52:50.021  7152  7152 I libpersona: KNOX_SDCARD checking this for 10011
06-30 12:52:50.021  7152  7152 E Zygote  : v2
,06-30 12:52:50.021  7152  7152 I libpersona: KNOX_SDCARD not a persona
06-30 12:52:50.021  1014  1026 I ActivityManager: Start proc com.google.android.gms:snet for service com.google.android.gms/.security.snet.SnetLaunchService: pid=7152 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
06-30 12:52:50.021  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 12:52:50.031  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 12:52:50.031  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:52:50.041  1729  1729 D SnetService: snet destroyed
,06-30 12:52:50.051  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:52:50.051  7152  7152 D ActivityThread: Added TimaKeyStore provider
,06-30 12:52:50.071  7152  7152 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 12:52:50.071  7152  7152 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:52:50.091  7152  7152 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:52:50.091  7152  7152 I MultiDex: install
06-30 12:52:50.091  7152  7152 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:52:50.101  7152  7152 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,06-30 12:52:50.121  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.121  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.121  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.121  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:50.121  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,06-30 12:52:50.121  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.121  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.121  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.121  1014  1496 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
06-30 12:52:50.121  1014  1496 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
06-30 12:52:50.121  1014  1496 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
06-30 12:52:50.121  1014  1496 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,06-30 12:52:50.121  1622  2547 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 12:52:50.121  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.121  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.121  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.131  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.131  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.131  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.131  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.131  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.131  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.141  1622  1622 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 12:52:50.141  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.141  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.141  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.151  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.151  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.151  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.151  1729  1729 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 12:52:50.161  1014  1391 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:50.161  1014  1391 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,06-30 12:52:50.161  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.161  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.161  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.161  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.161  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.161  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.171  1014  3078 W ActivityManager: userId = 0, bbcId = -10000,
06-30 12:52:50.171  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.171  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.181  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.181  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.181  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.181  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:50.181  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:52:50.181  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:52:50.181  1014  1496 D BatteryService: stay LED for fully charged
06-30 12:52:50.181  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:50.181  1014  1014 I MotionRecognitionService: Plugged,
,06-30 12:52:50.181  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:52:50.181  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:52:50.181  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:50.191  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:52:50.191  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:52:50.201  1014  1391 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.201  1014  1391 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.201  1014  1391 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 12:52:50.201  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:50.201  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:50.211  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:50.211  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.211  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:50.211  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.211  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:50.211  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.211  1014  1220 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:50.211  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.211  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.211  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.221  1014  3078 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.221  1014  3078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.221  1014  3078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.231  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.231  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.231  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.231  1014  1220 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:52:50.231  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
06-30 12:52:50.231  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.231  1014  1220 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.231  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.241  1729  7169 D LocationInitializer: Restart initialization of location
,06-30 12:52:50.241  1014  1120 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:50.241  1014  1120 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.241  1014  1120 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.241  1014  1120 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.241  6832  6832 D WearableService: callingUid 10011, callindPid: 6832
,06-30 12:52:50.251  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.251  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.251  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.251  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 12:52:50.251  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,06-30 12:52:50.251  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.251  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.251  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.261  1597  4514 E MDM     : [163] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,06-30 12:52:50.261  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:50.261  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
06-30 12:52:50.261  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.261  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.271  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 12:52:50.271  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,06-30 12:52:50.271  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 12:52:50.271  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 12:52:50.561  7152  7168 D com.google.android.snet.Snet: Hello Snet!
,06-30 12:52:50.591  1014  1027 D PackageManager: findPreferredActivity: No PreferredActivities set
,06-30 12:52:50.591  1014  1027 I PackageManager: No preferred activity: intent should not be shown
,06-30 12:52:50.601  7152  7168 W Settings: Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,06-30 12:52:50.621  7152  7168 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,06-30 12:52:50.621  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:52:50.621  7152  7168 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:52:50.621  7152  7168 I System.out: (HTTPLog)-Thread-1297-629594009: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:52:50.621  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:50.621   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:50.621   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:50.671  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:50.851  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:50.851  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:50.971  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:50.971   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:50.971   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:51.021  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:51.301  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
,06-30 12:52:51.301  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,06-30 12:52:51.301  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,06-30 12:52:51.301  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:51.301  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
06-30 12:52:51.301  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:51.301  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:51.601  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
,06-30 12:52:51.601  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
06-30 12:52:51.601  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:51.601  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
06-30 12:52:51.601  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:51.601  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:51.601   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:51.601   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:51.911  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
06-30 12:52:51.911  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,06-30 12:52:51.911  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:51.911  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
06-30 12:52:51.911  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:51.911  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:52.151   297   297 E SMD     : DCD OFF
,06-30 12:52:52.441  7152  7168 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 12:52:52.651  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:52.651   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:52.651   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:52.701  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:52.981  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
,06-30 12:52:52.981  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
06-30 12:52:52.981  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:52.981  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
06-30 12:52:52.981  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:52.981  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:53.281  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
,06-30 12:52:53.281  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
06-30 12:52:53.281  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:53.281  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
,06-30 12:52:53.281  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:53.281  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:52:53.281   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:53.281   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:53.531  7152  7168 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Mozilla/5.0 (iPhone; CPU iPhone OS 7_1_1 like Mac OS X) AppleWebKit/537.51.2 (KHTML, like Gecko) Version/7.0 Mobile/11D201 Safari/9537.53
,06-30 12:52:53.531  7152  7168 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,06-30 12:52:53.541  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isSBSettingEnabled false
06-30 12:52:53.541  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):isShipBuild true
06-30 12:52:53.541  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SMARTBONDING_ENABLED is false
06-30 12:52:53.541  7152  7168 I System.out: Thread-1297(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,06-30 12:52:53.651  7152  7168 I System.out: IntentService[SnetLaunchService] calls detatch()
,06-30 12:52:53.651   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:53.651   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:53.941   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:53.941   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:55.161   297   297 E SMD     : DCD OFF
,06-30 12:52:55.621   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
06-30 12:52:55.621   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:52:55.631  7152  7168 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,06-30 12:52:55.641  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:55.641  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:55.871  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
06-30 12:52:55.871   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:55.871   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:55.881  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,06-30 12:52:55.911  1014  2720 D SSRM:n  : SIOP:: AP = 310
,06-30 12:52:56.561   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 12:52:56.561   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 12:52:56.591  7152  7168 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:52:56.601  7152  7168 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:52:57.481  1014  3078 I ActivityManager: Killing 6763:com.android.providers.calendar/u0a37 (adj 15): empty #21
,06-30 12:52:57.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:58.161   297   297 E SMD     : DCD OFF
,06-30 12:52:58.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:59.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:59.991  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 12:53:00.251  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:00.251  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:53:00.251  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:53:00.251  1014  1496 D BatteryService: stay LED for fully charged
06-30 12:53:00.251  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:00.251  1014  1014 I MotionRecognitionService: Plugged,
06-30 12:53:00.251  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:53:00.251  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:00.261  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:00.261  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:53:00.261  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:53:00.271  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:00.271  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:00.271  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:00.271  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:53:00.271  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:00.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:01.161   297   297 E SMD     : DCD OFF
,06-30 12:53:01.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:02.911   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:53:04.161   297   297 E SMD     : DCD OFF
,06-30 12:53:05.651  1014  1046 I PowerManagerService: [PWL] Off : 140s ago
,06-30 12:53:05.921  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 12:53:07.161   297   297 E SMD     : DCD OFF
,06-30 12:53:08.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:10.161   297   297 E SMD     : DCD OFF
,06-30 12:53:10.311  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:11.031  1014  1304 E Watchdog: !@Sync 6
,06-30 12:53:13.161   297   297 E SMD     : DCD OFF
,06-30 12:53:15.931  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 12:53:16.161   297   297 E SMD     : DCD OFF
,06-30 12:53:19.171   297   297 E SMD     : DCD OFF
,06-30 12:53:20.371  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
06-30 12:53:20.371  1014  3079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:53:20.371  1014  3079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:53:20.371  1014  3079 D BatteryService: stay LED for fully charged
06-30 12:53:20.371  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:20.381  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:53:20.381  1014  1014 I MotionRecognitionService: Plugged,
06-30 12:53:20.381  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:53:20.381  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:53:20.381  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:53:20.381  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:53:20.401  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:53:20.401  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:20.411  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:20.411  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:20.411  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:22.171   297   297 E SMD     : DCD OFF
,06-30 12:53:25.171   297   297 E SMD     : DCD OFF,
,06-30 12:53:25.951  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 12:53:27.911   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:53:27.911   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:53:28.171   297   297 E SMD     : DCD OFF
,06-30 12:53:28.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:29.061  1014  1092 V AlarmManager: waitForAlarm result :4
,06-30 12:53:29.071  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:53:29.071  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:53:29.081  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:53:29.081  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:53:29.091  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:53:29.091  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 12:53:29.091  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:53:29.121  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:53:29.131  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:53:29.131  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:53:29.151  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:53:30.441  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:31.171   297   297 E SMD     : DCD OFF
,06-30 12:53:34.171   297   297 E SMD     : DCD OFF,
,06-30 12:53:35.961  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 12:53:37.171   297   297 E SMD     : DCD OFF
,06-30 12:53:37.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:38.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:39.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:40.181   297   297 E SMD     : DCD OFF
,06-30 12:53:40.501  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:40.911   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:41.031  1014  1304 E Watchdog: !@Sync 7
,06-30 12:53:41.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:42.921   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:53:43.181   297   297 E SMD     : DCD OFF
,06-30 12:53:45.671  1014  1046 I PowerManagerService: [PWL] Off : 180s ago
,06-30 12:53:45.971  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 12:53:46.181   297   297 E SMD     : DCD OFF
,06-30 12:53:47.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:48.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:48.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:49.181   297   297 E SMD     : DCD OFF
,06-30 12:53:49.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:50.571  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:50.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:51.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:52.181   297   297 E SMD     : DCD OFF
,06-30 12:53:52.921   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:53:55.181   297   297 E SMD     : DCD OFF
,06-30 12:53:55.991  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:53:58.181   297   297 E SMD     : DCD OFF
,06-30 12:54:00.001  1014  1092 V AlarmManager: waitForAlarm result :8,
,06-30 12:54:00.641  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:01.181   297   297 E SMD     : DCD OFF
,06-30 12:54:02.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:03.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:04.191   297   297 E SMD     : DCD OFF
,06-30 12:54:04.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:05.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:06.001  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:06.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:07.191   297   297 E SMD     : DCD OFF
,06-30 12:54:07.921   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:54:08.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:10.191   297   297 E SMD     : DCD OFF,
,06-30 12:54:10.701  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:10.701  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:54:10.701  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:54:10.701  1014  1496 D BatteryService: stay LED for fully charged
,06-30 12:54:10.701  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:10.711  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:54:10.711  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
06-30 12:54:10.711  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:54:10.711  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:10.711  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:54:10.711  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:54:10.721  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:54:10.721  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:10.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:10.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:10.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:11.031  1014  1304 E Watchdog: !@Sync 8
,06-30 12:54:13.191   297   297 E SMD     : DCD OFF
,06-30 12:54:16.021  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:16.191   297   297 E SMD     : DCD OFF
,06-30 12:54:19.191   297   297 E SMD     : DCD OFF
,06-30 12:54:20.771  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
06-30 12:54:20.771  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:54:20.771  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:54:20.771  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:54:20.771  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:54:20.771  1014  1026 D BatteryService: stay LED for fully charged
06-30 12:54:20.771  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:54:20.771  1014  1014 I MotionRecognitionService: Plugged,
06-30 12:54:20.771  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:54:20.781  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:54:20.781  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:54:20.791  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 12:54:20.791  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:20.801  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:20.801  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:54:20.801  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:22.191   297   297 E SMD     : DCD OFF
,06-30 12:54:22.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:23.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:24.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:25.201   297   297 E SMD     : DCD OFF
,06-30 12:54:25.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:54:26.031  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:26.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:27.921   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:54:28.201   297   297 E SMD     : DCD OFF
,06-30 12:54:28.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:30.681  1014  1046 I PowerManagerService: [PWL] Off : 225s ago,
,06-30 12:54:30.831  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:30.831  1014  1120 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:54:30.831  1014  1120 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:54:30.831  1014  1120 D BatteryService: stay LED for fully charged
06-30 12:54:30.831  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,06-30 12:54:30.831  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:54:30.841  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:54:30.841  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:30.841  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:30.841  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:54:30.841  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:54:30.851  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:54:30.851  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:30.861  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:30.861  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:30.871  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:31.201   297   297 E SMD     : DCD OFF
,06-30 12:54:34.201   297   297 E SMD     : DCD OFF
,06-30 12:54:36.041  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:37.201   297   297 E SMD     : DCD OFF
,06-30 12:54:40.201   297   297 E SMD     : DCD OFF,
,06-30 12:54:40.901  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:41.031  1014  1304 E Watchdog: !@Sync 9
,06-30 12:54:43.201   297   297 E SMD     : DCD OFF
,06-30 12:54:46.061  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:46.201   297   297 E SMD     : DCD OFF
,06-30 12:54:47.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:48.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:48.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:49.211   297   297 E SMD     : DCD OFF
,06-30 12:54:49.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:50.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:50.961  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:51.921   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:52.211   297   297 E SMD     : DCD OFF
,06-30 12:54:52.921   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:54:55.211   297   297 E SMD     : DCD OFF
,06-30 12:54:56.071  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:54:58.211   297   297 E SMD     : DCD OFF
,06-30 12:55:01.021  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:01.211   297   297 E SMD     : DCD OFF
,06-30 12:55:04.211   297   297 E SMD     : DCD OFF
,06-30 12:55:06.081  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:55:07.211   297   297 E SMD     : DCD OFF
,06-30 12:55:08.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:08.681  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:55:08.681  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 12:55:08.681  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:55:08.681  1014  1083 I TLC_TIMA_PKM_initialize: initializing...
,06-30 12:55:08.681  1014  1083 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
06-30 12:55:08.691  1014  1083 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
06-30 12:55:08.691  1014  1083 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
06-30 12:55:08.691  1014  1083 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 12:55:08.691  1014  1083 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
06-30 12:55:08.691  1014  1083 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
06-30 12:55:08.691  1014  1083 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
06-30 12:55:08.691  1014  1083 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 12:55:08.691  1014  1083 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:55:08.711  1014  1083 D QSEECOMAPI: : Loaded image: APP id = 10
,06-30 12:55:08.721  1014  1083 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 12:55:08.731  1014  1083 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 12:55:10.211   297   297 E SMD     : DCD OFF
,06-30 12:55:10.631  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:55:10.631  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:55:10.631  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:10.641  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:11.031  1014  1304 E Watchdog: !@Sync 10
,06-30 12:55:11.091  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:55:11.091  1014  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:55:11.091  1014  1220 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:55:11.091  1014  1220 D BatteryService: stay LED for fully charged
06-30 12:55:11.091  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:11.091  1014  1014 I MotionRecognitionService: Plugged
06-30 12:55:11.091  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:55:11.091  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:11.091  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:11.101  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:55:11.101  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:55:11.111  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:11.111  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:11.121  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:11.121  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:11.121  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:13.221   297   297 E SMD     : DCD OFF
,06-30 12:55:16.101  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:55:16.221   297   297 E SMD     : DCD OFF
,06-30 12:55:17.931   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:55:17.931   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:55:19.221   297   297 E SMD     : DCD OFF
,06-30 12:55:20.681  1014  1046 I PowerManagerService: [PWL] Off : 275s ago
,06-30 12:55:21.151  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:21.151  1014  1519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:55:21.151  1014  1519 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:55:21.151  1014  1519 D BatteryService: stay LED for fully charged
06-30 12:55:21.151  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:21.161  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:55:21.161  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
06-30 12:55:21.161  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:21.161  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:21.161  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:55:21.161  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:55:21.171  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:21.171  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:21.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:21.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:21.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:22.221   297   297 E SMD     : DCD OFF
,06-30 12:55:25.221   297   297 E SMD     : DCD OFF,
,06-30 12:55:26.111  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:55:28.221   297   297 E SMD     : DCD OFF
,06-30 12:55:28.261  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:31.221  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:31.221  1014  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:55:31.221  1014  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:55:31.221  1014  1027 D BatteryService: stay LED for fully charged
,06-30 12:55:31.221  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:31.221  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:55:31.221  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:55:31.221   297   297 E SMD     : DCD OFF
,06-30 12:55:31.231  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:55:31.231  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
06-30 12:55:31.231  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:55:31.231  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:55:31.241  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:55:31.241  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:31.251  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 12:55:31.251  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:31.251  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:32.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:33.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:34.231   297   297 E SMD     : DCD OFF
,06-30 12:55:34.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:35.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:55:36.121  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:55:36.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:55:37.231   297   297 E SMD     : DCD OFF
,06-30 12:55:37.931   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-30 12:55:40.231   297   297 E SMD     : DCD OFF,
,06-30 12:55:41.031  1014  1304 E Watchdog: !@Sync 11,
,06-30 12:55:41.281  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:55:42.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:43.231   297   297 E SMD     : DCD OFF
,06-30 12:55:43.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:44.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:45.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:46.141  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:55:46.231  1014  1092 V AlarmManager: waitForAlarm result :8,
,06-30 12:55:46.231   297   297 E SMD     : DCD OFF,
,06-30 12:55:46.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:47.931   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:55:48.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:49.231   297   297 E SMD     : DCD OFF
,06-30 12:55:51.351  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:51.351  1014  3078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:55:51.351  1014  3078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:55:51.351  1014  3078 D BatteryService: stay LED for fully charged
,06-30 12:55:51.351  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:51.351  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:51.351  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:51.361  1014  1014 I MotionRecognitionService: Plugged
06-30 12:55:51.361  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:55:51.361  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:55:51.361  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:55:51.371  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:51.371  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:51.381  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:51.381  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:51.381  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:52.241   297   297 E SMD     : DCD OFF
,06-30 12:55:55.241   297   297 E SMD     : DCD OFF,
,06-30 12:55:56.151  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:55:57.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:58.241   297   297 E SMD     : DCD OFF
,06-30 12:55:58.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:59.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:00.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:56:01.241   297   297 E SMD     : DCD OFF
,06-30 12:56:01.411  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
06-30 12:56:01.411  1014  3079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:56:01.411  1014  3079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:56:01.411  1014  3079 D BatteryService: stay LED for fully charged
06-30 12:56:01.411  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:01.421  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:56:01.421  1014  1014 I MotionRecognitionService: Plugged
06-30 12:56:01.421  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:56:01.421  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:56:01.421  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:56:01.421  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:56:01.431  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:01.431  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:01.441  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:01.441  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:01.441  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:01.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:56:02.931   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:56:04.241   297   297 E SMD     : DCD OFF
,06-30 12:56:06.161  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:07.241   297   297 E SMD     : DCD OFF
,06-30 12:56:08.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:10.241   297   297 E SMD     : DCD OFF
,06-30 12:56:11.031  1014  1304 E Watchdog: !@Sync 12
,06-30 12:56:11.471  1014  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:13.251   297   297 E SMD     : DCD OFF
,06-30 12:56:15.681  1014  1046 I PowerManagerService: [PWL] Off : 330s ago
,06-30 12:56:16.181  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:16.251   297   297 E SMD     : DCD OFF
,06-30 12:56:17.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:18.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:19.251   297   297 E SMD     : DCD OFF
,06-30 12:56:19.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:56:20.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:21.541  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:21.541  1014  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
06-30 12:56:21.541  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:56:21.541  1014  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:56:21.541  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:56:21.541  1014  1480 D BatteryService: stay LED for fully charged
06-30 12:56:21.541  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:56:21.541  1014  1014 I MotionRecognitionService: Plugged
06-30 12:56:21.541  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
06-30 12:56:21.551  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:56:21.551  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:56:21.561  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:21.561  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:21.571  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:21.571  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:21.571  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:21.931   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:22.251   297   297 E SMD     : DCD OFF
,06-30 12:56:22.941   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:56:25.251   297   297 E SMD     : DCD OFF,
,06-30 12:56:26.191  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:28.251   297   297 E SMD     : DCD OFF
,06-30 12:56:28.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:31.251   297   297 E SMD     : DCD OFF
,06-30 12:56:31.601  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:31.601  1014  1391 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:56:31.601  1014  1391 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:56:31.601  1014  1391 D BatteryService: stay LED for fully charged
,06-30 12:56:31.601  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:31.611  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:31.611  1014  1014 I MotionRecognitionService: Plugged
06-30 12:56:31.611  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:31.611  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:56:31.611  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:56:31.611  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:56:31.631  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:31.631  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:31.641  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 12:56:31.641  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:31.641  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:34.261   297   297 E SMD     : DCD OFF
,06-30 12:56:36.211  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:37.261   297   297 E SMD     : DCD OFF
,06-30 12:56:40.261   297   297 E SMD     : DCD OFF
,06-30 12:56:41.041  1014  1304 E Watchdog: !@Sync 13
,06-30 12:56:41.661  1014  1393 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:41.671  1014  1393 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
06-30 12:56:41.671  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:56:41.671  1014  1393 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
06-30 12:56:41.671  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:56:41.671  1014  1393 D BatteryService: stay LED for fully charged
06-30 12:56:41.671  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:56:41.671  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:56:41.671  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:56:41.671  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
06-30 12:56:41.671  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 12:56:41.681  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,06-30 12:56:41.681  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:41.681  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:41.691  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 12:56:41.691  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:42.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:43.261   297   297 E SMD     : DCD OFF
,06-30 12:56:43.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:44.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:45.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:56:46.221  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:46.261   297   297 E SMD     : DCD OFF
,06-30 12:56:46.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:56:47.941   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,06-30 12:56:48.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:49.261   297   297 E SMD     : DCD OFF
,06-30 12:56:51.731  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:51.731  1014  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:56:51.731  1014  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:56:51.731  1014  1480 D BatteryService: stay LED for fully charged
,06-30 12:56:51.731  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:51.731  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:56:51.731  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:56:51.731  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:51.731  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:56:51.741  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:56:51.741  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:56:51.751  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:56:51.751  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:51.761  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:51.761  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:56:51.761  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:52.261   297   297 E SMD     : DCD OFF
,06-30 12:56:55.261   297   297 E SMD     : DCD OFF,
,06-30 12:56:56.241  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:56:58.271   297   297 E SMD     : DCD OFF
,06-30 12:57:00.001  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 12:57:00.001  1014  1092 V AlarmManager: No more alarm at this time.nowELAPSED=426461 batch.start=1176672
,06-30 12:57:00.001  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:57:00.001  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:57:00.011  1014  1014 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,06-30 12:57:00.011  1014  1014 V SAMP_GCMKill: GCM kill size 0. just return
,06-30 12:57:00.021  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 12:57:00.021  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 12:57:00.031  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:57:00.031  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 12:57:00.031  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:57:00.061  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:57:00.071  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:57:00.071  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:57:00.081  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,06-30 12:57:01.271   297   297 E SMD     : DCD OFF
,06-30 12:57:01.791  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:01.791  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:57:01.791  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:57:01.791  1014  1496 D BatteryService: stay LED for fully charged
,06-30 12:57:01.791  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:01.801  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:01.801  1014  1014 I MotionRecognitionService: Plugged
06-30 12:57:01.801  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:57:01.801  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:57:01.801  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:57:01.801  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,06-30 12:57:01.811  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:01.821  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:01.831  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:01.831  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:01.831  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:04.271   297   297 E SMD     : DCD OFF
,06-30 12:57:06.251  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:07.271   297   297 E SMD     : DCD OFF
,06-30 12:57:08.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:10.271   297   297 E SMD     : DCD OFF
,06-30 12:57:11.041  1014  1304 E Watchdog: !@Sync 14
,06-30 12:57:11.851  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:57:11.851  1014  3079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:57:11.851  1014  3079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:57:11.851  1014  3079 D BatteryService: stay LED for fully charged
06-30 12:57:11.851  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:11.861  1014  1014 I MotionRecognitionService: Plugged,
06-30 12:57:11.861  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 12:57:11.861  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:57:11.861  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:11.861  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:57:11.861  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:57:11.871  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:11.871  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:11.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:11.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:11.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:12.941   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:57:12.941   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:57:13.271   297   297 E SMD     : DCD OFF
,06-30 12:57:15.681  1014  1046 I PowerManagerService: [PWL] Off : 390s ago,
,06-30 12:57:16.271  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:16.271   297   297 E SMD     : DCD OFF
,06-30 12:57:19.271   297   297 E SMD     : DCD OFF
,06-30 12:57:21.921  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:22.281   297   297 E SMD     : DCD OFF
,06-30 12:57:25.281   297   297 E SMD     : DCD OFF
,06-30 12:57:26.281  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:28.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:28.281   297   297 E SMD     : DCD OFF
,06-30 12:57:31.281   297   297 E SMD     : DCD OFF
,06-30 12:57:31.991  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:57:32.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:33.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:34.281   297   297 E SMD     : DCD OFF
,06-30 12:57:34.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:35.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:36.291  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:36.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:37.281   297   297 E SMD     : DCD OFF,
,06-30 12:57:37.941   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,06-30 12:57:40.281   297   297 E SMD     : DCD OFF
,06-30 12:57:41.041  1014  1304 E Watchdog: !@Sync 15
,06-30 12:57:42.061  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:57:42.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:43.291   297   297 E SMD     : DCD OFF
,06-30 12:57:43.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:44.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:45.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:46.291   297   297 E SMD     : DCD OFF
,06-30 12:57:46.311  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:46.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:47.941   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:57:48.271  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:49.291   297   297 E SMD     : DCD OFF
,06-30 12:57:52.121  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:57:52.291   297   297 E SMD     : DCD OFF
,06-30 12:57:55.291   297   297 E SMD     : DCD OFF
,06-30 12:57:56.321  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:57:57.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:58.291   297   297 E SMD     : DCD OFF
,06-30 12:57:58.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:59.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:57:59.991  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 12:58:00.421   329   329 I bootchecker: bootchecker wake up!!,
,06-30 12:58:00.941   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:01.291   297   297 E SMD     : DCD OFF
,06-30 12:58:01.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:02.181  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:02.951   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:58:04.291   297   297 E SMD     : DCD OFF
,06-30 12:58:06.341  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:58:07.301   297   297 E SMD     : DCD OFF
,06-30 12:58:08.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:10.301   297   297 E SMD     : DCD OFF
,06-30 12:58:11.041  1014  1304 E Watchdog: !@Sync 16
,06-30 12:58:12.251  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:58:13.301   297   297 E SMD     : DCD OFF
,06-30 12:58:16.301   297   297 E SMD     : DCD OFF
,06-30 12:58:16.351  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:58:17.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:58:18.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:19.301   297   297 E SMD     : DCD OFF
,06-30 12:58:19.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:20.681  1014  1046 I PowerManagerService: [PWL] Off : 455s ago
,06-30 12:58:20.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:58:21.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:58:22.301   297   297 E SMD     : DCD OFF,
,06-30 12:58:22.321  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:58:22.951   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:58:25.301   297   297 E SMD     : DCD OFF
,06-30 12:58:26.361  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:58:28.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,06-30 12:58:28.311   297   297 E SMD     : DCD OFF
,06-30 12:58:31.311   297   297 E SMD     : DCD OFF
,06-30 12:58:32.381  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:34.311   297   297 E SMD     : DCD OFF
,06-30 12:58:36.381  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:58:37.311   297   297 E SMD     : DCD OFF
,06-30 12:58:40.311   297   297 E SMD     : DCD OFF
,06-30 12:58:41.041  1014  1304 E Watchdog: !@Sync 17
,06-30 12:58:42.451  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:42.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,06-30 12:58:43.311   297   297 E SMD     : DCD OFF
,06-30 12:58:43.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:44.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:45.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:46.311   297   297 E SMD     : DCD OFF
,06-30 12:58:46.391  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 12:58:46.951   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:47.951   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:58:48.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:49.311   297   297 E SMD     : DCD OFF
,06-30 12:58:52.321   297   297 E SMD     : DCD OFF
,06-30 12:58:52.521  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 12:58:55.321   297   297 E SMD     : DCD OFF
,06-30 12:58:56.401  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:58:58.321   297   297 E SMD     : DCD OFF
,06-30 12:59:01.321   297   297 E SMD     : DCD OFF
,06-30 12:59:02.581  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:04.321   297   297 E SMD     : DCD OFF
,06-30 12:59:06.421  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:07.321   297   297 E SMD     : DCD OFF
,06-30 12:59:08.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:10.321   297   297 E SMD     : DCD OFF
,06-30 12:59:11.041  1014  1304 E Watchdog: !@Sync 18
,06-30 12:59:12.651  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:12.951   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:59:12.951   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:59:13.321   297   297 E SMD     : DCD OFF
,06-30 12:59:16.331   297   297 E SMD     : DCD OFF
,06-30 12:59:16.431  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:19.331   297   297 E SMD     : DCD OFF
,06-30 12:59:22.331   297   297 E SMD     : DCD OFF
,06-30 12:59:22.721  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:59:22.721  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:59:22.721  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
06-30 12:59:22.721  1014  1519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:59:22.721  1014  1519 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:59:22.721  1014  1519 D BatteryService: stay LED for fully charged,
06-30 12:59:22.721  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 12:59:22.721  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:59:22.721  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 12:59:22.731  1014  1014 I MotionRecognitionService: Plugged
06-30 12:59:22.731  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:59:22.741  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:22.741  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:22.751  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:22.751  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:22.751  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:25.331   297   297 E SMD     : DCD OFF
,06-30 12:59:26.441  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:28.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:28.331   297   297 E SMD     : DCD OFF
,06-30 12:59:30.691  1014  1046 I PowerManagerService: [PWL] Off : 525s ago,
,06-30 12:59:31.331   297   297 E SMD     : DCD OFF
,06-30 12:59:32.781  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:59:32.781  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:59:32.781  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:59:32.781  1014  1496 D BatteryService: stay LED for fully charged
06-30 12:59:32.781  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:32.791  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:59:32.791  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
,06-30 12:59:32.791  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 12:59:32.791  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 12:59:32.791  1014  1014 I MotionRecognitionService: Plugged
,06-30 12:59:32.791  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:59:32.811  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:32.811  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:32.821  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 12:59:32.821  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:32.821  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:34.331   297   297 E SMD     : DCD OFF
,06-30 12:59:36.461  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:37.341   297   297 E SMD     : DCD OFF
,06-30 12:59:37.951   332   332 I Atfwd_Daemon: Stop the daemon....
,06-30 12:59:40.341   297   297 E SMD     : DCD OFF
,06-30 12:59:41.041  1014  1304 E Watchdog: !@Sync 19
,06-30 12:59:42.851  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:42.851  1014  3079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:59:42.851  1014  3079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:59:42.851  1014  3079 D BatteryService: stay LED for fully charged
06-30 12:59:42.851  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
06-30 12:59:42.851  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:59:42.851  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 12:59:42.851  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:59:42.851  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 12:59:42.861  1014  1014 I MotionRecognitionService: Plugged
06-30 12:59:42.861  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:59:42.871  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:42.871  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:42.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 12:59:42.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:42.881  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:43.341   297   297 E SMD     : DCD OFF
,06-30 12:59:46.341   297   297 E SMD     : DCD OFF
,06-30 12:59:46.471  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:48.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:49.341   297   297 E SMD     : DCD OFF
,06-30 12:59:52.341   297   297 E SMD     : DCD OFF
,06-30 12:59:52.911  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:52.911  1014  1519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 12:59:52.911  1014  1519 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 12:59:52.911  1014  1519 D BatteryService: stay LED for fully charged
06-30 12:59:52.911  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:52.911  1014  1014 I MotionRecognitionService: Plugged
06-30 12:59:52.911  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 12:59:52.921  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:59:52.921  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
06-30 12:59:52.921  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:59:52.921  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 12:59:52.931  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:52.931  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:52.941  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:52.941  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:52.941  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:55.341   297   297 E SMD     : DCD OFF
,06-30 12:59:56.481  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 12:59:58.341   297   297 E SMD     : DCD OFF
,06-30 13:00:01.351   297   297 E SMD     : DCD OFF
,06-30 13:00:02.981  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:02.981  1014  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:00:02.981  1014  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:00:02.981  1014  1496 D BatteryService: stay LED for fully charged
06-30 13:00:02.981  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:00:02.981  1014  1014 I MotionRecognitionService: Plugged
,06-30 13:00:02.981  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:00:02.991  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:02.991  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:00:02.991  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
06-30 13:00:02.991  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:00:03.001  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:00:03.001  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:00:03.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:03.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:00:03.011  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:04.351   297   297 E SMD     : DCD OFF
,06-30 13:00:06.511  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 13:00:07.351   297   297 E SMD     : DCD OFF
,06-30 13:00:08.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:08.681  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:00:08.681  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 13:00:08.681  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:00:09.491  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:00:09.491  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:00:09.501  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:00:09.501  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:00:10.351   297   297 E SMD     : DCD OFF
,06-30 13:00:11.041  1014  1304 E Watchdog: !@Sync 20
,06-30 13:00:13.041  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:00:13.351   297   297 E SMD     : DCD OFF
,06-30 13:00:16.351   297   297 E SMD     : DCD OFF
,06-30 13:00:16.521  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:00:19.351   297   297 E SMD     : DCD OFF
,06-30 13:00:22.351   297   297 E SMD     : DCD OFF
,06-30 13:00:23.111  1014  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:25.361   297   297 E SMD     : DCD OFF
,06-30 13:00:26.541  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:00:28.281  1014  2736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:28.361   297   297 E SMD     : DCD OFF
,06-30 13:00:31.361   297   297 E SMD     : DCD OFF
,06-30 13:00:33.171  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:34.361   297   297 E SMD     : DCD OFF
,06-30 13:00:36.551  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:00:37.361   297   297 E SMD     : DCD OFF
,06-30 13:00:40.361   297   297 E SMD     : DCD OFF
,06-30 13:00:41.041  1014  1304 E Watchdog: !@Sync 21
,06-30 13:00:43.241  1014  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:43.361   297   297 E SMD     : DCD OFF
,06-30 13:00:45.701  1014  1046 I PowerManagerService: [PWL] Off : 600s ago
,06-30 13:00:46.371   297   297 E SMD     : DCD OFF
,06-30 13:00:46.561  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:00:49.371   297   297 E SMD     : DCD OFF
,06-30 13:00:52.371   297   297 E SMD     : DCD OFF
,06-30 13:00:53.301  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:00:55.371   297   297 E SMD     : DCD OFF
,06-30 13:00:56.571  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:00:58.371   297   297 E SMD     : DCD OFF
,06-30 13:01:01.371   297   297 E SMD     : DCD OFF
,06-30 13:01:03.361  1014  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:04.371   297   297 E SMD     : DCD OFF
,06-30 13:01:06.591  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:07.371   297   297 E SMD     : DCD OFF
,06-30 13:01:10.381   297   297 E SMD     : DCD OFF
,06-30 13:01:11.041  1014  1304 E Watchdog: !@Sync 22
,06-30 13:01:13.381   297   297 E SMD     : DCD OFF
,06-30 13:01:13.431  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:16.381   297   297 E SMD     : DCD OFF
,06-30 13:01:16.601  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:19.381   297   297 E SMD     : DCD OFF
,06-30 13:01:22.381   297   297 E SMD     : DCD OFF
,06-30 13:01:23.501  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:25.381   297   297 E SMD     : DCD OFF
,06-30 13:01:26.611  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:28.381   297   297 E SMD     : DCD OFF
,06-30 13:01:31.391   297   297 E SMD     : DCD OFF
,06-30 13:01:33.561  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:34.391   297   297 E SMD     : DCD OFF
,06-30 13:01:36.631  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:37.391   297   297 E SMD     : DCD OFF
,06-30 13:01:40.391   297   297 E SMD     : DCD OFF
,06-30 13:01:41.041  1014  1304 E Watchdog: !@Sync 23
,06-30 13:01:43.391   297   297 E SMD     : DCD OFF
,06-30 13:01:43.631  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:01:43.631  1014  3078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:01:43.631  1014  3078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:01:43.631  1014  3078 D BatteryService: stay LED for fully charged
06-30 13:01:43.631  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:43.631  1014  1014 I MotionRecognitionService: Plugged
,06-30 13:01:43.631  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 13:01:43.641  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:43.641  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:43.641  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:01:43.641  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:01:43.651  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:01:43.651  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:43.661  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 13:01:43.661  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:43.661  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:46.391   297   297 E SMD     : DCD OFF
,06-30 13:01:46.641  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:49.391   297   297 E SMD     : DCD OFF
,06-30 13:01:52.391   297   297 E SMD     : DCD OFF
,06-30 13:01:53.701  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:53.701  1014  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:01:53.701  1014  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:01:53.701  1014  1480 D BatteryService: stay LED for fully charged
,06-30 13:01:53.701  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
06-30 13:01:53.701  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:01:53.701  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:01:53.701  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:01:53.701  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:01:53.711  1014  1014 I MotionRecognitionService: Plugged
06-30 13:01:53.711  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:01:53.711  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:53.711  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:53.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:53.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:53.731  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:55.401   297   297 E SMD     : DCD OFF
,06-30 13:01:56.661  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:01:58.401   297   297 E SMD     : DCD OFF
,06-30 13:02:00.011  1014  1092 V AlarmManager: waitForAlarm result :8,
,06-30 13:02:01.401   297   297 E SMD     : DCD OFF
,06-30 13:02:03.761  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:04.401   297   297 E SMD     : DCD OFF
,06-30 13:02:05.701  1014  1046 I PowerManagerService: [PWL] Off : 680s ago
,06-30 13:02:06.671  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:02:07.401   297   297 E SMD     : DCD OFF
,06-30 13:02:10.401   297   297 E SMD     : DCD OFF
,06-30 13:02:11.051  1014  1304 E Watchdog: !@Sync 24
,06-30 13:02:13.401   297   297 E SMD     : DCD OFF
,06-30 13:02:13.821  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:13.821  1014  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
06-30 13:02:13.821  1014  1220 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:02:13.831  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:02:13.821  1014  1220 D BatteryService: stay LED for fully charged
06-30 13:02:13.831  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:02:13.821  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
06-30 13:02:13.831  1014  1014 I MotionRecognitionService: Plugged,
06-30 13:02:13.831  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 13:02:13.831  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:02:13.831  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:02:13.841  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:02:13.841  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:13.851  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:13.851  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:13.851  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:16.401   297   297 E SMD     : DCD OFF
,06-30 13:02:16.681  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:02:19.411   297   297 E SMD     : DCD OFF
,06-30 13:02:22.411   297   297 E SMD     : DCD OFF
,06-30 13:02:23.891  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:25.411   297   297 E SMD     : DCD OFF
,06-30 13:02:26.701  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:02:28.411   297   297 E SMD     : DCD OFF
,06-30 13:02:31.411   297   297 E SMD     : DCD OFF
,06-30 13:02:33.951  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:34.411   297   297 E SMD     : DCD OFF
,06-30 13:02:36.711  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:02:37.411   297   297 E SMD     : DCD OFF
,06-30 13:02:40.421   297   297 E SMD     : DCD OFF
,06-30 13:02:41.051  1014  1304 E Watchdog: !@Sync 25
,06-30 13:02:43.421   297   297 E SMD     : DCD OFF
,06-30 13:02:44.011  1014  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:44.011  1014  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:02:44.011  1014  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:02:44.011  1014  1479 D BatteryService: stay LED for fully charged
06-30 13:02:44.011  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:44.021  1014  1014 I MotionRecognitionService: Plugged,
06-30 13:02:44.021  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:02:44.021  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:44.021  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:44.021  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 13:02:44.031  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:02:44.041  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:44.041  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:44.051  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:44.051  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:44.051  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:46.421   297   297 E SMD     : DCD OFF
,06-30 13:02:46.721  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 13:02:49.421   297   297 E SMD     : DCD OFF
,06-30 13:02:52.421   297   297 E SMD     : DCD OFF
,06-30 13:02:54.081  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:54.081  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:02:54.081  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:02:54.081  1014  1026 D BatteryService: stay LED for fully charged
06-30 13:02:54.081  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:54.081  1014  1014 I MotionRecognitionService: Plugged
,06-30 13:02:54.081  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:02:54.081  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:54.081  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:54.091  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
06-30 13:02:54.091  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:02:54.091  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:02:54.101  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:54.111  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 13:02:54.111  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:54.111  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:55.421   297   297 E SMD     : DCD OFF
,06-30 13:02:56.731  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:02:58.421   297   297 E SMD     : DCD OFF
,06-30 13:03:01.421   297   297 E SMD     : DCD OFF
,06-30 13:03:04.141  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:04.431   297   297 E SMD     : DCD OFF
,06-30 13:03:06.751  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:07.431   297   297 E SMD     : DCD OFF
,06-30 13:03:10.431   297   297 E SMD     : DCD OFF
,06-30 13:03:11.051  1014  1304 E Watchdog: !@Sync 26
,06-30 13:03:13.431   297   297 E SMD     : DCD OFF
,06-30 13:03:14.211  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:16.431   297   297 E SMD     : DCD OFF
,06-30 13:03:16.761  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:19.431   297   297 E SMD     : DCD OFF
,06-30 13:03:22.431   297   297 E SMD     : DCD OFF
,06-30 13:03:24.271  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:25.431   297   297 E SMD     : DCD OFF
,06-30 13:03:26.771  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:28.441   297   297 E SMD     : DCD OFF
,06-30 13:03:30.701  1014  1046 I PowerManagerService: [PWL] Off : 765s ago
,06-30 13:03:31.441   297   297 E SMD     : DCD OFF
,06-30 13:03:34.331  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:34.441   297   297 E SMD     : DCD OFF,
,06-30 13:03:36.791  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:37.441   297   297 E SMD     : DCD OFF
,06-30 13:03:40.441   297   297 E SMD     : DCD OFF
,06-30 13:03:41.051  1014  1304 E Watchdog: !@Sync 27,
,06-30 13:03:43.441   297   297 E SMD     : DCD OFF
,06-30 13:03:44.401  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:46.441   297   297 E SMD     : DCD OFF
,06-30 13:03:46.801  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:49.451   297   297 E SMD     : DCD OFF
,06-30 13:03:52.451   297   297 E SMD     : DCD OFF
,06-30 13:03:54.461  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:55.451   297   297 E SMD     : DCD OFF
,06-30 13:03:56.811  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:03:58.451   297   297 E SMD     : DCD OFF
,06-30 13:04:01.451   297   297 E SMD     : DCD OFF
,06-30 13:04:04.451   297   297 E SMD     : DCD OFF
,06-30 13:04:04.531  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:04:06.831  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:04:07.451   297   297 E SMD     : DCD OFF
,06-30 13:04:10.451   297   297 E SMD     : DCD OFF
,06-30 13:04:11.051  1014  1304 E Watchdog: !@Sync 28
,06-30 13:04:13.461   297   297 E SMD     : DCD OFF
,06-30 13:04:14.601  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:16.461   297   297 E SMD     : DCD OFF
,06-30 13:04:16.841  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:04:19.461   297   297 E SMD     : DCD OFF
,06-30 13:04:22.461   297   297 E SMD     : DCD OFF
,06-30 13:04:24.661  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:25.461   297   297 E SMD     : DCD OFF
,06-30 13:04:26.851  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:04:28.461   297   297 E SMD     : DCD OFF
,06-30 13:04:31.461   297   297 E SMD     : DCD OFF
,06-30 13:04:34.471   297   297 E SMD     : DCD OFF
,06-30 13:04:34.721  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:36.871  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:04:37.471   297   297 E SMD     : DCD OFF
,06-30 13:04:40.471   297   297 E SMD     : DCD OFF
,06-30 13:04:41.051  1014  1304 E Watchdog: !@Sync 29
,06-30 13:04:43.471   297   297 E SMD     : DCD OFF
,06-30 13:04:44.781  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:04:46.471   297   297 E SMD     : DCD OFF
,06-30 13:04:46.881  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:04:49.471   297   297 E SMD     : DCD OFF
,06-30 13:04:52.471   297   297 E SMD     : DCD OFF
,06-30 13:04:54.841  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:55.471   297   297 E SMD     : DCD OFF
,06-30 13:04:56.891  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 13:04:58.481   297   297 E SMD     : DCD OFF
,06-30 13:05:00.701  1014  1046 I PowerManagerService: [PWL] Off : 855s ago
,06-30 13:05:01.481   297   297 E SMD     : DCD OFF
,06-30 13:05:04.481   297   297 E SMD     : DCD OFF
,06-30 13:05:04.911  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:06.911  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:07.481   297   297 E SMD     : DCD OFF
,06-30 13:05:08.681  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:05:08.681  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 13:05:08.681  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:05:10.481   297   297 E SMD     : DCD OFF
,06-30 13:05:10.571  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:05:10.571  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:05:10.581  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:10.581  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:11.051  1014  1304 E Watchdog: !@Sync 30
,06-30 13:05:13.481   297   297 E SMD     : DCD OFF
,06-30 13:05:14.971  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:05:16.481   297   297 E SMD     : DCD OFF
,06-30 13:05:16.931  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:19.491   297   297 E SMD     : DCD OFF
,06-30 13:05:22.491   297   297 E SMD     : DCD OFF
,06-30 13:05:25.041  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:25.491   297   297 E SMD     : DCD OFF
,06-30 13:05:26.941  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:28.491   297   297 E SMD     : DCD OFF
,06-30 13:05:31.491   297   297 E SMD     : DCD OFF
,06-30 13:05:34.491   297   297 E SMD     : DCD OFF
,06-30 13:05:35.101  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:36.961  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:37.491   297   297 E SMD     : DCD OFF
,06-30 13:05:40.491   297   297 E SMD     : DCD OFF
,06-30 13:05:41.051  1014  1304 E Watchdog: !@Sync 31
,06-30 13:05:43.501   297   297 E SMD     : DCD OFF
,06-30 13:05:45.171  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:05:46.501   297   297 E SMD     : DCD OFF
,06-30 13:05:46.971  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:49.501   297   297 E SMD     : DCD OFF
,06-30 13:05:52.501   297   297 E SMD     : DCD OFF
,06-30 13:05:55.231  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:55.501   297   297 E SMD     : DCD OFF
,06-30 13:05:56.981  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:05:58.501   297   297 E SMD     : DCD OFF
,06-30 13:06:01.501   297   297 E SMD     : DCD OFF
,06-30 13:06:04.501   297   297 E SMD     : DCD OFF
,06-30 13:06:05.301  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:06:06.991  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:07.511   297   297 E SMD     : DCD OFF
,06-30 13:06:10.511   297   297 E SMD     : DCD OFF
,06-30 13:06:11.051  1014  1304 E Watchdog: !@Sync 32
,06-30 13:06:13.511   297   297 E SMD     : DCD OFF
,06-30 13:06:15.361  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:16.511   297   297 E SMD     : DCD OFF
,06-30 13:06:17.011  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:19.511   297   297 E SMD     : DCD OFF
,06-30 13:06:22.511   297   297 E SMD     : DCD OFF
,06-30 13:06:25.421  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:06:25.511   297   297 E SMD     : DCD OFF,
,06-30 13:06:27.021  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:28.521   297   297 E SMD     : DCD OFF
,06-30 13:06:31.521   297   297 E SMD     : DCD OFF
,06-30 13:06:34.521   297   297 E SMD     : DCD OFF
,06-30 13:06:35.491  1014  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:06:35.701  1014  1046 I PowerManagerService: [PWL] Off : 950s ago
,06-30 13:06:37.031  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:37.521   297   297 E SMD     : DCD OFF
,06-30 13:06:40.521   297   297 E SMD     : DCD OFF
,06-30 13:06:41.051  1014  1304 E Watchdog: !@Sync 33
,06-30 13:06:43.521   297   297 E SMD     : DCD OFF
,06-30 13:06:45.551  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:46.521   297   297 E SMD     : DCD OFF
,06-30 13:06:47.051  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:49.521   297   297 E SMD     : DCD OFF
,06-30 13:06:52.531   297   297 E SMD     : DCD OFF
,06-30 13:06:55.531   297   297 E SMD     : DCD OFF
,06-30 13:06:55.621  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:57.061  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:06:58.531   297   297 E SMD     : DCD OFF
,06-30 13:07:01.531   297   297 E SMD     : DCD OFF
,06-30 13:07:04.531   297   297 E SMD     : DCD OFF
,06-30 13:07:05.681  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:07:07.081  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:07.531   297   297 E SMD     : DCD OFF
,06-30 13:07:10.531   297   297 E SMD     : DCD OFF
,06-30 13:07:11.061  1014  1304 E Watchdog: !@Sync 34
,06-30 13:07:13.541   297   297 E SMD     : DCD OFF
,06-30 13:07:15.751  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:16.541   297   297 E SMD     : DCD OFF
,06-30 13:07:17.091  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:19.541   297   297 E SMD     : DCD OFF
,06-30 13:07:22.541   297   297 E SMD     : DCD OFF
,06-30 13:07:25.541   297   297 E SMD     : DCD OFF,
,06-30 13:07:25.821  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:27.101  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:28.541   297   297 E SMD     : DCD OFF
,06-30 13:07:31.541   297   297 E SMD     : DCD OFF
,06-30 13:07:34.551   297   297 E SMD     : DCD OFF
,06-30 13:07:35.881  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:37.111  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:37.551   297   297 E SMD     : DCD OFF
,06-30 13:07:40.551   297   297 E SMD     : DCD OFF
,06-30 13:07:41.061  1014  1304 E Watchdog: !@Sync 35
,06-30 13:07:43.551   297   297 E SMD     : DCD OFF
,06-30 13:07:45.951  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:46.551   297   297 E SMD     : DCD OFF
,06-30 13:07:47.131  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:49.551   297   297 E SMD     : DCD OFF
,06-30 13:07:52.551   297   297 E SMD     : DCD OFF
,06-30 13:07:55.551   297   297 E SMD     : DCD OFF,
,06-30 13:07:56.011  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:57.141  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:07:58.561   297   297 E SMD     : DCD OFF
,06-30 13:08:01.561   297   297 E SMD     : DCD OFF
,06-30 13:08:04.561   297   297 E SMD     : DCD OFF,
,06-30 13:08:06.081  1014  1120 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:07.151  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:07.561   297   297 E SMD     : DCD OFF
,06-30 13:08:10.561   297   297 E SMD     : DCD OFF
,06-30 13:08:11.061  1014  1304 E Watchdog: !@Sync 36
,06-30 13:08:13.561   297   297 E SMD     : DCD OFF
,06-30 13:08:15.211  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:08:15.211  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:08:15.211  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:08:15.301  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
06-30 13:08:15.301  6121  6121 I wpa_supplicant: nl80211: Received scan results (1 BSSes),
06-30 13:08:15.301  6121  6121 I wpa_supplicant: wlan0: State: COMPLETED -> ASSOCIATED
06-30 13:08:15.301  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:08:15.301  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:08:15.301  6121  6121 I wpa_supplicant: Prev BSS - hexdump(len=6): 84 b2 61 1a ce 70,
,06-30 13:08:15.301  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=84.CE.70 SSID=517273716330627261
06-30 13:08:15.301  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 13:08:15.301  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:08:15.301  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
06-30 13:08:15.301  6121  6121 I wpa_supplicant: Associated with 84.9C.30
,06-30 13:08:15.311  6121  6121 E wpa_supplicant: Cmd 35605 not handled
,06-30 13:08:15.311  1014  1125 E WifiStateMachine: NOT update Last BSSID
06-30 13:08:15.311  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:08:15.311  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:08:15.371  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:0f:9c:30,
06-30 13:08:15.371  6121  6121 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
06-30 13:08:15.371  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=84.9C.30 SSID=517273716330627261
,06-30 13:08:15.381  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
06-30 13:08:15.381  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:08:15.801  1014  1046 I PowerManagerService: [PWL] Off : 1050s ago
,06-30 13:08:16.141  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:08:16.141  1014  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:08:16.141  1014  1220 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:08:16.141  1014  1220 D BatteryService: stay LED for fully charged
06-30 13:08:16.141  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:16.151  1014  1014 I MotionRecognitionService: Plugged
06-30 13:08:16.151  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:08:16.151  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,06-30 13:08:16.151  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:08:16.151  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 13:08:16.151  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:08:16.161  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:16.161  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:16.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:16.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:16.181  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:16.361  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:0f:9c:30
06-30 13:08:16.361  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 13:08:16.401  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:0f:9c:30
06-30 13:08:16.401  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 13:08:16.401  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
06-30 13:08:16.401  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=84.9C.30 SSID=517273716330627261
06-30 13:08:16.401  6121  6121 I wpa_supplicant: wlan0: WPA: Key negotiation completed with 84:b2:61:0f:9c:30 [PTK=CCMP GTK=CCMP]
06-30 13:08:16.401  6121  6121 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-30 13:08:16.401  6121  6121 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to 84.9C.30 completed (auth) [id=0 id_str=]
06-30 13:08:16.401  6121  6121 I wpa_supplicant: Blacklist: Clear (temp) 
06-30 13:08:16.401  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=84.9C.30 SSID=517273716330627261
,06-30 13:08:16.401  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:08:16.401  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:08:16.401  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 13:08:16.411  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,06-30 13:08:16.411  1014  1125 D WifiStateMachine: getDhcpRenewAfterRoamingMode
06-30 13:08:16.411  1014  1125 D WifiStateMachine: mDhcpRenewAfterRoamingMode : 0
,06-30 13:08:16.411  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:08:16.411  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:08:16.411  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 13:08:16.411  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:08:16.411  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:08:16.411  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:08:16.411  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
,06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:08:16.421  1014  1146 D WifiWatchdogStateMachine.QualityResultHandler_0: [EVENT_NETWORK_PROPERTIES_CHANGED] 2
,06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 13:08:16.421  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1014  1125 E WifiNative-wlan0: do suspend false
,06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:16.421  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:08:16.421  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:08:16.421  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
06-30 13:08:16.421  1014  1125 D SecContentProvider2: mCursor = null
06-30 13:08:16.421  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:08:16.441  7564  7564 I dhcpcd  : sending signal 14 to pid 6207
,06-30 13:08:16.441  6207  6207 I dhcpcd  : received SIGALRM, renewing
06-30 13:08:16.441  6207  6207 I dhcpcd  : wlan0: renewing lease of 10.76.13.33
06-30 13:08:16.441  6207  6207 I dhcpcd  : start_renew() if(wlan0) new BSSID get Success. (MAC : 84.9C.30)
06-30 13:08:16.441  6207  6207 I dhcpcd  : start_renew() if(wlan0) old BSSID get Success. (MAC : 84.CE.70)
06-30 13:08:16.441  6207  6207 I dhcpcd  : start_renew() bssid NOT match, update bssid
,06-30 13:08:16.561   297   297 E SMD     : DCD OFF
,06-30 13:08:17.171  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:17.431  6121  6121 E wpa_supplicant: IAPP Type:40, Func Type: 1
06-30 13:08:17.431  6121  6121 E wpa_supplicant: UnSupported IAPP Type 64
,06-30 13:08:19.571   297   297 E SMD     : DCD OFF
,06-30 13:08:21.411  6207  6207 I dhcpcd  : roaming renew timeout
,06-30 13:08:21.421  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
06-30 13:08:21.421  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 13:08:21.421  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:08:21.421  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 13:08:21.421  1014  1125 D WifiStateMachine: roamin renew timeout or ip lost but ignore this message clear link properties
06-30 13:08:21.421  1014  1127 D ConnectivityService: Removing Route [fe80::/64 -> :: wlan0] from network 502
,06-30 13:08:21.421  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:08:21.421  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}, oldLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
06-30 13:08:21.431  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 13:08:21.431  1014  1127 D ConnectivityService: Removing Route [10.76.12.0/22 -> 0.0.0.0 wlan0] from network 502
06-30 13:08:21.431  1014  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
06-30 13:08:21.431  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:08:21.431  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:08:21.431  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
06-30 13:08:21.431  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:08:21.431  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "Qrsqc0bra"
06-30 13:08:21.431   281   949 E Netd    : netlink response contains error (No such process)
,06-30 13:08:21.431  1014  6205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:08:21.431  1014  1127 E ConnectivityService: Exception in removeRoute: java.lang.IllegalStateException: command '52 network route remove 502 wlan0 10.76.12.0/22' failed with '400 52 removeRoute() failed (No such process)'
06-30 13:08:21.431   281   949 E Netd    : netlink response contains error (No such process)
06-30 13:08:21.431  1014  1127 D ConnectivityService: Removing Route [0.0.0.0/0 -> 10.76.12.1 wlan0] from network 502
,06-30 13:08:21.441  1014  1127 E ConnectivityService: Exception in removeRoute: java.lang.IllegalStateException: command '53 network route remove 502 wlan0 0.0.0.0/0 10.76.12.1' failed with '400 53 removeRoute() failed (No such process)'
06-30 13:08:21.441  1014  1127 D ConnectivityService: Invalid tcpBufferSizes string: null, using defaults,
06-30 13:08:21.441  1014  1127 D ConnectivityService: Setting tx/rx TCP buffers to 4096,87380,110208,4096,16384,110208
,06-30 13:08:21.441  1014  1127 E ConnectivityService: remove dns info for 502while DATA_SUSPEND
06-30 13:08:21.441  1014  1127 D ConnectivityService: Setting Dns servers for network 502 to [/0.0.0.0]
06-30 13:08:21.441  1014  1127 D ConnectivityService: LTETest block dns file not exists
06-30 13:08:21.441   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:08:21.441   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 1000
06-30 13:08:21.441  1014  1127 E ConnectivityService: Exception in setDnsServersForNetwork: java.lang.IllegalArgumentException: command '54 resolver setnetdns 502 ' failed with '500 54 Wrong number of arguments to resolver setnetdns'
,06-30 13:08:21.451  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
06-30 13:08:21.451  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,06-30 13:08:21.451  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:08:21.451  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:08:21.451  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
06-30 13:08:21.451  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-30 13:08:21.451  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-30 13:08:21.461  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:08:21.451  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
06-30 13:08:21.461  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:08:21.461  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 13:08:21.461  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:08:21.461  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:08:21.461  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:08:21.631  1014  6206 D NetUtils: dhcp_do_request failed : wlan0 (renew)
,06-30 13:08:21.631  1014  6206 E DhcpStateMachine: DHCP failed on wlan0: DHCP Renew result was failed
,06-30 13:08:21.831  1014  1125 E WifiNative-wlan0: do suspend true
,06-30 13:08:21.851  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
06-30 13:08:21.851  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:08:21.851  1014  1125 E WifiStateMachine: Maintain Current connection if DHCP failed by Roaming RENEW,
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:08:21.861  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1014  1125 E WifiNative-wlan0: do suspend false
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:08:21.861  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:21.861  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:08:21.871  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,06-30 13:08:21.871  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:08:22.081  7582  7582 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 13:08:22.081  7582  7582 I dhcpcd  : version 5.5.6 starting
,06-30 13:08:22.081  7582  7582 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 13:08:22.131  7582  7582 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
06-30 13:08:22.131  7582  7582 I dhcpcd  : if(wlan0) info get Success. (MAC : 84.9C.30)
06-30 13:08:22.131  7582  7582 I dhcpcd  : bssid match
,06-30 13:08:22.141  7582  7582 I dhcpcd  : wlan0: rebinding lease of 10.76.14.204
,06-30 13:08:22.261  7582  7582 I dhcpcd  : wlan0: acknowledged 10.76.14.204 from 131.200.201.74,
,06-30 13:08:22.411  7582  7582 I dhcpcd  : wlan0: leased 10.76.14.204 for 3600 seconds,
,06-30 13:08:22.411  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,06-30 13:08:22.411  1014  1127 D ConnectivityService: Adding iface wlan0 to network 502
06-30 13:08:22.411  1014  1127 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,06-30 13:08:22.421  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502],
06-30 13:08:22.421  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:08:22.421  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:08:22.421  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:08:22.571   297   297 E SMD     : DCD OFF,
,06-30 13:08:22.681  1014  1125 E WifiNative-wlan0: do suspend true
,06-30 13:08:22.701  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,06-30 13:08:22.701  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
06-30 13:08:22.701  1014  1125 E WifiStateMachine: result: 0, Moved BSSID: 84:b2:61:0f:9c:30
,06-30 13:08:22.701  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:08:22.701  1014  1127 D ConnectivityService: Adding Route [10.76.12.0/22 -> 0.0.0.0 wlan0] to network 502
,06-30 13:08:22.711  1014  1014 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
06-30 13:08:22.711  1014  1014 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,06-30 13:08:22.711  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 10.76.12.1 wlan0] to network. 502
06-30 13:08:22.711  1014  1014 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:08:22.711  1014  1127 D ConnectivityService: Setting Dns servers for network 502 to [/131.200.201.74, /131.200.78.74, /131.200.48.74, /131.200.16.74]
06-30 13:08:22.711  1014  1014 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:08:22.711  1014  1127 D ConnectivityService: LTETest block dns file not exists
06-30 13:08:22.711  1014  1014 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:08:22.711  1014  1146 D WifiWatchdogStateMachine.QualityResultHandler_0: [EVENT_NETWORK_PROPERTIES_CHANGED] 1
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:08:22.711  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.system,ui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:08:22.711  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:08:22.711  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"Qrsqc0bra"WPA_EAP
,06-30 13:08:22.731  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:08:22.731  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:08:22.731  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:08:22.731  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:08:25.571   297   297 E SMD     : DCD OFF
,06-30 13:08:26.211  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:08:26.211  1014  1519 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:08:26.211  1014  1519 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:08:26.211  1014  1519 D BatteryService: stay LED for fully charged
06-30 13:08:26.211  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:26.211  1014  1014 I MotionRecognitionService: Plugged,
06-30 13:08:26.221  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:08:26.211  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 13:08:26.221  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:08:26.211  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:08:26.211  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:08:26.231  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:08:26.231  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:26.231  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:26.231  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:26.231  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:26.331  7582  7582 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:08:27.181  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:28.571   297   297 E SMD     : DCD OFF
,06-30 13:08:29.831  1014  1092 V AlarmManager: waitForAlarm result :4
,06-30 13:08:29.841  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 13:08:29.841  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:08:29.841  1014  1014 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,06-30 13:08:29.851  1014  1014 V SAMP_GCMKill: GCM kill size 0. just return
,06-30 13:08:29.851  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:08:29.851  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:08:29.871  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:08:29.871  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 13:08:29.871  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:08:29.871   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:08:29.871   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 13:08:29.911  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:08:29.911  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:08:29.921  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:08:29.931  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:08:30.151  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:08:30.151  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:08:30.151  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:08:30.331  7582  7582 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,06-30 13:08:30.751  1622  7622 D GCM     : Connected
,06-30 13:08:30.761  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:08:30.761  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:08:30.761  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:08:30.781  1622  7622 D GCM     : Message class com.google.f.a.a.p
,06-30 13:08:31.571   297   297 E SMD     : DCD OFF
,06-30 13:08:34.331  7582  7582 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 13:08:34.331  7582  7582 I dhcpcd  : wlan0: no IPv6 Routers available
,06-30 13:08:34.571   297   297 E SMD     : DCD OFF
,06-30 13:08:36.271  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:08:37.191  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:37.571   297   297 E SMD     : DCD OFF
,06-30 13:08:40.581   297   297 E SMD     : DCD OFF
,06-30 13:08:41.061  1014  1304 E Watchdog: !@Sync 37
,06-30 13:08:43.581   297   297 E SMD     : DCD OFF
,06-30 13:08:46.341  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:46.581   297   297 E SMD     : DCD OFF
,06-30 13:08:47.211  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:49.581   297   297 E SMD     : DCD OFF
,06-30 13:08:52.581   297   297 E SMD     : DCD OFF
,06-30 13:08:55.581   297   297 E SMD     : DCD OFF
,06-30 13:08:56.401  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:57.221  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:08:58.581   297   297 E SMD     : DCD OFF
,06-30 13:08:59.991  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 13:09:01.581   297   297 E SMD     : DCD OFF
,06-30 13:09:04.591   297   297 E SMD     : DCD OFF
,06-30 13:09:06.471  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:07.231  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:07.591   297   297 E SMD     : DCD OFF
,06-30 13:09:10.591   297   297 E SMD     : DCD OFF
,06-30 13:09:11.061  1014  1304 E Watchdog: !@Sync 38
,06-30 13:09:13.591   297   297 E SMD     : DCD OFF
,06-30 13:09:16.531  1014  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:09:16.591   297   297 E SMD     : DCD OFF,
,06-30 13:09:17.251  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:19.591   297   297 E SMD     : DCD OFF
,06-30 13:09:22.591   297   297 E SMD     : DCD OFF
,06-30 13:09:25.601   297   297 E SMD     : DCD OFF,
,06-30 13:09:26.601  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:27.261  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:28.601   297   297 E SMD     : DCD OFF
,06-30 13:09:31.601   297   297 E SMD     : DCD OFF
,06-30 13:09:31.771  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,06-30 13:09:31.771  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
06-30 13:09:31.771  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,06-30 13:09:31.851  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
,06-30 13:09:31.851  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.851  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.851  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
06-30 13:09:31.851  6121  6121 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=COMPLETED bssid=84:b2:61:0f:9c:30)
06-30 13:09:31.851  6121  6121 E wpa_supplicant: Cmd 35605 not handled
06-30 13:09:31.851  6121  6121 I wpa_supplicant: nl80211: Received scan results (1 BSSes)
06-30 13:09:31.851  6121  6121 I wpa_supplicant: wlan0: State: COMPLETED -> ASSOCIATED
06-30 13:09:31.851  6121  6121 I wpa_supplicant: Prev BSS - hexdump(len=6): 84 b2 61 0f 9c 30
06-30 13:09:31.851  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=84.9C.30 SSID=517273716330627261
,06-30 13:09:31.851  6121  6121 I wpa_supplicant: Associated with 84.CE.70
06-30 13:09:31.851  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.851  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,06-30 13:09:31.851  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
06-30 13:09:31.851  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 13:09:31.851  6121  6121 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
06-30 13:09:31.851  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=84.CE.70 SSID=517273716330627261
,06-30 13:09:31.861  1014  1125 E WifiStateMachine: NOT update Last BSSID
,06-30 13:09:31.861  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:09:31.861  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:09:31.861  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:09:31.861  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:09:31.871  6121  6121 I wpa_supplicant: wlan0: RX EAPOL from 84:b2:61:1a:ce:70
06-30 13:09:31.871  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,06-30 13:09:31.871  6121  6121 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
06-30 13:09:31.871  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=84.CE.70 SSID=517273716330627261
06-30 13:09:31.871  6121  6121 I wpa_supplicant: wlan0: WPA: Key negotiation completed with 84:b2:61:1a:ce:70 [PTK=CCMP GTK=CCMP]
06-30 13:09:31.871  6121  6121 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
06-30 13:09:31.871  6121  6121 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to 84.CE.70 completed (auth) [id=0 id_str=]
,06-30 13:09:31.871  6121  6121 I wpa_supplicant: Blacklist: Clear (temp) 
06-30 13:09:31.871  6121  6121 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=84.CE.70 SSID=517273716330627261
,06-30 13:09:31.871  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.871  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.871  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:09:31.881  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,06-30 13:09:31.881  1014  1125 D WifiStateMachine: getDhcpRenewAfterRoamingMode,
,06-30 13:09:31.881  1014  1125 D WifiStateMachine: mDhcpRenewAfterRoamingMode : 0
,06-30 13:09:31.881  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.881  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
06-30 13:09:31.881  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,06-30 13:09:31.881  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 13:09:31.891  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:31.891  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:09:31.891  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:09:31.891  1014  1146 D WifiWatchdogStateMachine.QualityResultHandler_0: [EVENT_NETWORK_PROPERTIES_CHANGED] 2
,06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:09:31.891  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:31.891  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:31.901  1014  1125 E WifiNative-wlan0: do suspend false
,06-30 13:09:31.901  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
06-30 13:09:31.901  1014  1125 D SecContentProvider2: mCursor = null
,06-30 13:09:31.901  6121  6121 E wpa_supplicant: IAPP Type:33, Func Type: 81
06-30 13:09:31.901  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
06-30 13:09:31.901  6121  6121 I wpa_supplicant: ccx_process_roam_frame driver command = SETCCXROAMSCANCHANNELS 3 1 40 136
06-30 13:09:31.901  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:09:31.911  7647  7647 I dhcpcd  : sending signal 14 to pid 7582
,06-30 13:09:31.911  7582  7582 I dhcpcd  : received SIGALRM, renewing
06-30 13:09:31.911  7582  7582 I dhcpcd  : wlan0: renewing lease of 10.76.14.204
06-30 13:09:31.911  7582  7582 I dhcpcd  : start_renew() if(wlan0) new BSSID get Success. (MAC : 84.CE.70)
06-30 13:09:31.911  7582  7582 I dhcpcd  : start_renew() if(wlan0) old BSSID get Success. (MAC : 84.9C.30)
06-30 13:09:31.911  7582  7582 I dhcpcd  : start_renew() bssid NOT match, update bssid
,06-30 13:09:31.941  6121  6121 E wpa_supplicant: IAPP Type:33, Func Type: 81
,06-30 13:09:31.941  6121  6121 I wpa_supplicant: Duplicate channel(11)
06-30 13:09:31.941  6121  6121 I wpa_supplicant: Duplicate channel(1)
06-30 13:09:31.941  6121  6121 I wpa_supplicant: Duplicate channel(6)
06-30 13:09:31.941  6121  6121 I wpa_supplicant: Duplicate channel(1)
06-30 13:09:31.941  6121  6121 I wpa_supplicant: Duplicate channel(36)
06-30 13:09:31.941  6121  6121 I wpa_supplicant: ccx_process_roam_frame driver command = SETCCXROAMSCANCHANNELS 6 1 6 11 40 36 48
,06-30 13:09:32.881  6121  6121 E wpa_supplicant: IAPP Type:40, Func Type: 1
,06-30 13:09:32.881  6121  6121 E wpa_supplicant: UnSupported IAPP Type 64
,06-30 13:09:34.601   297   297 E SMD     : DCD OFF
,06-30 13:09:35.701  7582  7582 I dhcpcd  : roaming renew timeout,
,06-30 13:09:35.711  1014  1125 D WifiStateMachine: roamin renew timeout or ip lost but ignore this message clear link properties,
06-30 13:09:35.711  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: []  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [10.76.14.204/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:35.711  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:35.721  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:09:35.721  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 13:09:35.721  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}, oldLp = {InterfaceName: wlan0 LinkAddresses: []  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:35.721  1014  1127 D ConnectivityService: Removing Route [10.76.12.0/22 -> 0.0.0.0 wlan0] from network 502
06-30 13:09:35.721  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:09:35.721  1014  1127 E ConnectivityService: Exception in removeRoute: java.lang.IllegalStateException: command '59 network route remove 502 wlan0 10.76.12.0/22' failed with '400 59 removeRoute() failed (No such process)'
,06-30 13:09:35.721   281   949 E Netd    : netlink response contains error (No such process)
06-30 13:09:35.721  1014  1127 D ConnectivityService: Removing Route [0.0.0.0/0 -> 10.76.12.1 wlan0] from network 502
06-30 13:09:35.721   281   949 E Netd    : netlink response contains error (No such process)
,06-30 13:09:35.721  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
06-30 13:09:35.721  1014  1120 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
06-30 13:09:35.721  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:09:35.721  1014  1127 E ConnectivityService: Exception in removeRoute: java.lang.IllegalStateException: command '60 network route remove 502 wlan0 0.0.0.0/0 10.76.12.1' failed with '400 60 removeRoute() failed (No such process)'
06-30 13:09:35.721  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation,
,06-30 13:09:35.721  1014  1127 D ConnectivityService: Invalid tcpBufferSizes string: null, using defaults
06-30 13:09:35.721  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
06-30 13:09:35.721  1014  1127 D ConnectivityService: Setting tx/rx TCP buffers to 4096,87380,110208,4096,16384,110208
06-30 13:09:35.721  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "Qrsqc0bra"
06-30 13:09:35.721  1014  6205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 13:09:35.731   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:09:35.731   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 1000,
,06-30 13:09:35.731  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
06-30 13:09:35.731  1014  6205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,06-30 13:09:35.731  1014  1127 E ConnectivityService: remove dns info for 502while DATA_SUSPEND
06-30 13:09:35.741  1014  1127 D ConnectivityService: Setting Dns servers for network 502 to [/0.0.0.0]
06-30 13:09:35.741  1014  1127 D ConnectivityService: LTETest block dns file not exists
,06-30 13:09:35.741  1014  1127 E ConnectivityService: Exception in setDnsServersForNetwork: java.lang.IllegalArgumentException: command '61 resolver setnetdns 502 ' failed with '500 61 Wrong number of arguments to resolver setnetdns',
06-30 13:09:35.741  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:09:35.741  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:09:35.741  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:09:35.751  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:35.751  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
06-30 13:09:35.751  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:09:35.751  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
06-30 13:09:35.751  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:09:35.751  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
06-30 13:09:35.751  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
06-30 13:09:35.751  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
06-30 13:09:35.751  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,06-30 13:09:35.911  1014  6206 D NetUtils: dhcp_do_request failed : wlan0 (renew)
06-30 13:09:35.911  1014  6206 E DhcpStateMachine: DHCP failed on wlan0: DHCP Renew result was failed
,06-30 13:09:36.111  1014  1125 E WifiNative-wlan0: do suspend true,
,06-30 13:09:36.131  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
,06-30 13:09:36.131  1014  1125 E WifiStateMachine: Maintain Current connection if DHCP failed by Roaming RENEW
06-30 13:09:36.131  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 13:09:36.141  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
,06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,06-30 13:09:36.141  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:36.141  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:36.151  1014  1125 E WifiNative-wlan0: do suspend false
,06-30 13:09:36.191  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,06-30 13:09:36.191  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:09:36.391  7664  7664 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,06-30 13:09:36.401  7664  7664 I dhcpcd  : version 5.5.6 starting
06-30 13:09:36.401  7664  7664 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,06-30 13:09:36.451  7664  7664 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
06-30 13:09:36.461  7664  7664 I dhcpcd  : if(wlan0) info get Success. (MAC : 84.CE.70),
06-30 13:09:36.461  7664  7664 I dhcpcd  : bssid match
06-30 13:09:36.461  7664  7664 I dhcpcd  : wlan0: rebinding lease of 10.76.13.33
,06-30 13:09:36.571  7664  7664 I dhcpcd  : wlan0: acknowledged 10.76.13.33 from 131.200.201.74,
,06-30 13:09:36.641  7664  7664 I dhcpcd  : wlan0: leased 10.76.13.33 for 3600 seconds,
,06-30 13:09:36.641  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
06-30 13:09:36.641  1014  1127 D ConnectivityService: Adding iface wlan0 to network 502
06-30 13:09:36.641  1014  1127 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,06-30 13:09:36.651  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:36.651  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:36.651  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
06-30 13:09:36.651  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:09:36.671  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:36.671  1014  3078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:09:36.671  1014  3078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:09:36.671  1014  3078 D BatteryService: stay LED for fully charged
06-30 13:09:36.671  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:36.671  1014  1014 I MotionRecognitionService: Plugged
,06-30 13:09:36.671  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:09:36.681  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:36.681  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:09:36.681  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:09:36.681  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 13:09:36.681  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:36.691  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:36.691  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:36.701  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:36.701  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:37.001  1014  1125 E WifiNative-wlan0: do suspend true,
,06-30 13:09:37.021  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,06-30 13:09:37.021  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,06-30 13:09:37.031  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:37.031  1014  1127 D ConnectivityService: Adding Route [10.76.12.0/22 -> 0.0.0.0 wlan0] to network 502
,06-30 13:09:37.031  1014  1125 E WifiStateMachine: result: 0, Moved BSSID: 84:b2:61:1a:ce:70
,06-30 13:09:37.031  1014  1014 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
06-30 13:09:37.031  1014  1125 W WifiNetworkLists: findNetwork(84:b2:61:1a:ce:70) == true,
06-30 13:09:37.031  1014  1014 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:37.031  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 10.76.12.1 wlan0] to network. 502
,06-30 13:09:37.031  1014  1014 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:37.031  1014  1127 D ConnectivityService: Setting Dns servers for network 502 to [/131.200.201.74, /131.200.78.74, /131.200.48.74, /131.200.16.74]
06-30 13:09:37.031  1014  1014 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
06-30 13:09:37.031  1014  1127 D ConnectivityService: LTETest block dns file not exists
06-30 13:09:37.031  1014  1014 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [10.76.13.33/22,]  Routes: [10.76.12.0/22 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 10.76.12.1 wlan0,] DnsAddresses: [131.200.201.74,131.200.78.74,131.200.48.74,131.200.16.74,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
06-30 13:09:37.031  1014  1146 D WifiWatchdogStateMachine.QualityResultHandler_0: [EVENT_NETWORK_PROPERTIES_CHANGED] 1
06-30 13:09:37.031  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:09:37.031  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:09:37.031  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.031  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.031  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.031  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.031  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"Qrsqc0bra"WPA_EAP
06-30 13:09:37.041  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056a/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014e/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
06-30 13:09:37.041  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
06-30 13:09:37.041  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.041  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:37.041  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
06-30 13:09:37.041  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,06-30 13:09:37.041  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:37.051  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,06-30 13:09:37.051  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:09:37.051  1172  1677 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,06-30 13:09:37.271  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:37.601   297   297 E SMD     : DCD OFF,
,06-30 13:09:40.081  1014  1092 V AlarmManager: waitForAlarm result :4
,06-30 13:09:40.101  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
06-30 13:09:40.101  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:09:40.101  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:09:40.101  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:09:40.111  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:09:40.111  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 13:09:40.111  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:09:40.121  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
,06-30 13:09:40.121  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:09:40.121  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
06-30 13:09:40.121  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:09:40.121  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,06-30 13:09:40.141   281   945 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:09:40.141   281   945 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,06-30 13:09:40.151  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:09:40.161  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:09:40.171  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:09:40.181  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 13:09:40.191  1014  3079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 13:09:40.191  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:09:40.191  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:09:40.191  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:09:40.201  1729  7699 I EventLogService: Aggregate from 1467283932010 (log), 1467283170164 (data)
,06-30 13:09:40.321  1622  2016 I art     : Explicit concurrent mark sweep GC freed 7632(400KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 7MB/11MB, paused 1.009ms total 47.185ms
,06-30 13:09:40.341  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:09:40.341  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:09:40.341  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:09:40.561  1622  7704 D GCM     : Connected
,06-30 13:09:40.571  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:09:40.571  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:09:40.571  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,06-30 13:09:40.591  1622  7704 D GCM     : Message class com.google.f.a.a.p
,06-30 13:09:40.601   297   297 E SMD     : DCD OFF
,06-30 13:09:40.691  7664  7664 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:09:41.061  1014  1304 E Watchdog: !@Sync 39
,06-30 13:09:43.601   297   297 E SMD     : DCD OFF
,06-30 13:09:44.691  7664  7664 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,06-30 13:09:46.611   297   297 E SMD     : DCD OFF
,06-30 13:09:46.731  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:09:46.741  1014  1480 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:09:46.741  1014  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:09:46.741  1014  1480 D BatteryService: stay LED for fully charged
,06-30 13:09:46.741  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:46.741  1014  1014 I MotionRecognitionService: Plugged
,06-30 13:09:46.741  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:09:46.741  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:46.741  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:46.751  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 13:09:46.751  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:09:46.761  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:46.761  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:46.771  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 13:09:46.771  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:46.771  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:47.291  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:48.691  7664  7664 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
06-30 13:09:48.691  7664  7664 I dhcpcd  : wlan0: no IPv6 Routers available
,06-30 13:09:49.611   297   297 E SMD     : DCD OFF
,06-30 13:09:52.611   297   297 E SMD     : DCD OFF
,06-30 13:09:55.611   297   297 E SMD     : DCD OFF
,06-30 13:09:56.801  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:57.301  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:09:58.611   297   297 E SMD     : DCD OFF
,06-30 13:09:59.991  1014  1092 V AlarmManager: waitForAlarm result :8
,06-30 13:10:00.801  1014  1046 I PowerManagerService: [PWL] Off : 1155s ago
,06-30 13:10:01.611   297   297 E SMD     : DCD OFF
,06-30 13:10:04.611   297   297 E SMD     : DCD OFF
,06-30 13:10:06.871  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:10:07.311  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:10:07.611   297   297 E SMD     : DCD OFF
,06-30 13:10:08.681  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:10:08.681  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
06-30 13:10:08.681  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:10:08.711  1014  1038 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:08.751  1014  1100 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,06-30 13:10:08.751  1014  1100 I ApplicationUsage: Updating Usage Statistics in DB @ 1467285008755
,06-30 13:10:08.751  1014  1100 I ApplicationPolicy: updateDataUsageMap
,06-30 13:10:08.931  1014  1100 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,06-30 13:10:08.931  1014  1100 I NetworkDataUsageDb: ::isTableExists: Table exists 
,06-30 13:10:08.941  1014  1100 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467285008947
,06-30 13:10:09.491  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:10:09.491  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:10:09.491  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:10:09.491  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:10:10.621   297   297 E SMD     : DCD OFF
,06-30 13:10:11.061  1014  1304 E Watchdog: !@Sync 40
,06-30 13:10:13.621   297   297 E SMD     : DCD OFF
,06-30 13:10:16.621   297   297 E SMD     : DCD OFF
,06-30 13:10:16.931  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:17.341  1014  2720 D SSRM:n  : SIOP:: AP = 300
,06-30 13:10:19.621   297   297 E SMD     : DCD OFF
,06-30 13:10:22.621   297   297 E SMD     : DCD OFF
,06-30 13:10:25.621   297   297 E SMD     : DCD OFF
,06-30 13:10:27.001  1014  3079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:27.001  1014  3079 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:10:27.001  1014  3079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:10:27.001  1014  3079 D BatteryService: stay LED for fully charged
,06-30 13:10:27.001  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:27.001  1014  1014 I MotionRecognitionService: Plugged
06-30 13:10:27.001  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:10:27.011  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:27.011  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:10:27.011  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:27.011  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,06-30 13:10:27.021  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:27.021  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:27.031  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:27.031  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:27.031  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:27.351  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:10:28.621   297   297 E SMD     : DCD OFF
,06-30 13:10:31.621   297   297 E SMD     : DCD OFF
,06-30 13:10:34.631   297   297 E SMD     : DCD OFF
,06-30 13:10:37.061  1014  3078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 13:10:37.061  1014  3078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:10:37.061  1014  3078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:10:37.061  1014  3078 D BatteryService: stay LED for fully charged
06-30 13:10:37.061  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:37.071  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:10:37.071  1014  1014 I MotionRecognitionService: Plugged
06-30 13:10:37.071  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:10:37.071  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 13:10:37.071  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:10:37.071  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,06-30 13:10:37.091  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:37.091  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:37.101  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:37.101  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:37.101  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:37.371  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:10:37.631   297   297 E SMD     : DCD OFF
,06-30 13:10:40.631   297   297 E SMD     : DCD OFF
,06-30 13:10:41.061  1014  1304 E Watchdog: !@Sync 41
,06-30 13:10:43.631   297   297 E SMD     : DCD OFF
,06-30 13:10:46.631   297   297 E SMD     : DCD OFF
,06-30 13:10:47.131  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:47.381  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:10:49.631   297   297 E SMD     : DCD OFF
,06-30 13:10:52.631   297   297 E SMD     : DCD OFF
,06-30 13:10:55.631   297   297 E SMD     : DCD OFF
,06-30 13:10:57.191  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:57.391  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:10:58.641   297   297 E SMD     : DCD OFF
,06-30 13:11:01.641   297   297 E SMD     : DCD OFF
,06-30 13:11:04.641   297   297 E SMD     : DCD OFF
,06-30 13:11:07.261  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:07.411  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:11:07.641   297   297 E SMD     : DCD OFF
,06-30 13:11:10.641   297   297 E SMD     : DCD OFF
,06-30 13:11:11.061  1014  1304 E Watchdog: !@Sync 42
,06-30 13:11:13.641   297   297 E SMD     : DCD OFF
,06-30 13:11:16.641   297   297 E SMD     : DCD OFF
,06-30 13:11:17.321  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:17.421  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 13:11:19.651   297   297 E SMD     : DCD OFF
,06-30 13:11:22.651   297   297 E SMD     : DCD OFF
,06-30 13:11:25.651   297   297 E SMD     : DCD OFF,
,06-30 13:11:27.391  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:27.431  1014  2720 D SSRM:n  : SIOP:: AP = 290,
,06-30 13:11:28.651   297   297 E SMD     : DCD OFF
,06-30 13:11:31.651   297   297 E SMD     : DCD OFF
,06-30 13:11:34.651   297   297 E SMD     : DCD OFF
,06-30 13:11:37.451  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:11:37.451  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:37.651   297   297 E SMD     : DCD OFF
,06-30 13:11:40.651   297   297 E SMD     : DCD OFF
,06-30 13:11:41.061  1014  1304 E Watchdog: !@Sync 43
,06-30 13:11:43.661   297   297 E SMD     : DCD OFF
,06-30 13:11:46.661   297   297 E SMD     : DCD OFF
,06-30 13:11:47.461  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:11:47.511  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:49.661   297   297 E SMD     : DCD OFF
,06-30 13:11:50.871  1014  1046 I PowerManagerService: [PWL] Off : 1265s ago,
,06-30 13:11:52.661   297   297 E SMD     : DCD OFF
,06-30 13:11:55.661   297   297 E SMD     : DCD OFF,
,06-30 13:11:57.471  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:11:57.581  1014  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:58.661   297   297 E SMD     : DCD OFF
,06-30 13:12:01.661   297   297 E SMD     : DCD OFF
,06-30 13:12:04.671   297   297 E SMD     : DCD OFF
,06-30 13:12:07.481  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:07.651  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:07.671   297   297 E SMD     : DCD OFF,
,06-30 13:12:10.671   297   297 E SMD     : DCD OFF,
,06-30 13:12:11.071  1014  1304 E Watchdog: !@Sync 44
,06-30 13:12:13.671   297   297 E SMD     : DCD OFF
,06-30 13:12:16.671   297   297 E SMD     : DCD OFF
,06-30 13:12:17.501  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:17.711  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:12:19.671   297   297 E SMD     : DCD OFF
,06-30 13:12:22.671   297   297 E SMD     : DCD OFF
,06-30 13:12:25.681   297   297 E SMD     : DCD OFF
,06-30 13:12:27.511  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:27.771  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:28.681   297   297 E SMD     : DCD OFF
,06-30 13:12:31.681   297   297 E SMD     : DCD OFF
,06-30 13:12:34.681   297   297 E SMD     : DCD OFF
,06-30 13:12:37.521  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:37.681   297   297 E SMD     : DCD OFF
,06-30 13:12:37.841  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:40.681   297   297 E SMD     : DCD OFF
,06-30 13:12:41.071  1014  1304 E Watchdog: !@Sync 45
,06-30 13:12:43.681   297   297 E SMD     : DCD OFF
,06-30 13:12:46.681   297   297 E SMD     : DCD OFF
,06-30 13:12:47.541  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:47.901  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:49.691   297   297 E SMD     : DCD OFF,
,06-30 13:12:52.691   297   297 E SMD     : DCD OFF
,06-30 13:12:55.691   297   297 E SMD     : DCD OFF,
,06-30 13:12:57.551  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:12:57.961  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:58.691   297   297 E SMD     : DCD OFF
,06-30 13:13:01.691   297   297 E SMD     : DCD OFF
,06-30 13:13:04.691   297   297 E SMD     : DCD OFF
,06-30 13:13:07.561  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:07.691   297   297 E SMD     : DCD OFF
,06-30 13:13:08.031  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:10.701   297   297 E SMD     : DCD OFF,
,06-30 13:13:11.071  1014  1304 E Watchdog: !@Sync 46
,06-30 13:13:13.701   297   297 E SMD     : DCD OFF
,06-30 13:13:16.701   297   297 E SMD     : DCD OFF
,06-30 13:13:17.581  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:18.101  1014  1391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:19.701   297   297 E SMD     : DCD OFF,
,06-30 13:13:22.701   297   297 E SMD     : DCD OFF
,06-30 13:13:25.701   297   297 E SMD     : DCD OFF
,06-30 13:13:27.591  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:28.161  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:28.701   297   297 E SMD     : DCD OFF
,06-30 13:13:29.851  1014  1092 V AlarmManager: waitForAlarm result :4,
,06-30 13:13:29.861  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
06-30 13:13:29.861  1014  1014 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
06-30 13:13:29.861  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:13:29.861  1014  1014 V SAMP_GCMKill: GCM kill size 0. just return
06-30 13:13:29.871  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 13:13:29.871  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 13:13:29.881  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:13:29.881  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 13:13:29.881  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:13:29.911  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:13:29.911  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:13:29.921  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 13:13:29.921  1014  1393 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-30 13:13:29.921  1014  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,06-30 13:13:29.921  1014  1393 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:13:29.921  1014  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:13:29.921  1014  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-30 13:13:29.951  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:13:31.701   297   297 E SMD     : DCD OFF
,06-30 13:13:34.711   297   297 E SMD     : DCD OFF
,06-30 13:13:37.601  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:37.711   297   297 E SMD     : DCD OFF
,06-30 13:13:38.231  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:40.711   297   297 E SMD     : DCD OFF,
,06-30 13:13:41.071  1014  1304 E Watchdog: !@Sync 47
,06-30 13:13:43.711   297   297 E SMD     : DCD OFF
,06-30 13:13:45.891  1014  1046 I PowerManagerService: [PWL] Off : 1380s ago
,06-30 13:13:46.711   297   297 E SMD     : DCD OFF
,06-30 13:13:47.611  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:48.291  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:49.711   297   297 E SMD     : DCD OFF,
,06-30 13:13:52.711   297   297 E SMD     : DCD OFF
,06-30 13:13:55.721   297   297 E SMD     : DCD OFF,
,06-30 13:13:57.631  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:13:58.351  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:13:58.721   297   297 E SMD     : DCD OFF
,06-30 13:13:59.991  1014  1092 V AlarmManager: waitForAlarm result :8,
,06-30 13:14:01.721   297   297 E SMD     : DCD OFF
,06-30 13:14:04.721   297   297 E SMD     : DCD OFF
,06-30 13:14:07.641  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:07.721   297   297 E SMD     : DCD OFF
,06-30 13:14:08.421  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:10.721   297   297 E SMD     : DCD OFF,
,06-30 13:14:11.071  1014  1304 E Watchdog: !@Sync 48
,06-30 13:14:13.721   297   297 E SMD     : DCD OFF
,06-30 13:14:16.731   297   297 E SMD     : DCD OFF
,06-30 13:14:17.651  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:18.481  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:14:19.731   297   297 E SMD     : DCD OFF
,06-30 13:14:22.731   297   297 E SMD     : DCD OFF
,06-30 13:14:25.731   297   297 E SMD     : DCD OFF,
,06-30 13:14:27.661  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:28.541  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:28.731   297   297 E SMD     : DCD OFF
,06-30 13:14:31.731   297   297 E SMD     : DCD OFF
,06-30 13:14:34.731   297   297 E SMD     : DCD OFF,
,06-30 13:14:37.681  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:37.741   297   297 E SMD     : DCD OFF
,06-30 13:14:38.611  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:40.741   297   297 E SMD     : DCD OFF,
,06-30 13:14:41.071  1014  1304 E Watchdog: !@Sync 49
,06-30 13:14:43.741   297   297 E SMD     : DCD OFF
,06-30 13:14:46.741   297   297 E SMD     : DCD OFF
,06-30 13:14:47.691  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:48.671  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,06-30 13:14:49.741   297   297 E SMD     : DCD OFF
,06-30 13:14:52.741   297   297 E SMD     : DCD OFF
,06-30 13:14:55.751   297   297 E SMD     : DCD OFF
,06-30 13:14:57.701  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:14:58.741  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:58.751   297   297 E SMD     : DCD OFF,
,06-30 13:15:01.751   297   297 E SMD     : DCD OFF
,06-30 13:15:04.751   297   297 E SMD     : DCD OFF,
,06-30 13:15:07.721  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:15:07.751   297   297 E SMD     : DCD OFF
,06-30 13:15:08.681  1014  1083 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:15:08.681  1014  1083 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:15:08.681  1014  1082 D TimaService: TimaServiceHandler.handleMessage what =1,
,06-30 13:15:08.801  1014  1519 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:10.581  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:15:10.581  1014  1083 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:15:10.581  1014  1083 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:15:10.591  1014  1083 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:15:10.751   297   297 E SMD     : DCD OFF,
,06-30 13:15:11.071  1014  1304 E Watchdog: !@Sync 50
,06-30 13:15:13.751   297   297 E SMD     : DCD OFF
,06-30 13:15:16.761   297   297 E SMD     : DCD OFF
,06-30 13:15:17.731  1014  2720 D SSRM:n  : SIOP:: AP = 290
,06-30 13:15:18.861  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:15:18.871  1014  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,06-30 13:15:18.871  1014  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:15:18.871  1014  1027 D BatteryService: stay LED for fully charged
06-30 13:15:18.871  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:15:18.871  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 13:15:18.871  1014  1014 I MotionRecognitionService: Plugged
06-30 13:15:18.871  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:15:18.871  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
06-30 13:15:18.871  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
06-30 13:15:18.871  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,06-30 13:15:18.891  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
06-30 13:15:18.891  2641  6053 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:15:18.901  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
06-30 13:15:18.901  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:15:18.901  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:15:19.761   297   297 E SMD     : DCD OFF
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:15:22.761   297   297 E SMD     : DCD OFF
06-30 13:15:23.971  7845  7845 D AndroidRuntime: 
06-30 13:15:23.971  7845  7845 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:15:23.981  7845  7845 D AndroidRuntime: CheckJNI is OFF
06-30 13:15:23.981  7845  7845 D AndroidRuntime: readGMSProperty: start
06-30 13:15:23.981  7845  7845 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:15:23.981  7845  7845 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:15:23.981  7845  7845 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:15:23.981  7845  7845 D AndroidRuntime: readGMSProperty: end
06-30 13:15:23.981  7845  7845 D AndroidRuntime: addProductProperty: start
06-30 13:15:24.091  7845  7845 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:15:24.121  7845  7845 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:15:24.131  1014  1496 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:15:24.131  1014  1496 D PackageManager: START PACKAGE DELETE: observer{295332618}
06-30 13:15:24.131  1014  1496 D PackageManager: pkg{<packageName>}
06-30 13:15:24.131  1014  1496 D PackageManager: user{0}
06-30 13:15:24.131  1014  1496 D PackageManager: caller{2000}
06-30 13:15:24.131  1014  1496 D PackageManager: flags{2}
06-30 13:15:24.131  1014  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:15:24.131  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:15:24.131  1014  1496 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:15:24.131  1014  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:24.131  1014  1496 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:15:24.131  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:15:24.131  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:15:24.131  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:15:24.131  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 13:15:24.141  1014  1054 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
06-30 13:15:24.141  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
06-30 13:15:24.141  1014  1039 I ActivityManager: Killing 5980:com.test.thalitest/u0a151 (adj 0): stop com.test.thalitest cause uninstall pkg
06-30 13:15:24.141  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{238453b6 u0 com.test.thalitest/.MainActivity t81}
06-30 13:15:24.161  1014  1039 D InputDispatcher: Focus left window: 5980
06-30 13:15:24.161   258  1094 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
06-30 13:15:24.161   258  1095 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
06-30 13:15:24.161  1014  1039 D InputDispatcher: Focused application released
06-30 13:15:24.161  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:15:24.161  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:15:24.271  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
06-30 13:15:24.281  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
06-30 13:15:24.311  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 13:15:24.321  5727  5727 I art     : Explicit concurrent mark sweep GC freed 17492(995KB) AllocSpace objects, 2(32KB) LOS objects, 49% free, 4MB/8MB, paused 838us total 33.744ms
06-30 13:15:24.331  1597  1772 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 13:15:24.341  1795  1795 E SamsungIME: mOCRHelper is null
06-30 13:15:24.351  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10151]
06-30 13:15:24.351  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
06-30 13:15:24.351  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:15:24.351  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
06-30 13:15:24.351  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
06-30 13:15:24.351  1014  1122 V NetworkStats: performPollLocked() took 4ms
06-30 13:15:24.351  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:15:24.361  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:15:24.371  1439  1439 D RegisteredServicesCache: empty dynamic service
06-30 13:15:24.401  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jun 30 13:15:24 GMT+02:00 2016
06-30 13:15:24.401  1014  1220 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
06-30 13:15:24.401  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
06-30 13:15:24.401  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.401  1014  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:15:24.401  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
06-30 13:15:24.401  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:15:24.401  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:15:24.411  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
06-30 13:15:24.411  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:15:24.411  3845  3845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
06-30 13:15:24.421  1014  1220 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
06-30 13:15:24.421  1014  1220 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
06-30 13:15:24.431  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
06-30 13:15:24.431  1014  1220 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
06-30 13:15:24.431  1014  1014 I art     : Explicit concurrent mark sweep GC freed 20301(1679KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 4.974ms total 150.915ms
06-30 13:15:24.441  1014  1054 I art     : WaitForGcToComplete blocked for 140.751ms for cause Explicit
06-30 13:15:24.441  1014  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.441  1014  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.441  1014  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.441  1014  1220 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.441  3845  3845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 13:15:24.451  7857  7857 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.451  7857  7857 I libpersona: KNOX_SDCARD checking this for 10090
06-30 13:15:24.451  7857  7857 E Zygote  : v2
06-30 13:15:24.451  7857  7857 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.461  7857  7857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.461  7857  7857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.461  1014  1220 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7857 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
06-30 13:15:24.461  7857  7857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.471  3845  3845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
06-30 13:15:24.481  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-30 13:15:24.481  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.481  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
06-30 13:15:24.481  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.481  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.481  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.481  1014  1391 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 13:15:24.481  1014  1391 D SecContentProvider2: mCursor = null
06-30 13:15:24.491  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
06-30 13:15:24.491  7857  7857 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.491  7857  7857 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.491  1014  1014 D RCPManagerService: PackageReceiver onReceive()
06-30 13:15:24.491  7872  7872 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.491  7872  7872 E Zygote  : v2
06-30 13:15:24.491  7872  7872 I libpersona: KNOX_SDCARD checking this for 10032
06-30 13:15:24.491  7872  7872 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.491  7872  7872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.501  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-30 13:15:24.501  7872  7872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.501  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 13:15:24.501  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-30 13:15:24.501  7872  7872 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-30 13:15:24.501  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
06-30 13:15:24.501  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
06-30 13:15:24.511  1014  1039 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7872 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:15:24.511  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
06-30 13:15:24.511  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
06-30 13:15:24.521  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
06-30 13:15:24.521  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.521  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.521  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.521  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.521  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
06-30 13:15:24.541  7887  7887 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.541  7887  7887 E Zygote  : v2
06-30 13:15:24.541  7887  7887 I libpersona: KNOX_SDCARD checking this for 10098
06-30 13:15:24.541  7887  7887 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.541  7887  7887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.541  7887  7887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.541  1014  1039 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7887 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
06-30 13:15:24.541  7872  7872 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.541  7872  7872 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.551  7887  7887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.561  1014  1479 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-30 13:15:24.561  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
06-30 13:15:24.561  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.561  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:15:24.561  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
06-30 13:15:24.581  7887  7887 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.581  7887  7887 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.591  6901  7899 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 13:15:24.601  1014  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
06-30 13:15:24.601  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.601  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.601  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.601  1014  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.621  7903  7903 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.621  7903  7903 E Zygote  : v2
06-30 13:15:24.621  7903  7903 I libpersona: KNOX_SDCARD checking this for 10055
06-30 13:15:24.621  7903  7903 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.621  7903  7903 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.621  7903  7903 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.631  7903  7903 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.631  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
06-30 13:15:24.641  1014  1480 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7903 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
06-30 13:15:24.641  7857  7857 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-30 13:15:24.641  7903  7903 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.641  7903  7903 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.651  7857  7857 D elm:15121: ELMEngine.ELMEngine( context ).
06-30 13:15:24.661  1014  1054 W art     : Suspending all threads took: 6.093ms
06-30 13:15:24.661  7857  7857 D elm:15121: MDMBridge.setEnterpriseBridge()
06-30 13:15:24.671  1014  1220 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 13:15:24.671  1014  1220 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
06-30 13:15:24.671  3845  7856 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-30 13:15:24.671  7872  7918 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 13:15:24.671  7872  7918 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 13:15:24.671  1014  1220 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.671  1014  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:15:24.671  1014  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
06-30 13:15:24.681  3845  7856 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
06-30 13:15:24.681  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
06-30 13:15:24.681  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:15:24.681  7857  7857 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-30 13:15:24.681  1014  1054 I art     : Explicit concurrent mark sweep GC freed 7458(425KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 9.661ms total 245.850ms
06-30 13:15:24.681  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicy: uID is 10151
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 13:15:24.681  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 13:15:24.681  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.681  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.681  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.681  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.701  7857  7857 D elm:15121: ElmAgentService : onCreate()
06-30 13:15:24.701  1014  1479 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:15:24.701  7921  7921 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.701  7921  7921 E Zygote  : v2
06-30 13:15:24.701  7921  7921 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:15:24.701  7921  7921 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.701  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.701  7872  7918 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:15:24.701  7872  7918 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:15:24.701  7872  7918 D SPPClientService: ============PushLog. stop!
06-30 13:15:24.701  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.711  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.711  7857  7920 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 13:15:24.711  7857  7920 D elm:15121: MainReceiver.listeningToPackageRemoved()
06-30 13:15:24.711  7857  7920 D elm:15121: MDMBridge.getInstance()
06-30 13:15:24.711  7857  7920 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:15:24.721  7857  7920 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:15:24.721  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicy: uID is 10151
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 13:15:24.721  1014  2720 D SSRM:bc : MSG_TYPE_APP_REMOVED::
06-30 13:15:24.721  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-30 13:15:24.721  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:15:24.721  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 13:15:24.731  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 13:15:24.731  1014  1014 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
06-30 13:15:24.731  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.731  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.731  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.731  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.731  3845  3845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
06-30 13:15:24.741  7936  7936 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.741  7936  7936 E Zygote  : v2
06-30 13:15:24.741  7936  7936 I libpersona: KNOX_SDCARD checking this for 10032
06-30 13:15:24.751  7936  7936 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.751  7903  7903 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
06-30 13:15:24.751  1014  1479 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7936 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:15:24.751  1014  1479 I ActivityManager: Killing 6817:com.wsomacp/u0a23 (adj 15): empty #21
06-30 13:15:24.751  7936  7936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.761  7936  7936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.761  7936  7936 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-30 13:15:24.771   317   317 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 22.274ms
06-30 13:15:24.771  3276  3276 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
06-30 13:15:24.771  1014  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-30 13:15:24.781  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.781  7921  7921 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.781  3276  3276 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:15:24.781  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.781  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:15:24.781  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
06-30 13:15:24.781  3276  3276 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-30 13:15:24.781  3276  3276 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:15:24.781  3276  3276 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 13:15:24.781  3276  3276 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:15:24.781  3276  3276 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:15:24.781  3276  3276 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 13:15:24.781  3276  3276 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 13:15:24.791   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.574ms
06-30 13:15:24.791  7903  7903 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
06-30 13:15:24.791  7903  7903 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-30 13:15:24.791  7903  7903 D UserAnalysis: Create SecureDbHelper
06-30 13:15:24.811  7903  7903 D IntelligenceServiceApplication: onCreate()
06-30 13:15:24.811  7903  7903 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
06-30 13:15:24.811   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 20.681ms
06-30 13:15:24.811  7936  7936 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.811  7936  7936 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.821  7903  7903 D IntelligenceServiceApplication: no applications having user consent for prediction
06-30 13:15:24.831  1014  1054 D PackageManager: delete codoeFile: 
06-30 13:15:24.831  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
06-30 13:15:24.831  1014  1054 I AASA_removePackage: UID=10151 Target=com.test.thalitest
06-30 13:15:24.831  1014  1054 D PackageManager: result of delete: 1{295332618}
06-30 13:15:24.841  1014  1519 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
06-30 13:15:24.841  7857  7857 D elm:15121: ElmAgentService : onDestroy().
06-30 13:15:24.841  1014  3079 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:15:24.841  1014  3079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 13:15:24.841  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
06-30 13:15:24.841  1014  3079 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.841  1014  3079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:15:24.841  1014  3079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 13:15:24.851  7845  7845 D AndroidRuntime: Shutting down VM
06-30 13:15:24.861  1622  1622 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 13:15:24.861  1622  1622 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 13:15:24.861  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 13:15:24.861  1014  1054 D PackageManager: userId{-1}
06-30 13:15:24.861  1014  1054 D PackageManager: andCode{true}
06-30 13:15:24.861  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
06-30 13:15:24.871  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
06-30 13:15:24.871  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
06-30 13:15:24.871  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 13:15:24.881  1014  1038 W TextServicesManagerService: no available spell checker services found
06-30 13:15:24.881  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.881  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.881  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:15:24.891  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.891  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.891  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:15:24.901  7956  7956 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.901  7956  7956 E Zygote  : v2
06-30 13:15:24.901  7956  7956 I libpersona: KNOX_SDCARD checking this for 10003
06-30 13:15:24.901  7956  7956 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.901  7956  7956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.911  7956  7956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.911  6662  6662 I art     : Explicit concurrent mark sweep GC freed 605(43KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 1.278ms total 43.707ms
06-30 13:15:24.911  7956  7956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.911  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7956 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 13:15:24.911  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
06-30 13:15:24.911  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:15:24.921  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
06-30 13:15:24.921  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
06-30 13:15:24.921  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:15:24.921  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.921  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:15:24.921  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 13:15:24.931  1014  1519 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
06-30 13:15:24.931  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.931  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.931  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.931  1014  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
06-30 13:15:24.941  7903  7903 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
06-30 13:15:24.951  7971  7971 E Zygote  : MountEmulatedStorage()
06-30 13:15:24.951  7971  7971 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:15:24.951  7971  7971 E Zygote  : v2
06-30 13:15:24.951  7971  7971 I libpersona: KNOX_SDCARD not a persona
06-30 13:15:24.951  7956  7956 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.951  7971  7971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:15:24.951  7956  7956 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.951  7971  7971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:15:24.951  7971  7971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:15:24.961  6662  7954 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
06-30 13:15:24.971  7903  7903 D BluetoothAdapter: cancelDiscovery
06-30 13:15:24.971  1014  1519 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:15:24.971  1014  1519 I ActivityManager: Killing 6721:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
06-30 13:15:24.971  7971  7971 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:15:24.981  7971  7971 D ActivityThread: Added TimaKeyStore provider
06-30 13:15:24.981  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
06-30 13:15:24.981  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
06-30 13:15:24.981  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:15:24.981  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:15:24.981  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
06-30 13:15:24.991  1729  7986 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 13:15:25.001  2641  2655 D BluetoothAdapterProperties: mDiscovering is false
06-30 13:15:25.001  1014  1391 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
06-30 13:15:25.001  2641  2655 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
06-30 13:15:25.001  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:25.001  7903  7903 D BluetoothAdapter: cancelDiscovery = true
06-30 13:15:25.001  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:25.001  7903  7903 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
06-30 13:15:25.001  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:15:25.001  1014  1391 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
