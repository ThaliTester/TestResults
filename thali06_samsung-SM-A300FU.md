#### Test 62509094b685d58_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
,03-17 12:31:11.094   293   293 E SMD     : DCD OFF
03-17 12:31:11.384  6093  6093 D AndroidRuntime: 
03-17 12:31:11.384  6093  6093 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:31:11.384  6093  6093 D AndroidRuntime: CheckJNI is OFF
03-17 12:31:11.384  6093  6093 D AndroidRuntime: readGMSProperty: start
03-17 12:31:11.384  6093  6093 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:31:11.384  6093  6093 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:31:11.384  6093  6093 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:31:11.384  6093  6093 D AndroidRuntime: readGMSProperty: end
03-17 12:31:11.384  6093  6093 D AndroidRuntime: addProductProperty: start
03-17 12:31:11.514  6093  6093 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:31:11.544  6093  6093 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:31:11.554  1019  1481 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:31:11.554  1019  1481 I PersonaManagerService: PersonaId don't exist
03-17 12:31:11.554  1019  1481 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:31:11.554  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
03-17 12:31:11.574  1019  1481 W ActivityManager: mDVFSHelper.acquire()
03-17 12:31:11.574  1019  1481 D FocusedStackFrame: Set to : 0
03-17 12:31:11.584  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:11.584  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:11.584  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:11.584  1019  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:11.594  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:31:11.594  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 12:31:11.594  6106  6106 E Zygote  : MountEmulatedStorage()
03-17 12:31:11.594  6106  6106 E Zygote  : v2
03-17 12:31:11.594  6106  6106 I libpersona: KNOX_SDCARD checking this for 10167
03-17 12:31:11.594  6106  6106 I libpersona: KNOX_SDCARD not a persona
03-17 12:31:11.594  6106  6106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 12:31:11.594  6106  6106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 12:31:11.604  6106  6106 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:31:11.604  1019  1481 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6106 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:31:11.604  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:31:11.604  1019  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:31:11.604  1019  1481 D InputDispatcher: Focused application set to: xxxx
03-17 12:31:11.604  1019  1481 D InputDispatcher: Focus left window: 1482
03-17 12:31:11.604  6093  6093 D AndroidRuntime: Shutting down VM
03-17 12:31:11.604  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:31:11.604  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:31:11.604   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-17 12:31:11.624  6106  6106 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:31:11.624  6106  6106 D ActivityThread: Added TimaKeyStore provider
03-17 12:31:11.624  1019  1480 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:31:11.634  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 12:31:11.634  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:31:11.634  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:31:11.644  1019  1480 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:31:11.654  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 12:31:11.684   257  1154 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 12:31:11.684   257   451 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 12:31:11.684  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{3b4aaa62 token=android.os.BinderProxy@2ffbdc53 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 12:31:11.694  1482  1482 D Launcher: onTrimMemory. Level: 20
03-17 12:31:11.754  6106  6106 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 12:31:11.764  6106  6106 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5978-5979)
03-17 12:31:11.774  6106  6106 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:31:11.794  6106  6106 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15f6ad9b}
03-17 12:31:11.804  6106  6106 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:31:11.804  6106  6106 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 12:31:11.814  6093  6093 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 12:31:11.834  6106  6106 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 12:31:11.834  6106  6106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:31:11.834  6106  6106 E SysUtils: ApplicationContext is null in ApplicationStatus
03-17 12:31:11.854  6106  6106 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-17 12:31:11.854  6106  6106 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:31:11.854  6106  6106 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:31:11.854  6106  6106 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:31:11.854  6106  6106 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:31:11.854  6106  6106 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:31:11.854  6106  6106 I Adreno-EGL: Local Branch: 
03-17 12:31:11.854  6106  6106 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:31:11.854  6106  6106 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:31:11.854  6106  6106 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 12:31:12.074  6106  6106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:31:12.094  6106  6106 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-17 12:31:12.094  6106  6106 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:31:12.104  6106  6106 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-17 12:31:12.104  6106  6106 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-17 12:31:12.114  6106  6106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:31:12.114  6106  6106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:31:12.144  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{dc85a4e u0 com.test.thalitest/.MainActivity t23}
03-17 12:31:12.224  6106  6146 D OpenGLRenderer: Render dirty regions requested: true
03-17 12:31:12.224  1019  1480 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 12:31:12.234  1019  1480 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:31:12.234  1019  1480 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:31:12.234  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:31:12.234  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:31:12.244  6106  6133 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-17 12:31:12.244  6106  6106 V ActivityThread: updateVisibility : ActivityRecord{33638903 token=android.os.BinderProxy@2b937bbd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-17 12:31:12.244  6106  6106 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:31:12.244  6106  6106 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:31:12.264   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
03-17 12:31:12.274  1019  1481 D InputDispatcher: Focus entered window: 6106
03-17 12:31:12.274  1019  2750 D SSRM:n  : SIOP:: AP = 260
03-17 12:31:12.284  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:31:12.284  6106  6106 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 12:31:12.284  6106  6146 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 12:31:12.284  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:31:12.284  6106  6146 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 12:31:12.284  6106  6146 D OpenGLRenderer: Enabling debug mode 0
03-17 12:31:12.304  1019  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-17 12:31:12.304  1175  1175 I StatusBar: Icon Only
03-17 12:31:12.304  1175  1175 D PanelView: There is/are notification(s) 
03-17 12:31:12.324  1019  1049 I ActivityManager: Displayed Component not be shown by security: +674ms (total +1m29s132ms)
03-17 12:31:12.324  1019  1049 W ActivityManager: mDVFSHelper.release()
03-17 12:31:12.324  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{dc85a4e u0 com.test.thalitest/.MainActivity t23} time:206535
03-17 12:31:12.334  6106  6106 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-17 12:31:12.334  6106  6106 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b937bbd time:206540
03-17 12:31:12.334  1019  6149 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 12:31:12.334   257   451 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
03-17 12:31:12.334   257  1154 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
03-17 12:31:12.374  1811  1811 I SamsungIME: getCurrentCandidateView
03-17 12:31:12.434  1811  1811 D SamsungIME: Dismiss ExpandCandiate
03-17 12:31:12.464  1811  1811 I SamsungIME: getDebugLevel  : 0x4f4c
03-17 12:31:12.494  6106  6106 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6106
03-17 12:31:12.514  1811  1811 I SamsungIME: getDebugLevel  : 0x4f4c
03-17 12:31:12.534  1811  1811 I SamsungIME: KeybaordView init() : load resources
03-17 12:31:12.554  1019  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 12:31:12.554  1019  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 12:31:12.554  1019  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 12:31:12.554  1019  1479 D BatteryService: stay LED for fully charged
03-17 12:31:12.554  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 12:31:12.564  1019  1019 I MotionRecognitionService: Plugged
03-17 12:31:12.564  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-17 12:31:12.564  1811  1811 I SamsungIME: getCurrentKeyboard
03-17 12:31:12.564  1811  1811 I SamsungIME: getTextKeyboard
03-17 12:31:12.564  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 12:31:12.564  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 12:31:12.564  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 12:31:12.564  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 12:31:12.574  2632  2632 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 12:31:12.574  2632  2729 D HeadsetStateMachine: Disconnected process message: 10
03-17 12:31:12.574  1811  1811 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
03-17 12:31:12.584  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:31:12.584  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:31:12.594  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:31:12.594  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 12:31:12.594  1175  1175 D SViewCoverView: level :100 plugged : 2
03-17 12:31:12.624  6106  6106 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:31:12.814  6106  6150 D jxcore_app_log: JniHelper::setJavaVM(0xb7bae448), pthread_self() = -1206835880
,03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 12:31:12.824  6106  6150 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@942f9b0 added. We now have 1 listener(s)
03-17 12:31:12.824  6106  6150 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
03-17 12:31:12.834  6106  6150 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 12:31:12.834  6106  6150 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 12:31:12.834  6106  6150 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 12:31:12.834  6106  6150 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dabf14f added. We now have 1 listener(s)
,03-17 12:31:12.844  6106  6150 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:31:12.844  6106  6150 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 12:31:12.844  6106  6150 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 12:31:12.844  6106  6150 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 12:31:12.844  6106  6150 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 12:31:12.844  6106  6150 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 12:31:12.854  6106  6150 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 12:31:12.854  6106  6150 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:31:12.854  6106  6150 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 12:31:12.854  6106  6150 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 12:31:12.854  6106  6150 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:31:12.864  6106  6106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:31:12.864  6106  6106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:31:12.884  6106  6106 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:31:13.374  6106  6157 W jxcore-log: Initializing JXcore engine
03-17 12:31:13.374  6106  6157 W jxcore-log: JXcore engine is ready
,03-17 12:31:13.434  1805  1805 E audit   : type=1400 msg=audit(1458214273.434:205): avc:  denied  { ioctl } for  pid=6157 comm="Thread-1049" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 12:31:13.434  1805  1805 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 12:31:13.434  1805  1805 E audit   : type=1300 msg=audit(1458214273.434:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9d4008f8 items=0 ppid=318 ppcomm=main pid=6157 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1049" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 12:31:13.434  1805  1805 E audit   : type=1320 msg=audit(1458214273.434:205): 
,03-17 12:31:13.444  6106  6157 W jxcore-log: Starting JXcore engine
,03-17 12:31:13.554  6106  6157 W jxcore-log: Platform android
03-17 12:31:13.554  6106  6157 W jxcore-log: 
03-17 12:31:13.554  6106  6157 W jxcore-log: Process ARCH arm
03-17 12:31:13.554  6106  6157 W jxcore-log: 
,03-17 12:31:13.774  6106  6157 I jxcore-log: JXcore Cordova bridge is ready!
03-17 12:31:13.774  6106  6157 I jxcore-log: 
,03-17 12:31:13.774  6106  6157 W jxcore-log: JXcore engine is started
,03-17 12:31:13.784  6106  6150 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:31:13.784  6106  6106 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 12:31:13.804  6106  6157 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:31:13.804  6106  6157 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:31:13.814  6106  6106 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 12:31:13.814  6106  6106 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 12:31:13.814  1019  1315 D FocusedStackFrame: Set to : 0
03-17 12:31:13.814  1019  1315 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:31:13.814  1019  1315 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:31:13.814  1019  1315 D InputDispatcher: Focused application set to: xxxx
03-17 12:31:13.814  1019  1315 D InputDispatcher: Focus left window: 6106
03-17 12:31:13.814  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:31:13.814  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:31:13.824  1019  1315 I ActivityManager: Killing 4456:com.google.android.music:main/u0a108 (adj 15): empty #31
03-17 12:31:13.834  6106  6150 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 12:31:13.834   257  1154 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,03-17 12:31:13.844   257   447 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-17 12:31:13.844  1019  1032 W ActivityManager: mDVFSHelper.acquire()
,03-17 12:31:13.854  1019  1032 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 12:31:13.854  6106  6106 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@27d600dc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:31:13.854  6106  6106 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@27d600dc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:31:13.854  6106  6106 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@308995e5 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:31:13.854  6106  6106 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@308995e5 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:31:13.854  6106  6106 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:31:13.874  1482  1482 D Launcher: onRestart, Launcher: 446282358
,03-17 12:31:13.874  1482  1482 D Launcher: onStart, Launcher: 446282358
,03-17 12:31:13.874  1482  1482 D Launcher.HomeView: onStart
03-17 12:31:13.874  1482  1482 D Launcher: onResume, Launcher: 446282358
,03-17 12:31:13.874  1019  3831 D SettingsProvider: name = kids_home_mode
,03-17 12:31:13.874  1019  3831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:31:13.874  1019  3831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:31:13.874  1019  3831 D SettingsProvider: selectionArgs: false
03-17 12:31:13.874  1019  3831 D SettingsProvider: selectionArgs: 10006
,03-17 12:31:13.874  1019  3831 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:31:13.874  1019  3831 D SettingsProvider: ret = -1
,03-17 12:31:13.874  1482  1482 D Launcher.HomeView: onResume
,03-17 12:31:13.874  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:31:13.884  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:13.884  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.884  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
03-17 12:31:13.884  1482  1482 D MenuAppsGridFragment: onResume
,03-17 12:31:13.884  1019  1542 D ActivityManager: handle home activity for 0
,03-17 12:31:13.884  1019  1542 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 12:31:13.884  1019  1542 D KnoxTimeoutHandler: post home show event for user 0
03-17 12:31:13.884  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 12:31:13.884  1019  1542 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 12:31:13.884  1019  1542 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:31:13.884  1019  1542 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 12:31:13.884  1482  1482 D Launcher.HomeView: onPause
,03-17 12:31:13.884  1019  1337 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-17 12:31:13.884  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 12:31:13.884  1019  1337 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
03-17 12:31:13.884  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 12:31:13.894  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:31:13.894  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:31:13.904  1019  1337 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.904  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.904  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-17 12:31:13.904  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:13.904  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.904  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 12:31:13.914  4967  4967 D GalleryCacheReady: Receive : home resume
,03-17 12:31:13.914  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.914  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.914  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-17 12:31:13.914  1019  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_4456/cgroup.procs: No such file or directory
,03-17 12:31:13.914  2533  2533 D Recents_RecreateReceiver: onReceive by home
,03-17 12:31:13.924  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:13.924  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.924  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
03-17 12:31:13.924   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,03-17 12:31:13.924  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:31:13.934  1019  1337 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.934  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.934  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-17 12:31:13.934  4720  4720 D Mms/UIEventReceiver: ui event
,03-17 12:31:13.934  5941  5941 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-17 12:31:13.934  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:31:13.934  1019  1337 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.934  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.934  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-17 12:31:13.944  1019  1214 D InputDispatcher: Focus entered window: 1482
,03-17 12:31:13.944  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:31:13.944  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:31:13.944  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:31:13.944  1019  1337 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:31:13.944  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.944  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-17 12:31:13.954  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{3b4aaa62 token=android.os.BinderProxy@2ffbdc53 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
,03-17 12:31:13.954  1482  1482 D Launcher.HomeView: onStop
03-17 12:31:13.954  1019  1337 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1482, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-17 12:31:13.954  1019  1337 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.954  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.954  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 12:31:13.954  1019  1543 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-17 12:31:13.954  1019  1337 I splitIntent: Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 12:31:13.964  1019  6163 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:31:13.964  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:13.964  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:13.964  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 12:31:13.964  1811  1811 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 12:31:13.964  5941  5941 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 12:31:13.974  1175  1175 I StatusBar: Icon Only
,03-17 12:31:13.974  1175  1175 D PanelView: There is/are notification(s) 
,03-17 12:31:13.974  6106  6106 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:31:13.994  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ffbdc53 time:208201
,03-17 12:31:14.014  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15d123e4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:208221
03-17 12:31:14.014  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-17 12:31:14.104   293   293 E SMD     : DCD OFF,
,03-17 12:31:14.114  6159  6159 D AndroidRuntime: ,
03-17 12:31:14.114  6159  6159 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 12:31:14.124  6159  6159 D AndroidRuntime: CheckJNI is OFF,
,03-17 12:31:14.124  6159  6159 D AndroidRuntime: readGMSProperty: start
03-17 12:31:14.124  6159  6159 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:31:14.124  6159  6159 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:31:14.124  6159  6159 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:31:14.124  6159  6159 D AndroidRuntime: readGMSProperty: end
03-17 12:31:14.124  6159  6159 D AndroidRuntime: addProductProperty: start
,03-17 12:31:14.134  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 12:31:14.334  6159  6159 E AffinityControl: AffinityControl: registerfunction enter
,03-17 12:31:14.354  6159  6159 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 12:31:14.364  1019  1543 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
03-17 12:31:14.364  1019  1543 D PackageManager: START PACKAGE DELETE: observer{814673170}
03-17 12:31:14.364  1019  1543 D PackageManager: pkg{<packageName>}
03-17 12:31:14.364  1019  1543 D PackageManager: user{0}
03-17 12:31:14.364  1019  1543 D PackageManager: caller{2000}
03-17 12:31:14.364  1019  1543 D PackageManager: flags{2}
03-17 12:31:14.364  1019  1543 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 12:31:14.364  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-17 12:31:14.364  1019  1543 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 12:31:14.364  1019  1543 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 12:31:14.364  1019  1543 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 12:31:14.364  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 12:31:14.364  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 12:31:14.364  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled,
03-17 12:31:14.364  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-17 12:31:14.374  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-17 12:31:14.404  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 12:31:14.404  1019  1044 I ActivityManager: Killing 6106:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-17 12:31:14.444  1019  1057 W PackageSettings: Skipping PackageSetting{1365aff1 com.example.hello/10346} due to missing metadata
,03-17 12:31:14.474  1019  1044 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:31:14.484  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 12:31:14.514  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 12:31:14.544  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 12:31:14.564  1811  1811 E SamsungIME: mOCRHelper is null
,03-17 12:31:14.564  4052  4052 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 913us total 44.203ms
,03-17 12:31:14.564  1655  2028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 12:31:14.574  5896  5896 I art     : Explicit concurrent mark sweep GC freed 369(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 2.011ms total 69.992ms
,03-17 12:31:14.614  3727  3727 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:31:14 GMT+01:00 2016
,03-17 12:31:14.624  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-17 12:31:14.624  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 12:31:14.624  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-17 12:31:14.634  1019  1123 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-17 12:31:14.634  1019  1123 V NetworkStats: performPollLocked(flags=0x3)
,03-17 12:31:14.644  1019  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 12:31:14.644  1019  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 12:31:14.644  1019  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 12:31:14.644  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.644  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:14.644  1019  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:14.644  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:31:14.644  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.654  1019  1123 V NetworkStats: performPollLocked() took 9ms
03-17 12:31:14.654  1019  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 12:31:14.654  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.664  3727  3727 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:31:14.664  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.664  1019  1543 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,03-17 12:31:14.664  1019  1543 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,03-17 12:31:14.664  1019  1543 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 12:31:14.664  1019  1543 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-17 12:31:14.674  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:14.674  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:14.674  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:14.674  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:31:14.684  1019  1542 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 12:31:14.684  1019  1542 D SecContentProvider2: mCursor = null
,03-17 12:31:14.684  3727  3727 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 12:31:14.684  1019  1543 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6177 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-17 12:31:14.694  6177  6177 E Zygote  : MountEmulatedStorage()
03-17 12:31:14.694  6177  6177 I libpersona: KNOX_SDCARD checking this for 10090
03-17 12:31:14.694  6177  6177 E Zygote  : v2
03-17 12:31:14.694  6177  6177 I libpersona: KNOX_SDCARD not a persona
,03-17 12:31:14.694  6177  6177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 12:31:14.694  6177  6177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:31:14.694  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 12:31:14.694  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 12:31:14.704  6177  6177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:31:14.704  3727  3727 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:31:14.704  3727  3727 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:31:14.724  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 12:31:14.734  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-17 12:31:14.734  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-17 12:31:14.734  6177  6177 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:31:14.744  6177  6177 D ActivityThread: Added TimaKeyStore provider
,03-17 12:31:14.744  1019  1019 I art     : Explicit concurrent mark sweep GC freed 31376(2MB) AllocSpace objects, 11(180KB) LOS objects, 33% free, 24MB/36MB, paused 3.339ms total 233.931ms
,03-17 12:31:14.754  1019  1057 I art     : WaitForGcToComplete blocked for 122.313ms for cause Explicit
,03-17 12:31:14.754  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-17 12:31:14.774  1441  1441 D RegisteredServicesCache: empty dynamic service
,03-17 12:31:14.824  6177  6177 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 12:31:14.824  6177  6177 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 12:31:14.824  6177  6177 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 12:31:14.824  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:14.824  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:14.824  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 12:31:14.824  6177  6177 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 12:31:14.824  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-17 12:31:14.834  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 12:31:14.834  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.834  6177  6177 D elm:15121: ElmAgentService : onCreate()
,03-17 12:31:14.834  6177  6192 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 12:31:14.834  6177  6192 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-17 12:31:14.834  6177  6192 D elm:15121: MDMBridge.getInstance()
03-17 12:31:14.844  6177  6192 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:31:14.844  6177  6192 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:31:14.844  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.844  3727  6176 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-17 12:31:14.844  3727  6176 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-17 12:31:14.854  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.854  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:31:14.854  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:31:14.854  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:31:14.854  3727  3727 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 12:31:14.854  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.864  6177  6177 D elm:15121: ElmAgentService : onDestroy().
,03-17 12:31:14.884  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-17 12:31:14.884  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 12:31:14.894  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 12:31:14.904  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.904  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.914  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:31:14.914  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:31:14.924  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.924  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:31:14.924  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:31:14.924  1019  1057 I art     : Explicit concurrent mark sweep GC freed 9850(458KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.479ms total 176.384ms
,03-17 12:31:14.934  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:31:14.934  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:31:14.954  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:31:14.964  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-17 12:31:14.964  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 12:31:14.994  1019  1057 D PackageManager: delete codoeFile: 
,03-17 12:31:14.994  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 12:31:14.994  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 12:31:14.994  1019  1057 D PackageManager: result of delete: 1{814673170}
,03-17 12:31:14.994  6159  6159 D AndroidRuntime: Shutting down VM
,03-17 12:31:15.004  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 12:31:15.004  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: uID is 10167
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 12:31:15.004  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 12:31:15.004  1019  1161 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0,
03-17 12:31:15.004  1019  2750 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null,
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 12:31:15.004  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 12:31:15.024  5649  5649 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 12:31:15.024  5649  5649 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:31:15.024  5649  5649 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:31:15.024  5649  5649 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-17 12:31:15.034  5782  5782 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ],
03-17 12:31:15.034  5782  5782 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-17 12:31:15.034  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:15.034  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:31:15.034  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-17 12:31:15.044  4967  4967 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-17 12:31:15.074  4720  4720 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-17 12:31:15.074  1019  1540 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:15.074  1019  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:15.074  1019  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 12:31:15.084  1019  1481 I TactileAssist: enable value -1
,03-17 12:31:15.084  1019  1481 I TactileAssist: internal enable value -1
,03-17 12:31:15.084  1019  1481 I TactileAssist: intensity value -1
03-17 12:31:15.084  1019  1481 I TactileAssist: saveAppList value true
,03-17 12:31:15.094  4720  6195 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,03-17 12:31:15.094  4720  6195 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,03-17 12:31:15.094  1019  1481 I TactileAssist: List of disabled apps :
,03-17 12:31:15.114  5728  5728 D Compatibility: onReceive() it will make start service
,03-17 12:31:15.114  1019  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:15.114  1019  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:15.114  1019  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-17 12:31:15.124  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.124  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.124  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.124  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:31:15.124  5728  6196 D Compatibility: onHandleIntent()
,03-17 12:31:15.134  5728  6196 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-17 12:31:15.134  6197  6197 E Zygote  : MountEmulatedStorage()
03-17 12:31:15.134  6197  6197 E Zygote  : v2
03-17 12:31:15.134  6197  6197 I libpersona: KNOX_SDCARD checking this for 10055
03-17 12:31:15.134  6197  6197 I libpersona: KNOX_SDCARD not a persona
,03-17 12:31:15.134  6197  6197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 12:31:15.134  5728  6196 D Compatibility: found: 2
03-17 12:31:15.134  5728  6196 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 12:31:15.134  5728  6196 D Compatibility: skipping ResolveInfo{23cf5538 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 12:31:15.134  5728  6196 D Compatibility: considering ResolveInfo{c8e8911 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 12:31:15.134  5728  6196 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-17 12:31:15.134  5728  6196 D Compatibility: enabling receiver ResolveInfo{1a99ba76 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 12:31:15.134  6197  6197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:31:15.134  6197  6197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:31:15.144  5728  6196 D Compatibility: enabling receiver ResolveInfo{17888877 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 12:31:15.144  1019  1479 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6197 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 12:31:15.144  5728  6196 D Compatibility: enabling receiver ResolveInfo{21c08ce4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 12:31:15.144  1019  1481 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:15.144  1019  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:15.144  1019  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-17 12:31:15.154  5728  6196 D Compatibility: enabling receiver ResolveInfo{2641a54d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 12:31:15.154  5728  6196 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-17 12:31:15.164  6197  6197 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:31:15.164  6197  6197 D ActivityThread: Added TimaKeyStore provider,
,03-17 12:31:15.184  6197  6197 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 12:31:15.204  6159  6159 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 12:31:15.214  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 12:31:15.214  1019  1057 D PackageManager: userId{-1}
03-17 12:31:15.214  1019  1057 D PackageManager: andCode{true}
03-17 12:31:15.224  6197  6197 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 12:31:15.224  6197  6197 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 12:31:15.224  6197  6197 D UserAnalysis: Create SecureDbHelper
03-17 12:31:15.224  6197  6197 D IntelligenceServiceApplication: onCreate()
03-17 12:31:15.224  6197  6197 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
03-17 12:31:15.234  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
03-17 12:31:15.234  6197  6197 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 12:31:15.234  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:31:15.234  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:15.234  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 12:31:15.234  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 12:31:15.234  1019  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.234  1019  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.234  1019  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.234  1019  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:31:15.254  6215  6215 E Zygote  : MountEmulatedStorage()
03-17 12:31:15.254  6215  6215 E Zygote  : v2
03-17 12:31:15.254  6215  6215 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:31:15.254  6215  6215 I libpersona: KNOX_SDCARD not a persona
03-17 12:31:15.254  6215  6215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:31:15.254  1019  1540 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 12:31:15.254  6215  6215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 12:31:15.254  6215  6215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:31:15.254  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 12:31:15.264  1019  3831 I ActivityManager: Killing 4037:com.google.android.talk/u0a102 (adj 15): empty #31
,03-17 12:31:15.284  6215  6215 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:31:15.284  6215  6215 D ActivityThread: Added TimaKeyStore provider
,03-17 12:31:15.294  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,03-17 12:31:15.294  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,03-17 12:31:15.304  6215  6215 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,03-17 12:31:15.304  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,03-17 12:31:15.314  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,03-17 12:31:15.324  6197  6197 D BluetoothAdapter: cancelDiscovery
,03-17 12:31:15.324  2632  2645 D BluetoothAdapterProperties: mDiscovering is false
,03-17 12:31:15.324  2632  2645 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,03-17 12:31:15.324  6197  6197 D BluetoothAdapter: cancelDiscovery = true,
,03-17 12:31:15.324  6197  6197 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
03-17 12:31:15.324  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-17 12:31:15.324  6197  6197 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 12:31:15.324  6197  6197 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 12:31:15.324  6197  6197 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 12:31:15.324  6197  6197 E UserAnalysis: It failed to get the database for dump_log
03-17 12:31:15.324  6197  6197 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 12:31:15.324  6197  6197 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 12:31:15.324  6197  6197 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 12:31:15.324  6197  6197 E UserAnalysis: It failed to get the database for dump_log
,03-17 12:31:15.354  6215  6215 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-17 12:31:15.364  1019  1479 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-17 12:31:15.364  1019  1479 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-17 12:31:15.364  5802  5802 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,03-17 12:31:15.364  5802  5802 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:31:15.374  1019  1315 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:31:15.374  1019  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:31:15.374  1019  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,03-17 12:31:15.384  5802  5802 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,03-17 12:31:15.384  5802  6231 I FilterInstaller: FilterPackageService : ACTION_REMOVED,
03-17 12:31:15.384  5802  6231 D FilterUnInstaller: before removeFromFS
,03-17 12:31:15.394  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:31:15.394  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.394  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:31:15.394  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:31:15.404  1019  1032 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6232 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 12:31:15.414  6232  6232 E Zygote  : MountEmulatedStorage()
03-17 12:31:15.414  6232  6232 E Zygote  : v2
03-17 12:31:15.414  6232  6232 I libpersona: KNOX_SDCARD checking this for 10095
03-17 12:31:15.414  6232  6232 I libpersona: KNOX_SDCARD not a persona
,03-17 12:31:15.414  6232  6232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 12:31:15.424  6232  6232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 12:31:15.424  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
