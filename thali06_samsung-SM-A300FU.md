#### Test 630369953a3bebd_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,03-16 11:20:19.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
03-16 11:20:19.610  6267  6267 D AndroidRuntime: 
03-16 11:20:19.610  6267  6267 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 11:20:19.620  6267  6267 D AndroidRuntime: CheckJNI is OFF
03-16 11:20:19.620  6267  6267 D AndroidRuntime: readGMSProperty: start
03-16 11:20:19.620  6267  6267 D AndroidRuntime: readGMSProperty: already setted!!
03-16 11:20:19.620  6267  6267 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 11:20:19.620  6267  6267 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 11:20:19.620  6267  6267 D AndroidRuntime: readGMSProperty: end
03-16 11:20:19.620  6267  6267 D AndroidRuntime: addProductProperty: start
03-16 11:20:19.760  6267  6267 E AffinityControl: AffinityControl: registerfunction enter
03-16 11:20:19.790  6267  6267 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 11:20:19.800  1020  1343 E PersonaManagerService: inState():  stateMachine is null !!
03-16 11:20:19.800  1020  1343 I PersonaManagerService: PersonaId don't exist
03-16 11:20:19.800  1020  1343 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 11:20:19.800  1020  1343 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:20:19.820  1020  1343 W ActivityManager: mDVFSHelper.acquire()
03-16 11:20:19.820  1020  1343 D FocusedStackFrame: Set to : 0
03-16 11:20:19.830  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 11:20:19.830  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 11:20:19.830  1020  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:19.830  1020  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:19.830  1020  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:19.830  1020  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:19.840  6279  6279 E Zygote  : MountEmulatedStorage()
03-16 11:20:19.840  6279  6279 E Zygote  : v2
03-16 11:20:19.840  6279  6279 I libpersona: KNOX_SDCARD checking this for 10167
03-16 11:20:19.840  6279  6279 I libpersona: KNOX_SDCARD not a persona
03-16 11:20:19.840  1020  1343 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6279 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:20:19.840  1020  1343 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 11:20:19.840  1020  1343 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:20:19.840  1020  1343 D InputDispatcher: Focused application set to: xxxx
03-16 11:20:19.840  1020  1343 D InputDispatcher: Focus left window: 1484
03-16 11:20:19.840  6279  6279 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:20:19.840  6267  6267 D AndroidRuntime: Shutting down VM
03-16 11:20:19.850  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 11:20:19.850  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 11:20:19.850   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-16 11:20:19.850  6279  6279 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:20:19.850  6279  6279 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 11:20:19.870  6279  6279 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:20:19.870  6279  6279 D ActivityThread: Added TimaKeyStore provider
03-16 11:20:19.870  1020  1781 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 11:20:19.870  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:20:19.870  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 11:20:19.890  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 11:20:19.900  1020  1781 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:20:19.910  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 11:20:19.930   258  1100 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-16 11:20:19.930   258   430 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-16 11:20:19.940  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{1a33c1bd token=android.os.BinderProxy@298d2b63 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 11:20:19.940  1484  1484 D Launcher: onTrimMemory. Level: 20
03-16 11:20:20.010  6279  6279 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-16 11:20:20.020  6279  6279 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6768-6769)
03-16 11:20:20.020  6279  6279 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:20:20.050  6279  6279 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b655b25}
03-16 11:20:20.050  6279  6279 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 11:20:20.050  6279  6279 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 11:20:20.050  6267  6267 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 11:20:20.080  6279  6279 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 11:20:20.080  6279  6279 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:20:20.080  6279  6279 E SysUtils: ApplicationContext is null in ApplicationStatus
03-16 11:20:20.100  6279  6279 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-16 11:20:20.110  6279  6279 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:20:20.110  6279  6279 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 11:20:20.110  6279  6279 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 11:20:20.110  6279  6279 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 11:20:20.110  6279  6279 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 11:20:20.110  6279  6279 I Adreno-EGL: Local Branch: 
03-16 11:20:20.110  6279  6279 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 11:20:20.110  6279  6279 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 11:20:20.110  6279  6279 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 11:20:20.140  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:20:20.140  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:20:20.140  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:20:20.140  1020  1033 D BatteryService: stay LED for fully charged
03-16 11:20:20.140  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:20:20.140  1020  1020 I MotionRecognitionService: Plugged
03-16 11:20:20.140  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:20:20.150  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:20:20.150  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:20:20.150  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:20:20.150  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 11:20:20.160  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 11:20:20.160  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
03-16 11:20:20.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:20:20.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:20:20.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:20:20.170  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:20:20.170  1177  1177 D SViewCoverView: level :100 plugged : 2
03-16 11:20:20.340  6279  6279 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:20:20.350  6279  6279 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-16 11:20:20.360  6279  6279 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 11:20:20.360  6279  6279 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-16 11:20:20.370  6279  6279 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-16 11:20:20.370  6279  6279 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:20:20.370  6279  6279 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:20:20.400  1020  1045 W ActivityManager: Activity pause timeout for ActivityRecord{14f01cf8 u0 com.test.thalitest/.MainActivity t23}
03-16 11:20:20.470  6279  6321 D OpenGLRenderer: Render dirty regions requested: true
03-16 11:20:20.470  1020  3947 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 11:20:20.470  1020  3947 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 11:20:20.470  1020  3947 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 11:20:20.470  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 11:20:20.470  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 11:20:20.520  6279  6308 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-16 11:20:20.520  6279  6279 V ActivityThread: updateVisibility : ActivityRecord{2970e44d token=android.os.BinderProxy@1e3fef77 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-16 11:20:20.530  6279  6279 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 11:20:20.530  6279  6279 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 11:20:20.540   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
03-16 11:20:20.560  1020  1033 D InputDispatcher: Focus entered window: 6279
03-16 11:20:20.560  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:20:20.560  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 11:20:20.560  6279  6279 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 11:20:20.560  6279  6321 I OpenGLRenderer: Initialized EGL, version 1.4
03-16 11:20:20.560  6279  6321 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 11:20:20.560  6279  6321 D OpenGLRenderer: Enabling debug mode 0
03-16 11:20:20.580  1020  1343 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 11:20:20.590  1177  1177 I StatusBar: Icon Only
03-16 11:20:20.590  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:20:20.590  1020  6323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 11:20:20.600  1020  1050 I ActivityManager: Displayed Component not be shown by security: +703ms (total +1m39s962ms)
03-16 11:20:20.600  1020  1050 W ActivityManager: mDVFSHelper.release()
03-16 11:20:20.600  6279  6279 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 11:20:20.600  6279  6279 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e3fef77 time:217348
03-16 11:20:20.600  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14f01cf8 u0 com.test.thalitest/.MainActivity t23} time:217349
03-16 11:20:20.610   258   430 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
03-16 11:20:20.610   258  1101 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
03-16 11:20:20.630  1879  1879 I SamsungIME: getCurrentCandidateView
03-16 11:20:20.670   289   289 E SMD     : DCD OFF
03-16 11:20:20.690  1879  1879 D SamsungIME: Dismiss ExpandCandiate
03-16 11:20:20.720  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 11:20:20.780  6279  6279 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6279
03-16 11:20:20.790  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 11:20:20.810  1879  1879 I SamsungIME: KeybaordView init() : load resources
03-16 11:20:20.830  1879  1879 I SamsungIME: getCurrentKeyboard
03-16 11:20:20.830  1879  1879 I SamsungIME: getTextKeyboard
03-16 11:20:20.850  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
03-16 11:20:20.920  6279  6279 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 11:20:21.110  6279  6324 D jxcore_app_log: JniHelper::setJavaVM(0xb7d95448), pthread_self() = -1204846432
,03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 11:20:21.120  6279  6324 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@221808b2 added. We now have 1 listener(s)
,03-16 11:20:21.120  6279  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-16 11:20:21.120  6279  6324 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-16 11:20:21.130  6279  6324 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-16 11:20:21.130  6279  6324 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-16 11:20:21.130  6279  6324 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274f05b9 added. We now have 1 listener(s)
,03-16 11:20:21.140  6279  6324 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 11:20:21.140  6279  6324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 11:20:21.140  6279  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 11:20:21.140  6279  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 11:20:21.140  6279  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 11:20:21.140  6279  6324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 11:20:21.150  6279  6324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 11:20:21.150  6279  6324 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 11:20:21.160  6279  6324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 11:20:21.160  6279  6324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 11:20:21.160  6279  6324 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 11:20:21.160  6279  6279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:20:21.170  6279  6279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:20:21.190  6279  6279 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 11:20:21.710  6279  6332 W jxcore-log: Initializing JXcore engine
03-16 11:20:21.710  6279  6332 W jxcore-log: JXcore engine is ready
,03-16 11:20:21.760  1868  1868 E audit   : type=1400 msg=audit(1458123621.760:205): avc:  denied  { ioctl } for  pid=6332 comm="Thread-1070" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-16 11:20:21.760  1868  1868 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 11:20:21.760  1868  1868 E audit   : type=1300 msg=audit(1458123621.760:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9eb058b8 items=0 ppid=306 ppcomm=main pid=6332 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1070" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 11:20:21.760  1868  1868 E audit   : type=1320 msg=audit(1458123621.760:205): 
,03-16 11:20:21.770  6279  6332 W jxcore-log: Starting JXcore engine
,03-16 11:20:21.790  1020  1052 I PowerManagerService: [PWL] Off : 140s ago
,03-16 11:20:21.860  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:20:21.880  6279  6332 W jxcore-log: Platform android
03-16 11:20:21.880  6279  6332 W jxcore-log: 
03-16 11:20:21.880  6279  6332 W jxcore-log: Process ARCH arm
03-16 11:20:21.880  6279  6332 W jxcore-log: 
,03-16 11:20:22.090  6279  6332 I jxcore-log: JXcore Cordova bridge is ready!,
03-16 11:20:22.090  6279  6332 I jxcore-log: 
03-16 11:20:22.090  6279  6332 W jxcore-log: JXcore engine is started
,03-16 11:20:22.090  6279  6324 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 11:20:22.100  6279  6332 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 11:20:22.100  6279  6332 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 11:20:22.110  6279  6279 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-16 11:20:22.110  1020  1503 D FocusedStackFrame: Set to : 0
,03-16 11:20:22.110  1020  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:20:22.110  1020  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 11:20:22.110  1020  1503 D InputDispatcher: Focused application set to: xxxx
,03-16 11:20:22.110  1020  1503 D InputDispatcher: Focus left window: 6279
,03-16 11:20:22.120  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 11:20:22.120  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 11:20:22.120  1020  1503 I ActivityManager: Killing 4213:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-16 11:20:22.130   258  1100 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-16 11:20:22.140   258   430 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-16 11:20:22.140  1020  3410 W ActivityManager: mDVFSHelper.acquire()
,03-16 11:20:22.160  1020  3410 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 11:20:22.160  6279  6279 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@dc8b95f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:20:22.160  6279  6279 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@dc8b95f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 11:20:22.160  6279  6279 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3679fdfe that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:20:22.160  6279  6279 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3679fdfe that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:20:22.160  6279  6279 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 11:20:22.180  1484  1484 D Launcher: onRestart, Launcher: 900580616
,03-16 11:20:22.180  1484  1484 D Launcher: onStart, Launcher: 900580616
,03-16 11:20:22.180  1484  1484 D Launcher.HomeView: onStart
,03-16 11:20:22.180  1484  1484 D Launcher: onResume, Launcher: 900580616
,03-16 11:20:22.180  1020  1343 D SettingsProvider: name = kids_home_mode
,03-16 11:20:22.180  1020  1343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:20:22.180  1020  1343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-16 11:20:22.180  1020  1343 D SettingsProvider: selectionArgs: false
03-16 11:20:22.180  1020  1343 D SettingsProvider: selectionArgs: 10006
,03-16 11:20:22.180  1020  1343 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:20:22.180  1020  1343 D SettingsProvider: ret = -1
03-16 11:20:22.180  1484  1484 D Launcher.HomeView: onResume
,03-16 11:20:22.190  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 11:20:22.190  1484  1484 D MenuAppsGridFragment: onResume
,03-16 11:20:22.190  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.190  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.190  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,03-16 11:20:22.200  1020  1339 D ActivityManager: handle home activity for 0
,03-16 11:20:22.200  1020  1339 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 11:20:22.200  1020  1339 D KnoxTimeoutHandler: post home show event for user 0
03-16 11:20:22.200  1020  1339 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 11:20:22.200  1020  1339 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 11:20:22.200  1020  1339 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 11:20:22.200  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 11:20:22.200  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 11:20:22.200  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 11:20:22.200  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 11:20:22.200  1484  1484 D Launcher.HomeView: onPause
03-16 11:20:22.200  1020  1483 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-16 11:20:22.200  1020  1483 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
03-16 11:20:22.200  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 11:20:22.200  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.200  1020  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.200  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
03-16 11:20:22.210  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.210  5016  5016 D GalleryCacheReady: Receive : home resume
03-16 11:20:22.210  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.210  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-16 11:20:22.210  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:20:22.210  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 11:20:22.210  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-16 11:20:22.220  2533  2533 D Recents_RecreateReceiver: onReceive by home
,03-16 11:20:22.220  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:20:22.220  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.220  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 11:20:22.230  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:20:22.230  1020  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.230  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-16 11:20:22.230  5679  5679 D Mms/UIEventReceiver: ui event
,03-16 11:20:22.240   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-16 11:20:22.240  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.240  1020  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.240  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-16 11:20:22.240  1020  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4213/cgroup.procs: No such file or directory
03-16 11:20:22.240  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:22.240  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:22.240  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:20:22.240  1020  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:20:22.240  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 11:20:22.250  1020  1339 D InputDispatcher: Focus entered window: 1484
,03-16 11:20:22.250  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:20:22.250  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 11:20:22.250  6060  6060 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
03-16 11:20:22.250  1484  1484 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 11:20:22.260  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 11:20:22.260  6336  6336 E Zygote  : MountEmulatedStorage()
,03-16 11:20:22.260  6336  6336 I libpersona: KNOX_SDCARD checking this for 10135
03-16 11:20:22.260  6336  6336 E Zygote  : v2
03-16 11:20:22.260  6336  6336 I libpersona: KNOX_SDCARD not a persona
03-16 11:20:22.260  6336  6336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:20:22.260  1020  1483 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6336 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-16 11:20:22.270  6336  6336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 11:20:22.270  6336  6336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:20:22.270  1484  1484 D Launcher.HomeView: onStop
03-16 11:20:22.270  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{1a33c1bd token=android.os.BinderProxy@298d2b63 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
,03-16 11:20:22.270  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.270  1020  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.270  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 11:20:22.270  1020  1483 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,03-16 11:20:22.280  1020  1669 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 11:20:22.280  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.280  1020  6344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 11:20:22.280  1020  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.280  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-16 11:20:22.290  1177  1177 I StatusBar: Icon Only
03-16 11:20:22.290  1177  1177 D PanelView: There is/are notification(s) 
,03-16 11:20:22.290  1879  1879 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-16 11:20:22.300   306   306 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 33.718ms
,03-16 11:20:22.310  6279  6279 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 11:20:22.310  6336  6336 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-16 11:20:22.310  6336  6336 D ActivityThread: Added TimaKeyStore provider
,03-16 11:20:22.310  1484  1484 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@298d2b63 time:219057
,03-16 11:20:22.310   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.833ms
,03-16 11:20:22.330  6336  6336 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 11:20:22.330  6336  6336 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 11:20:22.330  6336  6336 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 11:20:22.330  6336  6336 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 11:20:22.330  6336  6336 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:20:22.330   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.699ms
,03-16 11:20:22.340  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e8d7420 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:219080
03-16 11:20:22.340  1020  1050 W ActivityManager: mDVFSHelper.release()
,03-16 11:20:22.360  1020  3946 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 11:20:22.360  1020  3946 I ActivityManager: Killing 5691:com.samsung.helphub/1000 (adj 15): empty #31
,03-16 11:20:22.360  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:20:22.360  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:20:22.360  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 11:20:22.370  6060  6060 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-16 11:20:22.430  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 11:20:22.430  1020  1033 D PersonaManager: isKioskContainerExistOnDevice,
,03-16 11:20:22.470  1020  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_5691/cgroup.procs: No such file or directory
,03-16 11:20:23.670   289   289 E SMD     : DCD OFF,
,03-16 11:20:26.670   289   289 E SMD     : DCD OFF,
03-16 11:20:26.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:27.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:28.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:29.680   289   289 E SMD     : DCD OFF
,03-16 11:20:29.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:29.860  1020  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-16 11:20:30.210  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:20:30.210  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:20:30.210  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:20:30.210  1020  1343 D BatteryService: stay LED for fully charged
,03-16 11:20:30.210  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:20:30.220  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:20:30.220  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:20:30.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:20:30.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:20:30.220  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:20:30.220  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:20:30.240  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:20:30.240  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:20:30.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:20:30.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:20:30.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:20:30.240  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:20:30.250  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:20:30.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:31.500  1020  1317 E Watchdog: !@Sync 7
,03-16 11:20:31.680   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 11:20:31.870  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:20:32.680   289   289 E SMD     : DCD OFF
,03-16 11:20:35.690   289   289 E SMD     : DCD OFF
,03-16 11:20:36.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:37.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:38.680   289   289 E SMD     : DCD OFF,
03-16 11:20:38.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:39.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:20:39.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:40.270  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:20:40.270  1020  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:20:40.270  1020  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:20:40.270  1020  1483 D BatteryService: stay LED for fully charged
,03-16 11:20:40.270  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:20:40.270  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:20:40.270  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:20:40.280  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:20:40.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:20:40.280  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:20:40.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:20:40.290  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:20:40.290  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:20:40.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:20:40.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:20:40.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:20:40.300  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:20:40.310  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:20:40.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:41.680   289   289 E SMD     : DCD OFF
03-16 11:20:41.680   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-16 11:20:41.890  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:20:44.680   289   289 E SMD     : DCD OFF
,03-16 11:20:47.690   289   289 E SMD     : DCD OFF,
,03-16 11:20:50.330  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:20:50.690   289   289 E SMD     : DCD OFF
,03-16 11:20:51.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:51.910  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:20:52.680   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:53.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:53.690   289   289 E SMD     : DCD OFF
,03-16 11:20:54.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:20:55.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:20:56.690   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 11:20:56.690   289   289 E SMD     : DCD OFF
,03-16 11:20:59.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:20:59.690   289   289 E SMD     : DCD OFF
,03-16 11:21:00.400  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:21:00.400  1020  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:21:00.400  1020  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:21:00.400  1020  3410 D BatteryService: stay LED for fully charged
03-16 11:21:00.400  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:21:00.400  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:21:00.400  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:21:00.400  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:21:00.410  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:21:00.410  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:21:00.410  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:21:00.420  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:21:00.420  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:21:00.430  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:00.430  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:00.430  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:00.430  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:21:00.430  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:21:01.510  1020  1317 E Watchdog: !@Sync 8
,03-16 11:21:01.800  1020  1052 I PowerManagerService: [PWL] Off : 180s ago
,03-16 11:21:01.930  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:02.690   289   289 E SMD     : DCD OFF
,03-16 11:21:05.690   289   289 E SMD     : DCD OFF
,03-16 11:21:08.700   289   289 E SMD     : DCD OFF
,03-16 11:21:10.460  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:21:11.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:11.700   289   289 E SMD     : DCD OFF
,03-16 11:21:11.940  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:12.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:13.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:14.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:14.700   289   289 E SMD     : DCD OFF,
,03-16 11:21:15.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:16.690   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-16 11:21:17.700   289   289 E SMD     : DCD OFF
,03-16 11:21:19.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:21:20.520  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:21:20.520  1020  1781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:21:20.520  1020  1781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:21:20.520  1020  1781 D BatteryService: stay LED for fully charged
,03-16 11:21:20.520  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:21:20.530  1020  1020 I MotionRecognitionService: Plugged
03-16 11:21:20.530  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:21:20.530  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:21:20.530  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:21:20.530  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:21:20.530  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:21:20.540  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:21:20.540  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:21:20.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:20.560  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:20.560  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:20.560  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:21:20.560  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:21:20.700   289   289 E SMD     : DCD OFF
,03-16 11:21:21.970  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:23.700   289   289 E SMD     : DCD OFF
,03-16 11:21:26.710   289   289 E SMD     : DCD OFF
,03-16 11:21:27.950  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:21:27.960  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-16 11:21:27.960  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:21:27.970  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 11:21:27.970  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
03-16 11:21:27.980  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 11:21:27.980  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 11:21:27.980  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 11:21:28.020  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:21:28.020  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:21:28.020  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:21:28.030  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 11:21:28.050  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:21:28.180  6087  6382 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 11:21:28.200  6087  6383 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 11:21:28.200  1020  3681 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:21:28.200  1020  3681 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:21:28.200  1020  3681 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.220  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:21:28.220  1020  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:21:28.220  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.240  1686  1793 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 11:21:28.240  1686  1793 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 11:21:28.240  1686  1793 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-16 11:21:28.240  1686  1793 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:21:28.250  1686  1793 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:21:28.250  1020  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:21:28.250  1020  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 11:21:28.250  1020  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.280  1020  3410 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 11:21:28.280  1020  3410 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 11:21:28.290  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-16 11:21:28.290  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 11:21:28.300  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:21:28.300  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:21:28.300  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:21:28.300  1177  1177 I StatusBar: Icon Only
03-16 11:21:28.300  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:21:28.300  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:21:28.300  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:21:28.300  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:21:28.300  1177  1177 I StatusBar: Icon Only
03-16 11:21:28.300  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:21:28.300  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:21:28.300  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:21:28.300  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:21:28.300  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.310  1020  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:21:28.310  1020  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:21:28.310  1020  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.330  1686  1701 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-16 11:21:28.330  1686  1701 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-16 11:21:28.330  1686  1701 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 11:21:28.330  1686  1701 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:21:28.340  1686  1701 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:21:28.340  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:21:28.340  1020  1669 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:21:28.340  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:21:28.350  6087  6383 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 11:21:28.350  6087  6382 E BooksSync: Soft error
03-16 11:21:28.350  6087  6382 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:21:28.350  6087  6382 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:21:28.350  6087  6382 E BooksSync: Sync error
03-16 11:21:28.350  6087  6382 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:21:28.350  6087  6382 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:21:28.350  6087  6382 I BooksSync: Finished books sync
,03-16 11:21:28.360  1020  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284698, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 11:21:28.370  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 11:21:28.410  1020  1503 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 11:21:28.410  1020  1503 D SecContentProvider2: mCursor = null
,03-16 11:21:29.710   289   289 E SMD     : DCD OFF
,03-16 11:21:30.590  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:21:30.590  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:21:30.590  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:21:30.590  1020  1790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:21:30.590  1020  1790 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:21:30.590  1020  1790 D BatteryService: stay LED for fully charged
03-16 11:21:30.590  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:21:30.590  1020  1020 I MotionRecognitionService: Plugged
03-16 11:21:30.590  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:21:30.590  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:21:30.590  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:21:30.600  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:21:30.600  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:21:30.610  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:30.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:30.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:30.620  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:21:30.620  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:21:31.500  1020  1317 E Watchdog: !@Sync 9
,03-16 11:21:31.990  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:32.710   289   289 E SMD     : DCD OFF
,03-16 11:21:35.710   289   289 E SMD     : DCD OFF
,03-16 11:21:36.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:37.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:38.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:38.710   289   289 E SMD     : DCD OFF
,03-16 11:21:39.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:21:39.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:40.640  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:21:40.640  1020  1503 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:21:40.640  1020  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:21:40.640  1020  1503 D BatteryService: stay LED for fully charged
03-16 11:21:40.640  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:21:40.650  1020  1020 I MotionRecognitionService: Plugged
03-16 11:21:40.650  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:21:40.650  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:21:40.650  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:21:40.650  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:21:40.650  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-16 11:21:40.660  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:21:40.660  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:21:40.670  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:40.670  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:40.670  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:40.670  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:21:40.670  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:21:40.690   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:21:41.690   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-16 11:21:41.710   289   289 E SMD     : DCD OFF
,03-16 11:21:42.000  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:44.710   289   289 E SMD     : DCD OFF
,03-16 11:21:46.800  1020  1052 I PowerManagerService: [PWL] Off : 225s ago
,03-16 11:21:47.720   289   289 E SMD     : DCD OFF
,03-16 11:21:50.710  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:21:50.710  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:21:50.710  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:21:50.710  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:21:50.710  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-16 11:21:50.710  1020  1020 I MotionRecognitionService: Plugged
03-16 11:21:50.710  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false,
,03-16 11:21:50.710  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:21:50.720  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:21:50.720   289   289 E SMD     : DCD OFF
,03-16 11:21:50.720  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:21:50.720  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:21:50.730  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:21:50.730  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:21:50.740  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:50.740  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:21:50.740  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:21:50.740  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:21:50.740  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:21:52.020  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:21:53.720   289   289 E SMD     : DCD OFF
,03-16 11:21:56.720   289   289 E SMD     : DCD OFF
,03-16 11:21:58.180  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:21:58.560  1020  1089 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 11:21:58.570  1020  1089 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-16 11:21:58.570  1020  1088 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 11:21:58.570  1020  1089 I TLC_TIMA_PKM_initialize: initializing...
,03-16 11:21:58.570  1020  1089 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-16 11:21:58.570  1020  1089 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,03-16 11:21:58.580  1020  1089 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-16 11:21:58.580  1020  1089 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
03-16 11:21:58.580  1020  1089 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
03-16 11:21:58.580  1020  1089 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,03-16 11:21:58.580  1020  1089 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,03-16 11:21:58.580  1020  1089 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
03-16 11:21:58.580  1020  1089 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 11:21:58.600  1020  1089 D QSEECOMAPI: : Loaded image: APP id = 11
,03-16 11:21:58.610  1020  1089 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,03-16 11:21:58.620  1020  1089 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-16 11:21:59.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:21:59.720   289   289 E SMD     : DCD OFF
,03-16 11:21:59.990  1020  1098 V AlarmManager: waitForAlarm result :8
,03-16 11:22:00.570  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 11:22:00.570  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 11:22:00.580  1020  1089 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:22:00.580  1020  1089 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:22:00.770  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:22:01.500  1020  1317 E Watchdog: !@Sync 10
,03-16 11:22:02.040  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:02.720   289   289 E SMD     : DCD OFF
,03-16 11:22:05.720   289   289 E SMD     : DCD OFF
,03-16 11:22:06.700   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-16 11:22:06.700   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 11:22:08.730   289   289 E SMD     : DCD OFF
,03-16 11:22:10.840  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:22:10.840  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:22:10.840  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:22:10.840  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:22:10.840  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:22:10.850  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:22:10.850  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:22:10.850  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:22:10.850  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:22:10.850  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:22:10.850  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:22:10.860  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:22:10.860  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:22:10.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:22:10.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:10.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:10.880  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:22:10.880  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:22:11.730   289   289 E SMD     : DCD OFF
,03-16 11:22:12.060  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:14.730   289   289 E SMD     : DCD OFF
,03-16 11:22:17.730   289   289 E SMD     : DCD OFF
,03-16 11:22:19.350  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:22:20.730   289   289 E SMD     : DCD OFF
,03-16 11:22:20.910  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:22:21.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:22.070  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:22.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:23.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:23.730   289   289 E SMD     : DCD OFF
,03-16 11:22:24.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:25.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:26.700   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 11:22:26.730   289   289 E SMD     : DCD OFF
,03-16 11:22:29.740   289   289 E SMD     : DCD OFF
,03-16 11:22:30.970  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:22:30.970  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:22:30.970  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:22:30.970  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:22:30.970  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:22:30.970  1020  1020 I MotionRecognitionService: Plugged
03-16 11:22:30.970  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:22:30.980  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:22:30.980  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:22:30.980  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,03-16 11:22:30.980  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:22:30.990  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 11:22:30.990  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:22:31.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 11:22:31.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:31.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:31.000  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:22:31.000  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:22:31.500  1020  1317 E Watchdog: !@Sync 11
,03-16 11:22:31.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:22:32.090  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:32.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:32.740   289   289 E SMD     : DCD OFF
,03-16 11:22:33.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:34.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:35.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:22:35.740   289   289 E SMD     : DCD OFF,
,03-16 11:22:36.700   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-16 11:22:36.800  1020  1052 I PowerManagerService: [PWL] Off : 275s ago
,03-16 11:22:38.740   289   289 E SMD     : DCD OFF
,03-16 11:22:39.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:22:39.770  1686  1686 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:22:39.780  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:22:39.780  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:22:39.780  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:22:39.790  1020  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:22:39.790  1020  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:22:39.790  1020  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:22:39.810  1686  1793 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-16 11:22:39.820  1686  1793 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-16 11:22:39.820  1686  1793 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 11:22:39.820  1686  1793 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:22:39.820  1686  1793 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:22:39.830  1020  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:22:39.830  1020  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:22:39.830  1020  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:22:39.860  1020  1345 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 11:22:39.860  1020  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 11:22:39.860  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 11:22:39.860  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 11:22:39.870  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:22:39.870  1686  1793 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-16 11:22:39.870  1686  1793 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:461)
03-16 11:22:39.870  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:22:39.870  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:22:39.870  1177  1177 I StatusBar: Icon Only
03-16 11:22:39.870  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:22:39.870  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:22:39.870  1177  1177 D PersonaManager: isKioskContainerExistOnDevice,
03-16 11:22:39.870  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:22:39.870  1177  1177 I StatusBar: Icon Only
03-16 11:22:39.870  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:22:39.870  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:22:39.880  5410  5445 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-16 11:22:39.880  5410  5445 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-16 11:22:39.880  5410  5445 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
03-16 11:22:39.880  5410  5445 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-16 11:22:39.880  5410  5445 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
03-16 11:22:39.880  5410  5445 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-16 11:22:39.880  5410  5445 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:461)
,03-16 11:22:39.900  5410  5445 W System  : Ignoring header User-Agent because its value was null.
,03-16 11:22:39.910  5410  5445 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-16 11:22:39.910  5410  5445 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-16 11:22:39.910  5410  5445 I System.out: (HTTPLog)-Static: isShipBuild true
,03-16 11:22:39.910  5410  5445 I System.out: (HTTPLog)-Thread-913-430822553: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 11:22:39.910  5410  5445 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-16 11:22:39.910   279  1014 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 11:22:39.910   279  1014 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,03-16 11:22:39.920  5410  5445 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-16 11:22:39.940  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 11:22:41.040  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:22:41.040  1020  1781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:22:41.040  1020  1781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:22:41.040  1020  1781 D BatteryService: stay LED for fully charged
03-16 11:22:41.040  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:22:41.040  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:22:41.040  1020  1020 I MotionRecognitionService: Plugged
03-16 11:22:41.040  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 11:22:41.040  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:22:41.050  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:22:41.050  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:22:41.060  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:22:41.060  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:22:41.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:22:41.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:41.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:22:41.070  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:22:41.070  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:22:41.740   289   289 E SMD     : DCD OFF
,03-16 11:22:42.110  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:44.740   289   289 E SMD     : DCD OFF
,03-16 11:22:46.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:22:47.700   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:47.750   289   289 E SMD     : DCD OFF
,03-16 11:22:48.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:49.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:50.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:22:50.750   289   289 E SMD     : DCD OFF,
,03-16 11:22:51.100  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:22:51.100  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:22:51.100  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:22:51.100  1020  1033 D BatteryService: stay LED for fully charged
03-16 11:22:51.100  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:22:51.100  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:22:51.100  1020  1020 I MotionRecognitionService: Plugged
03-16 11:22:51.100  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:22:51.100  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:22:51.110  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:22:51.110  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:22:51.120  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:22:51.120  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:22:51.130  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:22:51.130  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:22:51.130  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:22:51.130  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:22:51.130  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:22:51.710   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 11:22:52.130  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:22:53.750   289   289 E SMD     : DCD OFF
,03-16 11:22:56.750   289   289 E SMD     : DCD OFF,
,03-16 11:22:59.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:22:59.750   289   289 E SMD     : DCD OFF
,03-16 11:23:01.160  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:23:01.160  1020  1032 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:23:01.160  1020  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:23:01.160  1020  1032 D BatteryService: stay LED for fully charged
03-16 11:23:01.160  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:23:01.160  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:23:01.160  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:23:01.170  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:23:01.170  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:23:01.170  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:23:01.170  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:23:01.180  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:23:01.180  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:23:01.190  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:23:01.190  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:23:01.190  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:23:01.190  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:23:01.190  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:23:01.510  1020  1317 E Watchdog: !@Sync 12
,03-16 11:23:02.140  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:02.750   289   289 E SMD     : DCD OFF
,03-16 11:23:05.750   289   289 E SMD     : DCD OFF
,03-16 11:23:06.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:23:07.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:23:08.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:08.760   289   289 E SMD     : DCD OFF
,03-16 11:23:09.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:10.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:11.220  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:23:11.710   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-16 11:23:11.760   289   289 E SMD     : DCD OFF
,03-16 11:23:12.160  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:14.760   289   289 E SMD     : DCD OFF
,03-16 11:23:17.760   289   289 E SMD     : DCD OFF
,03-16 11:23:19.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:23:20.760   289   289 E SMD     : DCD OFF
,03-16 11:23:21.280  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:23:22.180  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:23.760   289   289 E SMD     : DCD OFF
,03-16 11:23:26.770   289   289 E SMD     : DCD OFF
,03-16 11:23:29.770   289   289 E SMD     : DCD OFF
,03-16 11:23:31.350  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:23:31.510  1020  1317 E Watchdog: !@Sync 13,
,03-16 11:23:31.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:31.810  1020  1052 I PowerManagerService: [PWL] Off : 330s ago
,03-16 11:23:32.190  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:32.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:32.770   289   289 E SMD     : DCD OFF
,03-16 11:23:33.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:23:34.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:23:35.710   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:23:35.780   289   289 E SMD     : DCD OFF
,03-16 11:23:36.720   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-16 11:23:38.780   289   289 E SMD     : DCD OFF
,03-16 11:23:39.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:23:41.410  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:23:41.770   289   289 E SMD     : DCD OFF
,03-16 11:23:42.200  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:44.770   289   289 E SMD     : DCD OFF
,03-16 11:23:47.780   289   289 E SMD     : DCD OFF
,03-16 11:23:50.780   289   289 E SMD     : DCD OFF
,03-16 11:23:51.480  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:23:52.220  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:23:53.780   289   289 E SMD     : DCD OFF
,03-16 11:23:56.780   289   289 E SMD     : DCD OFF
,03-16 11:23:59.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:23:59.780   289   289 E SMD     : DCD OFF
,03-16 11:24:01.510  1020  1317 E Watchdog: !@Sync 14
,03-16 11:24:01.540  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:01.550  1020  1345 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:24:01.550  1020  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:24:01.550  1020  1345 D BatteryService: stay LED for fully charged
03-16 11:24:01.550  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:24:01.550  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:24:01.550  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:24:01.550  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:24:01.550  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:24:01.550  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:24:01.550  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:24:01.560  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:24:01.560  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:24:01.570  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:24:01.580  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:24:01.580  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:24:01.580  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:24:01.580  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:24:01.720   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-16 11:24:01.720   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 11:24:02.240  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:02.780   289   289 E SMD     : DCD OFF
,03-16 11:24:05.790   289   289 E SMD     : DCD OFF,
,03-16 11:24:08.790   289   289 E SMD     : DCD OFF
,03-16 11:24:11.610  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:11.610  1020  3946 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-16 11:24:11.610  1020  3946 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:24:11.610  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:24:11.610  1020  3946 D BatteryService: stay LED for fully charged
,03-16 11:24:11.610  1020  1020 I MotionRecognitionService: Plugged
03-16 11:24:11.610  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:24:11.620  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:24:11.620  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:24:11.620  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:24:11.620  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:24:11.630  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:24:11.630  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:24:11.650  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:24:11.650  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:24:11.650  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:24:11.650  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 11:24:11.650  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:24:11.790   289   289 E SMD     : DCD OFF
,03-16 11:24:12.260  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:14.790   289   289 E SMD     : DCD OFF
,03-16 11:24:17.790   289   289 E SMD     : DCD OFF
,03-16 11:24:19.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:24:20.790   289   289 E SMD     : DCD OFF
,03-16 11:24:21.670  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:21.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:22.270  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:22.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:23.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:23.790   289   289 E SMD     : DCD OFF
,03-16 11:24:24.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:25.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:26.720   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-16 11:24:26.800   289   289 E SMD     : DCD OFF
,03-16 11:24:29.800   289   289 E SMD     : DCD OFF
,03-16 11:24:31.510  1020  1317 E Watchdog: !@Sync 15
,03-16 11:24:31.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:31.740  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:31.820  1020  1052 I PowerManagerService: [PWL] Off : 390s ago
,03-16 11:24:32.290  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:32.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:32.800   289   289 E SMD     : DCD OFF
,03-16 11:24:33.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:34.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:35.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:35.800   289   289 E SMD     : DCD OFF
,03-16 11:24:36.720   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-16 11:24:38.800   289   289 E SMD     : DCD OFF
,03-16 11:24:39.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:24:41.800  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:41.800   289   289 E SMD     : DCD OFF,
,03-16 11:24:42.310  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:44.800   289   289 E SMD     : DCD OFF
,03-16 11:24:46.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:47.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:47.810   289   289 E SMD     : DCD OFF
,03-16 11:24:48.720   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:49.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:24:49.740   312   312 I bootchecker: bootchecker wake up!!
,03-16 11:24:50.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:24:50.810   289   289 E SMD     : DCD OFF
,03-16 11:24:51.730   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 11:24:51.860  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:24:52.330  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:24:53.810   289   289 E SMD     : DCD OFF
,03-16 11:24:56.810   289   289 E SMD     : DCD OFF
,03-16 11:24:59.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:24:59.810   289   289 E SMD     : DCD OFF
,03-16 11:24:59.990  1020  1098 V AlarmManager: waitForAlarm result :8,
03-16 11:24:59.990  1020  1098 V AlarmManager: No more alarm at this time.nowELAPSED=496733 batch.start=543559
,03-16 11:25:01.520  1020  1317 E Watchdog: !@Sync 16
,03-16 11:25:01.920  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:02.340  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:02.810   289   289 E SMD     : DCD OFF
,03-16 11:25:05.810   289   289 E SMD     : DCD OFF
,03-16 11:25:06.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:07.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:08.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:08.820   289   289 E SMD     : DCD OFF
,03-16 11:25:09.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:10.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:11.730   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-16 11:25:11.820   289   289 E SMD     : DCD OFF
,03-16 11:25:11.980  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:12.360  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:14.830   289   289 E SMD     : DCD OFF
,03-16 11:25:17.820   289   289 E SMD     : DCD OFF
,03-16 11:25:19.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-16 11:25:20.820   289   289 E SMD     : DCD OFF
,03-16 11:25:22.040  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:22.370  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:23.830   289   289 E SMD     : DCD OFF
,03-16 11:25:26.830   289   289 E SMD     : DCD OFF
,03-16 11:25:29.840   289   289 E SMD     : DCD OFF
,03-16 11:25:31.510  1020  1317 E Watchdog: !@Sync 17
,03-16 11:25:31.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:32.100  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:32.390  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:32.740   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:32.830   289   289 E SMD     : DCD OFF
,03-16 11:25:33.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 11:25:34.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:25:35.730   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:25:35.830   289   289 E SMD     : DCD OFF
,03-16 11:25:36.730   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-16 11:25:36.870  1020  1052 I PowerManagerService: [PWL] Off : 455s ago,
,03-16 11:25:38.830   289   289 E SMD     : DCD OFF,
,03-16 11:25:39.360  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:25:41.830   289   289 E SMD     : DCD OFF
,03-16 11:25:42.160  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:42.430  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:44.840   289   289 E SMD     : DCD OFF
,03-16 11:25:46.810  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:25:46.820  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 11:25:46.820  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:25:46.830  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 11:25:46.830  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 11:25:46.840  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:25:46.840  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 11:25:46.840  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 11:25:46.870  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:25:46.880  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:25:46.880  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:25:46.900  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 11:25:46.910  6087  6493 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 11:25:46.920  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:25:46.940  6087  6494 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 11:25:46.940  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:25:46.940  1020  1669 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:46.940  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:25:46.950  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:46.950  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:46.950  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:46.970  1686  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 11:25:46.970  1686  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 11:25:46.970  1686  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-16 11:25:46.970  1686  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:25:46.980  1686  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:25:46.980  1020  1343 W ActivityManager: userId = 0, bbcId = -10000,
03-16 11:25:46.980  1020  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:46.980  1020  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.000  1020  1790 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 11:25:47.000  1020  1790 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 11:25:47.000  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 11:25:47.000  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 11:25:47.010  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:25:47.010  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:25:47.010  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:25:47.010  1177  1177 I StatusBar: Icon Only
03-16 11:25:47.010  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:25:47.010  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:25:47.010  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:25:47.010  1177  1177 I PhoneStatusBar: Icon Only
,03-16 11:25:47.010  1177  1177 I StatusBar: Icon Only
03-16 11:25:47.010  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:25:47.010  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:25:47.010  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:47.010  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:47.010  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.030  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:47.030  1020  1669 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:47.030  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.040  1686  4012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 11:25:47.040  1686  4012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 11:25:47.040  1686  4012 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 11:25:47.040  1686  4012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:25:47.050  1686  4012 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:25:47.050  1020  1790 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:47.050  1020  1790 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:47.050  1020  1790 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.080  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 11:25:47.080  1020  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:47.080  1020  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:47.080  1020  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.090  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:25:47.090  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:25:47.090  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:25:47.100  6087  6494 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 11:25:47.100  6087  6493 E BooksSync: Soft error
03-16 11:25:47.100  6087  6493 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:25:47.100  6087  6493 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:25:47.100  6087  6493 E BooksSync: Sync error
03-16 11:25:47.100  6087  6493 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:25:47.100  6087  6493 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:25:47.100  6087  6493 I BooksSync: Finished books sync
,03-16 11:25:47.100  1020  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 543559, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 11:25:47.160  1020  3946 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 11:25:47.160  1020  3946 D SecContentProvider2: mCursor = null
,03-16 11:25:47.620  1686  1686 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-16 11:25:47.840   289   289 E SMD     : DCD OFF
,03-16 11:25:50.840   289   289 E SMD     : DCD OFF
,03-16 11:25:52.230  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:25:52.470  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:25:53.840   289   289 E SMD     : DCD OFF
,03-16 11:25:56.840   289   289 E SMD     : DCD OFF
,03-16 11:25:59.370  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:25:59.840   289   289 E SMD     : DCD OFF,
,03-16 11:25:59.990  1020  1098 V AlarmManager: waitForAlarm result :8,
,03-16 11:26:01.510  1020  1317 E Watchdog: !@Sync 18
,03-16 11:26:01.730   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-16 11:26:01.730   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 11:26:02.290  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:26:02.510  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:02.840   289   289 E SMD     : DCD OFF
,03-16 11:26:05.850   289   289 E SMD     : DCD OFF
,03-16 11:26:08.850   289   289 E SMD     : DCD OFF
,03-16 11:26:11.860   289   289 E SMD     : DCD OFF
,03-16 11:26:12.360  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:26:12.530  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:14.850   289   289 E SMD     : DCD OFF,
,03-16 11:26:16.900  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:26:16.900  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 11:26:16.900  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:26:16.910  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-16 11:26:16.910  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 11:26:16.920  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:26:16.920  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 11:26:16.920  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 11:26:16.940  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:26:16.940  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:26:16.960  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:26:16.970  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 11:26:16.990  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:26:17.860   289   289 E SMD     : DCD OFF
,03-16 11:26:19.370  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:26:20.850   289   289 E SMD     : DCD OFF
,03-16 11:26:22.420  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:26:22.570  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:23.860   289   289 E SMD     : DCD OFF
,03-16 11:26:26.740   316   316 I Atfwd_Daemon: Stop the daemon....,
,03-16 11:26:26.860   289   289 E SMD     : DCD OFF,
,03-16 11:26:29.860   289   289 E SMD     : DCD OFF,
,03-16 11:26:31.520  1020  1317 E Watchdog: !@Sync 19
,03-16 11:26:32.490  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:26:32.620  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:32.870   289   289 E SMD     : DCD OFF,
,03-16 11:26:35.860   289   289 E SMD     : DCD OFF
,03-16 11:26:38.870   289   289 E SMD     : DCD OFF
,03-16 11:26:39.370  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:26:41.860   289   289 E SMD     : DCD OFF
,03-16 11:26:42.550  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:26:42.630  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:44.870   289   289 E SMD     : DCD OFF,
,03-16 11:26:46.900  1020  1052 I PowerManagerService: [PWL] Off : 525s ago,
,03-16 11:26:47.880   289   289 E SMD     : DCD OFF
,03-16 11:26:50.870   289   289 E SMD     : DCD OFF
,03-16 11:26:52.610  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:26:52.650  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:26:53.870   289   289 E SMD     : DCD OFF
,03-16 11:26:56.880   289   289 E SMD     : DCD OFF
,03-16 11:26:58.560  1020  1089 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 11:26:58.570  1020  1088 D TimaService: TimaServiceHandler.handleMessage what =1
03-16 11:26:58.570  1020  1089 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-16 11:26:59.370  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:26:59.410  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 11:26:59.410  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 11:26:59.410  1020  1089 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:26:59.410  1020  1089 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:26:59.870   289   289 E SMD     : DCD OFF
,03-16 11:26:59.990  1020  1098 V AlarmManager: waitForAlarm result :8
,03-16 11:27:01.510  1020  1317 E Watchdog: !@Sync 20
,03-16 11:27:02.680  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:27:02.690  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:27:02.880   289   289 E SMD     : DCD OFF,
,03-16 11:27:05.880   289   289 E SMD     : DCD OFF
,03-16 11:27:08.880   289   289 E SMD     : DCD OFF
,03-16 11:27:11.880   289   289 E SMD     : DCD OFF,
,03-16 11:27:12.700  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:27:12.750  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:27:14.880   289   289 E SMD     : DCD OFF
,03-16 11:27:17.880   289   289 E SMD     : DCD OFF
,03-16 11:27:19.370  1020  2791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-16 11:27:20.880   289   289 E SMD     : DCD OFF,
,03-16 11:27:22.750  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:27:22.810  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:27:23.890   289   289 E SMD     : DCD OFF
,03-16 11:27:26.890   289   289 E SMD     : DCD OFF
,03-16 11:27:29.890   289   289 E SMD     : DCD OFF,
,03-16 11:27:31.510  1020  1317 E Watchdog: !@Sync 21
,03-16 11:27:32.790  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:27:32.870  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:27:32.900   289   289 E SMD     : DCD OFF
,03-16 11:27:35.890   289   289 E SMD     : DCD OFF,
,03-16 11:27:38.890   289   289 E SMD     : DCD OFF
,03-16 11:27:41.890   289   289 E SMD     : DCD OFF
,03-16 11:27:42.800  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:27:42.930  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:27:42.940  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:27:42.940  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 11:27:42.940  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:27:42.940  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:27:42.940  1020  1020 I MotionRecognitionService: Plugged
03-16 11:27:42.940  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:27:42.940  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:27:42.940  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:27:42.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:27:42.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:27:42.960  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 11:27:42.960  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:27:42.970  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 11:27:42.970  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:27:42.970  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:27:42.970  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:27:42.970  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:27:44.900   289   289 E SMD     : DCD OFF,
,03-16 11:27:47.900   289   289 E SMD     : DCD OFF
,03-16 11:27:50.900   289   289 E SMD     : DCD OFF
,03-16 11:27:52.820  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:27:53.000  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:27:53.900   289   289 E SMD     : DCD OFF
,03-16 11:27:56.910   289   289 E SMD     : DCD OFF
,03-16 11:27:59.900   289   289 E SMD     : DCD OFF,
,03-16 11:28:01.510  1020  1317 E Watchdog: !@Sync 22
,03-16 11:28:01.920  1020  1052 I PowerManagerService: [PWL] Off : 600s ago
,03-16 11:28:02.860  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:02.910   289   289 E SMD     : DCD OFF
,03-16 11:28:03.060  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:28:05.910   289   289 E SMD     : DCD OFF
,03-16 11:28:08.910   289   289 E SMD     : DCD OFF
,03-16 11:28:11.910   289   289 E SMD     : DCD OFF
,03-16 11:28:12.910  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:13.120  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:28:14.910   289   289 E SMD     : DCD OFF
,03-16 11:28:17.910   289   289 E SMD     : DCD OFF
,03-16 11:28:20.920   289   289 E SMD     : DCD OFF
,03-16 11:28:22.950  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:23.190  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:28:23.920   289   289 E SMD     : DCD OFF
,03-16 11:28:26.920   289   289 E SMD     : DCD OFF
,03-16 11:28:29.930   289   289 E SMD     : DCD OFF
,03-16 11:28:31.510  1020  1317 E Watchdog: !@Sync 23
,03-16 11:28:32.920   289   289 E SMD     : DCD OFF
,03-16 11:28:32.970  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:33.250  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:28:35.920   289   289 E SMD     : DCD OFF
,03-16 11:28:38.930   289   289 E SMD     : DCD OFF
,03-16 11:28:41.930   289   289 E SMD     : DCD OFF
,03-16 11:28:42.990  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:43.310  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:28:44.930   289   289 E SMD     : DCD OFF
,03-16 11:28:47.930   289   289 E SMD     : DCD OFF
,03-16 11:28:50.930   289   289 E SMD     : DCD OFF
,03-16 11:28:53.000  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:28:53.380  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:28:53.940   289   289 E SMD     : DCD OFF
,03-16 11:28:56.930   289   289 E SMD     : DCD OFF
,03-16 11:28:59.930   289   289 E SMD     : DCD OFF
,03-16 11:29:01.520  1020  1317 E Watchdog: !@Sync 24
,03-16 11:29:02.940   289   289 E SMD     : DCD OFF
,03-16 11:29:03.050  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:03.440  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:29:05.940   289   289 E SMD     : DCD OFF
,03-16 11:29:08.950   289   289 E SMD     : DCD OFF
,03-16 11:29:11.940   289   289 E SMD     : DCD OFF
,03-16 11:29:13.090  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:13.510  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:29:14.950   289   289 E SMD     : DCD OFF
,03-16 11:29:17.940   289   289 E SMD     : DCD OFF
,03-16 11:29:20.940   289   289 E SMD     : DCD OFF
,03-16 11:29:21.950  1020  1052 I PowerManagerService: [PWL] Off : 680s ago
,03-16 11:29:23.110  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:23.570  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:29:23.950   289   289 E SMD     : DCD OFF
,03-16 11:29:26.960   289   289 E SMD     : DCD OFF
,03-16 11:29:29.950   289   289 E SMD     : DCD OFF
,03-16 11:29:31.520  1020  1317 E Watchdog: !@Sync 25
,03-16 11:29:32.950   289   289 E SMD     : DCD OFF
,03-16 11:29:33.140  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:33.630  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:29:35.960   289   289 E SMD     : DCD OFF
,03-16 11:29:38.960   289   289 E SMD     : DCD OFF
,03-16 11:29:41.960   289   289 E SMD     : DCD OFF
,03-16 11:29:43.180  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:43.700  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:29:44.960   289   289 E SMD     : DCD OFF
,03-16 11:29:47.970   289   289 E SMD     : DCD OFF
,03-16 11:29:50.960   289   289 E SMD     : DCD OFF
,03-16 11:29:53.200  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:29:53.760  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:29:53.960   289   289 E SMD     : DCD OFF
,03-16 11:29:56.960   289   289 E SMD     : DCD OFF,
,03-16 11:29:59.970   289   289 E SMD     : DCD OFF
,03-16 11:30:01.520  1020  1317 E Watchdog: !@Sync 26
,03-16 11:30:02.970   289   289 E SMD     : DCD OFF
,03-16 11:30:03.210  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:03.830  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:30:05.970   289   289 E SMD     : DCD OFF
,03-16 11:30:08.970   289   289 E SMD     : DCD OFF
,03-16 11:30:11.970   289   289 E SMD     : DCD OFF
,03-16 11:30:13.230  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:13.890  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:30:14.970   289   289 E SMD     : DCD OFF
,03-16 11:30:17.970   289   289 E SMD     : DCD OFF,
,03-16 11:30:20.980   289   289 E SMD     : DCD OFF,
,03-16 11:30:23.260  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:23.950  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:30:23.980   289   289 E SMD     : DCD OFF
,03-16 11:30:26.980   289   289 E SMD     : DCD OFF
,03-16 11:30:29.980   289   289 E SMD     : DCD OFF
,03-16 11:30:31.530  1020  1317 E Watchdog: !@Sync 27,
,03-16 11:30:32.990   289   289 E SMD     : DCD OFF
,03-16 11:30:33.270  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:34.020  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:30:35.980   289   289 E SMD     : DCD OFF
,03-16 11:30:38.980   289   289 E SMD     : DCD OFF
,03-16 11:30:41.990   289   289 E SMD     : DCD OFF
,03-16 11:30:43.290  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:44.080  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:30:44.080  1020  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:30:44.080  1020  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:30:44.080  1020  3410 D BatteryService: stay LED for fully charged
03-16 11:30:44.080  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:30:44.080  1020  1020 I MotionRecognitionService: Plugged
03-16 11:30:44.080  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:30:44.080  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:30:44.080  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:30:44.080  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:30:44.080  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:30:44.090  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:30:44.090  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:30:44.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 11:30:44.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:30:44.110  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:30:44.110  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:30:44.110  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:30:44.990   289   289 E SMD     : DCD OFF
,03-16 11:30:46.950  1020  1052 I PowerManagerService: [PWL] Off : 765s ago,
,03-16 11:30:47.990   289   289 E SMD     : DCD OFF
,03-16 11:30:50.990   289   289 E SMD     : DCD OFF
,03-16 11:30:53.300  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:30:53.990   289   289 E SMD     : DCD OFF
,03-16 11:30:54.140  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:30:54.140  1020  1669 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:30:54.140  1020  1669 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:30:54.140  1020  1669 D BatteryService: stay LED for fully charged
,03-16 11:30:54.140  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:30:54.150  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:30:54.150  1020  1020 I MotionRecognitionService: Plugged
03-16 11:30:54.150  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:30:54.150  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:30:54.150  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:30:54.150  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:30:54.160  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:30:54.160  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:30:54.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:30:54.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:30:54.170  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:30:54.170  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:30:54.170  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:30:56.990   289   289 E SMD     : DCD OFF,
,03-16 11:31:00.000   289   289 E SMD     : DCD OFF
,03-16 11:31:01.520  1020  1317 E Watchdog: !@Sync 28
,03-16 11:31:03.000   289   289 E SMD     : DCD OFF
,03-16 11:31:03.350  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:04.210  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:31:04.210  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:31:04.210  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:31:04.210  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:31:04.210  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:31:04.210  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:31:04.210  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:31:04.210  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:31:04.210  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:31:04.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:31:04.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:31:04.230  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:31:04.230  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:31:04.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:31:04.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:31:04.240  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:31:04.240  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:31:04.240  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:31:06.010   289   289 E SMD     : DCD OFF
,03-16 11:31:09.010   289   289 E SMD     : DCD OFF
,03-16 11:31:12.000   289   289 E SMD     : DCD OFF
,03-16 11:31:13.400  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:14.270  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:31:14.270  1020  3681 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:31:14.270  1020  3681 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:31:14.270  1020  3681 D BatteryService: stay LED for fully charged
,03-16 11:31:14.270  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:31:14.270  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:31:14.270  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:31:14.280  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:31:14.280  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:31:14.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:31:14.280  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:31:14.290  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 11:31:14.290  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:31:14.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:31:14.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:31:14.300  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:31:14.300  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:31:14.300  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:31:15.000   289   289 E SMD     : DCD OFF
,03-16 11:31:18.000   289   289 E SMD     : DCD OFF
,03-16 11:31:21.010   289   289 E SMD     : DCD OFF
,03-16 11:31:23.410  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:24.010   289   289 E SMD     : DCD OFF
,03-16 11:31:24.330  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:31:27.010   289   289 E SMD     : DCD OFF
,03-16 11:31:30.010   289   289 E SMD     : DCD OFF
,03-16 11:31:31.520  1020  1317 E Watchdog: !@Sync 29
,03-16 11:31:33.010   289   289 E SMD     : DCD OFF
,03-16 11:31:33.430  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:34.400  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:31:36.020   289   289 E SMD     : DCD OFF
,03-16 11:31:39.010   289   289 E SMD     : DCD OFF
,03-16 11:31:42.020   289   289 E SMD     : DCD OFF
,03-16 11:31:43.440  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:44.460  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:31:45.020   289   289 E SMD     : DCD OFF
,03-16 11:31:48.020   289   289 E SMD     : DCD OFF
,03-16 11:31:51.020   289   289 E SMD     : DCD OFF
,03-16 11:31:53.460  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:31:54.020   289   289 E SMD     : DCD OFF
,03-16 11:31:54.520  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:31:57.020   289   289 E SMD     : DCD OFF
,03-16 11:31:58.560  1020  1089 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-16 11:31:58.570  1020  1089 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-16 11:31:58.570  1020  1088 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 11:32:00.030   289   289 E SMD     : DCD OFF
,03-16 11:32:00.520  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3,
03-16 11:32:00.520  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 11:32:00.520  1020  1089 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-16 11:32:00.520  1020  1089 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:32:01.520  1020  1317 E Watchdog: !@Sync 30
,03-16 11:32:03.030   289   289 E SMD     : DCD OFF
,03-16 11:32:03.470  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:04.590  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:06.030   289   289 E SMD     : DCD OFF
,03-16 11:32:09.040   289   289 E SMD     : DCD OFF
,03-16 11:32:12.030   289   289 E SMD     : DCD OFF
,03-16 11:32:13.490  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:14.650  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:15.030   289   289 E SMD     : DCD OFF
,03-16 11:32:16.970  1020  1052 I PowerManagerService: [PWL] Off : 855s ago
,03-16 11:32:18.030   289   289 E SMD     : DCD OFF
,03-16 11:32:21.040   289   289 E SMD     : DCD OFF,
,03-16 11:32:21.510  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:32:21.520  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-16 11:32:21.520  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:32:21.540  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 11:32:21.540  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 11:32:21.560  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:32:21.560  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 11:32:21.560  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 11:32:21.600  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:32:21.610  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:32:21.610  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:32:21.640  1020  1031 I art     : Background sticky concurrent mark sweep GC freed 65690(6MB) AllocSpace objects, 308(4MB) LOS objects, 32% free, 24MB/35MB, paused 3.126ms total 119.975ms
,03-16 11:32:21.640  1020  1343 I art     : WaitForGcToComplete blocked for 23.561ms for cause Explicit
,03-16 11:32:21.780  1020  1343 I art     : Explicit concurrent mark sweep GC freed 9727(564KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 23MB/35MB, paused 2.365ms total 145.765ms
,03-16 11:32:21.790  1686  4036 D GCM     : Message class com.google.f.a.a.i
,03-16 11:32:21.790  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 11:32:21.800  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:32:23.530  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:24.040   289   289 E SMD     : DCD OFF
,03-16 11:32:24.710  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:27.040   289   289 E SMD     : DCD OFF
,03-16 11:32:30.050   289   289 E SMD     : DCD OFF
,03-16 11:32:31.520  1020  1317 E Watchdog: !@Sync 31
,03-16 11:32:33.050   289   289 E SMD     : DCD OFF
,03-16 11:32:33.550  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:34.780  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:36.050   289   289 E SMD     : DCD OFF
,03-16 11:32:39.050   289   289 E SMD     : DCD OFF
,03-16 11:32:42.050   289   289 E SMD     : DCD OFF
,03-16 11:32:43.570  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:44.840  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:45.050   289   289 E SMD     : DCD OFF
,03-16 11:32:48.050   289   289 E SMD     : DCD OFF
,03-16 11:32:51.060   289   289 E SMD     : DCD OFF
,03-16 11:32:53.590  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:32:54.050   289   289 E SMD     : DCD OFF
,03-16 11:32:54.910  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:32:57.060   289   289 E SMD     : DCD OFF
,03-16 11:32:59.990  1020  1098 V AlarmManager: waitForAlarm result :8,
,03-16 11:33:00.060   289   289 E SMD     : DCD OFF
,03-16 11:33:01.530  1020  1317 E Watchdog: !@Sync 32
,03-16 11:33:03.070   289   289 E SMD     : DCD OFF
,03-16 11:33:03.610  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:33:04.970  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:33:06.060   289   289 E SMD     : DCD OFF
,03-16 11:33:09.060   289   289 E SMD     : DCD OFF
,03-16 11:33:12.060   289   289 E SMD     : DCD OFF
,03-16 11:33:13.650  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:33:15.030  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:33:15.040  1020  1032 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:33:15.040  1020  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:33:15.040  1020  1032 D BatteryService: stay LED for fully charged
03-16 11:33:15.040  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:33:15.040  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:33:15.040  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:33:15.040  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:33:15.040  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:33:15.050  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:33:15.050  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:33:15.060  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:33:15.060  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:33:15.070   289   289 E SMD     : DCD OFF
,03-16 11:33:15.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:33:15.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:33:15.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:33:15.070  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:33:15.070  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:33:18.070   289   289 E SMD     : DCD OFF
,03-16 11:33:21.070   289   289 E SMD     : DCD OFF
,03-16 11:33:23.670  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:33:24.070   289   289 E SMD     : DCD OFF
,03-16 11:33:25.100  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:33:27.070   289   289 E SMD     : DCD OFF
,03-16 11:33:30.070   289   289 E SMD     : DCD OFF
,03-16 11:33:31.530  1020  1317 E Watchdog: !@Sync 33
,03-16 11:33:33.080   289   289 E SMD     : DCD OFF
,03-16 11:33:33.710  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:33:35.160  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:33:36.080   289   289 E SMD     : DCD OFF,
,03-16 11:33:39.080   289   289 E SMD     : DCD OFF
,03-16 11:33:42.080   289   289 E SMD     : DCD OFF
,03-16 11:33:43.760  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:33:45.080   289   289 E SMD     : DCD OFF
,03-16 11:33:45.220  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:33:48.080   289   289 E SMD     : DCD OFF
,03-16 11:33:51.080   289   289 E SMD     : DCD OFF,
,03-16 11:33:51.990  1020  1052 I PowerManagerService: [PWL] Off : 950s ago
,03-16 11:33:53.770  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:33:54.090   289   289 E SMD     : DCD OFF
,03-16 11:33:55.290  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:33:55.290  1020  1669 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:33:55.290  1020  1669 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:33:55.290  1020  1669 D BatteryService: stay LED for fully charged
,03-16 11:33:55.290  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:33:55.290  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:33:55.300  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:33:55.290  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:33:55.300  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:33:55.300  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:33:55.300  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:33:55.310  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 11:33:55.310  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:33:55.320  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:33:55.320  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:33:55.320  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:33:55.320  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:33:55.320  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:33:57.090   289   289 E SMD     : DCD OFF
,03-16 11:34:00.090   289   289 E SMD     : DCD OFF
,03-16 11:34:01.530  1020  1317 E Watchdog: !@Sync 34
,03-16 11:34:03.090   289   289 E SMD     : DCD OFF
,03-16 11:34:03.790  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:05.350  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:34:05.350  1020  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:34:05.350  1020  1142 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:34:05.350  1020  1142 D BatteryService: stay LED for fully charged
,03-16 11:34:05.350  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:34:05.360  1020  1020 I MotionRecognitionService: Plugged
03-16 11:34:05.360  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:34:05.360  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:34:05.360  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:34:05.360  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:34:05.360  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:34:05.370  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:34:05.380  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:34:05.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:34:05.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:05.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:34:05.390  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:34:05.390  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:34:06.100   289   289 E SMD     : DCD OFF
,03-16 11:34:09.090   289   289 E SMD     : DCD OFF
,03-16 11:34:12.090   289   289 E SMD     : DCD OFF
,03-16 11:34:13.840  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:15.100   289   289 E SMD     : DCD OFF
,03-16 11:34:15.420  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:34:15.420  1020  1781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:34:15.420  1020  1781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:34:15.420  1020  1781 D BatteryService: stay LED for fully charged
03-16 11:34:15.420  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:34:15.420  1020  1020 I MotionRecognitionService: Plugged
03-16 11:34:15.420  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:34:15.420  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:34:15.420  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:34:15.430  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:34:15.430  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:34:15.440  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 11:34:15.440  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:34:15.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:15.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:15.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:15.450  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:34:15.450  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:34:18.100   289   289 E SMD     : DCD OFF
,03-16 11:34:21.100   289   289 E SMD     : DCD OFF,
,03-16 11:34:23.850  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:24.010  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:34:24.020  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-16 11:34:24.020  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:34:24.020  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 11:34:24.030  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 11:34:24.040  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:34:24.040  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-16 11:34:24.040  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,03-16 11:34:24.070  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:34:24.070  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:34:24.070  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:34:24.080  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-16 11:34:24.100  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:34:24.100   289   289 E SMD     : DCD OFF
,03-16 11:34:24.500  6087  6708 I BooksSync: Starting books sync for 61035162, extras: ade
,03-16 11:34:24.520  6087  6709 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-16 11:34:24.520  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.520  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:34:24.520  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.530  1020  3681 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.530  1020  3681 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:34:24.530  1020  3681 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.550  1686  1793 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 11:34:24.550  1686  1793 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 11:34:24.550  1686  1793 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 11:34:24.550  1686  1793 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:34:24.560  1686  1793 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:34:24.560  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.560  1020  1669 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:34:24.560  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.580  1020  1339 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-16 11:34:24.580  1020  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-16 11:34:24.580  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 11:34:24.590  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 11:34:24.590  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:34:24.590  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:34:24.590  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:34:24.590  1177  1177 I StatusBar: Icon Only
03-16 11:34:24.590  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:34:24.590  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:34:24.590  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:34:24.590  1177  1177 I PhoneStatusBar: Icon Only
03-16 11:34:24.590  1177  1177 I StatusBar: Icon Only
,03-16 11:34:24.600  1177  1177 D PanelView: There is/are notification(s) 
03-16 11:34:24.600  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:34:24.600  1020  1343 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.600  1020  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:34:24.600  1020  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.620  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.620  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 11:34:24.620  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.630  1686  1792 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-16 11:34:24.640  1686  1792 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 11:34:24.640  1686  1792 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 11:34:24.640  1686  1792 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 11:34:24.640  1686  1792 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:34:24.640  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:34:24.640  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 11:34:24.650  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 11:34:24.660  6087  6709 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-16 11:34:24.660  6087  6708 E BooksSync: Soft error
03-16 11:34:24.660  6087  6708 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:34:24.660  6087  6708 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:34:24.660  6087  6708 E BooksSync: Sync error
03-16 11:34:24.660  6087  6708 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-16 11:34:24.660  6087  6708 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-16 11:34:24.660  6087  6708 I BooksSync: Finished books sync
,03-16 11:34:24.660  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-16 11:34:24.670  1020  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1060758, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-16 11:34:24.720  1020  1339 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 11:34:24.720  1020  1339 D SecContentProvider2: mCursor = null
,03-16 11:34:25.480  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:34:25.480  1020  1503 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:34:25.480  1020  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 11:34:25.480  1020  1503 D BatteryService: stay LED for fully charged
03-16 11:34:25.480  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:34:25.490  1020  1020 I MotionRecognitionService: Plugged
03-16 11:34:25.490  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:34:25.490  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:34:25.490  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:34:25.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:34:25.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:34:25.500  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:34:25.500  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:34:25.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:34:25.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:25.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:34:25.510  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:34:25.510  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:34:27.110   289   289 E SMD     : DCD OFF
,03-16 11:34:30.100   289   289 E SMD     : DCD OFF
,03-16 11:34:31.530  1020  1317 E Watchdog: !@Sync 35,
,03-16 11:34:33.110   289   289 E SMD     : DCD OFF
,03-16 11:34:33.900  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:35.540  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:34:36.110   289   289 E SMD     : DCD OFF,
,03-16 11:34:39.110   289   289 E SMD     : DCD OFF
,03-16 11:34:42.110   289   289 E SMD     : DCD OFF
,03-16 11:34:43.920  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:45.120   289   289 E SMD     : DCD OFF
,03-16 11:34:45.610  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:34:48.110   289   289 E SMD     : DCD OFF
,03-16 11:34:51.110   289   289 E SMD     : DCD OFF,
,03-16 11:34:53.960  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:34:54.120   289   289 E SMD     : DCD OFF
,03-16 11:34:54.500  1020  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:34:55.670  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:34:57.120   289   289 E SMD     : DCD OFF
,03-16 11:34:59.990  1020  1098 V AlarmManager: waitForAlarm result :8,
,03-16 11:35:00.120   289   289 E SMD     : DCD OFF,
,03-16 11:35:01.530  1020  1317 E Watchdog: !@Sync 36
,03-16 11:35:03.120   289   289 E SMD     : DCD OFF
,03-16 11:35:03.980  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:35:05.740  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:35:06.120   289   289 E SMD     : DCD OFF,
,03-16 11:35:09.130   289   289 E SMD     : DCD OFF
,03-16 11:35:12.120   289   289 E SMD     : DCD OFF
,03-16 11:35:13.990  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:35:15.130   289   289 E SMD     : DCD OFF
,03-16 11:35:15.800  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:35:15.800  1020  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:35:15.800  1020  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:35:15.800  1020  1483 D BatteryService: stay LED for fully charged
03-16 11:35:15.800  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:35:15.800  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:35:15.800  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:35:15.810  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:35:15.810  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:35:15.810  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:35:15.810  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:35:15.820  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:35:15.820  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:35:15.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:15.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:15.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:35:15.830  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:35:15.830  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:35:18.130   289   289 E SMD     : DCD OFF
,03-16 11:35:21.130   289   289 E SMD     : DCD OFF
,03-16 11:35:24.040  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:35:24.130   289   289 E SMD     : DCD OFF
,03-16 11:35:25.860  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:35:25.860  1020  1345 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:35:25.860  1020  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:35:25.860  1020  1345 D BatteryService: stay LED for fully charged
03-16 11:35:25.860  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:35:25.870  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:35:25.870  1020  1020 I MotionRecognitionService: Plugged
03-16 11:35:25.870  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 11:35:25.870  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:35:25.870  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:35:25.870  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:35:25.880  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:35:25.890  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:35:25.900  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:25.900  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:35:25.900  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:25.900  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:35:25.900  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:35:27.130   289   289 E SMD     : DCD OFF
,03-16 11:35:30.130   289   289 E SMD     : DCD OFF
,03-16 11:35:31.530  1020  1317 E Watchdog: !@Sync 37
,03-16 11:35:32.000  1020  1052 I PowerManagerService: [PWL] Off : 1050s ago,
,03-16 11:35:33.140   289   289 E SMD     : DCD OFF
,03-16 11:35:34.090  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:35:35.930  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:35:35.930  1020  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:35:35.930  1020  1142 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:35:35.930  1020  1142 D BatteryService: stay LED for fully charged
,03-16 11:35:35.930  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:35:35.930  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:35:35.930  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:35:35.930  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:35:35.940  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:35:35.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:35:35.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:35:35.950  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:35:35.950  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:35:35.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:35.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:35:35.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:35.960  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:35:35.960  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:35:36.140   289   289 E SMD     : DCD OFF,
,03-16 11:35:39.140   289   289 E SMD     : DCD OFF
,03-16 11:35:42.140   289   289 E SMD     : DCD OFF,
,03-16 11:35:44.100  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:35:45.140   289   289 E SMD     : DCD OFF
,03-16 11:35:45.990  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:35:48.140   289   289 E SMD     : DCD OFF
,03-16 11:35:51.150   289   289 E SMD     : DCD OFF,
,03-16 11:35:54.120  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:35:54.150   289   289 E SMD     : DCD OFF
,03-16 11:35:56.060  1020  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:35:56.060  1020  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:35:56.060  1020  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:35:56.060  1020  1483 D BatteryService: stay LED for fully charged
,03-16 11:35:56.060  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:35:56.060  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:35:56.060  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:35:56.060  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:35:56.060  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:35:56.070  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:35:56.070  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:35:56.080  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:35:56.080  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:35:56.090  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:56.090  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:35:56.090  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:35:56.090  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:35:56.090  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:35:57.150   289   289 E SMD     : DCD OFF
,03-16 11:36:00.150   289   289 E SMD     : DCD OFF
,03-16 11:36:01.530  1020  1317 E Watchdog: !@Sync 38
,03-16 11:36:03.150   289   289 E SMD     : DCD OFF
,03-16 11:36:04.160  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:06.120  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:36:06.150   289   289 E SMD     : DCD OFF
,03-16 11:36:09.150   289   289 E SMD     : DCD OFF
,03-16 11:36:12.160   289   289 E SMD     : DCD OFF
,03-16 11:36:14.170  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:15.160   289   289 E SMD     : DCD OFF
,03-16 11:36:16.190  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:36:16.190  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:36:16.190  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:36:16.190  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:36:16.190  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:36:16.200  1020  1020 I MotionRecognitionService: Plugged,
,03-16 11:36:16.200  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:36:16.200  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:36:16.200  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 11:36:16.200  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:36:16.200  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:36:16.220  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 11:36:16.220  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:36:16.230  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:36:16.230  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:36:16.230  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:36:16.230  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:36:16.230  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:36:18.160   289   289 E SMD     : DCD OFF
,03-16 11:36:21.160   289   289 E SMD     : DCD OFF
,03-16 11:36:24.160   289   289 E SMD     : DCD OFF
,03-16 11:36:24.220  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:26.270  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:36:27.160   289   289 E SMD     : DCD OFF,
,03-16 11:36:30.170   289   289 E SMD     : DCD OFF
,03-16 11:36:31.530  1020  1317 E Watchdog: !@Sync 39,
,03-16 11:36:33.170   289   289 E SMD     : DCD OFF
,03-16 11:36:34.270  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:36.170   289   289 E SMD     : DCD OFF
,03-16 11:36:36.330  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:36:36.330  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:36:36.330  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:36:36.330  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:36:36.330  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:36:36.330  1020  1020 I MotionRecognitionService: Plugged
03-16 11:36:36.330  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:36:36.330  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:36:36.330  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:36:36.330  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:36:36.330  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:36:36.350  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:36:36.350  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:36:36.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:36:36.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:36:36.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:36:36.360  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:36:36.360  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:36:39.170   289   289 E SMD     : DCD OFF
,03-16 11:36:42.180   289   289 E SMD     : DCD OFF
,03-16 11:36:44.290  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:45.180   289   289 E SMD     : DCD OFF
,03-16 11:36:46.390  1020  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:36:48.180   289   289 E SMD     : DCD OFF
,03-16 11:36:51.180   289   289 E SMD     : DCD OFF
,03-16 11:36:54.180   289   289 E SMD     : DCD OFF
,03-16 11:36:54.300  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:36:56.450  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:36:56.450  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:36:56.450  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:36:56.450  1020  1343 D BatteryService: stay LED for fully charged
,03-16 11:36:56.450  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:36:56.460  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:36:56.460  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:36:56.460  1020  1020 I MotionRecognitionService: Plugged
03-16 11:36:56.460  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:36:56.460  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:36:56.460  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:36:56.470  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:36:56.470  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:36:56.480  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:36:56.480  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:36:56.480  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:36:56.490  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:36:56.490  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:36:57.190   289   289 E SMD     : DCD OFF
,03-16 11:36:58.560  1020  1089 D TimaService: TIMA: TimaService scheduler is intialized. 
03-16 11:36:58.560  1020  1089 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-16 11:36:58.570  1020  1088 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 11:36:59.060  1020  1043 I UsageStatsService: User[0] Flushing usage stats to disk
,03-16 11:36:59.100  1020  1106 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,03-16 11:36:59.100  1020  1106 I ApplicationUsage: Updating Usage Statistics in DB @ 1458124619111
,03-16 11:36:59.110  1020  1106 I ApplicationPolicy: updateDataUsageMap,
,03-16 11:36:59.400  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 11:36:59.400  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 11:36:59.410  1020  1089 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:36:59.410  1020  1089 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:36:59.440  1020  1106 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-16 11:36:59.440  1020  1106 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-16 11:36:59.460  1020  1106 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458124619478
,03-16 11:37:00.180   289   289 E SMD     : DCD OFF
,03-16 11:37:01.540  1020  1317 E Watchdog: !@Sync 40
,03-16 11:37:03.180   289   289 E SMD     : DCD OFF
,03-16 11:37:04.320  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:06.180   289   289 E SMD     : DCD OFF
,03-16 11:37:06.510  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:37:06.510  1020  1339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:37:06.510  1020  1339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 11:37:06.510  1020  1339 D BatteryService: stay LED for fully charged
03-16 11:37:06.510  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:37:06.520  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:37:06.520  1020  1020 I MotionRecognitionService: Plugged
03-16 11:37:06.520  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:37:06.520  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:37:06.520  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:37:06.520  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:37:06.530  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:37:06.530  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:37:06.540  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:37:06.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:37:06.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:37:06.550  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:37:06.550  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:37:09.190   289   289 E SMD     : DCD OFF
,03-16 11:37:12.190   289   289 E SMD     : DCD OFF
,03-16 11:37:14.330  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:15.190   289   289 E SMD     : DCD OFF
,03-16 11:37:16.580  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:37:17.000  1020  1052 I PowerManagerService: [PWL] Off : 1155s ago
,03-16 11:37:18.190   289   289 E SMD     : DCD OFF
,03-16 11:37:21.190   289   289 E SMD     : DCD OFF
,03-16 11:37:24.200   289   289 E SMD     : DCD OFF
,03-16 11:37:24.380  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:26.640  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:37:27.200   289   289 E SMD     : DCD OFF
,03-16 11:37:30.200   289   289 E SMD     : DCD OFF
,03-16 11:37:31.530  1020  1317 E Watchdog: !@Sync 41
,03-16 11:37:33.200   289   289 E SMD     : DCD OFF
,03-16 11:37:34.430  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:36.210   289   289 E SMD     : DCD OFF
,03-16 11:37:36.710  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:37:39.200   289   289 E SMD     : DCD OFF
,03-16 11:37:42.200   289   289 E SMD     : DCD OFF
,03-16 11:37:44.440  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:45.210   289   289 E SMD     : DCD OFF
,03-16 11:37:46.770  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:37:48.210   289   289 E SMD     : DCD OFF
,03-16 11:37:51.210   289   289 E SMD     : DCD OFF,
,03-16 11:37:54.220   289   289 E SMD     : DCD OFF
,03-16 11:37:54.470  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:37:56.830  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:37:56.830  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:37:56.830  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:37:56.830  1020  1033 D BatteryService: stay LED for fully charged,
03-16 11:37:56.830  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:37:56.830  1020  1020 I MotionRecognitionService: Plugged
03-16 11:37:56.830  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:37:56.840  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:37:56.840  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:37:56.840  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:37:56.840  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:37:56.850  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 11:37:56.850  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:37:56.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:37:56.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:37:56.860  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:37:56.870  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:37:56.870  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:37:57.210   289   289 E SMD     : DCD OFF
,03-16 11:38:00.210   289   289 E SMD     : DCD OFF
,03-16 11:38:01.540  1020  1317 E Watchdog: !@Sync 42
,03-16 11:38:03.210   289   289 E SMD     : DCD OFF
,03-16 11:38:04.520  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:06.220   289   289 E SMD     : DCD OFF
,03-16 11:38:06.900  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:38:06.900  1020  3947 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:38:06.900  1020  3947 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:38:06.900  1020  3947 D BatteryService: stay LED for fully charged
03-16 11:38:06.900  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:38:06.900  1020  1020 I MotionRecognitionService: Plugged
03-16 11:38:06.900  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:38:06.900  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:38:06.900  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:38:06.900  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:38:06.900  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:38:06.910  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:38:06.910  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:38:06.930  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:06.930  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:06.930  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:06.930  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:38:06.930  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:38:09.220   289   289 E SMD     : DCD OFF,
,03-16 11:38:12.220   289   289 E SMD     : DCD OFF
,03-16 11:38:14.530  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:15.230   289   289 E SMD     : DCD OFF
,03-16 11:38:16.960  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:38:16.960  1020  1503 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:38:16.960  1020  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:38:16.960  1020  1503 D BatteryService: stay LED for fully charged
,03-16 11:38:16.960  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:38:16.960  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:38:16.960  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:38:16.970  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:38:16.970  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:38:16.970  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:38:16.970  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:38:16.980  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:38:16.980  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:38:16.990  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:16.990  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:16.990  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:16.990  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:38:16.990  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:38:18.220   289   289 E SMD     : DCD OFF
,03-16 11:38:21.220   289   289 E SMD     : DCD OFF
,03-16 11:38:24.230   289   289 E SMD     : DCD OFF
,03-16 11:38:24.580  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:27.020  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:38:27.020  1020  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:38:27.020  1020  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:38:27.020  1020  3410 D BatteryService: stay LED for fully charged
03-16 11:38:27.020  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:38:27.030  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:38:27.030  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:38:27.030  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 11:38:27.030  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:38:27.030  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:38:27.030  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:38:27.040  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:38:27.040  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:38:27.060  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:27.060  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:27.060  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:27.060  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:38:27.060  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:38:27.230   289   289 E SMD     : DCD OFF
,03-16 11:38:30.240   289   289 E SMD     : DCD OFF
,03-16 11:38:31.540  1020  1317 E Watchdog: !@Sync 43,
,03-16 11:38:33.230   289   289 E SMD     : DCD OFF
,03-16 11:38:34.630  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:36.230   289   289 E SMD     : DCD OFF
,03-16 11:38:37.090  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:38:39.230   289   289 E SMD     : DCD OFF
,03-16 11:38:42.230   289   289 E SMD     : DCD OFF
,03-16 11:38:44.650  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:45.240   289   289 E SMD     : DCD OFF
,03-16 11:38:47.150  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:38:47.150  1020  1781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:38:47.150  1020  1781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:38:47.150  1020  1781 D BatteryService: stay LED for fully charged
,03-16 11:38:47.150  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:38:47.160  1020  1020 I MotionRecognitionService: Plugged
03-16 11:38:47.160  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:38:47.160  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:38:47.160  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:38:47.160  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:38:47.160  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:38:47.170  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:38:47.170  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:38:47.180  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:47.180  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:47.180  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:47.180  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:38:47.180  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:38:48.240   289   289 E SMD     : DCD OFF
,03-16 11:38:51.240   289   289 E SMD     : DCD OFF
,03-16 11:38:54.240   289   289 E SMD     : DCD OFF
,03-16 11:38:54.700  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:38:57.210  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:38:57.210  1020  1790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:38:57.210  1020  1790 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:38:57.210  1020  1790 D BatteryService: stay LED for fully charged
03-16 11:38:57.210  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:38:57.220  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:38:57.220  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:38:57.220  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:38:57.220  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:38:57.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:38:57.220  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:38:57.240  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:38:57.240  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:38:57.240   289   289 E SMD     : DCD OFF
,03-16 11:38:57.250  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:38:57.250  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:57.250  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:38:57.250  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:38:57.250  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:39:00.240   289   289 E SMD     : DCD OFF
,03-16 11:39:01.540  1020  1317 E Watchdog: !@Sync 44
,03-16 11:39:03.240   289   289 E SMD     : DCD OFF
,03-16 11:39:04.750  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:06.250   289   289 E SMD     : DCD OFF
,03-16 11:39:07.000  1020  1052 I PowerManagerService: [PWL] Off : 1265s ago,
,03-16 11:39:07.280  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:39:09.250   289   289 E SMD     : DCD OFF
,03-16 11:39:12.250   289   289 E SMD     : DCD OFF
,03-16 11:39:14.770  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:15.250   289   289 E SMD     : DCD OFF
,03-16 11:39:17.330  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:39:17.330  1020  1790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:39:17.330  1020  1790 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:39:17.330  1020  1790 D BatteryService: stay LED for fully charged
03-16 11:39:17.330  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:39:17.340  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:39:17.340  1020  1020 I MotionRecognitionService: Plugged
03-16 11:39:17.340  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:39:17.340  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:39:17.340  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 11:39:17.340  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:39:17.350  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:39:17.350  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:39:17.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:39:17.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:39:17.370  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:39:17.370  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:39:17.370  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:39:18.250   289   289 E SMD     : DCD OFF
,03-16 11:39:21.250   289   289 E SMD     : DCD OFF,
,03-16 11:39:24.260   289   289 E SMD     : DCD OFF
,03-16 11:39:24.780  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:27.270   289   289 E SMD     : DCD OFF
,03-16 11:39:27.400  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:39:30.270   289   289 E SMD     : DCD OFF
,03-16 11:39:31.540  1020  1317 E Watchdog: !@Sync 45
,03-16 11:39:33.260   289   289 E SMD     : DCD OFF
,03-16 11:39:34.830  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:36.260   289   289 E SMD     : DCD OFF
,03-16 11:39:37.460  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:39:39.270   289   289 E SMD     : DCD OFF
,03-16 11:39:42.270   289   289 E SMD     : DCD OFF,
,03-16 11:39:44.850  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:45.270   289   289 E SMD     : DCD OFF
,03-16 11:39:47.520  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:39:47.520  1020  1669 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:39:47.520  1020  1669 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:39:47.520  1020  1669 D BatteryService: stay LED for fully charged
03-16 11:39:47.520  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:39:47.530  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:39:47.530  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:39:47.530  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:39:47.530  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:39:47.530  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:39:47.530  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:39:47.540  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:39:47.540  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:39:47.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:39:47.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:39:47.550  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:39:47.550  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 11:39:47.560  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:39:48.270   289   289 E SMD     : DCD OFF
,03-16 11:39:51.270   289   289 E SMD     : DCD OFF
,03-16 11:39:54.270   289   289 E SMD     : DCD OFF
,03-16 11:39:54.900  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:39:57.270   289   289 E SMD     : DCD OFF,
,03-16 11:39:57.590  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:40:00.280   289   289 E SMD     : DCD OFF
,03-16 11:40:01.550  1020  1317 E Watchdog: !@Sync 46
,03-16 11:40:03.280   289   289 E SMD     : DCD OFF
,03-16 11:40:04.930  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:06.280   289   289 E SMD     : DCD OFF
,03-16 11:40:07.650  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:40:09.280   289   289 E SMD     : DCD OFF
,03-16 11:40:12.280   289   289 E SMD     : DCD OFF
,03-16 11:40:14.950  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:15.280   289   289 E SMD     : DCD OFF
,03-16 11:40:17.710  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:40:18.290   289   289 E SMD     : DCD OFF
,03-16 11:40:21.290   289   289 E SMD     : DCD OFF
,03-16 11:40:24.290   289   289 E SMD     : DCD OFF
,03-16 11:40:24.960  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:27.290   289   289 E SMD     : DCD OFF
,03-16 11:40:27.780  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:40:30.290   289   289 E SMD     : DCD OFF
,03-16 11:40:31.550  1020  1317 E Watchdog: !@Sync 47,
,03-16 11:40:33.300   289   289 E SMD     : DCD OFF
,03-16 11:40:34.980  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:36.290   289   289 E SMD     : DCD OFF
,03-16 11:40:37.840  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:40:37.840  1020  3681 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-16 11:40:37.840  1020  3681 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:40:37.840  1020  3681 D BatteryService: stay LED for fully charged
,03-16 11:40:37.840  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:40:37.850  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:40:37.850  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:40:37.850  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:40:37.850  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:40:37.860  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:40:37.860  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:40:37.870  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:40:37.870  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:40:37.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:37.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:37.880  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:37.880  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 11:40:37.880  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:40:39.290   289   289 E SMD     : DCD OFF
,03-16 11:40:42.300   289   289 E SMD     : DCD OFF
,03-16 11:40:45.000  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:45.300   289   289 E SMD     : DCD OFF
,03-16 11:40:47.910  1020  3946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:40:47.910  1020  3946 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:40:47.910  1020  3946 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:40:47.910  1020  3946 D BatteryService: stay LED for fully charged
03-16 11:40:47.910  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:40:47.910  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:40:47.910  1020  1020 I MotionRecognitionService: Plugged
03-16 11:40:47.910  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-16 11:40:47.910  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:40:47.920  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 11:40:47.920  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:40:47.930  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 11:40:47.930  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:40:47.940  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:47.940  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:47.940  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:47.940  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:40:47.940  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:40:48.310   289   289 E SMD     : DCD OFF
,03-16 11:40:51.300   289   289 E SMD     : DCD OFF,
,03-16 11:40:54.300   289   289 E SMD     : DCD OFF
,03-16 11:40:55.050  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:40:57.300   289   289 E SMD     : DCD OFF,
,03-16 11:40:57.970  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:40:57.970  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:40:57.970  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:40:57.970  1020  1033 D BatteryService: stay LED for fully charged
,03-16 11:40:57.970  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:40:57.970  1020  1020 I MotionRecognitionService: Plugged
03-16 11:40:57.970  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false,
,03-16 11:40:57.980  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:40:57.980  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-16 11:40:57.980  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:40:57.980  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:40:57.990  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:40:57.990  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:40:58.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:58.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:40:58.000  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:40:58.000  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:40:58.000  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:00.310   289   289 E SMD     : DCD OFF
,03-16 11:41:01.540  1020  1317 E Watchdog: !@Sync 48
,03-16 11:41:02.010  1020  1052 I PowerManagerService: [PWL] Off : 1380s ago,
,03-16 11:41:03.310   289   289 E SMD     : DCD OFF
,03-16 11:41:05.060  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:06.320   289   289 E SMD     : DCD OFF,
,03-16 11:41:08.030  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:41:08.030  1020  3947 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-16 11:41:08.040  1020  3947 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:41:08.040  1020  3947 D BatteryService: stay LED for fully charged
,03-16 11:41:08.040  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:41:08.040  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:41:08.040  1020  1020 I MotionRecognitionService: Plugged
03-16 11:41:08.040  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:41:08.040  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:41:08.040  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:41:08.050  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:41:08.050  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:41:08.050  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:41:08.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:08.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:08.070  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:08.070  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 11:41:08.070  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:09.310   289   289 E SMD     : DCD OFF
,03-16 11:41:12.310   289   289 E SMD     : DCD OFF
,03-16 11:41:15.080  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:15.310   289   289 E SMD     : DCD OFF
,03-16 11:41:18.100  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:41:18.100  1020  1503 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:41:18.100  1020  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:41:18.100  1020  1503 D BatteryService: stay LED for fully charged
,03-16 11:41:18.100  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:41:18.110  1020  1020 I MotionRecognitionService: Plugged
03-16 11:41:18.110  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:41:18.110  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:41:18.110  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:41:18.110  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:41:18.110  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:41:18.120  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:41:18.120  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:41:18.130  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:18.140  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:18.140  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:41:18.140  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:41:18.140  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:18.310   289   289 E SMD     : DCD OFF
,03-16 11:41:21.320   289   289 E SMD     : DCD OFF,
,03-16 11:41:24.320   289   289 E SMD     : DCD OFF
,03-16 11:41:25.120  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:27.320   289   289 E SMD     : DCD OFF
,03-16 11:41:28.160  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:41:30.330   289   289 E SMD     : DCD OFF
,03-16 11:41:31.540  1020  1317 E Watchdog: !@Sync 49
,03-16 11:41:33.320   289   289 E SMD     : DCD OFF
,03-16 11:41:35.140  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:36.320   289   289 E SMD     : DCD OFF,
,03-16 11:41:38.230  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:41:38.230  1020  1032 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:41:38.230  1020  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:41:38.230  1020  1032 D BatteryService: stay LED for fully charged
03-16 11:41:38.230  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 11:41:38.230  1020  1020 I MotionRecognitionService: Plugged
03-16 11:41:38.230  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:41:38.230  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:41:38.230  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:41:38.230  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:41:38.230  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-16 11:41:38.240  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:41:38.250  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:41:38.260  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:38.260  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:38.260  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:41:38.260  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:41:38.260  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:39.330   289   289 E SMD     : DCD OFF
,03-16 11:41:42.330   289   289 E SMD     : DCD OFF
,03-16 11:41:45.160  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:45.330   289   289 E SMD     : DCD OFF
,03-16 11:41:48.290  1020  1669 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:41:48.290  1020  1669 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:41:48.290  1020  1669 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:41:48.290  1020  1669 D BatteryService: stay LED for fully charged
,03-16 11:41:48.290  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:41:48.300  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:41:48.300  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:41:48.300  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:41:48.300  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:41:48.300  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:41:48.300  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:41:48.310  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:41:48.310  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:41:48.330  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:48.330  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:48.330  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:48.330  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:41:48.330  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:48.330   289   289 E SMD     : DCD OFF
,03-16 11:41:51.330   289   289 E SMD     : DCD OFF,
,03-16 11:41:54.330   289   289 E SMD     : DCD OFF
,03-16 11:41:55.180  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:41:57.330   289   289 E SMD     : DCD OFF
,03-16 11:41:58.350  1020  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:41:58.360  1020  1503 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:41:58.360  1020  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:41:58.360  1020  1503 D BatteryService: stay LED for fully charged
,03-16 11:41:58.360  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:41:58.360  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:41:58.360  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:41:58.360  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:41:58.360  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:41:58.370  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:41:58.370  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:41:58.380  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:41:58.380  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:41:58.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:41:58.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:41:58.390  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:41:58.390  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:41:58.390  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:41:58.560  1020  1089 D TimaService: TIMA: TimaService scheduler is intialized. 
03-16 11:41:58.560  1020  1089 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-16 11:41:58.570  1020  1088 D TimaService: TimaServiceHandler.handleMessage what =1
,03-16 11:42:00.340   289   289 E SMD     : DCD OFF
,03-16 11:42:00.510  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-16 11:42:00.510  1020  1089 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-16 11:42:00.520  1020  1089 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:42:00.520  1020  1089 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-16 11:42:01.540  1020  1317 E Watchdog: !@Sync 50
,03-16 11:42:03.340   289   289 E SMD     : DCD OFF
,03-16 11:42:05.230  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:42:06.340   289   289 E SMD     : DCD OFF,
,03-16 11:42:08.420  1020  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:42:08.420  1020  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:42:08.420  1020  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:42:08.420  1020  3410 D BatteryService: stay LED for fully charged
03-16 11:42:08.420  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:42:08.420  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:42:08.420  1020  1020 I MotionRecognitionService: Plugged
03-16 11:42:08.420  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:42:08.420  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:42:08.430  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:42:08.430  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:42:08.440  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:42:08.440  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:42:08.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:08.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:08.450  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:08.450  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:42:08.450  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:42:09.340   289   289 E SMD     : DCD OFF
,03-16 11:42:12.350   289   289 E SMD     : DCD OFF
,03-16 11:42:15.240  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:42:15.340   289   289 E SMD     : DCD OFF
,03-16 11:42:18.340   289   289 E SMD     : DCD OFF
,03-16 11:42:18.480  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:42:18.480  1020  1790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:42:18.480  1020  1790 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:42:18.480  1020  1790 D BatteryService: stay LED for fully charged
03-16 11:42:18.480  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:42:18.480  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:42:18.480  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:42:18.490  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:42:18.490  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:42:18.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:42:18.490  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:42:18.500  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-16 11:42:18.500  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:42:18.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:18.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:18.510  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:18.510  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:42:18.510  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:42:21.350   289   289 E SMD     : DCD OFF
,03-16 11:42:24.350   289   289 E SMD     : DCD OFF
,03-16 11:42:25.270  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:42:27.350   289   289 E SMD     : DCD OFF
,03-16 11:42:28.540  1020  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:42:30.350   289   289 E SMD     : DCD OFF,
,03-16 11:42:31.550  1020  1317 E Watchdog: !@Sync 51
,03-16 11:42:33.360   289   289 E SMD     : DCD OFF
,03-16 11:42:35.290  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:42:36.350   289   289 E SMD     : DCD OFF,
,03-16 11:42:38.610  1020  1790 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:42:38.610  1020  1790 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:42:38.610  1020  1790 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:42:38.610  1020  1790 D BatteryService: stay LED for fully charged
,03-16 11:42:38.610  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:42:38.610  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:42:38.610  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 11:42:38.610  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 11:42:38.610  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 11:42:38.620  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:42:38.620  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:42:38.620  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:38.630  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:42:38.630  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:42:38.640  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-16 11:42:38.640  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:38.640  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:42:38.640  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:42:39.360   289   289 E SMD     : DCD OFF
,03-16 11:42:42.370   289   289 E SMD     : DCD OFF
,03-16 11:42:45.310  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:42:45.360   289   289 E SMD     : DCD OFF
,03-16 11:42:48.360   289   289 E SMD     : DCD OFF
,03-16 11:42:48.670  1020  1781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:42:48.670  1020  1781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:42:48.670  1020  1781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 11:42:48.670  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:42:48.670  1020  1781 D BatteryService: stay LED for fully charged
,03-16 11:42:48.680  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:42:48.680  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:42:48.680  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:42:48.680  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:42:48.680  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:42:48.680  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:42:48.700  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:42:48.700  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:42:48.710  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:48.710  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:48.710  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:48.710  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-16 11:42:48.710  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:42:51.360   289   289 E SMD     : DCD OFF,
,03-16 11:42:54.370   289   289 E SMD     : DCD OFF
,03-16 11:42:55.360  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:42:57.370   289   289 E SMD     : DCD OFF
,03-16 11:42:58.740  1020  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-16 11:42:58.740  1020  1343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:42:58.740  1020  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:42:58.740  1020  1343 D BatteryService: stay LED for fully charged
03-16 11:42:58.740  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-16 11:42:58.740  1020  1020 I MotionRecognitionService: Plugged
03-16 11:42:58.740  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:42:58.740  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:42:58.740  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:42:58.750  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:42:58.750  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:42:58.760  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:42:58.760  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:42:58.780  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:58.780  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:42:58.780  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:42:58.780  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:42:58.780  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:43:00.380   289   289 E SMD     : DCD OFF
,03-16 11:43:01.550  1020  1317 E Watchdog: !@Sync 52,
,03-16 11:43:02.020  1020  1052 I PowerManagerService: [PWL] Off : 1500s ago
,03-16 11:43:03.380   289   289 E SMD     : DCD OFF
,03-16 11:43:05.410  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:43:06.380   289   289 E SMD     : DCD OFF
,03-16 11:43:08.790  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:43:08.790  1020  3681 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:43:08.790  1020  3681 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:43:08.790  1020  3681 D BatteryService: stay LED for fully charged
03-16 11:43:08.790  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:43:08.800  1020  1020 I MotionRecognitionService: Plugged,
03-16 11:43:08.800  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:43:08.800  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-16 11:43:08.800  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:43:08.800  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:43:08.800  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:43:08.810  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:43:08.810  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:43:08.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:43:08.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:43:08.830  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:43:08.830  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:43:08.830  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:43:09.370   289   289 E SMD     : DCD OFF
,03-16 11:43:12.370   289   289 E SMD     : DCD OFF
,03-16 11:43:15.380   289   289 E SMD     : DCD OFF
,03-16 11:43:15.440  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:43:18.380   289   289 E SMD     : DCD OFF
,03-16 11:43:18.860  1020  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 11:43:18.860  1020  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:43:18.860  1020  1142 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:43:18.860  1020  1142 D BatteryService: stay LED for fully charged
03-16 11:43:18.860  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:43:18.860  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:43:18.860  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:43:18.870  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:43:18.870  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:43:18.870  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,03-16 11:43:18.870  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:43:18.880  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:43:18.880  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:43:18.890  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:43:18.890  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:43:18.890  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:43:18.890  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:43:18.890  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:43:21.380   289   289 E SMD     : DCD OFF
,03-16 11:43:24.380   289   289 E SMD     : DCD OFF
,03-16 11:43:25.480  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:43:27.380   289   289 E SMD     : DCD OFF
,03-16 11:43:28.920  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:43:28.920  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 11:43:28.920  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 11:43:28.920  1020  1033 D BatteryService: stay LED for fully charged
,03-16 11:43:28.920  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:43:28.930  1020  1020 I MotionRecognitionService: Plugged
,03-16 11:43:28.930  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:43:28.930  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:43:28.930  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:43:28.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-16 11:43:28.940  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:43:28.950  2631  2631 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:43:28.950  2631  2737 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:43:28.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:43:28.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:43:28.960  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:43:28.960  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 11:43:28.960  1177  1177 D SViewCoverView: level :100 plugged : 2
,03-16 11:43:30.390   289   289 E SMD     : DCD OFF
,03-16 11:43:31.550  1020  1317 E Watchdog: !@Sync 53,
,03-16 11:43:33.390   289   289 E SMD     : DCD OFF
,03-16 11:43:35.530  1020  2746 D SSRM:n  : SIOP:: AP = 260
,03-16 11:43:36.390   289   289 E SMD     : DCD OFF
,03-16 11:43:38.980  1020  3947 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-16 11:43:39.390   289   289 E SMD     : DCD OFF
,03-16 11:43:42.390   289   289 E SMD     : DCD OFF
,03-16 11:43:45.390   289   289 E SMD     : DCD OFF
,03-16 11:43:45.560  1020  2746 D SSRM:n  : SIOP:: AP = 260,
,03-16 11:43:48.400   289   289 E SMD     : DCD OFF
,03-16 11:43:49.050  1020  3681 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,TIME-OUT KILL (timeout was 1400000ms),03-16 11:43:51.370  6940  6940 D AndroidRuntime: 
03-16 11:43:51.370  6940  6940 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 11:43:51.370  6940  6940 D AndroidRuntime: CheckJNI is OFF
03-16 11:43:51.380  6940  6940 D AndroidRuntime: readGMSProperty: start
03-16 11:43:51.380  6940  6940 D AndroidRuntime: readGMSProperty: already setted!!
03-16 11:43:51.380  6940  6940 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 11:43:51.380  6940  6940 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 11:43:51.380  6940  6940 D AndroidRuntime: readGMSProperty: end
03-16 11:43:51.380  6940  6940 D AndroidRuntime: addProductProperty: start
03-16 11:43:51.390   289   289 E SMD     : DCD OFF
03-16 11:43:51.560  6940  6940 E AffinityControl: AffinityControl: registerfunction enter
03-16 11:43:51.590  6940  6940 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-16 11:43:51.600  1020  1790 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-16 11:43:51.600  1020  1790 D PackageManager: START PACKAGE DELETE: observer{26805402}
03-16 11:43:51.600  1020  1790 D PackageManager: pkg{<packageName>}
03-16 11:43:51.600  1020  1790 D PackageManager: user{0}
03-16 11:43:51.600  1020  1790 D PackageManager: caller{2000}
03-16 11:43:51.600  1020  1790 D PackageManager: flags{2}
03-16 11:43:51.600  1020  1790 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-16 11:43:51.610  1020  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 11:43:51.600  1020  1790 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 11:43:51.600  1020  1790 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 11:43:51.600  1020  1790 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 11:43:51.610  1020  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 11:43:51.610  1020  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-16 11:43:51.610  1020  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
03-16 11:43:51.610  1020  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-16 11:43:51.610  1020  1058 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-16 11:43:51.630  1020  1045 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-16 11:43:51.630  1020  1045 I ActivityManager: Killing 6279:com.test.thalitest/u0a167 (adj 15): stop com.test.thalitest cause uninstall pkg
03-16 11:43:51.710  1020  1058 W PackageSettings: Skipping PackageSetting{901ec26 com.example.hello/10346} due to missing metadata
03-16 11:43:51.740  1020  1781 W ActivityManager: Spurious death for ProcessRecord{36aa11cb 6279:com.test.thalitest/u0a167}, curProc for 6279: null
03-16 11:43:51.760  1020  1058 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
03-16 11:43:51.780  1020  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-16 11:43:51.810  1020  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-16 11:43:51.820  4038  4038 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 879us total 26.618ms
03-16 11:43:51.840  6013  6013 I art     : Explicit concurrent mark sweep GC freed 356(26KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 749us total 61.798ms
03-16 11:43:51.840  1879  1879 E SamsungIME: mOCRHelper is null
03-16 11:43:51.840  1822  2089 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-16 11:43:51.860  1020  1131 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-16 11:43:51.860  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:43:51.860  1020  1131 V NetworkStats: performPollLocked(flags=0x3)
03-16 11:43:51.870  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
03-16 11:43:51.870  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
03-16 11:43:51.870  1020  1131 V NetworkStats: performPollLocked() took 6ms
03-16 11:43:51.870  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:43:51.880  3682  3682 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 11:43:51 GMT+01:00 2016
03-16 11:43:51.890  1020  3410 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:51.890  1020  3410 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:51.890  1020  3410 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-16 11:43:51.890  3682  3682 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-16 11:43:51.900  1020  1503 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-16 11:43:51.900  1020  1503 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-16 11:43:51.900  1020  1503 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-16 11:43:51.900  1020  1503 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
03-16 11:43:51.900  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:43:51.900  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:43:51.900  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:51.900  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:51.900  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:51.900  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:51.920  6954  6954 E Zygote  : MountEmulatedStorage()
03-16 11:43:51.920  6954  6954 E Zygote  : v2
03-16 11:43:51.920  6954  6954 I libpersona: KNOX_SDCARD checking this for 10090
03-16 11:43:51.920  6954  6954 I libpersona: KNOX_SDCARD not a persona
03-16 11:43:51.920  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:43:51.920  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:43:51.920  1020  1503 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6954 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-16 11:43:51.920  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:43:51.940  1020  1032 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 11:43:51.940  1020  1032 D SecContentProvider2: mCursor = null
03-16 11:43:51.950  3682  3682 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-16 11:43:51.950  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:43:51.950  6954  6954 D ActivityThread: Added TimaKeyStore provider
03-16 11:43:51.960  3682  3682 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-16 11:43:51.970  3682  3682 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-16 11:43:51.980  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-16 11:43:51.990  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
03-16 11:43:51.990  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
03-16 11:43:51.990  1438  1438 D RegisteredServicesCache: empty dynamic service
03-16 11:43:52.000  1020  1020 I art     : Explicit concurrent mark sweep GC freed 57552(6MB) AllocSpace objects, 287(4MB) LOS objects, 33% free, 23MB/35MB, paused 2.932ms total 212.343ms
03-16 11:43:52.000  1020  1058 I art     : WaitForGcToComplete blocked for 146.058ms for cause Explicit
03-16 11:43:52.000  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
03-16 11:43:52.040  1020  1020 D RCPManagerService: PackageReceiver onReceive()
03-16 11:43:52.040  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-16 11:43:52.050  6954  6954 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-16 11:43:52.050  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.050  6954  6954 D elm:15121: ELMEngine.ELMEngine( context ).
03-16 11:43:52.050  6954  6954 D elm:15121: MDMBridge.setEnterpriseBridge()
03-16 11:43:52.050  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.050  1020  1669 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.060  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-16 11:43:52.080  6954  6954 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-16 11:43:52.080  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
03-16 11:43:52.080  6954  6954 D elm:15121: ElmAgentService : onCreate()
03-16 11:43:52.080  6954  6970 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-16 11:43:52.090  6954  6970 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-16 11:43:52.090  6954  6970 D elm:15121: MDMBridge.getInstance()
03-16 11:43:52.090  6954  6970 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-16 11:43:52.090  3682  6953 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-16 11:43:52.090  3682  6953 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
03-16 11:43:52.100  3682  3682 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
03-16 11:43:52.100  6954  6970 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-16 11:43:52.120  6954  6954 D elm:15121: ElmAgentService : onDestroy().
03-16 11:43:52.130  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 11:43:52.130  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 11:43:52.130  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: uID is 10167
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 11:43:52.130  1020  2746 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-16 11:43:52.130  1020  1164 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 11:43:52.130  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-16 11:43:52.140  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 11:43:52.190  1020  1058 I art     : Explicit concurrent mark sweep GC freed 12556(627KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.168ms total 189.684ms
03-16 11:43:52.200  5712  5712 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 11:43:52.200  5712  5712 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 11:43:52.200  5712  5712 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 11:43:52.200  5712  5712 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.220  5880  5880 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-16 11:43:52.220  5880  5880 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
03-16 11:43:52.230  1020  1781 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.230  1020  1781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.230  1020  1781 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
03-16 11:43:52.240  5016  5016 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
03-16 11:43:52.250  1020  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-16 11:43:52.250  1020  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-16 11:43:52.250  1020  1043 W TextServicesManagerService: no available spell checker services found
03-16 11:43:52.260  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.260  5679  5679 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.260  1020  1058 D PackageManager: delete codoeFile: 
03-16 11:43:52.260  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.260  1020  1058 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-16 11:43:52.260  1020  1058 I AASA_removePackage: UID=10167 Target=com.test.thalitest
03-16 11:43:52.260  1020  1058 D PackageManager: result of delete: 1{26805402}
03-16 11:43:52.260  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.270  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.270  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.270  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-16 11:43:52.270  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.270  6940  6940 D AndroidRuntime: Shutting down VM
03-16 11:43:52.280  1020  3410 I TactileAssist: enable value -1
03-16 11:43:52.280  1020  3410 I TactileAssist: internal enable value -1
03-16 11:43:52.280  1020  3410 I TactileAssist: intensity value -1
03-16 11:43:52.280  1020  3410 I TactileAssist: saveAppList value true
03-16 11:43:52.280  5679  6973 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-16 11:43:52.280  5679  6973 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-16 11:43:52.290  1020  3410 I TactileAssist: List of disabled apps :
03-16 11:43:52.300  1020  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 11:43:52.300  1020  1058 D PackageManager: userId{-1}
03-16 11:43:52.300  1020  1058 D PackageManager: andCode{true}
03-16 11:43:52.320  5895  5895 D Compatibility: onReceive() it will make start service
03-16 11:43:52.320  1020  3681 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.320  1020  3681 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.320  1020  3681 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
03-16 11:43:52.330  1020  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.330  1020  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.330  1020  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.330  1020  3946 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.340  5895  6975 D Compatibility: onHandleIntent()
03-16 11:43:52.340  5895  6975 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-16 11:43:52.340  6976  6976 E Zygote  : MountEmulatedStorage()
03-16 11:43:52.340  6976  6976 I libpersona: KNOX_SDCARD checking this for 10055
03-16 11:43:52.340  6976  6976 E Zygote  : v2
03-16 11:43:52.340  6976  6976 I libpersona: KNOX_SDCARD not a persona
03-16 11:43:52.340  5895  6975 D Compatibility: found: 2
03-16 11:43:52.340  5895  6975 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 11:43:52.340  5895  6975 D Compatibility: skipping ResolveInfo{2f8b44fa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-16 11:43:52.340  5895  6975 D Compatibility: considering ResolveInfo{acbaab com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-16 11:43:52.340  5895  6975 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 11:43:52.340  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:43:52.350  5895  6975 D Compatibility: enabling receiver ResolveInfo{35adc508 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-16 11:43:52.350  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:43:52.350  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:43:52.350  1020  3946 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6976 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-16 11:43:52.350  5895  6975 D Compatibility: enabling receiver ResolveInfo{393584a1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 11:43:52.360  5895  6975 D Compatibility: enabling receiver ResolveInfo{1fb8b6c6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-16 11:43:52.360  5895  6975 D Compatibility: enabling receiver ResolveInfo{2c7a5687 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 11:43:52.370  5895  6975 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
03-16 11:43:52.370  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:43:52.380  6976  6976 D ActivityThread: Added TimaKeyStore provider
03-16 11:43:52.380  1020  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-16 11:43:52.380  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.380  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.380  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.390  1020  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 11:43:52.390  1020  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:43:52.390  1020  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:43:52.390  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.390  1020  3410 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.390  1020  3410 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.390  1020  3410 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
03-16 11:43:52.410  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.410  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.410  6976  6976 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-16 11:43:52.410  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.410  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 11:43:52.420  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.420  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.420  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 11:43:52.420  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.420  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-16 11:43:52.430  1020  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 11:43:52.430  1020  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-16 11:43:52.430  1020  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-16 11:43:52.440  6976  6976 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-16 11:43:52.450  6976  6976 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 11:43:52.450  6976  6976 D UserAnalysis: Create SecureDbHelper
03-16 11:43:52.450  6976  6976 D IntelligenceServiceApplication: onCreate()
03-16 11:43:52.450  6976  6976 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
03-16 11:43:52.460  5916  5916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-16 11:43:52.460  1020  1503 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.460  1020  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.460  1020  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-16 11:43:52.460  6976  6976 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 11:43:52.460  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 11:43:52.470  1020  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.470  1020  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.470  1020  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.470  1020  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.470  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 11:43:52.480  6993  6993 E Zygote  : MountEmulatedStorage()
03-16 11:43:52.480  6993  6993 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:43:52.480  6993  6993 E Zygote  : v2
03-16 11:43:52.480  6993  6993 I libpersona: KNOX_SDCARD not a persona
03-16 11:43:52.480  6993  6993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:43:52.480  6993  6993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:43:52.480  1020  1345 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 11:43:52.480  6940  6940 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-16 11:43:52.490  6993  6993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:43:52.500  1020  3681 I ActivityManager: Killing 5327:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-16 11:43:52.510  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
03-16 11:43:52.510  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
03-16 11:43:52.510  6993  6993 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:43:52.510  6993  6993 D ActivityThread: Added TimaKeyStore provider
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
03-16 11:43:52.520  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
03-16 11:43:52.530  6976  6976 D BluetoothAdapter: cancelDiscovery
03-16 11:43:52.530  2631  2642 D BluetoothAdapterProperties: mDiscovering is false
03-16 11:43:52.530  2631  2642 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
03-16 11:43:52.530  6976  6976 D BluetoothAdapter: cancelDiscovery = true
03-16 11:43:52.530  6976  6976 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
03-16 11:43:52.530  6993  6993 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:43:52.540  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 11:43:52.540  6976  6976 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 11:43:52.610  6976  6976 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-16 11:43:52.610  1020  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_5327/cgroup.procs: No such file or directory
03-16 11:43:52.610  6993  6993 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-16 11:43:52.620  1020  1781 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-16 11:43:52.620  1020  1781 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-16 11:43:52.620  5939  5939 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: Error inserting timestamp=1458125032546 message=Predictor: service stopped by removePlaceCategories()
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:43:52.630  6976  6976 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:43:52.630  6976  6976 E UserAnalysis: It failed to insert to dump_log table
03-16 11:43:52.630  5939  5939 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
03-16 11:43:52.640  1020  1669 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:43:52.640  1020  1669 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:43:52.640  1020  1669 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
03-16 11:43:52.650  5939  5939 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
03-16 11:43:52.650  1020  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.650  1020  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.650  1020  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.650  1020  1790 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.660  5939  7010 I FilterInstaller: FilterPackageService : ACTION_REMOVED
03-16 11:43:52.660  5939  7010 D FilterUnInstaller: before removeFromFS
03-16 11:43:52.670  7011  7011 E Zygote  : MountEmulatedStorage()
03-16 11:43:52.670  7011  7011 E Zygote  : v2
03-16 11:43:52.670  7011  7011 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:43:52.670  7011  7011 I libpersona: KNOX_SDCARD not a persona
03-16 11:43:52.670  1020  1790 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 11:43:52.670  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:43:52.670  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.670  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.670  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.670  1020  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:43:52.680  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:43:52.680  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:43:52.690  7021  7021 E Zygote  : MountEmulatedStorage()
03-16 11:43:52.690  7021  7021 E Zygote  : v2
03-16 11:43:52.690  7021  7021 I libpersona: KNOX_SDCARD checking this for 10095
03-16 11:43:52.690  7021  7021 I libpersona: KNOX_SDCARD not a persona
03-16 11:43:52.690  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:43:52.690  7011  7011 D ActivityThread: Added TimaKeyStore provider
03-16 11:43:52.700  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 11:43:52.700  1020  1503 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7021 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-16 11:43:52.700  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 11:43:52.700  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
