#### Test 75789268d2ecd3a_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-08 14:02:23.629   290   290 E SMD     : DCD OFF
,07-08 14:02:24.029  6647  6647 D AndroidRuntime: 
07-08 14:02:24.029  6647  6647 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-08 14:02:24.029  6647  6647 D AndroidRuntime: CheckJNI is OFF
07-08 14:02:24.039  6647  6647 D AndroidRuntime: readGMSProperty: start
07-08 14:02:24.039  6647  6647 D AndroidRuntime: readGMSProperty: already setted!!
07-08 14:02:24.039  6647  6647 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-08 14:02:24.039  6647  6647 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-08 14:02:24.039  6647  6647 D AndroidRuntime: readGMSProperty: end
07-08 14:02:24.039  6647  6647 D AndroidRuntime: addProductProperty: start
07-08 14:02:24.169  6647  6647 E AffinityControl: AffinityControl: registerfunction enter
--------- beginning of system
07-08 14:02:24.179  1016  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-08 14:02:24.179  1016  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-08 14:02:24.179  1016  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-08 14:02:24.179  1016  1135 D BatteryService: stay LED for fully charged
07-08 14:02:24.179  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-08 14:02:24.189  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-08 14:02:24.189  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
07-08 14:02:24.189  1016  1016 I MotionRecognitionService: Plugged
07-08 14:02:24.189  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
07-08 14:02:24.189  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-08 14:02:24.189  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-08 14:02:24.189  6647  6647 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-08 14:02:24.199  3384  3384 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-08 14:02:24.199  3384  3490 D HeadsetStateMachine: Disconnected process message: 10
07-08 14:02:24.209  1016  1497 E PersonaManagerService: inState():  stateMachine is null !!
07-08 14:02:24.209  1016  1497 I PersonaManagerService: PersonaId don't exist
07-08 14:02:24.209  1016  1497 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-08 14:02:24.209  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-08 14:02:24.209  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-08 14:02:24.209  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-08 14:02:24.209  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-08 14:02:24.229  1016  1497 W ActivityManager: mDVFSHelper.acquire()
07-08 14:02:24.229  1016  1497 D FocusedStackFrame: Set to : 0
07-08 14:02:24.239  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-08 14:02:24.239  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-08 14:02:24.239  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:24.239  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:24.239  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:24.239  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:24.249  1016  1497 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6658 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-08 14:02:24.249  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-08 14:02:24.249  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-08 14:02:24.249  1016  1497 D InputDispatcher: Focused application set to: xxxx
07-08 14:02:24.249  1016  1497 D InputDispatcher: Focus left window: 1481
07-08 14:02:24.259  6647  6647 D AndroidRuntime: Shutting down VM
07-08 14:02:24.259  6658  6658 E Zygote  : MountEmulatedStorage()
07-08 14:02:24.259  6658  6658 E Zygote  : v2
07-08 14:02:24.259  6658  6658 I libpersona: KNOX_SDCARD checking this for 10170
07-08 14:02:24.259  6658  6658 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:24.259  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-08 14:02:24.259  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-08 14:02:24.259   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-08 14:02:24.259  6658  6658 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:24.259  6658  6658 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:24.269  6658  6658 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-08 14:02:24.279  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-08 14:02:24.279  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-08 14:02:24.289  6658  6658 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:24.289  6658  6658 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:24.289  1016  1331 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-08 14:02:24.289  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-08 14:02:24.309  1016  1331 D PersonaManager: isKioskContainerExistOnDevice
07-08 14:02:24.329  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-08 14:02:24.349   257   448 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
07-08 14:02:24.349   257  6083 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
07-08 14:02:24.359  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{abf5041 token=android.os.BinderProxy@2d17ee6d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-08 14:02:24.359  1481  1481 D Launcher: onTrimMemory. Level: 20
07-08 14:02:24.429  6658  6658 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-08 14:02:24.449  6658  6658 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6659-6660)
07-08 14:02:24.449  6658  6658 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:02:24.459  6647  6647 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-08 14:02:24.479  6658  6658 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32d281b9}
07-08 14:02:24.479  6658  6658 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-08 14:02:24.479  6658  6658 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-08 14:02:24.509  6658  6658 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-08 14:02:24.509  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:02:24.519  6658  6658 E SysUtils: ApplicationContext is null in ApplicationStatus
07-08 14:02:24.539  6658  6658 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-08 14:02:24.539  6658  6658 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-08 14:02:24.539  6658  6658 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-08 14:02:24.549  6658  6658 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-08 14:02:24.549  6658  6658 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-08 14:02:24.549  6658  6658 I Adreno-EGL: Build Date: 04/06/15 Mon
07-08 14:02:24.549  6658  6658 I Adreno-EGL: Local Branch: 
07-08 14:02:24.549  6658  6658 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-08 14:02:24.549  6658  6658 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-08 14:02:24.549  6658  6658 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-08 14:02:24.749  6658  6686 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-08 14:02:24.799  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:02:24.809  6658  6658 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-08 14:02:24.809  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{3d527f10 u0 com.test.thalitest/.MainActivity t3}
07-08 14:02:24.819  6658  6658 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-08 14:02:24.819  6658  6658 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-08 14:02:24.829  6658  6658 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-08 14:02:24.839  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:02:24.839  6658  6658 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-08 14:02:24.899  6658  6699 D OpenGLRenderer: Render dirty regions requested: true
07-08 14:02:24.909  1016  1252 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-08 14:02:24.909  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-08 14:02:24.909  1016  1252 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-08 14:02:24.909  1016  1252 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-08 14:02:24.909  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-08 14:02:24.969  6658  6658 V ActivityThread: updateVisibility : ActivityRecord{2dac25c8 token=android.os.BinderProxy@57b07ba {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-08 14:02:24.969  6658  6658 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-08 14:02:24.969  6658  6658 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-08 14:02:24.979   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-08 14:02:24.989  1016  1029 D InputDispatcher: Focus entered window: 6658
07-08 14:02:24.989  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-08 14:02:24.989  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-08 14:02:24.989  6658  6658 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-08 14:02:24.989  6658  6699 I OpenGLRenderer: Initialized EGL, version 1.4
07-08 14:02:24.999  6658  6699 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-08 14:02:24.999  6658  6699 D OpenGLRenderer: Enabling debug mode 0
07-08 14:02:25.019  1016  1331 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-08 14:02:25.029  1016  6702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-08 14:02:25.029  1175  1175 I StatusBar: Icon Only
07-08 14:02:25.029  1175  1175 D PanelView: There is/are notification(s) 
07-08 14:02:25.039  1016  1047 I ActivityManager: Displayed Component not be shown by security: +728ms (total +32s266ms)
07-08 14:02:25.039  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d527f10 u0 com.test.thalitest/.MainActivity t3} time:147254
07-08 14:02:25.039  1016  1047 W ActivityManager: mDVFSHelper.release()
07-08 14:02:25.049   257  1038 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-08 14:02:25.049   257   446 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-08 14:02:25.049  6658  6658 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-08 14:02:25.049  6658  6658 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@57b07ba time:147266
07-08 14:02:25.079  1823  1823 I SamsungIME: getCurrentCandidateView
07-08 14:02:25.109  6658  6658 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6658
07-08 14:02:25.209  1823  1823 D SamsungIME: Dismiss ExpandCandiate
,07-08 14:02:25.249  6658  6658 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-08 14:02:25.369  1823  1823 I SamsungIME: getDebugLevel  : 0x4f4c
07-08 14:02:25.409  1823  1823 I SamsungIME: getDebugLevel  : 0x4f4c
07-08 14:02:25.419  1823  1823 I SamsungIME: KeybaordView init() : load resources
07-08 14:02:25.439  6658  6703 D jxcore_app_log: JniHelper::setJavaVM(0xb76d92f0), pthread_self() = -1211938640
07-08 14:02:25.449  1823  1823 I SamsungIME: getCurrentKeyboard
07-08 14:02:25.449  1823  1823 I SamsungIME: getTextKeyboard
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-08 14:02:25.449  6658  6703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9890f8 added. We now have 1 listener(s)
07-08 14:02:25.459  6658  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
07-08 14:02:25.459  6658  6703 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-08 14:02:25.459  6658  6703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:02:25.459  6658  6703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3170c737 added. We now have 1 listener(s)
07-08 14:02:25.469  6658  6703 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:25.469  6658  6703 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:02:25.479  6658  6703 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:25.489  6658  6703 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:25.489  6658  6703 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-08 14:02:25.489  6658  6703 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:25.489  6658  6703 I io.jxcore.node.LifeCycleMonitor: start: OK
07-08 14:02:25.489  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:25.489  6658  6658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:25.489  1823  1823 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-08 14:02:25.519  6658  6658 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-08 14:02:26.089  6658  6709 W jxcore-log: Initializing JXcore engine
07-08 14:02:26.089  6658  6709 W jxcore-log: JXcore engine is ready
,07-08 14:02:26.139  1959  1959 E audit   : type=1400 msg=audit(1467979346.139:205): avc:  denied  { ioctl } for  pid=6709 comm="Thread-1203" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-08 14:02:26.139  1959  1959 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:26.139  1959  1959 E audit   : type=1300 msg=audit(1467979346.139:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9eaf28f8 items=0 ppid=314 ppcomm=main pid=6709 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1203" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-08 14:02:26.139  1959  1959 E audit   : type=1320 msg=audit(1467979346.139:205): 
,07-08 14:02:26.149  6658  6709 W jxcore-log: Starting JXcore engine
,07-08 14:02:26.249  6658  6709 W jxcore-log: Platform android
07-08 14:02:26.249  6658  6709 W jxcore-log: 
07-08 14:02:26.249  6658  6709 W jxcore-log: Process ARCH arm
07-08 14:02:26.249  6658  6709 W jxcore-log: 
,07-08 14:02:26.449  6658  6709 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:02:26.449  6658  6709 I jxcore-log: 
,07-08 14:02:26.449  6658  6709 W jxcore-log: JXcore engine is started
,07-08 14:02:26.459  6658  6703 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-08 14:02:26.459  6658  6658 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-08 14:02:26.469  6658  6709 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-08 14:02:26.469  6658  6709 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-08 14:02:26.479  6658  6658 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-08 14:02:26.479  6658  6658 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-08 14:02:26.479  1016  1331 D FocusedStackFrame: Set to : 0
07-08 14:02:26.479  1016  1331 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-08 14:02:26.479  1016  1331 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-08 14:02:26.479  1016  1331 D InputDispatcher: Focused application set to: xxxx
07-08 14:02:26.479  1016  1331 D InputDispatcher: Focus left window: 6658
07-08 14:02:26.479  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-08 14:02:26.479  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-08 14:02:26.489  1016  1331 I ActivityManager: Killing 6272:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-08 14:02:26.489  6658  6658 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-08 14:02:26.499  6658  6658 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-08 14:02:26.499  6658  6703 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
07-08 14:02:26.499  6658  6658 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:02:26.499  6658  6658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:02:26.499  6658  6658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:02:26.499  6658  6658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:02:26.499  6658  6658 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9890f8 removed from the list
07-08 14:02:26.499  6658  6658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:02:26.499  6658  6658 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3170c737 removed from the list
07-08 14:02:26.499  6658  6658 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:02:26.499  6658  6658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-08 14:02:26.499  6658  6658 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-08 14:02:26.519   257  1038 I SurfaceFlinger: id=13 Removed NainActivit (6/8),
07-08 14:02:26.519   257   448 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-08 14:02:26.519  1016  1931 W ActivityManager: mDVFSHelper.acquire()
,07-08 14:02:26.529  1016  1931 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-08 14:02:26.559  1481  1481 D Launcher: onRestart, Launcher: 756056181
,07-08 14:02:26.559  1481  1481 D Launcher: onStart, Launcher: 756056181
07-08 14:02:26.559  1481  1481 D Launcher.HomeView: onStart
07-08 14:02:26.559  1481  1481 D Launcher: onResume, Launcher: 756056181
,07-08 14:02:26.569  1016  1497 D SettingsProvider: name = kids_home_mode
07-08 14:02:26.569  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-08 14:02:26.569  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-08 14:02:26.569  1016  1497 D SettingsProvider: selectionArgs: false
07-08 14:02:26.569  1016  1497 D SettingsProvider: selectionArgs: 10006
,07-08 14:02:26.569  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-08 14:02:26.569  1016  1497 D SettingsProvider: ret = -1
07-08 14:02:26.569  1481  1481 D Launcher.HomeView: onResume
,07-08 14:02:26.579  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-08 14:02:26.579  1481  1481 D MenuAppsGridFragment: onResume
,07-08 14:02:26.579  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:26.579  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.579  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-08 14:02:26.579  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-08 14:02:26.589  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-08 14:02:26.589  1016  1931 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-08 14:02:26.589  1016  1931 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-08 14:02:26.589  1016  1931 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:26.589  1016  1931 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.589  1016  1931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-08 14:02:26.589  1016  1931 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-08 14:02:26.589  1016  1931 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.589  1016  1931 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.589  1016  1931 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.589  1016  1931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:26.619  6714  6714 E Zygote  : MountEmulatedStorage()
,07-08 14:02:26.619  6714  6714 E Zygote  : v2
07-08 14:02:26.619  6714  6714 I libpersona: KNOX_SDCARD checking this for 10039
07-08 14:02:26.619  6714  6714 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:26.619  1016  1931 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6714 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-08 14:02:26.619  6714  6714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:26.619  1016  1135 D ActivityManager: handle home activity for 0,
,07-08 14:02:26.619  1016  1135 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-08 14:02:26.619  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-08 14:02:26.619  1016  1135 D KnoxTimeoutHandler: post home show event for user 0
07-08 14:02:26.619  1016  1135 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-08 14:02:26.619  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-08 14:02:26.619  1016  1135 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-08 14:02:26.619  1016  1135 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-08 14:02:26.619  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-08 14:02:26.619  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-08 14:02:26.619  1481  1481 D Launcher.HomeView: onPause
07-08 14:02:26.619  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-08 14:02:26.619  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.619  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.619  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-08 14:02:26.629  6714  6714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:26.629  6714  6714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:26.629   290   290 E SMD     : DCD OFF
,07-08 14:02:26.629  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.629  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-08 14:02:26.629  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-08 14:02:26.629  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.629  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-08 14:02:26.629  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.629  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.629  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:26.649  6729  6729 E Zygote  : MountEmulatedStorage()
,07-08 14:02:26.649  6729  6729 E Zygote  : v2
07-08 14:02:26.649  6729  6729 I libpersona: KNOX_SDCARD checking this for 10089
07-08 14:02:26.649  6729  6729 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:26.649  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6729 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-08 14:02:26.649  6729  6729 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:26.649  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.649  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-08 14:02:26.649  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.649  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-08 14:02:26.649  6729  6729 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:26.649  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.649  6729  6729 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-08 14:02:26.649  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.649  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.649  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.659  6714  6714 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:26.659  6714  6714 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:26.669  6739  6739 E Zygote  : MountEmulatedStorage(),
07-08 14:02:26.669  6739  6739 E Zygote  : v2
07-08 14:02:26.669  6739  6739 I libpersona: KNOX_SDCARD checking this for 10139
07-08 14:02:26.669  6739  6739 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:26.669  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6739 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,07-08 14:02:26.669  6739  6739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:26.669  6739  6739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:26.669  6739  6739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:26.689  6729  6729 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:26.689  6729  6729 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:26.699   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-08 14:02:26.699  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-08 14:02:26.699  6739  6739 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:26.699  1016  1252 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-08 14:02:26.699  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.699  1016  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.699  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-08 14:02:26.699  6739  6739 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:26.709  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.709  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.709  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-08 14:02:26.709  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-08 14:02:26.709  2602  2602 D Recents_RecreateReceiver: onReceive by home
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-08 14:02:26.709  6714  6714 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-08 14:02:26.709  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:26.709  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.709  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-08 14:02:26.709  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-08 14:02:26.709  1016  1477 D InputDispatcher: Focus entered window: 1481
,07-08 14:02:26.719  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.719  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.719  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.719  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:26.719  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-08 14:02:26.719  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-08 14:02:26.719  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-08 14:02:26.719  6729  6729 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-08 14:02:26.719  6729  6729 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-08 14:02:26.729  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{abf5041 token=android.os.BinderProxy@2d17ee6d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-08 14:02:26.729  1481  1481 D Launcher.HomeView: onStop
07-08 14:02:26.729  1016  1331 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-08 14:02:26.739  6658  6658 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-08 14:02:26.739  1016  6760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-08 14:02:26.739  6762  6762 E Zygote  : MountEmulatedStorage()
07-08 14:02:26.739  6762  6762 E Zygote  : v2
07-08 14:02:26.739  1175  1175 I StatusBar: Icon Only
,07-08 14:02:26.749  1175  1175 D PanelView: There is/are notification(s) 
07-08 14:02:26.749  6762  6762 I libpersona: KNOX_SDCARD checking this for 10084
07-08 14:02:26.749  6762  6762 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:26.749  1016  1029 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6762 uid=10084 gids={50084, 9997} abi=armeabi-v7a
07-08 14:02:26.749  6762  6762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:26.759  6762  6762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-08 14:02:26.759  6762  6762 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-08 14:02:26.779  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d17ee6d time:148999
,07-08 14:02:26.789  6710  6710 D AndroidRuntime: 
07-08 14:02:26.789  6710  6710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<,
07-08 14:02:26.789  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:26.789  6762  6762 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:26.789  6710  6710 D AndroidRuntime: CheckJNI is OFF
,07-08 14:02:26.789  6710  6710 D AndroidRuntime: readGMSProperty: start
07-08 14:02:26.789  6710  6710 D AndroidRuntime: readGMSProperty: already setted!!
07-08 14:02:26.789  6710  6710 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-08 14:02:26.789  6710  6710 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-08 14:02:26.789  6710  6710 D AndroidRuntime: readGMSProperty: end
07-08 14:02:26.789  6710  6710 D AndroidRuntime: addProductProperty: start
,07-08 14:02:26.809  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-08 14:02:26.809  6762  6762 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-08 14:02:26.809  6739  6739 V TaskCloserActivity: TaskCloserActivity enter()
,07-08 14:02:26.809  1823  1823 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-08 14:02:26.819  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7ccf959 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:149031
07-08 14:02:26.819  1016  1047 W ActivityManager: mDVFSHelper.release()
,07-08 14:02:26.819  6739  6739 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-08 14:02:26.819  1016  3020 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.819  1016  3020 I ActivityManager: Killing 6305:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-08 14:02:26.819  1016  3020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.819  1016  3020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-08 14:02:26.839  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:26.839  1016  1252 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-08 14:02:26.839  1016  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:26.839  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-08 14:02:26.839  1016  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:26.839  1016  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.839  1016  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:26.839  1016  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:26.849  6787  6787 E Zygote  : MountEmulatedStorage()
07-08 14:02:26.849  6787  6787 E Zygote  : v2
07-08 14:02:26.849  6787  6787 I libpersona: KNOX_SDCARD checking this for 10135
07-08 14:02:26.849  6787  6787 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:26.849  1016  1252 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6787 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-08 14:02:26.849  1016  1252 I ActivityManager: Killing 6338:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
07-08 14:02:26.849  6787  6787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:26.859  6787  6787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-08 14:02:26.859  1016  1252 I ActivityManager: Killing 6357:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-08 14:02:26.859  6787  6787 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:26.889  6787  6787 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:26.889  6787  6787 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:26.899  6787  6787 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-08 14:02:26.899  6787  6787 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-08 14:02:26.899  6787  6787 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,07-08 14:02:26.899  6787  6787 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,07-08 14:02:26.899  6787  6787 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-08 14:02:26.919  1016  1135 D PersonaManager: isKioskContainerExistOnDevice
,07-08 14:02:26.929  6710  6710 E AffinityControl: AffinityControl: registerfunction enter
,07-08 14:02:26.929  6714  6714 D NearbySource: Nearby Source Create!
,07-08 14:02:26.939  6714  6714 D NearbyContext: Nearby Context Create!
,07-08 14:02:26.939  1016  3020 I ActivityManager: Killing 6325:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-08 14:02:26.949  6710  6710 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-08 14:02:26.969  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-08 14:02:26.969  1016  1028 D PackageManager: START PACKAGE DELETE: observer{185471518}
07-08 14:02:26.969  1016  1028 D PackageManager: pkg{<packageName>}
07-08 14:02:26.969  1016  1028 D PackageManager: user{0}
07-08 14:02:26.969  1016  1028 D PackageManager: caller{2000}
07-08 14:02:26.969  1016  1028 D PackageManager: flags{2}
07-08 14:02:26.969  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-08 14:02:26.969  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-08 14:02:26.969  1016  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-08 14:02:26.969  1016  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-08 14:02:26.969  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,07-08 14:02:26.969  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-08 14:02:26.969  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-08 14:02:26.969  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-08 14:02:26.969  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-08 14:02:26.969  1016  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-08 14:02:26.969  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-08 14:02:26.969  1016  1042 I ActivityManager: Killing 6658:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-08 14:02:26.989   256   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-08 14:02:26.989   256   534 W Vold    : Returning OperationFailed - no handler for errno 0
,07-08 14:02:26.989  6714  6714 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
,07-08 14:02:26.989  6714  6714 D SLinkSource: Samsung link source created
,07-08 14:02:27.069  1016  1055 W PackageSettings: Skipping PackageSetting{1e9fd040 com.example.hello/10168} due to missing metadata
,07-08 14:02:27.119  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-08 14:02:27.169  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-08 14:02:27.189  2775  2775 I art     : Explicit concurrent mark sweep GC freed 24241(1313KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.082ms total 53.902ms
,07-08 14:02:27.199  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-08 14:02:27.229  6478  6478 I art     : Explicit concurrent mark sweep GC freed 604(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 705us total 91.192ms
,07-08 14:02:27.239  1823  1823 E SamsungIME: mOCRHelper is null
,07-08 14:02:27.239  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-08 14:02:27.259  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,07-08 14:02:27.259  1439  1439 D RegisteredServicesCache: empty dynamic service
,07-08 14:02:27.279  6714  6804 D ContactProvider: getAllContactInfoList Start
,07-08 14:02:27.279  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,07-08 14:02:27.279  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,07-08 14:02:27.299  4712  4712 I art     : Explicit concurrent mark sweep GC freed 9072(560KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/16MB, paused 2.682ms total 154.871ms
,07-08 14:02:27.359  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-08 14:02:27.359  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-08 14:02:27.359  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
,07-08 14:02:27.359  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
07-08 14:02:27.359  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-08 14:02:27.359  1016  1122 V NetworkStats: performPollLocked() took 6ms
07-08 14:02:27.359  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-08 14:02:27.379  1016  1016 I art     : Explicit concurrent mark sweep GC freed 60629(3MB) AllocSpace objects, 25(400KB) LOS objects, 33% free, 24MB/36MB, paused 3.872ms total 225.651ms
,07-08 14:02:27.379  1016  1028 I art     : WaitForGcToComplete blocked for 140.675ms for cause Explicit
,07-08 14:02:27.409  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,07-08 14:02:27.409  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-08 14:02:27.409  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-08 14:02:27.409  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-08 14:02:27.409  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-08 14:02:27.409  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-08 14:02:27.409  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-08 14:02:27.419  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,07-08 14:02:27.419  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-08 14:02:27.479  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-08 14:02:27.479  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-08 14:02:27.479  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-08 14:02:27.479  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-08 14:02:27.479  1016  3513 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-08 14:02:27.479  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-08 14:02:27.489  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-08 14:02:27.549  1016  1028 I art     : Explicit concurrent mark sweep GC freed 19171(1260KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 4.044ms total 168.661ms
,07-08 14:02:27.549  1016  1055 I art     : WaitForGcToComplete blocked for 217.205ms for cause Explicit
07-08 14:02:27.549  1981  2168 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-08 14:02:27.549  1016  1491 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-08 14:02:27.549  1016  1491 D SecContentProvider2: mCursor = null
,07-08 14:02:27.549  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
07-08 14:02:27.549  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-08 14:02:27.549  1016  1041 W TextServicesManagerService: no available spell checker services found
,07-08 14:02:27.559  1016  3020 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-08 14:02:27.559  6714  6714 D GalleryCacheReady: Receive : home resume
,07-08 14:02:27.569  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.569  1016  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.569  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-08 14:02:27.569  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.579  6205  6205 D Mms/UIEventReceiver: ui event,
07-08 14:02:27.579  1016  1331 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
07-08 14:02:27.579  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.579  1016  1331 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.579  1016  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.579  1016  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-08 14:02:27.589  6739  6739 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-08 14:02:27.589  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.599  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.599  2727  2727 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 08 14:02:27 GMT+02:00 2016
,07-08 14:02:27.599  1016  1497 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-08 14:02:27.599  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-08 14:02:27.609  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:27.609  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.609  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-08 14:02:27.609  6714  6804 D ContactProvider: getAllContactInfoList End
,07-08 14:02:27.609  6714  6804 I syncContacts: thread: 1188, sync time = 446
,07-08 14:02:27.619  2727  2727 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-08 14:02:27.619  1016  1135 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-08 14:02:27.619  1016  1135 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-08 14:02:27.619  1016  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-08 14:02:27.619  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:27.619  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.619  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.619  1016  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:27.629  6807  6807 E Zygote  : MountEmulatedStorage(),
07-08 14:02:27.629  6807  6807 I libpersona: KNOX_SDCARD checking this for 10090
07-08 14:02:27.629  6807  6807 E Zygote  : v2
07-08 14:02:27.629  6807  6807 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:27.629  6807  6807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:27.639  2727  2727 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
07-08 14:02:27.639  1016  1135 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6807 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-08 14:02:27.639  6807  6807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-08 14:02:27.639  6807  6807 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:27.639  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-08 14:02:27.639  6205  6205 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-08 14:02:27.639  2727  2727 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-08 14:02:27.639  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.639  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-08 14:02:27.639  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.639  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-08 14:02:27.649  2727  2727 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-08 14:02:27.659  6822  6822 E Zygote  : MountEmulatedStorage()
,07-08 14:02:27.659  6822  6822 E Zygote  : v2
07-08 14:02:27.659  6822  6822 I libpersona: KNOX_SDCARD checking this for 1000
07-08 14:02:27.659  6822  6822 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:27.659  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:27.659  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-08 14:02:27.659  6807  6807 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:27.659  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-08 14:02:27.659  6807  6807 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:27.669  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.669  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.669  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.669  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.669  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:27.669  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-08 14:02:27.669  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:27.669  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-08 14:02:27.669  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-08 14:02:27.669  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-08 14:02:27.679  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-08 14:02:27.679  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.679  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.689  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-08 14:02:27.699   314   314 I art     : Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.846ms total 36.247ms
,07-08 14:02:27.699  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-08 14:02:27.699  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-08 14:02:27.699  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-08 14:02:27.699  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.719   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.764ms
,07-08 14:02:27.729  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:27.729  6822  6822 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:27.729  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.729  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.739   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 19.111ms
07-08 14:02:27.739  1016  1055 I art     : Explicit concurrent mark sweep GC freed 6204(339KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.056ms total 187.872ms
07-08 14:02:27.739  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-08 14:02:27.739  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-08 14:02:27.739  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-08 14:02:27.749  6837  6837 E Zygote  : MountEmulatedStorage()
07-08 14:02:27.749  6837  6837 I libpersona: KNOX_SDCARD checking this for 1000
07-08 14:02:27.749  6837  6837 E Zygote  : v2
07-08 14:02:27.749  6837  6837 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:27.749  6837  6837 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:27.749  2727  6806 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-08 14:02:27.749  2727  6806 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
07-08 14:02:27.749  1016  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6837 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-08 14:02:27.749  1016  1472 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-08 14:02:27.749  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-08 14:02:27.759  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.759  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.759  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-08 14:02:27.759  6837  6837 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:27.759  6837  6837 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:27.769  2727  2727 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-08 14:02:27.769  1016  1252 I TactileAssist: enable value -1
07-08 14:02:27.769  1016  1252 I TactileAssist: internal enable value -1
07-08 14:02:27.769  1016  1252 I TactileAssist: intensity value -1
07-08 14:02:27.769  1016  1252 I TactileAssist: saveAppList value true
,07-08 14:02:27.769  1016  1252 I TactileAssist: List of disabled apps :
,07-08 14:02:27.779  6205  6845 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-08 14:02:27.779  6205  6845 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-08 14:02:27.779  6837  6837 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:27.779  1016  1055 D PackageManager: delete codoeFile: 
07-08 14:02:27.779  6837  6837 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:27.789  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.789  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,07-08 14:02:27.789  1016  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-08 14:02:27.799  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-08 14:02:27.799  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-08 14:02:27.799  1016  1055 D PackageManager: result of delete: 1{185471518}
,07-08 14:02:27.799  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-08 14:02:27.799  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-08 14:02:27.799  6460  6460 D Compatibility: onReceive() it will make start service
07-08 14:02:27.799  1016  1584 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-08 14:02:27.799  1016  1584 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-08 14:02:27.799  1016  1584 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.799  1016  1584 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.799  1016  1584 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-08 14:02:27.809  6837  6837 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-08 14:02:27.809  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-08 14:02:27.809  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-08 14:02:27.809  1016  1497 D SecContentProvider2: uri = -1 selection = getSealedState
07-08 14:02:27.809  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-08 14:02:27.809  1016  1497 D SecContentProvider2: mCursor = null
07-08 14:02:27.809  6710  6710 D AndroidRuntime: Shutting down VM
07-08 14:02:27.809  6837  6837 I PopupuiReceiver_KNOX: getSealedState : true
07-08 14:02:27.809  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-08 14:02:27.819  1016  3020 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-08 14:02:27.819  1016  3020 D SecContentProvider2: mCursor = null
,07-08 14:02:27.819  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-08 14:02:27.819  6807  6807 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-08 14:02:27.819  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.819  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:27.819  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-08 14:02:27.819  6807  6807 D elm:15121: ELMEngine.ELMEngine( context ).
,07-08 14:02:27.819  6807  6807 D elm:15121: MDMBridge.setEnterpriseBridge()
07-08 14:02:27.819  6822  6822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-08 14:02:27.819  6837  6837 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
07-08 14:02:27.819  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-08 14:02:27.819  1016  1055 D PackageManager: userId{-1}
07-08 14:02:27.819  1016  1055 D PackageManager: andCode{true}
07-08 14:02:27.819  1016  1135 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,07-08 14:02:27.819  1016  1135 D SecContentProvider2: mCursor = null
07-08 14:02:27.819  6837  6837 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-08 14:02:27.819  6837  6837 D PopupuiReceiver: Action package removed
,07-08 14:02:27.819  1016  1472 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-08 14:02:27.819  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-08 14:02:27.819  6460  6853 D Compatibility: onHandleIntent()
,07-08 14:02:27.819  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.819  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.819  6460  6853 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
07-08 14:02:27.819  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
07-08 14:02:27.819  6460  6853 D Compatibility: found: 2
07-08 14:02:27.819  6460  6853 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-08 14:02:27.819  6460  6853 D Compatibility: skipping ResolveInfo{472bbac com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-08 14:02:27.819  6460  6853 D Compatibility: considering ResolveInfo{2d108075 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-08 14:02:27.819  6460  6853 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-08 14:02:27.829  6807  6807 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-08 14:02:27.829  6460  6853 D Compatibility: enabling receiver ResolveInfo{6a8880a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-08 14:02:27.829  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-08 14:02:27.829  6478  6854 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-08 14:02:27.829  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.829  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.829  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.829  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:27.829  6807  6807 D elm:15121: ElmAgentService : onCreate()
07-08 14:02:27.829  6807  6855 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-08 14:02:27.829  6807  6855 D elm:15121: MainReceiver.listeningToPackageRemoved(),
07-08 14:02:27.829  6807  6855 D elm:15121: MDMBridge.getInstance()
07-08 14:02:27.829  6807  6855 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-08 14:02:27.829  6807  6855 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-08 14:02:27.839  6460  6853 D Compatibility: enabling receiver ResolveInfo{30f1287b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-08 14:02:27.839  6856  6856 E Zygote  : MountEmulatedStorage()
07-08 14:02:27.839  6856  6856 E Zygote  : v2
07-08 14:02:27.839  6856  6856 I libpersona: KNOX_SDCARD checking this for 10145
07-08 14:02:27.839  6460  6853 D Compatibility: enabling receiver ResolveInfo{1b25e698 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-08 14:02:27.839  6856  6856 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:27.839  6856  6856 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:27.849  6856  6856 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-08 14:02:27.849  6856  6856 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:27.849  1016  1497 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6856 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
07-08 14:02:27.849  1016  1584 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-08 14:02:27.849  1016  1584 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-08 14:02:27.849  1016  1584 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.849  1016  1584 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:27.849  1016  1584 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-08 14:02:27.849  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-08 14:02:27.859  6460  6853 D Compatibility: enabling receiver ResolveInfo{cf5aef1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-08 14:02:27.859  6807  6807 D elm:15121: ElmAgentService : onDestroy().
,07-08 14:02:27.859  6460  6853 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-08 14:02:27.869  2901  2901 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-08 14:02:27.869  2901  2901 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-08 14:02:27.869  2901  2901 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-08 14:02:27.869  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-08 14:02:27.869  2901  2901 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-08 14:02:27.869  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.869  2901  2901 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-08 14:02:27.869  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.869  2901  2901 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-08 14:02:27.869  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.869  2901  2901 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-08 14:02:27.869  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.869  2901  2901 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:27.869  2901  2901 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-08 14:02:27.869  2901  2901 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-08 14:02:27.869  2901  2901 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:27.869  2901  2901 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:02:27.869  2901  2901 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-08 14:02:27.869  2901  2901 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-08 14:02:27.879  6856  6856 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:27.879  6856  6856 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:27.889  6874  6874 E Zygote  : MountEmulatedStorage()
07-08 14:02:27.889  1016  1497 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6874 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-08 14:02:27.889  6874  6874 E Zygote  : v2
07-08 14:02:27.889  6874  6874 I libpersona: KNOX_SDCARD checking this for 1000
07-08 14:02:27.889  6874  6874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:27.889  6874  6874 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:27.899  6874  6874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:27.899  1016  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-08 14:02:27.899  6874  6874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:27.899  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.899  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.899  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.899  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:27.919  6888  6888 E Zygote  : MountEmulatedStorage(),
07-08 14:02:27.919  6888  6888 E Zygote  : v2
07-08 14:02:27.919  6888  6888 I libpersona: KNOX_SDCARD checking this for 10055
07-08 14:02:27.919  6888  6888 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:27.919  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:27.919  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:27.919  1016  1497 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6888 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-08 14:02:27.919  6874  6874 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:27.919  6874  6874 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:27.929  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:27.929  1016  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-08 14:02:27.939  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.939  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:27.939  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-08 14:02:27.949  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:27.949  1016  1931 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-08 14:02:27.949  6888  6888 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:27.949  1016  1931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-08 14:02:27.949  6856  6856 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-08 14:02:27.949  6856  6856 D ThemeInfoUtil: isCurrentFestival = false
,07-08 14:02:27.949  1016  1931 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:27.949  1016  1931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-08 14:02:27.949  1016  1931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-08 14:02:27.959  6874  6874 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-08 14:02:27.959  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-08 14:02:27.959  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.959  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.959  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.959  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:27.969  6874  6874 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-08 14:02:27.969  1016  1472 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,07-08 14:02:27.969  1016  1472 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-08 14:02:27.979  6904  6904 E Zygote  : MountEmulatedStorage()
,07-08 14:02:27.979  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-08 14:02:27.979  6904  6904 E Zygote  : v2
07-08 14:02:27.979  6904  6904 I libpersona: KNOX_SDCARD checking this for 1000
07-08 14:02:27.979  6904  6904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:27.979  6904  6904 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:27.979  1016  3020 I ActivityManager: Killing 6402:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-08 14:02:27.989  1016  1584 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-08 14:02:27.989  1016  1584 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-08 14:02:27.989  1016  1584 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:27.989  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-08 14:02:27.989  1016  1584 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:27.989  1016  1584 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-08 14:02:27.989  6904  6904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:27.989  6904  6904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:27.989  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,07-08 14:02:27.989  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:27.989  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-08 14:02:27.999  1016  3020 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,07-08 14:02:27.999  1016  3020 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.999  1016  3020 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.999  1016  3020 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:27.999  1016  3020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:28.009  6917  6917 E Zygote  : MountEmulatedStorage()
07-08 14:02:28.009  6917  6917 E Zygote  : v2
07-08 14:02:28.009  6917  6917 I libpersona: KNOX_SDCARD checking this for 10148
07-08 14:02:28.009  6917  6917 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:28.009  6917  6917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:28.019  6917  6917 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:28.019  6917  6917 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:28.019  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
07-08 14:02:28.019  6904  6904 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:28.019  6710  6710 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-08 14:02:28.019  1016  3020 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6917 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
,07-08 14:02:28.019  1016  3020 I ActivityManager: Killing 6423:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-08 14:02:28.029  6888  6888 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-08 14:02:28.049  6917  6917 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:28.049  6917  6917 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:28.049  1016  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-08 14:02:28.049  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-08 14:02:28.049  6511  6511 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,07-08 14:02:28.049  6511  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,07-08 14:02:28.049  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:28.049  1016  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:28.049  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-08 14:02:28.049  1016  1252 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-08 14:02:28.049  1016  1252 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,07-08 14:02:28.059  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:28.059  1016  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-08 14:02:28.059  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,07-08 14:02:28.059  6511  6511 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,07-08 14:02:28.069  6904  6904 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-08 14:02:28.069  6904  6904 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-08 14:02:28.069  6904  6904 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-08 14:02:28.069  6888  6888 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-08 14:02:28.069  6888  6888 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-08 14:02:28.069  6888  6888 D UserAnalysis: Create SecureDbHelper
,07-08 14:02:28.079  6511  6935 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,07-08 14:02:28.079  6511  6935 D FilterUnInstaller: before removeFromFS
,07-08 14:02:28.089  1016  1497 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,07-08 14:02:28.089  6904  6904 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-08 14:02:28.089  6904  6904 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-08 14:02:28.089  6904  6904 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-08 14:02:28.089  6904  6904 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-08 14:02:28.089  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.089  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.089  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.089  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:28.099  6937  6937 E Zygote  : MountEmulatedStorage()
07-08 14:02:28.099  6937  6937 E Zygote  : v2
,07-08 14:02:28.099  6937  6937 I libpersona: KNOX_SDCARD checking this for 10095
07-08 14:02:28.099  6937  6937 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:28.099  1016  1497 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6937 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
07-08 14:02:28.099  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:28.109  6888  6888 D IntelligenceServiceApplication: onCreate()
,07-08 14:02:28.109  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:28.109  1016  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,07-08 14:02:28.109  6888  6888 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
07-08 14:02:28.109  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:28.109  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.109  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.109  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.109  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:28.119  6888  6888 D IntelligenceServiceApplication: no applications having user consent for prediction
07-08 14:02:28.119  6917  6917 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,07-08 14:02:28.129  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:28.129  6937  6937 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:28.129  6952  6952 E Zygote  : MountEmulatedStorage()
07-08 14:02:28.129  6952  6952 E Zygote  : v2
,07-08 14:02:28.129  6952  6952 I libpersona: KNOX_SDCARD checking this for 10029
07-08 14:02:28.129  6952  6952 I libpersona: KNOX_SDCARD not a persona
,07-08 14:02:28.129  6952  6952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:28.139  1016  1477 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6952 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,07-08 14:02:28.139  6952  6952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-08 14:02:28.139  1016  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast,
07-08 14:02:28.139  6952  6952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:28.139  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-08 14:02:28.139  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.139  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.139  1016  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-08 14:02:28.159  6965  6965 E Zygote  : MountEmulatedStorage()
07-08 14:02:28.159  6965  6965 E Zygote  : v2,
07-08 14:02:28.159  6965  6965 I libpersona: KNOX_SDCARD checking this for 1000
07-08 14:02:28.159  6965  6965 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:28.159  1016  1477 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-08 14:02:28.159  1016  1477 I ActivityManager: Killing 6444:com.wsomacp/u0a23 (adj 15): empty #21
07-08 14:02:28.159  1016  1331 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-08 14:02:28.169  6965  6965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-08 14:02:28.169  1016  1331 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:28.169  1016  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-08 14:02:28.169  1016  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-08 14:02:28.169  6965  6965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:28.169  6965  6965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-08 14:02:28.179  1016  3020 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-08 14:02:28.179  6952  6952 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:28.179  6952  6952 D ActivityThread: Added TimaKeyStore provider
,07-08 14:02:28.179  6888  6888 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-08 14:02:28.199  6965  6965 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-08 14:02:28.199  6965  6965 D ActivityThread: Added TimaKeyStore provider
07-08 14:02:28.199  1016  1135 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-08 14:02:28.199  1016  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-08 14:02:28.199  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
07-08 14:02:28.199  1016  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-08 14:02:28.199  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-08 14:02:28.209  6888  6888 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-08 14:02:28.219  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,07-08 14:02:28.219  6888  6888 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
07-08 14:02:28.219  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.219  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.219  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.219  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-08 14:02:28.219  6627  6627 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,07-08 14:02:28.219  6888  6888 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-08 14:02:28.219  6888  6888 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-08 14:02:28.219  6888  6888 D AndroidRuntime: Shutting down VM
,07-08 14:02:28.219  6888  6888 E AndroidRuntime: FATAL EXCEPTION: main
07-08 14:02:28.219  6888  6888 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6888
07-08 14:02:28.219  6888  6888 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-08 14:02:28.219  6888  6888 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-08 14:02:28.229  6985  6985 E Zygote  : MountEmulatedStorage()
07-08 14:02:28.229  6985  6985 I libpersona: KNOX_SDCARD checking this for 10152
07-08 14:02:28.229  6985  6985 E Zygote  : v2
07-08 14:02:28.229  6985  6985 I libpersona: KNOX_SDCARD not a persona
07-08 14:02:28.229  6985  6985 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-08 14:02:28.229  6627  6981 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-08 14:02:28.239  6985  6985 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-08 14:02:28.239  6985  6985 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-08 14:02:28.239  1016  1028 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6985 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/history.db'.
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-08 14:02:28.239  6627  6627 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-08 14:02:28.239  1016  1584 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
07-08 14:02:28.239  6627  6627 D AndroidRuntime: Shutting down VM
07-08 14:02:28.249  6627  6627 E AndroidRuntime: FATAL EXCEPTION: main
07-08 14:02:28.249  6627  6627 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6627
07-08 14:02:28.249  6627  6627 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-08 14:02:28.249  6627  6627 E AndroidRuntime: 	... 9 more
07-08 14:02:28.249  6627  6981 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
07-08 14:02:28.249  6937  6937 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,07-08 14:02:28.249  1016  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
07-08 14:02:28.259  6937  6937 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/seatbelt.db'.
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2237)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
07-08 14:02:28.259  6627  6981 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-08 14:02:28.259  6627  6981 I Process : Sending signal. PID: 6627 SIG: 9

```
