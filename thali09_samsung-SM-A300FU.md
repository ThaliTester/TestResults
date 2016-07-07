#### Test 7214543179cc02a_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main,
07-07 12:13:18.733   294   294 E SMD     : DCD OFF
07-07 12:13:19.003  6734  6734 D AndroidRuntime: 
07-07 12:13:19.003  6734  6734 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-07 12:13:19.013  6734  6734 D AndroidRuntime: CheckJNI is OFF
07-07 12:13:19.013  6734  6734 D AndroidRuntime: readGMSProperty: start
07-07 12:13:19.013  6734  6734 D AndroidRuntime: readGMSProperty: already setted!!
07-07 12:13:19.013  6734  6734 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 12:13:19.013  6734  6734 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 12:13:19.013  6734  6734 D AndroidRuntime: readGMSProperty: end
07-07 12:13:19.013  6734  6734 D AndroidRuntime: addProductProperty: start
07-07 12:13:19.143  6734  6734 E AffinityControl: AffinityControl: registerfunction enter
07-07 12:13:19.163  6734  6734 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 12:13:19.183  1014  1503 E PersonaManagerService: inState():  stateMachine is null !!
07-07 12:13:19.183  1014  1503 I PersonaManagerService: PersonaId don't exist
07-07 12:13:19.183  1014  1503 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-07 12:13:19.183  1014  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-07 12:13:19.193  1014  1503 W ActivityManager: mDVFSHelper.acquire()
07-07 12:13:19.203  1014  1503 D FocusedStackFrame: Set to : 0
07-07 12:13:19.203  1014  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:19.203  1014  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:19.203  1014  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:19.203  1014  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:19.203  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-07 12:13:19.203  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-07 12:13:19.223  6745  6745 E Zygote  : MountEmulatedStorage()
07-07 12:13:19.223  6745  6745 E Zygote  : v2
07-07 12:13:19.223  6745  6745 I libpersona: KNOX_SDCARD checking this for 10170
07-07 12:13:19.223  1014  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 12:13:19.223  1014  1503 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6745 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-07 12:13:19.223  1014  1503 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 12:13:19.223  1014  1503 D InputDispatcher: Focused application set to: xxxx
07-07 12:13:19.223  1014  1503 D InputDispatcher: Focus left window: 1494
07-07 12:13:19.223  6745  6745 I libpersona: KNOX_SDCARD not a persona
07-07 12:13:19.223  6734  6734 D AndroidRuntime: Shutting down VM
07-07 12:13:19.223  6745  6745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 12:13:19.223  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-07 12:13:19.223  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-07 12:13:19.223  6745  6745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:19.223   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-07 12:13:19.233  6745  6745 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-07 12:13:19.253  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 12:13:19.253  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 12:13:19.253  6745  6745 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 12:13:19.253  6745  6745 D ActivityThread: Added TimaKeyStore provider
07-07 12:13:19.253  1014  4047 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-07 12:13:19.253  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 12:13:19.263  1014  4047 D PersonaManager: isKioskContainerExistOnDevice
07-07 12:13:19.273  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-07 12:13:19.313   258  1036 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-07 12:13:19.313   258   443 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-07 12:13:19.313  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{5eb76d4 token=android.os.BinderProxy@3df4788f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-07 12:13:19.313  1494  1494 D Launcher: onTrimMemory. Level: 20
07-07 12:13:19.383  6745  6745 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-07 12:13:19.393  6745  6745 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5576-5577)
07-07 12:13:19.393  6745  6745 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 12:13:19.423  6745  6745 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dde30ac}
07-07 12:13:19.423  6745  6745 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 12:13:19.423  6745  6745 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 12:13:19.433  6734  6734 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-07 12:13:19.453  6745  6745 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 12:13:19.453  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 12:13:19.453  6745  6745 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 12:13:19.473  6745  6745 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-07 12:13:19.473  6745  6745 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-07 12:13:19.473  6745  6745 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-07 12:13:19.483  6745  6745 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-07 12:13:19.483  6745  6745 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-07 12:13:19.483  6745  6745 I Adreno-EGL: Build Date: 04/06/15 Mon
07-07 12:13:19.483  6745  6745 I Adreno-EGL: Local Branch: 
07-07 12:13:19.483  6745  6745 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-07 12:13:19.483  6745  6745 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-07 12:13:19.483  6745  6745 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-07 12:13:19.693  6745  6771 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-07 12:13:19.733  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 12:13:19.753  6745  6745 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 12:13:19.763  6745  6745 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-07 12:13:19.763  6745  6745 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-07 12:13:19.763  6745  6745 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-07 12:13:19.773  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 12:13:19.773  6745  6745 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 12:13:19.773  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{2e310801 u0 com.test.thalitest/.MainActivity t44}
,07-07 12:13:19.843  6745  6784 D OpenGLRenderer: Render dirty regions requested: true
,07-07 12:13:19.853  1014  1529 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-07 12:13:19.853  1014  1529 D KnoxTimeoutHandler: postActiveUserChange for user 0,
07-07 12:13:19.853  1014  1529 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 12:13:19.853  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-07 12:13:19.853  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
,07-07 12:13:19.863  6745  6745 V ActivityThread: updateVisibility : ActivityRecord{1a4e4747 token=android.os.BinderProxy@3dfc5761 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-07 12:13:19.863  6745  6745 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-07 12:13:19.863  6745  6745 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-07 12:13:19.873   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-07 12:13:19.893  1014  1889 D InputDispatcher: Focus entered window: 6745
,07-07 12:13:19.893  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-07 12:13:19.893  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 12:13:19.893  6745  6745 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-07 12:13:19.893  6745  6784 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 12:13:19.903  6745  6784 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-07 12:13:19.903  6745  6784 D OpenGLRenderer: Enabling debug mode 0
,07-07 12:13:19.923  1014  1531 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-07 12:13:19.923  1168  1168 I StatusBar: Icon Only
,07-07 12:13:19.923  1168  1168 D PanelView: There is/are notification(s) 
,07-07 12:13:19.923  1014  6786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 12:13:19.943  1014  1045 I ActivityManager: Displayed Component not be shown by security: +667ms (total +2m11s736ms)
,07-07 12:13:19.943  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e310801 u0 com.test.thalitest/.MainActivity t44} time:246121
07-07 12:13:19.943  1014  1045 W ActivityManager: mDVFSHelper.release()
,07-07 12:13:19.943   258  2533 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-07 12:13:19.943   258  1036 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-07 12:13:19.953  6745  6745 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 12:13:19.953  6745  6745 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3dfc5761 time:246130
07-07 12:13:19.953  1902  1902 I SamsungIME: getCurrentCandidateView
,07-07 12:13:20.053  6745  6745 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6745
,07-07 12:13:20.063  1902  1902 D SamsungIME: Dismiss ExpandCandiate
,07-07 12:13:20.183  6745  6745 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 12:13:20.213  1902  1902 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 12:13:20.243  1902  1902 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 12:13:20.253  1902  1902 I SamsungIME: KeybaordView init() : load resources
,07-07 12:13:20.293  1902  1902 I SamsungIME: getCurrentKeyboard
07-07 12:13:20.293  1902  1902 I SamsungIME: getTextKeyboard
,07-07 12:13:20.313  1902  1902 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-07 12:13:20.343  6745  6789 D jxcore_app_log: JniHelper::setJavaVM(0xb791c2f0), pthread_self() = -1209568520
,07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-07 12:13:20.353  6745  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38519037 added. We now have 1 listener(s)
,07-07 12:13:20.353  6745  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27,
07-07 12:13:20.353  6745  6789 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-07 12:13:20.363  6745  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 12:13:20.363  6745  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
,07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 12:13:20.363  6745  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97282c2 added. We now have 1 listener(s)
07-07 12:13:20.363  6745  6789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,07-07 12:13:20.373  6745  6789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-07 12:13:20.373  6745  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-07 12:13:20.373  6745  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-07 12:13:20.373  6745  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 12:13:20.373  6745  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-07 12:13:20.383  6745  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 12:13:20.383  6745  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 12:13:20.393  6745  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-07 12:13:20.393  6745  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 12:13:20.393  6745  6789 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 12:13:20.393  6745  6789 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 12:13:20.393  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 12:13:20.393  6745  6745 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 12:13:20.423  6745  6745 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,07-07 12:13:20.853  1014  1215 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-07 12:13:20.863  1014  1215 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-07 12:13:20.863  1014  1215 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-07 12:13:20.863  1014  1215 D BatteryService: stay LED for fully charged
07-07 12:13:20.863  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-07 12:13:20.873  1014  1014 I MotionRecognitionService: Plugged
,07-07 12:13:20.873  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-07 12:13:20.873  1168  1168 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-07 12:13:20.873  1168  1168 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-07 12:13:20.873  1431  1431 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-07 12:13:20.873  1431  1431 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-07 12:13:20.883  3378  3378 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-07 12:13:20.883  3378  3472 D HeadsetStateMachine: Disconnected process message: 10
,07-07 12:13:20.893  1168  1168 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-07 12:13:20.893  1168  1168 D SViewCoverView: level :100 plugged : 2,
07-07 12:13:20.893  1168  1168 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-07 12:13:20.893  1168  1168 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-07 12:13:20.893  1168  1168 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-07 12:13:20.993  6745  6794 W jxcore-log: Initializing JXcore engine,
,07-07 12:13:20.993  6745  6794 W jxcore-log: JXcore engine is ready
,07-07 12:13:21.053  1943  1943 E audit   : type=1400 msg=audit(1467886401.043:205): avc:  denied  { ioctl } for  pid=6794 comm="Thread-1203" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 12:13:21.053  1943  1943 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:21.053  1943  1943 E audit   : type=1300 msg=audit(1467886401.043:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=2 a3=9e5008f8 items=0 ppid=322 ppcomm=main pid=6794 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1203" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-07 12:13:21.053  1943  1943 E audit   : type=1320 msg=audit(1467886401.043:205): 
,07-07 12:13:21.063  6745  6794 W jxcore-log: Starting JXcore engine
,07-07 12:13:21.163  6745  6794 W jxcore-log: Platform android
07-07 12:13:21.163  6745  6794 W jxcore-log: 
07-07 12:13:21.163  6745  6794 W jxcore-log: Process ARCH arm
07-07 12:13:21.163  6745  6794 W jxcore-log: 
,07-07 12:13:21.373  6745  6794 I jxcore-log: JXcore Cordova bridge is ready!
07-07 12:13:21.373  6745  6794 I jxcore-log: 
,07-07 12:13:21.373  6745  6794 W jxcore-log: JXcore engine is started
,07-07 12:13:21.373  6745  6789 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 12:13:21.373  6745  6745 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 12:13:21.383  6745  6794 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 12:13:21.383  6745  6794 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 12:13:21.393  6745  6745 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-07 12:13:21.393  6745  6745 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 12:13:21.393  1014  1529 D FocusedStackFrame: Set to : 0
07-07 12:13:21.393  1014  1529 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 12:13:21.393  1014  1529 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 12:13:21.393  1014  1529 D InputDispatcher: Focused application set to: xxxx
07-07 12:13:21.393  1014  1529 D InputDispatcher: Focus left window: 6745
07-07 12:13:21.403  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 12:13:21.403  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 12:13:21.403  1014  1529 I ActivityManager: Killing 6271:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-07 12:13:21.403  6745  6745 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 12:13:21.403  6745  6745 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-07 12:13:21.413  6745  6745 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 12:13:21.413  6745  6745 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 12:13:21.413  6745  6745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 12:13:21.413  6745  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 12:13:21.413  6745  6745 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38519037 removed from the list
07-07 12:13:21.413  6745  6745 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 12:13:21.413  6745  6745 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97282c2 removed from the list
07-07 12:13:21.413  6745  6745 D io.jxcore.node.ConnectivityMonitor: stop
07-07 12:13:21.413  6745  6745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 12:13:21.413  6745  6745 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 12:13:21.423   258  1036 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-07 12:13:21.423   258   448 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-07 12:13:21.433  1014  1889 W ActivityManager: mDVFSHelper.acquire()
,07-07 12:13:21.433  1014  1889 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-07 12:13:21.453  1494  1494 D Launcher: onRestart, Launcher: 139701144
,07-07 12:13:21.463  1494  1494 D Launcher: onStart, Launcher: 139701144
,07-07 12:13:21.463  1494  1494 D Launcher.HomeView: onStart
07-07 12:13:21.463  1494  1494 D Launcher: onResume, Launcher: 139701144
,07-07 12:13:21.463  1014  1026 D SettingsProvider: name = kids_home_mode
07-07 12:13:21.463  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-07 12:13:21.463  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-07 12:13:21.463  1014  1026 D SettingsProvider: selectionArgs: false
07-07 12:13:21.463  1014  1026 D SettingsProvider: selectionArgs: 10006
07-07 12:13:21.463  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-07 12:13:21.463  1014  1026 D SettingsProvider: ret = -1
,07-07 12:13:21.463  1494  1494 D Launcher.HomeView: onResume
,07-07 12:13:21.473  1494  1494 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-07 12:13:21.473  1494  1494 D MenuAppsGridFragment: onResume
,07-07 12:13:21.473  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-07 12:13:21.473  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.473  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-07 12:13:21.483  1494  1494 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,07-07 12:13:21.483  1014  1027 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
07-07 12:13:21.483  1014  1027 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-07 12:13:21.483  1494  1494 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-07 12:13:21.483  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.483  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
07-07 12:13:21.483  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.483  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-07 12:13:21.483  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.483  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.483  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.483  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.503  6800  6800 E Zygote  : MountEmulatedStorage(),
,07-07 12:13:21.503  6800  6800 E Zygote  : v2
,07-07 12:13:21.503  6800  6800 I libpersona: KNOX_SDCARD checking this for 10039
07-07 12:13:21.503  6800  6800 I libpersona: KNOX_SDCARD not a persona
,07-07 12:13:21.503  1014  1027 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6800 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-07 12:13:21.503  6800  6800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 12:13:21.513  1014  1133 D ActivityManager: handle home activity for 0
07-07 12:13:21.513  1014  1133 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-07 12:13:21.513  1014  1133 D KnoxTimeoutHandler: post home show event for user 0
07-07 12:13:21.513  1014  1133 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-07 12:13:21.513  1014  1133 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 12:13:21.513  1014  1133 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 12:13:21.513  1494  1494 D Launcher.HomeView: onPause
,07-07 12:13:21.513  1494  1494 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-07 12:13:21.513  6800  6800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 12:13:21.513  6800  6800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 12:13:21.513  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.513  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.513  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-07 12:13:21.513  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,07-07 12:13:21.513  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-07 12:13:21.513  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-07 12:13:21.513  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-07 12:13:21.513  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-07 12:13:21.513  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.513  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.513  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.513  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-07 12:13:21.513  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.513  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-07 12:13:21.513  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.533  6810  6810 E Zygote  : MountEmulatedStorage()
,07-07 12:13:21.533  6810  6810 E Zygote  : v2
07-07 12:13:21.533  6810  6810 I libpersona: KNOX_SDCARD checking this for 10089
,07-07 12:13:21.533  6810  6810 I libpersona: KNOX_SDCARD not a persona
07-07 12:13:21.533  1014  1040 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6810 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,07-07 12:13:21.533  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-07 12:13:21.533  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.533  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-07 12:13:21.533  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,07-07 12:13:21.533  6810  6810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 12:13:21.533  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.533  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.533  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.533  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.543  6810  6810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-07 12:13:21.543  6810  6810 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-07 12:13:21.553  6824  6824 E Zygote  : MountEmulatedStorage(),
07-07 12:13:21.553  1014  1040 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6824 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-07 12:13:21.553  6824  6824 E Zygote  : v2
07-07 12:13:21.553  6824  6824 I libpersona: KNOX_SDCARD checking this for 10139
07-07 12:13:21.553  6824  6824 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 12:13:21.553  6824  6824 I libpersona: KNOX_SDCARD not a persona
07-07 12:13:21.553  6824  6824 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:21.553  6824  6824 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 12:13:21.563  6810  6810 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 12:13:21.563  6810  6810 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:21.573  6800  6800 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 12:13:21.573  6800  6800 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:21.583   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
07-07 12:13:21.583  6824  6824 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 12:13:21.583  6824  6824 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:21.583  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.583  1014  1485 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1494, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-07 12:13:21.583  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.583  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 12:13:21.583  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-07 12:13:21.593  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-07 12:13:21.593  1014  1027 D InputDispatcher: Focus entered window: 1494
,07-07 12:13:21.593  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-07 12:13:21.593  1014  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.593  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
07-07 12:13:21.593  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 12:13:21.593  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-07 12:13:21.593  2615  2615 D Recents_RecreateReceiver: onReceive by home
07-07 12:13:21.593  1494  1494 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-07 12:13:21.593  1014  1529 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.593  1014  1529 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-07 12:13:21.593  1014  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.593  1014  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-07 12:13:21.603  1014  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.603  1014  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.603  1014  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.603  1014  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.603  1494  1494 D Launcher.HomeView: onStop
07-07 12:13:21.603  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{5eb76d4 token=android.os.BinderProxy@3df4788f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-07 12:13:21.613  1014  1487 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-07 12:13:21.613  6810  6810 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 12:13:21.613  6810  6810 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-07 12:13:21.613  1014  6848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 12:13:21.613  6745  6745 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-07 12:13:21.613  6800  6800 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-07 12:13:21.623  1902  1902 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-07 12:13:21.623  1168  1168 I StatusBar: Icon Only
07-07 12:13:21.623  1168  1168 D PanelView: There is/are notification(s) 
,07-07 12:13:21.633  6850  6850 E Zygote  : MountEmulatedStorage()
,07-07 12:13:21.633  6850  6850 E Zygote  : v2
07-07 12:13:21.633  6850  6850 I libpersona: KNOX_SDCARD checking this for 10084
07-07 12:13:21.633  6850  6850 I libpersona: KNOX_SDCARD not a persona
,07-07 12:13:21.633  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-07 12:13:21.633  1014  1529 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6850 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-07 12:13:21.633  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:21.643  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-07 12:13:21.653  1494  1494 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3df4788f time:247831
,07-07 12:13:21.653  6824  6824 V TaskCloserActivity: TaskCloserActivity enter()
,07-07 12:13:21.663  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 12:13:21.663  6850  6850 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:21.673  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38b9afd0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:247858
07-07 12:13:21.673  1014  1045 W ActivityManager: mDVFSHelper.release()
,07-07 12:13:21.683  6824  6824 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-07 12:13:21.683  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.683  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.683  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-07 12:13:21.683  1014  1026 I ActivityManager: Killing 6310:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-07 12:13:21.683  6850  6850 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 12:13:21.703  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:21.703  1014  1215 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-07 12:13:21.703  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:21.703  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-07 12:13:21.703  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.703  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.703  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:21.703  1014  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:21.713  6797  6797 D AndroidRuntime: ,
,07-07 12:13:21.713  6797  6797 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-07 12:13:21.713  6797  6797 D AndroidRuntime: CheckJNI is OFF
07-07 12:13:21.713  6797  6797 D AndroidRuntime: readGMSProperty: start
,07-07 12:13:21.713  6797  6797 D AndroidRuntime: readGMSProperty: already setted!!
07-07 12:13:21.713  6797  6797 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 12:13:21.713  6797  6797 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 12:13:21.713  6797  6797 D AndroidRuntime: readGMSProperty: end,
07-07 12:13:21.713  6797  6797 D AndroidRuntime: addProductProperty: start
,07-07 12:13:21.723  6867  6867 E Zygote  : MountEmulatedStorage(),
07-07 12:13:21.723  6867  6867 E Zygote  : v2
07-07 12:13:21.723  6867  6867 I libpersona: KNOX_SDCARD checking this for 10135
07-07 12:13:21.723  6867  6867 I libpersona: KNOX_SDCARD not a persona,
,07-07 12:13:21.723  6867  6867 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 12:13:21.723  6867  6867 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 12:13:21.723  1014  1215 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6867 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-07 12:13:21.733  6867  6867 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 12:13:21.723  1014  1215 I ActivityManager: Killing 6352:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
07-07 12:13:21.733  1014  1133 I ActivityManager: Killing 6325:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-07 12:13:21.733  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
07-07 12:13:21.733   294   294 E SMD     : DCD OFF
,07-07 12:13:21.753  1014  1889 D PersonaManager: isKioskContainerExistOnDevice
,07-07 12:13:21.753  6867  6867 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 12:13:21.753  6867  6867 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:21.773  6867  6867 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-07 12:13:21.773  6867  6867 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 12:13:21.773  6867  6867 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-07 12:13:21.773  6867  6867 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-07 12:13:21.773  6867  6867 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-07 12:13:21.813  1014  1485 I ActivityManager: Killing 6192:com.android.mms/u0a41 (adj 15): empty #21
,07-07 12:13:21.813  6800  6800 D NearbySource: Nearby Source Create!
,07-07 12:13:21.813  6800  6800 D NearbyContext: Nearby Context Create!
,07-07 12:13:21.843  6797  6797 E AffinityControl: AffinityControl: registerfunction enter
,07-07 12:13:21.853   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-07 12:13:21.853   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,07-07 12:13:21.853  6800  6800 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-07 12:13:21.853  6800  6800 D SLinkSource: Samsung link source created
07-07 12:13:21.863  6797  6797 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-07 12:13:21.873  1014  1215 D PackageManager: START PACKAGE DELETE: observer{240459703}
07-07 12:13:21.873  1014  1215 D PackageManager: pkg{<packageName>}
07-07 12:13:21.873  1014  1215 D PackageManager: user{0}
07-07 12:13:21.873  1014  1215 D PackageManager: caller{2000}
07-07 12:13:21.873  1014  1215 D PackageManager: flags{2}
07-07 12:13:21.873  1014  1215 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-07 12:13:21.873  1014  1215 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-07 12:13:21.873  1014  1215 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-07 12:13:21.873  1014  1215 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 12:13:21.873  1014  1215 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 12:13:21.883  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-07 12:13:21.883  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-07 12:13:21.883  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-07 12:13:21.883  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-07 12:13:21.883  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-07 12:13:21.883  1014  1055 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-07 12:13:21.883  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
07-07 12:13:21.883  1014  1040 I ActivityManager: Killing 6745:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-07 12:13:21.913  1014  1529 D CountryDetector: No listener is left
,07-07 12:13:21.983  1014  1055 W PackageSettings: Skipping PackageSetting{291e8e1f com.example.hello/10168} due to missing metadata
,07-07 12:13:22.013  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 12:13:22.023  6800  6892 D ContactProvider: getAllContactInfoList Start
,07-07 12:13:22.033  1014  1503 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-07 12:13:22.033  6800  6800 D GalleryCacheReady: Receive : home resume
,07-07 12:13:22.043  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,07-07 12:13:22.043  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:22.043  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-07 12:13:22.043  1014  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-07 12:13:22.043  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.043  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.043  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.043  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:22.073  6894  6894 E Zygote  : MountEmulatedStorage()
07-07 12:13:22.073  6894  6894 E Zygote  : v2
,07-07 12:13:22.073  6894  6894 I libpersona: KNOX_SDCARD checking this for 10041
07-07 12:13:22.073  6894  6894 I libpersona: KNOX_SDCARD not a persona
,07-07 12:13:22.073  1014  1485 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=6894 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-07 12:13:22.073  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 12:13:22.073  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
07-07 12:13:22.073  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 12:13:22.073  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-07 12:13:22.123  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-07 12:13:22.123  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 12:13:22.123  6894  6894 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:22.133  6463  6463 I art     : Explicit concurrent mark sweep GC freed 597(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 703us total 34.819ms
,07-07 12:13:22.143  2760  2760 I art     : Explicit concurrent mark sweep GC freed 23422(1278KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.203ms total 40.888ms
,07-07 12:13:22.163  6894  6894 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-07 12:13:22.163  6894  6894 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 12:13:22.163  6894  6894 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-07 12:13:22.163  6894  6894 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-07 12:13:22.163  6894  6894 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-07 12:13:22.173  1902  1902 E SamsungIME: mOCRHelper is null
,07-07 12:13:22.173  2004  2207 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 12:13:22.183  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 12:13:22.193  4774  4774 I art     : Explicit concurrent mark sweep GC freed 21177(1308KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/16MB, paused 1.260ms total 103.335ms
,07-07 12:13:22.203  1014  1120 V NetworkStats: removeUidsLocked() for UIDs [10170]
,07-07 12:13:22.213  1014  1120 V NetworkStats: performPollLocked(flags=0x3)
,07-07 12:13:22.213  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 12:13:22.213  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,07-07 12:13:22.213  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-07 12:13:22.223  1014  1120 V NetworkStats: performPollLocked() took 16ms
,07-07 12:13:22.223  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 12:13:22.223  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,07-07 12:13:22.243  1462  1462 D RegisteredServicesCache: empty dynamic service
,07-07 12:13:22.263  6894  6894 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-07 12:13:22.263  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 12:13:22.263  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 12:13:22.273  6800  6892 D ContactProvider: getAllContactInfoList End
,07-07 12:13:22.273  6800  6892 I syncContacts: thread: 1188, sync time = 371
,07-07 12:13:22.283  1462  1462 D RegisteredComponentCache: Collect Tech packages for Knox
,07-07 12:13:22.293  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,07-07 12:13:22.313  1014  1531 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-07 12:13:22.313  1014  1531 D SecContentProvider2: mCursor = null
,07-07 12:13:22.323  1014  1014 I art     : Explicit concurrent mark sweep GC freed 60138(4MB) AllocSpace objects, 58(928KB) LOS objects, 33% free, 23MB/35MB, paused 2.875ms total 234.249ms
,07-07 12:13:22.333  1014  1055 I art     : WaitForGcToComplete blocked for 199.614ms for cause Explicit
,07-07 12:13:22.373  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,07-07 12:13:22.373  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-07 12:13:22.383  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.383  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-07 12:13:22.383  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-07 12:13:22.383  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,07-07 12:13:22.393  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-07 12:13:22.413  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
07-07 12:13:22.413  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-07 12:13:22.413  1014  1039 W TextServicesManagerService: no available spell checker services found
,07-07 12:13:22.423  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.433  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.443  6894  6894 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 126.622ms
,07-07 12:13:22.453  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.463  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.523  6894  6910 D Mms/ArtClassLoader: init before art
,07-07 12:13:22.523  6894  6894 D Mms/TelephonyPermission: start operation mode monitor
,07-07 12:13:22.533  6894  6894 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-07 12:13:22.533  1014  1055 I art     : Explicit concurrent mark sweep GC freed 14984(696KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.100ms total 197.843ms
,07-07 12:13:22.543  6894  6894 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
07-07 12:13:22.543  6894  6894 D Mms/TelephonyPermission: isDefault true
,07-07 12:13:22.543  6894  6894 D Mms/MmsApp: onCreate() com.android.mms
,07-07 12:13:22.573  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-07 12:13:22.583  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-07 12:13:22.583  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
,07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-07 12:13:22.583  6894  6894 D Mms/MmsApp: [start]    initCountryIso consume time = 321.783124
,07-07 12:13:22.583  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-07 12:13:22.583  1014  1485 D CountryDetector: The first listener is added
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: uID is 10170
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 12:13:22.583  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 12:13:22.593  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 12:13:22.593  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 12:13:22.593  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 12:13:22.593  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-07 12:13:22.593  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-07 12:13:22.593  1014  3497 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-07 12:13:22.593  1014  1014 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
07-07 12:13:22.593  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=44_task.xml
,07-07 12:13:22.593  6894  6894 D Mms/MmsApp: [end]    initCountryIso consume time = 12.29724
07-07 12:13:22.593  6894  6894 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.109375
,07-07 12:13:22.603  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 12:13:22.603  1014  1055 D PackageManager: delete codoeFile: 
,07-07 12:13:22.603  6894  6894 D Mms/MmsConfig: before partial update
,07-07 12:13:22.603  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,07-07 12:13:22.603  1014  1055 I AASA_removePackage: UID=10170 Target=com.test.thalitest
07-07 12:13:22.603  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.603  1014  1055 D PackageManager: result of delete: 1{240459703}
,07-07 12:13:22.613  6797  6797 D AndroidRuntime: Shutting down VM
,07-07 12:13:22.623  6894  6894 D Mms/MmsConfig: Load Resize quality : 80
,07-07 12:13:22.623  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.623  6894  6894 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,07-07 12:13:22.623  6894  6894 D EasySignUpManager_1.0.1: isAuth is false
,07-07 12:13:22.623  6894  6894 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
07-07 12:13:22.623  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 12:13:22.623  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 12:13:22.623  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 12:13:22.623  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.633  1477  1880 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6894
,07-07 12:13:22.633  1477  1880 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.301 ms
,07-07 12:13:22.643  6894  6894 D EasySignUpManager_1.0.1: isAuth is false
,07-07 12:13:22.643  6894  6894 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,07-07 12:13:22.643  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.643  6894  6894 E CscParser: mps_code.dat does not exist
07-07 12:13:22.643  6894  6894 E CscParser: customer_path =/system/csc/customer.xml
07-07 12:13:22.643  6894  6894 E CscParser: fileName + /system/csc/customer.xml
,07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.653  6894  6894 E CscParser: mps_code.dat does not exist
,07-07 12:13:22.653  6894  6894 E CscParser: customer_path =/system/csc/customer.xml
07-07 12:13:22.653  6894  6894 E CscParser: fileName + /system/csc/customer.xml
,07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 12:13:22.653  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 12:13:22.663  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 12:13:22.663  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 12:13:22.663  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 12:13:22.663  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-07 12:13:22.663  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-07 12:13:22.673  6894  6894 D CscParser: getInstance fileName =/system/csc/customer.xml
,07-07 12:13:22.673  6894  6894 D Mms/MmsConfig:  enable multiwindow = false
,07-07 12:13:22.683  6894  6894 E Mms/MessageUtils: setCountryDetector : update country detector info 
07-07 12:13:22.683  6894  6894 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-07 12:13:22.683  6894  6894 D Mms/MmsConfig: [end]    init() consume time = 87.574167
,07-07 12:13:22.683  6894  6894 D Mms/Contact: [start]    init() consume time = 1.289166
,07-07 12:13:22.693  1477  1486 D TP/MmsSmsProvider: query,matched:13, calling pid = 6894
,07-07 12:13:22.693  1477  1486 D TP/MmsSmsProvider: match 13:Elapsed time : 1.243 ms
,07-07 12:13:22.693   333   333 I ServiceManager: Waiting for service AtCmdFwd...
07-07 12:13:22.703  6894  6894 D Mms/Contact: [end]    init consume time = 13.499271
07-07 12:13:22.703  6894  6917 D Mms/DraftCache: [start]    rebuildCache consume time = 5.366094
,07-07 12:13:22.713  6894  6894 D Mms/MethodReflector: getSubId is called
07-07 12:13:22.713  6894  6894 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-07 12:13:22.713  1477  1723 D TP/MmsSmsProvider: query,matched:12, calling pid = 6894
,07-07 12:13:22.713  1477  1723 D TP/MmsSmsProvider: match 12:Elapsed time : 1.437 ms
,07-07 12:13:22.713  6894  6894 D Mms/MethodReflector: getTelephonyProperty is called
07-07 12:13:22.713  6894  6894 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-07 12:13:22.713  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-07 12:13:22.713  6894  6894 D Mms/DownloadManager: auto download without roaming -> true
07-07 12:13:22.713  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-07 12:13:22.713  6894  6894 D Mms/MethodReflector: getSubId is called
,07-07 12:13:22.723  6894  6917 D Mms/DraftCache: [end]    rebuildCache consume time = 14.100469
07-07 12:13:22.723  6894  6894 D Mms/MethodReflector: getDefaultSmsSubId is called
07-07 12:13:22.723  6894  6894 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-07 12:13:22.723  6894  6894 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-07 12:13:22.723  6894  6894 D Mms/MethodReflector: getTelephonyProperty is called
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: auto download without roaming -> true
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: auto download during roaming secondary -> false
07-07 12:13:22.723  6894  6894 D Mms/DownloadManager: mAutoDownload ------> true
,07-07 12:13:22.753  6894  6894 D ComposerPerformance: 1467886402766 ms / [DONE] Composer constructor
,07-07 12:13:22.753  6894  6894 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,07-07 12:13:22.753  6894  6894 I Mms/ReservationManager: ReservationManager()
,07-07 12:13:22.753  6894  6894 I Mms/ReservationManager: resetAfterConnected()
,07-07 12:13:22.753  6894  6918 D Mms/Conversation: [start]    init() consume time = 39.075
,07-07 12:13:22.763  1477  1880 D TP/MmsSmsProvider: query,matched:7, calling pid = 6894
,07-07 12:13:22.763  1477  1880 D TP/MmsSmsProvider: match 7:Elapsed time : 1.526 ms
,07-07 12:13:22.763  1477  1723 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,07-07 12:13:22.763  1477  1723 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
07-07 12:13:22.763  1477  1723 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,07-07 12:13:22.763  6894  6894 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,07-07 12:13:22.763  1477  1723 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,07-07 12:13:22.773  6894  6894 D Mms/MmsApp: [end]    onCreate() consume time = 12.445
,07-07 12:13:22.773  6894  6894 D Mms/UIEventReceiver: ui event
07-07 12:13:22.773  6894  6894 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,07-07 12:13:22.773  6894  6894 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,07-07 12:13:22.773  1014  1528 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-07 12:13:22.773  1014  1528 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:22.773  1014  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:22.773  1014  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-07 12:13:22.773  1477  1723 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
07-07 12:13:22.773  1477  1723 D TP/MmsSmsProvider: need read changed broadcast:false
07-07 12:13:22.773  6894  6894 D Mms/MethodReflector: getSubId is called
07-07 12:13:22.773  6894  6894 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-07 12:13:22.773  6824  6824 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
07-07 12:13:22.783  6894  6894 D Mms/MethodReflector: getTelephonyProperty is called
07-07 12:13:22.783  6894  6894 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-07 12:13:22.783  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-07 12:13:22.783  6894  6894 D Mms/DownloadManager: auto download without roaming -> true
07-07 12:13:22.783  6894  6894 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-07 12:13:22.783  6894  6894 D Mms/DownloadManager: mAutoDownload ------> true
07-07 12:13:22.783  6894  6918 D Mms/Conversation: [end]    init consume time = 8.834479
07-07 12:13:22.783  1014  1026 I ActivityManager: Killing 6392:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-07 12:13:22.783  6894  6918 D Mms/MessagingNotification: [start]    init() consume time = 3.592291
,07-07 12:13:22.783  2711  2711 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jul 07 12:13:22 GMT+02:00 2016
,07-07 12:13:22.783  1014  1215 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-07 12:13:22.783  1014  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-07 12:13:22.783  1014  1215 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:22.783  1014  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:22.783  1014  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-07 12:13:22.793  6894  6918 D Mms/MessagingNotification: [end]    init consume time = 9.643594
,07-07 12:13:22.793  2711  2711 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-07 12:13:22.793  1014  1133 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-07 12:13:22.793  1014  1133 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-07 12:13:22.793  1014  1133 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-07 12:13:22.793  6894  6920 D Mms/Synchronizer: [start]    doSync consume time = 4.709636
,07-07 12:13:22.793  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.793  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.793  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.793  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:22.803  6894  6919 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.523333
07-07 12:13:22.803  2711  2711 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-07 12:13:22.803  2711  2711 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-07 12:13:22.803  2711  2711 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-07 12:13:22.813  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-07 12:13:22.813  6922  6922 E Zygote  : MountEmulatedStorage()
,07-07 12:13:22.813  6922  6922 E Zygote  : v2
07-07 12:13:22.813  6922  6922 I libpersona: KNOX_SDCARD checking this for 10090
07-07 12:13:22.813  6922  6922 I libpersona: KNOX_SDCARD not a persona,
,07-07 12:13:22.813  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 12:13:22.813  1014  1133 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6922 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-07 12:13:22.813  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-07 12:13:22.813  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-07 12:13:22.813  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 12:13:22.823  6797  6797 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-07 12:13:22.823  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-07 12:13:22.833  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-07 12:13:22.833  6894  6894 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.833  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:22.833  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-07 12:13:22.843   322   322 I art     : Explicit concurrent mark sweep GC freed 8680(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 32.246ms
,07-07 12:13:22.843  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 12:13:22.843  6922  6922 D ActivityThread: Added TimaKeyStore provider
,07-07 12:13:22.843  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-07 12:13:22.843  1014  1055 D PackageManager: userId{-1}
07-07 12:13:22.843  1014  1055 D PackageManager: andCode{true}
,07-07 12:13:22.863   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.437ms
,07-07 12:13:22.863  6894  6910 D Mms/ArtClassLoader: init [DONE] art
,07-07 12:13:22.873   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.317ms
,07-07 12:13:22.893  6938  6938 E Zygote  : MountEmulatedStorage(),
07-07 12:13:22.893  6938  6938 E Zygote  : v2
07-07 12:13:22.893  6938  6938 I libpersona: KNOX_SDCARD checking this for 1000
07-07 12:13:22.893  6938  6938 I libpersona: KNOX_SDCARD not a persona,
07-07 12:13:22.893  6938  6938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 12:13:22.893  1014  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-07 12:13:22.893  1014  4047 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-07 12:13:22.893  1014  4047 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-07 12:13:22.893  1014  4047 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:22.893  1014  4047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:22.893  1014  4047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-07 12:13:22.893  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-07 12:13:22.893  6938  6938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:22.893  6938  6938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 12:13:22.893  1477  1486 D TP/MmsSmsProvider: query,matched:400, calling pid = 6894
,07-07 12:13:22.903  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-07 12:13:22.903  6894  6946 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,07-07 12:13:22.903  6894  6946 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-07 12:13:22.913  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-07 12:13:22.923  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.923  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.923  2711  6921 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-07 12:13:22.923  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.923  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:22.923  2711  6921 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-07 12:13:22.933  6938  6938 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 12:13:22.933  6938  6938 D ActivityThread: Added TimaKeyStore provider
07-07 12:13:22.933  6922  6922 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-07 12:13:22.933  6922  6922 D elm:15121: ELMEngine.ELMEngine( context ).
,07-07 12:13:22.933  6922  6922 D elm:15121: MDMBridge.setEnterpriseBridge(),
,07-07 12:13:22.933  6955  6955 E Zygote  : MountEmulatedStorage(),
,07-07 12:13:22.933  1014  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-07 12:13:22.943  6955  6955 E Zygote  : v2
07-07 12:13:22.943  6955  6955 I libpersona: KNOX_SDCARD checking this for 1000
07-07 12:13:22.943  6955  6955 I libpersona: KNOX_SDCARD not a persona
,07-07 12:13:22.943  1014  1888 I TactileAssist: enable value -1
07-07 12:13:22.943  1014  1888 I TactileAssist: internal enable value -1
07-07 12:13:22.943  1014  1888 I TactileAssist: intensity value -1
07-07 12:13:22.943  1014  1888 I TactileAssist: saveAppList value true
,07-07 12:13:22.943  6955  6955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-07 12:13:22.953  1014  1888 I TactileAssist: List of disabled apps :
,07-07 12:13:22.953  2711  2711 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
07-07 12:13:22.953  1014  1528 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-07 12:13:22.953  1014  1528 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-07 12:13:22.953  1014  1528 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:22.953  1014  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:22.953  1014  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
07-07 12:13:22.953  6955  6955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:22.953  6955  6955 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 12:13:22.953  6922  6922 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-07 12:13:22.963  6922  6922 D elm:15121: ElmAgentService : onCreate()
,07-07 12:13:22.963  1477  1488 D TP/MmsSmsProvider: update, matched:300, calling pid = 6894
07-07 12:13:22.963  1477  1488 V TP/MmsSmsProvider: syncDBData start
07-07 12:13:22.963  1477  1488 V TP/MmsSmsProvider: syncDBData sms end
07-07 12:13:22.963  1477  1488 V TP/MmsSmsProvider: syncDBData mms end
07-07 12:13:22.963  1477  1488 V TP/MmsSmsProvider: syncDBData end
,07-07 12:13:22.963  6922  6963 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-07 12:13:22.963  6922  6963 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-07 12:13:22.963  6922  6963 D elm:15121: MDMBridge.getInstance()
07-07 12:13:22.963  6922  6963 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
07-07 12:13:22.963  6922  6963 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-07 12:13:22.973  2882  2882 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-07 12:13:22.973  2882  2882 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-07 12:13:22.973  2882  2882 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-07 12:13:22.973  2882  2882 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-07 12:13:22.973  2882  2882 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 12:13:22.973  2882  2882 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 12:13:22.973  2882  2882 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 12:13:22.973  2882  2882 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 12:13:22.973  2882  2882 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-07 12:13:22.973  6955  6955 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 12:13:22.973  6955  6955 D ActivityThread: Added TimaKeyStore provider
07-07 12:13:22.983  6894  6919 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 182.831875
07-07 12:13:22.983  6922  6922 D elm:15121: ElmAgentService : onDestroy().
07-07 12:13:22.983  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
07-07 12:13:22.993  1477  1486 D TP/MmsSmsProvider: query,matched:0, calling pid = 6894
07-07 12:13:22.993  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.993  1477  1486 V TP/MmsSmsProvider: getSimpleConversations entered.
07-07 12:13:22.993  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.993  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.993  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:22.993  1477  1486 D TP/MmsSmsProvider: match 0:Elapsed time : 2.580 ms
,07-07 12:13:23.003  6972  6972 E Zygote  : MountEmulatedStorage()
07-07 12:13:23.003  6972  6972 I libpersona: KNOX_SDCARD checking this for 1000
07-07 12:13:23.003  6972  6972 E Zygote  : v2
07-07 12:13:23.003  6972  6972 I libpersona: KNOX_SDCARD not a persona
07-07 12:13:23.003  6972  6972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-07 12:13:23.003  1014  1014 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-07 12:13:23.003  6972  6972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-07 12:13:23.003  6972  6972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 12:13:23.013  6894  6920 D Mms/Synchronizer: [end]    doSync consume time = 27.063385
07-07 12:13:23.013  1014  1503 I ActivityManager: Killing 6404:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-07 12:13:23.013  6938  6938 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-07 12:13:23.013  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-07 12:13:23.013  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-07 12:13:23.023  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
07-07 12:13:23.023  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 12:13:23.023  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-07 12:13:23.023  6446  6446 D Compatibility: onReceive() it will make start service
,07-07 12:13:23.023  1014  1889 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-07 12:13:23.023  6955  6955 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-07 12:13:23.023  1014  1889 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:23.023  1014  1889 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 12:13:23.023  1014  1889 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 12:13:23.023  1014  1889 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
