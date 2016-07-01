#### Test 757892680c366d1_thali01_samsung-SM-A300FU Logs


```
--------- beginning of system
07-01 12:08:22.328  1014  2864 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
07-01 12:08:22.988  6861  6861 D AndroidRuntime: 
07-01 12:08:22.988  6861  6861 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:08:22.998  6861  6861 D AndroidRuntime: CheckJNI is OFF
07-01 12:08:22.998  6861  6861 D AndroidRuntime: readGMSProperty: start
07-01 12:08:22.998  6861  6861 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:08:22.998  6861  6861 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 12:08:22.998  6861  6861 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 12:08:22.998  6861  6861 D AndroidRuntime: readGMSProperty: end
07-01 12:08:22.998  6861  6861 D AndroidRuntime: addProductProperty: start
07-01 12:08:23.128  6861  6861 E AffinityControl: AffinityControl: registerfunction enter
07-01 12:08:23.148  6861  6861 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 12:08:23.158  1014  1319 E PersonaManagerService: inState():  stateMachine is null !!
07-01 12:08:23.158  1014  1319 I PersonaManagerService: PersonaId don't exist
07-01 12:08:23.158  1014  1319 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 12:08:23.158  1014  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:23.178  1014  1319 W ActivityManager: mDVFSHelper.acquire()
07-01 12:08:23.178  1014  1319 D FocusedStackFrame: Set to : 0
07-01 12:08:23.188  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-01 12:08:23.188  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:23.188  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:23.188  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:23.188  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:23.188  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-01 12:08:23.198  6872  6872 E Zygote  : MountEmulatedStorage()
07-01 12:08:23.198  6872  6872 E Zygote  : v2
07-01 12:08:23.198  6872  6872 I libpersona: KNOX_SDCARD checking this for 10151
07-01 12:08:23.198  6872  6872 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:23.198  1014  1319 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6872 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:08:23.198  1014  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 12:08:23.198  1014  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:23.198  1014  1319 D InputDispatcher: Focused application set to: xxxx
07-01 12:08:23.198  1014  1319 D InputDispatcher: Focus left window: 1502
07-01 12:08:23.198  6872  6872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:23.198  6861  6861 D AndroidRuntime: Shutting down VM
07-01 12:08:23.208  6872  6872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:23.208  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-01 12:08:23.208  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-01 12:08:23.208  6872  6872 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 12:08:23.208   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-01 12:08:23.228  6872  6872 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:23.228  6872  6872 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:23.228  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:23.228  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:23.228  1014  1539 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-01 12:08:23.238  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 12:08:23.248  1014  1539 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:08:23.268  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-01 12:08:23.288   257   448 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-01 12:08:23.298   257  1094 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-01 12:08:23.298  1502  1502 V ActivityThread: updateVisibility : ActivityRecord{187220b8 token=android.os.BinderProxy@3f8c35bd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 12:08:23.298  1502  1502 D Launcher: onTrimMemory. Level: 20
07-01 12:08:23.378  6872  6872 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 12:08:23.388  6872  6872 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6292-6293)
07-01 12:08:23.388  6872  6872 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:23.408  6861  6861 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-01 12:08:23.418  6872  6872 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c5aca09}
,07-01 12:08:23.418  6872  6872 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:23.418  6872  6872 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 12:08:23.428  1014  1539 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:08:23.428  1014  1539 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,07-01 12:08:23.428  1014  1539 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-01 12:08:23.428  1014  1539 D BatteryService: stay LED for fully charged
07-01 12:08:23.428  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:08:23.438  1014  1014 I MotionRecognitionService: Plugged
07-01 12:08:23.438  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-01 12:08:23.438  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:08:23.438  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:08:23.438  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-01 12:08:23.438  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-01 12:08:23.448  2766  2766 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:08:23.448  2766  2877 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:08:23.458  6872  6872 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 12:08:23.458  6872  6872 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:23.458  6872  6872 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 12:08:23.458  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:08:23.458  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:08:23.458  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:08:23.478  6872  6872 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 12:08:23.478  6872  6872 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-01 12:08:23.478  6872  6872 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-01 12:08:23.488  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,07-01 12:08:23.488  6872  6872 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-01 12:08:23.488  6872  6872 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-01 12:08:23.488  6872  6872 I Adreno-EGL: Build Date: 04/06/15 Mon
07-01 12:08:23.488  6872  6872 I Adreno-EGL: Local Branch: 
07-01 12:08:23.488  6872  6872 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-01 12:08:23.488  6872  6872 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-01 12:08:23.488  6872  6872 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-01 12:08:23.518  1014  2847 D SSRM:n  : SIOP:: AP = 310
,07-01 12:08:23.628  6872  6900 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-01 12:08:23.678  6872  6872 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:23.688  6872  6872 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 12:08:23.698  6872  6872 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-01 12:08:23.698  6872  6872 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-01 12:08:23.708  6872  6872 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-01 12:08:23.708  6872  6872 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:23.708  6872  6872 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:08:23.728   291   291 E SMD     : DCD OFF,
,07-01 12:08:23.758  1014  1039 W ActivityManager: Activity pause timeout for ActivityRecord{1fe67620 u0 com.test.thalitest/.MainActivity t81}
,07-01 12:08:23.778  6872  6913 D OpenGLRenderer: Render dirty regions requested: true
,07-01 12:08:23.778  1014  1494 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-01 12:08:23.778  1014  1494 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 12:08:23.778  1014  1494 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-01 12:08:23.778  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 12:08:23.778  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,07-01 12:08:23.788  6872  6872 V ActivityThread: updateVisibility : ActivityRecord{28e90358 token=android.os.BinderProxy@21c7a6ca {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-01 12:08:23.798  6872  6872 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-01 12:08:23.798  6872  6872 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-01 12:08:23.798   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,07-01 12:08:23.818  1014  1539 D InputDispatcher: Focus entered window: 6872
,07-01 12:08:23.828  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-01 12:08:23.828  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:23.828  6872  6872 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-01 12:08:23.828  6872  6913 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 12:08:23.828  6872  6913 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-01 12:08:23.828  6872  6913 D OpenGLRenderer: Enabling debug mode 0
,07-01 12:08:23.858  1014  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-01 12:08:23.868  1177  1177 I StatusBar: Icon Only
,07-01 12:08:23.868  1177  1177 D PanelView: There is/are notification(s) 
,07-01 12:08:23.868  1014  6916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:08:23.878  1014  1044 I ActivityManager: Displayed Component not be shown by security: +625ms (total +28s395ms)
,07-01 12:08:23.878  1014  1044 W ActivityManager: mDVFSHelper.release()
07-01 12:08:23.878  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1fe67620 u0 com.test.thalitest/.MainActivity t81} time:136787
,07-01 12:08:23.888  6872  6872 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-01 12:08:23.888  6872  6872 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21c7a6ca time:136794
,07-01 12:08:23.888   257  1901 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,07-01 12:08:23.888   257   448 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,07-01 12:08:23.958  1831  1831 I SamsungIME: getCurrentCandidateView
,07-01 12:08:23.968  6872  6872 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6872
,07-01 12:08:24.048  1831  1831 D SamsungIME: Dismiss ExpandCandiate
,07-01 12:08:24.088  6872  6872 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 12:08:24.198  1831  1831 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 12:08:24.208  6872  6918 D jxcore_app_log: JniHelper::setJavaVM(0xb80cd2f0), pthread_self() = -1201503136
,07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 12:08:24.218  6872  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cff288 added. We now have 1 listener(s)
,07-01 12:08:24.218  6872  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-01 12:08:24.218  6872  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-01 12:08:24.218  6872  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 12:08:24.218  6872  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:08:24.228  6872  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e8207 added. We now have 1 listener(s)
,07-01 12:08:24.228  6872  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:08:24.238  6872  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 12:08:24.238  6872  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,07-01 12:08:24.248  1831  1831 I SamsungIME: getDebugLevel  : 0x4f4c
,07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:1a:ce:70
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:08:24.248  6872  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:08:24.248  6872  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:08:24.248  6872  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 12:08:24.248  6872  6918 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 12:08:24.248  6872  6872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:24.258  6872  6872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:08:24.258  1831  1831 I SamsungIME: KeybaordView init() : load resources
,07-01 12:08:24.278  6872  6872 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 12:08:24.288  1831  1831 I SamsungIME: getCurrentKeyboard
,07-01 12:08:24.288  1831  1831 I SamsungIME: getTextKeyboard
,07-01 12:08:24.308  1831  1831 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-01 12:08:24.528  1014  1318 E Watchdog: !@Sync 4,
,07-01 12:08:24.888  6872  6923 W jxcore-log: Initializing JXcore engine
07-01 12:08:24.888  6872  6923 W jxcore-log: JXcore engine is ready
,07-01 12:08:24.938  1925  1925 E audit   : type=1400 msg=audit(1467367704.938:205): avc:  denied  { ioctl } for  pid=6923 comm="Thread-1278" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 12:08:24.938  1925  1925 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:24.938  1925  1925 E audit   : type=1300 msg=audit(1467367704.938:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9ee008f8 items=0 ppid=311 ppcomm=main pid=6923 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1278" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-01 12:08:24.948  1925  1925 E audit   : type=1320 msg=audit(1467367704.938:205): 
,07-01 12:08:24.948  6872  6923 W jxcore-log: Starting JXcore engine,
,07-01 12:08:25.058  6872  6923 W jxcore-log: Platform android,
07-01 12:08:25.058  6872  6923 W jxcore-log: 
07-01 12:08:25.058  6872  6923 W jxcore-log: Process ARCH arm
07-01 12:08:25.058  6872  6923 W jxcore-log: 
,07-01 12:08:25.258  6872  6923 I jxcore-log: JXcore Cordova bridge is ready!
07-01 12:08:25.258  6872  6923 I jxcore-log: 
,07-01 12:08:25.258  6872  6923 W jxcore-log: JXcore engine is started
,07-01 12:08:25.258  6872  6918 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 12:08:25.258  6872  6872 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 12:08:25.268  6872  6923 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-01 12:08:25.268  6872  6923 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 12:08:25.278  6872  6872 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-01 12:08:25.278  6872  6872 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 12:08:25.278  1014  1539 D FocusedStackFrame: Set to : 0
07-01 12:08:25.278  1014  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:25.278  1014  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-01 12:08:25.278  1014  1539 D InputDispatcher: Focused application set to: xxxx
07-01 12:08:25.278  1014  1539 D InputDispatcher: Focus left window: 6872
07-01 12:08:25.288  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:25.288  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:25.288  1014  1539 I ActivityManager: Killing 6345:com.samsung.android.sm/1000 (adj 15): empty #21
07-01 12:08:25.288  6872  6872 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 12:08:25.298  6872  6872 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-01 12:08:25.298  6872  6872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-01 12:08:25.298  6872  6872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:08:25.298  6872  6872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:25.298  6872  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 12:08:25.298  6872  6872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cff288 removed from the list
07-01 12:08:25.298  6872  6872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:25.298  6872  6872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8e8207 removed from the list
07-01 12:08:25.298  6872  6872 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:25.298  6872  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-01 12:08:25.298  6872  6872 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 12:08:25.308   257   455 I SurfaceFlinger: id=14 Removed NainActivit (6/8),
07-01 12:08:25.308   257   448 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,07-01 12:08:25.308  1014  1320 W ActivityManager: mDVFSHelper.acquire()
,07-01 12:08:25.318  1014  1320 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-01 12:08:25.338  1502  1502 D Launcher: onRestart, Launcher: 1021115845
,07-01 12:08:25.338  1502  1502 D Launcher: onStart, Launcher: 1021115845
,07-01 12:08:25.338  1502  1502 D Launcher.HomeView: onStart
,07-01 12:08:25.338  1502  1502 D Launcher: onResume, Launcher: 1021115845
,07-01 12:08:25.338  1014  1494 D SettingsProvider: name = kids_home_mode
,07-01 12:08:25.338  1014  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 12:08:25.338  1014  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:08:25.338  1014  1494 D SettingsProvider: selectionArgs: false
,07-01 12:08:25.338  1014  1494 D SettingsProvider: selectionArgs: 10006
07-01 12:08:25.338  1014  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:08:25.338  1014  1494 D SettingsProvider: ret = -1
,07-01 12:08:25.348  1502  1502 D Launcher.HomeView: onResume
,07-01 12:08:25.348  1502  1502 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-01 12:08:25.348  1502  1502 D MenuAppsGridFragment: onResume,
,07-01 12:08:25.358  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.358  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.358  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-01 12:08:25.358  1502  1502 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-01 12:08:25.358  1502  1502 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-01 12:08:25.358  1014  1026 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-01 12:08:25.358  1014  1026 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-01 12:08:25.368  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:25.368  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 12:08:25.368  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-01 12:08:25.368  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-01 12:08:25.368  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.368  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.368  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.368  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.398  6930  6930 E Zygote  : MountEmulatedStorage()
,07-01 12:08:25.398  6930  6930 E Zygote  : v2
07-01 12:08:25.398  6930  6930 I libpersona: KNOX_SDCARD checking this for 10039
07-01 12:08:25.398  6930  6930 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.398  1014  1026 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6930 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-01 12:08:25.398  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.408  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-01 12:08:25.408  1014  1320 D ActivityManager: handle home activity for 0
07-01 12:08:25.408  1014  1320 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-01 12:08:25.408  1014  1320 D KnoxTimeoutHandler: post home show event for user 0
07-01 12:08:25.408  1014  1320 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 12:08:25.408  1014  1320 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 12:08:25.408  1014  1320 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 12:08:25.408  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:08:25.408  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-01 12:08:25.408  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-01 12:08:25.408  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-01 12:08:25.408  1502  1502 D Launcher.HomeView: onPause
07-01 12:08:25.408  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-01 12:08:25.408  1502  1502 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-01 12:08:25.408  1014  1039 W ActivityManager: userId = 0, bbcId = -10000,
07-01 12:08:25.408  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.408  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings,
,07-01 12:08:25.418  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.418  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-01 12:08:25.418  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.418  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,07-01 12:08:25.418  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 12:08:25.418  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.418  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.418  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,07-01 12:08:25.428  6945  6945 E Zygote  : MountEmulatedStorage()
,07-01 12:08:25.428  6945  6945 E Zygote  : v2
07-01 12:08:25.428  6945  6945 I libpersona: KNOX_SDCARD checking this for 10089
07-01 12:08:25.428  6945  6945 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.428  1014  1039 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6945 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-01 12:08:25.438  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.438  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:25.438  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:25.438  6930  6930 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:25.438  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 12:08:25.438  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.438  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.438  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-01 12:08:25.438  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
,07-01 12:08:25.438  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.438  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.438  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.438  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,07-01 12:08:25.458  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-01 12:08:25.458  6945  6945 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.458  6959  6959 E Zygote  : MountEmulatedStorage()
,07-01 12:08:25.458  6959  6959 E Zygote  : v2
07-01 12:08:25.458  6959  6959 I libpersona: KNOX_SDCARD checking this for 10139
07-01 12:08:25.458  6959  6959 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:25.468  6959  6959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.468  6959  6959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:25.468  6959  6959 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-01 12:08:25.468  1014  1039 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6959 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,07-01 12:08:25.488   311   311 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 19.913ms
,07-01 12:08:25.488  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.488  1014  1539 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1502, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-01 12:08:25.488  1014  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.488  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-01 12:08:25.498  6959  6959 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.498   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,07-01 12:08:25.508  6959  6959 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.508  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-01 12:08:25.508  1014  1039 W ActivityManager: userId = 0, bbcId = -10000,
07-01 12:08:25.508  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.508  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui,
,07-01 12:08:25.518  2602  2602 D Recents_RecreateReceiver: onReceive by home
,07-01 12:08:25.518   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.922ms
,07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-01 12:08:25.518  6930  6930 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 12:08:25.518  1014  1540 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.518  1014  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.518  1014  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-01 12:08:25.518  1014  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-01 12:08:25.528  6945  6945 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:08:25.528  6945  6945 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-01 12:08:25.538  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-01 12:08:25.538  1014  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.538  1014  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.538  1014  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 12:08:25.538   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.601ms
07-01 12:08:25.538  1014  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.538  1014  1319 D InputDispatcher: Focus entered window: 1502
,07-01 12:08:25.538  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-01 12:08:25.538  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
07-01 12:08:25.538  1502  1502 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-01 12:08:25.558  6976  6976 E Zygote  : MountEmulatedStorage()
07-01 12:08:25.558  6976  6976 I libpersona: KNOX_SDCARD checking this for 10084
07-01 12:08:25.558  6976  6976 E Zygote  : v2
07-01 12:08:25.558  6976  6976 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.558  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:25.558  1014  1540 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6976 uid=10084 gids={50084, 9997} abi=armeabi-v7a
07-01 12:08:25.558  6925  6925 D AndroidRuntime: 
07-01 12:08:25.558  6925  6925 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:08:25.558  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:25.558  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-01 12:08:25.558  6925  6925 D AndroidRuntime: CheckJNI is OFF
07-01 12:08:25.558  6925  6925 D AndroidRuntime: readGMSProperty: start
07-01 12:08:25.558  6925  6925 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:08:25.558  6925  6925 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-01 12:08:25.558  6925  6925 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-01 12:08:25.558  6925  6925 D AndroidRuntime: readGMSProperty: end
07-01 12:08:25.558  6925  6925 D AndroidRuntime: addProductProperty: start
07-01 12:08:25.568  1502  1502 D Launcher.HomeView: onStop
07-01 12:08:25.568  1502  1502 V ActivityThread: updateVisibility : ActivityRecord{187220b8 token=android.os.BinderProxy@3f8c35bd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-01 12:08:25.568  1014  1320 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-01 12:08:25.568  1177  1177 I StatusBar: Icon Only
07-01 12:08:25.568  1177  1177 D PanelView: There is/are notification(s) 
07-01 12:08:25.578  6872  6872 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-01 12:08:25.578  1831  1831 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
07-01 12:08:25.578  1014  6984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-01 12:08:25.578  6959  6959 V TaskCloserActivity: TaskCloserActivity enter()
07-01 12:08:25.588  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.588  6976  6976 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:25.588  6959  6959 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
07-01 12:08:25.598  1014  1540 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.608  1014  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.608  1014  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-01 12:08:25.608  1502  1502 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f8c35bd time:138513
07-01 12:08:25.608  1014  1540 I ActivityManager: Killing 6514:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,07-01 12:08:25.618  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:25.618  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-01 12:08:25.618  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:25.618  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-01 12:08:25.618  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.618  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.618  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:25.618  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:25.638  7001  7001 E Zygote  : MountEmulatedStorage()
,07-01 12:08:25.638  7001  7001 E Zygote  : v2
07-01 12:08:25.638  7001  7001 I libpersona: KNOX_SDCARD checking this for 10135
07-01 12:08:25.638  7001  7001 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:25.638  7001  7001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:25.638  7001  7001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:25.638  1014  1027 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7001 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,07-01 12:08:25.638  7001  7001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:08:25.638  1014  1027 I ActivityManager: Killing 6562:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
07-01 12:08:25.638  6976  6976 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:25.648  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-01 12:08:25.648  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f0d8344 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t79} time:138559
07-01 12:08:25.648  1014  1044 W ActivityManager: mDVFSHelper.release()
,07-01 12:08:25.668  1014  1319 I ActivityManager: Killing 6587:com.sec.pcw.device/1000 (adj 15): empty #21
,07-01 12:08:25.678  7001  7001 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:25.678  7001  7001 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:25.708  1014  1541 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:08:25.708  7001  7001 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-01 12:08:25.708  7001  7001 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-01 12:08:25.708  7001  7001 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-01 12:08:25.708  7001  7001 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-01 12:08:25.708  7001  7001 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-01 12:08:25.708  6925  6925 E AffinityControl: AffinityControl: registerfunction enter
,07-01 12:08:25.718   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,07-01 12:08:25.728  1014  1539 I ActivityManager: Killing 6192:com.android.mms/u0a41 (adj 15): empty #21
,07-01 12:08:25.738  6925  6925 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-01 12:08:25.748  6930  6930 D NearbySource: Nearby Source Create!
07-01 12:08:25.748  6930  6930 D NearbyContext: Nearby Context Create!
07-01 12:08:25.758  1014  1511 D PackageManager: START PACKAGE DELETE: observer{213294323}
07-01 12:08:25.758  1014  1511 D PackageManager: pkg{<packageName>}
07-01 12:08:25.758  1014  1511 D PackageManager: user{0}
07-01 12:08:25.758  1014  1511 D PackageManager: caller{2000}
07-01 12:08:25.758  1014  1511 D PackageManager: flags{2}
07-01 12:08:25.758  1014  1511 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-01 12:08:25.758  1014  1511 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 12:08:25.758  1014  1511 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-01 12:08:25.758  1014  1511 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:08:25.758  1014  1511 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:08:25.758  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 12:08:25.758  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-01 12:08:25.758  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-01 12:08:25.758  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 12:08:25.758  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-01 12:08:25.758  1014  1054 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
07-01 12:08:25.768  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
07-01 12:08:25.768  1014  1039 I ActivityManager: Killing 6872:com.test.thalitest/u0a151 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-01 12:08:25.788  1014  1319 D CountryDetector: No listener is left
,07-01 12:08:25.788   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-01 12:08:25.788   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:08:25.788  6930  6930 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-01 12:08:25.788  6930  6930 D SLinkSource: Samsung link source created
,07-01 12:08:25.898  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,07-01 12:08:25.928  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-01 12:08:25.958  5908  5908 I art     : Explicit concurrent mark sweep GC freed 21317(1157KB) AllocSpace objects, 2(32KB) LOS objects, 49% free, 4MB/8MB, paused 1.220ms total 48.618ms
,07-01 12:08:25.968  6465  6465 I art     : Explicit concurrent mark sweep GC freed 588(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 883us total 56.636ms
,07-01 12:08:25.978  1014  3993 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:08:25.978  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 12:08:25.998  1831  1831 E SamsungIME: mOCRHelper is null
,07-01 12:08:26.008  1731  1860 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 12:08:26.018  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,07-01 12:08:26.028  1014  1120 V NetworkStats: removeUidsLocked() for UIDs [10151]
07-01 12:08:26.028  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:08:26.028  1014  1120 V NetworkStats: performPollLocked(flags=0x3)
,07-01 12:08:26.028  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
07-01 12:08:26.028  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-01 12:08:26.038  1014  1120 V NetworkStats: performPollLocked() took 4ms
07-01 12:08:26.038  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:08:26.038  1462  1462 D RegisteredServicesCache: empty dynamic service
,07-01 12:08:26.038  6930  7020 D ContactProvider: getAllContactInfoList Start
,07-01 12:08:26.048  1462  1462 D RegisteredComponentCache: Collect Tech packages for Knox
,07-01 12:08:26.058  1462  1462 D PersonaManager: isKioskContainerExistOnDevice
,07-01 12:08:26.068  1014  1541 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:08:26.068  6930  6930 D GalleryCacheReady: Receive : home resume
,07-01 12:08:26.078  1014  1511 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.078  1014  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:26.078  1014  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-01 12:08:26.078  1014  1511 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-01 12:08:26.088  1014  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.088  1014  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.088  1014  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.088  1014  1511 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.098  7022  7022 E Zygote  : MountEmulatedStorage(),
,07-01 12:08:26.098  7022  7022 E Zygote  : v2
07-01 12:08:26.098  7022  7022 I libpersona: KNOX_SDCARD checking this for 10041
,07-01 12:08:26.098  7022  7022 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.098  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.108  1014  1511 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7022 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-01 12:08:26.108  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:26.108  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.118  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:08:26.118  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:08:26.118  1014  1131 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-01 12:08:26.118  1014  1131 D SecContentProvider2: mCursor = null
,07-01 12:08:26.128  1014  1014 I art     : Explicit concurrent mark sweep GC freed 52367(3MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 23MB/34MB, paused 4.439ms total 200.319ms
,07-01 12:08:26.128  1014  1131 I art     : WaitForGcToComplete blocked for 6.116ms for cause Explicit
,07-01 12:08:26.148  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.148  7022  7022 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.168  6930  7020 D ContactProvider: getAllContactInfoList End
,07-01 12:08:26.168  6930  7020 I syncContacts: thread: 1263, sync time = 230
,07-01 12:08:26.178  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,07-01 12:08:26.178  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-01 12:08:26.188  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-01 12:08:26.188  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-01 12:08:26.188  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,07-01 12:08:26.188  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
07-01 12:08:26.188  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-01 12:08:26.188  1014  1038 W TextServicesManagerService: no available spell checker services found
,07-01 12:08:26.198  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.198  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,07-01 12:08:26.198  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-01 12:08:26.198  7022  7022 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-01 12:08:26.198  7022  7022 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:26.198  7022  7022 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:08:26.198  7022  7022 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-01 12:08:26.198  7022  7022 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-01 12:08:26.208  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.228  7022  7022 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-01 12:08:26.248  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.258  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.298  1014  1131 I art     : Explicit concurrent mark sweep GC freed 14353(832KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 3.444ms total 162.671ms
,07-01 12:08:26.298  1014  1054 I art     : WaitForGcToComplete blocked for 272.976ms for cause Explicit
,07-01 12:08:26.358  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-01 12:08:26.368  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.368  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.378  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-01 12:08:26.378  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-01 12:08:26.378  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,07-01 12:08:26.378  1014  1014 V EnterpriseBillingPolicy: uID is 10151
07-01 12:08:26.378  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
,07-01 12:08:26.378  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-01 12:08:26.378  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-01 12:08:26.378  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.388  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null,
07-01 12:08:26.388  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 12:08:26.388  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-01 12:08:26.388  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-01 12:08:26.388  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:26.388  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-01 12:08:26.388  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:08:26.388  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-01 12:08:26.388  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.388  7022  7022 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 119.125ms
07-01 12:08:26.388  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
,07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicy: uID is 10151
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-01 12:08:26.398  1014  2847 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-01 12:08:26.398  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-01 12:08:26.398  1014  1014 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
,07-01 12:08:26.418  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.418  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.418  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.418  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.428  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.428  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.428  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.428  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-01 12:08:26.428  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-01 12:08:26.438  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-01 12:08:26.438  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-01 12:08:26.438  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-01 12:08:26.458  1014  1054 I art     : Explicit concurrent mark sweep GC freed 8644(470KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 5.009ms total 160.093ms
,07-01 12:08:26.478  1014  1054 D PackageManager: delete codoeFile: 
,07-01 12:08:26.478  7022  7037 D Mms/ArtClassLoader: init before art
,07-01 12:08:26.488  7022  7022 D Mms/TelephonyPermission: start operation mode monitor
,07-01 12:08:26.488  1014  1054 I AASA_removePackage: UID=10151 Target=com.test.thalitest
07-01 12:08:26.488  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
,07-01 12:08:26.488  1014  1054 D PackageManager: result of delete: 1{213294323}
,07-01 12:08:26.488  6925  6925 D AndroidRuntime: Shutting down VM
,07-01 12:08:26.508  7022  7022 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:08:26.508  7022  7022 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,07-01 12:08:26.508  7022  7022 D Mms/TelephonyPermission: isDefault true
,07-01 12:08:26.508  7022  7022 D Mms/MmsApp: onCreate() com.android.mms
,07-01 12:08:26.538  7022  7022 D Mms/MmsApp: [start]    initCountryIso consume time = 305.03625
,07-01 12:08:26.538  1014  1497 D CountryDetector: The first listener is added
,07-01 12:08:26.548  7022  7022 D Mms/MmsApp: [end]    initCountryIso consume time = 7.204062
07-01 12:08:26.548  7022  7022 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.113802
,07-01 12:08:26.548  7022  7022 D Mms/MmsConfig: before partial update
,07-01 12:08:26.568  7022  7022 D Mms/MmsConfig: Load Resize quality : 80
,07-01 12:08:26.568  7022  7022 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,07-01 12:08:26.568  7022  7022 D EasySignUpManager_1.0.1: isAuth is false
,07-01 12:08:26.568  7022  7022 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,07-01 12:08:26.578  1477  1489 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7022
,07-01 12:08:26.578  1477  1489 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.231 ms
,07-01 12:08:26.578  7022  7022 D EasySignUpManager_1.0.1: isAuth is false
,07-01 12:08:26.578  7022  7022 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,07-01 12:08:26.588  7022  7022 E CscParser: mps_code.dat does not exist
,07-01 12:08:26.588  7022  7022 E CscParser: customer_path =/system/csc/customer.xml
07-01 12:08:26.588  7022  7022 E CscParser: fileName + /system/csc/customer.xml
,07-01 12:08:26.598  7022  7022 E CscParser: mps_code.dat does not exist
07-01 12:08:26.598  7022  7022 E CscParser: customer_path =/system/csc/customer.xml
07-01 12:08:26.598  7022  7022 E CscParser: fileName + /system/csc/customer.xml
,07-01 12:08:26.598  7022  7022 D CscParser: getInstance fileName =/system/csc/customer.xml
,07-01 12:08:26.598  7022  7022 D Mms/MmsConfig:  enable multiwindow = false
,07-01 12:08:26.608  7022  7022 E Mms/MessageUtils: setCountryDetector : update country detector info 
,07-01 12:08:26.608  7022  7022 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-01 12:08:26.618  7022  7022 D Mms/MmsConfig: [end]    init() consume time = 70.271563
,07-01 12:08:26.618  7022  7022 D Mms/Contact: [start]    init() consume time = 1.144218
,07-01 12:08:26.618  1477  1489 D TP/MmsSmsProvider: query,matched:13, calling pid = 7022
,07-01 12:08:26.618  1477  1489 D TP/MmsSmsProvider: match 13:Elapsed time : 1.239 ms
,07-01 12:08:26.628  7022  7022 D Mms/Contact: [end]    init consume time = 13.436094
,07-01 12:08:26.638  7022  7043 D Mms/DraftCache: [start]    rebuildCache consume time = 10.543646
,07-01 12:08:26.638  7022  7022 D Mms/MethodReflector: getSubId is called
07-01 12:08:26.638  7022  7022 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-01 12:08:26.638  1477  4510 D TP/MmsSmsProvider: query,matched:12, calling pid = 7022
,07-01 12:08:26.648  1477  4510 D TP/MmsSmsProvider: match 12:Elapsed time : 1.301 ms
07-01 12:08:26.648  7022  7022 D Mms/MethodReflector: getTelephonyProperty is called
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: auto download without roaming -> true
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-01 12:08:26.648  7022  7022 D Mms/MethodReflector: getSubId is called
07-01 12:08:26.648  7022  7022 D Mms/MethodReflector: getDefaultSmsSubId is called
07-01 12:08:26.648  7022  7022 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-01 12:08:26.648  7022  7022 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-01 12:08:26.648  7022  7022 D Mms/MethodReflector: getTelephonyProperty is called
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: auto download without roaming -> true
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: auto download during roaming secondary -> false
07-01 12:08:26.648  7022  7022 D Mms/DownloadManager: mAutoDownload ------> true
07-01 12:08:26.648  7022  7043 D Mms/DraftCache: [end]    rebuildCache consume time = 9.899323
,07-01 12:08:26.688  7022  7022 D ComposerPerformance: 1467367706697 ms / [DONE] Composer constructor
,07-01 12:08:26.688  7022  7022 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,07-01 12:08:26.688  7022  7022 I Mms/ReservationManager: ReservationManager()
,07-01 12:08:26.688  7022  7022 I Mms/ReservationManager: resetAfterConnected()
,07-01 12:08:26.688  1477  1489 D TP/MmsSmsProvider: query,matched:7, calling pid = 7022
,07-01 12:08:26.688  1477  1489 D TP/MmsSmsProvider: match 7:Elapsed time : 2.104 ms
,07-01 12:08:26.688  7022  7022 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
07-01 12:08:26.698  6925  6925 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-01 12:08:26.698  7022  7044 D Mms/Conversation: [start]    init() consume time = 52.268021
,07-01 12:08:26.708  7022  7022 D Mms/MmsApp: [end]    onCreate() consume time = 2.614427,
07-01 12:08:26.708  7022  7022 D Mms/UIEventReceiver: ui event
,07-01 12:08:26.708  1477  4510 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
07-01 12:08:26.708  1014  1497 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
07-01 12:08:26.708  1477  4510 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
07-01 12:08:26.708  1477  4510 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
07-01 12:08:26.708  1014  1497 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.708  1014  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-01 12:08:26.708  1014  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-01 12:08:26.708  1477  4510 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,07-01 12:08:26.708  7022  7022 D Mms/MethodReflector: getSubId is called
07-01 12:08:26.708  7022  7022 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-01 12:08:26.708  7022  7022 D Mms/MethodReflector: getTelephonyProperty is called
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: auto download without roaming -> true
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-01 12:08:26.708  7022  7022 D Mms/DownloadManager: mAutoDownload ------> true
,07-01 12:08:26.718  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-01 12:08:26.718  1014  1054 D PackageManager: userId{-1}
07-01 12:08:26.718  1014  1054 D PackageManager: andCode{true}
,07-01 12:08:26.718   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:08:26.718  1477  4510 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
07-01 12:08:26.718  1477  4510 D TP/MmsSmsProvider: need read changed broadcast:false
,07-01 12:08:26.718  6959  6959 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
07-01 12:08:26.718  7022  7044 D Mms/Conversation: [end]    init consume time = 12.920104
,07-01 12:08:26.718  1014  1539 I ActivityManager: Killing 6631:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-01 12:08:26.718  7022  7044 D Mms/MessagingNotification: [start]    init() consume time = 2.947864
,07-01 12:08:26.728  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.728   291   291 E SMD     : DCD OFF
,07-01 12:08:26.728  4059  4059 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 01 12:08:26 GMT+02:00 2016
,07-01 12:08:26.728  1014  1319 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-01 12:08:26.728  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.738  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,07-01 12:08:26.738  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-01 12:08:26.738  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-01 12:08:26.748  7022  7044 D Mms/MessagingNotification: [end]    init consume time = 27.630261
,07-01 12:08:26.748  4059  4059 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-01 12:08:26.758  1014  3993 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-01 12:08:26.758  1014  3993 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-01 12:08:26.758  1014  3993 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-01 12:08:26.758  4059  4059 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-01 12:08:26.758  1014  3993 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.758  1014  3993 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.758  1014  3993 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.758  1014  3993 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.758  7022  7049 D Mms/Synchronizer: [start]    doSync consume time = 13.274114
,07-01 12:08:26.758  7022  7047 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.457657
,07-01 12:08:26.768  4059  4059 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-01 12:08:26.768  4059  4059 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-01 12:08:26.768  4059  7048 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-01 12:08:26.768  7050  7050 E Zygote  : MountEmulatedStorage(),
07-01 12:08:26.768  7050  7050 I libpersona: KNOX_SDCARD checking this for 10090
07-01 12:08:26.768  7050  7050 E Zygote  : v2
07-01 12:08:26.768  7050  7050 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.768  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:26.768  1014  3993 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7050 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
07-01 12:08:26.778  4059  7048 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
07-01 12:08:26.778  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.778  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.778  4059  7048 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-01 12:08:26.778  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-01 12:08:26.778  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-01 12:08:26.778  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.778  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.778  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.778  1477  1489 D TP/MmsSmsProvider: query,matched:0, calling pid = 7022
07-01 12:08:26.778  1477  1489 V TP/MmsSmsProvider: getSimpleConversations entered.
07-01 12:08:26.778  1477  1489 D TP/MmsSmsProvider: match 0:Elapsed time : 0.869 ms
,07-01 12:08:26.788  4059  7048 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-01 12:08:26.798  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:08:26.808  7050  7050 D ActivityThread: Added TimaKeyStore provider
,07-01 12:08:26.818  7022  7037 D Mms/ArtClassLoader: init [DONE] art,
,07-01 12:08:26.818  7066  7066 E Zygote  : MountEmulatedStorage()
,07-01 12:08:26.818  7066  7066 E Zygote  : v2
07-01 12:08:26.818  7066  7066 I libpersona: KNOX_SDCARD checking this for 10032
07-01 12:08:26.818  7066  7066 I libpersona: KNOX_SDCARD not a persona
,07-01 12:08:26.828  1014  1039 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7066 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
07-01 12:08:26.828  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
07-01 12:08:26.828  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.828  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.828  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.828  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.838  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.838  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-01 12:08:26.838  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.838  7072  7072 E Zygote  : MountEmulatedStorage()
07-01 12:08:26.838  7072  7072 I libpersona: KNOX_SDCARD checking this for 10098
07-01 12:08:26.838  7072  7072 E Zygote  : v2
07-01 12:08:26.838  7072  7072 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.838  1014  1039 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7072 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 12:08:26.838  7072  7072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-01 12:08:26.848  7072  7072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-01 12:08:26.848  7072  7072 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:08:26.848  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-01 12:08:26.848  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-01 12:08:26.848  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
07-01 12:08:26.848  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-01 12:08:26.848  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-01 12:08:26.848  1477  2503 D TP/MmsSmsProvider: update, matched:300, calling pid = 7022
07-01 12:08:26.848  1477  2503 V TP/MmsSmsProvider: syncDBData start
,07-01 12:08:26.848  1477  2503 V TP/MmsSmsProvider: syncDBData sms end
07-01 12:08:26.858  1477  2503 V TP/MmsSmsProvider: syncDBData mms end
,07-01 12:08:26.858  1477  2503 V TP/MmsSmsProvider: syncDBData end
07-01 12:08:26.858  1477  1708 D TP/MmsSmsProvider: query,matched:400, calling pid = 7022
,07-01 12:08:26.858  7022  7049 D Mms/Synchronizer: [end]    doSync consume time = 100.513333
07-01 12:08:26.858  1014  1319 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,07-01 12:08:26.868  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.868  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.868  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:08:26.868  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:08:26.868  6465  7083 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-01 12:08:26.868  4059  7048 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-01 12:08:26.878  4059  7048 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,07-01 12:08:26.888  7097  7097 E Zygote  : MountEmulatedStorage(),
07-01 12:08:26.888  7097  7097 E Zygote  : v2,
,07-01 12:08:26.888  7097  7097 I libpersona: KNOX_SDCARD checking this for 10068,
07-01 12:08:26.888  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-01 12:08:26.888  7097  7097 I libpersona: KNOX_SDCARD not a persona
07-01 12:08:26.888  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:08:26.888  7066  7066 D ActivityThread: Added TimaKeyStore provider
07-01 12:08:26.888  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable

```
