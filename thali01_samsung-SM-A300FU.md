#### Test 757892681403989_thali01_samsung-SM-A300FU Logs


```
--------- beginning of system
07-05 12:00:02.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:00:03.173  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:00:03.173  1015  1529 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:00:03.173  1015  1529 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:00:03.173  1015  1529 D BatteryService: stay LED for fully charged
07-05 12:00:03.173  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:00:03.183  1015  1015 I MotionRecognitionService: Plugged
07-05 12:00:03.183  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
07-05 12:00:03.183  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:00:03.183  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:00:03.183  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:00:03.183  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-05 12:00:03.193  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:00:03.193  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
07-05 12:00:03.203  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:03.203  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:03.203  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:03.203  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:00:03.203  1176  1176 D SViewCoverView: level :100 plugged : 2
07-05 12:00:03.273  6733  6733 D AndroidRuntime: 
07-05 12:00:03.273  6733  6733 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:00:03.283  6733  6733 D AndroidRuntime: CheckJNI is OFF
07-05 12:00:03.283  6733  6733 D AndroidRuntime: readGMSProperty: start
07-05 12:00:03.283  6733  6733 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:00:03.283  6733  6733 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 12:00:03.283  6733  6733 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 12:00:03.283  6733  6733 D AndroidRuntime: readGMSProperty: end
07-05 12:00:03.283  6733  6733 D AndroidRuntime: addProductProperty: start
07-05 12:00:03.413  6733  6733 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:00:03.443  6733  6733 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 12:00:03.453  1015  1490 E PersonaManagerService: inState():  stateMachine is null !!
07-05 12:00:03.453  1015  1490 I PersonaManagerService: PersonaId don't exist
07-05 12:00:03.453  1015  1490 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 12:00:03.453  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:00:03.473  1015  1490 W ActivityManager: mDVFSHelper.acquire()
07-05 12:00:03.473  1015  1490 D FocusedStackFrame: Set to : 0
07-05 12:00:03.473  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 12:00:03.473  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-05 12:00:03.483  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:03.483  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:03.483  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:03.483  1015  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:00:03.493  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 12:00:03.493  1015  1490 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6746 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:00:03.493  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:00:03.493  6746  6746 I libpersona: KNOX_SDCARD checking this for 10151
07-05 12:00:03.493  1015  1490 D InputDispatcher: Focused application set to: xxxx
07-05 12:00:03.493  6746  6746 I libpersona: KNOX_SDCARD not a persona
07-05 12:00:03.493  1015  1490 D InputDispatcher: Focus left window: 1491
07-05 12:00:03.493  6746  6746 E Zygote  : MountEmulatedStorage()
07-05 12:00:03.493  6746  6746 E Zygote  : v2
07-05 12:00:03.493  6733  6733 D AndroidRuntime: Shutting down VM
07-05 12:00:03.493  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 12:00:03.493  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 12:00:03.493   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-05 12:00:03.493  6746  6746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:00:03.503  6746  6746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:00:03.503  6746  6746 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 12:00:03.523  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:00:03.523  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 12:00:03.523  6746  6746 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:00:03.523  6746  6746 D ActivityThread: Added TimaKeyStore provider
07-05 12:00:03.523  1015  1134 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 12:00:03.533  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:00:03.543  1015  1134 D PersonaManager: isKioskContainerExistOnDevice
07-05 12:00:03.553  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-05 12:00:03.583   257   443 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
07-05 12:00:03.583   257  1095 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
07-05 12:00:03.583   287   287 E SMD     : DCD OFF
07-05 12:00:03.583  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{1c11b14d token=android.os.BinderProxy@386930a9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 12:00:03.583  1491  1491 D Launcher: onTrimMemory. Level: 20
07-05 12:00:03.653  6746  6746 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 12:00:03.663  6746  6746 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6845-6847)
07-05 12:00:03.663  6746  6746 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:03.683  6746  6746 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14b6e0b5}
07-05 12:00:03.693  6746  6746 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:00:03.693  6746  6746 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:00:03.703  6733  6733 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-05 12:00:03.723  6746  6746 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-05 12:00:03.723  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:00:03.723  6746  6746 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 12:00:03.743  6746  6746 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-05 12:00:03.753  6746  6746 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-05 12:00:03.753  6746  6746 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-05 12:00:03.753  6746  6746 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 12:00:03.753  6746  6746 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 12:00:03.753  6746  6746 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 12:00:03.753  6746  6746 I Adreno-EGL: Local Branch: 
07-05 12:00:03.753  6746  6746 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 12:00:03.753  6746  6746 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 12:00:03.753  6746  6746 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 12:00:03.943  6746  6772 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-05 12:00:03.993  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:00:04.003  6746  6746 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 12:00:04.013  6746  6746 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-05 12:00:04.013  6746  6746 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-05 12:00:04.023  6746  6746 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 12:00:04.033  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:00:04.033  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:00:04.053  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{1203a882 u0 com.test.thalitest/.MainActivity t81}
,07-05 12:00:04.083  1015  2885 D SSRM:n  : SIOP:: AP = 320
,07-05 12:00:04.093  6746  6785 D OpenGLRenderer: Render dirty regions requested: true
,07-05 12:00:04.093  1015  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-05 12:00:04.103  1015  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 12:00:04.103  1015  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-05 12:00:04.103  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-05 12:00:04.103  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 12:00:04.103  6746  6746 V ActivityThread: updateVisibility : ActivityRecord{350147b4 token=android.os.BinderProxy@28f324c6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 12:00:04.113  6746  6746 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-05 12:00:04.113  6746  6746 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-05 12:00:04.123   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-05 12:00:04.133  1015  1489 D InputDispatcher: Focus entered window: 6746
,07-05 12:00:04.133  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:00:04.133  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 12:00:04.133  6746  6746 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-05 12:00:04.133  6746  6785 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 12:00:04.143  6746  6785 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-05 12:00:04.143  6746  6785 D OpenGLRenderer: Enabling debug mode 0
,07-05 12:00:04.163  1015  1529 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 12:00:04.163  1176  1176 I StatusBar: Icon Only
,07-05 12:00:04.163  1176  1176 D PanelView: There is/are notification(s) 
,07-05 12:00:04.163  6746  6746 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28f324c6 time:137346,
,07-05 12:00:04.163  6746  6746 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-05 12:00:04.173  1015  6787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:00:04.173  1015  1045 I ActivityManager: Displayed Component not be shown by security: +629ms (total +21s315ms)
,07-05 12:00:04.173  1015  1045 W ActivityManager: mDVFSHelper.release()
07-05 12:00:04.183  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1203a882 u0 com.test.thalitest/.MainActivity t81} time:137360
,07-05 12:00:04.183   257  1160 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,07-05 12:00:04.183   257   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
,07-05 12:00:04.223  1825  1825 I SamsungIME: getCurrentCandidateView
,07-05 12:00:04.313  6746  6746 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6746
,07-05 12:00:04.353  1825  1825 D SamsungIME: Dismiss ExpandCandiate
,07-05 12:00:04.443  6746  6746 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 12:00:04.503  1825  1825 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 12:00:04.523  6746  6746 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 12:00:04.543  1825  1825 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 12:00:04.543  1015  1311 E Watchdog: !@Sync 4
,07-05 12:00:04.553  1825  1825 I SamsungIME: KeybaordView init() : load resources
,07-05 12:00:04.573  6746  6790 D jxcore_app_log: JniHelper::setJavaVM(0xb717f2f0), pthread_self() = -1217546624
,07-05 12:00:04.573  1825  1825 I SamsungIME: getCurrentKeyboard
07-05 12:00:04.573  1825  1825 I SamsungIME: getTextKeyboard
,07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:00:04.583  6746  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6005e4 added. We now have 1 listener(s)
,07-05 12:00:04.593  6746  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-05 12:00:04.593  6746  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-05 12:00:04.593  6746  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 12:00:04.593  6746  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 12:00:04.593  1825  1825 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@218fc213 added. We now have 1 listener(s)
,07-05 12:00:04.603  6746  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 12:00:04.603  6746  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 12:00:04.603  6746  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 12:00:04.603  6746  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 12:00:04.603  6746  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 12:00:04.603  6746  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 12:00:04.613  6746  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 12:00:04.613  6746  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:1a:ce:70
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:00:04.623  6746  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 12:00:04.623  6746  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:00:04.623  6746  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 12:00:04.623  6746  6790 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 12:00:04.623  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:00:04.633  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:00:04.653  6746  6746 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:00:05.163  6746  6796 W jxcore-log: Initializing JXcore engine
07-05 12:00:05.163  6746  6796 W jxcore-log: JXcore engine is ready
,07-05 12:00:05.213  1945  1945 E audit   : type=1400 msg=audit(1467712805.213:205): avc:  denied  { ioctl } for  pid=6796 comm="Thread-1254" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 12:00:05.213  1945  1945 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:00:05.213  1945  1945 E audit   : type=1300 msg=audit(1467712805.213:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9dbfe8f8 items=0 ppid=304 ppcomm=main pid=6796 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1254" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 12:00:05.213  1945  1945 E audit   : type=1320 msg=audit(1467712805.213:205): 
,07-05 12:00:05.223  6746  6796 W jxcore-log: Starting JXcore engine
,07-05 12:00:05.323  6746  6796 W jxcore-log: Platform android
07-05 12:00:05.323  6746  6796 W jxcore-log: 
,07-05 12:00:05.323  6746  6796 W jxcore-log: Process ARCH arm
07-05 12:00:05.323  6746  6796 W jxcore-log: 
,07-05 12:00:05.523  6746  6796 I jxcore-log: JXcore Cordova bridge is ready!
07-05 12:00:05.523  6746  6796 I jxcore-log: 
,07-05 12:00:05.523  6746  6796 W jxcore-log: JXcore engine is started
,07-05 12:00:05.593   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:00:06.583   287   287 E SMD     : DCD OFF
,07-05 12:00:06.593   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:00:07.593   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:00:08.543  1015  1995 V SAMP_SPCM_test: CSC File load.. 
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings,
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
07-05 12:00:08.563  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,07-05 12:00:08.593   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
07-05 12:00:08.613  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall,
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
07-05 12:00:08.623  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,07-05 12:00:08.643  1015  1995 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-05 12:00:09.583   287   287 E SMD     : DCD OFF
,07-05 12:00:09.593   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:10.593   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:00:12.583   287   287 E SMD     : DCD OFF
,07-05 12:00:13.243  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:13.243  1015  1506 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:00:13.243  1015  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:00:13.243  1015  1506 D BatteryService: stay LED for fully charged
07-05 12:00:13.243  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:00:13.253  1015  1015 I MotionRecognitionService: Plugged
07-05 12:00:13.253  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:00:13.253  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:00:13.253  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-05 12:00:13.253  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:00:13.253  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:00:13.263  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:00:13.263  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:00:13.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:13.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:13.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:00:13.273  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:00:13.273  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:00:13.483  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 12:00:14.103  1015  2885 D SSRM:n  : SIOP:: AP = 320
,07-05 12:00:15.583   287   287 E SMD     : DCD OFF
,07-05 12:00:18.583   287   287 E SMD     : DCD OFF
,07-05 12:00:18.923  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
,07-05 12:00:21.583   287   287 E SMD     : DCD OFF,
,07-05 12:00:22.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:00:23.313  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:00:23.313  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:00:23.313  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:00:23.313  1015  1490 D BatteryService: stay LED for fully charged
07-05 12:00:23.313  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:00:23.313  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:00:23.313  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:00:23.313  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:00:23.323  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
07-05 12:00:23.323  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:00:23.323  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:00:23.333  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:00:23.333  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:00:23.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:00:23.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:23.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:00:23.343  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:00:23.343  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:00:24.123  1015  2885 D SSRM:n  : SIOP:: AP = 310
,07-05 12:00:24.593   287   287 E SMD     : DCD OFF,
,07-05 12:00:25.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:26.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:27.593   287   287 E SMD     : DCD OFF,
,07-05 12:00:27.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:28.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:29.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:30.593   287   287 E SMD     : DCD OFF
,07-05 12:00:30.603   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:00:33.373  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:33.593   287   287 E SMD     : DCD OFF,
,07-05 12:00:34.133  1015  2885 D SSRM:n  : SIOP:: AP = 310
,07-05 12:00:34.543  1015  1311 E Watchdog: !@Sync 5
,07-05 12:00:36.593   287   287 E SMD     : DCD OFF
,07-05 12:00:39.593   287   287 E SMD     : DCD OFF,
,07-05 12:00:42.603   287   287 E SMD     : DCD OFF
,07-05 12:00:42.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:00:43.443  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:00:44.173  1015  2885 D SSRM:n  : SIOP:: AP = 310
,07-05 12:00:45.603   287   287 E SMD     : DCD OFF,
,07-05 12:00:48.603   287   287 E SMD     : DCD OFF,
,07-05 12:00:48.923  1015  1047 I PowerManagerService: [PWL] Off : 105s ago
,07-05 12:00:50.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:51.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:51.603   287   287 E SMD     : DCD OFF
,07-05 12:00:52.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:53.503  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:00:53.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:54.203  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:00:54.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:00:54.603   287   287 E SMD     : DCD OFF,
,07-05 12:00:55.603   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:00:57.603   287   287 E SMD     : DCD OFF
,07-05 12:01:00.613   287   287 E SMD     : DCD OFF,
,07-05 12:01:00.843  1015  1093 V AlarmManager: waitForAlarm result :4
,07-05 12:01:00.853  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-05 12:01:00.863  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-05 12:01:00.863  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-05 12:01:00.863  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:01:00.863  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:01:00.873  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 12:01:00.883  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 12:01:00.893  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:00.893  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 12:01:00.893  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:01:00.903  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 12:01:00.903  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,07-05 12:01:00.903  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:01:00.903  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:01:00.903  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-05 12:01:00.943  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:00.943  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:00.953  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:00.953  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,07-05 12:01:00.963  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:01:02.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:01:03.573  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:03.573  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:01:03.573  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:01:03.573  1015  1027 D BatteryService: stay LED for fully charged
,07-05 12:01:03.573  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:01:03.573  1015  1015 I MotionRecognitionService: Plugged
07-05 12:01:03.573  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:01:03.573  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:01:03.573  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:01:03.583  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:01:03.583  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:01:03.593  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:01:03.593  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:01:03.603  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:03.603  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:01:03.603  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:01:03.603  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:01:03.603  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:01:03.613   287   287 E SMD     : DCD OFF,
,07-05 12:01:04.213  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:04.543  1015  1311 E Watchdog: !@Sync 6
,07-05 12:01:06.613   287   287 E SMD     : DCD OFF
,07-05 12:01:09.613   287   287 E SMD     : DCD OFF
,07-05 12:01:12.613   287   287 E SMD     : DCD OFF
,07-05 12:01:13.633  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:14.233  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:15.613   287   287 E SMD     : DCD OFF,
,07-05 12:01:18.613   287   287 E SMD     : DCD OFF
,07-05 12:01:20.603   313   313 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:01:20.603   313   313 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:01:21.613   287   287 E SMD     : DCD OFF
,07-05 12:01:22.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:01:23.703  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:23.923  1015  1047 I PowerManagerService: [PWL] Off : 140s ago,
,07-05 12:01:24.263  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:24.623   287   287 E SMD     : DCD OFF
,07-05 12:01:27.623   287   287 E SMD     : DCD OFF,
,07-05 12:01:30.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:30.623   287   287 E SMD     : DCD OFF,
,07-05 12:01:31.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:32.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:33.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:01:33.623   287   287 E SMD     : DCD OFF,
,07-05 12:01:33.763  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:34.273  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:34.543  1015  1311 E Watchdog: !@Sync 7
,07-05 12:01:34.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:35.603   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:01:36.623   287   287 E SMD     : DCD OFF
,07-05 12:01:37.853  1015  1093 V AlarmManager: waitForAlarm result :4
,07-05 12:01:39.623   287   287 E SMD     : DCD OFF,
,07-05 12:01:40.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:41.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:42.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:42.633   287   287 E SMD     : DCD OFF
,07-05 12:01:42.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:01:43.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:43.823  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:44.313  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:44.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:01:45.603   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:01:45.633   287   287 E SMD     : DCD OFF
,07-05 12:01:48.633   287   287 E SMD     : DCD OFF,
,07-05 12:01:51.633   287   287 E SMD     : DCD OFF
,07-05 12:01:53.893  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:01:54.343  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:01:54.633   287   287 E SMD     : DCD OFF,
,07-05 12:01:55.603   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:56.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:57.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:57.633   287   287 E SMD     : DCD OFF
,07-05 12:01:58.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:01:59.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:01:59.993  1015  1093 V AlarmManager: waitForAlarm result :8,
,07-05 12:02:00.613   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:02:00.643   287   287 E SMD     : DCD OFF
,07-05 12:02:02.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:02:03.643   287   287 E SMD     : DCD OFF,
,07-05 12:02:03.953  1015  1047 I PowerManagerService: [PWL] Off : 180s ago
,07-05 12:02:03.953  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:02:04.363  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:02:04.543  1015  1311 E Watchdog: !@Sync 8,
,07-05 12:02:06.643   287   287 E SMD     : DCD OFF
,07-05 12:02:09.643   287   287 E SMD     : DCD OFF,
,07-05 12:02:12.643   287   287 E SMD     : DCD OFF
,07-05 12:02:14.023  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:14.373  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:02:15.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:15.643   287   287 E SMD     : DCD OFF,
,07-05 12:02:16.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:17.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:18.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:02:18.643   287   287 E SMD     : DCD OFF
,07-05 12:02:19.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:20.613   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:02:21.653   287   287 E SMD     : DCD OFF
,07-05 12:02:22.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:02:24.083  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:24.093  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:02:24.093  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:02:24.093  1015  1490 D BatteryService: stay LED for fully charged
,07-05 12:02:24.093  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:24.093  1015  1015 I MotionRecognitionService: Plugged
07-05 12:02:24.093  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:02:24.093  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:02:24.093  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:02:24.103  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-05 12:02:24.103  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:02:24.103  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:02:24.103  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:02:24.123  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:24.123  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:24.123  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:24.123  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:02:24.123  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:02:24.383  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:02:24.653   287   287 E SMD     : DCD OFF
,07-05 12:02:27.653   287   287 E SMD     : DCD OFF,
,07-05 12:02:30.653   287   287 E SMD     : DCD OFF,
,07-05 12:02:33.653   287   287 E SMD     : DCD OFF,
,07-05 12:02:34.153  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:34.153  1015  1529 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:02:34.153  1015  1529 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:02:34.153  1015  1529 D BatteryService: stay LED for fully charged
,07-05 12:02:34.153  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:34.153  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:02:34.153  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:02:34.163  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:34.163  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:02:34.163  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:02:34.163  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:02:34.173  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:02:34.173  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:02:34.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:34.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:34.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:02:34.183  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:02:34.193  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:02:34.403  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:02:34.543  1015  1311 E Watchdog: !@Sync 9
,07-05 12:02:36.653   287   287 E SMD     : DCD OFF
,07-05 12:02:39.663   287   287 E SMD     : DCD OFF,
,07-05 12:02:40.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:41.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:42.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:42.663   287   287 E SMD     : DCD OFF
,07-05 12:02:42.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:02:43.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:02:44.213  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:44.413  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:02:44.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:02:45.613   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:02:45.663   287   287 E SMD     : DCD OFF,
,07-05 12:02:48.663   287   287 E SMD     : DCD OFF
,07-05 12:02:48.953  1015  1047 I PowerManagerService: [PWL] Off : 225s ago
,07-05 12:02:51.663   287   287 E SMD     : DCD OFF
,07-05 12:02:54.283  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:02:54.283  1015  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:02:54.283  1015  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:02:54.283  1015  3410 D BatteryService: stay LED for fully charged
,07-05 12:02:54.283  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:02:54.293  1015  1015 I MotionRecognitionService: Plugged,
07-05 12:02:54.293  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
07-05 12:02:54.293  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:02:54.293  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:02:54.293  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:02:54.293  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:02:54.303  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:02:54.303  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:02:54.313  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:02:54.313  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:54.313  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:02:54.313  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:02:54.313  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:02:54.423  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:02:54.663   287   287 E SMD     : DCD OFF,
,07-05 12:02:57.663   287   287 E SMD     : DCD OFF,
,07-05 12:03:00.673   287   287 E SMD     : DCD OFF,
,07-05 12:03:01.553  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:03:01.553  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:03:01.553  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:03:01.553  1015  1084 I TLC_TIMA_PKM_initialize: initializing...
07-05 12:03:01.563  1015  1084 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-05 12:03:01.563  1015  1084 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-05 12:03:01.563  1015  1084 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-05 12:03:01.563  1015  1084 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-05 12:03:01.563  1015  1084 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-05 12:03:01.563  1015  1084 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-05 12:03:01.563  1015  1084 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-05 12:03:01.563  1015  1084 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
07-05 12:03:01.563  1015  1084 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 12:03:01.583  1015  1084 D QSEECOMAPI: : Loaded image: APP id = 12
,07-05 12:03:01.593  1015  1084 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 12:03:01.603  1015  1084 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 12:03:02.963  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:03:03.473  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:03:03.473  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:03:03.483  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:03:03.483  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:03:03.673   287   287 E SMD     : DCD OFF
,07-05 12:03:04.343  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:04.343  1015  3411 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:03:04.343  1015  3411 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:03:04.343  1015  3411 D BatteryService: stay LED for fully charged
,07-05 12:03:04.343  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:04.353  1015  1015 I MotionRecognitionService: Plugged
07-05 12:03:04.353  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:03:04.353  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:04.353  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:03:04.353  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:03:04.353  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:03:04.363  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:03:04.373  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:04.383  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:04.383  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:04.383  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:04.383  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:03:04.383  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:03:04.443  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:03:04.543  1015  1311 E Watchdog: !@Sync 10
,07-05 12:03:06.673   287   287 E SMD     : DCD OFF,
,07-05 12:03:09.673   287   287 E SMD     : DCD OFF,
,07-05 12:03:10.613   313   313 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:03:10.613   313   313 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:03:12.673   287   287 E SMD     : DCD OFF,
,07-05 12:03:14.413  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:03:14.413  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:03:14.413  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:03:14.413  1015  1134 D BatteryService: stay LED for fully charged
07-05 12:03:14.413  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,07-05 12:03:14.413  1015  1015 I MotionRecognitionService: Plugged
07-05 12:03:14.413  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
,07-05 12:03:14.423  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:14.423  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:03:14.423  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:03:14.423  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:03:14.433  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:14.433  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:14.443  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:14.443  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:14.443  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:14.443  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:03:14.443  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:03:14.453  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:03:15.673   287   287 E SMD     : DCD OFF
,07-05 12:03:18.683   287   287 E SMD     : DCD OFF,
,07-05 12:03:21.683   287   287 E SMD     : DCD OFF
,07-05 12:03:22.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:03:24.473  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:03:24.473  1015  1268 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-05 12:03:24.473  1015  1268 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:03:24.473  1015  1268 D BatteryService: stay LED for fully charged
07-05 12:03:24.473  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:03:24.483  1015  1015 I MotionRecognitionService: Plugged,
07-05 12:03:24.483  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:03:24.483  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:03:24.483  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:03:24.483  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:03:24.483  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:03:24.493  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:03:24.503  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:24.503  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:24.513  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:24.513  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:24.513  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:24.513  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:03:24.513  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:03:24.683   287   287 E SMD     : DCD OFF
,07-05 12:03:25.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:26.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:27.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:27.683   287   287 E SMD     : DCD OFF,
,07-05 12:03:28.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:03:29.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:03:30.613   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 12:03:30.683   287   287 E SMD     : DCD OFF,
,07-05 12:03:33.683   287   287 E SMD     : DCD OFF,
,07-05 12:03:34.523  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:03:34.543  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:34.543  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:03:34.543  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:03:34.543  1015  1027 D BatteryService: stay LED for fully charged
07-05 12:03:34.543  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:34.543  1015  1311 E Watchdog: !@Sync 11
,07-05 12:03:34.543  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:03:34.543  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:03:34.553  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:03:34.553  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:03:34.553  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:03:34.553  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:03:34.563  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:34.563  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:34.573  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:34.573  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:34.573  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:34.573  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:03:34.573  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:03:35.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:36.613   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:36.683   287   287 E SMD     : DCD OFF
,07-05 12:03:37.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:38.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:38.953  1015  1047 I PowerManagerService: [PWL] Off : 275s ago
,07-05 12:03:39.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:39.693   287   287 E SMD     : DCD OFF
,07-05 12:03:40.623   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:03:42.693   287   287 E SMD     : DCD OFF,
,07-05 12:03:42.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:03:44.563  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:03:44.603  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:45.693   287   287 E SMD     : DCD OFF
,07-05 12:03:48.693   287   287 E SMD     : DCD OFF,
,07-05 12:03:50.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:51.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:51.693   287   287 E SMD     : DCD OFF,
,07-05 12:03:52.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:53.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:03:54.593  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:03:54.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:03:54.673  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:03:54.673  1015  3411 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:03:54.673  1015  3411 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:03:54.673  1015  3411 D BatteryService: stay LED for fully charged
,07-05 12:03:54.673  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:03:54.683  1015  1015 I MotionRecognitionService: Plugged,
07-05 12:03:54.683  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:03:54.683  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:03:54.683  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:03:54.683  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 12:03:54.683  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:03:54.693  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:03:54.693  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:03:54.693   287   287 E SMD     : DCD OFF
,07-05 12:03:54.703  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:54.703  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:03:54.703  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:03:54.703  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:03:54.703  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:03:55.623   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 12:03:57.693   287   287 E SMD     : DCD OFF
,07-05 12:04:00.703   287   287 E SMD     : DCD OFF,
,07-05 12:04:02.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:04:03.703   287   287 E SMD     : DCD OFF
,07-05 12:04:03.903  1015  1093 V AlarmManager: waitForAlarm result :4
,07-05 12:04:03.903  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 12:04:03.903  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:04:03.923  1015  1015 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,07-05 12:04:03.923  1015  1015 V SAMP_GCMKill: GCM kill size 0. just return
,07-05 12:04:03.933  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 12:04:03.933  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 12:04:03.943  1015  1529 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:04:03.943  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:04:03.943  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 12:04:03.943  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
07-05 12:04:03.943  1015  1529 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,07-05 12:04:03.943  1015  1529 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:04:03.943  1015  1529 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:04:03.943  1015  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:04:03.973  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:04:03.983  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 12:04:03.983  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,07-05 12:04:03.983  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:04:03.983  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 12:04:03.993  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:04:03.993  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:04:04.003  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,07-05 12:04:04.013  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:04:04.023  3424  6900 I EventLogService: Aggregate from 1467711137475 (log), 1467711137475 (data)
,07-05 12:04:04.543  1015  1311 E Watchdog: !@Sync 12
,07-05 12:04:04.613  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:04:04.743  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:06.703   287   287 E SMD     : DCD OFF,
,07-05 12:04:09.703   287   287 E SMD     : DCD OFF
,07-05 12:04:10.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:11.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:12.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:12.703   287   287 E SMD     : DCD OFF
,07-05 12:04:13.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:14.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:14.643  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:04:14.803  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:04:15.623   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:04:15.703   287   287 E SMD     : DCD OFF
,07-05 12:04:18.703   287   287 E SMD     : DCD OFF,
,07-05 12:04:21.713   287   287 E SMD     : DCD OFF
,07-05 12:04:22.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:04:24.673  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:04:24.713   287   287 E SMD     : DCD OFF,
,07-05 12:04:24.873  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:27.713   287   287 E SMD     : DCD OFF
,07-05 12:04:30.713   287   287 E SMD     : DCD OFF
,07-05 12:04:33.713   287   287 E SMD     : DCD OFF,
,07-05 12:04:33.963  1015  1047 I PowerManagerService: [PWL] Off : 330s ago,
,07-05 12:04:34.543  1015  1311 E Watchdog: !@Sync 13
,07-05 12:04:34.713  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:04:34.943  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:34.943  1015  1506 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:04:34.943  1015  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:04:34.943  1015  1506 D BatteryService: stay LED for fully charged
,07-05 12:04:34.943  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:04:34.943  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:04:34.943  1015  1015 I MotionRecognitionService: Plugged
07-05 12:04:34.943  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:04:34.943  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
07-05 12:04:34.953  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:04:34.953  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:04:34.963  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:04:34.963  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:04:34.973  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:34.973  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:04:34.973  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:34.973  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:04:34.973  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:04:35.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:36.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:36.713   287   287 E SMD     : DCD OFF
,07-05 12:04:37.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:38.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:39.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:04:39.713   287   287 E SMD     : DCD OFF
,07-05 12:04:40.623   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:04:42.713   287   287 E SMD     : DCD OFF,
,07-05 12:04:42.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:04:44.743  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:04:45.003  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:04:45.003  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:04:45.003  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:04:45.003  1015  1028 D BatteryService: stay LED for fully charged
,07-05 12:04:45.003  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:04:45.013  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:04:45.013  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:04:45.013  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:04:45.013  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:04:45.013  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:04:45.013  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:04:45.033  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:04:45.033  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:04:45.043  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:45.043  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:04:45.043  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:04:45.043  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:04:45.043  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:04:45.723   287   287 E SMD     : DCD OFF
,07-05 12:04:48.723   287   287 E SMD     : DCD OFF
,07-05 12:04:51.723   287   287 E SMD     : DCD OFF
,07-05 12:04:54.723   287   287 E SMD     : DCD OFF
,07-05 12:04:54.773  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:04:55.073  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:04:57.723   287   287 E SMD     : DCD OFF,
,07-05 12:04:59.993  1015  1093 V AlarmManager: waitForAlarm result :8
,07-05 12:05:00.723   287   287 E SMD     : DCD OFF,
,07-05 12:05:02.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:05:03.723   287   287 E SMD     : DCD OFF
,07-05 12:05:04.543  1015  1311 E Watchdog: !@Sync 14,
,07-05 12:05:04.793  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:05:05.133  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:05.133  1015  3343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-05 12:05:05.133  1015  3343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:05:05.133  1015  3343 D BatteryService: stay LED for fully charged
07-05 12:05:05.133  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:05:05.143  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:05:05.143  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:05:05.143  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:05:05.143  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:05:05.143  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:05:05.143  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:05:05.153  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:05:05.153  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:05:05.163  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:05.163  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:05:05.163  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:05.163  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:05:05.163  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:05:05.623   313   313 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:05:05.623   313   313 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:05:06.733   287   287 E SMD     : DCD OFF
,07-05 12:05:09.733   287   287 E SMD     : DCD OFF,
,07-05 12:05:12.733   287   287 E SMD     : DCD OFF
,07-05 12:05:14.823  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:05:15.203  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:05:15.203  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:05:15.203  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:05:15.203  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
07-05 12:05:15.203  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
07-05 12:05:15.203  1015  1027 D BatteryService: stay LED for fully charged
07-05 12:05:15.203  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:05:15.203  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:05:15.203  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-05 12:05:15.203  1015  1015 I MotionRecognitionService: Plugged
07-05 12:05:15.203  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:05:15.213  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:05:15.213  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:05:15.233  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:15.233  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:05:15.233  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:05:15.233  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:05:15.233  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:05:15.733   287   287 E SMD     : DCD OFF,
,07-05 12:05:18.733   287   287 E SMD     : DCD OFF,
,07-05 12:05:21.733   287   287 E SMD     : DCD OFF,
,07-05 12:05:22.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:05:24.743   287   287 E SMD     : DCD OFF,
,07-05 12:05:24.863  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:05:25.263  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:25.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:05:26.623   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:27.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:27.743   287   287 E SMD     : DCD OFF,
,07-05 12:05:28.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:29.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:30.633   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:05:30.743   287   287 E SMD     : DCD OFF
,07-05 12:05:33.743   287   287 E SMD     : DCD OFF
,07-05 12:05:33.963  1015  1047 I PowerManagerService: [PWL] Off : 390s ago
,07-05 12:05:34.543  1015  1311 E Watchdog: !@Sync 15
,07-05 12:05:34.873  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:05:35.323  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:05:35.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:05:36.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 12:05:36.743   287   287 E SMD     : DCD OFF,
,07-05 12:05:37.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:38.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:39.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:39.743   287   287 E SMD     : DCD OFF
,07-05 12:05:40.633   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:05:42.743   287   287 E SMD     : DCD OFF
,07-05 12:05:42.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:05:44.913  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:05:45.393  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:05:45.753   287   287 E SMD     : DCD OFF,
,07-05 12:05:48.753   287   287 E SMD     : DCD OFF
,07-05 12:05:50.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:51.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:51.753   287   287 E SMD     : DCD OFF
,07-05 12:05:52.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:53.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:53.733   309   309 I bootchecker: bootchecker wake up!!
,07-05 12:05:54.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:05:54.753   287   287 E SMD     : DCD OFF,
,07-05 12:05:54.923  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:05:55.453  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:05:55.633   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 12:05:57.753   287   287 E SMD     : DCD OFF,
,07-05 12:06:00.753   287   287 E SMD     : DCD OFF,
,07-05 12:06:02.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:06:03.753   287   287 E SMD     : DCD OFF,
,07-05 12:06:04.543  1015  1311 E Watchdog: !@Sync 16,
,07-05 12:06:04.933  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:05.513  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:06.763   287   287 E SMD     : DCD OFF
,07-05 12:06:09.763   287   287 E SMD     : DCD OFF,
,07-05 12:06:10.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:11.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:12.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:12.763   287   287 E SMD     : DCD OFF
,07-05 12:06:13.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:14.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:14.973  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:15.583  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:15.633   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:06:15.763   287   287 E SMD     : DCD OFF
,07-05 12:06:18.763   287   287 E SMD     : DCD OFF,
,07-05 12:06:21.763   287   287 E SMD     : DCD OFF
,07-05 12:06:22.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:06:24.773   287   287 E SMD     : DCD OFF
,07-05 12:06:24.983  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:25.653  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:27.773   287   287 E SMD     : DCD OFF
,07-05 12:06:30.773   287   287 E SMD     : DCD OFF
,07-05 12:06:33.773   287   287 E SMD     : DCD OFF,
,07-05 12:06:34.543  1015  1311 E Watchdog: !@Sync 17,
,07-05 12:06:34.993  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:35.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:35.713  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:06:36.633   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:36.773   287   287 E SMD     : DCD OFF,
,07-05 12:06:37.643   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:38.643   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:38.963  1015  1047 I PowerManagerService: [PWL] Off : 455s ago
,07-05 12:06:39.643   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 12:06:39.773   287   287 E SMD     : DCD OFF,
,07-05 12:06:40.643   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 12:06:42.773   287   287 E SMD     : DCD OFF
,07-05 12:06:42.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:06:45.013  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:45.783  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:06:45.783   287   287 E SMD     : DCD OFF
07-05 12:06:45.783  1015  3343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-05 12:06:45.783  1015  3343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:06:45.783  1015  3343 D BatteryService: stay LED for fully charged
07-05 12:06:45.783  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:06:45.783  1015  1015 I MotionRecognitionService: Plugged
07-05 12:06:45.783  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:06:45.783  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:06:45.783  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:06:45.793  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:06:45.793  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:06:45.803  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:06:45.803  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:06:45.813  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:06:45.813  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:06:45.813  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:06:45.813  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:06:45.813  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:06:48.783   287   287 E SMD     : DCD OFF,
,07-05 12:06:51.783   287   287 E SMD     : DCD OFF
,07-05 12:06:54.783   287   287 E SMD     : DCD OFF,
,07-05 12:06:55.023  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:06:55.843  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:06:57.793   287   287 E SMD     : DCD OFF
,07-05 12:07:00.793   287   287 E SMD     : DCD OFF,
,07-05 12:07:02.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:07:03.793   287   287 E SMD     : DCD OFF,
,07-05 12:07:04.543  1015  1311 E Watchdog: !@Sync 18
,07-05 12:07:05.063  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:07:05.643   313   313 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 12:07:05.643   313   313 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 12:07:05.903  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:06.793   287   287 E SMD     : DCD OFF,
,07-05 12:07:09.793   287   287 E SMD     : DCD OFF,
,07-05 12:07:12.793   287   287 E SMD     : DCD OFF,
,07-05 12:07:15.073  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:07:15.803   287   287 E SMD     : DCD OFF
,07-05 12:07:15.973  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:18.803   287   287 E SMD     : DCD OFF
,07-05 12:07:21.803   287   287 E SMD     : DCD OFF,
,07-05 12:07:22.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:07:24.803   287   287 E SMD     : DCD OFF
,07-05 12:07:25.113  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:07:26.033  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:27.803   287   287 E SMD     : DCD OFF
,07-05 12:07:30.643   313   313 I Atfwd_Daemon: Stop the daemon....,
,07-05 12:07:30.803   287   287 E SMD     : DCD OFF,
,07-05 12:07:33.803   287   287 E SMD     : DCD OFF
,07-05 12:07:34.543  1015  1311 E Watchdog: !@Sync 19
,07-05 12:07:35.123  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:07:36.103  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:36.813   287   287 E SMD     : DCD OFF,
,07-05 12:07:39.813   287   287 E SMD     : DCD OFF
,07-05 12:07:42.813   287   287 E SMD     : DCD OFF,
,07-05 12:07:42.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 12:07:45.163  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:07:45.813   287   287 E SMD     : DCD OFF
,07-05 12:07:46.163  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:46.163  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:07:46.163  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:07:46.163  1015  1028 D BatteryService: stay LED for fully charged
07-05 12:07:46.163  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:46.163  1015  1015 I MotionRecognitionService: Plugged
07-05 12:07:46.163  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:07:46.163  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:07:46.163  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:07:46.163  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:07:46.173  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:07:46.173  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:07:46.173  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:07:46.193  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:46.193  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:46.193  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:46.193  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:07:46.193  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:07:48.813   287   287 E SMD     : DCD OFF
,07-05 12:07:48.973  1015  1047 I PowerManagerService: [PWL] Off : 525s ago
,07-05 12:07:51.813   287   287 E SMD     : DCD OFF
,07-05 12:07:54.813   287   287 E SMD     : DCD OFF,
,07-05 12:07:55.193  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:07:56.223  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:07:56.223  1015  3411 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:07:56.233  1015  3411 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:07:56.233  1015  3411 D BatteryService: stay LED for fully charged
07-05 12:07:56.233  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:07:56.233  1015  1015 I MotionRecognitionService: Plugged
07-05 12:07:56.233  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:07:56.233  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:07:56.233  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:07:56.233  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:07:56.233  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:07:56.243  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:07:56.243  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:07:56.253  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:56.263  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:07:56.263  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:07:56.263  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:07:56.263  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:07:57.823   287   287 E SMD     : DCD OFF
,07-05 12:08:00.823   287   287 E SMD     : DCD OFF,
,07-05 12:08:01.553  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 12:08:01.553  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
07-05 12:08:01.553  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:08:02.363  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:08:02.363  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:08:02.363  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:08:02.363  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:08:02.973  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:08:03.823   287   287 E SMD     : DCD OFF
,07-05 12:08:04.543  1015  1311 E Watchdog: !@Sync 20
,07-05 12:08:05.233  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:08:06.293  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:06.823   287   287 E SMD     : DCD OFF
,07-05 12:08:09.823   287   287 E SMD     : DCD OFF
,07-05 12:08:12.823   287   287 E SMD     : DCD OFF
,07-05 12:08:15.273  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:08:15.833   287   287 E SMD     : DCD OFF
,07-05 12:08:16.353  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:18.833   287   287 E SMD     : DCD OFF
,07-05 12:08:21.833   287   287 E SMD     : DCD OFF
,07-05 12:08:22.983  1015  2904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 12:08:24.833   287   287 E SMD     : DCD OFF
,07-05 12:08:25.303  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:08:26.423  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:27.833   287   287 E SMD     : DCD OFF
,07-05 12:08:30.833   287   287 E SMD     : DCD OFF
,07-05 12:08:33.833   287   287 E SMD     : DCD OFF
,07-05 12:08:34.553  1015  1311 E Watchdog: !@Sync 21
,07-05 12:08:35.323  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:08:36.483  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:36.493  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:08:36.493  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:08:36.493  1015  1489 D BatteryService: stay LED for fully charged
07-05 12:08:36.493  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:08:36.493  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:36.493  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:08:36.493  1015  1015 I MotionRecognitionService: Plugged
07-05 12:08:36.493  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:08:36.493  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:08:36.493  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:08:36.503  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:36.503  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:36.513  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:36.523  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:08:36.523  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:08:36.523  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:08:36.523  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:08:36.833   287   287 E SMD     : DCD OFF
,07-05 12:08:39.843   287   287 E SMD     : DCD OFF
,07-05 12:08:42.843   287   287 E SMD     : DCD OFF
,07-05 12:08:45.353  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:08:45.843   287   287 E SMD     : DCD OFF,
,07-05 12:08:46.553  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:08:46.553  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:08:46.553  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:08:46.553  1015  1479 D BatteryService: stay LED for fully charged
,07-05 12:08:46.553  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,07-05 12:08:46.553  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:08:46.563  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:08:46.563  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:08:46.563  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 12:08:46.563  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:08:46.563  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:08:46.573  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:08:46.573  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:08:46.583  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:08:46.583  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:08:46.583  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:08:46.583  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:08:46.583  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:08:48.843   287   287 E SMD     : DCD OFF
,07-05 12:08:51.843   287   287 E SMD     : DCD OFF
,07-05 12:08:54.843   287   287 E SMD     : DCD OFF
,07-05 12:08:55.383  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:08:56.613  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:08:57.843   287   287 E SMD     : DCD OFF
,07-05 12:09:00.853   287   287 E SMD     : DCD OFF,
,07-05 12:09:03.853   287   287 E SMD     : DCD OFF,
,07-05 12:09:03.983  1015  1047 I PowerManagerService: [PWL] Off : 600s ago
,07-05 12:09:04.553  1015  1311 E Watchdog: !@Sync 22,
,07-05 12:09:05.403  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:09:06.673  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:09:06.853   287   287 E SMD     : DCD OFF
,07-05 12:09:09.853   287   287 E SMD     : DCD OFF
,07-05 12:09:12.853   287   287 E SMD     : DCD OFF
,07-05 12:09:15.413  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:09:15.853   287   287 E SMD     : DCD OFF
,07-05 12:09:16.743  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:18.853   287   287 E SMD     : DCD OFF
,07-05 12:09:21.863   287   287 E SMD     : DCD OFF
,07-05 12:09:24.863   287   287 E SMD     : DCD OFF
,07-05 12:09:25.433  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:09:26.803  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:27.863   287   287 E SMD     : DCD OFF
,07-05 12:09:30.863   287   287 E SMD     : DCD OFF
,07-05 12:09:33.863   287   287 E SMD     : DCD OFF,
,07-05 12:09:34.553  1015  1311 E Watchdog: !@Sync 23
,07-05 12:09:35.453  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:09:36.863   287   287 E SMD     : DCD OFF,
,07-05 12:09:36.873  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:39.863   287   287 E SMD     : DCD OFF
,07-05 12:09:42.873   287   287 E SMD     : DCD OFF
,07-05 12:09:45.473  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:09:45.873   287   287 E SMD     : DCD OFF,
,07-05 12:09:46.933  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:09:48.873   287   287 E SMD     : DCD OFF,
,07-05 12:09:51.873   287   287 E SMD     : DCD OFF
,07-05 12:09:54.873   287   287 E SMD     : DCD OFF,
,07-05 12:09:55.503  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:09:57.003  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:09:57.003  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:09:57.003  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:09:57.003  1015  1134 D BatteryService: stay LED for fully charged
07-05 12:09:57.003  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:09:57.003  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:09:57.003  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:09:57.013  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:09:57.013  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:09:57.013  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:09:57.013  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:09:57.023  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:09:57.023  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:09:57.033  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:09:57.033  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:09:57.033  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:09:57.033  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:09:57.033  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:09:57.873   287   287 E SMD     : DCD OFF,
,07-05 12:10:00.883   287   287 E SMD     : DCD OFF,
,07-05 12:10:03.883   287   287 E SMD     : DCD OFF,
,07-05 12:10:04.553  1015  1311 E Watchdog: !@Sync 24
,07-05 12:10:05.513  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:06.883   287   287 E SMD     : DCD OFF,
,07-05 12:10:07.063  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:10:07.063  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:10:07.063  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:10:07.063  1015  1490 D BatteryService: stay LED for fully charged
07-05 12:10:07.063  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:07.073  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:07.073  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:07.073  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:10:07.073  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:10:07.083  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-05 12:10:07.083  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:10:07.093  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:07.093  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:07.103  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:07.103  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:10:07.103  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:07.103  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:10:07.103  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:10:09.883   287   287 E SMD     : DCD OFF,
,07-05 12:10:12.883   287   287 E SMD     : DCD OFF
,07-05 12:10:15.533  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:15.883   287   287 E SMD     : DCD OFF,
,07-05 12:10:17.133  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:18.893   287   287 E SMD     : DCD OFF,
,07-05 12:10:21.893   287   287 E SMD     : DCD OFF
,07-05 12:10:23.993  1015  1047 I PowerManagerService: [PWL] Off : 680s ago,
,07-05 12:10:24.893   287   287 E SMD     : DCD OFF
,07-05 12:10:25.543  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:27.193  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:27.893   287   287 E SMD     : DCD OFF,
,07-05 12:10:30.893   287   287 E SMD     : DCD OFF,
,07-05 12:10:33.893   287   287 E SMD     : DCD OFF,
,07-05 12:10:34.553  1015  1311 E Watchdog: !@Sync 25,
,07-05 12:10:35.563  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:36.893   287   287 E SMD     : DCD OFF,
,07-05 12:10:37.263  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:37.263  1015  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:10:37.263  1015  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:10:37.263  1015  3410 D BatteryService: stay LED for fully charged
,07-05 12:10:37.263  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:37.273  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:10:37.273  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:10:37.273  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:10:37.273  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:37.273  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:10:37.273  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:10:37.283  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:10:37.283  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:37.293  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:37.293  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:37.293  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:10:37.293  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:10:37.293  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:10:39.903   287   287 E SMD     : DCD OFF
,07-05 12:10:42.903   287   287 E SMD     : DCD OFF,
,07-05 12:10:45.583  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:45.903   287   287 E SMD     : DCD OFF,
,07-05 12:10:47.323  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:47.333  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:10:47.333  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:10:47.333  1015  1028 D BatteryService: stay LED for fully charged
07-05 12:10:47.333  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:10:47.333  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:10:47.333  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:10:47.333  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:10:47.343  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:10:47.343  1015  1015 I MotionRecognitionService: Plugged
07-05 12:10:47.343  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:10:47.353  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 12:10:47.353  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:10:47.363  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:47.363  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:10:47.363  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:10:47.363  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:10:47.363  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:10:48.903   287   287 E SMD     : DCD OFF,
,07-05 12:10:51.903   287   287 E SMD     : DCD OFF
,07-05 12:10:54.903   287   287 E SMD     : DCD OFF,
,07-05 12:10:55.603  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:10:57.393  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:10:57.913   287   287 E SMD     : DCD OFF,
,07-05 12:11:00.913   287   287 E SMD     : DCD OFF,
,07-05 12:11:03.913   287   287 E SMD     : DCD OFF,
,07-05 12:11:04.553  1015  1311 E Watchdog: !@Sync 26
,07-05 12:11:05.623  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:11:06.913   287   287 E SMD     : DCD OFF,
,07-05 12:11:07.463  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:07.463  1015  3343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:11:07.463  1015  3343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:11:07.463  1015  3343 D BatteryService: stay LED for fully charged
,07-05 12:11:07.463  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:07.463  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:07.463  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:07.473  1015  1015 I MotionRecognitionService: Plugged
07-05 12:11:07.473  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:11:07.473  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:11:07.473  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:11:07.473  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:07.483  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:07.493  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:07.493  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:07.493  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:07.493  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:11:07.493  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:11:08.273  1015  1093 V AlarmManager: waitForAlarm result :8
,07-05 12:11:09.913   287   287 E SMD     : DCD OFF,
,07-05 12:11:12.913   287   287 E SMD     : DCD OFF
,07-05 12:11:15.663  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:11:15.923   287   287 E SMD     : DCD OFF
,07-05 12:11:17.523  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:17.523  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:11:17.523  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:11:17.523  1015  1489 D BatteryService: stay LED for fully charged
07-05 12:11:17.523  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:17.533  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:11:17.533  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:17.533  1015  1015 I MotionRecognitionService: Plugged
07-05 12:11:17.533  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:11:17.533  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:11:17.533  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:11:17.543  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:17.543  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:17.553  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:17.553  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:17.553  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:17.553  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:11:17.553  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:11:18.923   287   287 E SMD     : DCD OFF,
,07-05 12:11:21.923   287   287 E SMD     : DCD OFF
,07-05 12:11:24.923   287   287 E SMD     : DCD OFF,
,07-05 12:11:25.693  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:11:27.593  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:11:27.593  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:11:27.593  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:11:27.593  1015  1479 D BatteryService: stay LED for fully charged
07-05 12:11:27.593  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:11:27.593  1015  1015 I MotionRecognitionService: Plugged
07-05 12:11:27.593  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:11:27.593  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:11:27.593  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:11:27.603  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:11:27.603  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:11:27.613  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:11:27.613  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:11:27.623  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:27.623  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:11:27.623  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:11:27.623  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:11:27.623  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:11:27.923   287   287 E SMD     : DCD OFF
,07-05 12:11:30.923   287   287 E SMD     : DCD OFF
,07-05 12:11:33.923   287   287 E SMD     : DCD OFF,
,07-05 12:11:34.553  1015  1311 E Watchdog: !@Sync 27,
,07-05 12:11:35.713  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:11:36.933   287   287 E SMD     : DCD OFF
,07-05 12:11:37.653  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:39.933   287   287 E SMD     : DCD OFF,
,07-05 12:11:42.933   287   287 E SMD     : DCD OFF
,07-05 12:11:45.743  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:11:45.933   287   287 E SMD     : DCD OFF,
,07-05 12:11:47.723  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:48.933   287   287 E SMD     : DCD OFF,
,07-05 12:11:49.013  1015  1047 I PowerManagerService: [PWL] Off : 765s ago,
,07-05 12:11:51.933   287   287 E SMD     : DCD OFF
,07-05 12:11:54.943   287   287 E SMD     : DCD OFF
,07-05 12:11:55.753  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:11:57.783  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:11:57.943   287   287 E SMD     : DCD OFF
,07-05 12:12:00.943   287   287 E SMD     : DCD OFF,
,07-05 12:12:03.943   287   287 E SMD     : DCD OFF
,07-05 12:12:04.553  1015  1311 E Watchdog: !@Sync 28
,07-05 12:12:05.783  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:12:06.943   287   287 E SMD     : DCD OFF,
,07-05 12:12:07.853  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:09.943   287   287 E SMD     : DCD OFF,
,07-05 12:12:12.953   287   287 E SMD     : DCD OFF
,07-05 12:12:15.793  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:12:15.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:17.913  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:18.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:21.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:24.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:25.813  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:12:27.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:27.983  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:12:30.953   287   287 E SMD     : DCD OFF,
,07-05 12:12:33.963   287   287 E SMD     : DCD OFF,
,07-05 12:12:34.553  1015  1311 E Watchdog: !@Sync 29
,07-05 12:12:35.833  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:12:36.963   287   287 E SMD     : DCD OFF,
,07-05 12:12:38.043  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:12:38.043  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:12:38.043  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:12:38.043  1015  1489 D BatteryService: stay LED for fully charged
07-05 12:12:38.043  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:38.053  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:12:38.053  1015  1015 I MotionRecognitionService: Plugged
07-05 12:12:38.053  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:12:38.053  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:12:38.053  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:12:38.053  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:12:38.073  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:12:38.073  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:38.083  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:12:38.083  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:12:38.083  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:12:38.083  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:12:38.083  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:12:39.963   287   287 E SMD     : DCD OFF,
,07-05 12:12:42.963   287   287 E SMD     : DCD OFF
,07-05 12:12:45.843  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:12:45.963   287   287 E SMD     : DCD OFF
,07-05 12:12:48.113  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:12:48.113  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:12:48.113  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:12:48.113  1015  1479 D BatteryService: stay LED for fully charged
07-05 12:12:48.113  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:12:48.113  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:12:48.123  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:12:48.113  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:12:48.123  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 12:12:48.123  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:12:48.123  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:12:48.133  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:12:48.133  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:12:48.143  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:48.143  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:12:48.143  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:12:48.143  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:12:48.143  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:12:48.963   287   287 E SMD     : DCD OFF,
,07-05 12:12:51.963   287   287 E SMD     : DCD OFF
,07-05 12:12:54.973   287   287 E SMD     : DCD OFF,
,07-05 12:12:55.863  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:12:57.973   287   287 E SMD     : DCD OFF,
,07-05 12:12:58.173  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:00.973   287   287 E SMD     : DCD OFF
,07-05 12:13:01.553  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:13:01.553  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:13:01.553  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:13:03.433  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:13:03.433  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:13:03.433  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:13:03.433  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:13:03.973   287   287 E SMD     : DCD OFF
,07-05 12:13:04.553  1015  1311 E Watchdog: !@Sync 30
,07-05 12:13:05.883  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:06.973   287   287 E SMD     : DCD OFF,
,07-05 12:13:08.243  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:09.973   287   287 E SMD     : DCD OFF,
,07-05 12:13:12.983   287   287 E SMD     : DCD OFF,
,07-05 12:13:15.883  1015  1093 V AlarmManager: waitForAlarm result :4
,07-05 12:13:15.893  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 12:13:15.893  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 12:13:15.893  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 12:13:15.893  1015  1015 E SAMP_GCMKill: got intent GCM_LOCKER_ALARM, mScreenOn=false
,07-05 12:13:15.903  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 12:13:15.903  1015  1015 V SAMP_GCMKill: GCM kill size 0. just return,
,07-05 12:13:15.913  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:15.913  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 12:13:15.913  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 12:13:15.923  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:15.953  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:15.963  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:15.963  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:15.973  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,07-05 12:13:15.983   287   287 E SMD     : DCD OFF
,07-05 12:13:15.983  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 12:13:16.183  1661  2712 D GCM     : Message class com.google.f.a.a.i
,07-05 12:13:18.303  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:18.313  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:13:18.313  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:13:18.313  1015  1028 D BatteryService: stay LED for fully charged
07-05 12:13:18.313  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:13:18.313  1015  1015 I MotionRecognitionService: Plugged
07-05 12:13:18.313  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:13:18.313  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:13:18.313  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:13:18.323  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:13:18.323  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:13:18.333  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:13:18.333  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:13:18.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:13:18.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:13:18.343  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:13:18.343  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:13:18.343  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:13:18.983   287   287 E SMD     : DCD OFF
,07-05 12:13:19.013  1015  1047 I PowerManagerService: [PWL] Off : 855s ago
,07-05 12:13:21.983   287   287 E SMD     : DCD OFF
,07-05 12:13:24.983   287   287 E SMD     : DCD OFF
,07-05 12:13:25.963  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:27.983   287   287 E SMD     : DCD OFF,
,07-05 12:13:28.373  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:30.983   287   287 E SMD     : DCD OFF
,07-05 12:13:33.993   287   287 E SMD     : DCD OFF,
,07-05 12:13:34.553  1015  1311 E Watchdog: !@Sync 31,
,07-05 12:13:35.973  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:36.993   287   287 E SMD     : DCD OFF
,07-05 12:13:38.443  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:39.993   287   287 E SMD     : DCD OFF,
,07-05 12:13:42.993   287   287 E SMD     : DCD OFF,
,07-05 12:13:45.993   287   287 E SMD     : DCD OFF
,07-05 12:13:46.013  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:48.503  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:49.003   287   287 E SMD     : DCD OFF
,07-05 12:13:52.003   287   287 E SMD     : DCD OFF
,07-05 12:13:55.003   287   287 E SMD     : DCD OFF
,07-05 12:13:56.023  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:13:58.003   287   287 E SMD     : DCD OFF
,07-05 12:13:58.573  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:13:59.993  1015  1093 V AlarmManager: waitForAlarm result :8
,07-05 12:14:01.003   287   287 E SMD     : DCD OFF
,07-05 12:14:04.003   287   287 E SMD     : DCD OFF
,07-05 12:14:04.553  1015  1311 E Watchdog: !@Sync 32
,07-05 12:14:06.043  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:14:07.003   287   287 E SMD     : DCD OFF
,07-05 12:14:08.643  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:10.013   287   287 E SMD     : DCD OFF
,07-05 12:14:13.013   287   287 E SMD     : DCD OFF
,07-05 12:14:16.013   287   287 E SMD     : DCD OFF
,07-05 12:14:16.053  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:14:18.703  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:19.013   287   287 E SMD     : DCD OFF
,07-05 12:14:22.013   287   287 E SMD     : DCD OFF
,07-05 12:14:25.013   287   287 E SMD     : DCD OFF,
,07-05 12:14:26.073  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:14:28.013   287   287 E SMD     : DCD OFF
,07-05 12:14:28.773  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:14:31.013   287   287 E SMD     : DCD OFF
,07-05 12:14:34.023   287   287 E SMD     : DCD OFF
,07-05 12:14:34.553  1015  1311 E Watchdog: !@Sync 33
,07-05 12:14:36.103  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:14:37.023   287   287 E SMD     : DCD OFF,
,07-05 12:14:38.833  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:14:40.023   287   287 E SMD     : DCD OFF
,07-05 12:14:43.023   287   287 E SMD     : DCD OFF
,07-05 12:14:46.023   287   287 E SMD     : DCD OFF
,07-05 12:14:46.113  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:14:48.903  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:14:49.023   287   287 E SMD     : DCD OFF
,07-05 12:14:52.023   287   287 E SMD     : DCD OFF
,07-05 12:14:54.073  1015  1047 I PowerManagerService: [PWL] Off : 950s ago
,07-05 12:14:55.023   287   287 E SMD     : DCD OFF
,07-05 12:14:56.123  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:14:58.033   287   287 E SMD     : DCD OFF
,07-05 12:14:58.973  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:01.033   287   287 E SMD     : DCD OFF
,07-05 12:15:04.033   287   287 E SMD     : DCD OFF
,07-05 12:15:04.553  1015  1311 E Watchdog: !@Sync 34,
,07-05 12:15:06.163  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:15:07.033   287   287 E SMD     : DCD OFF
,07-05 12:15:09.033  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:10.033   287   287 E SMD     : DCD OFF
,07-05 12:15:13.033   287   287 E SMD     : DCD OFF
,07-05 12:15:16.033   287   287 E SMD     : DCD OFF,
,07-05 12:15:16.203  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:15:19.043   287   287 E SMD     : DCD OFF
,07-05 12:15:19.103  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:15:22.043   287   287 E SMD     : DCD OFF
,07-05 12:15:25.043   287   287 E SMD     : DCD OFF
,07-05 12:15:26.243  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:15:28.043   287   287 E SMD     : DCD OFF
,07-05 12:15:29.163  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:31.043   287   287 E SMD     : DCD OFF
,07-05 12:15:34.043   287   287 E SMD     : DCD OFF
,07-05 12:15:34.553  1015  1311 E Watchdog: !@Sync 35,
,07-05 12:15:36.263  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:15:37.043   287   287 E SMD     : DCD OFF
,07-05 12:15:39.233  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:15:40.043   287   287 E SMD     : DCD OFF
,07-05 12:15:43.053   287   287 E SMD     : DCD OFF
,07-05 12:15:46.053   287   287 E SMD     : DCD OFF
,07-05 12:15:46.283  1015  2885 D SSRM:n  : SIOP:: AP = 300
,07-05 12:15:49.053   287   287 E SMD     : DCD OFF
,07-05 12:15:49.303  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:15:52.053   287   287 E SMD     : DCD OFF
,07-05 12:15:55.053   287   287 E SMD     : DCD OFF
,07-05 12:15:56.293  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:15:58.053   287   287 E SMD     : DCD OFF
,07-05 12:15:59.373  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:01.053   287   287 E SMD     : DCD OFF,
,07-05 12:16:04.063   287   287 E SMD     : DCD OFF,
,07-05 12:16:04.553  1015  1311 E Watchdog: !@Sync 36
,07-05 12:16:06.333  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:16:07.063   287   287 E SMD     : DCD OFF
,07-05 12:16:09.433  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:10.063   287   287 E SMD     : DCD OFF
,07-05 12:16:13.063   287   287 E SMD     : DCD OFF
,07-05 12:16:16.063   287   287 E SMD     : DCD OFF
,07-05 12:16:16.353  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:16:19.063   287   287 E SMD     : DCD OFF
,07-05 12:16:19.503  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:22.063   287   287 E SMD     : DCD OFF
,07-05 12:16:25.063   287   287 E SMD     : DCD OFF
,07-05 12:16:26.363  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:16:28.073   287   287 E SMD     : DCD OFF
,07-05 12:16:29.563  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:31.073   287   287 E SMD     : DCD OFF
,07-05 12:16:34.073   287   287 E SMD     : DCD OFF
,07-05 12:16:34.143  1015  1047 I PowerManagerService: [PWL] Off : 1050s ago
,07-05 12:16:34.553  1015  1311 E Watchdog: !@Sync 37,
,07-05 12:16:36.383  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:16:37.073   287   287 E SMD     : DCD OFF
,07-05 12:16:39.633  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:40.073   287   287 E SMD     : DCD OFF
,07-05 12:16:43.073   287   287 E SMD     : DCD OFF
,07-05 12:16:46.073   287   287 E SMD     : DCD OFF
,07-05 12:16:46.393  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:16:49.083   287   287 E SMD     : DCD OFF
,07-05 12:16:49.693  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:16:52.083   287   287 E SMD     : DCD OFF
,07-05 12:16:55.083   287   287 E SMD     : DCD OFF,
,07-05 12:16:56.433  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:16:58.083   287   287 E SMD     : DCD OFF
,07-05 12:16:59.763  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:17:01.083   287   287 E SMD     : DCD OFF
,07-05 12:17:04.083   287   287 E SMD     : DCD OFF,
,07-05 12:17:04.563  1015  1311 E Watchdog: !@Sync 38,
,07-05 12:17:06.443  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:17:07.083   287   287 E SMD     : DCD OFF
,07-05 12:17:09.823  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:17:10.083   287   287 E SMD     : DCD OFF,
,07-05 12:17:13.093   287   287 E SMD     : DCD OFF
,07-05 12:17:16.093   287   287 E SMD     : DCD OFF,
,07-05 12:17:16.483  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:17:19.093   287   287 E SMD     : DCD OFF,
,07-05 12:17:19.893  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:19.893  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-05 12:17:19.893  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:17:19.893  1015  1479 D BatteryService: stay LED for fully charged
07-05 12:17:19.893  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:17:19.893  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:17:19.893  1015  1015 I MotionRecognitionService: Plugged
07-05 12:17:19.893  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 12:17:19.893  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:17:19.903  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:17:19.903  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:17:19.913  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:17:19.913  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:19.923  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:19.923  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:19.923  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:19.923  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:17:19.923  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:17:22.093   287   287 E SMD     : DCD OFF
,07-05 12:17:25.093   287   287 E SMD     : DCD OFF
,07-05 12:17:26.503  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:17:28.093   287   287 E SMD     : DCD OFF
,07-05 12:17:29.953  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:29.953  1015  1529 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-05 12:17:29.953  1015  1529 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:17:29.953  1015  1529 D BatteryService: stay LED for fully charged
07-05 12:17:29.953  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:17:29.963  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:17:29.963  1015  1015 I MotionRecognitionService: Plugged
07-05 12:17:29.963  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:17:29.963  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:17:29.963  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:17:29.963  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:17:29.973  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:17:29.973  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:29.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:17:29.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:17:29.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:17:29.983  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
07-05 12:17:29.983  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:17:31.093   287   287 E SMD     : DCD OFF
,07-05 12:17:34.103   287   287 E SMD     : DCD OFF
,07-05 12:17:34.563  1015  1311 E Watchdog: !@Sync 39
,07-05 12:17:36.543  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:17:37.103   287   287 E SMD     : DCD OFF
,07-05 12:17:40.023  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:17:40.103   287   287 E SMD     : DCD OFF,
,07-05 12:17:43.103   287   287 E SMD     : DCD OFF
,07-05 12:17:46.103   287   287 E SMD     : DCD OFF
,07-05 12:17:46.583  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:17:49.103   287   287 E SMD     : DCD OFF
,07-05 12:17:50.083  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:17:50.083  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:17:50.083  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:17:50.083  1015  1028 D BatteryService: stay LED for fully charged
07-05 12:17:50.083  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:17:50.093  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:17:50.093  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:17:50.093  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:17:50.093  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:17:50.093  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:17:50.093  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:17:50.103  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:17:50.103  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:17:50.113  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:50.113  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:17:50.113  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:17:50.113  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:17:50.113  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:17:52.103   287   287 E SMD     : DCD OFF
,07-05 12:17:55.103   287   287 E SMD     : DCD OFF
,07-05 12:17:56.593  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:17:58.113   287   287 E SMD     : DCD OFF
,07-05 12:18:00.143  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:18:00.143  1015  1506 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:18:00.153  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:18:00.143  1015  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:18:00.153  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:18:00.143  1015  1506 D BatteryService: stay LED for fully charged
07-05 12:18:00.143  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:18:00.153  1015  1015 I MotionRecognitionService: Plugged,
07-05 12:18:00.153  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:18:00.153  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:18:00.153  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:18:00.173  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:00.173  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:00.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:00.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:00.183  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:00.183  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:18:00.183  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:18:01.113   287   287 E SMD     : DCD OFF
,07-05 12:18:01.553  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. ,
07-05 12:18:01.553  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 12:18:01.553  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:18:02.183  1015  1039 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 12:18:02.223  1015  1100 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 12:18:02.223  1015  1100 I ApplicationUsage: Updating Usage Statistics in DB @ 1467713882226
,07-05 12:18:02.223  1015  1100 I ApplicationPolicy: updateDataUsageMap
,07-05 12:18:02.363  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:18:02.363  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:18:02.363  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:18:02.363  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:18:02.473  1015  1100 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,07-05 12:18:02.473  1015  1100 I NetworkDataUsageDb: ::isTableExists: Table exists 
,07-05 12:18:02.483  1015  1100 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467713882494
,07-05 12:18:04.113   287   287 E SMD     : DCD OFF,
,07-05 12:18:04.563  1015  1311 E Watchdog: !@Sync 40
,07-05 12:18:06.633  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:18:07.113   287   287 E SMD     : DCD OFF
,07-05 12:18:10.113   287   287 E SMD     : DCD OFF
,07-05 12:18:10.213  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:10.213  1015  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:18:10.213  1015  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:18:10.213  1015  1489 D BatteryService: stay LED for fully charged
07-05 12:18:10.213  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:10.213  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:18:10.213  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
07-05 12:18:10.213  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
07-05 12:18:10.213  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:18:10.213  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 12:18:10.213  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:18:10.223  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:10.223  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:10.233  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:10.243  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:10.243  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:10.243  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:18:10.243  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:18:13.113   287   287 E SMD     : DCD OFF
,07-05 12:18:15.903  1015  1093 V AlarmManager: waitForAlarm result :8
,07-05 12:18:16.113   287   287 E SMD     : DCD OFF
,07-05 12:18:16.643  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:18:19.113   287   287 E SMD     : DCD OFF,
,07-05 12:18:19.153  1015  1047 I PowerManagerService: [PWL] Off : 1155s ago,
,07-05 12:18:20.273  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:20.273  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:18:20.273  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:18:20.273  1015  1027 D BatteryService: stay LED for fully charged
07-05 12:18:20.273  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:20.273  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:18:20.283  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:18:20.283  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:20.283  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:20.283  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:18:20.283  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:18:20.293  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:20.293  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:20.303  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:20.303  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:20.303  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:20.313  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:18:20.313  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:18:22.123   287   287 E SMD     : DCD OFF
,07-05 12:18:25.123   287   287 E SMD     : DCD OFF,
,07-05 12:18:26.653  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:18:28.123   287   287 E SMD     : DCD OFF
,07-05 12:18:30.333  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:30.343  1015  1256 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:18:30.343  1015  1256 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:18:30.343  1015  1256 D BatteryService: stay LED for fully charged
,07-05 12:18:30.343  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:18:30.343  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:18:30.343  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:18:30.353  1015  1015 I MotionRecognitionService: Plugged
07-05 12:18:30.353  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:18:30.353  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:18:30.353  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:18:30.363  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:18:30.363  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:18:30.373  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:30.373  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:18:30.373  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:18:30.373  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:18:30.373  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:18:31.123   287   287 E SMD     : DCD OFF
,07-05 12:18:34.123   287   287 E SMD     : DCD OFF,
,07-05 12:18:34.563  1015  1311 E Watchdog: !@Sync 41
,07-05 12:18:36.703  1015  2885 D SSRM:n  : SIOP:: AP = 300,
,07-05 12:18:37.123   287   287 E SMD     : DCD OFF
,07-05 12:18:40.123   287   287 E SMD     : DCD OFF
,07-05 12:18:40.403  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:18:43.133   287   287 E SMD     : DCD OFF
,07-05 12:18:46.133   287   287 E SMD     : DCD OFF
,07-05 12:18:46.743  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:18:49.133   287   287 E SMD     : DCD OFF,
,07-05 12:18:50.463  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:18:52.133   287   287 E SMD     : DCD OFF
,07-05 12:18:55.133   287   287 E SMD     : DCD OFF
,07-05 12:18:56.783  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:18:58.133   287   287 E SMD     : DCD OFF
,07-05 12:19:00.523  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:01.133   287   287 E SMD     : DCD OFF
,07-05 12:19:04.143   287   287 E SMD     : DCD OFF,
,07-05 12:19:04.563  1015  1311 E Watchdog: !@Sync 42
,07-05 12:19:06.823  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:19:07.143   287   287 E SMD     : DCD OFF
,07-05 12:19:10.143   287   287 E SMD     : DCD OFF
,07-05 12:19:10.593  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:19:13.143   287   287 E SMD     : DCD OFF,
,07-05 12:19:16.143   287   287 E SMD     : DCD OFF
,07-05 12:19:16.863  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:19:19.143   287   287 E SMD     : DCD OFF,
,07-05 12:19:20.653  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:22.143   287   287 E SMD     : DCD OFF
,07-05 12:19:25.143   287   287 E SMD     : DCD OFF
,07-05 12:19:26.883  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:19:28.153   287   287 E SMD     : DCD OFF,
,07-05 12:19:30.723  1015  1268 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:19:31.153   287   287 E SMD     : DCD OFF
,07-05 12:19:34.153   287   287 E SMD     : DCD OFF
,07-05 12:19:34.563  1015  1311 E Watchdog: !@Sync 43
,07-05 12:19:36.923  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:19:37.153   287   287 E SMD     : DCD OFF
,07-05 12:19:40.153   287   287 E SMD     : DCD OFF
,07-05 12:19:40.783  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:19:43.153   287   287 E SMD     : DCD OFF,
,07-05 12:19:46.153   287   287 E SMD     : DCD OFF
,07-05 12:19:46.963  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:19:49.153   287   287 E SMD     : DCD OFF
,07-05 12:19:50.853  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:19:52.163   287   287 E SMD     : DCD OFF
,07-05 12:19:55.163   287   287 E SMD     : DCD OFF
,07-05 12:19:56.973  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:19:58.163   287   287 E SMD     : DCD OFF,
,07-05 12:20:00.913  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:01.163   287   287 E SMD     : DCD OFF
,07-05 12:20:04.163   287   287 E SMD     : DCD OFF
,07-05 12:20:04.563  1015  1311 E Watchdog: !@Sync 44,
,07-05 12:20:06.993  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:20:07.163   287   287 E SMD     : DCD OFF
,07-05 12:20:09.253  1015  1047 I PowerManagerService: [PWL] Off : 1266s ago
,07-05 12:20:10.163   287   287 E SMD     : DCD OFF
,07-05 12:20:10.983  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:20:13.173   287   287 E SMD     : DCD OFF,
,07-05 12:20:16.173   287   287 E SMD     : DCD OFF,
,07-05 12:20:17.003  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:20:19.173   287   287 E SMD     : DCD OFF,
,07-05 12:20:21.043  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:22.173   287   287 E SMD     : DCD OFF
,07-05 12:20:25.173   287   287 E SMD     : DCD OFF
,07-05 12:20:27.023  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:20:28.173   287   287 E SMD     : DCD OFF,
,07-05 12:20:31.113  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:31.173   287   287 E SMD     : DCD OFF
,07-05 12:20:34.173   287   287 E SMD     : DCD OFF
,07-05 12:20:34.563  1015  1311 E Watchdog: !@Sync 45
,07-05 12:20:37.033  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:20:37.183   287   287 E SMD     : DCD OFF
,07-05 12:20:40.183   287   287 E SMD     : DCD OFF
,07-05 12:20:41.173  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 12:20:41.173  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:20:41.173  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:20:41.173  1015  1490 D BatteryService: stay LED for fully charged
07-05 12:20:41.173  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:41.183  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:41.183  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:20:41.183  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:20:41.183  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:20:41.193  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:20:41.193  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:20:41.193  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:41.203  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:41.213  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:41.213  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:41.213  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:41.213  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:20:41.213  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:20:43.183   287   287 E SMD     : DCD OFF,
,07-05 12:20:46.183   287   287 E SMD     : DCD OFF
,07-05 12:20:47.083  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:20:49.183   287   287 E SMD     : DCD OFF
,07-05 12:20:51.243  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:20:51.243  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:20:51.243  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:20:51.243  1015  1479 D BatteryService: stay LED for fully charged
,07-05 12:20:51.243  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:20:51.253  1015  1015 I MotionRecognitionService: Plugged
07-05 12:20:51.253  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:20:51.253  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:20:51.253  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:20:51.253  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:20:51.253  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:20:51.263  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:20:51.263  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:20:51.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:20:51.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:51.273  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:20:51.273  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:20:51.273  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:20:52.183   287   287 E SMD     : DCD OFF
,07-05 12:20:55.183   287   287 E SMD     : DCD OFF
,07-05 12:20:57.123  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:20:58.183   287   287 E SMD     : DCD OFF
,07-05 12:21:01.193   287   287 E SMD     : DCD OFF,
,07-05 12:21:01.303  1015  1529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:21:01.303  1015  1529 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:21:01.303  1015  1529 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:21:01.303  1015  1529 D BatteryService: stay LED for fully charged
07-05 12:21:01.303  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 12:21:01.303  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:21:01.303  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:21:01.313  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:21:01.313  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:21:01.313  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:21:01.313  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:21:01.323  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:21:01.323  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:21:01.333  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:01.333  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:01.333  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:01.333  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:21:01.333  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:21:04.193   287   287 E SMD     : DCD OFF
,07-05 12:21:04.563  1015  1311 E Watchdog: !@Sync 46
,07-05 12:21:07.133  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:07.193   287   287 E SMD     : DCD OFF
,07-05 12:21:10.193   287   287 E SMD     : DCD OFF
,07-05 12:21:11.373  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:13.193   287   287 E SMD     : DCD OFF,
,07-05 12:21:16.193   287   287 E SMD     : DCD OFF
,07-05 12:21:17.153  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:19.193   287   287 E SMD     : DCD OFF
,07-05 12:21:21.433  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:21:22.193   287   287 E SMD     : DCD OFF
,07-05 12:21:25.203   287   287 E SMD     : DCD OFF
,07-05 12:21:27.163  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:28.203   287   287 E SMD     : DCD OFF,
,07-05 12:21:31.203   287   287 E SMD     : DCD OFF
,07-05 12:21:31.503  1015  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:31.503  1015  1256 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:21:31.503  1015  1256 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:21:31.503  1015  1256 D BatteryService: stay LED for fully charged
07-05 12:21:31.503  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:21:31.503  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:21:31.503  1015  1015 I MotionRecognitionService: Plugged
07-05 12:21:31.503  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-05 12:21:31.513  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:21:31.513  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-05 12:21:31.513  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:21:31.523  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:21:31.523  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:21:31.533  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:21:31.533  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:31.533  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:31.533  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:21:31.533  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:21:34.203   287   287 E SMD     : DCD OFF,
,07-05 12:21:34.563  1015  1311 E Watchdog: !@Sync 47
,07-05 12:21:37.203   287   287 E SMD     : DCD OFF
,07-05 12:21:37.203  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:40.203   287   287 E SMD     : DCD OFF
,07-05 12:21:41.563  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:41.563  1015  3343 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:21:41.563  1015  3343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:21:41.563  1015  3343 D BatteryService: stay LED for fully charged
07-05 12:21:41.563  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:21:41.563  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:21:41.563  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:21:41.573  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:21:41.573  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:21:41.573  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:21:41.573  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:21:41.583  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:21:41.583  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:21:41.593  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:21:41.593  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:41.593  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:41.593  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:21:41.593  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:21:43.203   287   287 E SMD     : DCD OFF,
,07-05 12:21:46.213   287   287 E SMD     : DCD OFF
,07-05 12:21:47.223  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:49.213   287   287 E SMD     : DCD OFF
,07-05 12:21:51.623  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:21:51.623  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:21:51.623  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:21:51.623  1015  1490 D BatteryService: stay LED for fully charged
,07-05 12:21:51.623  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:21:51.633  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:21:51.633  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:21:51.633  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:21:51.633  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:21:51.643  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:21:51.643  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:21:51.653  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:21:51.653  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:21:51.663  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:21:51.663  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:51.663  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:21:51.663  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:21:51.663  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:21:52.213   287   287 E SMD     : DCD OFF,
,07-05 12:21:55.213   287   287 E SMD     : DCD OFF,
,07-05 12:21:57.233  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:21:58.213   287   287 E SMD     : DCD OFF
,07-05 12:22:01.213   287   287 E SMD     : DCD OFF
,07-05 12:22:01.683  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:01.683  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:22:01.683  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:22:01.693  1015  1479 D BatteryService: stay LED for fully charged
07-05 12:22:01.693  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:01.693  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:22:01.693  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:22:01.693  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:01.693  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:01.693  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:22:01.693  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:22:01.703  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 12:22:01.703  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:01.713  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:01.713  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:01.713  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:01.713  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:22:01.713  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:22:04.213   287   287 E SMD     : DCD OFF
,07-05 12:22:04.253  1015  1047 I PowerManagerService: [PWL] Off : 1381s ago,
,07-05 12:22:04.563  1015  1311 E Watchdog: !@Sync 48,
,07-05 12:22:07.213   287   287 E SMD     : DCD OFF
,07-05 12:22:07.273  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:22:10.223   287   287 E SMD     : DCD OFF
,07-05 12:22:11.753  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 12:22:11.753  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:22:11.753  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:22:11.753  1015  1028 D BatteryService: stay LED for fully charged
07-05 12:22:11.753  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:11.753  1015  1015 I MotionRecognitionService: Plugged
07-05 12:22:11.753  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:22:11.763  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 12:22:11.763  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 12:22:11.763  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 12:22:11.763  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:22:11.773  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:22:11.773  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:11.783  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 12:22:11.783  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:11.783  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:11.783  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:22:11.783  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:22:13.223   287   287 E SMD     : DCD OFF
,07-05 12:22:16.223   287   287 E SMD     : DCD OFF
,07-05 12:22:17.283  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:22:19.223   287   287 E SMD     : DCD OFF
,07-05 12:22:21.813  1015  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:22:22.223   287   287 E SMD     : DCD OFF,
,07-05 12:22:25.223   287   287 E SMD     : DCD OFF
,07-05 12:22:27.333  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:22:28.223   287   287 E SMD     : DCD OFF
,07-05 12:22:31.223   287   287 E SMD     : DCD OFF,
,07-05 12:22:31.883  1015  3343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:22:34.233   287   287 E SMD     : DCD OFF
,07-05 12:22:34.563  1015  1311 E Watchdog: !@Sync 49
,07-05 12:22:37.233   287   287 E SMD     : DCD OFF
,07-05 12:22:37.373  1015  2885 D SSRM:n  : SIOP:: AP = 290,
,07-05 12:22:40.233   287   287 E SMD     : DCD OFF
,07-05 12:22:41.953  1015  3410 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:41.953  1015  3410 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:22:41.953  1015  3410 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:22:41.953  1015  3410 D BatteryService: stay LED for fully charged
,07-05 12:22:41.953  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:41.953  1015  1015 I MotionRecognitionService: Plugged
07-05 12:22:41.953  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:22:41.953  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:41.953  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:41.963  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:22:41.963  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:22:41.973  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:22:41.973  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:41.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:41.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:41.983  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:41.983  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,07-05 12:22:41.983  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:22:43.233   287   287 E SMD     : DCD OFF
,07-05 12:22:46.233   287   287 E SMD     : DCD OFF
,07-05 12:22:47.383  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:22:49.233   287   287 E SMD     : DCD OFF,
,07-05 12:22:52.013  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:22:52.013  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 12:22:52.013  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-05 12:22:52.013  1015  1134 D BatteryService: stay LED for fully charged
,07-05 12:22:52.013  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 12:22:52.023  1015  1015 I MotionRecognitionService: Plugged
,07-05 12:22:52.023  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 12:22:52.023  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 12:22:52.023  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 12:22:52.023  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 12:22:52.033  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 12:22:52.043  2810  2810 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 12:22:52.043  2810  3032 D HeadsetStateMachine: Disconnected process message: 10
,07-05 12:22:52.053  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:52.053  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 12:22:52.053  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 12:22:52.053  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-05 12:22:52.053  1176  1176 D SViewCoverView: level :100 plugged : 2
,07-05 12:22:52.233   287   287 E SMD     : DCD OFF
,07-05 12:22:55.243   287   287 E SMD     : DCD OFF
,07-05 12:22:57.423  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:22:58.243   287   287 E SMD     : DCD OFF
,07-05 12:23:01.243   287   287 E SMD     : DCD OFF
,07-05 12:23:01.553  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 12:23:01.553  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 12:23:01.553  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 12:23:02.083  1015  3411 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 12:23:03.433  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 12:23:03.433  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 12:23:03.443  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:23:03.453  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 12:23:04.243   287   287 E SMD     : DCD OFF
,07-05 12:23:04.563  1015  1311 E Watchdog: !@Sync 50
,07-05 12:23:07.243   287   287 E SMD     : DCD OFF
,07-05 12:23:07.433  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:23:10.243   287   287 E SMD     : DCD OFF
,07-05 12:23:12.143  1015  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:13.243   287   287 E SMD     : DCD OFF
,07-05 12:23:16.243   287   287 E SMD     : DCD OFF
,07-05 12:23:17.483  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:23:19.253   287   287 E SMD     : DCD OFF,
,07-05 12:23:22.213  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:22.253   287   287 E SMD     : DCD OFF,
,07-05 12:23:25.253   287   287 E SMD     : DCD OFF
,07-05 12:23:27.493  1015  2885 D SSRM:n  : SIOP:: AP = 290
,07-05 12:23:28.253   287   287 E SMD     : DCD OFF
,07-05 12:23:31.253   287   287 E SMD     : DCD OFF
,07-05 12:23:32.273  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 12:23:34.253   287   287 E SMD     : DCD OFF
,07-05 12:23:34.563  1015  1311 E Watchdog: !@Sync 51
,TIME-OUT KILL (timeout was 1401000ms),07-05 12:23:37.253   287   287 E SMD     : DCD OFF
07-05 12:23:37.543  1015  2885 D SSRM:n  : SIOP:: AP = 290
07-05 12:23:37.743  7375  7375 D AndroidRuntime: 
07-05 12:23:37.743  7375  7375 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 12:23:37.743  7375  7375 D AndroidRuntime: CheckJNI is OFF
07-05 12:23:37.743  7375  7375 D AndroidRuntime: readGMSProperty: start
07-05 12:23:37.743  7375  7375 D AndroidRuntime: readGMSProperty: already setted!!
07-05 12:23:37.743  7375  7375 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 12:23:37.743  7375  7375 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 12:23:37.743  7375  7375 D AndroidRuntime: readGMSProperty: end
07-05 12:23:37.743  7375  7375 D AndroidRuntime: addProductProperty: start
07-05 12:23:37.883  7375  7375 E AffinityControl: AffinityControl: registerfunction enter
07-05 12:23:37.913  7375  7375 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 12:23:37.923  1015  3410 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 12:23:37.923  1015  3410 D PackageManager: START PACKAGE DELETE: observer{48038319}
07-05 12:23:37.923  1015  3410 D PackageManager: pkg{<packageName>}
07-05 12:23:37.923  1015  3410 D PackageManager: user{0}
07-05 12:23:37.923  1015  3410 D PackageManager: caller{2000}
07-05 12:23:37.923  1015  3410 D PackageManager: flags{2}
07-05 12:23:37.923  1015  3410 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 12:23:37.923  1015  3410 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 12:23:37.923  1015  3410 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 12:23:37.923  1015  3410 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 12:23:37.923  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 12:23:37.923  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 12:23:37.923  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 12:23:37.923  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 12:23:37.923  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 12:23:37.923  1015  1055 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
07-05 12:23:37.933  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
07-05 12:23:37.933  1015  1040 I ActivityManager: Killing 6746:com.test.thalitest/u0a151 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 12:23:37.933  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{1203a882 u0 com.test.thalitest/.MainActivity t81}
07-05 12:23:37.943  1015  1040 D InputDispatcher: Focus left window: 6746
07-05 12:23:37.943   257  1160 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 12:23:37.943   257   447 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 12:23:37.943  1015  1040 D InputDispatcher: Focused application released
07-05 12:23:37.943  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 12:23:37.943  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 12:23:38.073  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
07-05 12:23:38.083  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
07-05 12:23:38.103  6106  6106 I art     : Explicit concurrent mark sweep GC freed 986(83KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 4MB/6MB, paused 740us total 25.995ms
07-05 12:23:38.103  6559  6559 I art     : Explicit concurrent mark sweep GC freed 18961(1024KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 804us total 28.015ms
07-05 12:23:38.103  6157  6157 I art     : Explicit concurrent mark sweep GC freed 61(14KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 955us total 33.906ms
07-05 12:23:38.113  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 12:23:38.123  1015  1015 D RCPManagerService: PackageReceiver onReceive()
07-05 12:23:38.123  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 12:23:38.123  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 12:23:38.123  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-05 12:23:38.123  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
07-05 12:23:38.133  1769  1966 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 12:23:38.133  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
07-05 12:23:38.133  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-05 12:23:38.133  1825  1825 E SamsungIME: mOCRHelper is null
07-05 12:23:38.143  4151  4151 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 05 12:23:38 GMT+02:00 2016
07-05 12:23:38.143  1015  3410 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-05 12:23:38.143  1015  3410 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
07-05 12:23:38.143  1015  3410 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.153  1015  3410 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:23:38.153  1015  3410 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
07-05 12:23:38.163  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10151]
07-05 12:23:38.163  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:38.163  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
07-05 12:23:38.163  4151  4151 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
07-05 12:23:38.163  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
07-05 12:23:38.173  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
07-05 12:23:38.173  4151  4151 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
07-05 12:23:38.173  1015  3411 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-05 12:23:38.173  1015  3411 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-05 12:23:38.173  1015  1121 V NetworkStats: performPollLocked() took 13ms
07-05 12:23:38.183  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:38.183  1449  1449 D PersonaManager: isKioskContainerExistOnDevice
07-05 12:23:38.183  4151  4151 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 12:23:38.183  1015  3411 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 12:23:38.183  1015  3411 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.183  1015  3411 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.183  4151  4151 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-05 12:23:38.183  1015  3411 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.183  1015  3411 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.193  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-05 12:23:38.203  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
07-05 12:23:38.203  7387  7387 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.203  7387  7387 E Zygote  : v2
07-05 12:23:38.203  7387  7387 I libpersona: KNOX_SDCARD checking this for 10090
07-05 12:23:38.203  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-05 12:23:38.203  7387  7387 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.213  1015  3411 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7387 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
07-05 12:23:38.213  7387  7387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.213  7387  7387 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.213  7387  7387 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:38.213  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-05 12:23:38.233  1449  1449 D RegisteredServicesCache: empty dynamic service
07-05 12:23:38.233  7387  7387 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.243  7387  7387 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.253  1449  1449 D RegisteredComponentCache: Collect Tech packages for Knox
07-05 12:23:38.253  1449  1449 D PersonaManager: isKioskContainerExistOnDevice
07-05 12:23:38.253  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 12:23:38.253  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicy: uID is 10151
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 12:23:38.253  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 12:23:38.273  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 12:23:38.273  1015  1015 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
07-05 12:23:38.273  1015  1161 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
07-05 12:23:38.273  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 12:23:38.273  1015  1027 D SecContentProvider2: mCursor = null
07-05 12:23:38.273  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 12:23:38.283  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.283  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.283  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.283  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.293  1015  1040 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7402 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:23:38.293  7402  7402 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.293  7402  7402 I libpersona: KNOX_SDCARD checking this for 10032
07-05 12:23:38.293  7402  7402 E Zygote  : v2
07-05 12:23:38.293  7402  7402 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.303  7402  7402 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.303  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
07-05 12:23:38.303  7402  7402 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.303  7402  7402 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 12:23:38.313  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.313  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.313  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.313  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.313  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicy: uID is 10151
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 12:23:38.323  1015  2885 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-05 12:23:38.323  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 12:23:38.333  7411  7411 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.333  7411  7411 E Zygote  : v2
07-05 12:23:38.333  7411  7411 I libpersona: KNOX_SDCARD checking this for 10052
07-05 12:23:38.333  7411  7411 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.333  7411  7411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.333  1015  1040 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7411 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
07-05 12:23:38.333  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
07-05 12:23:38.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.343  7387  7387 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 12:23:38.343  7411  7411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.353  7387  7387 D elm:15121: ELMEngine.ELMEngine( context ).
07-05 12:23:38.353  7411  7411 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-05 12:23:38.353  7387  7387 D elm:15121: MDMBridge.setEnterpriseBridge()
07-05 12:23:38.353  7402  7402 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.363  7402  7402 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.363  4151  7385 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 12:23:38.363  1015  1040 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7426 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-05 12:23:38.363  7426  7426 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.363  7426  7426 E Zygote  : v2
07-05 12:23:38.363  7426  7426 I libpersona: KNOX_SDCARD checking this for 10098
07-05 12:23:38.363  7426  7426 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.363  7426  7426 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.363  4151  7385 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
07-05 12:23:38.363  7426  7426 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.373  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:38.373  1015  1256 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 12:23:38.373  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 12:23:38.373  1015  1256 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-05 12:23:38.373  7426  7426 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:38.373  1015  1256 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.373  1015  1256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 12:23:38.373  1015  1256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
07-05 12:23:38.373  4151  4151 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
07-05 12:23:38.373  7387  7387 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 12:23:38.393  7387  7387 D elm:15121: ElmAgentService : onCreate()
07-05 12:23:38.393  7387  7435 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 12:23:38.393  7387  7435 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-05 12:23:38.393  7387  7435 D elm:15121: MDMBridge.getInstance()
07-05 12:23:38.393  3599  3599 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 12:23:38.393  7387  7435 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
07-05 12:23:38.393  7387  7435 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
07-05 12:23:38.393  7411  7411 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.403  7411  7411 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.403  3599  3599 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 12:23:38.403  3599  3599 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-05 12:23:38.403  3599  3599 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 12:23:38.403  3599  3599 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 12:23:38.403  3599  3599 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:23:38.403  3599  3599 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:23:38.403  3599  3599 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 12:23:38.403  3599  3599 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 12:23:38.423  7426  7426 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.423  7426  7426 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.433  7387  7387 D elm:15121: ElmAgentService : onDestroy().
07-05 12:23:38.433  1661  1661 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 12:23:38.433  1661  1661 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 12:23:38.433  1015  1055 I art     : Explicit concurrent mark sweep GC freed 25221(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 3.190ms total 289.660ms
07-05 12:23:38.443  1015  1529 I ActivityManager: Killing 5772:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
07-05 12:23:38.453  1015  1055 D PackageManager: delete codoeFile: 
07-05 12:23:38.473  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
07-05 12:23:38.473  1015  1055 I AASA_removePackage: UID=10151 Target=com.test.thalitest
07-05 12:23:38.473  7402  7450 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 12:23:38.473  7402  7450 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 12:23:38.483  1015  1055 D PackageManager: result of delete: 1{48038319}
07-05 12:23:38.483  1015  1268 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
07-05 12:23:38.483  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.483  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.483  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.483  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.493  7375  7375 D AndroidRuntime: Shutting down VM
07-05 12:23:38.493  7402  7450 D SPPClientService: PushLog.txt file is not deleted.
07-05 12:23:38.493  7402  7450 D SPPClientService: PushLog.txt file is not deleted.
07-05 12:23:38.493  7402  7450 D SPPClientService: ============PushLog. stop!
07-05 12:23:38.503  7452  7452 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.503  7452  7452 E Zygote  : v2
07-05 12:23:38.503  7452  7452 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:23:38.503  7452  7452 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.503  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.503  1015  1268 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7452 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 12:23:38.503  1015  1268 I ActivityManager: Killing 6386:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
07-05 12:23:38.503  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.503  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:38.503  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-05 12:23:38.503  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
07-05 12:23:38.513  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.513  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 12:23:38.513  1015  1055 D PackageManager: userId{-1}
07-05 12:23:38.513  1015  1055 D PackageManager: andCode{true}
07-05 12:23:38.513  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.513  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.523  1015  1268 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 12:23:38.533  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.533  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.533  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.533  1015  1268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.533  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.533  7452  7452 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.553  3424  7467 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 12:23:38.553  7470  7470 I libpersona: KNOX_SDCARD checking this for 10032
07-05 12:23:38.553  7470  7470 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.553  7470  7470 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.553  7470  7470 E Zygote  : v2
07-05 12:23:38.553  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.553  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.553  3424  7467 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 12:23:38.553  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 12:23:38.563  1015  1268 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7470 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 12:23:38.563  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-05 12:23:38.573  3424  3424 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-05 12:23:38.573  3424  3424 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-05 12:23:38.573  3424  3424 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:23:38.583  3424  3424 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:23:38.583  1015  1529 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 12:23:38.583  1015  1529 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.583  1015  1529 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.583  1015  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.593  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.593  7470  7470 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.593  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 12:23:38.603  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.603  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.603  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.603  1015  1529 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:38.603  1015  1529 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
07-05 12:23:38.603  1015  1529 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.603  1015  1529 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.603  1015  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.603  3424  3424 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-05 12:23:38.603  3424  3424 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-05 12:23:38.603  3424  3424 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 12:23:38.603  3424  3424 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 12:23:38.613  1015  3343 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-05 12:23:38.613  1015  3343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-05 12:23:38.613  1015  3343 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.613  1015  3343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.613  1015  3343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-05 12:23:38.623  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-05 12:23:38.623  3424  7467 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 12:23:38.623  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.623  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.623  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.623  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.633  7491  7491 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.633  7491  7491 I libpersona: KNOX_SDCARD checking this for 10055
07-05 12:23:38.633  7491  7491 E Zygote  : v2
07-05 12:23:38.633  7491  7491 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.633  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.643  1015  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7491 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
07-05 12:23:38.643  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.643  1015  3410 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 12:23:38.643  1015  3410 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
07-05 12:23:38.643  1015  3410 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.643  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:38.643  1015  3410 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.643  1015  3410 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.643  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 12:23:38.653  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.653  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.653  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.653  1015  1479 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-05 12:23:38.663  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.663  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.663  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.663  1015  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.673  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.673  7491  7491 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.673  7506  7506 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.673  7506  7506 E Zygote  : v2
07-05 12:23:38.673  7506  7506 I libpersona: KNOX_SDCARD checking this for 1000
07-05 12:23:38.673  7506  7506 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.683  7506  7506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.683  7506  7506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.683  1015  1479 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7506 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 12:23:38.683  7506  7506 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 12:23:38.683  1015  1479 I ActivityManager: Killing 6404:com.google.android.partnersetup/u0a14 (adj 15): empty #21
07-05 12:23:38.683  3424  7490 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 12:23:38.683  3424  7490 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 12:23:38.683  3424  7490 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 12:23:38.683  3424  7490 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 12:23:38.693  1015  3343 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 12:23:38.693  1015  3343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
07-05 12:23:38.693  7375  7375 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-05 12:23:38.703  1015  3343 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.703  1015  3343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.703  1015  3343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.703  1015  3343 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.703  1015  3343 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.703  1015  3343 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.703  1015  3343 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 12:23:38.713  7411  7488 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 12:23:38.713  3424  7490 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 12:23:38.713  3424  7490 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 12:23:38.713  3424  7490 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 12:23:38.713   304   304 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 35.175ms
07-05 12:23:38.733  7506  7506 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 12:23:38.733  7506  7506 D ActivityThread: Added TimaKeyStore provider
07-05 12:23:38.733  3424  7490 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 12:23:38.733  3424  7490 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 12:23:38.733   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.772ms
07-05 12:23:38.733  3424  7490 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 12:23:38.753   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.433ms
07-05 12:23:38.763  7523  7523 E Zygote  : MountEmulatedStorage()
07-05 12:23:38.763  7523  7523 I libpersona: KNOX_SDCARD checking this for 10011
07-05 12:23:38.763  7523  7523 E Zygote  : v2
07-05 12:23:38.763  7523  7523 I libpersona: KNOX_SDCARD not a persona
07-05 12:23:38.773  1015  3343 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7523 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
07-05 12:23:38.773  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 12:23:38.773  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
07-05 12:23:38.773  7523  7523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 12:23:38.773  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 12:23:38.773  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 12:23:38.773  7523  7523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 12:23:38.773  7523  7523 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL

```
