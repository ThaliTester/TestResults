#### Test 627544039ea0a99_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
03-17 12:58:35.575   292   292 E SMD     : DCD OFF
03-17 12:58:35.875  6059  6059 D AndroidRuntime: 
03-17 12:58:35.875  6059  6059 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:58:35.875  6059  6059 D AndroidRuntime: CheckJNI is OFF
03-17 12:58:35.875  6059  6059 D AndroidRuntime: readGMSProperty: start
03-17 12:58:35.875  6059  6059 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:58:35.875  6059  6059 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:58:35.875  6059  6059 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:58:35.875  6059  6059 D AndroidRuntime: readGMSProperty: end
03-17 12:58:35.875  6059  6059 D AndroidRuntime: addProductProperty: start
03-17 12:58:36.025  6059  6059 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:58:36.055  6059  6059 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:58:36.065  1017  3782 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:58:36.065  1017  3782 I PersonaManagerService: PersonaId don't exist
03-17 12:58:36.065  1017  3782 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:58:36.065  1017  3782 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
03-17 12:58:36.075  1017  3782 W ActivityManager: mDVFSHelper.acquire()
03-17 12:58:36.085  1017  3782 D FocusedStackFrame: Set to : 0
03-17 12:58:36.085  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:58:36.085  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 12:58:36.095  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:36.095  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:36.095  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:36.095  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:36.105  6071  6071 E Zygote  : MountEmulatedStorage()
03-17 12:58:36.105  6071  6071 E Zygote  : v2
03-17 12:58:36.105  6071  6071 I libpersona: KNOX_SDCARD checking this for 10167
03-17 12:58:36.105  6071  6071 I libpersona: KNOX_SDCARD not a persona
03-17 12:58:36.105  1017  3782 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6071 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:58:36.105  1017  3782 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:58:36.105  1017  3782 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:58:36.105  1017  3782 D InputDispatcher: Focused application set to: xxxx
03-17 12:58:36.105  1017  3782 D InputDispatcher: Focus left window: 1479
03-17 12:58:36.105  6071  6071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:58:36.105  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:58:36.105  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:58:36.105  6059  6059 D AndroidRuntime: Shutting down VM
03-17 12:58:36.105   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-17 12:58:36.115  6071  6071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:58:36.115  6071  6071 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:58:36.135  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:58:36.135  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:58:36.135  6071  6071 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:58:36.135  6071  6071 D ActivityThread: Added TimaKeyStore provider
03-17 12:58:36.145  1017  3803 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:58:36.145  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 12:58:36.155  1017  3803 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:58:36.185  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 12:58:36.215   259  1098 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 12:58:36.215   259   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 12:58:36.215  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{20b293b token=android.os.BinderProxy@337ba19b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 12:58:36.215  1479  1479 D Launcher: onTrimMemory. Level: 20
03-17 12:58:36.275  6071  6071 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 12:58:36.295  6071  6071 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5880-5882)
03-17 12:58:36.295  6071  6071 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:58:36.315  6059  6059 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 12:58:36.325  6071  6071 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e8cdfe0}
03-17 12:58:36.325  6071  6071 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:58:36.325  6071  6071 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:58:36.355  6071  6071 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:58:36.355  6071  6071 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-17 12:58:36.355  6071  6071 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:58:36.375  6071  6071 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:58:36.375  6071  6071 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:58:36.375  6071  6071 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:58:36.375  6071  6071 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:58:36.375  6071  6071 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:58:36.375  6071  6071 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:58:36.375  6071  6071 I Adreno-EGL: Local Branch: 
03-17 12:58:36.375  6071  6071 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:58:36.375  6071  6071 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:58:36.375  6071  6071 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:58:36.605  6071  6071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:58:36.615  6071  6071 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:58:36.625  6071  6071 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 12:58:36.625  6071  6071 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 12:58:36.625  6071  6071 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 12:58:36.635  6071  6071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:58:36.635  6071  6071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:58:36.675  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{1280d7c u0 com.test.thalitest/.MainActivity t23}
,03-17 12:58:36.695  6071  6112 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:58:36.705  1017  1138 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 12:58:36.705  1017  1138 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:58:36.705  1017  1138 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:58:36.705  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 12:58:36.705  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:58:36.715  6071  6099 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 12:58:36.715  6071  6071 V ActivityThread: updateVisibility : ActivityRecord{33e2e228 token=android.os.BinderProxy@1e04951a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-17 12:58:36.715  6071  6071 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-17 12:58:36.715  6071  6071 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 12:58:36.735   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-17 12:58:36.745  1017  1029 D InputDispatcher: Focus entered window: 6071
,03-17 12:58:36.745  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 12:58:36.745  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:58:36.745  6071  6071 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:58:36.745  6071  6112 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 12:58:36.755  6071  6112 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 12:58:36.755  6071  6112 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:58:36.785  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:58:36.785  1172  1172 I StatusBar: Icon Only
,03-17 12:58:36.785  1172  1172 D PanelView: There is/are notification(s) 
,03-17 12:58:36.795  1017  6114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:58:36.795  1017  1048 I ActivityManager: Displayed Component not be shown by security: +629ms (total +1m29s119ms)
,03-17 12:58:36.805  1017  1048 W ActivityManager: mDVFSHelper.release()
03-17 12:58:36.805  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1280d7c u0 com.test.thalitest/.MainActivity t23} time:206390
,03-17 12:58:36.805  6071  6071 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-17 12:58:36.805  6071  6071 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e04951a time:206398
03-17 12:58:36.805   259   447 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,03-17 12:58:36.815   259  1098 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
03-17 12:58:36.815  1839  1839 I SamsungIME: getCurrentCandidateView
,03-17 12:58:36.875  1839  1839 D SamsungIME: Dismiss ExpandCandiate
,03-17 12:58:36.935  1839  1839 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:58:36.995  1839  1839 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:58:37.015  1839  1839 I SamsungIME: KeybaordView init() : load resources
,03-17 12:58:37.045  6071  6071 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6071
,03-17 12:58:37.055  1839  1839 I SamsungIME: getCurrentKeyboard
03-17 12:58:37.055  1839  1839 I SamsungIME: getTextKeyboard
,03-17 12:58:37.065  1839  1839 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 12:58:37.195  6071  6071 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:58:37.275  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:58:37.275  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 12:58:37.275  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 12:58:37.275  1017  1029 D BatteryService: stay LED for fully charged
03-17 12:58:37.275  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:58:37.275  1017  1017 I MotionRecognitionService: Plugged
,03-17 12:58:37.275  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:58:37.275  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:58:37.275  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:58:37.275  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 12:58:37.285  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:58:37.285  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 12:58:37.285  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:58:37.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:58:37.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:58:37.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:58:37.305  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 12:58:37.305  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 12:58:37.415  6071  6117 D jxcore_app_log: JniHelper::setJavaVM(0xb89f6448), pthread_self() = -1191865312
,03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 12:58:37.425  6071  6117 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9be6b1 added. We now have 1 listener(s)
,03-17 12:58:37.425  6071  6117 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41,
,03-17 12:58:37.435  6071  6117 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"},
,03-17 12:58:37.435  6071  6117 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-17 12:58:37.435  6071  6117 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false,
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 12:58:37.435  6071  6117 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37153f04 added. We now have 1 listener(s)
,03-17 12:58:37.435  6071  6117 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:58:37.445  6071  6117 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 12:58:37.445  6071  6117 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
03-17 12:58:37.445  6071  6117 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 12:58:37.445  6071  6117 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 12:58:37.445  6071  6117 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 12:58:37.445  6071  6117 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-17 12:58:37.455  6071  6117 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:58:37.455  6071  6117 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:58:37.455  6071  6117 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 12:58:37.455  6071  6117 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:58:37.455  6071  6071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:58:37.465  6071  6071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:58:37.505  6071  6071 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:58:38.025  6071  6124 W jxcore-log: Initializing JXcore engine
03-17 12:58:38.025  6071  6124 W jxcore-log: JXcore engine is ready
,03-17 12:58:38.075  1837  1837 E audit   : type=1400 msg=audit(1458215918.075:205): avc:  denied  { ioctl } for  pid=6124 comm="Thread-1050" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 12:58:38.075  1837  1837 E audit   :  SEPF_SM-A300FU_5.0.2_0027,
03-17 12:58:38.075  1837  1837 E audit   : type=1300 msg=audit(1458215918.075:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9e7828f8 items=0 ppid=309 ppcomm=main pid=6124 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1050" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 12:58:38.075  1837  1837 E audit   : type=1320 msg=audit(1458215918.075:205): 
,03-17 12:58:38.085  6071  6124 W jxcore-log: Starting JXcore engine
,03-17 12:58:38.185  6071  6124 W jxcore-log: Platform android
03-17 12:58:38.185  6071  6124 W jxcore-log: 
03-17 12:58:38.185  6071  6124 W jxcore-log: Process ARCH arm
03-17 12:58:38.185  6071  6124 W jxcore-log: 
,03-17 12:58:38.395  6071  6124 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:58:38.395  6071  6124 I jxcore-log: 
,03-17 12:58:38.395  6071  6124 W jxcore-log: JXcore engine is started
,03-17 12:58:38.405  6071  6117 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:58:38.415  6071  6124 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:58:38.415  6071  6124 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:58:38.425  6071  6071 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 12:58:38.425  1017  1029 D FocusedStackFrame: Set to : 0
,03-17 12:58:38.425  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 12:58:38.425  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 12:58:38.425  1017  1029 D InputDispatcher: Focused application set to: xxxx
,03-17 12:58:38.425  1017  1029 D InputDispatcher: Focus left window: 6071
,03-17 12:58:38.425  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 12:58:38.425  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:58:38.435  1017  1029 I ActivityManager: Killing 5194:com.google.android.gm/u0a99 (adj 15): empty #31
,03-17 12:58:38.445   259   450 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-17 12:58:38.445   259  1098 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-17 12:58:38.455  1017  1431 W ActivityManager: mDVFSHelper.acquire()
,03-17 12:58:38.455  1017  1431 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:58:38.465  6071  6071 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1c035722 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:58:38.465  6071  6071 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1c035722 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:58:38.465  6071  6071 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2e573ced that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:58:38.465  6071  6071 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2e573ced that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:58:38.465  6071  6071 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:58:38.475  1479  1479 D Launcher: onRestart, Launcher: 359067967
,03-17 12:58:38.475  1479  1479 D Launcher: onStart, Launcher: 359067967
,03-17 12:58:38.485  1479  1479 D Launcher.HomeView: onStart
03-17 12:58:38.485  1479  1479 D Launcher: onResume, Launcher: 359067967
03-17 12:58:38.485  1017  3803 D SettingsProvider: name = kids_home_mode
03-17 12:58:38.485  1017  3803 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:58:38.485  1017  3803 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:58:38.485  1017  3803 D SettingsProvider: selectionArgs: false
03-17 12:58:38.485  1017  3803 D SettingsProvider: selectionArgs: 10006
03-17 12:58:38.485  1017  3803 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:58:38.485  1017  3803 D SettingsProvider: ret = -1
,03-17 12:58:38.485  1479  1479 D Launcher.HomeView: onResume
,03-17 12:58:38.485  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:58:38.495  1479  1479 D MenuAppsGridFragment: onResume
,03-17 12:58:38.495  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:58:38.495  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.495  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
03-17 12:58:38.495  1017  2111 D ActivityManager: handle home activity for 0
03-17 12:58:38.495  1017  2111 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 12:58:38.495  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 12:58:38.495  1017  2111 D KnoxTimeoutHandler: post home show event for user 0
03-17 12:58:38.495  1017  2111 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 12:58:38.495  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 12:58:38.495  1017  2111 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:58:38.495  1017  2111 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:58:38.495  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:58:38.495  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:58:38.495  1017  1431 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-17 12:58:38.495  1479  1479 D Launcher.HomeView: onPause
,03-17 12:58:38.495  1017  1431 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-17 12:58:38.505  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:58:38.505  1017  1431 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.505  1017  1431 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:58:38.505  1017  1431 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-17 12:58:38.505  4985  4985 D GalleryCacheReady: Receive : home resume
,03-17 12:58:38.505  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:58:38.505  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.515  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 12:58:38.515  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:58:38.515  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.515  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-17 12:58:38.515  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.515  2537  2537 D Recents_RecreateReceiver: onReceive by home
,03-17 12:58:38.515  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.515  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 12:58:38.525  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:58:38.525  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.525  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-17 12:58:38.525  5936  5936 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-17 12:58:38.525  5601  5601 D Mms/UIEventReceiver: ui event
,03-17 12:58:38.525   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-17 12:58:38.525  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:58:38.535  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:58:38.535  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.535  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.535  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-17 12:58:38.535  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:38.535  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:38.535  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:58:38.535  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:58:38.535  1017  3912 D InputDispatcher: Focus entered window: 1479
,03-17 12:58:38.545  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:58:38.545  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:58:38.545  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:58:38.545  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{20b293b token=android.os.BinderProxy@337ba19b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-17 12:58:38.545  1479  1479 D Launcher.HomeView: onStop
,03-17 12:58:38.545  1017  1431 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:58:38.555  1017  6129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:58:38.555  6071  6071 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:58:38.555  1839  1839 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 12:58:38.565  6132  6132 E Zygote  : MountEmulatedStorage(),
03-17 12:58:38.565  6132  6132 E Zygote  : v2
03-17 12:58:38.565  6132  6132 I libpersona: KNOX_SDCARD checking this for 10135
03-17 12:58:38.565  6132  6132 I libpersona: KNOX_SDCARD not a persona
,03-17 12:58:38.565  6132  6132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:58:38.565  6132  6132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:58:38.565  1017  1138 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6132 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 12:58:38.565  6132  6132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:58:38.565  1172  1172 I StatusBar: Icon Only
,03-17 12:58:38.565  1172  1172 D PanelView: There is/are notification(s) ,
03-17 12:58:38.575  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.575  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.575  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-17 12:58:38.575   292   292 E SMD     : DCD OFF
,03-17 12:58:38.585  1017  2111 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:58:38.595  6132  6132 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:58:38.595  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.595  6132  6132 D ActivityThread: Added TimaKeyStore provider
,03-17 12:58:38.595  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.595  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 12:58:38.595  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@337ba19b time:208186
03-17 12:58:38.595  1017  1138 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,03-17 12:58:38.615  1017  1048 W ActivityManager: mDVFSHelper.release()
,03-17 12:58:38.615  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cd9da55 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:208204
,03-17 12:58:38.615  6132  6132 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:58:38.615  6132  6132 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:58:38.615  6132  6132 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 12:58:38.615  6132  6132 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:58:38.615  6132  6132 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:58:38.645  1017  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_5194/cgroup.procs: No such file or directory
,03-17 12:58:38.655  1017  3803 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 12:58:38.655  1017  3803 I ActivityManager: Killing 4155:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-17 12:58:38.655  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:58:38.655  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:58:38.655  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 12:58:38.655  5936  5936 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 12:58:38.705  1017  1042 W libprocessgroup: failed to open /acct/uid_10032/pid_4155/cgroup.procs: No such file or directory
,03-17 12:58:38.735  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 12:58:39.185  1017  2764 D SSRM:n  : SIOP:: AP = 290
,03-17 12:58:41.575   292   292 E SMD     : DCD OFF
,03-17 12:58:43.545   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 12:58:43.545   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 12:58:44.575   292   292 E SMD     : DCD OFF
,03-17 12:58:46.085  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 12:58:46.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:58:47.335  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 12:58:47.335  1017  3803 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 12:58:47.335  1017  3803 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 12:58:47.335  1017  3803 D BatteryService: stay LED for fully charged
03-17 12:58:47.335  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 12:58:47.335  1017  1017 I MotionRecognitionService: Plugged
03-17 12:58:47.335  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-17 12:58:47.335  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 12:58:47.335  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 12:58:47.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 12:58:47.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 12:58:47.345  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 12:58:47.345  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
03-17 12:58:47.355  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:58:47.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:58:47.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:58:47.365  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 12:58:47.365  1172  1172 D SViewCoverView: level :100 plugged : 2
03-17 12:58:47.585   292   292 E SMD     : DCD OFF
,03-17 12:58:49.025  1017  1050 I PowerManagerService: [PWL] Off : 140s ago
,03-17 12:58:49.205  1017  2764 D SSRM:n  : SIOP:: AP = 270
,03-17 12:58:50.585   292   292 E SMD     : DCD OFF,
,03-17 12:58:53.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:58:53.585   292   292 E SMD     : DCD OFF,
,03-17 12:58:54.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:58:55.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:58:56.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:58:56.585   292   292 E SMD     : DCD OFF
,03-17 12:58:57.395  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:58:57.395  1017  1431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 12:58:57.395  1017  1431 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 12:58:57.395  1017  1431 D BatteryService: stay LED for fully charged
,03-17 12:58:57.395  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:58:57.395  1017  1017 I MotionRecognitionService: Plugged
,03-17 12:58:57.395  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:58:57.395  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:58:57.405  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:58:57.405  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 12:58:57.405  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:58:57.415  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 12:58:57.415  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:58:57.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:58:57.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:58:57.425  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:58:57.425  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 12:58:57.425  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 12:58:57.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:58:58.455  1017  1328 E Watchdog: !@Sync 7
,03-17 12:58:58.545   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-17 12:58:59.225  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:58:59.585   292   292 E SMD     : DCD OFF
,03-17 12:58:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 12:59:02.585   292   292 E SMD     : DCD OFF
,03-17 12:59:03.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:04.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:05.545   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:05.595   292   292 E SMD     : DCD OFF
,03-17 12:59:06.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:06.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:59:07.445  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:07.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:08.555   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-17 12:59:08.595   292   292 E SMD     : DCD OFF,
,03-17 12:59:09.265  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:11.595   292   292 E SMD     : DCD OFF
,03-17 12:59:14.595   292   292 E SMD     : DCD OFF
,03-17 12:59:17.515  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:17.595   292   292 E SMD     : DCD OFF
,03-17 12:59:18.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:19.305  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:19.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:20.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:20.595   292   292 E SMD     : DCD OFF
,03-17 12:59:21.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:22.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 12:59:23.555   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 12:59:23.605   292   292 E SMD     : DCD OFF,
,03-17 12:59:26.605   292   292 E SMD     : DCD OFF
,03-17 12:59:26.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:59:27.575  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:28.455  1017  1328 E Watchdog: !@Sync 8
,03-17 12:59:29.035  1017  1050 I PowerManagerService: [PWL] Off : 180s ago
,03-17 12:59:29.355  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:29.605   292   292 E SMD     : DCD OFF
,03-17 12:59:32.605   292   292 E SMD     : DCD OFF
,03-17 12:59:35.605   292   292 E SMD     : DCD OFF
,03-17 12:59:37.635  1017  1363 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:38.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:38.605   292   292 E SMD     : DCD OFF
,03-17 12:59:39.395  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:39.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:40.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:41.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:59:41.615   292   292 E SMD     : DCD OFF
,03-17 12:59:42.555   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 12:59:43.555   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 12:59:44.615   292   292 E SMD     : DCD OFF
,03-17 12:59:46.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:59:47.615   292   292 E SMD     : DCD OFF
,03-17 12:59:47.695  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:49.425  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:50.615   292   292 E SMD     : DCD OFF
,03-17 12:59:53.615   292   292 E SMD     : DCD OFF
,03-17 12:59:56.615   292   292 E SMD     : DCD OFF
,03-17 12:59:57.675  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 12:59:57.685  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 12:59:57.685  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 12:59:57.695  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 12:59:57.695  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 12:59:57.715  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:59:57.715  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-17 12:59:57.715  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 12:59:57.745  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:59:57.755  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:59:57.755  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:59:57.765  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 12:59:57.765  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:59:57.775  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:59:57.865  5964  6180 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 12:59:58.045  1017  3413 I art     : Explicit concurrent mark sweep GC freed 57980(3MB) AllocSpace objects, 81(1301KB) LOS objects, 33% free, 23MB/35MB, paused 2.347ms total 170.911ms
,03-17 12:59:58.065  5964  6181 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 12:59:58.065  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:59:58.065  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.065  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.085  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:59:58.085  1017  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.085  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.105  1716  1805 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 12:59:58.105  1716  1805 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 12:59:58.105  1716  1805 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 12:59:58.105  1716  1805 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 12:59:58.105  1716  1805 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:59:58.115  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:59:58.115  1017  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.115  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.135  1017  1363 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 12:59:58.135  1017  1363 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 12:59:58.145  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 12:59:58.145  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 12:59:58.145  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:59:58.145  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:59:58.145  1172  1172 I PhoneStatusBar: Icon Only
03-17 12:59:58.145  1172  1172 I StatusBar: Icon Only
03-17 12:59:58.145  1172  1172 D PanelView: There is/are notification(s) 
03-17 12:59:58.145  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:59:58.155  1172  1172 D PersonaManager: isKioskContainerExistOnDevice,
03-17 12:59:58.155  1172  1172 I PhoneStatusBar: Icon Only
03-17 12:59:58.155  1172  1172 I StatusBar: Icon Only
03-17 12:59:58.155  1172  1172 D PanelView: There is/are notification(s) 
03-17 12:59:58.155  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:59:58.155  1017  3782 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:59:58.155  1017  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.155  1017  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.165  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:59:58.165  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.165  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.185  1716  1727 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 12:59:58.185  1716  1727 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 12:59:58.185  1716  1727 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 12:59:58.185  1716  1727 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 12:59:58.195  1716  1727 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:59:58.195  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:59:58.195  1017  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 12:59:58.195  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:59:58.205  5964  6181 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 12:59:58.205  5964  6180 E BooksSync: Soft error
03-17 12:59:58.205  5964  6180 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 12:59:58.205  5964  6180 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 12:59:58.205  5964  6180 E BooksSync: Sync error
03-17 12:59:58.205  5964  6180 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 12:59:58.205  5964  6180 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 12:59:58.205  5964  6180 I BooksSync: Finished books sync
,03-17 12:59:58.215  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 287269, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 12:59:58.225  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 12:59:58.265  1017  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 12:59:58.275  1017  1029 D SecContentProvider2: mCursor = null
,03-17 12:59:58.455  1017  1328 E Watchdog: !@Sync 9
,03-17 12:59:59.445  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 12:59:59.625   292   292 E SMD     : DCD OFF
,03-17 12:59:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:00:02.625   292   292 E SMD     : DCD OFF
,03-17 13:00:03.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:04.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:00:05.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:00:05.625   292   292 E SMD     : DCD OFF
,03-17 13:00:06.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:06.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:00:07.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:07.835  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:00:08.565   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 13:00:08.625   292   292 E SMD     : DCD OFF
,03-17 13:00:09.455  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:11.625   292   292 E SMD     : DCD OFF
,03-17 13:00:14.045  1017  1050 I PowerManagerService: [PWL] Off : 225s ago
,03-17 13:00:14.625   292   292 E SMD     : DCD OFF
,03-17 13:00:17.635   292   292 E SMD     : DCD OFF
,03-17 13:00:17.885  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:00:19.505  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:20.635   292   292 E SMD     : DCD OFF
,03-17 13:00:23.635   292   292 E SMD     : DCD OFF
,03-17 13:00:25.435  1017  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:00:25.435  1017  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-17 13:00:25.435  1017  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:00:25.445  1017  1086 I TLC_TIMA_PKM_initialize: initializing...,
03-17 13:00:25.445  1017  1086 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-17 13:00:25.445  1017  1086 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
03-17 13:00:25.445  1017  1086 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15,
03-17 13:00:25.445  1017  1086 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
03-17 13:00:25.445  1017  1086 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
03-17 13:00:25.445  1017  1086 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,03-17 13:00:25.445  1017  1086 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080,
03-17 13:00:25.445  1017  1086 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
03-17 13:00:25.445  1017  1086 D QSEECOMAPI: : App is not loaded in QSEE,
,03-17 13:00:25.475  1017  1086 D QSEECOMAPI: : Loaded image: APP id = 11
,03-17 13:00:25.485  1017  1086 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,03-17 13:00:25.485  1017  1086 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-17 13:00:26.635   292   292 E SMD     : DCD OFF
,03-17 13:00:26.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:00:27.445  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:00:27.445  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:00:27.455  1017  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:00:27.455  1017  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:00:27.865  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:00:27.875  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:00:27.875  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:00:27.875  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:00:27.885  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:00:27.905  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:00:27.905  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:00:27.905  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:00:27.935  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:00:27.945  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:00:27.945  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:00:27.955  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:00:27.965  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:00:27.975  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:00:28.455  1017  1328 E Watchdog: !@Sync 10
,03-17 13:00:29.545  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:29.635   292   292 E SMD     : DCD OFF
,03-17 13:00:32.635   292   292 E SMD     : DCD OFF
,03-17 13:00:33.565   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
03-17 13:00:33.565   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:00:35.645   292   292 E SMD     : DCD OFF
,03-17 13:00:38.025  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:00:38.645   292   292 E SMD     : DCD OFF
,03-17 13:00:39.585  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:41.645   292   292 E SMD     : DCD OFF
,03-17 13:00:44.645   292   292 E SMD     : DCD OFF
,03-17 13:00:46.935  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:00:47.645   292   292 E SMD     : DCD OFF
,03-17 13:00:48.085  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:00:48.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:49.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:49.605  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:50.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:50.645   292   292 E SMD     : DCD OFF
,03-17 13:00:51.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:52.565   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:00:53.565   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-17 13:00:53.655   292   292 E SMD     : DCD OFF
,03-17 13:00:56.655   292   292 E SMD     : DCD OFF
,03-17 13:00:58.145  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:00:58.455  1017  1328 E Watchdog: !@Sync 11
,03-17 13:00:58.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:59.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:00:59.625  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:00:59.655   292   292 E SMD     : DCD OFF
,03-17 13:00:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:01:00.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:01.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:02.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:01:02.655   292   292 E SMD     : DCD OFF
,03-17 13:01:03.575   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-17 13:01:04.085  1017  1050 I PowerManagerService: [PWL] Off : 275s ago
,03-17 13:01:05.655   292   292 E SMD     : DCD OFF
,03-17 13:01:06.615  1716  1716 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:01:06.625  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:01:06.625  1017  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:01:06.625  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:01:06.635  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:01:06.635  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:01:06.635  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:01:06.655  1716  1727 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-17 13:01:06.655  1716  1727 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:01:06.655  1716  1727 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:01:06.655  1716  1727 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:01:06.665  1716  1727 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:01:06.665  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:01:06.665  1017  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:01:06.665  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:01:06.695  1017  1488 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 13:01:06.695  1017  1488 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:01:06.695  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:01:06.705  1716  1727 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-17 13:01:06.705  1716  1727 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:461)
,03-17 13:01:06.705  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-17 13:01:06.705  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:01:06.705  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:01:06.705  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:01:06.705  1172  1172 I StatusBar: Icon Only
03-17 13:01:06.705  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:01:06.705  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 13:01:06.705  5347  5380 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-17 13:01:06.705  5347  5380 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-17 13:01:06.705  5347  5380 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
03-17 13:01:06.705  5347  5380 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-17 13:01:06.705  5347  5380 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
03-17 13:01:06.705  5347  5380 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-17 13:01:06.705  5347  5380 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:461)
03-17 13:01:06.705  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:01:06.705  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:01:06.705  1172  1172 I StatusBar: Icon Only
03-17 13:01:06.705  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:01:06.705  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:01:06.725  5347  5380 W System  : Ignoring header User-Agent because its value was null.
,03-17 13:01:06.735  5347  5380 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 13:01:06.735  5347  5380 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 13:01:06.735  5347  5380 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 13:01:06.735  5347  5380 I System.out: (HTTPLog)-Thread-908-226791268: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 13:01:06.735  5347  5380 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:01:06.735   282   973 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:01:06.735   282   973 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,03-17 13:01:06.735  5347  5380 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:01:06.775  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:01:06.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:01:08.215  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:01:08.655   292   292 E SMD     : DCD OFF
,03-17 13:01:09.645  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:01:11.665   292   292 E SMD     : DCD OFF
,03-17 13:01:13.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:14.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:14.665   292   292 E SMD     : DCD OFF
,03-17 13:01:15.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:16.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:17.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:17.665   292   292 E SMD     : DCD OFF
,03-17 13:01:18.275  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:01:18.275  1017  1543 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:01:18.275  1017  1543 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:01:18.275  1017  1543 D BatteryService: stay LED for fully charged
03-17 13:01:18.275  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:01:18.275  1017  1017 I MotionRecognitionService: Plugged
03-17 13:01:18.275  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:01:18.275  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:01:18.275  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:01:18.285  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:01:18.285  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:01:18.295  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:01:18.295  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:01:18.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:01:18.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:01:18.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:01:18.305  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:01:18.305  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:01:18.575   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:01:19.655  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:01:20.665   292   292 E SMD     : DCD OFF
,03-17 13:01:23.665   292   292 E SMD     : DCD OFF
,03-17 13:01:26.675   292   292 E SMD     : DCD OFF
,03-17 13:01:26.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:01:28.335  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:01:28.455  1017  1328 E Watchdog: !@Sync 12
,03-17 13:01:29.675   292   292 E SMD     : DCD OFF
,03-17 13:01:29.695  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:01:32.675   292   292 E SMD     : DCD OFF,
,03-17 13:01:33.575   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:34.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:35.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:35.675   292   292 E SMD     : DCD OFF
,03-17 13:01:36.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:01:37.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:38.395  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:01:38.585   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-17 13:01:38.675   292   292 E SMD     : DCD OFF,
,03-17 13:01:39.725  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:01:41.685   292   292 E SMD     : DCD OFF,
,03-17 13:01:44.685   292   292 E SMD     : DCD OFF,
,03-17 13:01:46.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:01:47.685   292   292 E SMD     : DCD OFF,
,03-17 13:01:48.455  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:01:49.765  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:01:50.685   292   292 E SMD     : DCD OFF
,03-17 13:01:53.685   292   292 E SMD     : DCD OFF
,03-17 13:01:56.695   292   292 E SMD     : DCD OFF,
,03-17 13:01:58.455  1017  1328 E Watchdog: !@Sync 13
,03-17 13:01:58.515  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:01:58.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:59.125  1017  1050 I PowerManagerService: [PWL] Off : 330s ago
,03-17 13:01:59.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:01:59.695   292   292 E SMD     : DCD OFF
,03-17 13:01:59.785  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:02:00.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:01.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:02.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:02.695   292   292 E SMD     : DCD OFF
,03-17 13:02:03.585   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-17 13:02:05.695   292   292 E SMD     : DCD OFF
,03-17 13:02:06.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:02:08.575  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:02:08.695   292   292 E SMD     : DCD OFF
,03-17 13:02:09.795  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:02:11.695   292   292 E SMD     : DCD OFF
,03-17 13:02:14.705   292   292 E SMD     : DCD OFF
,03-17 13:02:17.705   292   292 E SMD     : DCD OFF
,03-17 13:02:18.635  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:02:19.835  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:02:20.705   292   292 E SMD     : DCD OFF
,03-17 13:02:23.705   292   292 E SMD     : DCD OFF
,03-17 13:02:26.705   292   292 E SMD     : DCD OFF
,03-17 13:02:26.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:02:28.455  1017  1328 E Watchdog: !@Sync 14
,03-17 13:02:28.585   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-17 13:02:28.585   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:02:28.705  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:02:29.705   292   292 E SMD     : DCD OFF
,03-17 13:02:29.875  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:02:32.715   292   292 E SMD     : DCD OFF
,03-17 13:02:35.715   292   292 E SMD     : DCD OFF
,03-17 13:02:38.715   292   292 E SMD     : DCD OFF
,03-17 13:02:38.765  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:02:39.885  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:02:41.715   292   292 E SMD     : DCD OFF
,03-17 13:02:44.715   292   292 E SMD     : DCD OFF
,03-17 13:02:46.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:02:47.715   292   292 E SMD     : DCD OFF
,03-17 13:02:48.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:02:48.835  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:02:49.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:49.935  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:02:50.585   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:50.725   292   292 E SMD     : DCD OFF
,03-17 13:02:51.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:02:52.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:02:53.595   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-17 13:02:53.725   292   292 E SMD     : DCD OFF
,03-17 13:02:56.725   292   292 E SMD     : DCD OFF
,03-17 13:02:58.455  1017  1328 E Watchdog: !@Sync 15
,03-17 13:02:58.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:02:58.895  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:02:59.185  1017  1050 I PowerManagerService: [PWL] Off : 390s ago
,03-17 13:02:59.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:02:59.725   292   292 E SMD     : DCD OFF
,03-17 13:02:59.945  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:00.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:01.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:03:02.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:03:02.725   292   292 E SMD     : DCD OFF
,03-17 13:03:03.595   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-17 13:03:05.725   292   292 E SMD     : DCD OFF
,03-17 13:03:06.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:03:08.735   292   292 E SMD     : DCD OFF
,03-17 13:03:08.955  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:03:09.965  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:11.735   292   292 E SMD     : DCD OFF
,03-17 13:03:13.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:14.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:14.735   292   292 E SMD     : DCD OFF
,03-17 13:03:15.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:16.595   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:16.615   316   316 I bootchecker: bootchecker wake up!!
,03-17 13:03:17.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:03:17.735   292   292 E SMD     : DCD OFF,
,03-17 13:03:18.605   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-17 13:03:19.015  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:03:20.005  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:20.735   292   292 E SMD     : DCD OFF
,03-17 13:03:23.735   292   292 E SMD     : DCD OFF
,03-17 13:03:26.745   292   292 E SMD     : DCD OFF
,03-17 13:03:26.945  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:03:28.455  1017  1328 E Watchdog: !@Sync 16
,03-17 13:03:29.085  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:03:29.745   292   292 E SMD     : DCD OFF
,03-17 13:03:30.025  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:32.745   292   292 E SMD     : DCD OFF
,03-17 13:03:33.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:34.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:35.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:35.745   292   292 E SMD     : DCD OFF
,03-17 13:03:36.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:37.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 13:03:38.605   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-17 13:03:38.745   292   292 E SMD     : DCD OFF
,03-17 13:03:39.145  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:03:39.145  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:03:39.145  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:03:39.145  1017  1030 D BatteryService: stay LED for fully charged
03-17 13:03:39.145  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:03:39.145  1017  1017 I MotionRecognitionService: Plugged
03-17 13:03:39.145  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:03:39.145  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:03:39.145  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:03:39.145  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:03:39.145  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-17 13:03:39.155  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:03:39.155  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:03:39.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:03:39.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:03:39.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:03:39.175  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:03:39.175  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:03:40.045  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:41.745   292   292 E SMD     : DCD OFF
,03-17 13:03:44.745   292   292 E SMD     : DCD OFF
,03-17 13:03:46.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:03:47.755   292   292 E SMD     : DCD OFF
,03-17 13:03:49.205  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:03:50.055  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:03:50.755   292   292 E SMD     : DCD OFF
,03-17 13:03:53.755   292   292 E SMD     : DCD OFF,
,03-17 13:03:56.755   292   292 E SMD     : DCD OFF,
,03-17 13:03:58.465  1017  1328 E Watchdog: !@Sync 17
,03-17 13:03:58.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:59.265  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:03:59.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:03:59.755   292   292 E SMD     : DCD OFF
,03-17 13:03:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:03:59.995  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=529581 batch.start=549077
,03-17 13:04:00.075  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:00.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:04:01.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:04:02.605   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:04:02.755   292   292 E SMD     : DCD OFF,
,03-17 13:04:03.605   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-17 13:04:04.185  1017  1050 I PowerManagerService: [PWL] Off : 455s ago
,03-17 13:04:05.765   292   292 E SMD     : DCD OFF
,03-17 13:04:06.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:04:08.765   292   292 E SMD     : DCD OFF,
,03-17 13:04:09.325  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:10.115  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:11.765   292   292 E SMD     : DCD OFF,
,03-17 13:04:14.765   292   292 E SMD     : DCD OFF
,03-17 13:04:17.765   292   292 E SMD     : DCD OFF
,03-17 13:04:19.385  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:19.485  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:04:19.495  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:04:19.495  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
03-17 13:04:19.495  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:04:19.505  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:04:19.505  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:04:19.505  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-17 13:04:19.505  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:04:19.545  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:04:19.545  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:04:19.555  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:04:19.575  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:04:19.575  5964  6291 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 13:04:19.585  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:04:19.605  5964  6292 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 13:04:19.605  1017  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.605  1017  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:04:19.605  1017  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.625  1017  3782 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.625  1017  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:04:19.625  1017  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.635  1716  1809 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:04:19.635  1716  1809 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-17 13:04:19.645  1716  1809 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:04:19.645  1716  1809 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:04:19.645  1716  1809 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:04:19.645  1017  1431 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.655  1017  1431 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:04:19.655  1017  1431 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.675  1017  1431 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:04:19.675  1017  1431 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:04:19.675  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:04:19.685  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:04:19.685  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:04:19.685  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:04:19.685  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:04:19.685  1172  1172 I StatusBar: Icon Only
03-17 13:04:19.685  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:04:19.685  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:04:19.685  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:04:19.685  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:04:19.685  1172  1172 I StatusBar: Icon Only
03-17 13:04:19.685  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:04:19.685  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:04:19.695  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.695  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:04:19.695  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.705  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.705  1017  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:04:19.705  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.725  1716  3409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:04:19.725  1716  3409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:04:19.725  1716  3409 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:04:19.725  1716  3409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:04:19.735  1716  3409 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:04:19.735  1017  3782 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:04:19.735  1017  3782 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:04:19.735  1017  3782 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:04:19.755  5964  6292 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 13:04:19.755  5964  6291 E BooksSync: Soft error
03-17 13:04:19.755  5964  6291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:04:19.755  5964  6291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-17 13:04:19.755  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
03-17 13:04:19.755  5964  6291 E BooksSync: Sync error
03-17 13:04:19.755  5964  6291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:04:19.755  5964  6291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:04:19.755  5964  6291 I BooksSync: Finished books sync
,03-17 13:04:19.765  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 549077, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 13:04:19.825  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:04:19.825  1017  1030 D SecContentProvider2: mCursor = null
,03-17 13:04:20.155  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:20.765   292   292 E SMD     : DCD OFF
,03-17 13:04:23.775   292   292 E SMD     : DCD OFF
,03-17 13:04:26.775   292   292 E SMD     : DCD OFF,
,03-17 13:04:26.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 13:04:28.465  1017  1328 E Watchdog: !@Sync 18,
,03-17 13:04:28.605   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-17 13:04:28.605   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-17 13:04:29.445  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:29.775   292   292 E SMD     : DCD OFF,
,03-17 13:04:30.175  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:32.775   292   292 E SMD     : DCD OFF,
,03-17 13:04:35.775   292   292 E SMD     : DCD OFF
,03-17 13:04:38.775   292   292 E SMD     : DCD OFF,
,03-17 13:04:39.505  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:40.185  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:41.785   292   292 E SMD     : DCD OFF,
,03-17 13:04:44.785   292   292 E SMD     : DCD OFF,
,03-17 13:04:46.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:04:47.785   292   292 E SMD     : DCD OFF,
,03-17 13:04:49.565  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:04:49.575  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:50.205  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:04:50.785   292   292 E SMD     : DCD OFF,
,03-17 13:04:53.615   322   322 I Atfwd_Daemon: Stop the daemon....,
,03-17 13:04:53.795   292   292 E SMD     : DCD OFF,
,03-17 13:04:56.795   292   292 E SMD     : DCD OFF,
,03-17 13:04:58.465  1017  1328 E Watchdog: !@Sync 19,
,03-17 13:04:59.635  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:04:59.795   292   292 E SMD     : DCD OFF
,03-17 13:04:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:05:00.225  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:02.795   292   292 E SMD     : DCD OFF,
,03-17 13:05:05.795   292   292 E SMD     : DCD OFF,
,03-17 13:05:06.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:05:08.805   292   292 E SMD     : DCD OFF,
,03-17 13:05:09.695  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:05:10.235  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:11.805   292   292 E SMD     : DCD OFF,
,03-17 13:05:14.195  1017  1050 I PowerManagerService: [PWL] Off : 525s ago
,03-17 13:05:14.805   292   292 E SMD     : DCD OFF,
,03-17 13:05:17.805   292   292 E SMD     : DCD OFF,
,03-17 13:05:19.765  1017  1363 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:05:20.255  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:20.805   292   292 E SMD     : DCD OFF
,03-17 13:05:23.815   292   292 E SMD     : DCD OFF,
,03-17 13:05:25.435  1017  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:05:25.435  1017  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-17 13:05:25.435  1017  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:05:26.275  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:05:26.275  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:05:26.275  1017  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:05:26.285  1017  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-17 13:05:26.815   292   292 E SMD     : DCD OFF,
,03-17 13:05:26.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:05:28.465  1017  1328 E Watchdog: !@Sync 20,
,03-17 13:05:29.815   292   292 E SMD     : DCD OFF,
,03-17 13:05:29.825  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:05:30.295  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:32.815   292   292 E SMD     : DCD OFF
,03-17 13:05:35.815   292   292 E SMD     : DCD OFF
,03-17 13:05:38.825   292   292 E SMD     : DCD OFF,
,03-17 13:05:39.885  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:05:40.315  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:41.825   292   292 E SMD     : DCD OFF,
,03-17 13:05:44.825   292   292 E SMD     : DCD OFF
,03-17 13:05:46.955  1017  2809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:05:47.825   292   292 E SMD     : DCD OFF,
,03-17 13:05:49.955  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:05:50.355  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:05:50.825   292   292 E SMD     : DCD OFF,
,03-17 13:05:53.835   292   292 E SMD     : DCD OFF,
,03-17 13:05:56.835   292   292 E SMD     : DCD OFF,
,03-17 13:05:58.465  1017  1328 E Watchdog: !@Sync 21
,03-17 13:05:59.835   292   292 E SMD     : DCD OFF
,03-17 13:06:00.015  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:06:00.375  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:06:02.835   292   292 E SMD     : DCD OFF
,03-17 13:06:05.835   292   292 E SMD     : DCD OFF
,03-17 13:06:08.835   292   292 E SMD     : DCD OFF
,03-17 13:06:10.075  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:06:10.385  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:06:11.845   292   292 E SMD     : DCD OFF,
,03-17 13:06:14.845   292   292 E SMD     : DCD OFF,
,03-17 13:06:17.845   292   292 E SMD     : DCD OFF
,03-17 13:06:20.135  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:06:20.135  1017  3912 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:06:20.135  1017  3912 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:06:20.135  1017  3912 D BatteryService: stay LED for fully charged
03-17 13:06:20.135  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:06:20.135  1017  1017 I MotionRecognitionService: Plugged,
03-17 13:06:20.135  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:06:20.145  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:06:20.145  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:06:20.145  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:06:20.145  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:06:20.155  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:06:20.155  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:06:20.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:06:20.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:06:20.175  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:06:20.175  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:06:20.175  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:06:20.405  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:06:20.845   292   292 E SMD     : DCD OFF
,03-17 13:06:23.845   292   292 E SMD     : DCD OFF,
,03-17 13:06:26.855   292   292 E SMD     : DCD OFF,
,03-17 13:06:28.465  1017  1328 E Watchdog: !@Sync 22,
,03-17 13:06:29.195  1017  1050 I PowerManagerService: [PWL] Off : 600s ago
,03-17 13:06:29.855   292   292 E SMD     : DCD OFF,
,03-17 13:06:30.205  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:06:30.205  1017  2111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:06:30.205  1017  2111 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:06:30.205  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:06:30.205  1017  2111 D BatteryService: stay LED for fully charged
,03-17 13:06:30.205  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:06:30.205  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:06:30.215  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:06:30.215  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:06:30.215  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:06:30.215  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:06:30.225  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:06:30.225  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:06:30.235  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:06:30.235  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:06:30.235  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:06:30.235  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:06:30.235  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:06:30.435  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:06:32.855   292   292 E SMD     : DCD OFF
,03-17 13:06:35.855   292   292 E SMD     : DCD OFF,
,03-17 13:06:38.855   292   292 E SMD     : DCD OFF,
,03-17 13:06:40.265  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:06:40.475  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:06:41.865   292   292 E SMD     : DCD OFF
,03-17 13:06:44.865   292   292 E SMD     : DCD OFF
,03-17 13:06:47.865   292   292 E SMD     : DCD OFF
,03-17 13:06:50.335  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:06:50.335  1017  3782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:06:50.335  1017  3782 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:06:50.335  1017  3782 D BatteryService: stay LED for fully charged
,03-17 13:06:50.335  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:06:50.335  1017  1017 I MotionRecognitionService: Plugged,
03-17 13:06:50.335  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:06:50.345  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:06:50.345  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:06:50.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:06:50.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-17 13:06:50.355  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:06:50.355  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:06:50.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:06:50.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:06:50.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:06:50.365  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:06:50.365  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:06:50.495  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:06:50.865   292   292 E SMD     : DCD OFF
,03-17 13:06:53.865   292   292 E SMD     : DCD OFF
,03-17 13:06:56.875   292   292 E SMD     : DCD OFF,
,03-17 13:06:58.465  1017  1328 E Watchdog: !@Sync 23,
,03-17 13:06:59.875   292   292 E SMD     : DCD OFF,
,03-17 13:07:00.395  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:00.515  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:07:02.875   292   292 E SMD     : DCD OFF
,03-17 13:07:05.875   292   292 E SMD     : DCD OFF,
,03-17 13:07:08.875   292   292 E SMD     : DCD OFF
,03-17 13:07:10.455  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:10.535  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:07:11.885   292   292 E SMD     : DCD OFF,
,03-17 13:07:14.885   292   292 E SMD     : DCD OFF,
,03-17 13:07:17.885   292   292 E SMD     : DCD OFF,
,03-17 13:07:20.525  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:20.555  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:07:20.885   292   292 E SMD     : DCD OFF
,03-17 13:07:23.885   292   292 E SMD     : DCD OFF
,03-17 13:07:26.885   292   292 E SMD     : DCD OFF
,03-17 13:07:28.465  1017  1328 E Watchdog: !@Sync 24
,03-17 13:07:29.895   292   292 E SMD     : DCD OFF
,03-17 13:07:30.565  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:07:30.605  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:32.895   292   292 E SMD     : DCD OFF,
,03-17 13:07:35.895   292   292 E SMD     : DCD OFF,
,03-17 13:07:38.895   292   292 E SMD     : DCD OFF
,03-17 13:07:40.595  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:07:40.665  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:41.905   292   292 E SMD     : DCD OFF,
,03-17 13:07:44.905   292   292 E SMD     : DCD OFF,
,03-17 13:07:47.905   292   292 E SMD     : DCD OFF,
,03-17 13:07:49.195  1017  1050 I PowerManagerService: [PWL] Off : 680s ago
,03-17 13:07:50.615  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:07:50.725  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:07:50.905   292   292 E SMD     : DCD OFF,
,03-17 13:07:53.905   292   292 E SMD     : DCD OFF,
,03-17 13:07:56.915   292   292 E SMD     : DCD OFF,
,03-17 13:07:58.465  1017  1328 E Watchdog: !@Sync 25,
,03-17 13:07:59.915   292   292 E SMD     : DCD OFF,
,03-17 13:08:00.655  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:08:00.785  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:08:02.915   292   292 E SMD     : DCD OFF,
,03-17 13:08:05.915   292   292 E SMD     : DCD OFF,
,03-17 13:08:08.915   292   292 E SMD     : DCD OFF
,03-17 13:08:10.685  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:08:10.845  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:08:11.925   292   292 E SMD     : DCD OFF
,03-17 13:08:14.925   292   292 E SMD     : DCD OFF,
,03-17 13:08:17.925   292   292 E SMD     : DCD OFF
,03-17 13:08:20.725  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:08:20.915  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:08:20.925   292   292 E SMD     : DCD OFF,
,03-17 13:08:23.925   292   292 E SMD     : DCD OFF
,03-17 13:08:26.925   292   292 E SMD     : DCD OFF
,03-17 13:08:28.465  1017  1328 E Watchdog: !@Sync 26,
,03-17 13:08:29.935   292   292 E SMD     : DCD OFF,
,03-17 13:08:30.775  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:08:30.975  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:08:32.935   292   292 E SMD     : DCD OFF,
,03-17 13:08:35.935   292   292 E SMD     : DCD OFF
,03-17 13:08:38.935   292   292 E SMD     : DCD OFF
,03-17 13:08:40.825  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:08:41.035  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:08:41.935   292   292 E SMD     : DCD OFF,
,03-17 13:08:44.935   292   292 E SMD     : DCD OFF
,03-17 13:08:47.935   292   292 E SMD     : DCD OFF
,03-17 13:08:50.845  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:08:50.945   292   292 E SMD     : DCD OFF
,03-17 13:08:51.105  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:08:51.105  1017  1540 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:08:51.105  1017  1540 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:08:51.105  1017  1540 D BatteryService: stay LED for fully charged
03-17 13:08:51.105  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:08:51.105  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:08:51.105  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:08:51.105  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:08:51.115  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:08:51.115  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:08:51.115  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:08:51.115  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:08:51.125  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:08:51.135  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:08:51.135  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:08:51.135  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:08:51.135  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:08:51.135  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:08:53.945   292   292 E SMD     : DCD OFF
,03-17 13:08:56.945   292   292 E SMD     : DCD OFF
,03-17 13:08:58.465  1017  1328 E Watchdog: !@Sync 27
,03-17 13:08:59.945   292   292 E SMD     : DCD OFF
,03-17 13:09:00.865  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:09:01.165  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:09:01.165  1017  3781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:09:01.165  1017  3781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:09:01.165  1017  3781 D BatteryService: stay LED for fully charged
,03-17 13:09:01.165  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:09:01.165  1017  1017 I MotionRecognitionService: Plugged
03-17 13:09:01.165  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:09:01.175  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:09:01.175  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:09:01.175  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:09:01.175  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:09:01.185  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:09:01.185  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:09:01.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:09:01.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:09:01.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:09:01.195  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:09:01.195  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:09:02.945   292   292 E SMD     : DCD OFF,
,03-17 13:09:05.945   292   292 E SMD     : DCD OFF,
,03-17 13:09:08.955   292   292 E SMD     : DCD OFF
,03-17 13:09:10.915  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:09:11.225  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:09:11.955   292   292 E SMD     : DCD OFF
,03-17 13:09:14.195  1017  1050 I PowerManagerService: [PWL] Off : 765s ago
,03-17 13:09:14.955   292   292 E SMD     : DCD OFF
,03-17 13:09:17.955   292   292 E SMD     : DCD OFF
,03-17 13:09:20.955  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:09:20.955   292   292 E SMD     : DCD OFF,
,03-17 13:09:21.285  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:09:23.955   292   292 E SMD     : DCD OFF
,03-17 13:09:26.955   292   292 E SMD     : DCD OFF
,03-17 13:09:28.465  1017  1328 E Watchdog: !@Sync 28
,03-17 13:09:29.965   292   292 E SMD     : DCD OFF
,03-17 13:09:31.005  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:09:31.355  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:09:32.965   292   292 E SMD     : DCD OFF
,03-17 13:09:35.965   292   292 E SMD     : DCD OFF
,03-17 13:09:38.965   292   292 E SMD     : DCD OFF
,03-17 13:09:41.055  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:09:41.415  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:09:41.415  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:09:41.415  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:09:41.415  1017  1029 D BatteryService: stay LED for fully charged
03-17 13:09:41.415  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:09:41.415  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:09:41.415  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:09:41.425  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:09:41.425  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:09:41.425  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:09:41.425  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
03-17 13:09:41.425  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:09:41.435  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:09:41.445  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:09:41.445  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:09:41.445  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:09:41.445  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:09:41.445  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:09:41.965   292   292 E SMD     : DCD OFF
,03-17 13:09:44.965   292   292 E SMD     : DCD OFF,
,03-17 13:09:47.975   292   292 E SMD     : DCD OFF
,03-17 13:09:50.975   292   292 E SMD     : DCD OFF
,03-17 13:09:51.095  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:09:51.475  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:09:53.975   292   292 E SMD     : DCD OFF,
,03-17 13:09:56.975   292   292 E SMD     : DCD OFF
,03-17 13:09:58.465  1017  1328 E Watchdog: !@Sync 29,
,03-17 13:09:59.975   292   292 E SMD     : DCD OFF
,03-17 13:10:01.145  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:10:01.535  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:10:02.975   292   292 E SMD     : DCD OFF
,03-17 13:10:05.985   292   292 E SMD     : DCD OFF
,03-17 13:10:08.985   292   292 E SMD     : DCD OFF,
,03-17 13:10:11.175  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:10:11.605  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:10:11.985   292   292 E SMD     : DCD OFF,
,03-17 13:10:14.985   292   292 E SMD     : DCD OFF
,03-17 13:10:17.985   292   292 E SMD     : DCD OFF
,03-17 13:10:20.995   292   292 E SMD     : DCD OFF
,03-17 13:10:21.195  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:10:21.665  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:10:23.995   292   292 E SMD     : DCD OFF,
,03-17 13:10:25.435  1017  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-17 13:10:25.435  1017  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-17 13:10:25.435  1017  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:10:26.995   292   292 E SMD     : DCD OFF
,03-17 13:10:27.395  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:10:27.395  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:10:27.395  1017  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:10:27.405  1017  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:10:28.465  1017  1328 E Watchdog: !@Sync 30,
,03-17 13:10:29.995   292   292 E SMD     : DCD OFF
,03-17 13:10:31.215  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:10:31.735  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:10:32.995   292   292 E SMD     : DCD OFF
,03-17 13:10:35.995   292   292 E SMD     : DCD OFF
,03-17 13:10:39.005   292   292 E SMD     : DCD OFF
,03-17 13:10:39.435  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:10:39.445  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-17 13:10:39.445  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:10:39.455  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:10:39.465  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:10:39.465  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:10:39.465  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:10:39.465  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:10:39.495  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:10:39.505  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:10:39.505  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:10:39.515  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:10:39.525  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:10:39.595  1716  2606 D GCM     : Message class com.google.f.a.a.i
,03-17 13:10:41.255  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:10:41.795  1017  1363 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:10:42.005   292   292 E SMD     : DCD OFF,
,03-17 13:10:44.205  1017  1050 I PowerManagerService: [PWL] Off : 855s ago
,03-17 13:10:45.005   292   292 E SMD     : DCD OFF
,03-17 13:10:48.005   292   292 E SMD     : DCD OFF,
,03-17 13:10:51.005   292   292 E SMD     : DCD OFF,
,03-17 13:10:51.285  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:10:51.855  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:10:54.005   292   292 E SMD     : DCD OFF
,03-17 13:10:57.015   292   292 E SMD     : DCD OFF
,03-17 13:10:58.465  1017  1328 E Watchdog: !@Sync 31
,03-17 13:10:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:11:00.015   292   292 E SMD     : DCD OFF
,03-17 13:11:01.305  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:11:01.915  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:11:03.015   292   292 E SMD     : DCD OFF
,03-17 13:11:06.015   292   292 E SMD     : DCD OFF
,03-17 13:11:09.015   292   292 E SMD     : DCD OFF
,03-17 13:11:11.345  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:11:11.975  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:11:12.015   292   292 E SMD     : DCD OFF,
,03-17 13:11:15.025   292   292 E SMD     : DCD OFF
,03-17 13:11:18.025   292   292 E SMD     : DCD OFF,
,03-17 13:11:21.025   292   292 E SMD     : DCD OFF,
,03-17 13:11:21.395  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:11:22.045  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:11:24.025   292   292 E SMD     : DCD OFF
,03-17 13:11:27.025   292   292 E SMD     : DCD OFF
,03-17 13:11:28.475  1017  1328 E Watchdog: !@Sync 32
,03-17 13:11:30.025   292   292 E SMD     : DCD OFF
,03-17 13:11:31.425  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:11:32.105  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:11:33.035   292   292 E SMD     : DCD OFF
,03-17 13:11:36.035   292   292 E SMD     : DCD OFF
,03-17 13:11:39.035   292   292 E SMD     : DCD OFF
,03-17 13:11:41.465  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:11:42.035   292   292 E SMD     : DCD OFF
,03-17 13:11:42.165  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:11:45.035   292   292 E SMD     : DCD OFF
,03-17 13:11:48.035   292   292 E SMD     : DCD OFF
,03-17 13:11:51.045   292   292 E SMD     : DCD OFF
,03-17 13:11:51.485  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:11:52.235  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:11:54.045   292   292 E SMD     : DCD OFF
,03-17 13:11:57.045   292   292 E SMD     : DCD OFF
,03-17 13:11:58.475  1017  1328 E Watchdog: !@Sync 33
,03-17 13:12:00.045   292   292 E SMD     : DCD OFF
,03-17 13:12:01.535  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:12:02.285  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:12:03.045   292   292 E SMD     : DCD OFF
,03-17 13:12:06.045   292   292 E SMD     : DCD OFF
,03-17 13:12:09.045   292   292 E SMD     : DCD OFF
,03-17 13:12:11.545  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:12:12.055   292   292 E SMD     : DCD OFF
,03-17 13:12:12.355  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:12:15.055   292   292 E SMD     : DCD OFF,
,03-17 13:12:18.055   292   292 E SMD     : DCD OFF
,03-17 13:12:19.295  1017  1050 I PowerManagerService: [PWL] Off : 951s ago
,03-17 13:12:21.055   292   292 E SMD     : DCD OFF
,03-17 13:12:21.595  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:12:22.415  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:12:24.055   292   292 E SMD     : DCD OFF,
,03-17 13:12:27.055   292   292 E SMD     : DCD OFF
,03-17 13:12:28.475  1017  1328 E Watchdog: !@Sync 34
,03-17 13:12:30.065   292   292 E SMD     : DCD OFF
,03-17 13:12:31.645  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:12:32.485  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:12:33.065   292   292 E SMD     : DCD OFF
,03-17 13:12:36.065   292   292 E SMD     : DCD OFF
,03-17 13:12:39.065   292   292 E SMD     : DCD OFF
,03-17 13:12:41.685  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:12:42.065   292   292 E SMD     : DCD OFF
,03-17 13:12:42.535  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:12:45.065   292   292 E SMD     : DCD OFF
,03-17 13:12:48.075   292   292 E SMD     : DCD OFF,
,03-17 13:12:51.075   292   292 E SMD     : DCD OFF,
,03-17 13:12:51.735  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:12:52.605  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:12:54.075   292   292 E SMD     : DCD OFF
,03-17 13:12:57.075   292   292 E SMD     : DCD OFF
,03-17 13:12:58.475  1017  1328 E Watchdog: !@Sync 35
,03-17 13:13:00.075   292   292 E SMD     : DCD OFF
,03-17 13:13:01.755  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:02.305  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:13:02.315  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 13:13:02.315  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 13:13:02.325  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 13:13:02.325  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 13:13:02.335  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:13:02.335  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 13:13:02.335  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 13:13:02.365  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:13:02.375  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:13:02.375  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:13:02.385  1172  1172 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-17 13:13:02.405  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 13:13:02.665  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:13:02.845  5964  6507 I BooksSync: Starting books sync for 61035162, extras: ade
,03-17 13:13:02.865  5964  6508 I BooksConfig: GmsCore Version = 7.8.99 (2134222-434)
,03-17 13:13:02.865  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.865  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.865  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.875  1017  3413 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.875  1017  3413 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.875  1017  3413 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.895  1716  3409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:13:02.895  1716  3409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:13:02.895  1716  3409 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:13:02.895  1716  3409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:13:02.895  1716  3409 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:13:02.895  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.895  1017  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.895  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.915  1017  3781 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 13:13:02.915  1017  3781 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 13:13:02.915  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:13:02.925  1172  1172 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:13:02.925  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:13:02.925  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:13:02.925  1172  1172 I PhoneStatusBar: Icon Only
03-17 13:13:02.925  1172  1172 I StatusBar: Icon Only
03-17 13:13:02.925  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:13:02.925  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:13:02.925  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.925  1017  3781 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.925  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.935  1172  1172 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:13:02.935  1172  1172 I PhoneStatusBar: Icon Only
,03-17 13:13:02.935  1172  1172 I StatusBar: Icon Only
,03-17 13:13:02.935  1172  1172 D PanelView: There is/are notification(s) 
03-17 13:13:02.935  1172  1172 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:13:02.935  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.935  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.945  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.955  1716  1727 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-17 13:13:02.955  1716  1727 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 13:13:02.955  1716  1727 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 13:13:02.955  1716  1727 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 13:13:02.955  1716  1727 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:13:02.965  1017  1363 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:13:02.965  1017  1363 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:13:02.965  1017  1363 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 13:13:02.975  5964  6508 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-17 13:13:02.975  5964  6507 E BooksSync: Soft error
03-17 13:13:02.975  5964  6507 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:13:02.975  5964  6507 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 13:13:02.975  5964  6507 E BooksSync: Sync error
03-17 13:13:02.975  5964  6507 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 13:13:02.975  5964  6507 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-17 13:13:02.975  5964  6507 I BooksSync: Finished books sync
,03-17 13:13:02.975  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1071897, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 13:13:02.995  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 13:13:03.015  1017  1540 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 13:13:03.015  1017  1540 D SecContentProvider2: mCursor = null
,03-17 13:13:03.075   292   292 E SMD     : DCD OFF
,03-17 13:13:06.085   292   292 E SMD     : DCD OFF
,03-17 13:13:09.085   292   292 E SMD     : DCD OFF
,03-17 13:13:11.805  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:12.085   292   292 E SMD     : DCD OFF
,03-17 13:13:12.725  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:13:15.085   292   292 E SMD     : DCD OFF
,03-17 13:13:18.085   292   292 E SMD     : DCD OFF
,03-17 13:13:21.085   292   292 E SMD     : DCD OFF
,03-17 13:13:21.825  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:22.785  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:13:24.085   292   292 E SMD     : DCD OFF
,03-17 13:13:27.095   292   292 E SMD     : DCD OFF
,03-17 13:13:28.475  1017  1328 E Watchdog: !@Sync 36
,03-17 13:13:30.095   292   292 E SMD     : DCD OFF
,03-17 13:13:31.875  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:32.845  1017  1096 V AlarmManager: waitForAlarm result :4
,03-17 13:13:32.845  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:13:33.095   292   292 E SMD     : DCD OFF
,03-17 13:13:36.095   292   292 E SMD     : DCD OFF
,03-17 13:13:39.095   292   292 E SMD     : DCD OFF
,03-17 13:13:41.895  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:42.095   292   292 E SMD     : DCD OFF
,03-17 13:13:42.915  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:13:45.105   292   292 E SMD     : DCD OFF,
,03-17 13:13:48.105   292   292 E SMD     : DCD OFF
,03-17 13:13:51.105   292   292 E SMD     : DCD OFF
,03-17 13:13:51.905  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:13:52.975  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:13:54.105   292   292 E SMD     : DCD OFF
,03-17 13:13:57.105   292   292 E SMD     : DCD OFF,
,03-17 13:13:58.475  1017  1328 E Watchdog: !@Sync 37,
,03-17 13:13:59.325  1017  1050 I PowerManagerService: [PWL] Off : 1051s ago,
,03-17 13:13:59.995  1017  1096 V AlarmManager: waitForAlarm result :8
,03-17 13:14:00.105   292   292 E SMD     : DCD OFF,
,03-17 13:14:01.925  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:03.035  1017  1363 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:14:03.115   292   292 E SMD     : DCD OFF
,03-17 13:14:06.115   292   292 E SMD     : DCD OFF
,03-17 13:14:09.115   292   292 E SMD     : DCD OFF,
,03-17 13:14:11.945  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:12.115   292   292 E SMD     : DCD OFF,
,03-17 13:14:13.095  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:14:13.095  1017  1431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:14:13.095  1017  1431 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:14:13.095  1017  1431 D BatteryService: stay LED for fully charged
03-17 13:14:13.095  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:14:13.095  1017  1017 I MotionRecognitionService: Plugged
03-17 13:14:13.095  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:14:13.105  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:14:13.105  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:14:13.105  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:14:13.105  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:14:13.115  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:14:13.115  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:14:13.125  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:14:13.125  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:14:13.125  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:14:13.125  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:14:13.125  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:14:15.115   292   292 E SMD     : DCD OFF
,03-17 13:14:18.125   292   292 E SMD     : DCD OFF,
,03-17 13:14:21.125   292   292 E SMD     : DCD OFF,
,03-17 13:14:21.955  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:23.155  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:14:23.155  1017  2111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:14:23.155  1017  2111 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-17 13:14:23.155  1017  2111 D BatteryService: stay LED for fully charged
03-17 13:14:23.155  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:14:23.165  1017  1017 I MotionRecognitionService: Plugged
03-17 13:14:23.165  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:14:23.165  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:14:23.165  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:14:23.165  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:14:23.165  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:14:23.175  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:14:23.175  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:14:23.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:14:23.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:14:23.195  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:14:23.195  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:14:23.195  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:14:24.125   292   292 E SMD     : DCD OFF
,03-17 13:14:27.125   292   292 E SMD     : DCD OFF
,03-17 13:14:28.475  1017  1328 E Watchdog: !@Sync 38
,03-17 13:14:30.125   292   292 E SMD     : DCD OFF,
,03-17 13:14:31.975  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:33.135   292   292 E SMD     : DCD OFF
,03-17 13:14:33.225  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:14:36.135   292   292 E SMD     : DCD OFF
,03-17 13:14:39.135   292   292 E SMD     : DCD OFF
,03-17 13:14:41.985  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:42.135   292   292 E SMD     : DCD OFF,
,03-17 13:14:43.275  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:14:45.135   292   292 E SMD     : DCD OFF
,03-17 13:14:48.145   292   292 E SMD     : DCD OFF,
,03-17 13:14:51.145   292   292 E SMD     : DCD OFF
,03-17 13:14:52.005  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:14:53.335  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:14:54.145   292   292 E SMD     : DCD OFF
,03-17 13:14:57.145   292   292 E SMD     : DCD OFF,
,03-17 13:14:58.475  1017  1328 E Watchdog: !@Sync 39
,03-17 13:15:00.145   292   292 E SMD     : DCD OFF,
,03-17 13:15:02.015  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:03.145   292   292 E SMD     : DCD OFF,
,03-17 13:15:03.395  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:15:06.155   292   292 E SMD     : DCD OFF
,03-17 13:15:09.155   292   292 E SMD     : DCD OFF
,03-17 13:15:12.035  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:12.155   292   292 E SMD     : DCD OFF,
,03-17 13:15:13.465  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:15:13.465  1017  2111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:15:13.465  1017  2111 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:15:13.465  1017  2111 D BatteryService: stay LED for fully charged
03-17 13:15:13.465  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:15:13.465  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:15:13.465  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:15:13.465  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:15:13.465  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:15:13.475  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:15:13.475  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:15:13.485  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:15:13.485  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:15:13.495  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:13.495  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:15:13.495  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:13.495  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:15:13.495  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:15:15.155   292   292 E SMD     : DCD OFF
,03-17 13:15:18.155   292   292 E SMD     : DCD OFF
,03-17 13:15:21.155   292   292 E SMD     : DCD OFF,
,03-17 13:15:22.045  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:23.525  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:15:23.525  1017  1431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:15:23.525  1017  1431 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:15:23.525  1017  1431 D BatteryService: stay LED for fully charged
,03-17 13:15:23.525  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:15:23.535  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:15:23.535  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:15:23.535  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:15:23.535  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:15:23.535  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:15:23.535  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:15:23.545  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:15:23.555  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:15:23.565  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:23.565  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:15:23.565  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:15:23.565  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:15:23.565  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:15:24.165   292   292 E SMD     : DCD OFF
,03-17 13:15:25.435  1017  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
03-17 13:15:25.435  1017  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-17 13:15:25.435  1017  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:15:26.065  1017  1042 I UsageStatsService: User[0] Flushing usage stats to disk
,03-17 13:15:26.115  1017  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB,
03-17 13:15:26.115  1017  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1458216926123
,03-17 13:15:26.115  1017  1103 I ApplicationPolicy: updateDataUsageMap
,03-17 13:15:26.275  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:15:26.275  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:15:26.275  1017  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:15:26.275  1017  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:15:26.435  1017  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-17 13:15:26.435  1017  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-17 13:15:26.455  1017  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458216926468
,03-17 13:15:27.165   292   292 E SMD     : DCD OFF
,03-17 13:15:28.475  1017  1328 E Watchdog: !@Sync 40
,03-17 13:15:30.165   292   292 E SMD     : DCD OFF,
,03-17 13:15:32.095  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:33.165   292   292 E SMD     : DCD OFF,
,03-17 13:15:33.595  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:15:36.165   292   292 E SMD     : DCD OFF,
,03-17 13:15:39.175   292   292 E SMD     : DCD OFF,
,03-17 13:15:42.115  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:42.175   292   292 E SMD     : DCD OFF
,03-17 13:15:43.655  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:15:43.655  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:15:43.655  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:15:43.655  1017  1029 D BatteryService: stay LED for fully charged
,03-17 13:15:43.655  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:15:43.655  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:15:43.655  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:15:43.665  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:15:43.665  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:15:43.665  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:15:43.665  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:15:43.675  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:15:43.675  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:15:43.685  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:43.685  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:43.695  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:15:43.695  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:15:43.695  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:15:44.325  1017  1050 I PowerManagerService: [PWL] Off : 1156s ago
,03-17 13:15:45.175   292   292 E SMD     : DCD OFF
,03-17 13:15:48.175   292   292 E SMD     : DCD OFF
,03-17 13:15:51.175   292   292 E SMD     : DCD OFF
,03-17 13:15:52.135  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:15:53.715  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:15:54.175   292   292 E SMD     : DCD OFF,
,03-17 13:15:57.185   292   292 E SMD     : DCD OFF,
,03-17 13:15:58.475  1017  1328 E Watchdog: !@Sync 41
,03-17 13:16:00.185   292   292 E SMD     : DCD OFF
,03-17 13:16:02.165  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:03.185   292   292 E SMD     : DCD OFF
,03-17 13:16:03.785  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:16:06.185   292   292 E SMD     : DCD OFF
,03-17 13:16:09.185   292   292 E SMD     : DCD OFF
,03-17 13:16:12.185  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:12.195   292   292 E SMD     : DCD OFF
,03-17 13:16:13.845  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:16:15.195   292   292 E SMD     : DCD OFF
,03-17 13:16:18.195   292   292 E SMD     : DCD OFF
,03-17 13:16:21.195   292   292 E SMD     : DCD OFF
,03-17 13:16:22.205  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:23.905  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:16:23.905  1017  2111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:16:23.905  1017  2111 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:16:23.905  1017  2111 D BatteryService: stay LED for fully charged
03-17 13:16:23.905  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:16:23.905  1017  1017 I MotionRecognitionService: Plugged
03-17 13:16:23.905  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:16:23.905  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:16:23.905  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:16:23.905  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:16:23.905  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:16:23.915  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:23.915  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:16:23.915  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:16:23.925  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:23.925  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:16:23.925  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:16:23.925  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:16:24.195   292   292 E SMD     : DCD OFF
,03-17 13:16:27.195   292   292 E SMD     : DCD OFF
,03-17 13:16:28.485  1017  1328 E Watchdog: !@Sync 42
,03-17 13:16:30.205   292   292 E SMD     : DCD OFF
,03-17 13:16:32.255  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:33.205   292   292 E SMD     : DCD OFF
,03-17 13:16:33.965  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:16:33.965  1017  1431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:16:33.965  1017  1431 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:16:33.965  1017  1431 D BatteryService: stay LED for fully charged
,03-17 13:16:33.965  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:16:33.965  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:16:33.965  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:16:33.975  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:16:33.975  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:16:33.975  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:16:33.975  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:16:33.985  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:16:33.985  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:16:33.995  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:33.995  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:16:34.005  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:16:34.005  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:16:34.005  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:16:36.205   292   292 E SMD     : DCD OFF,
,03-17 13:16:39.205   292   292 E SMD     : DCD OFF
,03-17 13:16:42.205   292   292 E SMD     : DCD OFF
,03-17 13:16:42.275  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:44.025  1017  2111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:16:44.025  1017  2111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:16:44.025  1017  2111 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:16:44.025  1017  2111 D BatteryService: stay LED for fully charged
03-17 13:16:44.025  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:16:44.025  1017  1017 I MotionRecognitionService: Plugged
03-17 13:16:44.025  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:16:44.035  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:16:44.035  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:16:44.035  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:16:44.035  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:16:44.045  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:16:44.045  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:16:44.055  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:44.055  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:44.055  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:44.065  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:16:44.065  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:16:45.205   292   292 E SMD     : DCD OFF
,03-17 13:16:48.215   292   292 E SMD     : DCD OFF
,03-17 13:16:51.215   292   292 E SMD     : DCD OFF
,03-17 13:16:52.325  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:16:54.085  1017  1431 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:16:54.085  1017  1431 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:16:54.085  1017  1431 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:16:54.085  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:16:54.085  1017  1431 D BatteryService: stay LED for fully charged
03-17 13:16:54.085  1017  1017 I MotionRecognitionService: Plugged
03-17 13:16:54.085  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:16:54.095  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:16:54.095  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:16:54.095  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:16:54.095  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:16:54.105  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:16:54.105  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:16:54.115  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:54.115  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:54.115  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:16:54.115  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:16:54.115  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:16:54.215   292   292 E SMD     : DCD OFF
,03-17 13:16:57.215   292   292 E SMD     : DCD OFF
,03-17 13:16:58.485  1017  1328 E Watchdog: !@Sync 43
,03-17 13:17:00.215   292   292 E SMD     : DCD OFF
,03-17 13:17:02.375  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:03.215   292   292 E SMD     : DCD OFF
,03-17 13:17:04.155  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:17:04.155  1017  1543 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:17:04.155  1017  1543 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:17:04.155  1017  1543 D BatteryService: stay LED for fully charged
,03-17 13:17:04.155  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:17:04.155  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:17:04.155  1017  1017 I MotionRecognitionService: Plugged,
03-17 13:17:04.155  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:17:04.155  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:17:04.165  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:17:04.165  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:17:04.165  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:04.165  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:17:04.165  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:17:04.185  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:17:04.185  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:04.185  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:17:04.185  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:17:06.225   292   292 E SMD     : DCD OFF
,03-17 13:17:09.225   292   292 E SMD     : DCD OFF
,03-17 13:17:12.225   292   292 E SMD     : DCD OFF
,03-17 13:17:12.385  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:14.215  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:17:14.215  1017  3912 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:17:14.215  1017  3912 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:17:14.215  1017  3912 D BatteryService: stay LED for fully charged
03-17 13:17:14.215  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:17:14.215  1017  1017 I MotionRecognitionService: Plugged,
03-17 13:17:14.215  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:17:14.215  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:17:14.215  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:17:14.225  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:17:14.225  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:17:14.235  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:17:14.235  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:17:14.245  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:14.245  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:14.245  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:14.245  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:17:14.245  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:17:15.225   292   292 E SMD     : DCD OFF
,03-17 13:17:18.225   292   292 E SMD     : DCD OFF
,03-17 13:17:21.225   292   292 E SMD     : DCD OFF
,03-17 13:17:22.435  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:24.235   292   292 E SMD     : DCD OFF
,03-17 13:17:24.275  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:17:24.285  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:17:24.275  1017  1543 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:17:24.285  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:17:24.275  1017  1543 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:17:24.275  1017  1543 D BatteryService: stay LED for fully charged
03-17 13:17:24.275  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:17:24.285  1017  1017 I MotionRecognitionService: Plugged
03-17 13:17:24.285  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:17:24.285  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:17:24.285  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:17:24.295  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:17:24.295  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:17:24.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:17:24.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:17:24.305  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:17:24.305  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:17:24.305  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:17:27.235   292   292 E SMD     : DCD OFF
,03-17 13:17:28.485  1017  1328 E Watchdog: !@Sync 44
,03-17 13:17:30.235   292   292 E SMD     : DCD OFF
,03-17 13:17:32.495  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:33.235   292   292 E SMD     : DCD OFF
,03-17 13:17:34.325  1017  1050 I PowerManagerService: [PWL] Off : 1266s ago
,03-17 13:17:34.335  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:17:34.335  1017  3912 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:17:34.335  1017  3912 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:17:34.345  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:17:34.335  1017  3912 D BatteryService: stay LED for fully charged
,03-17 13:17:34.345  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:17:34.335  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:17:34.335  1017  1017 I MotionRecognitionService: Plugged
03-17 13:17:34.335  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:17:34.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:17:34.345  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:17:34.355  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:17:34.355  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:17:34.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,03-17 13:17:34.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:17:34.365  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:17:34.365  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:17:34.365  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:17:36.235   292   292 E SMD     : DCD OFF
,03-17 13:17:39.235   292   292 E SMD     : DCD OFF
,03-17 13:17:42.245   292   292 E SMD     : DCD OFF
,03-17 13:17:42.505  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:44.405  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:17:45.245   292   292 E SMD     : DCD OFF
,03-17 13:17:48.245   292   292 E SMD     : DCD OFF
,03-17 13:17:51.245   292   292 E SMD     : DCD OFF
,03-17 13:17:52.565  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:17:54.245   292   292 E SMD     : DCD OFF,
,03-17 13:17:54.465  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:17:57.245   292   292 E SMD     : DCD OFF
,03-17 13:17:58.485  1017  1328 E Watchdog: !@Sync 45
,03-17 13:18:00.255   292   292 E SMD     : DCD OFF
,03-17 13:18:02.585  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:18:03.255   292   292 E SMD     : DCD OFF
,03-17 13:18:04.525  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:18:06.255   292   292 E SMD     : DCD OFF
,03-17 13:18:09.255   292   292 E SMD     : DCD OFF
,03-17 13:18:12.255   292   292 E SMD     : DCD OFF
,03-17 13:18:12.605  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:18:14.585  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:18:15.255   292   292 E SMD     : DCD OFF
,03-17 13:18:18.255   292   292 E SMD     : DCD OFF
,03-17 13:18:21.265   292   292 E SMD     : DCD OFF
,03-17 13:18:22.655  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:18:24.265   292   292 E SMD     : DCD OFF,
,03-17 13:18:24.645  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:18:27.265   292   292 E SMD     : DCD OFF
,03-17 13:18:28.485  1017  1328 E Watchdog: !@Sync 46
,03-17 13:18:30.265   292   292 E SMD     : DCD OFF
,03-17 13:18:32.675  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:18:33.265   292   292 E SMD     : DCD OFF
,03-17 13:18:34.705  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:18:36.265   292   292 E SMD     : DCD OFF
,03-17 13:18:39.275   292   292 E SMD     : DCD OFF
,03-17 13:18:42.275   292   292 E SMD     : DCD OFF
,03-17 13:18:42.685  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:18:44.765  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:18:44.765  1017  3782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:18:44.765  1017  3782 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:18:44.765  1017  3782 D BatteryService: stay LED for fully charged
03-17 13:18:44.775  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:18:44.765  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:18:44.775  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:18:44.775  1017  1017 I MotionRecognitionService: Plugged
03-17 13:18:44.775  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:18:44.775  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:18:44.775  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:18:44.785  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,03-17 13:18:44.795  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:18:44.795  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:18:44.805  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:18:44.805  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:18:44.805  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:18:44.805  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:18:45.275   292   292 E SMD     : DCD OFF
,03-17 13:18:48.275   292   292 E SMD     : DCD OFF
,03-17 13:18:51.275   292   292 E SMD     : DCD OFF
,03-17 13:18:52.745  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:18:54.275   292   292 E SMD     : DCD OFF
,03-17 13:18:54.825  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:18:54.825  1017  1138 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:18:54.825  1017  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:18:54.825  1017  1138 D BatteryService: stay LED for fully charged
03-17 13:18:54.825  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:18:54.835  1017  1017 I MotionRecognitionService: Plugged
03-17 13:18:54.835  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:18:54.835  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:18:54.835  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:18:54.835  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:18:54.835  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:18:54.845  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:18:54.845  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:18:54.855  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:18:54.855  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:18:54.855  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:18:54.855  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:18:54.855  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:18:57.275   292   292 E SMD     : DCD OFF
,03-17 13:18:58.485  1017  1328 E Watchdog: !@Sync 47
,03-17 13:19:00.285   292   292 E SMD     : DCD OFF
,03-17 13:19:02.775  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:19:03.285   292   292 E SMD     : DCD OFF
,03-17 13:19:04.885  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:04.885  1017  3782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:19:04.885  1017  3782 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:19:04.885  1017  3782 D BatteryService: stay LED for fully charged
03-17 13:19:04.885  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:19:04.895  1017  1017 I MotionRecognitionService: Plugged
,03-17 13:19:04.895  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:19:04.895  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:19:04.895  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:19:04.895  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:19:04.895  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:19:04.905  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:19:04.905  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:19:04.925  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-17 13:19:04.925  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:19:04.925  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:19:04.925  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:19:04.925  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:19:06.285   292   292 E SMD     : DCD OFF,
,03-17 13:19:09.285   292   292 E SMD     : DCD OFF,
,03-17 13:19:12.285   292   292 E SMD     : DCD OFF
,03-17 13:19:12.785  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:19:14.945  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:15.285   292   292 E SMD     : DCD OFF
,03-17 13:19:18.295   292   292 E SMD     : DCD OFF
,03-17 13:19:21.295   292   292 E SMD     : DCD OFF
,03-17 13:19:22.815  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:19:24.295   292   292 E SMD     : DCD OFF
,03-17 13:19:25.005  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:25.005  1017  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:19:25.005  1017  1468 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:19:25.005  1017  1468 D BatteryService: stay LED for fully charged
03-17 13:19:25.005  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:19:25.015  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:19:25.015  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 13:19:25.015  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:19:25.015  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 13:19:25.015  1017  1017 I MotionRecognitionService: Plugged
03-17 13:19:25.015  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:19:25.025  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:19:25.025  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:19:25.035  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:19:25.045  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:19:25.045  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:19:25.045  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:19:25.045  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:19:27.295   292   292 E SMD     : DCD OFF
,03-17 13:19:28.485  1017  1328 E Watchdog: !@Sync 48
,03-17 13:19:29.335  1017  1050 I PowerManagerService: [PWL] Off : 1381s ago
,03-17 13:19:30.295   292   292 E SMD     : DCD OFF
,03-17 13:19:32.865  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:19:33.295   292   292 E SMD     : DCD OFF
,03-17 13:19:35.065  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:35.065  1017  3413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:19:35.065  1017  3413 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:19:35.065  1017  3413 D BatteryService: stay LED for fully charged
,03-17 13:19:35.075  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:19:35.075  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:19:35.075  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:19:35.075  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:19:35.085  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 13:19:35.085  1017  1017 I MotionRecognitionService: Plugged
03-17 13:19:35.085  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:19:35.085  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:19:35.095  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:19:35.105  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:19:35.105  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:19:35.105  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:19:35.105  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:19:35.105  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:19:36.295   292   292 E SMD     : DCD OFF
,03-17 13:19:39.305   292   292 E SMD     : DCD OFF
,03-17 13:19:42.305   292   292 E SMD     : DCD OFF
,03-17 13:19:42.885  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:19:45.135  1017  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:45.305   292   292 E SMD     : DCD OFF
,03-17 13:19:48.305   292   292 E SMD     : DCD OFF
,03-17 13:19:51.305   292   292 E SMD     : DCD OFF
,03-17 13:19:52.935  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:19:54.315   292   292 E SMD     : DCD OFF
,03-17 13:19:55.195  1017  3912 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:19:57.315   292   292 E SMD     : DCD OFF
,03-17 13:19:58.485  1017  1328 E Watchdog: !@Sync 49
,03-17 13:20:00.315   292   292 E SMD     : DCD OFF
,03-17 13:20:02.995  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:20:03.315   292   292 E SMD     : DCD OFF
,03-17 13:20:05.265  1017  3803 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:05.265  1017  3803 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:20:05.265  1017  3803 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:20:05.265  1017  3803 D BatteryService: stay LED for fully charged
03-17 13:20:05.265  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:20:05.265  1017  1017 I MotionRecognitionService: Plugged
03-17 13:20:05.265  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:20:05.265  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:20:05.265  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:20:05.265  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:20:05.265  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:20:05.275  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:20:05.275  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:20:05.295  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:20:05.295  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:20:05.295  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:20:05.295  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:20:05.295  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:20:06.315   292   292 E SMD     : DCD OFF
,03-17 13:20:09.315   292   292 E SMD     : DCD OFF
,03-17 13:20:12.325   292   292 E SMD     : DCD OFF
,03-17 13:20:13.015  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:20:15.325   292   292 E SMD     : DCD OFF
03-17 13:20:15.325  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:18.325   292   292 E SMD     : DCD OFF
,03-17 13:20:21.325   292   292 E SMD     : DCD OFF
,03-17 13:20:23.065  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:20:24.325   292   292 E SMD     : DCD OFF
,03-17 13:20:25.385  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:25.385  1017  1138 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-17 13:20:25.385  1017  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:20:25.385  1017  1138 D BatteryService: stay LED for fully charged
03-17 13:20:25.385  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:20:25.395  1017  1017 I MotionRecognitionService: Plugged
03-17 13:20:25.395  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:20:25.395  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-17 13:20:25.395  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:20:25.395  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:20:25.395  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:20:25.405  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-17 13:20:25.405  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:20:25.415  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:20:25.415  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:20:25.415  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:20:25.415  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-17 13:20:25.415  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:20:25.435  1017  1086 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-17 13:20:25.435  1017  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-17 13:20:25.435  1017  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,03-17 13:20:27.325   292   292 E SMD     : DCD OFF
,03-17 13:20:27.385  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-17 13:20:27.395  1017  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-17 13:20:27.395  1017  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-17 13:20:27.395  1017  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-17 13:20:28.485  1017  1328 E Watchdog: !@Sync 50
,03-17 13:20:30.335   292   292 E SMD     : DCD OFF
,03-17 13:20:33.085  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:20:33.335   292   292 E SMD     : DCD OFF,
,03-17 13:20:35.455  1017  3782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:36.335   292   292 E SMD     : DCD OFF
,03-17 13:20:39.335   292   292 E SMD     : DCD OFF
,03-17 13:20:42.335   292   292 E SMD     : DCD OFF
,03-17 13:20:43.105  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:20:45.335   292   292 E SMD     : DCD OFF
,03-17 13:20:45.515  1017  3413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:48.335   292   292 E SMD     : DCD OFF,
,03-17 13:20:51.345   292   292 E SMD     : DCD OFF
,03-17 13:20:53.135  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:20:54.345   292   292 E SMD     : DCD OFF
,03-17 13:20:55.575  1017  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:20:57.345   292   292 E SMD     : DCD OFF
,03-17 13:20:58.485  1017  1328 E Watchdog: !@Sync 51
,03-17 13:21:00.345   292   292 E SMD     : DCD OFF
,03-17 13:21:03.175  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:21:03.345   292   292 E SMD     : DCD OFF
,03-17 13:21:05.635  1017  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:21:06.345   292   292 E SMD     : DCD OFF
,03-17 13:21:09.355   292   292 E SMD     : DCD OFF
,03-17 13:21:12.355   292   292 E SMD     : DCD OFF
,03-17 13:21:13.205  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:21:15.355   292   292 E SMD     : DCD OFF
,03-17 13:21:15.695  1017  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:21:15.695  1017  1138 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:21:15.695  1017  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:21:15.695  1017  1138 D BatteryService: stay LED for fully charged
03-17 13:21:15.695  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:21:15.695  1017  1017 I MotionRecognitionService: Plugged,
03-17 13:21:15.695  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:21:15.695  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:21:15.695  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:21:15.695  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:21:15.695  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:21:15.705  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:21:15.705  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:21:15.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:21:15.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:21:15.725  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:21:15.725  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:21:15.725  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:21:18.355   292   292 E SMD     : DCD OFF,
,03-17 13:21:21.355   292   292 E SMD     : DCD OFF,
,03-17 13:21:23.265  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:21:24.355   292   292 E SMD     : DCD OFF
,03-17 13:21:25.745  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:21:27.365   292   292 E SMD     : DCD OFF
,03-17 13:21:28.495  1017  1328 E Watchdog: !@Sync 52
,03-17 13:21:29.345  1017  1050 I PowerManagerService: [PWL] Off : 1501s ago,
,03-17 13:21:30.365   292   292 E SMD     : DCD OFF
,03-17 13:21:33.285  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:21:33.365   292   292 E SMD     : DCD OFF
,03-17 13:21:35.815  1017  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:21:35.815  1017  1540 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:21:35.815  1017  1540 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:21:35.815  1017  1540 D BatteryService: stay LED for fully charged
03-17 13:21:35.815  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:21:35.815  1017  1017 I MotionRecognitionService: Plugged
03-17 13:21:35.815  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:21:35.815  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:21:35.815  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:21:35.825  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:21:35.825  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:21:35.835  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:21:35.835  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:21:35.845  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:21:35.845  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:21:35.845  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:21:35.845  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:21:35.845  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:21:36.365   292   292 E SMD     : DCD OFF,
,03-17 13:21:39.365   292   292 E SMD     : DCD OFF,
,03-17 13:21:42.365   292   292 E SMD     : DCD OFF
,03-17 13:21:43.315  1017  2764 D SSRM:n  : SIOP:: AP = 260,
,03-17 13:21:45.365   292   292 E SMD     : DCD OFF
,03-17 13:21:45.875  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-17 13:21:48.375   292   292 E SMD     : DCD OFF,
,03-17 13:21:51.375   292   292 E SMD     : DCD OFF,
,03-17 13:21:53.365  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:21:54.375   292   292 E SMD     : DCD OFF,
,03-17 13:21:55.935  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:21:55.935  1017  3781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:21:55.935  1017  3781 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-17 13:21:55.935  1017  3781 D BatteryService: stay LED for fully charged
03-17 13:21:55.935  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:21:55.945  1017  1017 I MotionRecognitionService: Plugged
03-17 13:21:55.945  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:21:55.945  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:21:55.945  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:21:55.945  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:21:55.945  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:21:55.955  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:21:55.955  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:21:55.955  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:21:55.965  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:21:55.975  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:21:55.975  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:21:55.975  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:21:57.375   292   292 E SMD     : DCD OFF
,03-17 13:21:58.495  1017  1328 E Watchdog: !@Sync 53
,03-17 13:22:00.375   292   292 E SMD     : DCD OFF
,03-17 13:22:03.375   292   292 E SMD     : DCD OFF
,03-17 13:22:03.415  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:22:05.995  1017  1363 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 13:22:05.995  1017  1363 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:22:05.995  1017  1363 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:22:05.995  1017  1363 D BatteryService: stay LED for fully charged
03-17 13:22:05.995  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-17 13:22:05.995  1017  1017 I MotionRecognitionService: Plugged
03-17 13:22:05.995  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
03-17 13:22:06.005  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:22:06.005  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:22:06.005  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-17 13:22:06.005  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:22:06.015  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:22:06.015  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:22:06.025  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:22:06.025  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:22:06.025  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:22:06.025  1172  1172 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:22:06.025  1172  1172 D SViewCoverView: level :100 plugged : 2
,03-17 13:22:06.385   292   292 E SMD     : DCD OFF
,03-17 13:22:09.385   292   292 E SMD     : DCD OFF
,03-17 13:22:12.385   292   292 E SMD     : DCD OFF
,03-17 13:22:13.435  1017  2764 D SSRM:n  : SIOP:: AP = 260
,03-17 13:22:15.385   292   292 E SMD     : DCD OFF
,03-17 13:22:16.055  1017  3781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1400000ms),03-17 13:22:18.385   292   292 E SMD     : DCD OFF
03-17 13:22:18.645  6733  6733 D AndroidRuntime: 
03-17 13:22:18.645  6733  6733 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:22:18.645  6733  6733 D AndroidRuntime: CheckJNI is OFF
03-17 13:22:18.645  6733  6733 D AndroidRuntime: readGMSProperty: start
03-17 13:22:18.645  6733  6733 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:22:18.645  6733  6733 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:22:18.645  6733  6733 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:22:18.645  6733  6733 D AndroidRuntime: readGMSProperty: end
03-17 13:22:18.645  6733  6733 D AndroidRuntime: addProductProperty: start
03-17 13:22:18.805  6733  6733 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:22:18.825  6733  6733 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-17 13:22:18.845  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 13:22:18.845  1017  1030 D PackageManager: START PACKAGE DELETE: observer{516117554}
03-17 13:22:18.845  1017  1030 D PackageManager: pkg{<packageName>}
03-17 13:22:18.845  1017  1030 D PackageManager: user{0}
03-17 13:22:18.845  1017  1030 D PackageManager: caller{2000}
03-17 13:22:18.845  1017  1030 D PackageManager: flags{2}
03-17 13:22:18.845  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 13:22:18.845  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 13:22:18.845  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 13:22:18.845  1017  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 13:22:18.845  1017  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 13:22:18.845  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 13:22:18.845  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 13:22:18.845  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 13:22:18.845  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-17 13:22:18.855  1017  1056 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-17 13:22:18.875  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 13:22:18.875  1017  1043 I ActivityManager: Killing 6071:com.test.thalitest/u0a167 (adj 15): stop com.test.thalitest cause uninstall pkg
03-17 13:22:18.955  1017  1056 W PackageSettings: Skipping PackageSetting{3092cd79 com.example.hello/10346} due to missing metadata
03-17 13:22:19.005  1017  3782 W ActivityManager: Spurious death for ProcessRecord{2d7e4583 6071:com.test.thalitest/u0a167}, curProc for 6071: null
03-17 13:22:19.035  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
03-17 13:22:19.055  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-17 13:22:19.075  4036  4036 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 787us total 25.830ms
03-17 13:22:19.085  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 13:22:19.105  5234  5234 I art     : Explicit concurrent mark sweep GC freed 11534(828KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 722us total 56.871ms
03-17 13:22:19.115  1678  2049 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 13:22:19.115  1839  1839 E SamsungIME: mOCRHelper is null
03-17 13:22:19.145  3694  3694 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:22:19 GMT+01:00 2016
03-17 13:22:19.145  1017  1126 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 13:22:19.145  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:22:19.145  1017  1126 V NetworkStats: performPollLocked(flags=0x3)
03-17 13:22:19.145  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 13:22:19.145  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
03-17 13:22:19.155  1017  1126 V NetworkStats: performPollLocked() took 5ms
03-17 13:22:19.155  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:22:19.165  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.165  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.165  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 13:22:19.175  3694  3694 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-17 13:22:19.175  1017  1138 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-17 13:22:19.175  1017  1138 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-17 13:22:19.175  1017  1138 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 13:22:19.175  1017  1138 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
03-17 13:22:19.175  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.175  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.175  3694  3694 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-17 13:22:19.185  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.185  1017  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.195  6746  6746 E Zygote  : MountEmulatedStorage()
03-17 13:22:19.195  6746  6746 E Zygote  : v2
03-17 13:22:19.195  6746  6746 I libpersona: KNOX_SDCARD checking this for 10090
03-17 13:22:19.195  6746  6746 I libpersona: KNOX_SDCARD not a persona
03-17 13:22:19.195  6746  6746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:22:19.195  6746  6746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:22:19.205  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:22:19.205  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 13:22:19.205  3694  3694 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 13:22:19.215  6746  6746 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:22:19.215  1017  1138 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6746 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 13:22:19.215  3694  3694 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 13:22:19.215  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 13:22:19.215  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
03-17 13:22:19.225  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
03-17 13:22:19.235  1017  1363 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 13:22:19.235  1017  1363 D SecContentProvider2: mCursor = null
03-17 13:22:19.255  6746  6746 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:22:19.255  6746  6746 D ActivityThread: Added TimaKeyStore provider
03-17 13:22:19.265  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
03-17 13:22:19.315  6746  6746 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-17 13:22:19.315  6746  6746 D elm:15121: ELMEngine.ELMEngine( context ).
03-17 13:22:19.315  6746  6746 D elm:15121: MDMBridge.setEnterpriseBridge()
03-17 13:22:19.325  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.325  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.325  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-17 13:22:19.325  6746  6746 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-17 13:22:19.335  6746  6746 D elm:15121: ElmAgentService : onCreate()
03-17 13:22:19.335  6746  6761 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 13:22:19.335  6746  6761 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-17 13:22:19.335  6746  6761 D elm:15121: MDMBridge.getInstance()
03-17 13:22:19.335  6746  6761 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 13:22:19.345  1017  1017 I art     : Explicit concurrent mark sweep GC freed 48631(5MB) AllocSpace objects, 218(3MB) LOS objects, 33% free, 24MB/36MB, paused 4.275ms total 282.015ms
03-17 13:22:19.345  1017  1056 I art     : WaitForGcToComplete blocked for 222.116ms for cause Explicit
03-17 13:22:19.355  6746  6761 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 13:22:19.375  1441  1441 D RegisteredServicesCache: empty dynamic service
03-17 13:22:19.385  6746  6746 D elm:15121: ElmAgentService : onDestroy().
03-17 13:22:19.405  1017  1017 D RCPManagerService: PackageReceiver onReceive()
03-17 13:22:19.405  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-17 13:22:19.405  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.405  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
03-17 13:22:19.425  3694  6745 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-17 13:22:19.425  3694  6745 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
03-17 13:22:19.435  3694  3694 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
03-17 13:22:19.475  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 13:22:19.475  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-17 13:22:19.475  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-17 13:22:19.475  1017  1160 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 13:22:19.475  1017  2764 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 13:22:19.475  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 13:22:19.485  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-17 13:22:19.495  5649  5649 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:22:19.495  5649  5649 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:22:19.495  5649  5649 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:22:19.495  5649  5649 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.525  5736  5736 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-17 13:22:19.525  5736  5736 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
03-17 13:22:19.535  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.535  1017  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.535  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
03-17 13:22:19.545  1017  1056 I art     : Explicit concurrent mark sweep GC freed 13941(735KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.898ms total 193.230ms
03-17 13:22:19.555  4985  4985 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
03-17 13:22:19.565  5601  5601 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.565  1017  1540 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.565  1017  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.565  1017  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 13:22:19.575  1017  3782 I TactileAssist: enable value -1
03-17 13:22:19.575  1017  3782 I TactileAssist: internal enable value -1
03-17 13:22:19.575  1017  3782 I TactileAssist: intensity value -1
03-17 13:22:19.575  1017  3782 I TactileAssist: saveAppList value true
03-17 13:22:19.575  5601  6764 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-17 13:22:19.575  5601  6764 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-17 13:22:19.585  1017  3782 I TactileAssist: List of disabled apps :
03-17 13:22:19.585  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 13:22:19.585  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 13:22:19.585  1017  1042 W TextServicesManagerService: no available spell checker services found
03-17 13:22:19.595  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.595  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.595  1017  1056 D PackageManager: delete codoeFile: 
03-17 13:22:19.595  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 13:22:19.595  1017  1056 I AASA_removePackage: UID=10167 Target=com.test.thalitest
03-17 13:22:19.595  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.595  1017  1056 D PackageManager: result of delete: 1{516117554}
03-17 13:22:19.605  6733  6733 D AndroidRuntime: Shutting down VM
03-17 13:22:19.605  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.605  5827  5827 D Compatibility: onReceive() it will make start service
03-17 13:22:19.605  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 13:22:19.605  1017  1056 D PackageManager: userId{-1}
03-17 13:22:19.605  1017  1056 D PackageManager: andCode{true}
03-17 13:22:19.615  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.615  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.615  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
03-17 13:22:19.615  1017  2111 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.615  1017  2111 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.615  1017  2111 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.615  1017  2111 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.625  5827  6765 D Compatibility: onHandleIntent()
03-17 13:22:19.625  5827  6765 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-17 13:22:19.625  5827  6765 D Compatibility: found: 2
03-17 13:22:19.625  5827  6765 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 13:22:19.625  5827  6765 D Compatibility: skipping ResolveInfo{571c299 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 13:22:19.625  5827  6765 D Compatibility: considering ResolveInfo{1610a95e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 13:22:19.625  5827  6765 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 13:22:19.635  5827  6765 D Compatibility: enabling receiver ResolveInfo{1566f13f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 13:22:19.635  6766  6766 E Zygote  : MountEmulatedStorage()
03-17 13:22:19.635  6766  6766 I libpersona: KNOX_SDCARD checking this for 10055
03-17 13:22:19.635  6766  6766 E Zygote  : v2
03-17 13:22:19.635  6766  6766 I libpersona: KNOX_SDCARD not a persona
03-17 13:22:19.635  6766  6766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:22:19.635  5827  6765 D Compatibility: enabling receiver ResolveInfo{10101a0c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-17 13:22:19.635  1017  2111 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6766 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-17 13:22:19.635  6766  6766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:22:19.635  6766  6766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:22:19.645  5827  6765 D Compatibility: enabling receiver ResolveInfo{3012ef55 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 13:22:19.655  5827  6765 D Compatibility: enabling receiver ResolveInfo{2db9fd6a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-17 13:22:19.665  5827  6765 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
03-17 13:22:19.665  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:22:19.665  6766  6766 D ActivityThread: Added TimaKeyStore provider
03-17 13:22:19.675  1017  1138 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.675  1017  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.675  1017  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
03-17 13:22:19.695  6766  6766 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-17 13:22:19.705  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-17 13:22:19.705  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.705  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.705  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.715  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:22:19.715  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:22:19.715  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:22:19.715  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.735  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.735  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.735  6766  6766 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 13:22:19.735  6766  6766 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 13:22:19.735  6766  6766 D UserAnalysis: Create SecureDbHelper
03-17 13:22:19.735  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.735  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:22:19.735  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.735  6766  6766 D IntelligenceServiceApplication: onCreate()
03-17 13:22:19.745  6766  6766 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
03-17 13:22:19.745  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.745  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:22:19.745  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.745  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 13:22:19.745  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 13:22:19.745  5846  5846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-17 13:22:19.755  6766  6766 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 13:22:19.755  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 13:22:19.755  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-17 13:22:19.755  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.755  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.755  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 13:22:19.755  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-17 13:22:19.755  1017  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.755  1017  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.755  1017  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.755  1017  3781 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.765  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 13:22:19.775  6784  6784 E Zygote  : MountEmulatedStorage()
03-17 13:22:19.775  6784  6784 E Zygote  : v2
03-17 13:22:19.775  6784  6784 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:22:19.775  6784  6784 I libpersona: KNOX_SDCARD not a persona
03-17 13:22:19.775  6784  6784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:22:19.775  1017  3781 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:22:19.775  6784  6784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:22:19.775  6784  6784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:22:19.785  1017  1030 I ActivityManager: Killing 5176:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
03-17 13:22:19.795  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
03-17 13:22:19.795  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
03-17 13:22:19.795  6784  6784 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:22:19.795  6784  6784 D ActivityThread: Added TimaKeyStore provider
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-17 13:22:19.805  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
03-17 13:22:19.815  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
03-17 13:22:19.815  6733  6733 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 13:22:19.815  6784  6784 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:22:19.825  6766  6766 D BluetoothAdapter: cancelDiscovery
03-17 13:22:19.825  2656  2939 D BluetoothAdapterProperties: mDiscovering is false
03-17 13:22:19.825  2656  2939 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
03-17 13:22:19.825  6766  6766 D BluetoothAdapter: cancelDiscovery = true
03-17 13:22:19.825  6766  6766 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
03-17 13:22:19.825  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 13:22:19.825  6766  6766 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 13:22:19.845  1017  1042 W libprocessgroup: failed to open /acct/uid_10032/pid_5176/cgroup.procs: No such file or directory
03-17 13:22:19.845  6784  6784 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-17 13:22:19.855  1017  1540 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-17 13:22:19.855  1017  1540 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-17 13:22:19.855  5866  5866 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
03-17 13:22:19.855  5866  5866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
03-17 13:22:19.865  1017  3781 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:22:19.865  1017  3781 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:22:19.865  1017  3781 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
03-17 13:22:19.875  5866  5866 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
03-17 13:22:19.875  5866  6799 I FilterInstaller: FilterPackageService : ACTION_REMOVED
03-17 13:22:19.875  5866  6799 D FilterUnInstaller: before removeFromFS
03-17 13:22:19.875  1017  3413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.875  1017  3413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.885  1017  3413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.885  1017  3413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.905  6801  6801 E Zygote  : MountEmulatedStorage()
03-17 13:22:19.905  6801  6801 E Zygote  : v2
03-17 13:22:19.905  6801  6801 I libpersona: KNOX_SDCARD checking this for 10095
03-17 13:22:19.905  6801  6801 I libpersona: KNOX_SDCARD not a persona
03-17 13:22:19.905  6801  6801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:22:19.905  1017  3413 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6801 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 13:22:19.905  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.905  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.905  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.915  6801  6801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:22:19.905  1017  3782 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:22:19.915  6801  6801 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:22:19.915  6766  6766 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-17 13:22:19.915  6766  6766 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: Error inserting timestamp=1458217339760 message=Predictor: service is stopped by Application.onCreate
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:22:19.925  6766  6766 E UserAnalysis: It failed to insert to dump_log table
03-17 13:22:19.925  6766  6766 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-17 13:22:19.925  6766  6766 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: Error inserting timestamp=1458217339832 message=Predictor: service stopped by removePlaceCategories()
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:22:19.925  6766  6766 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:22:19.925  6766  6766 E UserAnalysis: It failed to insert to dump_log table
03-17 13:22:19.935   309   309 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 706us total 23.730ms
03-17 13:22:19.945  6801  6801 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:22:19.945  6801  6801 D ActivityThread: Added TimaKeyStore provider
03-17 13:22:19.945   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.792ms
03-17 13:22:19.965   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.771ms
03-17 13:22:19.975  6817  6817 E Zygote  : MountEmulatedStorage()
03-17 13:22:19.975  6817  6817 E Zygote  : v2
03-17 13:22:19.975  6817  6817 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:22:19.975  6817  6817 I libpersona: KNOX_SDCARD not a persona
03-17 13:22:19.985  1017  3782 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6817 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:22:19.985  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:22:19.985  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
```
