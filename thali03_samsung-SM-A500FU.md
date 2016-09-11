#### Test 84265062bba4ad4_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-11 11:55:49.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:55:50.435  6337  6337 D AndroidRuntime: 
09-11 11:55:50.435  6337  6337 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-11 11:55:50.445  6337  6337 D AndroidRuntime: CheckJNI is OFF
09-11 11:55:50.445  6337  6337 D AndroidRuntime: readGMSProperty: start
09-11 11:55:50.445  6337  6337 D AndroidRuntime: readGMSProperty: already setted!!
09-11 11:55:50.445  6337  6337 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-11 11:55:50.445  6337  6337 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-11 11:55:50.445  6337  6337 D AndroidRuntime: readGMSProperty: end
09-11 11:55:50.445  6337  6337 D AndroidRuntime: addProductProperty: start
09-11 11:55:50.595  6337  6337 E AffinityControl: AffinityControl: registerfunction enter
09-11 11:55:50.625  6337  6337 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-11 11:55:50.635  1014  1479 E PersonaManagerService: inState():  stateMachine is null !!
09-11 11:55:50.635  1014  1479 I PersonaManagerService: PersonaId don't exist
09-11 11:55:50.635  1014  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-11 11:55:50.635  1014  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-11 11:55:50.655  1014  1479 W ActivityManager: mDVFSHelper.acquire()
09-11 11:55:50.665  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-11 11:55:50.665  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-11 11:55:50.665  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:55:50.665  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:55:50.665  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:55:50.665  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:55:50.675  6348  6348 E Zygote  : MountEmulatedStorage()
09-11 11:55:50.685  6348  6348 E Zygote  : v2
09-11 11:55:50.685  6348  6348 I libpersona: KNOX_SDCARD checking this for 10155
09-11 11:55:50.685  6348  6348 I libpersona: KNOX_SDCARD not a persona
09-11 11:55:50.685  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-11 11:55:50.685  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-11 11:55:50.685   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-11 11:55:50.685  1014  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-11 11:55:50.685  1014  1479 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6348 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-11 11:55:50.685  1014  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-11 11:55:50.695  6348  6348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:55:50.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
09-11 11:55:50.695  6348  6348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:55:50.695  6348  6348 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-11 11:55:50.695  1014  1479 D InputDispatcher: Focused application set to: xxxx
09-11 11:55:50.695  1014  1479 D InputDispatcher: Focus left window: 3062
09-11 11:55:50.705  6337  6337 D AndroidRuntime: Shutting down VM
09-11 11:55:50.725  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-11 11:55:50.725  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
09-11 11:55:50.725  6348  6348 D TimaKeyStoreProvider: TimaSignature is unavailable
09-11 11:55:50.735  6348  6348 D ActivityThread: Added TimaKeyStore provider
09-11 11:55:50.735  1014  1014 V ActivityManager: Display changed displayId=0
09-11 11:55:50.745  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-11 11:55:50.765  1014  1558 D PersonaManager: isKioskContainerExistOnDevice
09-11 11:55:50.785   257   450 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-11 11:55:50.795   257  1509 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-11 11:55:50.795  3062  3062 V ActivityThread: updateVisibility : ActivityRecord{295b0998 token=android.os.BinderProxy@9174bcf {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-11 11:55:50.875  6348  6348 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-11 11:55:50.885  6348  6348 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5177-5178)
09-11 11:55:50.885  6348  6348 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:55:50.905  6337  6337 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-11 11:55:50.915  6348  6348 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cd32ed4}
,09-11 11:55:50.925  6348  6348 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-11 11:55:50.925  6348  6348 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-11 11:55:50.955  6348  6348 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-11 11:55:50.955  6348  6348 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-11 11:55:50.955  6348  6348 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-11 11:55:50.975  6348  6348 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-11 11:55:50.975  6348  6348 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
09-11 11:55:50.975  6348  6348 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-11 11:55:50.985  6348  6348 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-11 11:55:50.985  6348  6348 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-11 11:55:50.985  6348  6348 I Adreno-EGL: Build Date: 04/06/15 Mon
09-11 11:55:50.985  6348  6348 I Adreno-EGL: Local Branch: 
09-11 11:55:50.985  6348  6348 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-11 11:55:50.985  6348  6348 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-11 11:55:50.985  6348  6348 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-11 11:55:51.105  6348  6375 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-11 11:55:51.155  6348  6348 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:55:51.165  6348  6348 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-11 11:55:51.175  6348  6348 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-11 11:55:51.175  6348  6348 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-11 11:55:51.185  6348  6348 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-11 11:55:51.185  6348  6348 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:55:51.185  6348  6348 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:55:51.225  6348  6388 D OpenGLRenderer: Render dirty regions requested: true
,09-11 11:55:51.235  1014  1560 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-11 11:55:51.235  1014  1560 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-11 11:55:51.235  1014  1560 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-11 11:55:51.235  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-11 11:55:51.235  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-11 11:55:51.245  6348  6348 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-11 11:55:51.245  6348  6348 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-11 11:55:51.255   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-11 11:55:51.265  1014  6147 D InputDispatcher: Focus entered window: 6348
,09-11 11:55:51.265  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-11 11:55:51.265  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-11 11:55:51.265  6348  6348 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-11 11:55:51.265  6348  6388 I OpenGLRenderer: Initialized EGL, version 1.4
,09-11 11:55:51.275  6348  6388 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-11 11:55:51.275  6348  6388 D OpenGLRenderer: Enabling debug mode 0
,09-11 11:55:51.295  6348  6348 V ActivityThread: updateVisibility : ActivityRecord{39a3780f token=android.os.BinderProxy@16f718e9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-11 11:55:51.315  1014  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-11 11:55:51.315  1171  1171 D PanelView: There is/are notification(s) 
,09-11 11:55:51.315  1014  6391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-11 11:55:51.325  6348  6348 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-11 11:55:51.325  6348  6348 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16f718e9 time:115618
,09-11 11:55:51.335  1819  1819 I SamsungIME: getCurrentCandidateView
,09-11 11:55:51.335  1014  1044 I ActivityManager: Displayed Component not be shown by security: +565ms (total +668ms)
,09-11 11:55:51.335  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e9c3b97 u0 com.test.thalitest/.MainActivity t128} time:115622
09-11 11:55:51.335  1014  1044 W ActivityManager: mDVFSHelper.release()
,09-11 11:55:51.335   257  1509 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-11 11:55:51.335   257   448 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-11 11:55:51.425  6348  6348 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6348
,09-11 11:55:51.445  1819  1819 D SamsungIME: Dismiss ExpandCandiate
,09-11 11:55:51.535  6348  6348 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-11 11:55:51.585  1819  1819 I SamsungIME: getDebugLevel  : 0x4f4c
,09-11 11:55:51.625  1819  1819 I SamsungIME: getDebugLevel  : 0x4f4c
,09-11 11:55:51.635  1819  1819 I SamsungIME: KeybaordView init() : load resources
,09-11 11:55:51.645  6348  6393 D jxcore_app_log: JniHelper::setJavaVM(0xb701e328), pthread_self() = -1218954136
,09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-11 11:55:51.655  6348  6393 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25882ff added. We now have 1 listener(s)
,09-11 11:55:51.655  1819  1819 I SamsungIME: getCurrentKeyboard
09-11 11:55:51.655  1819  1819 I SamsungIME: getTextKeyboard
,09-11 11:55:51.665  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-11 11:55:51.665  6348  6393 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:55:51.665  6348  6393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:55:51.665  6348  6393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:55:51.675  1819  1819 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
,09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
,09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-11 11:55:51.675  6348  6393 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f0a2a added. We now have 1 listener(s)
09-11 11:55:51.675  6348  6393 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-11 11:55:51.685  6348  6393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:55:51.695  6348  6393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-11 11:55:51.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:55:51.695  6348  6393 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:55:51.695  6348  6393 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-11 11:55:51.695  6348  6393 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-11 11:55:51.695  6348  6393 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:55:51.705  6348  6393 I io.jxcore.node.LifeCycleMonitor: start: OK
09-11 11:55:51.705   290   290 E SMD     : DCD OFF
,09-11 11:55:51.705  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:55:51.705  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:55:51.745  6348  6348 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-11 11:55:51.785  1014  3130 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-11 11:55:51.785  1014  3130 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-11 11:55:51.785  1014  3130 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-11 11:55:51.785  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-11 11:55:51.785  1014  3130 D BatteryService: stay LED for charging
,09-11 11:55:51.795  1014  1014 I MotionRecognitionService: Plugged
,09-11 11:55:51.795  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-11 11:55:51.795  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-11 11:55:51.795  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-11 11:55:51.795  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-11 11:55:51.805  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-11 11:55:51.815  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-11 11:55:51.815  2648  2774 D HeadsetStateMachine: Disconnected process message: 10
,09-11 11:55:51.825  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-11 11:55:51.825  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:55:51.825  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:55:52.215  1819  6397 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-11 11:55:52.225  6348  6401 W jxcore-log: Initializing JXcore engine
09-11 11:55:52.225  6348  6401 W jxcore-log: JXcore engine is ready
,09-11 11:55:52.285  1928  1928 E audit   : type=1400 msg=audit(1473587752.275:205): avc:  denied  { ioctl } for  pid=6401 comm="Thread-1084" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-11 11:55:52.285  1928  1928 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:55:52.285  1928  1928 E audit   : type=1300 msg=audit(1473587752.275:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e5048f8 items=0 ppid=312 ppcomm=main pid=6401 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1084" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-11 11:55:52.285  1928  1928 E audit   : type=1320 msg=audit(1473587752.275:205): 
,09-11 11:55:52.295  6348  6401 W jxcore-log: Starting JXcore engine
,09-11 11:55:52.405  6348  6401 W jxcore-log: Platform android
09-11 11:55:52.405  6348  6401 W jxcore-log: 
09-11 11:55:52.405  6348  6401 W jxcore-log: Process ARCH arm
09-11 11:55:52.405  6348  6401 W jxcore-log: 
,09-11 11:55:52.605  6348  6401 I jxcore-log: JXcore Cordova bridge is ready!
09-11 11:55:52.605  6348  6401 I jxcore-log: 
,09-11 11:55:52.605  6348  6401 W jxcore-log: JXcore engine is started
,09-11 11:55:52.605  5563  5563 D FactoryTest: Not factory mode
,09-11 11:55:52.605  5563  5563 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-11 11:55:52.605  5563  5563 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-11 11:55:52.605  5563  5563 D MTPRx   : still no open session command from host, so toast
,09-11 11:55:52.615  5563  5563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-11 11:55:52.615  5563  5563 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116901
09-11 11:55:52.615  5563  5563 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-11 11:55:52.615  1014  3132 E PersonaManagerService: inState():  stateMachine is null !!
09-11 11:55:52.615  1014  3132 I PersonaManagerService: PersonaId don't exist
09-11 11:55:52.615  1014  3132 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-11 11:55:52.615  6348  6393 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-11 11:55:52.615  6348  6348 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-11 11:55:52.615  1014  3132 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-11 11:55:52.615  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:55:52.615  1014  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:55:52.615  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-11 11:55:52.625  1014  3132 W ActivityManager: mDVFSHelper.acquire()
,09-11 11:55:52.635  1014  3132 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:55:52.645  1014  3132 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-11 11:55:52.645  1014  3132 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-11 11:55:52.645  1014  3132 D InputDispatcher: Focused application set to: xxxx
,09-11 11:55:52.645  1014  3132 D InputDispatcher: Focus left window: 6348
,09-11 11:55:52.645  5563  5563 E MTPRx   : started activity for popup
,09-11 11:55:52.645  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-11 11:55:52.645  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-11 11:55:52.675  5563  5563 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-11 11:55:52.685  1014  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-11 11:55:52.695  5563  5563 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-11 11:55:52.695  1014  1332 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-11 11:55:52.695  1014  1332 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-11 11:55:52.695  1014  1332 D InputDispatcher: Focused application set to: xxxx
,09-11 11:55:52.695  1014  1332 D InputDispatcher: Focus entered window: 6348
,09-11 11:55:52.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:55:52.695  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-11 11:55:52.695  1014  4271 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-11 11:55:52.695  1014  4271 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@28413a26 attribute=null, token = android.os.BinderProxy@256a0776
,09-11 11:55:52.705  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-11 11:55:52.735  5563  5563 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-11 11:55:52.745  5563  5563 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-11 11:55:52.745  5563  5563 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-11 11:55:52.765  6348  6348 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-11 11:55:52.765  6348  6348 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-11 11:55:52.765  6348  6348 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-11 11:55:52.765  6348  6348 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-11 11:55:52.765  1014  3132 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-11 11:55:52.765  1014  3132 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-11 11:55:52.765  1014  3132 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-11 11:55:52.765  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-11 11:55:52.765  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-11 11:55:52.775  6348  6348 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-11 11:55:52.775  6348  6348 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-11 11:55:52.785  6348  6348 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3889f504 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@25a8586c, 16908290=android.view.AbsSavedState$1@25a8586c}, android:focusedViewId=100}]}]
09-11 11:55:52.785  6348  6348 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-11 11:55:52.785  6348  6348 V ActivityThread: updateVisibility : ActivityRecord{39a3780f token=android.os.BinderProxy@16f718e9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-11 11:55:52.785  6348  6348 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-11 11:55:52.785  6348  6348 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-11 11:55:52.785  6348  6348 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16f718e9 time:117072
,09-11 11:55:52.795  1014  3131 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:55:53.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:55:54.695   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-11 11:55:54.705   290   290 E SMD     : DCD OFF,
,09-11 11:55:55.625  1014  1039 W ActivityManager: mDVFSHelper.release()
,09-11 11:55:55.715  1014  1093 V AlarmManager: waitForAlarm result :4,
09-11 11:55:55.715  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-11 11:55:55.735  1948  1948 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-11 11:55:55.775  1014  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:55:55.775  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-11 11:55:55.775  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:55:55.775  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:55:55.775  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:55:55.855  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:55:55.855  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.HeartbeatAlarm$ConnectionInfoPersistService; callingUser = 0; userId(target) = 0
,09-11 11:55:55.855  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:55:55.855  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:55:55.855  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:55:55.885  1014  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:55:55.885  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-11 11:55:55.885  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:55:55.885  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:55:55.885  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:55:55.905  1014  1332 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-11 11:55:55.905  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-11 11:55:55.925  1948  1948 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-11 11:55:55.945  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:55:55.955  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:55:55.955  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:55:55.955  1014  2735 D SSRM:n  : SIOP:: AP = 310
,09-11 11:55:57.705   290   290 E SMD     : DCD OFF,
,09-11 11:55:59.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:55:59.985  1014  1093 V AlarmManager: waitForAlarm result :8
,09-11 11:56:00.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:56:00.705   290   290 E SMD     : DCD OFF,
09-11 11:56:00.715  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-11 11:56:01.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:56:01.835  1014  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-11 11:56:01.845  1014  1318 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-11 11:56:01.845  1014  1318 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-11 11:56:01.845  1014  1318 D BatteryService: stay LED for charging
09-11 11:56:01.845  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-11 11:56:01.845  1014  1014 I MotionRecognitionService: Plugged
09-11 11:56:01.845  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-11 11:56:01.845  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-11 11:56:01.845  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
09-11 11:56:01.845  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-11 11:56:01.845  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-11 11:56:01.855  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-11 11:56:01.855  2648  2774 D HeadsetStateMachine: Disconnected process message: 10
,09-11 11:56:01.865  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:01.865  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-11 11:56:01.865  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:02.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:56:03.695   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:56:03.705   290   290 E SMD     : DCD OFF,
,09-11 11:56:04.695   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-11 11:56:04.735  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-11 11:56:04.735  6348  6401 I jxcore-log: 
,09-11 11:56:04.735  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-11 11:56:04.735  6348  6401 I jxcore-log: 
,09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:04.735  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:04.735  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:04.745  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-11 11:56:04.745  6348  6401 I jxcore-log: 
,09-11 11:56:04.745  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-11 11:56:04.745  6348  6401 I jxcore-log: 
,09-11 11:56:04.755  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,09-11 11:56:05.405  6348  6401 D executeNativeTests: Running unit tests,
,09-11 11:56:05.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-11 11:56:05.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 added. We now have 2 listener(s)
09-11 11:56:05.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-11 11:56:05.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-11 11:56:05.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:05.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:05.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a added. We now have 2 listener(s)
09-11 11:56:05.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:05.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-11 11:56:05.495  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:05.495  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:05.495  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:05.495  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:05.505  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.505  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-11 11:56:05.505  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:05.505  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-11 11:56:05.505  6348  6401 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-11 11:56:05.515  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.515  6348  6401 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
,09-11 11:56:05.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:05.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-11 11:56:05.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:05.515  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-11 11:56:05.515  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-11 11:56:05.515  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:05.515  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:05.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:05.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 removed from the list
09-11 11:56:05.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a removed from the list
,09-11 11:56:05.515  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop,
09-11 11:56:05.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.525  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.525  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.525  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
,09-11 11:56:05.525  6348  6401 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-11 11:56:05.525  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:05.535  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.535  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.535  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.535  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.535  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.535  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.535  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.535  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.535  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.535  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.535  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.535  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.535  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.535  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:05.535  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.535  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-11 11:56:05.535  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:05.545  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:05.545  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.545  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.545  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.545  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-11 11:56:05.545  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.545  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.545  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.545  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
,09-11 11:56:05.545  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.545  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.545  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.545  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.545  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.545  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.545  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.545  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.545  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list,
09-11 11:56:05.555  6348  6401 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-11 11:56:05.555  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:05.555  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:05.555  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:05.555  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:05.555  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:05.555  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:05.555  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:05.555  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:05.555  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:05.565  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.565  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-11 11:56:05.565  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:05.575  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:05.575  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:05.585  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-11 11:56:05.585  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-11 11:56:05.585  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:05.585  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-11 11:56:05.585  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:05.605  2648  5135 D BtGatt.GattService: registerClient() - UUID=34115197-f2b9-43ac-aeb9-f94daf1e5de6
,09-11 11:56:05.645  2648  2728 D BtGatt.GattService: onClientRegistered() - UUID=34115197-f2b9-43ac-aeb9-f94daf1e5de6, clientIf=6
,09-11 11:56:05.655  6348  6362 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-11 11:56:05.655  2648  2665 D BtGatt.GattService: start scan with filters
,09-11 11:56:05.655  2648  2769 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:05.655  2648  2769 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:05.665  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-11 11:56:05.665  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:05.665  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-11 11:56:05.665  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:05.665  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.665  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-11 11:56:05.675  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.675  2648  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-11 11:56:05.675  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.675  2648  2769 D BtGatt.ScanManager: allow scan with filters
,09-11 11:56:05.675  2648  2769 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-11 11:56:05.675  2648  2769 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-11 11:56:05.675  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:05.685  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-11 11:56:05.685  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.685  2648  2769 D BtGatt.ScanManager: Starting BLE batch scan
,09-11 11:56:05.685  2648  2769 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-11 11:56:05.685  6348  6401 I io.jxcore.node.ConnectionHelper: start: OK
,09-11 11:56:05.695  2648  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-11 11:56:05.695  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.695  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.695  6348  6401 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:05.695  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.695  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:05.695  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.695  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:05.695  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:05.695  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:05.695  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:05.695  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-11 11:56:05.695  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:05.695  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-11 11:56:05.695  2648  2661 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:05.705  2648  5135 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-11 11:56:05.705  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-11 11:56:05.705  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:05.705  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:05.705  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:05.705  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:05.705  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:05.715  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.715  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:05.715  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.715  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:05.715  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.715  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.715  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.715  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.715  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.715  6348  6401 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-11 11:56:05.715  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:05.715  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:05.715  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:05.725  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:05.725  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:05.725  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:05.725  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:05.725  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:05.725  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:05.725  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:05.725  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:05.725  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.725  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:05.735  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.735  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:05.735  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:05.735  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-11 11:56:05.745  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-11 11:56:05.745  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:05.745  2648  2769 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 85
,09-11 11:56:05.745  2648  5135 D BtGatt.GattService: registerClient() - UUID=b2d2fe6e-a5c3-4c2b-b5e4-23c7a52bffe5
,09-11 11:56:05.765  2648  2769 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 85
,09-11 11:56:05.765  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:05.765  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:05.765  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,09-11 11:56:05.775  2648  2769 D BtGatt.ScanManager: filter size is 1
,09-11 11:56:05.775  2648  2769 D BtGatt.ScanManager: delete FilterIndex - 3
,09-11 11:56:05.775  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-11 11:56:05.775  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.775  2648  2769 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:05.775  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-11 11:56:05.775  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.775  2648  2769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-11 11:56:05.785  2648  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
09-11 11:56:05.785  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.785  2648  2728 D BtGatt.GattService: current time is 130073610833
09-11 11:56:05.785  2648  2728 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -90, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-11 11:56:05.785  2648  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-11 11:56:05.785  2648  2728 D ScanRecord: parseFromBytes
09-11 11:56:05.785  2648  2728 D ScanRecord: first manudata for manu ID
09-11 11:56:05.785  2648  2728 D BtGatt.GattService: onClientRegistered() - UUID=b2d2fe6e-a5c3-4c2b-b5e4-23c7a52bffe5, clientIf=6
09-11 11:56:05.785  6348  6362 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-11 11:56:05.795  2648  2665 D BtGatt.GattService: start scan with filters
09-11 11:56:05.795  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:05.795  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:05.795  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:05.795  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-11 11:56:05.795  2648  2769 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:05.795  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.795  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:05.795  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.795  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:05.795  2648  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-11 11:56:05.805  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.805  2648  2769 D BtGatt.ScanManager: allow scan with filters
09-11 11:56:05.805  2648  2769 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-11 11:56:05.805  6348  6401 I io.jxcore.node.ConnectionHelper: start: OK
09-11 11:56:05.805  2648  2769 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-11 11:56:05.805  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:05.805  6348  6401 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:05.805  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:05.805  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-11 11:56:05.805  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:05.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-11 11:56:05.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:05.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:05.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-11 11:56:05.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:05.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-11 11:56:05.805  2648  5135 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:05.805  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-11 11:56:05.805  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.805  2648  2769 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:05.805  2648  2769 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
09-11 11:56:05.805  2648  3096 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:05.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-11 11:56:05.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-11 11:56:05.815  2648  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-11 11:56:05.815  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:05.815  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-11 11:56:05.815  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:05.815  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:05.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.815  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:05.815  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.815  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.815  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.825  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.825  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.825  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:05.825  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.825  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.825  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
,09-11 11:56:05.825  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-11 11:56:05.825  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.825  6348  6401 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-11 11:56:05.825  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:05.835  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:05.835  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:05.835  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:05.835  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:05.835  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:05.835  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:05.835  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:05.835  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:05.845  2648  2769 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,09-11 11:56:05.845  2648  2769 D BtGatt.ScanManager: filter size is 1
09-11 11:56:05.845  2648  2769 D BtGatt.ScanManager: delete FilterIndex - 4
,09-11 11:56:05.845  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-11 11:56:05.845  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.845  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.845  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:05.845  2648  2769 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:05.845  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:05.845  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-11 11:56:05.845  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.845  2648  2769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-11 11:56:05.855  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:05.855  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:05.855  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-11 11:56:05.855  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:05.855  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:05.855  2648  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-11 11:56:05.855  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.855  2648  2665 D BtGatt.GattService: registerClient() - UUID=34f7d0f7-584b-47a9-aca3-6624d56cb8c8
,09-11 11:56:05.905  2648  2728 D BtGatt.GattService: onClientRegistered() - UUID=34f7d0f7-584b-47a9-aca3-6624d56cb8c8, clientIf=6
,09-11 11:56:05.905  6348  6363 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-11 11:56:05.905  2648  2661 D BtGatt.GattService: start scan with filters
,09-11 11:56:05.905  2648  2769 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:05.905  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-11 11:56:05.905  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:05.905  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-11 11:56:05.905  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:05.905  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.905  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:05.905  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-11 11:56:05.915  2648  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-11 11:56:05.915  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.915  2648  2769 D BtGatt.ScanManager: allow scan with filters
09-11 11:56:05.915  2648  2769 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-11 11:56:05.915  2648  2769 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-11 11:56:05.915  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:05.915  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-11 11:56:05.915  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.915  2648  2769 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:05.915  2648  2769 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-11 11:56:05.915  6348  6401 I io.jxcore.node.ConnectionHelper: start: OK
,09-11 11:56:05.915  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:05.915  6348  6401 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:05.915  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.915  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-11 11:56:05.915  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.915  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-11 11:56:05.915  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:05.925  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:05.925  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:05.925  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-11 11:56:05.925  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-11 11:56:05.925  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-11 11:56:05.925  2648  2665 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:05.925  2648  2661 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-11 11:56:05.925  2648  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-11 11:56:05.925  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.925  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-11 11:56:05.925  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-11 11:56:05.925  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:05.925  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-11 11:56:05.925  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-11 11:56:05.935  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-11 11:56:05.935  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.935  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:05.935  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:05.935  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:05.935  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:05.945  2648  2769 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 2
,09-11 11:56:05.945  2648  2769 D BtGatt.ScanManager: filter size is 1
09-11 11:56:05.945  2648  2769 D BtGatt.ScanManager: delete FilterIndex - 5
,09-11 11:56:05.945  2648  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-11 11:56:05.945  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:05.945  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.945  6348  6401 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-11 11:56:05.945  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.945  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.945  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:05.945  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.945  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.945  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.945  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:05.945  2648  2769 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:05.945  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:05.945  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:05.945  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.945  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
,09-11 11:56:05.945  2648  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-11 11:56:05.945  6348  6401 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-11 11:56:05.945  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.945  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.945  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.945  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.945  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.945  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.945  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.945  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.945  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.945  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.945  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.945  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:05.945  2648  2769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-11 11:56:05.955  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-11 11:56:05.955  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-11 11:56:05.955  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  2648  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-11 11:56:05.955  2648  2728 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:05.955  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:05.955  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-11 11:56:05.955  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-11 11:56:05.955  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.955  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.955  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.955  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.955  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.955  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.955  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.965  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.965  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.965  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.965  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:05.965  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-11 11:56:05.965  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-11 11:56:05.965  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-11 11:56:05.965  6348  6401 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:05.965  6348  6401 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-11 11:56:05.965  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:05.965  6348  6401 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-11 11:56:05.965  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-11 11:56:05.965  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-11 11:56:05.975  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-11 11:56:05.975  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-11 11:56:05.975  6348  6401 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-11 11:56:05.975  6348  6401 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-11 11:56:05.975  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.975  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.975  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.975  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.975  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.975  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.975  6348  6418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1148)
09-11 11:56:05.975  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-11 11:56:05.975  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.975  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.975  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.975  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.975  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.975  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.975  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.975  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.975  6348  6419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1148
09-11 11:56:05.975  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.975  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.975  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.975  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.975  6348  6401 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-11 11:56:05.975  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6418 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-11 11:56:05.985  6348  6401 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:05.985  6348  6401 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-11 11:56:05.985  6348  6401 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:05.985  6348  6401 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  1014  2735 D SSRM:n  : SIOP:: AP = 320
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:05.985  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.985  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.985  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.985  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.985  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.985  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.995  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-11 11:56:05.995  6348  6418 D BluetoothSocket: connect(): myUserId = 0
09-11 11:56:05.995  6348  6418 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-11 11:56:05.995  2648  2665 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-11 11:56:05.995  6348  6420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-11 11:56:05.995  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:05.995  6348  6420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-11 11:56:05.995  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:05.995  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:05.995  6348  6348 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-11 11:56:05.995  6348  6348 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-11 11:56:05.995  6348  6418 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-11 11:56:05.995  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.005  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.005  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:06.005  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.005  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.005  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6348 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-11 11:56:06.005  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.005  6348  6401 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-11 11:56:06.005  6348  6401 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-11 11:56:06.005  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-11 11:56:06.005  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.005  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.005  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.005  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.005  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.005  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.005  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.015  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.015  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:06.015  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:06.015  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19849ea5 not in the list
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:06.015  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:06.015  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e6c027a not in the list
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:06.015  6348  6401 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:06.015  6348  6401 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-11 11:56:06.015  6348  6401 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-11 11:56:06.015  6348  6401 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-11 11:56:06.015  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.015  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c507ccc added. We now have 2 listener(s)
09-11 11:56:06.015  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.025  6348  6401 D BluetoothAdapter: enable()
,09-11 11:56:06.025  6348  6401 D BluetoothAdapter: enable(): BT is already enabled..!
09-11 11:56:06.025  1014  1137 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-11 11:56:06.025  1014  1137 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-11 11:56:06.025  1014  1137 D SecContentProvider2: mCursor = null
09-11 11:56:06.025  1014  1137 D WifiService: setWifiEnabled: true pid=6348, uid=10155
09-11 11:56:06.025  1014  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:06.025  1014  1137 W WifiService: Failed getting userId using ActivityManagerNative
09-11 11:56:06.025  1014  1137 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:06.025  1014  1137 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-11 11:56:06.025  1014  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-11 11:56:06.025  1014  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-11 11:56:06.025  1014  1137 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-11 11:56:06.025  1014  1137 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-11 11:56:06.025  1014  1137 D SettingsProvider: name = wifi_on
09-11 11:56:06.025  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.025  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16137b15 added. We now have 3 listener(s)
09-11 11:56:06.025  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.035  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.035  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d09fe2a added. We now have 4 listener(s)
09-11 11:56:06.035  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.035  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:06.035  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@272e341b added. We now have 5 listener(s)
09-11 11:56:06.035  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:06.035  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-11 11:56:06.035  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-11 11:56:06.035  1014  1027 D SecContentProvider2: mCursor = null
09-11 11:56:06.035  1014  1027 D WifiService: setWifiEnabled: false pid=6348, uid=10155
09-11 11:56:06.035  1014  1027 D SettingsProvider: name = wifi_on
09-11 11:56:06.045  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-11 11:56:06.045  6348  6401 D BluetoothAdapter: disable()
09-11 11:56:06.045  2093  2093 I wpa_supplicant: reset timer : RESET_TIMER 0
09-11 11:56:06.045  2093  2093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-11 11:56:06.045  2093  2093 I wpa_supplicant: P2P: Current p2p state = IDLE
09-11 11:56:06.045  1014  6147 D SettingsProvider: name = bluetooth_on
09-11 11:56:06.045  2093  2093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-11 11:56:06.055  2648  2720 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-11 11:56:06.055  1014  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:06.055  2648  2720 D BluetoothAdapterProperties: Setting state to 13
09-11 11:56:06.055  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-11 11:56:06.055  2648  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-11 11:56:06.055  2648  2720 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:06.055  2648  2720 D BluetoothAdapterService: updateAdapterState state is 13
09-11 11:56:06.055  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-11 11:56:06.055  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.055  1014  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.055  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.055  2648  2648 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
09-11 11:56:06.065  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@85b67e7, channel: 19, state: LISTENING
09-11 11:56:06.065  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@85b67e7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17f3fc9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c3dcf94mSocket: android.net.LocalSocket@c08aa3d impl:android.net.LocalSocketImpl@2bbd4232 fd:FileDescriptor[74]
,09-11 11:56:06.065  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c08aa3d impl:android.net.LocalSocketImpl@2bbd4232 fd:FileDescriptor[74]
09-11 11:56:06.065  2648  2720 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:06.065  2648  2720 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-11 11:56:06.065  2648  2720 D BluetoothAdapterService: terminating service from this receiver
09-11 11:56:06.065  1297  1297 D BluetoothPbap: Proxy object disconnected
09-11 11:56:06.065  1297  1297 D PbapServerProfile: Bluetooth service disconnected
,09-11 11:56:06.065  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.065  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-11 11:56:06.065  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-11 11:56:06.065  1819  1819 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-11 11:56:06.075  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.075  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:06.075  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-11 11:56:06.075  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25f25100, channel: 5, state: LISTENING
09-11 11:56:06.075  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25f25100, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c9e29ef, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22daad39mSocket: android.net.LocalSocket@2af94f7e impl:android.net.LocalSocketImpl@3bd36cdf fd:FileDescriptor[76]
09-11 11:56:06.075  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2af94f7e impl:android.net.LocalSocketImpl@3bd36cdf fd:FileDescriptor[76]
,09-11 11:56:06.075  1014  1125 E WifiNative-wlan0: do suspend true
,09-11 11:56:06.075  2648  2648 I BtOppRfcommListener: stopping Accept Thread
09-11 11:56:06.075  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37ab7d2c, channel: 12, state: LISTENING
09-11 11:56:06.075  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@37ab7d2c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e9a1f01, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@302fe3f5mSocket: android.net.LocalSocket@2056e58a impl:android.net.LocalSocketImpl@11abf7fb fd:FileDescriptor[79]
09-11 11:56:06.075  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2056e58a impl:android.net.LocalSocketImpl@11abf7fb fd:FileDescriptor[79]
,09-11 11:56:06.075  2648  5142 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:06.075  2648  5142 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-11 11:56:06.075  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.075  1014  1558 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:06.075  1014  3132 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-11 11:56:06.075  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:06.075  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-11 11:56:06.085  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:06.085  1014  1318 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:06.085  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:06.085  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.085  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.085  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-11 11:56:06.085  1014  1318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.085  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.085  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.085  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:06.085  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.085  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.085  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.085  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.085  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.085  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-11 11:56:06.095  2648  2648 V BluetoothOppManager: cleanUp...,
09-11 11:56:06.095  2648  2720 D BluetoothAdapterProperties: onBluetoothDisable()
09-11 11:56:06.095  2648  2720 D BluetoothAdapterProperties: mDiscovering is false
,09-11 11:56:06.095  1014  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-11 11:56:06.095  2648  2720 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-11 11:56:06.105  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-11 11:56:06.105  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-11 11:56:06.105  2648  2728 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-11 11:56:06.105  2648  2728 D BluetoothAdapterProperties: Scan Mode:20
,09-11 11:56:06.105  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.105  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-11 11:56:06.105  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:06.115  2648  2720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-11 11:56:06.115  2648  2720 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-11 11:56:06.115  2648  2720 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-11 11:56:06.115  2648  2720 E bt-btif : cmd socket is not created
,09-11 11:56:06.115  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:06.115  2648  2720 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-11 11:56:06.115  2648  2894 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-11 11:56:06.115  2648  2894 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-11 11:56:06.115  6348  6418 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@203db391, channel: -1, state: INIT
09-11 11:56:06.115  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-11 11:56:06.115  6348  6418 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@203db391, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a21d2f6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ef1f6f7mSocket: android.net.LocalSocket@304f9964 impl:android.net.LocalSocketImpl@19f8f7cd fd:FileDescriptor[106]
09-11 11:56:06.115  6348  6418 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@304f9964 impl:android.net.LocalSocketImpl@19f8f7cd fd:FileDescriptor[106]
09-11 11:56:06.115  6348  6418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1148)
09-11 11:56:06.115  1014  1560 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:06.115  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.115  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.115  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.115  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:06.115  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:06.115  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:06.115  2648  2894 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-11 11:56:06.125  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.125  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.125  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:06.135  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.135  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:06.135  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.135  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-11 11:56:06.135  1014  1332 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-11 11:56:06.145  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.145  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.145  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.145  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:06.155  6426  6426 E Zygote  : MountEmulatedStorage(),
09-11 11:56:06.155  6426  6426 I libpersona: KNOX_SDCARD checking this for 10003
09-11 11:56:06.155  6426  6426 E Zygote  : v2
09-11 11:56:06.155  6426  6426 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:06.155  1014  1332 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6426 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
09-11 11:56:06.165  6426  6426 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:56:06.165  6426  6426 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:06.165  6426  6426 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:06.185  6426  6426 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:06.195  6426  6426 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:06.215  6426  6426 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-11 11:56:06.225  2093  2093 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
,09-11 11:56:06.225  1014  1124 D WifiP2pService: InactiveState{ what=147461 }
,09-11 11:56:06.225  1014  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-11 11:56:06.235  1014  1124 D WifiP2pService: DefaultState{ what=147461 }
,09-11 11:56:06.235   277  1002 D CommandListener: Clearing all IP addresses on wlan0,
09-11 11:56:06.235  1948  4547 V NativeCrypto: Read error: ssl=0xb74de168: I/O error during system call, Connection timed out
09-11 11:56:06.235  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
09-11 11:56:06.235  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-11 11:56:06.245  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:06.245  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-11 11:56:06.245  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:06.245  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.245  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-11 11:56:06.245  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.245  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.245  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.245  1948  4547 V NativeCrypto: SSL shutdown failed: ssl=0xb74de168: I/O error during system call, Broken pipe
09-11 11:56:06.245  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:06.245  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:06.245  1948  4547 E GCM     : Wifi connection closed with errorCode 20
09-11 11:56:06.245  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-11 11:56:06.255  1014  1479 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-11 11:56:06.255  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.255  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.255  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-11 11:56:06.255  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.255  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-11 11:56:06.255  1014  2214 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-11 11:56:06.255  1014  2214 I qtaguid : Tagging socket 355 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
09-11 11:56:06.255  6426  6426 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-11 11:56:06.255  6426  6426 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-11 11:56:06.255  6426  6426 D UserAnalysis: Create SecureDbHelper
,09-11 11:56:06.265  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-11 11:56:06.265  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:06.265  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-11 11:56:06.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.265  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-11 11:56:06.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:06.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:06.265  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1,
09-11 11:56:06.275  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-11 11:56:06.265  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.265  1014  2214 I qtaguid : Untagging socket 355
09-11 11:56:06.265  1014  2214 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-11 11:56:06.265  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-11 11:56:06.265  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:06.275  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-11 11:56:06.275  6426  6426 D IntelligenceServiceApplication: onCreate(),
,09-11 11:56:06.275  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:06.275  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:06.275  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-11 11:56:06.275  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-11 11:56:06.285  1014  1559 I ActivityManager: Killing 5484:com.google.android.talk/u0a104 (adj 15): empty #31,
,09-11 11:56:06.285  6426  6426 D IntelligenceServiceApplication: no applications having user consent for prediction,
,09-11 11:56:06.295  1014  3132 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-11 11:56:06.295  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.295  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.295  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.295  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:06.305  6448  6448 E Zygote  : MountEmulatedStorage()
09-11 11:56:06.305  6448  6448 I libpersona: KNOX_SDCARD checking this for 10107
09-11 11:56:06.305  6448  6448 E Zygote  : v2
09-11 11:56:06.305  6448  6448 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:06.305  6448  6448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:06.315  6448  6448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:06.315  6448  6448 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:06.315  1014  3132 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6448 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:06.315  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:06.315  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:06.315  2648  2894 W bt-btif : ag scb idx 1 not allocated
09-11 11:56:06.315  2648  2894 W bt-btif : ag scb idx 2 not allocated
09-11 11:56:06.315  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-11 11:56:06.315  2648  2894 E bt-btif : BTA AG is already disabled, ignoring ...
09-11 11:56:06.315  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:06.315  2648  2980 I bt_userial_mct: exiting userial_read_thread
09-11 11:56:06.315  1014  1044 D WifiDisplayController: disconnect
09-11 11:56:06.315  2648  2980 D bt_userial_mct: Leaving userial_evt_read_thread()
09-11 11:56:06.315  1014  1044 D WifiDisplayController: updateConnection
09-11 11:56:06.315  2648  2728 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-11 11:56:06.315  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:06.315  2648  2896 I bt_vendor: hw_epilog_process
09-11 11:56:06.315  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-11 11:56:06.315  2648  2728 D bt_userial_mct: userial_close
09-11 11:56:06.315  1014  1124 D WifiP2pService: P2pDisablingState
09-11 11:56:06.315  2648  2728 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-11 11:56:06.315  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-11 11:56:06.315  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-11 11:56:06.315  1014  1124 D WifiP2pService: p2p socket connection lost
,09-11 11:56:06.315  6426  6426 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-11 11:56:06.315  1014  1124 D WifiP2pService: P2pDisabledState
09-11 11:56:06.315  1014  1125 E WifiNative-wlan0: do suspend true
,09-11 11:56:06.325  6426  6426 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-11 11:56:06.325  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-11 11:56:06.325  1014  1560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-11 11:56:06.325  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-11 11:56:06.325  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-11 11:56:06.325  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:06.325  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-11 11:56:06.325  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null,
,09-11 11:56:06.335  6448  6448 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:06.335  6448  6448 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:06.375  1014  1252 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:06.375  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.375  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:06.375  1014  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.375  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.415  1014  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:06.425   277   998 D EnterpriseController: uids 1000
,09-11 11:56:06.425   277   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-11 11:56:06.425   277   998 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-11 11:56:06.425  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-11 11:56:06.425  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
09-11 11:56:06.425  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-11 11:56:06.425  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-11 11:56:06.425  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-11 11:56:06.425  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-11 11:56:06.425  1014  2214 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler },
09-11 11:56:06.425  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.425  1171  1718 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-11 11:56:06.425  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-11 11:56:06.425  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-11 11:56:06.425  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false,
09-11 11:56:06.425  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:06.425  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:06.425  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-11 11:56:06.425  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-11 11:56:06.425  3846  5025 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-11 11:56:06.435  1014  1560 W ActivityManager: userId = 0, bbcId = -10000,
09-11 11:56:06.435  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.435  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.435   277  1002 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:06.435  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:06.435  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:06.435  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.435  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.435  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.435  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.435  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-11 11:56:06.435  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-11 11:56:06.435  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:06.435  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:06.435  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:06.445  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-11 11:56:06.445  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-11 11:56:06.445  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-11 11:56:06.445  1014  1122 V NetworkStats: updateIfacesLocked()
09-11 11:56:06.445  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.445  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-11 11:56:06.445  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-11 11:56:06.445  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: updateDataNetType()
,09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-11 11:56:06.455  1014  1122 V NetworkStats: performPollLocked() took 6ms
,09-11 11:56:06.455  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-11 11:56:06.455  2093  2093 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-11 11:56:06.455  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-11 11:56:06.455  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:06.455  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:06.455  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.455  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-11 11:56:06.455  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:06.455  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-11 11:56:06.455  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:06.465  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:06.465  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:06.465  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.465  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:06.465  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:06.475  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:06.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-11 11:56:06.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:06.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:06.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:06.475  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:06.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-11 11:56:06.475  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:06.475  1171  1171 D HotspotTile: onReceive : 0, 0
,09-11 11:56:06.475  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:06.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.485  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:06.495  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:06.495  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.495  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:06.505  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:06.505  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:06.505  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:06.505  6348  6348 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:06.515  2648  2728 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-11 11:56:06.515  2648  2728 I bt_vendor: bluetooth satus is on
09-11 11:56:06.515  2648  2728 I bt_vendor: bt-vendor : resetting BT status
09-11 11:56:06.515  2648  2728 I bt_vendor: Starting hciattach daemon
09-11 11:56:06.515  2648  2728 I bt_vendor: try to set false
,09-11 11:56:06.515  2648  2728 I bt_vendor: Starting hciattach daemon
,09-11 11:56:06.515  2648  2728 I bt_vendor: try to set false
,09-11 11:56:06.515  2648  2728 I bt_vendor: cleanup
,09-11 11:56:06.515  2648  2894 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-11 11:56:06.515  2648  2728 I GKI_LINUX: GKI_exit_task 0 done
09-11 11:56:06.515  2648  2728 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-11 11:56:06.515  2648  2720 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
09-11 11:56:06.515  2648  2720 D BtConfig.SecureMode: isSecureModeOn:false
09-11 11:56:06.515  2648  2720 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-11 11:56:06.515  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-11 11:56:06.515  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-11 11:56:06.515  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-11 11:56:06.525  1014  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:06.525  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-11 11:56:06.525  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:06.525  1014  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.525  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:06.525  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-11 11:56:06.525  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:06.525  2648  2648 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:06.525  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-11 11:56:06.525  2648  2648 D BtGatt.GattService: Received stop request...Stopping profile...
09-11 11:56:06.525  2648  2648 D BtGatt.GattService: stop()
09-11 11:56:06.525  2648  2648 D BtGatt.AdvertiseManager: advertise clients cleared
,09-11 11:56:06.535  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:06.535  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.535  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.535  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.535  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.535  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
09-11 11:56:06.535  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-11 11:56:06.535  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:06.535  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:06.535  1014  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:06.535  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.535  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:06.535  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.535  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.545  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-11 11:56:06.545  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-11 11:56:06.545  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-11 11:56:06.545  1014  4271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:06.545  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.545  1014  4271 W ActivityManager: userId = 0, bbcId = -10000,
09-11 11:56:06.545  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:06.545  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.545  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-11 11:56:06.545  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-11 11:56:06.545  2093  2093 I wpa_supplicant: Blacklist: Clear (all) 
,09-11 11:56:06.545  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-11 11:56:06.555  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:06.555  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.555  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.555  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.555  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:06.555  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-11 11:56:06.555  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-11 11:56:06.555  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-11 11:56:06.555  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:06.555  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.555  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.555  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.555  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:06.565  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:06.565  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.565  2648  2720 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:06.565  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:06.565  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.565  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-11 11:56:06.565  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.565  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:06.565  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-11 11:56:06.565  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-11 11:56:06.565  2648  2720 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-11 11:56:06.565  1014  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:06.565  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-11 11:56:06.575  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.575  1014  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.575  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:06.575  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:06.575  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-11 11:56:06.575  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-11 11:56:06.575  2648  2720 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-11 11:56:06.575  2648  2720 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-11 11:56:06.575  2648  2720 D BluetoothAdapterState: Stopping profile services that were post enabled
09-11 11:56:06.575  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-11 11:56:06.575  2648  2648 D HeadsetService: Received stop request...Stopping profile...
,09-11 11:56:06.585  2093  2093 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-11 11:56:06.585  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:06.585  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:06.585  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:06.585  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:06.595  2648  2648 D A2dpService: Received stop request...Stopping profile...
,09-11 11:56:06.595  2648  2781 D A2dpStateMachine: Exit Disconnected: -1
,09-11 11:56:06.595  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-11 11:56:06.605  1297  1297 D HeadsetProfile: Bluetooth service disconnected
,09-11 11:56:06.615  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:06.615  2093  2093 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-11 11:56:06.615  2093  2093 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-11 11:56:06.615  2093  2093 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-11 11:56:06.615  2093  2093 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:06.615  2093  2093 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-11 11:56:06.615  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-11 11:56:06.615  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.615  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.615  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:06.615  1014  1128 D Tethering: InitialState.processMessage what=4
,09-11 11:56:06.615  2648  2648 D HidService: Received stop request...Stopping profile...
09-11 11:56:06.615  2648  2648 D HidService: Stopping Bluetooth HidService
09-11 11:56:06.615  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:06.615  2648  2648 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-11 11:56:06.615  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-11 11:56:06.615  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:06.625  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:06.625  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-11 11:56:06.625  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-11 11:56:06.625  1297  1297 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:06.625  1297  1297 D A2dpProfile: Bluetooth service disconnected
09-11 11:56:06.625  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.625  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.625  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:06.625  1014  1128 E Tethering: No numeric data
,09-11 11:56:06.625  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.625  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.625  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:06.625  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.625  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:06.625  1014  1128 D Tethering: clearTetheredNotification()
09-11 11:56:06.625  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.635  2648  2648 D HealthService: Received stop request...Stopping profile...
09-11 11:56:06.635  1297  1297 D BluetoothInputDevice: Proxy object disconnected
09-11 11:56:06.635  1297  1297 D HidProfile: Bluetooth service disconnected
,09-11 11:56:06.635  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:06.635  2854  2854 D BluetoothA2dp: Proxy object disconnected
,09-11 11:56:06.635  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.635  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.635  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.635  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-11 11:56:06.645  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-11 11:56:06.645  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:06.645  1014  1122 V NetworkStats: performPollLocked() took 5ms
09-11 11:56:06.645  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.645  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.645  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-11 11:56:06.645  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.645  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.655  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.655  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.655  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.655  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-11 11:56:06.655  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.655  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.665  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.665  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.665  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.665  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:06.665  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:06.665  1014  4271 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-11 11:56:06.665  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-11 11:56:06.665  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.665  2648  2648 D PanService: Received stop request...Stopping profile...
09-11 11:56:06.665  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.665  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.665  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
,09-11 11:56:06.665  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.675  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.675  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.675  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.675  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.675  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.675  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-11 11:56:06.675   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb88457c8
09-11 11:56:06.675   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-11 11:56:06.675   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
09-11 11:56:06.675   270   294 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1199286984)
,09-11 11:56:06.685  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-11 11:56:06.685  1297  1297 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:06.685  1297  1297 D PanProfile: Bluetooth service disconnected
09-11 11:56:06.685  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.685  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:06.685  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.685  2648  2648 D BluetoothMapService: Received stop request...Stopping profile...
,09-11 11:56:06.695  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-11 11:56:06.695  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4,
09-11 11:56:06.695  1948  1948 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-11 11:56:06.695  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-11 11:56:06.695  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-11 11:56:06.705  2648  2648 D SapService: Received stop request...Stopping profile...
09-11 11:56:06.705  1948  1948 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-11 11:56:06.705  2648  2648 D SapService: Stopping Bluetooth SapService
,09-11 11:56:06.705  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3cd32ed4
09-11 11:56:06.705   290   290 E SMD     : DCD OFF
,09-11 11:56:06.715  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-11 11:56:06.715  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-11 11:56:06.715  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-11 11:56:06.715  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-11 11:56:06.715  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-11 11:56:06.715  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-11 11:56:06.715  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-11 11:56:06.715  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-11 11:56:06.715  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-11 11:56:06.715  2648  2648 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:06.715  2648  2648 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-11 11:56:06.725  2648  2782 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-11 11:56:06.725  1297  1297 D BluetoothMap: Proxy object disconnected
09-11 11:56:06.725  1297  1297 D MapProfile: Bluetooth service disconnected
09-11 11:56:06.725  2648  2648 I GKI_LINUX: GKI_exit_task 2 done
09-11 11:56:06.725  2648  2648 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-11 11:56:06.725  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-11 11:56:06.725  1297  1297 D SapProfile: Bluetooth service disconnected
,09-11 11:56:06.735  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-11 11:56:06.735  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-11 11:56:06.735  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:06.735  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:06.735  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-11 11:56:06.735  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:06.735  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-11 11:56:06.735  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=320 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java,.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=230 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.File.exists(File.java:363)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.openFileIn,put(ContextImpl.java:1331)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.e.b(PG:170)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.k.c(PG:583)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.e.b(PG:170)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  6448  6448 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.io.File.exists(File.java:363)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:06.735  6448  6448 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-11 11:56:06.735  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-11 11:56:06.735  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-11 11:56:06.735  2648  2648 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-11 11:56:06.735  2648  2648 E BluetoothAdapterService(1020473044): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-11 11:56:06.735  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-11 11:56:06.735  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-11 11:56:06.735  2648  2720 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-11 11:56:06.735  2648  2720 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:06.735  2648  2720 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-11 11:56:06.735  2648  2720 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:06.735  2648  2720 D BluetoothAdapterService: updateAdapterState state is 10
09-11 11:56:06.735  2648  2720 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:06.735  2648  2720 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-11 11:56:06.735  2648  2720 I BluetoothAdapterState: Entering OffState
09-11 11:56:06.735  1297  1308 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.735  1297  1308 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.745   270   294 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-11 11:56:06.745   270   294 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-11 11:56:06.745   270   294 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1199286984) wakelock released: 1, error no: 0
09-11 11:56:06.745   270   294 I rmt_storage: 
09-11 11:56:06.745   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb88457c8
09-11 11:56:06.755  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:06.755  1297  1306 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-11 11:56:06.765  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.765  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.765  1297  1308 D BluetoothPbap: onBluetoothStateChange: up=false
09-11 11:56:06.765  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-11 11:56:06.765  6348  6362 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.765  1014  1558 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:06.765  6348  6362 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.765  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:06.765  6348  6362 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-11 11:56:06.765  6348  6362 D BluetoothLeAdvertiser: Exit stop advertising
09-11 11:56:06.765  6348  6362 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-11 11:56:06.765  6348  6362 D BluetoothLeScanner: Exiting stopAllScan
09-11 11:56:06.765  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.765  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:06.765  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-11 11:56:06.765  3577  3577 I Hs20UtilService: Starting #8
09-11 11:56:06.765  2648  3096 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.765  2648  3096 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.775  1948  2109 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.775  1948  2109 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:06.775  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-11 11:56:06.775  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-11 11:56:06.775  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-11 11:56:06.775  1438  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.775  1438  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.775  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:06.775  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:06.775  1297  1308 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:06.775  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:06.775  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:06.775  3577  3602 I Hs20UtilService: Message received 5007
09-11 11:56:06.775  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-11 11:56:06.775  2854  2869 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:06.785  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-11 11:56:06.785  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-11 11:56:06.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-11 11:56:06.785  1014  1558 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-11 11:56:06.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:06.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:06.785  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:06.785  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-11 11:56:06.785  2854  2866 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.785  2854  2866 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.785  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.785  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.785  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-11 11:56:06.785  1014  1559 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-11 11:56:06.785  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.785  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.785  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.785  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.795  6448  6470 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-11 11:56:06.805  2093  2093 I wpa_supplicant: Blacklist: Clear (all) 
09-11 11:56:06.805  6492  6492 E Zygote  : MountEmulatedStorage()
09-11 11:56:06.805  6492  6492 E Zygote  : v2
09-11 11:56:06.805  6492  6492 I libpersona: KNOX_SDCARD checking this for 10068
09-11 11:56:06.805  6492  6492 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:06.805  6492  6492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:06.805  1014  1559 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6492 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:06.815  6492  6492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:06.815  2648  2665 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:06.815  1297  1306 D Bluetoothsap: onBluetoothStateChange: up=false
09-11 11:56:06.815  1297  1306 D Bluetoothsap: Unbinding service...
09-11 11:56:06.815  6492  6492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:06.815  1452  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.815  1452  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.815  1427  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.815  1427  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:06.815  1297  1306 D BluetoothMap: onBluetoothStateChange: up=false
,09-11 11:56:06.815  1171  3601 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:06.825  1014  1318 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-11 11:56:06.815  1171  3601 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:06.825  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.825  1014  1318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.825  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.825  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-11 11:56:06.825  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-11 11:56:06.835  2093  2093 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-11 11:56:06.845  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.845  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:06.845  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:06.845  6492  6492 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:06.845  6492  6492 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:06.855  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.855  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,09-11 11:56:06.855  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-11 11:56:06.865  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:06.865  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:06.865  1171  1739 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:06.865  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.865  1171  1171 D BluetoothTile:  getBluetoothState : 10
,09-11 11:56:06.865  1171  1739 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:06.865  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:06.865  1014  3131 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-11 11:56:06.865  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:06.865  1819  1819 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-11 11:56:06.865  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:06.865  1014  1558 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:06.865  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.865  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.875  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.875  1948  2121 D BluetoothAdapter: 216489189: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:06.875  1014  6147 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-11 11:56:06.875  1948  2121 D BluetoothAdapter: 216489189: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:06.875  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-11 11:56:06.875  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-11 11:56:06.875  2648  2728 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-11 11:56:06.875  2648  2648 I GKI_LINUX: GKI_exit_task 1 done
09-11 11:56:06.875  2648  2648 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-11 11:56:06.875  2648  2648 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-11 11:56:06.875  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:06.875  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.875  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.875  2648  2648 I art     : System.exit called, status: 0
09-11 11:56:06.875  2648  2648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-11 11:56:06.885  6492  6492 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-11 11:56:06.905  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:06.905  1014  1559 W ActivityManager: userId = 0, bbcId = -10000,
09-11 11:56:06.905  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:06.905  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-11 11:56:06.905  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:06.905  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-11 11:56:06.915  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-11 11:56:06.925  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:06.925  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:06.925  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:06.925  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:06.935  6492  6492 D FileShare-Client: Outbound.stopDelayTimer - 
,09-11 11:56:06.935  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:06.945  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-11 11:56:06.955  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:06.955  3062  3062 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-11 11:56:06.965  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.965  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:06.965  3062  3062 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-11 11:56:06.965  1014  3132 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-11 11:56:06.965  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.965  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.965  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:06.965  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: android.os.DeadObjectException
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-11 11:56:06.965  6448  6470 E BluetoothAdapter: 	at java.lang.Thread.run(Thread.java:818)
,09-11 11:56:06.985  6517  6517 E Zygote  : MountEmulatedStorage(),
09-11 11:56:06.985  6517  6517 E Zygote  : v2
09-11 11:56:06.985  6517  6517 I libpersona: KNOX_SDCARD checking this for 10069
,09-11 11:56:06.985  6517  6517 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:06.985  1014  3132 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6517 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:06.985  6517  6517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:06.995  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-11 11:56:06.995  6517  6517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:06.995  1014  1026 I ActivityManager: Process com.android.bluetooth (pid 2648)(adj 0) has died(42,1107)
09-11 11:56:06.995  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-11 11:56:06.995  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-11 11:56:06.995  6517  6517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:07.005  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:07.005  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-11 11:56:07.005  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:07.005  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:07.005  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:07.005  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:07.005  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:07.005  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:07.005  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-11 11:56:07.005  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:07.005  1948  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:07.015  1171  1171 D HotspotTile: onReceive : 1, 0
09-11 11:56:07.015  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:07.015  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:07.015  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:07.035  6517  6517 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:07.035  6517  6517 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:07.035  1948  1948 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=7a207835-40f8-4cef-8115-96f0db807369
,09-11 11:56:07.045  1014  1252 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-11 11:56:07.045  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-11 11:56:07.045  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.045  1014  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:07.045  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:07.055  1014  1027 I ActivityManager: Killing 5143:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-11 11:56:07.065  6517  6517 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:07.075  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.075  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.075  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-11 11:56:07.075  1014  4271 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-11 11:56:07.075  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.075  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.075  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.075  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.095  6533  6533 E Zygote  : MountEmulatedStorage(),
,09-11 11:56:07.095  6533  6533 E Zygote  : v2
,09-11 11:56:07.095  6533  6533 I libpersona: KNOX_SDCARD checking this for 10104
09-11 11:56:07.095  6533  6533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:56:07.095  6533  6533 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:07.095  1014  4271 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6533 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-11 11:56:07.095  6533  6533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:07.095  6533  6533 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-11 11:56:07.105  1014  1026 I ActivityManager: Killing 5757:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-11 11:56:07.115  6533  6533 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:07.115  6533  6533 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:07.125  6533  6533 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-11 11:56:07.225  1948  2106 W GCoreFlp: No location to return for getLastLocation()
,09-11 11:56:07.335  6533  6556 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-11 11:56:07.335  6533  6556 I Babel   : MmsConfig.loadMmsSettings
,09-11 11:56:07.335  6533  6556 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-11 11:56:07.335  6533  6556 I Babel   : MmsConfig.loadFromDatabase
,09-11 11:56:07.345  6533  6556 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-11 11:56:07.345  6533  6556 I Babel   : MmsConfig.loadFromResources
,09-11 11:56:07.355  6533  6556 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-11 11:56:07.355  6533  6556 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-11 11:56:07.395  1014  3132 I art     : Explicit concurrent mark sweep GC freed 57958(3MB) AllocSpace objects, 20(368KB) LOS objects, 33% free, 28MB/42MB, paused 2.589ms total 160.020ms
,09-11 11:56:07.415  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:07.415  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.415  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.415  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:07.415  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:07.425  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.425  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.425  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:07.425  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:07.425  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.425  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.425  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:07.435  1014  1559 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-11 11:56:07.435  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-11 11:56:07.435  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.435  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.435  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-11 11:56:07.445  6533  6533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:07.455  3846  6466 D UdcContextInitService: registered all accounts: true
,09-11 11:56:07.465  1014  1041 D Tethering: interfaceRemoved wlan0
,09-11 11:56:07.465  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-11 11:56:07.475  1948  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-11 11:56:07.505  6533  6533 I Babel_StickerModule: App launched.
,09-11 11:56:07.505  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.505  1014  6147 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.505  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.525   285   682 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-11 11:56:07.525   285   682 W QCamera2Factory: getCameraInfo: X
,09-11 11:56:07.525   285   285 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,09-11 11:56:07.525   285   285 W QCamera2Factory: getCameraInfo: X
,09-11 11:56:07.535  6533  6533 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-11 11:56:07.545  6533  6533 W AudioCapabilities: Unsupported mime audio/evrc
,09-11 11:56:07.545  6533  6533 W AudioCapabilities: Unsupported mime audio/qcelp
,09-11 11:56:07.545  6533  6533 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-11 11:56:07.545  6533  6533 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-11 11:56:07.545  6533  6533 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-11 11:56:07.555  6533  6533 W AudioCapabilities: Unsupported mime audio/x-ima
,09-11 11:56:07.555  6533  6533 W AudioCapabilities: Unsupported mime audio/qcelp
,09-11 11:56:07.555  6533  6533 W AudioCapabilities: Unsupported mime audio/evrc
,09-11 11:56:07.565  6533  6533 W VideoCapabilities: Unsupported mime video/wvc1
,09-11 11:56:07.565  6533  6533 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-11 11:56:07.575  6533  6533 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-11 11:56:07.575  6533  6533 W VideoCapabilities: Unsupported mime video/wvc1
,09-11 11:56:07.575  6533  6533 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-11 11:56:07.585  6533  6533 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-11 11:56:07.585  6533  6533 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-11 11:56:07.585  1014  1041 D Tethering: interfaceRemoved p2p0
09-11 11:56:07.585  6533  6533 W VideoCapabilities: Unsupported mime video/mp43
,09-11 11:56:07.595  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-11 11:56:07.595  6533  6533 W VideoCapabilities: Unsupported mime video/sorenson
,09-11 11:56:07.605  1948  2122 I art     : Explicit concurrent mark sweep GC freed 52434(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 14MB/24MB, paused 1.668ms total 114.706ms
,09-11 11:56:07.605  6533  6533 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-11 11:56:07.605  1948  2122 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-11 11:56:07.615  1014  6147 I ActivityManager: Killing 5665:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-11 11:56:07.635  6533  6533 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-11 11:56:07.635  1014  1332 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:07.635  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:07.635  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.635  1014  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.635  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:07.635  3577  3577 I Hs20UtilService: Starting #9
,09-11 11:56:07.635  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:07.645  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:07.645  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-11 11:56:07.645  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:07.645  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-11 11:56:07.645  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:07.645  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-11 11:56:07.645  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:07.655  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.655  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.655  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.655  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:07.655  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:07.655  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.655  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.655  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:07.665  3577  3577 I Hs20UtilService: Starting #10
,09-11 11:56:07.665  1014  3132 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-11 11:56:07.665  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:07.665  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.665  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.665  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.665  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.675  6559  6559 E Zygote  : MountEmulatedStorage()
09-11 11:56:07.675  6559  6559 E Zygote  : v2
09-11 11:56:07.675  6559  6559 I libpersona: KNOX_SDCARD checking this for 1000
09-11 11:56:07.675  6559  6559 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:07.675  6559  6559 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:07.675  6559  6559 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:07.675  1014  3132 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6559 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-11 11:56:07.675  6559  6559 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-11 11:56:07.675  1014  1479 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-11 11:56:07.675  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
09-11 11:56:07.685  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.685  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.685  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-11 11:56:07.695  1014  1559 I ActivityManager: Killing 5951:com.sec.pcw.device/1000 (adj 15): empty #31
,09-11 11:56:07.705  6559  6559 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:07.705  6559  6559 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:07.725  1948  2122 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-11 11:56:07.735  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-11 11:56:07.735  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
09-11 11:56:07.735  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
,09-11 11:56:07.745  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:07.755  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.755  1014  6147 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.755  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.755  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.755  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.755  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.765  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.765  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.765  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.765  1014  1137 I ActivityManager: Killing 5966:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-11 11:56:07.765  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.765  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.765  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.775  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.775  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.775  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.775  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.775  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.775  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-11 11:56:07.775  1948  2122 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,09-11 11:56:07.785  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.785  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.785  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.785  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.795  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.795  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.795  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.795  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.805  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:07.805  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:07.805  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-11 11:56:07.805  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:07.805  1014  1560 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:07.815  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-11 11:56:07.815  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.815  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:07.815  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:07.815  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:07.815  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:07.825  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:07.825  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-11 11:56:07.825  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-11 11:56:07.825  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.835  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.835  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.835  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:07.845  6577  6577 E Zygote  : MountEmulatedStorage(),
09-11 11:56:07.845  6577  6577 I libpersona: KNOX_SDCARD checking this for 1002
09-11 11:56:07.845  6577  6577 E Zygote  : v2,
09-11 11:56:07.845  6577  6577 I libpersona: KNOX_SDCARD not a persona,
09-11 11:56:07.845  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:56:07.845  1014  1491 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6577 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-11 11:56:07.845  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:07.855  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:07.875  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:07.875  6577  6577 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:07.885  6577  6577 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-11 11:56:07.885  6577  6577 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-11 11:56:07.915  6577  6577 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding GattService
,09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding HeadsetService
,09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding A2dpService
09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding HidService
09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding HealthService
,09-11 11:56:07.945  6577  6577 D BtSettings.ProfileConfig: Adding PanService
09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding SapService
,09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding SapClientService
,09-11 11:56:07.955  6577  6577 D BtSettings.ProfileConfig: Adding HidDevService
09-11 11:56:07.955  6577  6577 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-11 11:56:07.955  1014  3130 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-11 11:56:07.955  1014  3130 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  3130 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.955  1014  3130 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  3130 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  3130 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  3130 D SettingsProvider: ret = -1
,09-11 11:56:07.955  1014  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-11 11:56:07.955  1014  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.955  1014  1560 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  1560 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  1560 D SettingsProvider: ret = -1
09-11 11:56:07.955  1014  6147 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-11 11:56:07.955  1014  6147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  6147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.955  1014  6147 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  6147 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  6147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  6147 D SettingsProvider: ret = -1
,09-11 11:56:07.955  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
,09-11 11:56:07.955  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.955  1014  1027 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  1027 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:07.955  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  1027 D SettingsProvider: ret = -1
09-11 11:56:07.955  1014  4271 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
09-11 11:56:07.955  1014  4271 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  4271 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.955  1014  4271 D SettingsProvider: selectionArgs: false
,09-11 11:56:07.955  1014  4271 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  4271 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  4271 D SettingsProvider: ret = -1
09-11 11:56:07.955  1014  3132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-11 11:56:07.955  1014  3132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  3132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:07.955  1014  3132 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  3132 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  3132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  3132 D SettingsProvider: ret = -1,
09-11 11:56:07.955  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-11 11:56:07.955  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.955  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:07.955  1014  1137 D SettingsProvider: selectionArgs: false
09-11 11:56:07.955  1014  1137 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.955  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.955  1014  1137 D SettingsProvider: ret = -1
,09-11 11:56:07.965  1014  1332 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-11 11:56:07.965  1014  1332 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.965  1014  1332 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.965  1014  1332 D SettingsProvider: selectionArgs: false
09-11 11:56:07.965  1014  1332 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.965  1014  1332 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.965  1014  1332 D SettingsProvider: ret = -1
09-11 11:56:07.965  1014  3131 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:07.965  1014  3131 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.965  1014  3131 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:07.965  1014  3131 D SettingsProvider: selectionArgs: false
09-11 11:56:07.965  1014  3131 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.965  1014  3131 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.965  1014  3131 D SettingsProvider: ret = -1
09-11 11:56:07.965  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:07.965  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:07.965  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.965  1014  1558 D SettingsProvider: selectionArgs: false,
09-11 11:56:07.965  1014  1558 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.965  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.965  1014  1558 D SettingsProvider: ret = -1
09-11 11:56:07.965  1014  1318 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-11 11:56:07.965  1014  1318 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:07.965  1014  1318 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.965  1014  1318 D SettingsProvider: selectionArgs: false
09-11 11:56:07.965  1014  1318 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.965  1014  1318 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.965  1014  1318 D SettingsProvider: ret = -1
,09-11 11:56:07.965  1014  1559 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-11 11:56:07.965  1014  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:07.965  1014  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:07.965  1014  1559 D SettingsProvider: selectionArgs: false
09-11 11:56:07.965  1014  1559 D SettingsProvider: selectionArgs: 1002
09-11 11:56:07.965  1014  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:07.965  1014  1559 D SettingsProvider: ret = -1
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: android.os.DeadObjectException
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-11 11:56:07.975  6448  6474 E BluetoothAdapter: 	at java.lang.Thread.run(Thread.java:818)
09-11 11:56:07.975  1014  1026 I ActivityManager: Killing 5689:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-11 11:56:07.975  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:07.975  1014  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:07.975  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-11 11:56:07.975  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:07.975  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:07.975  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:07.985  1948  6593 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-11 11:56:07.985  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:07.985  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-11 11:56:07.985  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.985  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.985  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:07.985  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.005  6594  6594 E Zygote  : MountEmulatedStorage()
09-11 11:56:08.005  6594  6594 E Zygote  : v2
09-11 11:56:08.005  6594  6594 I libpersona: KNOX_SDCARD checking this for 1000
09-11 11:56:08.005  6594  6594 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.005  6594  6594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.005  1014  1558 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6594 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
09-11 11:56:08.005  6594  6594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:08.005  1014  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:08.005  6594  6594 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-11 11:56:08.005  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.005  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.005  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:08.025  1014  6147 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:08.025  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:08.025  1014  6147 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:08.025  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:08.025  6594  6594 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.025  6594  6594 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.035  1948  6593 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-11 11:56:08.055  6594  6594 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-11 11:56:08.055  6594  6594 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-11 11:56:08.055  6594  6594 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-11 11:56:08.065  6594  6594 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-11 11:56:08.065  6594  6594 I PCWCLIENTTRACE_PushUtil: sales region : global
09-11 11:56:08.065  6594  6594 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-11 11:56:08.065  6594  6594 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:08.065  1014  1558 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-11 11:56:08.065  1014  1558 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-11 11:56:08.065  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-11 11:56:08.065  6594  6609 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-11 11:56:08.065  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.065  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.065  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.065  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.075  6611  6611 E Zygote  : MountEmulatedStorage(),
09-11 11:56:08.085  6611  6611 E Zygote  : v2
09-11 11:56:08.085  6611  6611 I libpersona: KNOX_SDCARD checking this for 10111
09-11 11:56:08.085  6611  6611 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:08.085  6611  6611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.085  1014  1558 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6611 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-11 11:56:08.085  6611  6611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:08.085  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-11 11:56:08.085  6611  6611 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.085  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.085  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.085  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.085  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.105   312   312 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 21.859ms
09-11 11:56:08.105  6611  6611 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.105  6611  6611 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.115   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 594us total 16.661ms,
,09-11 11:56:08.135   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 16.735ms
,09-11 11:56:08.155  6626  6626 E Zygote  : MountEmulatedStorage(),
09-11 11:56:08.155  6626  6626 E Zygote  : v2,
09-11 11:56:08.155  6626  6626 I libpersona: KNOX_SDCARD checking this for 10009
,09-11 11:56:08.155  6626  6626 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.155  6626  6626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.155  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6626 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:08.155  6626  6626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:08.165  1722  1722 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-11 11:56:08.165  6626  6626 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.185  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-11 11:56:08.185  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.185  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.185  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.185  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.195  6626  6626 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.205  6626  6626 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.215  6641  6641 E Zygote  : MountEmulatedStorage()
,09-11 11:56:08.215  6641  6641 E Zygote  : v2
09-11 11:56:08.215  6641  6641 I libpersona: KNOX_SDCARD checking this for 10145
09-11 11:56:08.215  6641  6641 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:08.215  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6641 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-11 11:56:08.215  6641  6641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.215  6641  6641 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:08.225  6641  6641 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-11 11:56:08.225  1722  1722 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-11 11:56:08.225  1722  1722 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-11 11:56:08.225  1722  1722 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-11 11:56:08.225  1722  1722 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-11 11:56:08.235  1722  1722 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-11 11:56:08.235  1722  1722 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-11 11:56:08.235  1014  1559 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-11 11:56:08.245  1325  1335 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-11 11:56:08.245  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.245  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.245  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.245  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.255  6655  6655 E Zygote  : MountEmulatedStorage()
,09-11 11:56:08.255  6655  6655 I libpersona: KNOX_SDCARD checking this for 10081
09-11 11:56:08.255  6655  6655 E Zygote  : v2
09-11 11:56:08.255  6655  6655 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.265  6655  6655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.265  6655  6655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-11 11:56:08.265  1014  1559 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6655 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-11 11:56:08.275  6655  6655 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.275  6641  6641 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.275  6641  6641 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.285  1722  1722 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-11 11:56:08.295  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.305  6655  6655 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.315  6641  6641 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-11 11:56:08.315  6641  6641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:08.315  6641  6641 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-11 11:56:08.315  6641  6641 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-11 11:56:08.315  6641  6641 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-11 11:56:08.315  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-11 11:56:08.315  6611  6611 I MusicStore: Database version: 108
,09-11 11:56:08.325  1014  1026 I ActivityManager: Killing 5278:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-11 11:56:08.325  3605  3605 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Sep 11 11:56:08 GMT+02:00 2016
,09-11 11:56:08.325  1014  1137 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-11 11:56:08.325  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.325  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.325  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:08.325  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-11 11:56:08.325  3605  3605 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-11 11:56:08.335  3605  3605 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-11 11:56:08.335  3605  3605 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-11 11:56:08.335  1014  1332 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
09-11 11:56:08.335  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.335  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.335  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.335  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.345  6677  6677 E Zygote  : MountEmulatedStorage()
,09-11 11:56:08.355  3605  3605 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-11 11:56:08.355  1014  1332 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6677 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-11 11:56:08.355  1014  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-11 11:56:08.355  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-11 11:56:08.355  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.355  1014  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.355  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.355  3605  6676 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-11 11:56:08.355  6677  6677 E Zygote  : v2
09-11 11:56:08.355  6677  6677 I libpersona: KNOX_SDCARD checking this for 10034
09-11 11:56:08.355  6677  6677 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.355  3605  6676 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-11 11:56:08.355  6677  6677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.365  6677  6677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:08.365  6677  6677 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.365  3605  6676 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-11 11:56:08.375  3605  6676 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-11 11:56:08.375  3605  3605 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-11 11:56:08.385  6677  6677 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.385  6677  6677 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.395  1014  1479 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.405  1014  1332 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.415  6677  6677 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-11 11:56:08.435  6611  6611 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-11 11:56:08.435  6611  6611 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-11 11:56:08.445  3099  6697 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-11 11:56:08.445  1014  3131 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-11 11:56:08.445  5387  5387 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-11 11:56:08.455  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.455  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.455  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.455  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.455  3099  6697 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-11 11:56:08.455  1014  1318 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.455  3099  6697 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-11 11:56:08.465  3099  6697 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-11 11:56:08.465  3099  6697 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-11 11:56:08.465  6701  6701 E Zygote  : MountEmulatedStorage()
09-11 11:56:08.465  6701  6701 I libpersona: KNOX_SDCARD checking this for 10113
09-11 11:56:08.465  6701  6701 E Zygote  : v2
09-11 11:56:08.465  6701  6701 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:08.465  6701  6701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.465  6701  6701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-11 11:56:08.465  1014  3131 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6701 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-11 11:56:08.475  6701  6701 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.475  1014  1558 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-11 11:56:08.475  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
,09-11 11:56:08.475  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.475  1014  1558 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-11 11:56:08.475  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-11 11:56:08.475  6611  6611 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-11 11:56:08.485  1014  1559 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.485  6167  6167 I SA      : [DM] init START
,09-11 11:56:08.495  6167  6167 I SA      : [DM] This device is not a Vodafone
,09-11 11:56:08.495  6701  6701 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.505  6701  6701 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.505  6167  6167 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-11 11:56:08.515  5387  6712 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-11 11:56:08.515  6167  6167 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
09-11 11:56:08.525  6167  6167 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-11 11:56:08.545  6167  6167 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-11 11:56:08.545  6167  6167 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-11 11:56:08.545  6167  6167 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-11 11:56:08.545  6167  6167 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-11 11:56:08.545  6167  6167 I SA      : [SCU] isHaveSA() - false
09-11 11:56:08.545  6167  6167 I SA      : support phone number id : false
09-11 11:56:08.545  6167  6167 I SA      : [DM] Supports Ref Jpn : true
,09-11 11:56:08.545  6167  6167 I SA      : [DM] init END
09-11 11:56:08.545  6167  6167 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-11 11:56:08.555  6611  6611 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-11 11:56:08.555  6611  6611 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f74cce8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-11 11:56:08.555  6611  6611 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-11 11:56:08.555  6611  6611 D AndroidMusic: GMSCore installation verified
09-11 11:56:08.555  6167  6167 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-11 11:56:08.555  6167  6167 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-11 11:56:08.555  6167  6167 I SA      : [SLFUCHKMGR] constructor called
,09-11 11:56:08.565  6167  6167 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-11 11:56:08.565  6167  6167 I SA      : [OR] == isSIMCardReady false ==
,09-11 11:56:08.565  6167  6167 I SA      : [SCU] == networkStateCheck == false
,09-11 11:56:08.565  6167  6167 I SA      : [OR] onReceive END
,09-11 11:56:08.565  1014  1137 I ActivityManager: Killing 5986:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-11 11:56:08.575  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:08.585  1014  3132 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:08.585  1014  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-11 11:56:08.585  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.585  1014  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.585  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.595  6611  6611 I ConfigStore: Config Database version: 1
,09-11 11:56:08.605  6126  6144 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-11 11:56:08.625  1014  3132 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.625  6126  6144 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-11 11:56:08.625  6126  6144 D BadgeProvider: sendNotify, [notify] : null
,09-11 11:56:08.625  6126  6144 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,09-11 11:56:08.625  6126  6144 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-11 11:56:08.625  6126  6144 D BadgeProvider: update, [UpdateCount] : 1
09-11 11:56:08.625  1475  1475 D Launcher.Model: reloadBadges entered.
,09-11 11:56:08.635  1014  1318 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.655  1014  3132 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.655  1014  3130 D RCPManagerService: exchangeData() failure , invalid userId
,09-11 11:56:08.665  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-11 11:56:08.665  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:08.665  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
09-11 11:56:08.665  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:08.665  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-11 11:56:08.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.665  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.685  6727  6727 E Zygote  : MountEmulatedStorage()
,09-11 11:56:08.685  6727  6727 I libpersona: KNOX_SDCARD checking this for 10159
09-11 11:56:08.685  6727  6727 E Zygote  : v2
09-11 11:56:08.685  6727  6727 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.685  1014  1027 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6727 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:08.685  6727  6727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.685  1014  1027 I ActivityManager: Killing 5724:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-11 11:56:08.685  6727  6727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:08.685  6727  6727 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-11 11:56:08.705   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-11 11:56:08.705   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.705  6611  6611 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-11 11:56:08.715  6727  6727 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.715  6727  6727 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.725   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-11 11:56:08.725   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.725  6611  6611 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-11 11:56:08.725   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-11 11:56:08.725   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.725  6611  6611 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-11 11:56:08.735  1014  3130 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-11 11:56:08.735  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.735  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.735  1014  3130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.735  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.755  1014  1560 I ActivityManager: Killing 6019:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-11 11:56:08.755  1014  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:08.765  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.765  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:08.765  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.765  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:08.775  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-11 11:56:08.775  3846  4670 I iu.UploadsManager: num queued entries: 0
,09-11 11:56:08.775  3846  4670 I iu.UploadsManager: num updated entries: 0
,09-11 11:56:08.775  3846  4670 I iu.SyncManager: NEXT; no task
,09-11 11:56:08.785  1014  6147 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:08.785  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-11 11:56:08.785  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:08.785  1014  6147 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.785  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.805  1014  1559 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:08.815  1014  1252 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:08.815  1014  1332 I AudioService: getStreamVolume 3 index 0
,09-11 11:56:08.825  6611  6611 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-11 11:56:08.825   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-11 11:56:08.825   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.825  6701  6745 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
09-11 11:56:08.825  6611  6611 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-11 11:56:08.845   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-11 11:56:08.845   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.845  6701  6745 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-11 11:56:08.855   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-11 11:56:08.855   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.855  6701  6748 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-11 11:56:08.855  1014  6147 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-11 11:56:08.855  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-11 11:56:08.855  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.855  1014  6147 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.855  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.855   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-11 11:56:08.855   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-11 11:56:08.855  1014  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-11 11:56:08.855  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.855  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.855  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.855  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-11 11:56:08.855  6701  6748 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-11 11:56:08.865  1014  4271 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:08.865  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.865  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.865  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.865  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.865  1014  3131 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-11 11:56:08.865  1014  3131 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-11 11:56:08.865  1014  3132 I ActivityManager: Killing 5916:com.samsung.android.sm/1000 (adj 15): empty #31
,09-11 11:56:08.875  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.875  1014  3130 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:08.875  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-11 11:56:08.885  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-11 11:56:08.885  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.885  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.885  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.885  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.895  6752  6752 E Zygote  : MountEmulatedStorage()
09-11 11:56:08.895  6752  6752 I libpersona: KNOX_SDCARD checking this for 10002
09-11 11:56:08.895  6752  6752 E Zygote  : v2
09-11 11:56:08.895  6752  6752 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:08.905  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6752 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:08.905  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:08.905  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:08.905  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-11 11:56:08.925  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:08.935  6752  6752 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:08.935  1014  1332 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-11 11:56:08.935  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
09-11 11:56:08.935  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.935  1014  1332 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:08.935  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-11 11:56:08.935  6611  6611 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-11 11:56:08.945  1014  4271 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-11 11:56:08.945  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-11 11:56:08.945  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:08.945  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:08.945  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:08.965  1014  1137 I ActivityManager: Killing 5932:com.android.mms/u0a46 (adj 15): empty #31
,09-11 11:56:08.995  1014  1479 I ActivityManager: Killing 6115:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-11 11:56:08.995  1014  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-11 11:56:08.995  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:08.995  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.995  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:08.995  1014  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:09.005  6783  6783 E Zygote  : MountEmulatedStorage()
,09-11 11:56:09.005  6783  6783 I libpersona: KNOX_SDCARD checking this for 1000
09-11 11:56:09.005  6783  6783 E Zygote  : v2
09-11 11:56:09.005  6783  6783 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:09.005  6783  6783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:09.005  1014  1479 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-11 11:56:09.015  6783  6783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-11 11:56:09.015  6783  6783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:09.035  1014  3130 D CountryDetector: No listener is left
,09-11 11:56:09.035  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:09.035  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:09.035  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:09.035  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-11 11:56:09.045  6783  6783 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:09.045  6783  6783 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:09.065  6701  6701 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-11 11:56:09.085  6701  6701 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3371-3373)
09-11 11:56:09.085  6701  6701 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-11 11:56:09.085  6701  6701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22daad39}
,09-11 11:56:09.085  6701  6701 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-11 11:56:09.085  6701  6701 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-11 11:56:09.095  6783  6783 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-11 11:56:09.105  1014  1558 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-11 11:56:09.105  6701  6701 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-11 11:56:09.105  1014  1558 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-11 11:56:09.115  1014  1558 D SecContentProvider2: mCursor = null
,09-11 11:56:09.115  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-11 11:56:09.115  1014  1558 D WifiService: setWifiEnabled: true pid=6348, uid=10155
09-11 11:56:09.115  1014  1558 W ActivityManager: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-11 11:56:09.115  6701  6701 E SysUtils: ApplicationContext is null in ApplicationStatus
09-11 11:56:09.115  1014  1558 W WifiService: Failed getting userId using ActivityManagerNative
09-11 11:56:09.115  1014  1558 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:09.115  1014  1558 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-11 11:56:09.115  1014  1558 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-11 11:56:09.115  1014  1558 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-11 11:56:09.115  1014  1558 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-11 11:56:09.115  1014  1558 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-11 11:56:09.115  1014  1558 D SettingsProvider: name = wifi_on
,09-11 11:56:09.115  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-11 11:56:09.135  6701  6701 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-11 11:56:09.135  6701  6701 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-11 11:56:09.135  6701  6701 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-11 11:56:09.145  6701  6701 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-11 11:56:09.145  6701  6701 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-11 11:56:09.145  6701  6701 I Adreno-EGL: Build Date: 04/06/15 Mon
09-11 11:56:09.145  6701  6701 I Adreno-EGL: Local Branch: 
09-11 11:56:09.145  6701  6701 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-11 11:56:09.145  6701  6701 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-11 11:56:09.145  6701  6701 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-11 11:56:09.225  6783  6783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-11 11:56:09.235  6783  6783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-11 11:56:09.235  6783  6783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:09.235  6783  6783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-11 11:56:09.235  6783  6783 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-11 11:56:09.235  6783  6783 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-11 11:56:09.325  6701  6815 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-11 11:56:09.335  6701  6701 I NSApplication: Starting up...
,09-11 11:56:09.345  1014  3131 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-11 11:56:09.345  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:09.345  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:09.345  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:09.345  1014  3131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:09.365  6823  6823 E Zygote  : MountEmulatedStorage()
09-11 11:56:09.365  6823  6823 I libpersona: KNOX_SDCARD checking this for 10120
09-11 11:56:09.365  6823  6823 E Zygote  : v2
09-11 11:56:09.365  6823  6823 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:09.365  6823  6823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:09.365  1014  3131 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6823 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
09-11 11:56:09.365  6823  6823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:09.365  1014  3131 I ActivityManager: Killing 6152:com.wsomacp/u0a25 (adj 15): empty #31
,09-11 11:56:09.365  1014  3131 I ActivityManager: Killing 6004:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #32
09-11 11:56:09.365  6823  6823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-11 11:56:09.395  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:09.395  6823  6823 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:09.415  6823  6823 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:56:09.465  1014  1041 D Tethering: interfaceAdded wlan0
,09-11 11:56:09.475  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-11 11:56:09.475  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:09.475  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:09.485  1014  1128 E Tethering: No numeric data
,09-11 11:56:09.485  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:09.485  1014  1128 D Tethering: clearTetheredNotification()
09-11 11:56:09.485  1014  1128 D Tethering: InitialState.processMessage what=4
,09-11 11:56:09.485  1014  1041 D Tethering: interfaceAdded p2p0
,09-11 11:56:09.485  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:09.485  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-11 11:56:09.495  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:09.495  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:09.495  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:09.495  1014  1128 E Tethering: No numeric data
09-11 11:56:09.495   277  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-11 11:56:09.495  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:09.495   277  1002 D SoftapController: Softap fwReload - Ok
09-11 11:56:09.495  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-11 11:56:09.505  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:09.505  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:09.505  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:09.505   277  1002 D CommandListener: Setting iface cfg
09-11 11:56:09.505   277  1002 D CommandListener: Trying to bring down wlan0
,09-11 11:56:09.505   277  1002 D CommandListener: Clearing all IP addresses on wlan0
,09-11 11:56:09.505  1014  1122 V NetworkStats: performPollLocked() took 15ms
09-11 11:56:09.505  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:09.505  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:09.505  1014  1128 D Tethering: clearTetheredNotification()
,09-11 11:56:09.515  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:09.515  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:09.515  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-11 11:56:09.515  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:09.515  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-11 11:56:09.515  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:09.515  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:09.515  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:09.515  1014  1122 V NetworkStats: performPollLocked() took 5ms,
,09-11 11:56:09.515  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:09.515  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:09.515  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-11 11:56:09.535  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-11 11:56:09.535  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-11 11:56:09.535  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:09.535  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:09.535  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-11 11:56:09.535  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:09.535  1171  1171 D HotspotTile: onReceive : 2, 0
09-11 11:56:09.535  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:09.535  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:09.535  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:09.535  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:09.535  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:09.535  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-11 11:56:09.535  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:09.535  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:09.535  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:09.565  6841  6841 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-11 11:56:09.565  6841  6841 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-11 11:56:09.565  6841  6841 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-11 11:56:09.585  6841  6841 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-11 11:56:09.585   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6841
,09-11 11:56:09.585   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-11 11:56:09.585  6841  6841 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-11 11:56:09.585  6841  6841 I wpa_supplicant: ssSupport state is = 1
,09-11 11:56:09.585  6841  6841 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-11 11:56:09.585  6841  6841 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-11 11:56:09.585   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6841
09-11 11:56:09.585   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-11 11:56:09.705   290   290 E SMD     : DCD OFF
,09-11 11:56:09.745  1014  1332 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-11 11:56:09.745  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:09.745  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:09.745  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:09.745  1014  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:09.755   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-11 11:56:09.765  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-11 11:56:09.765  6847  6847 E Zygote  : MountEmulatedStorage()
09-11 11:56:09.765  6847  6847 I libpersona: KNOX_SDCARD checking this for 10125
09-11 11:56:09.765  6847  6847 E Zygote  : v2
09-11 11:56:09.765  6847  6847 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:09.765  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:09.775  1014  1332 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6847 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-11 11:56:09.775  1014  1332 I ActivityManager: Killing 6193:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31,
,09-11 11:56:09.775  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:09.775  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:09.795  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:09.795  6847  6847 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:09.815  6847  6847 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:09.815  6847  6847 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-11 11:56:09.815  6847  6847 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-11 11:56:09.825  6847  6847 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
09-11 11:56:09.825  6847  6847 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-11 11:56:09.835  6841  6841 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-11 11:56:09.835  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
09-11 11:56:09.835  6847  6847 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-11 11:56:09.835  1014  1318 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-11 11:56:09.835  1014  1318 I ActivityManager: Killing 6221:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-11 11:56:09.835  1014  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:09.835  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:09.835  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:09.835  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:09.835  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:09.835  3577  3577 I Hs20UtilService: Starting #11
,09-11 11:56:09.845  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
09-11 11:56:09.845   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6841
09-11 11:56:09.845   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-11 11:56:09.845  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-11 11:56:09.845  6841  6841 I wpa_supplicant: ssSupport state is = 1
09-11 11:56:09.845  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-11 11:56:09.845  6841  6841 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:09.845  6841  6841 E wpa_supplicant: SIM READ ERROR
09-11 11:56:09.845  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:09.845  6841  6841 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:09.845  6841  6841 E wpa_supplicant: SIM READ ERROR
09-11 11:56:09.845  6841  6841 I wpa_supplicant: Blacklist: Clear (all) 
09-11 11:56:09.845  3577  3602 I Hs20UtilService: Message received 5011
09-11 11:56:09.845  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-11 11:56:09.845  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:09.845  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1,
09-11 11:56:09.845  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-11 11:56:09.845  6841  6841 I wpa_supplicant: wpa_default_ap_write_once
09-11 11:56:09.845  6841  6841 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-11 11:56:09.845  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:09.845  6841  6841 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-11 11:56:09.845  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:09.845  6841  6841 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-11 11:56:09.845  6841  6841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-11 11:56:09.845  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:09.845  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:09.845  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:09.855  1014  1332 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:09.855  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:09.855  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:09.855  1014  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:09.855  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:09.865  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-11 11:56:09.865  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:09.865  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
,09-11 11:56:09.865  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:09.865  3577  3577 I Hs20UtilService: Starting #12
,09-11 11:56:09.865  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:09.945  1014  1558 I art     : Explicit concurrent mark sweep GC freed 30304(1870KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.395ms total 143.948ms
,09-11 11:56:09.965  1948  2122 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-11 11:56:09.965  1948  2122 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-11 11:56:09.985  6841  6841 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-11 11:56:10.175  6841  6841 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-11 11:56:10.175  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-11 11:56:10.185  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-11 11:56:10.195   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6841,
09-11 11:56:10.195   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-11 11:56:10.195  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-11 11:56:10.195  6841  6841 I wpa_supplicant: ssSupport state is = 1
09-11 11:56:10.195  6841  6841 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-11 11:56:10.195  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-11 11:56:10.205  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-11 11:56:10.205   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6841
09-11 11:56:10.205   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-11 11:56:10.205  6841  6841 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-11 11:56:10.205  6841  6841 I wpa_supplicant: ssSupport state is = 1
09-11 11:56:10.205  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-11 11:56:10.205  6841  6841 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:10.205  6841  6841 E wpa_supplicant: SIM READ ERROR
09-11 11:56:10.205  6841  6841 I wpa_supplicant: wpa_default_ap_write_once
09-11 11:56:10.205  6841  6841 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-11 11:56:10.205  6841  6841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-11 11:56:10.215  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:10.215  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:10.215  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:10.215  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-11 11:56:10.215  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:10.215  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:10.345  6841  6841 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-11 11:56:10.345  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-11 11:56:10.425  6841  6841 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-11 11:56:10.425  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-11 11:56:10.425  6841  6841 I wpa_supplicant: Skip scan - bUseNetwork false
,09-11 11:56:10.435  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-11 11:56:10.435  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-11 11:56:10.435  6841  6841 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-11 11:56:10.435  6841  6841 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:10.435  6841  6841 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:10.435  6841  6841 E wpa_supplicant: SIM READ ERROR
09-11 11:56:10.435  6841  6841 I wpa_supplicant: Blacklist: Clear (all) 
,09-11 11:56:10.455  6841  6841 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-11 11:56:10.465  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210],
09-11 11:56:10.465  6841  6841 I wpa_supplicant: Skip scan - bUseNetwork false
09-11 11:56:10.465  1014  1125 D WifiConfigStore: Loading config and enabling all networks ,
,09-11 11:56:10.475  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-11 11:56:10.475  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:10.475  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:10.475  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:10.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:10.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:10.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:10.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:10.475  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:10.475  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:10.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:10.475  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-11 11:56:10.475  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:10.475  1171  1171 D HotspotTile: onReceive : 3, 0
,09-11 11:56:10.485  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:10.485  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.485  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:10.485  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.485  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:10.495  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:10.495  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:10.495  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:10.495  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:10.495  1014  3132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:10.495  1014  3132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:10.495  1014  1125 E WifiConfigStore: Not a HS20
,09-11 11:56:10.495  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:10.495  1014  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:10.495  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-11 11:56:10.495  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-11 11:56:10.495  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-11 11:56:10.495  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-11 11:56:10.495  6841  6841 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-11 11:56:10.495  6841  6841 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-11 11:56:10.505  3577  3577 I Hs20UtilService: Starting #13
,09-11 11:56:10.505  6841  6841 I wpa_supplicant: reset timer : RESET_TIMER 0
09-11 11:56:10.505  6841  6841 I wpa_supplicant: P2P: Current p2p state = IDLE
09-11 11:56:10.505  6841  6841 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-11 11:56:10.505  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-11 11:56:10.505  6841  6841 I wpa_supplicant: First Scan Start
09-11 11:56:10.505  6841  6841 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-11 11:56:10.505  3577  3602 I Hs20UtilService: Message received 5011
09-11 11:56:10.505  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-11 11:56:10.505  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:10.505  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-11 11:56:10.505  1014  1125 I WifiNative-HAL: startHal
09-11 11:56:10.505  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:10.505  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
09-11 11:56:10.505  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ca4388c
09-11 11:56:10.505  1014  1125 I WifiNative-HAL: Could not start hal
09-11 11:56:10.505  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:10.505  6533  6533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:10.505  1014  1125 E WifiNative-wlan0: do suspend true
,09-11 11:56:10.505  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-11 11:56:10.505  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-11 11:56:10.515   277  1002 D CommandListener: Setting iface cfg
09-11 11:56:10.515   277  1002 D CommandListener: Trying to bring up p2p0
,09-11 11:56:10.515  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-11 11:56:10.515  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.515  1014  1148 I WifiNative-HAL: startHal
09-11 11:56:10.515  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ddfd9bc
09-11 11:56:10.515  1014  1148 I WifiNative-HAL: Could not start hal
09-11 11:56:10.515  1014  1148 E WifiScanningService: could not start HAL
,09-11 11:56:10.515  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
09-11 11:56:10.515  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-11 11:56:10.515  1014  1124 D WifiP2pService: P2pEnablingState
09-11 11:56:10.515  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-11 11:56:10.515  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-11 11:56:10.515  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-11 11:56:10.515  1014  1124 D WifiP2pService: P2p socket connection successful
,09-11 11:56:10.515  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-11 11:56:10.515  1014  1124 D WifiP2pService: P2pEnabledState
09-11 11:56:10.515  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:10.515  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-11 11:56:10.515  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:10.515  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-11 11:56:10.515  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-11 11:56:10.515  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:10.515  6841  6841 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-11 11:56:10.515  1014  1044 D WifiDisplayController: disconnect
,09-11 11:56:10.525  1014  1044 D WifiDisplayController: updateConnection
09-11 11:56:10.525  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-11 11:56:10.525  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:10.525  6841  6841 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-11 11:56:10.525  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,09-11 11:56:10.525  6841  6841 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-11 11:56:10.525  1014  3131 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:10.525  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-11 11:56:10.525  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-11 11:56:10.525  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:10.535  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-11 11:56:10.525  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-11 11:56:10.535  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-11 11:56:10.525  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-11 11:56:10.535  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-11 11:56:10.535  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-11 11:56:10.535  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-11 11:56:10.535  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:10.535  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:10.535  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:10.535  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-11 11:56:10.535  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac,
09-11 11:56:10.535  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:10.535  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-11 11:56:10.535  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:10.535  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  secondary type: null
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  wps: 0
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  grpcapab: 0
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  devcapab: 0
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  status: 3
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  wfdInfo: null
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-11 11:56:10.535  1014  1044 D WifiDisplayController:  SConnectInfo : null
09-11 11:56:10.535  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:10.535  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-11 11:56:10.535  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:10.535  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:10.545  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:10.545  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-11 11:56:10.545  6492  6492 D FileShare-Client: Outbound.stopDelayTimer - 
,09-11 11:56:10.555  6517  6517 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:10.565  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-11 11:56:10.565  1014  1124 D WifiP2pService: InactiveState
09-11 11:56:10.565  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-11 11:56:10.565  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-11 11:56:10.565  6841  6841 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-11 11:56:10.565  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-11 11:56:10.565  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-11 11:56:11.735  6841  6841 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
,09-11 11:56:11.745  6841  6841 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-11 11:56:11.745  6841  6841 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-11 11:56:11.745  6841  6841 I wpa_supplicant: Trying to associate with  'G700'
09-11 11:56:11.745  6841  6841 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-11 11:56:11.745  1014  6865 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-11 11:56:11.745  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-11 11:56:11.765  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-11 11:56:11.765  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:11.885  6841  6841 E wpa_supplicant: Cmd 35605 not handled
09-11 11:56:11.885  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:11.885  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:11.885  6841  6841 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:11.885  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:11.885  6841  6841 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-11 11:56:11.885  6841  6841 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-11 11:56:11.885  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-11 11:56:11.885  6841  6841 I wpa_supplicant: Associated with F4.99.3E
09-11 11:56:11.885  6841  6841 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:11.885  6841  6841 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-11 11:56:11.885  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:11.885  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:11.885  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:11.885  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:11.895  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-11 11:56:11.895  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-11 11:56:11.895  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-11 11:56:11.895  1014  1128 E Tethering: No numeric data
,09-11 11:56:11.895  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:11.895  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:11.895  6841  6841 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:11.895  6841  6841 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-11 11:56:11.895  6841  6841 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-11 11:56:11.895  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:11.895  1014  1128 D Tethering: clearTetheredNotification()
09-11 11:56:11.895  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-11 11:56:11.895  6841  6841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:11.895  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-11 11:56:11.895  6841  6841 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-11 11:56:11.895  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:11.895  6841  6841 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-11 11:56:11.895  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:11.895  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:11.895  6841  6841 I wpa_supplicant: Blacklist: Clear (temp) 
09-11 11:56:11.895  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:11.895  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-11 11:56:11.895  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-11 11:56:11.895  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:11.905  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:11.905  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:11.905  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:11.905  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:11.905  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-11 11:56:11.905  1014  1122 V NetworkStats: performPollLocked() took 5ms
,09-11 11:56:11.905  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:11.905  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:11.905  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-11 11:56:11.905  1014  1560 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-11 11:56:11.905  1014  1560 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-11 11:56:11.905  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
09-11 11:56:11.905  1014  1560 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-11 11:56:11.905  1014  1560 D BatteryService: stay LED for charging
09-11 11:56:11.905  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-11 11:56:11.915  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:11.915  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:11.915  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:11.915  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:11.915  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:11.915  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:11.915  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-11 11:56:11.925  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-11 11:56:11.925  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:11.925  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-11 11:56:11.925  1014  1014 I MotionRecognitionService: Plugged
,09-11 11:56:11.925  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-11 11:56:11.925  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-11 11:56:11.925  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-11 11:56:11.925  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-11 11:56:11.925  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-11 11:56:11.945  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:11.945  1014  1559 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:11.945  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:11.945  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:11.945  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:11.945  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:11.955  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:11.955  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:11.955  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-11 11:56:11.955  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:11.955  3577  3577 I Hs20UtilService: Starting #14
,09-11 11:56:11.955  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:11.955  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:11.955  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-11 11:56:11.955  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:11.965  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:11.965  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:11.965  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:11.965  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:11.965   277  1002 D CommandListener: Setting iface cfg
,09-11 11:56:11.975  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-11 11:56:11.975  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-11 11:56:11.975  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:11.985  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-11 11:56:11.985  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-11 11:56:11.985  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:11.985  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:11.985  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:11.985  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:11.985  1014  1125 E WifiNative-wlan0: do suspend false
,09-11 11:56:11.995  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-11 11:56:11.995  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-11 11:56:11.995  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:11.995  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:12.125  1014  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-11 11:56:12.125  1014  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-11 11:56:12.125  1014  1491 D SecContentProvider2: mCursor = null
,09-11 11:56:12.125  1014  1491 D WifiService: setWifiEnabled: false pid=6348, uid=10155
,09-11 11:56:12.125  1014  1491 D SettingsProvider: name = wifi_on
,09-11 11:56:12.145  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:12.155  1014  1125 E WifiNative-wlan0: do suspend true,
,09-11 11:56:12.175  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-11 11:56:12.175  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-11 11:56:12.175  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:12.175  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-11 11:56:12.185  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:12.185  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:12.185  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:12.185  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.185  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:12.185   277  1002 D CommandListener: Clearing all IP addresses on wlan0
09-11 11:56:12.185  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-11 11:56:12.185  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:12.185  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-11 11:56:12.185  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:12.185  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-11 11:56:12.185  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-11 11:56:12.185  1014  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-11 11:56:12.185   277  1002 E Netd    : no such netId 503
09-11 11:56:12.185  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-11 11:56:12.185  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-11 11:56:12.185  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-11 11:56:12.185  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
,09-11 11:56:12.185  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-11 11:56:12.185  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-11 11:56:12.195  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-11 11:56:12.185  1014  6869 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:12.185  1014  6869 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-11 11:56:12.195  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:12.195  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:12.195  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-11 11:56:12.195  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:12.195  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.195  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.195  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.195  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-11 11:56:12.195  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:12.205  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-11 11:56:12.205  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-11 11:56:12.205  1014  1039 I ActivityManager: Killing 6242:com.samsung.helphub/1000 (adj 15): empty #31
,09-11 11:56:12.205  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-11 11:56:12.205  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:12.205  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-11 11:56:12.205  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-11 11:56:12.205  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:12.205  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-11 11:56:12.205  1014  1318 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:12.215  6874  6874 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-11 11:56:12.205  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:12.215  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:12.215  1014  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:12.215  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:12.215  1014  1124 D WifiP2pService: P2pDisablingState
,09-11 11:56:12.215  3577  3577 I Hs20UtilService: Starting #15
09-11 11:56:12.215  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-11 11:56:12.215  1014  1124 D WifiP2pService: p2p socket connection lost
09-11 11:56:12.215  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-11 11:56:12.215  1014  1125 E WifiNative-wlan0: do suspend true
09-11 11:56:12.215  3577  3602 I Hs20UtilService: Message received 5007
09-11 11:56:12.215  1014  1124 D WifiP2pService: P2pDisabledState
,09-11 11:56:12.215  6874  6874 I dhcpcd  : version 5.5.6 starting
09-11 11:56:12.215  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-11 11:56:12.215  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:12.215  1014  1044 D WifiDisplayController: disconnect
09-11 11:56:12.215  1014  1044 D WifiDisplayController: updateConnection
09-11 11:56:12.215  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-11 11:56:12.215  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:12.215  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:12.215  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-11 11:56:12.225  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:12.225  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-11 11:56:12.225  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:12.225  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-11 11:56:12.225  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-11 11:56:12.225  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-11 11:56:12.225  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:12.225  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:12.225  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-11 11:56:12.225  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-11 11:56:12.225  1014  1252 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:12.225  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-11 11:56:12.235  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-11 11:56:12.235  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-11 11:56:12.235  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:12.235  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:12.235  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:12.235  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-11 11:56:12.235  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:12.235  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:12.235  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-11 11:56:12.235  6492  6492 D FileShare-Client: Outbound.stopDelayTimer - 
,09-11 11:56:12.245  6517  6517 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:12.245  6874  6874 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-11 11:56:12.245  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-11 11:56:12.245  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-11 11:56:12.255   277  1002 D CommandListener: Clearing all IP addresses on wlan0,
,09-11 11:56:12.255  6841  6841 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-11 11:56:12.255  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:12.255  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:12.255  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.255  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.255  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.255  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-11 11:56:12.265  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-11 11:56:12.265  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-11 11:56:12.265  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:12.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:12.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:12.275  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-11 11:56:12.275  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:12.285  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:12.285  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-11 11:56:12.285  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.285  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.285  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.285  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.285  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:12.285  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-11 11:56:12.285  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:12.285  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-11 11:56:12.285  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:12.295  1171  1171 D HotspotTile: onReceive : 0, 0
,09-11 11:56:12.295  1014  1558 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:12.295  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:12.295  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.295  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:12.295  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:12.295  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:12.295  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:12.295  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.295  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:12.305  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.305  3577  3577 I Hs20UtilService: Starting #16
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:12.305  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:12.305  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:12.305  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:12.305  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:12.305  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:12.305  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-11 11:56:12.305  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:12.305  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:12.305  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:12.305  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-11 11:56:12.305  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:12.315  6874  6874 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-11 11:56:12.315  6874  6874 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-11 11:56:12.315  6874  6874 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-11 11:56:12.315  6874  6874 I dhcpcd  : bssid match,
09-11 11:56:12.315  6874  6874 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-11 11:56:12.315  1014  3132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:12.315  1014  3132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:12.315  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:12.325  1014  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:12.325  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:12.325  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-11 11:56:12.325  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:12.325  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
,09-11 11:56:12.325  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:12.325  3577  3577 I Hs20UtilService: Starting #17
,09-11 11:56:12.325  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:12.365  6841  6841 I wpa_supplicant: Blacklist: Clear (all) 
,09-11 11:56:12.385  6874  6874 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-11 11:56:12.435  6874  6874 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-11 11:56:12.435  6841  6841 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-11 11:56:12.435  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-11 11:56:12.435  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:12.435  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:12.455  6841  6841 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-11 11:56:12.465  6841  6841 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
09-11 11:56:12.465  6841  6841 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-11 11:56:12.465  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.465  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.465  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-11 11:56:12.465  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:12.465  1014  1128 D Tethering: InitialState.processMessage what=4
,09-11 11:56:12.465  6841  6841 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:12.465  6841  6841 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-11 11:56:12.475  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.475  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.475  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:12.475  1014  1128 E Tethering: No numeric data
09-11 11:56:12.475  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-11 11:56:12.475  1014  1128 D Tethering: clearTetheredNotification()
,09-11 11:56:12.475  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-11 11:56:12.475  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:12.475  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.475  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.475  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:12.475  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-11 11:56:12.485  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-11 11:56:12.485  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:12.485  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:12.485  1014  1122 V NetworkStats: performPollLocked() took 9ms
09-11 11:56:12.485  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:12.495  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:12.495  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:12.675  6841  6841 I wpa_supplicant: Blacklist: Clear (all) ,
,09-11 11:56:12.685  1014  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-11 11:56:12.715   290   290 E SMD     : DCD OFF,
,09-11 11:56:12.775  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-11 11:56:12.775  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.775  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:12.775  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:12.775  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-11 11:56:12.775  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:12.785  6841  6841 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-11 11:56:12.885  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-11 11:56:12.885  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-11 11:56:12.885  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-11 11:56:12.895  6533  6533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:12.905  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:12.905  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-11 11:56:12.905  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.905  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.905  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:12.905  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:12.905  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:12.905  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-11 11:56:12.915  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:12.915  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:12.915  1948  2121 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-11 11:56:12.915  1171  1171 D HotspotTile: onReceive : 1, 0
,09-11 11:56:12.915  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:12.925  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:12.925  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:12.925  1014  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-11 11:56:12.925  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:12.925  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:12.925  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:12.925  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:12.935  3577  3577 I Hs20UtilService: Starting #18
,09-11 11:56:12.935  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:12.935  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-11 11:56:12.935  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:12.935  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
09-11 11:56:12.935  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:13.365   277   996 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-11 11:56:13.365  1014  1041 D Tethering: interfaceRemoved wlan0
09-11 11:56:13.365  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-11 11:56:13.705  1014  1041 D Tethering: interfaceRemoved p2p0
,09-11 11:56:13.705  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-11 11:56:13.815  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:13.815  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:13.815  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.825  1014  1318 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-11 11:56:13.825  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-11 11:56:13.825  1014  1318 W ActivityManager: userId = 0, bbcId = -10000,
,09-11 11:56:13.825  1014  1318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:13.825  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.835  1014  1332 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
09-11 11:56:13.835  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-11 11:56:13.845  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:13.845  1014  1332 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:13.845  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-11 11:56:13.855  6701  6746 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-11 11:56:13.855  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:13.855  1014  3130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:13.855  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.865  1014  3131 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:13.865  1014  3131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-11 11:56:13.865  1014  3131 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:13.865  1014  3131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:13.865  1014  3131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.865  1014  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:13.875  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-11 11:56:13.875  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:13.875  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:13.875  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.875  1014  4271 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:13.875  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-11 11:56:13.875  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:13.875  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:13.875  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.895  1014  1559 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-11 11:56:13.895  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-11 11:56:13.895  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:13.895  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:13.895  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.915  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:13.925  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:13.925  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:13.925  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-11 11:56:13.925  1948  1948 D WearableService: callingUid 10012, callindPid: 1948
,09-11 11:56:13.965  1014  4271 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-11 11:56:13.965  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-11 11:56:13.965  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:13.965  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:13.965  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-11 11:56:13.985  6611  6904 I MusicLeanback: Conditions not met for autocaching.
,09-11 11:56:13.985  6611  6904 I MusicLeanback: Stop autocaching.
,09-11 11:56:13.995  6611  6611 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-11 11:56:13.995  6611  6909 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-11 11:56:14.005  1014  1307 E Watchdog: !@Sync 4
,09-11 11:56:14.385  1014  1093 V AlarmManager: waitForAlarm result :4
,09-11 11:56:14.385  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-11 11:56:14.395  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-11 11:56:14.395  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
09-11 11:56:14.395  1171  1171 D KeyguardUpdateMonitor: handleTimeUpdate
09-11 11:56:14.395  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-11 11:56:14.415  1171  1171 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-11 11:56:14.415  1171  1171 D SecKeyguardClockView: HomeTimezone(): 1
,09-11 11:56:14.425  1171  1171 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-11 11:56:14.425  1171  1171 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-11 11:56:14.425  1171  1171 I KeyguardEffectViewController: *** don't update sliding image ***
,09-11 11:56:14.465  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-11 11:56:14.465  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-11 11:56:14.465  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,09-11 11:56:14.475  1171  1171 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-11 11:56:14.485  1171  1171 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-11 11:56:14.705   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:56:15.145  6348  6401 D BluetoothAdapter: enable()
,09-11 11:56:15.145  1014  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-11 11:56:15.145  1014  1491 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-11 11:56:15.145  1014  1491 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-11 11:56:15.145  1014  1491 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-11 11:56:15.145  1014  1491 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:15.145  1014  1491 D SettingsProvider: name = bluetooth_on
,09-11 11:56:15.155  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-11 11:56:15.155  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:15.155  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-11 11:56:15.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-11 11:56:15.185  6577  6577 D BluetoothAdapterState: make
,09-11 11:56:15.185  6577  6577 I bluedroid: init
,09-11 11:56:15.195  6577  6577 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-11 11:56:15.195  6577  6912 I BluetoothAdapterState: Entering OffState
,09-11 11:56:15.195  6577  6577 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-11 11:56:15.195  6577  6577 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:15.195  6577  6577 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-11 11:56:15.195  6577  6577 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-11 11:56:15.195  6577  6577 I bluedroid: get_profile_interface socket
09-11 11:56:15.195  6577  6577 I bluedroid: get_profile_interface map_client
,09-11 11:56:15.195  6577  6915 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-11 11:56:15.195  6577  6577 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-11 11:56:15.205  6577  6915 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-11 11:56:15.205  6577  6915 E BluetoothServiceJni: populateRssiValuesNative
09-11 11:56:15.205  6577  6915 I bluedroid: getModelRssiValues
09-11 11:56:15.205  6577  6577 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-11 11:56:15.205  6577  6915 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-11 11:56:15.205  6577  6915 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-11 11:56:15.205  1014  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-11 11:56:15.205  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.205  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.205  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.205  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.205  6577  6915 D BluetoothAdapterProperties: Name is: A5-1
,09-11 11:56:15.205  1014  1014 D SettingsProvider: name = bluetooth_name
,09-11 11:56:15.205  6577  6585 I bluedroid: config_hci_snoop_log
09-11 11:56:15.215  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-11 11:56:15.215  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-11 11:56:15.215  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
09-11 11:56:15.215  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-11 11:56:15.215  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-11 11:56:15.215  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:15.215  6577  6577 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-11 11:56:15.215  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:15.225  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-11 11:56:15.225  6577  6912 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-11 11:56:15.225  6577  6912 D BluetoothAdapterProperties: Setting state to 11
09-11 11:56:15.225  6577  6912 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-11 11:56:15.225  6577  6912 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:15.225  6577  6912 D BluetoothAdapterService: updateAdapterState state is 11
,09-11 11:56:15.225  6577  6912 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:15.225  6577  6912 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-11 11:56:15.235  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:15.235  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-11 11:56:15.235  6577  6912 D BluetoothSecureManager: getInstant: null
09-11 11:56:15.235  6577  6912 D BluetoothSecureManager: calling getMethod for getService
09-11 11:56:15.235  6577  6912 D BluetoothSecureManager: calling getService
,09-11 11:56:15.235  6577  6912 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@686183b
09-11 11:56:15.235  1014  1318 D BluetoothSecureManagerService: isSecureModeEnabled
09-11 11:56:15.235  1014  1318 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-11 11:56:15.235  6577  6912 D BtConfig.SecureMode: isSecureModeOn:false
09-11 11:56:15.235  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-11 11:56:15.235  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-11 11:56:15.235  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:15.235  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-11 11:56:15.235  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:15.235  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-11 11:56:15.235  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService,
09-11 11:56:15.245  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-11 11:56:15.245  1171  1171 D BluetoothTile:  getBluetoothState : 11
09-11 11:56:15.245  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:15.245  1819  1819 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-11 11:56:15.245  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-11 11:56:15.245  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-11 11:56:15.245  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:15.245  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-11 11:56:15.245  6577  6912 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-11 11:56:15.245  6577  6912 D BluetoothBondStateMachine: make
,09-11 11:56:15.245  1014  4271 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-11 11:56:15.245  1014  3130 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:15.245  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-11 11:56:15.245  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-11 11:56:15.255  1014  1318 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-11 11:56:15.255  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-11 11:56:15.255  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.255  1014  3130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:15.255  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.255  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:15.255  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-11 11:56:15.255  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-11 11:56:15.255  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:15.255  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-11 11:56:15.255  6577  6916 I BluetoothBondStateMachine: StableState(): Entering Off State
09-11 11:56:15.255  1014  3131 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:15.255  1014  3131 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.255  1014  3131 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.255  1014  3131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.255  1014  3131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:15.255  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-11 11:56:15.255  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-11 11:56:15.255  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:15.255  6577  6577 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:15.265  6577  6577 D BtGatt.GattService: Received start request. Starting profile...
09-11 11:56:15.265  6577  6577 D BtGatt.GattService: start()
09-11 11:56:15.265  6577  6577 D BtGatt.GattService: start()
09-11 11:56:15.265  6577  6577 I bluedroid: get_profile_interface gatt
,09-11 11:56:15.265  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:15.265  6577  6577 D BtGatt.AdvertiseManager: advertise manager created
,09-11 11:56:15.265  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:15.265  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:15.265  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.265  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.265  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.265  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.275  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-11 11:56:15.275  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-11 11:56:15.275  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:15.275  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:15.275  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-11 11:56:15.275  1014  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:15.275  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.275  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.275  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:15.275  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.275  6577  6577 D BtGatt.GattService: mStartError = false
09-11 11:56:15.275  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:15.285  6577  6577 D HeadsetService: Received start request. Starting profile...
09-11 11:56:15.285  6577  6577 D HeadsetService: start()
,09-11 11:56:15.285  6577  6577 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-11 11:56:15.285  6577  6577 D HeadsetStateMachine: make
,09-11 11:56:15.285  6577  6577 E HeadsetStateMachine: # of Max HF connection is 2
,09-11 11:56:15.295  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-11 11:56:15.295  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-11 11:56:15.295  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-11 11:56:15.295  1014  1559 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-11 11:56:15.295  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.295  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.295  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.295  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-11 11:56:15.295  1014  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:15.295  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.295  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:15.295  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.295  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.305  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-11 11:56:15.305  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-11 11:56:15.305  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-11 11:56:15.305  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:15.305  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.305  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.305  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.305  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.305  1014  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-11 11:56:15.305  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-11 11:56:15.305  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-11 11:56:15.305  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.305  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.305  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-11 11:56:15.305  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-11 11:56:15.305  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-11 11:56:15.305  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:15.305  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.305  6577  6577 I bluedroid: get_profile_interface handsfree
,09-11 11:56:15.315  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.315  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.315  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.315  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:15.315  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:15.315  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:15.315  1014  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:15.315  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.325  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.325  1014  1318 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.325  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.325  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-11 11:56:15.325  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-11 11:56:15.325  6577  6912 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-11 11:56:15.335  1014  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:15.335  1014  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-11 11:56:15.335  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:15.335  1014  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:15.335  6577  6577 I DualScoManager: Instantiating Dual Sco Manager
09-11 11:56:15.335  6577  6577 I DualScoManager: Set HeadsetServiceHelper
09-11 11:56:15.335  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:15.335  6577  6577 D BluetoothAtMessage: createCMTIContentObservers
,09-11 11:56:15.335  1014  6147 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:15.335  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:15.335  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-11 11:56:15.335  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-11 11:56:15.335  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-11 11:56:15.335  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-11 11:56:15.335  6577  6912 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-11 11:56:15.335  1014  6147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:15.335  1014  6147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:15.335  1014  6147 D SettingsProvider: selectionArgs: false
09-11 11:56:15.335  1014  6147 D SettingsProvider: selectionArgs: 1002
09-11 11:56:15.335  1014  6147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:15.335  1014  6147 D SettingsProvider: ret = -1
09-11 11:56:15.335  6577  6921 D HeadsetStateMachine: Enter Disconnected: -2
,09-11 11:56:15.335  6577  6577 D HeadsetService: mStartError = false
09-11 11:56:15.335  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:15.335  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-11 11:56:15.345  6577  6577 D A2dpService: Received start request. Starting profile...
09-11 11:56:15.345  6577  6577 D A2dpService: start()
,09-11 11:56:15.345  6577  6921 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-11 11:56:15.345  6577  6921 D HeadsetStateMachine: map size, before remove : 0
09-11 11:56:15.345  6577  6921 D HeadsetStateMachine: map size, after remove: 0
09-11 11:56:15.345  6577  6577 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-11 11:56:15.345  6577  6577 I bluedroid: get_profile_interface avrcp
,09-11 11:56:15.355  6577  6577 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,09-11 11:56:15.365  6577  6577 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-11 11:56:15.365  6577  6925 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-11 11:56:15.365  6577  6577 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:15.365  6577  6577 D A2dpStateMachine: make
,09-11 11:56:15.365  6577  6577 I bluedroid: get_profile_interface a2dp
,09-11 11:56:15.365  6577  6927 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-11 11:56:15.365  6577  6577 E bt-btif : warning : media task started media_task_refcnt 1 
,09-11 11:56:15.375  6577  6577 D A2dpService: mStartError = false
09-11 11:56:15.375  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:15.375  6577  6577 D HeadsetStateMachine: Try to query the phonestate on bind
,09-11 11:56:15.375  6577  6926 D A2dpStateMachine: Enter Disconnected: -2
09-11 11:56:15.375  1427  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,09-11 11:56:15.375  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-11 11:56:15.375  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-11 11:56:15.375  1427  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,09-11 11:56:15.375  6577  6577 I BluetoothHidServiceJni: classInitNative: succeeds
,09-11 11:56:15.375  6577  6577 D HidService: Received start request. Starting profile...
09-11 11:56:15.375  6577  6577 D HidService: start()
09-11 11:56:15.375  6577  6577 I bluedroid: get_profile_interface hidhost
09-11 11:56:15.375  6577  6577 D HidService: setHidService(): set to: null
09-11 11:56:15.375  6577  6577 D HidService: mStartError = false
09-11 11:56:15.375  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:15.385  6577  6577 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-11 11:56:15.385  6577  6577 D HealthService: Received start request. Starting profile...
09-11 11:56:15.385  6577  6577 D HealthService: start()
,09-11 11:56:15.385  6577  6925 D BluetoothMediaBrowser: no now playing list
09-11 11:56:15.385  6577  6925 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-11 11:56:15.385  6577  6577 I bluedroid: get_profile_interface health
09-11 11:56:15.385  6577  6577 D HealthService: mStartError = false
09-11 11:56:15.385  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:15.385  6577  6577 D HeadsetStateMachine: Proxy object connected
,09-11 11:56:15.385  6577  6577 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-11 11:56:15.385  6577  6577 D PanService: Received start request. Starting profile...
09-11 11:56:15.385  6577  6577 D PanService: start()
09-11 11:56:15.385  6577  6577 D BluetoothPanServiceJni: initializeNative(L110): pan
09-11 11:56:15.385  6577  6577 I bluedroid: get_profile_interface pan
,09-11 11:56:15.385  6577  6577 D PanService: mStartError = false
09-11 11:56:15.385  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:15.385  6577  6577 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-11 11:56:15.385  6577  6921 D HeadsetStateMachine: Disconnected process message: 11
,09-11 11:56:15.395  6577  6577 D BluetoothMapService: Received start request. Starting profile...
09-11 11:56:15.395  6577  6577 D BluetoothMapService: start()
,09-11 11:56:15.395  6577  6577 D BluetoothMapService: mStartError = false
09-11 11:56:15.395  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:15.395  6577  6577 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-11 11:56:15.395  6577  6921 D HeadsetStateMachine: Disconnected process message: 18
09-11 11:56:15.395  6577  6577 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-11 11:56:15.395  6577  6577 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-11 11:56:15.405  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-11 11:56:15.405  6577  6577 D SapService: Received start request. Starting profile...
09-11 11:56:15.405  6577  6577 D SapService: start()
09-11 11:56:15.405  6577  6577 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-11 11:56:15.405  6577  6577 I bluedroid: get_profile_interface sap
09-11 11:56:15.405  6577  6577 D SapService: mStartError = false
09-11 11:56:15.405  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:15.405  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-11 11:56:15.405  6577  6577 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-11 11:56:15.405  6577  6577 D BluetoothA2dp: Proxy object connected
09-11 11:56:15.405  6577  6577 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-11 11:56:15.405  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-11 11:56:15.405  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-11 11:56:15.405  6577  6921 D HeadsetStateMachine: Disconnected process message: 10
09-11 11:56:15.405  6577  6921 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:15.405  6577  6921 D HeadsetStateMachine: Disconnected process message: 11
,09-11 11:56:15.405  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:15.405  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-11 11:56:15.405  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-11 11:56:15.435  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-11 11:56:15.435  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-11 11:56:15.435  6577  6912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-11 11:56:15.435  6577  6912 I bluedroid: enable
09-11 11:56:15.435  6577  6912 I bt_hci_bdroid: init
,09-11 11:56:15.445  6577  6932 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-11 11:56:15.445  6577  6912 I bt_vendor: bt-vendor : init
,09-11 11:56:15.445  6577  6912 I bt_vendor: bt-vendor : get_bt_soc_type
09-11 11:56:15.445  6577  6912 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-11 11:56:15.445  6577  6912 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-11 11:56:15.445  6577  6912 D bt_userial_mct: userial_init
,09-11 11:56:15.445  6577  6912 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-11 11:56:15.445  6577  6912 I bt_vendor: Starting hciattach daemon
09-11 11:56:15.445  6577  6912 I bt_vendor: try to set false
,09-11 11:56:15.445  6577  6912 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-11 11:56:15.445  6577  6912 I bt_vendor: Starting hciattach daemon
09-11 11:56:15.445  6577  6912 I bt_vendor: try to set true
,09-11 11:56:15.465  6936  6936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-11 11:56:15.505  6942  6942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-11 11:56:15.515  6943  6943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-11 11:56:15.535  6945  6945 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-11 11:56:15.545  6946  6946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-11 11:56:15.545  6947  6947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-11 11:56:15.555  6948  6948 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-11 11:56:15.705   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:56:15.715   290   290 E SMD     : DCD OFF,
,09-11 11:56:15.795  6951  6951 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-11 11:56:15.805  6952  6952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-11 11:56:15.855  6577  6912 I bt_vendor: bluetooth satus is on
,09-11 11:56:15.855  6577  6934 D bt_userial_mct: userial_open(port:0)
09-11 11:56:15.855  6577  6934 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-11 11:56:15.855  6577  6934 I bt_vendor: Done intiailizing UART,
,09-11 11:56:15.865  6577  6934 I bt_vendor: Done intiailizing UART,
09-11 11:56:15.865  6577  6934 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-11 11:56:15.865  6577  6934 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-11 11:56:15.865  6577  6954 D bt_userial_mct: Entering userial_read_thread()
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_HCI
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_AVRC
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_A2D
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_BNEP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_BTM
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_GAP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_PAN
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_SAP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_SDP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_GATT
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_SMP
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-11 11:56:15.875  6577  6932 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-11 11:56:15.975  6577  6932 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-11 11:56:15.985  6577  6932 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40496e9 
,09-11 11:56:15.985  6577  6932 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40496e9 
,09-11 11:56:15.995  6577  6915 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-11 11:56:16.005  6577  6915 E bt-btif : Calling BTA_HhEnable
,09-11 11:56:16.005  6577  6915 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-11 11:56:16.005  6577  6915 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-11 11:56:16.005  6577  6915 E BluetoothServiceJni: populateRssiValuesNative
09-11 11:56:16.005  6577  6915 I bluedroid: getModelRssiValues
,09-11 11:56:16.005  6577  6915 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-11 11:56:16.005  6577  6915 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-11 11:56:16.005  1014  1014 D SettingsProvider: name = bluetooth_name
,09-11 11:56:16.005  6577  6915 D BluetoothAdapterProperties: Name is: A5-1
,09-11 11:56:16.015  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:16.015  6577  6915 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-11 11:56:16.015  6577  6915 D BluetoothAdapterProperties: Scan Mode:20
09-11 11:56:16.015  6577  6915 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:16.015  6577  6915 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-11 11:56:16.015  6577  6915 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-11 11:56:16.015  6577  6915 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-11 11:56:16.015  6577  6915 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-11 11:56:16.015  6577  6915 E bt-btif : btif_sock_init: !vhci_init
09-11 11:56:16.015  6577  6915 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-11 11:56:16.025  6577  6915 D IOP_DB_BT: db_open: db_open : handle 3028037648l, read 13894 bytes onto local cache
09-11 11:56:16.025  6577  6915 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-11 11:56:16.025  6577  6915 D IOP_DB_BT: db_query: result 1
09-11 11:56:16.025  6577  6915 I         : iop_db_open: iop_db_open status 0
,09-11 11:56:16.025  6577  6915 D bte_conf: Device ID record 1 : primary
09-11 11:56:16.025  6577  6915 D bte_conf:   vendorId            = 0075
09-11 11:56:16.025  6577  6915 D bte_conf:   vendorIdSource      = 0001
09-11 11:56:16.025  6577  6915 D bte_conf:   product             = 0100
09-11 11:56:16.025  6577  6915 D bte_conf:   version             = 0200
09-11 11:56:16.025  6577  6915 D bte_conf:   clientExecutableURL = 
09-11 11:56:16.025  6577  6915 D bte_conf:   serviceDescription  = 
09-11 11:56:16.025  6577  6915 D bte_conf:   documentationURL    = 
09-11 11:56:16.025  6577  6915 D bte_conf: bte_load_did_conf no section named DID2.
,09-11 11:56:16.025  6577  6915 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-11 11:56:16.025  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:16.025  6577  6912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-11 11:56:16.025  6577  6912 D BluetoothAdapterProperties: ScanMode =  20
09-11 11:56:16.025  6577  6912 D BluetoothAdapterProperties: State =  11
,09-11 11:56:16.025  1014  1491 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-11 11:56:16.025  6577  6912 D BluetoothAdapterProperties: Setting state to 12
09-11 11:56:16.025  6577  6912 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-11 11:56:16.025  6577  6954 E bt_mct  : hci lib postload completed
,09-11 11:56:16.035  6577  6915 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-11 11:56:16.035  6577  6915 D BluetoothAdapterProperties: Scan Mode:21
,09-11 11:56:16.035  6577  6915 D BluetoothAdapterProperties: Discoverable Timeout:120
09-11 11:56:16.035  1014  2735 D SSRM:n  : SIOP:: AP = 320
,09-11 11:56:16.035  1014  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-11 11:56:16.035  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:16.035  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:16.035  1014  1027 D SettingsProvider: selectionArgs: false
,09-11 11:56:16.035  1014  1027 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:16.035  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-11 11:56:16.035  1014  1027 D SettingsProvider: ret = -1
,09-11 11:56:16.045  6577  6912 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:16.045  6577  6912 D BluetoothAdapterService: updateAdapterState state is 12
,09-11 11:56:16.045  1014  4271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:16.045  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.045  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.045  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.045  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.055  6577  6912 D BluetoothAdapterService: Autoconnection is available 
,09-11 11:56:16.055  6577  6912 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-11 11:56:16.055  6577  6912 D BluetoothAdapterService: starting service from this receiver
,09-11 11:56:16.055  1014  1252 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:16.055  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:16.055  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:16.055  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.055  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.055  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.065  6577  6912 I BluetoothAdapterState: Entering On State from state = 11
,09-11 11:56:16.065  2854  2869 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.065  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:16.065  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.065  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:16.065  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.065  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.065  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.065  2854  2869 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:16.075  1297  1308 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:16.075  1297  1308 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.075  6577  6577 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-11 11:56:16.075  1297  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:16.075  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:16.075  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-11 11:56:16.075  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.085  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.085  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.085  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.085  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:16.085  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.085  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-11 11:56:16.085  1297  1308 D BluetoothPbap: onBluetoothStateChange: up=true
,09-11 11:56:16.085  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-11 11:56:16.085  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.085  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.085  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.085  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.085  1452  1761 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.085  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:16.085  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.095  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.095  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.095  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.095  1452  1761 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:16.095  6577  6585 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:16.095  6577  6585 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.095  1014  1043 D BluetoothPan: Binding service...
09-11 11:56:16.095  6577  6577 I BluetoothPbapService: Handler(): got msg=1
,09-11 11:56:16.095  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-11 11:56:16.095  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.095  1014  1560 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-11 11:56:16.095  6348  6359 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.095  6348  6359 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.095  1427  2770 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.105  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:16.105  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.105  6577  6958 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-11 11:56:16.105  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.105  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.105  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.105  1427  2770 E BluetoothHeadset: BluetoothHeadset service is binded
09-11 11:56:16.105  6577  6585 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:16.105  1948  2109 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.105  1297  1297 D BluetoothInputDevice: Proxy object connected
09-11 11:56:16.105  1948  2109 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-11 11:56:16.105  1297  1297 D HidProfile: Bluetooth service connected
,09-11 11:56:16.105  1438  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.105  1438  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.105  6448  6459 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.105  6448  6459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.105  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:16.105  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-11 11:56:16.105  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-11 11:56:16.105  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.115  1297  1297 D BluetoothPbap: Proxy object connected
09-11 11:56:16.115  1297  1297 D PbapServerProfile: Bluetooth service connected
,09-11 11:56:16.115  1014  1014 D BluetoothA2dp: Proxy object connected
09-11 11:56:16.115  1297  1306 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:16.115  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-11 11:56:16.115  1297  1306 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.115  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-11 11:56:16.115  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.115  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.115  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.115  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.115  2854  2869 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:16.125  2854  2869 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.125  6577  6958 D BluetoothSocket: bindListen(): myUserId = 0
09-11 11:56:16.125  6577  6958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:16.125  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-11 11:56:16.125  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.125  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.125  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.125  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.125  2854  2854 D BluetoothA2dp: Proxy object connected
,09-11 11:56:16.125  1297  1297 D BluetoothA2dp: Proxy object connected
09-11 11:56:16.125  1297  1297 D A2dpProfile: Bluetooth service connected
,09-11 11:56:16.125  1427  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.125  6577  6958 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-11 11:56:16.125  6577  6958 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:16.125  6577  6958 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:16.125  6577  6958 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c9e29ef
09-11 11:56:16.125  6577  6958 D BluetoothSocket: channel: 19
09-11 11:56:16.125  6577  6958 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-11 11:56:16.125  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:16.125  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.125  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.125  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.125  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.135  1427  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:16.135  2854  2866 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.135  2854  2866 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.135  1297  1306 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.135  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:16.135  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.135  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.135  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.135  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.135  1297  1306 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:16.135  1297  1297 D HeadsetProfile: Bluetooth service connected
09-11 11:56:16.135  1297  6959 D Bluetoothsap: onBluetoothStateChange: up=true
,09-11 11:56:16.145  1297  6959 D Bluetoothsap: Binding service...
,09-11 11:56:16.145  1297  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-11 11:56:16.145  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-11 11:56:16.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.145  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.145  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.145  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.145  1297  6959 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-11 11:56:16.145  1427  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-11 11:56:16.145  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object connected
09-11 11:56:16.145  1297  1297 D SapProfile: Bluetooth service connected
09-11 11:56:16.145  1297  1297 D Bluetoothsap: getConnectedDevices()
,09-11 11:56:16.145  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:16.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:16.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:16.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.155  1427  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:16.155  1297  6959 D BluetoothPan: Binding service...
,09-11 11:56:16.155  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-11 11:56:16.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:16.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.155  1452  1709 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:16.165  1297  1297 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:16.165  1297  1297 D PanProfile: Bluetooth service connected
09-11 11:56:16.165  1452  1709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.165  1427  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:16.165  1427  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:16.165  1297  1306 D BluetoothMap: onBluetoothStateChange: up=true
,09-11 11:56:16.165  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-11 11:56:16.165  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.165  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.165  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:16.165  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.175  1297  1297 D BluetoothMap: Proxy object connected
09-11 11:56:16.175  1297  1297 D MapProfile: Bluetooth service connected
09-11 11:56:16.175  1297  1297 D BluetoothMap: getConnectedDevices()
09-11 11:56:16.175  1171  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:16.175  1171  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-11 11:56:16.175  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:16.175  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:16.175  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-11 11:56:16.175  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-11 11:56:16.175  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-11 11:56:16.175  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-11 11:56:16.175  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@64f0a2a, true
,09-11 11:56:16.175  1427  1427 D BluetoothHeadset: registerMessageListener
,09-11 11:56:16.185  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-11 11:56:16.185  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-11 11:56:16.185  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.185  1171  1171 D BluetoothTile:  getBluetoothState : 12
,09-11 11:56:16.185  1819  1819 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-11 11:56:16.195  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:16.195  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:16.195  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.195  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.195  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:16.195  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:16.195  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:16.195  6577  6961 D HeadsetService: registerMessageListener
,09-11 11:56:16.195  6577  6961 D HeadsetService: registerMessageListener
,09-11 11:56:16.195  6577  6921 D HeadsetStateMachine: Disconnected process message: 70
09-11 11:56:16.195  6577  6921 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@df8dcfc
09-11 11:56:16.195  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-11 11:56:16.195  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-11 11:56:16.205  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.205  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:16.205  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-11 11:56:16.205  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-11 11:56:16.205  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:16.205  1014  1332 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:16.205  1014  1560 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-11 11:56:16.205  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:16.205  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-11 11:56:16.205  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-11 11:56:16.205  6577  6964 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-11 11:56:16.215  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-11 11:56:16.215  1297  1297 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-11 11:56:16.215  1297  1297 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-11 11:56:16.215  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-11 11:56:16.215  1297  1297 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-11 11:56:16.215  1297  1297 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-11 11:56:16.215  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:16.215  6577  6921 D HeadsetStateMachine: Disconnected process message: 9
,09-11 11:56:16.215  6577  6921 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-11 11:56:16.215  6577  6964 D BluetoothSocket: bindListen(): myUserId = 0
09-11 11:56:16.215  6577  6964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:16.225  6577  6964 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-11 11:56:16.225  6577  6964 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:16.225  6577  6964 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:16.225  6577  6964 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d330f85
,09-11 11:56:16.225  6577  6964 D BluetoothSocket: channel: 5
,09-11 11:56:16.225   285   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-11 11:56:16.225   285   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-11 11:56:16.225   285   682 V voice   : voice_set_parameters: exit with code(-2)
09-11 11:56:16.225   285   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false,
09-11 11:56:16.225   285   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-11 11:56:16.225   285   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-11 11:56:16.225   285   682 V audio_hw_primary: adev_set_parameters: exit
09-11 11:56:16.225  6577  6921 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-11 11:56:16.235  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
09-11 11:56:16.235  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.235  1014  1560 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:16.235  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.235  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-11 11:56:16.235  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:16.235  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:16.235  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:16.245  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:16.245  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-11 11:56:16.255  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:16.255  6577  6577 D BtConfig.SecureMode: isSecureModeOn:false
,09-11 11:56:16.265  1014  3130 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:16.265  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.265  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.265  1014  3130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:16.265  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:16.275  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:16.285  1014  3131 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:16.285  1014  3131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-11 11:56:16.285  1014  3131 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.285  1014  3131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:16.285  1014  3131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:16.295  1014  1559 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-11 11:56:16.295  1948  6971 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-11 11:56:16.295  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:16.305  1014  6147 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:16.305  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:16.305  1014  6147 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:16.305  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:16.315  6577  6974 D BluetoothSocket: bindListen(): myUserId = 0
09-11 11:56:16.315  6577  6974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:16.315  6577  6974 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-11 11:56:16.315  6577  6974 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:16.315  6577  6974 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:16.315  6577  6974 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e9a1f01
09-11 11:56:16.325  6577  6974 D BluetoothSocket: channel: 12
09-11 11:56:16.325  6577  6974 I BtOppRfcommListener: Accept thread started.
,09-11 11:56:16.325  1014  1252 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:16.325  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:16.325  1014  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:16.325  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:16.335  1948  6971 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-11 11:56:16.705   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:56:17.705   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,09-11 11:56:18.155  6348  6401 D BluetoothAdapter: disable()
,09-11 11:56:18.155  1014  1558 D SettingsProvider: name = bluetooth_on
,09-11 11:56:18.165  6577  6912 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-11 11:56:18.165  6577  6912 D BluetoothAdapterProperties: Setting state to 13
09-11 11:56:18.165  6577  6912 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-11 11:56:18.165  6577  6912 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
,09-11 11:56:18.165  6577  6912 D BluetoothAdapterService: updateAdapterState state is 13,
,09-11 11:56:18.165  1014  6147 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.165  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.165  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-11 11:56:18.165  1014  6147 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.165  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-11 11:56:18.175  6577  6577 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-11 11:56:18.175  6577  6577 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8d7b1a6, channel: 19, state: LISTENING,
,09-11 11:56:18.175  6577  6577 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8d7b1a6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c9e29ef, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@85b67e7mSocket: android.net.LocalSocket@2c3dcf94 impl:android.net.LocalSocketImpl@c08aa3d fd:FileDescriptor[75]
09-11 11:56:18.175  6577  6577 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c3dcf94 impl:android.net.LocalSocketImpl@c08aa3d fd:FileDescriptor[75]
,09-11 11:56:18.175  6577  6912 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:18.175  6577  6912 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-11 11:56:18.175  6577  6912 D BluetoothAdapterService: terminating service from this receiver
,09-11 11:56:18.175  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-11 11:56:18.175  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.175  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.175  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.185  6577  6912 D BluetoothAdapterProperties: onBluetoothDisable()
09-11 11:56:18.185  6577  6912 D BluetoothAdapterProperties: mDiscovering is false
,09-11 11:56:18.185  1014  1332 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-11 11:56:18.185  6577  6912 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-11 11:56:18.185  1297  1297 D BluetoothPbap: Proxy object disconnected
09-11 11:56:18.185  1297  1297 D PbapServerProfile: Bluetooth service disconnected
,09-11 11:56:18.185  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:18.185  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-11 11:56:18.195  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-11 11:56:18.195  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:18.195  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:18.195  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-11 11:56:18.205  1819  1819 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-11 11:56:18.205  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-11 11:56:18.205  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:18.205  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:18.205  1014  1559 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:18.205  1014  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-11 11:56:18.205  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-11 11:56:18.215  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-11 11:56:18.215  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:18.215  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:18.215  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:18.215  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:18.225  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:18.225  6348  6348 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-11 11:56:18.225  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:18.225  1014  4271 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:18.225  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.225  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:18.235  6577  6915 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-11 11:56:18.235  6577  6915 D BluetoothAdapterProperties: Scan Mode:20
,09-11 11:56:18.235  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:18.235  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.235  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:18.235  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:18.235  6577  6912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-11 11:56:18.245  6577  6912 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-11 11:56:18.245  6577  6912 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-11 11:56:18.245  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:18.245  6577  6577 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e6c9b83, channel: 5, state: LISTENING
09-11 11:56:18.245  6577  6577 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e6c9b83, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d330f85, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25f25100mSocket: android.net.LocalSocket@22daad39 impl:android.net.LocalSocketImpl@2af94f7e fd:FileDescriptor[77]
09-11 11:56:18.245  6577  6577 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22daad39 impl:android.net.LocalSocketImpl@2af94f7e fd:FileDescriptor[77]
,09-11 11:56:18.245  6577  6912 E bt-btif : cmd socket is not created
,09-11 11:56:18.245  6577  6974 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-11 11:56:18.245  6577  6912 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-11 11:56:18.245  6577  6932 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-11 11:56:18.245  6577  6932 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-11 11:56:18.245  1014  1560 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:18.245  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-11 11:56:18.245  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-11 11:56:18.245  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:18.245  6577  6932 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:18.245  6577  6577 I BtOppRfcommListener: stopping Accept Thread
09-11 11:56:18.255  6577  6577 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bd36cdf, channel: 12, state: LISTENING
09-11 11:56:18.255  6577  6577 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bd36cdf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e9a1f01, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37ab7d2cmSocket: android.net.LocalSocket@302fe3f5 impl:android.net.LocalSocketImpl@2056e58a fd:FileDescriptor[80]
09-11 11:56:18.255  6577  6577 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@302fe3f5 impl:android.net.LocalSocketImpl@2056e58a fd:FileDescriptor[80]
,09-11 11:56:18.255  6577  6974 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-11 11:56:18.255  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.255  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.255  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:18.275  6577  6577 V BluetoothOppManager: cleanUp...
,09-11 11:56:18.275  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:18.275  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:18.285  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:18.285  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-11 11:56:18.315  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:18.325  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:18.415  1014  1988 V SAMP_SPCM_test: CSC File load.. 
,09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-11 11:56:18.435  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-11 11:56:18.445  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:18.445  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-11 11:56:18.455  6577  6954 I bt_userial_mct: exiting userial_read_thread
09-11 11:56:18.455  6577  6954 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-11 11:56:18.455  6577  6915 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-11 11:56:18.455  6577  6932 W bt-l2cap: HC lib lpm enable=0 return 0
09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-11 11:56:18.455  6577  6932 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-11 11:56:18.455  6577  6932 W bt-btif : ag scb idx 1 not allocated
,09-11 11:56:18.455  6577  6932 W bt-btif : ag scb idx 2 not allocated
09-11 11:56:18.455  6577  6932 E bt-btif : BTA AG is already disabled, ignoring ...
09-11 11:56:18.455  6577  6934 I bt_vendor: hw_epilog_process,
09-11 11:56:18.455  6577  6915 D bt_userial_mct: userial_close
09-11 11:56:18.455  6577  6915 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
,09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account,
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-11 11:56:18.465  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-11 11:56:18.475  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments,
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-11 11:56:18.485  1014  1988 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming,
,09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-11 11:56:18.485  1014  1988 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-11 11:56:18.485  1014  1988 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-11 11:56:18.485  1014  1988 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-11 11:56:18.485  1014  1988 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.b,bccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-11 11:56:18.485  1014  1988 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-11 11:56:18.505  6985  6985 E Zygote  : MountEmulatedStorage()
09-11 11:56:18.505  6985  6985 E Zygote  : v2
09-11 11:56:18.505  6985  6985 I libpersona: KNOX_SDCARD checking this for 1000
09-11 11:56:18.505  6985  6985 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:18.515  1014  1988 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6985 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,09-11 11:56:18.525  6985  6985 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:18.525  6985  6985 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:18.525  6985  6985 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-11 11:56:18.545   312   312 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.305ms total 31.402ms
,09-11 11:56:18.555  6985  6985 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:18.555  6985  6985 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:18.565   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 726us total 22.357ms
,09-11 11:56:18.575  6985  6985 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-11 11:56:18.595   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 735us total 20.203ms
,09-11 11:56:18.625  1014  1988 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-11 11:56:18.705   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,09-11 11:56:18.715   290   290 E SMD     : DCD OFF,
,09-11 11:56:18.725  6577  6915 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
09-11 11:56:18.725  6577  6915 I bt_vendor: bluetooth satus is on
09-11 11:56:18.725  6577  6915 I bt_vendor: bt-vendor : resetting BT status
09-11 11:56:18.725  6577  6915 I bt_vendor: Starting hciattach daemon
,09-11 11:56:18.725  6577  6915 I bt_vendor: try to set false
,09-11 11:56:18.725  6577  6915 I bt_vendor: Starting hciattach daemon
09-11 11:56:18.725  6577  6915 I bt_vendor: try to set false
09-11 11:56:18.725  6577  6915 I bt_vendor: cleanup,
09-11 11:56:18.725  6577  6932 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-11 11:56:18.725  6577  6915 I GKI_LINUX: GKI_exit_task 0 done
,09-11 11:56:18.725  6577  6915 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-11 11:56:18.725  6577  6912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-11 11:56:18.725  6577  6912 D BtConfig.SecureMode: isSecureModeOn:false
09-11 11:56:18.725  6577  6912 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-11 11:56:18.725  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-11 11:56:18.725  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-11 11:56:18.725  1014  1252 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.725  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-11 11:56:18.725  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-11 11:56:18.735  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.735  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.735  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.735  6577  6577 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:18.735  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-11 11:56:18.735  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-11 11:56:18.735  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:18.735  6577  6577 D BtGatt.GattService: Received stop request...Stopping profile...
09-11 11:56:18.735  1014  1332 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.735  6577  6577 D BtGatt.GattService: stop(),
,09-11 11:56:18.735  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
09-11 11:56:18.735  6577  6577 D BtGatt.AdvertiseManager: advertise clients cleared
09-11 11:56:18.735  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.735  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.735  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-11 11:56:18.735  1014  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:18.735  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-11 11:56:18.735  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-11 11:56:18.735  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-11 11:56:18.735  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-11 11:56:18.735  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:18.735  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.735  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.735  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.735  6577  6577 D HeadsetService: Received stop request...Stopping profile...
,09-11 11:56:18.735  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.735  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-11 11:56:18.745  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-11 11:56:18.745  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-11 11:56:18.745  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-11 11:56:18.745  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.745  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.745  1297  1297 D HeadsetProfile: Bluetooth service disconnected
,09-11 11:56:18.745  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.745  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.745  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.745  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-11 11:56:18.745  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-11 11:56:18.745  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-11 11:56:18.745  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.745  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.755  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.755  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.755  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-11 11:56:18.755  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-11 11:56:18.755  1014  1252 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.755  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.755  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:18.755  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.755  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.755  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:18.755  1014  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.755  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.755  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.755  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.755  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-11 11:56:18.755  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-11 11:56:18.755  6577  6912 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-11 11:56:18.755  1014  4271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:18.755  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.765  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.765  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.765  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-11 11:56:18.765  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService,
09-11 11:56:18.765  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-11 11:56:18.765  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
09-11 11:56:18.765  6577  6912 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-11 11:56:18.765  6577  6912 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-11 11:56:18.765  6577  6912 D BluetoothAdapterState: Stopping profile services that were post enabled
09-11 11:56:18.765  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-11 11:56:18.765  6577  6577 D A2dpService: Received stop request...Stopping profile...
,09-11 11:56:18.765  6577  6926 D A2dpStateMachine: Exit Disconnected: -1
,09-11 11:56:18.765  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.765  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:18.765  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-11 11:56:18.765  2854  2854 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:18.775  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-11 11:56:18.775  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-11 11:56:18.775  6577  6577 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-11 11:56:18.775  6577  6577 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-11 11:56:18.775  6577  6577 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-11 11:56:18.775  6577  6577 D HidService: Received stop request...Stopping profile...
,09-11 11:56:18.775  6577  6577 D HidService: Stopping Bluetooth HidService
09-11 11:56:18.775  6577  6577 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-11 11:56:18.775  6577  6577 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-11 11:56:18.775  6577  6577 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-11 11:56:18.775  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.775  6577  6577 D HealthService: Received stop request...Stopping profile...
,09-11 11:56:18.775  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.785  1297  1297 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:18.785  1297  1297 D A2dpProfile: Bluetooth service disconnected
,09-11 11:56:18.785  6577  6577 D PanService: Received stop request...Stopping profile...
,09-11 11:56:18.785  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:18.785  1297  1297 D BluetoothInputDevice: Proxy object disconnected
09-11 11:56:18.785  1297  1297 D HidProfile: Bluetooth service disconnected
,09-11 11:56:18.785  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:18.785  6577  6577 D BluetoothMapService: Received stop request...Stopping profile...
,09-11 11:56:18.785  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.785  6577  6577 D SapService: Received stop request...Stopping profile...
,09-11 11:56:18.785  6577  6577 D SapService: Stopping Bluetooth SapService
09-11 11:56:18.785  6577  6577 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:18.795  1297  1297 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-11 11:56:18.795  1297  1297 D PanProfile: Bluetooth service disconnected
09-11 11:56:18.795  1297  1297 D BluetoothMap: Proxy object disconnected
09-11 11:56:18.795  1297  1297 D MapProfile: Bluetooth service disconnected
09-11 11:56:18.795  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-11 11:56:18.795  1297  1297 D SapProfile: Bluetooth service disconnected
,09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-11 11:56:18.795  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-11 11:56:18.795  6577  6577 D BluetoothA2dp: Proxy object disconnected
09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-11 11:56:18.795  6577  6927 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-11 11:56:18.795  6577  6577 I GKI_LINUX: GKI_exit_task 2 done
,09-11 11:56:18.795  6577  6577 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-11 11:56:18.795  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-11 11:56:18.795  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.795  6577  6577 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-11 11:56:18.795  6577  6577 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-11 11:56:18.795  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:18.795  6577  6577 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-11 11:56:18.795  6577  6577 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-11 11:56:18.795  6577  6577 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-11 11:56:18.795  6577  6577 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-11 11:56:18.795  6577  6577 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-11 11:56:18.805  6577  6577 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-11 11:56:18.805  6577  6577 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-11 11:56:18.805  6577  6912 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-11 11:56:18.805  6577  6912 D BluetoothAdapterProperties: Setting state to 10
09-11 11:56:18.805  6577  6912 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-11 11:56:18.805  6577  6912 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:18.805  6577  6912 D BluetoothAdapterService: updateAdapterState state is 10
,09-11 11:56:18.805  6577  6912 D BluetoothAdapterService: Autoconnection is available 
,09-11 11:56:18.805  6577  6912 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-11 11:56:18.805  6577  6912 I BluetoothAdapterState: Entering OffState
,09-11 11:56:18.805  1297  6959 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.805  1297  6959 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.805  1297  1308 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-11 11:56:18.805  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.805  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.805  1297  1306 D BluetoothPbap: onBluetoothStateChange: up=false
,09-11 11:56:18.805  6577  6962 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.805  6577  6962 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.815  6348  6362 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.815  6348  6362 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-11 11:56:18.815  6348  6362 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-11 11:56:18.815  6348  6362 D BluetoothLeAdvertiser: Exit stop advertising
09-11 11:56:18.815  6348  6362 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-11 11:56:18.815  6348  6362 D BluetoothLeScanner: Exiting stopAllScan
,09-11 11:56:18.815  6577  6585 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-11 11:56:18.815  1948  1957 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.815  1948  1957 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.815  1438  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:18.815  1438  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.815  6448  6460 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.815  6448  6460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.815  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
09-11 11:56:18.815  1297  6959 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-11 11:56:18.815  2854  2866 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-11 11:56:18.825  2854  2869 D BluetoothAdapter: onBluetoothStateChange: up=false
09-11 11:56:18.825  2854  2869 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.825  1297  1306 D Bluetoothsap: onBluetoothStateChange: up=false
,09-11 11:56:18.825  1297  1306 D Bluetoothsap: Unbinding service...
,09-11 11:56:18.825  1452  1761 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.825  1452  1761 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.825  1427  2770 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.825  1427  2770 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.825  1297  1308 D BluetoothMap: onBluetoothStateChange: up=false
,09-11 11:56:18.825  1171  1201 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-11 11:56:18.825  1171  1201 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-11 11:56:18.825  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-11 11:56:18.835  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-11 11:56:18.835  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:18.835  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-11 11:56:18.835  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-11 11:56:18.835  6577  6915 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-11 11:56:18.845  6577  6577 I GKI_LINUX: GKI_exit_task 1 done
09-11 11:56:18.845  6577  6577 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-11 11:56:18.845  6577  6577 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-11 11:56:18.845  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:18.845  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:18.845  1171  1739 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:18.845  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:18.845  1171  1171 D BluetoothTile:  getBluetoothState : 10
,09-11 11:56:18.845  1171  1739 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:18.845  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:18.845  1171  1171 D BluetoothAdapter: 907785629: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:18.845  1014  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-11 11:56:18.845  6577  6577 I art     : System.exit called, status: 0
09-11 11:56:18.845  6577  6577 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-11 11:56:18.855  1819  1819 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-11 11:56:18.855  1014  3131 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-11 11:56:18.855  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-11 11:56:18.855  1948  2121 D BluetoothAdapter: 216489189: getState() :  mService = null. Returning STATE_OFF
09-11 11:56:18.855  1948  2121 D BluetoothAdapter: 216489189: getState() :  mService = null. Returning STATE_OFF
,09-11 11:56:18.855  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:18.855  1014  4271 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:18.855  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.855  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:18.855  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.855  1014  4271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:18.855  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:18.865  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-11 11:56:18.865  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:18.865  1014  1491 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:18.865  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-11 11:56:18.865  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:18.865  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:18.865  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:18.875  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:18.875  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:18.885  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:18.885  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-11 11:56:18.895  1014  1137 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-11 11:56:18.895  1014  1137 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-11 11:56:18.905  1014  1137 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-11 11:56:18.905  1014  1137 W BroadcastQueue: android.os.TransactionTooLargeException
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-11 11:56:18.905  1014  1137 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-11 11:56:18.905  1014  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-11 11:56:18.905  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:18.905  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.905  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:18.905  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:18.915  7007  7007 E Zygote  : MountEmulatedStorage()
,09-11 11:56:18.915  7007  7007 E Zygote  : v2
09-11 11:56:18.915  7007  7007 I libpersona: KNOX_SDCARD checking this for 1002
09-11 11:56:18.915  7007  7007 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:18.915  1014  1137 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7007 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-11 11:56:18.925  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:18.925  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-11 11:56:18.925  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:18.945  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:18.945  7007  7007 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:18.975  7007  7007 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-11 11:56:18.975  7007  7007 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-11 11:56:19.005  7007  7007 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-11 11:56:19.045  7007  7007 D BtSettings.ProfileConfig: Adding GattService
,09-11 11:56:19.045  7007  7007 D BtSettings.ProfileConfig: Adding HeadsetService
,09-11 11:56:19.045  7007  7007 D BtSettings.ProfileConfig: Adding A2dpService
09-11 11:56:19.045  7007  7007 D BtSettings.ProfileConfig: Adding HidService
09-11 11:56:19.045  7007  7007 D BtSettings.ProfileConfig: Adding HealthService
,09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding PanService
09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding SapService
,09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding SapClientService,
09-11 11:56:19.055  7007  7007 D BtSettings.ProfileConfig: Adding HidDevService
,09-11 11:56:19.055  7007  7007 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-11 11:56:19.055  1014  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-11 11:56:19.055  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:19.055  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.055  1014  1479 D SettingsProvider: selectionArgs: false
09-11 11:56:19.055  1014  1479 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.055  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.055  1014  1479 D SettingsProvider: ret = -1
09-11 11:56:19.055  1014  1332 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-11 11:56:19.055  1014  1332 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.055  1014  1332 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:19.055  1014  1332 D SettingsProvider: selectionArgs: false
09-11 11:56:19.055  1014  1332 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.055  1014  1332 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-11 11:56:19.055  1014  1332 D SettingsProvider: ret = -1
,09-11 11:56:19.055  1014  3132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-11 11:56:19.055  1014  3132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-11 11:56:19.055  1014  3132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.055  1014  3132 D SettingsProvider: selectionArgs: false
09-11 11:56:19.055  1014  3132 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.055  1014  3132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.055  1014  3132 D SettingsProvider: ret = -1
09-11 11:56:19.055  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-11 11:56:19.055  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.055  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.055  1014  1491 D SettingsProvider: selectionArgs: false
,09-11 11:56:19.055  1014  1491 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.055  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.055  1014  1491 D SettingsProvider: ret = -1
,09-11 11:56:19.055  1014  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-11 11:56:19.055  1014  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.055  1014  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:19.055  1014  1560 D SettingsProvider: selectionArgs: false
09-11 11:56:19.055  1014  1560 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.055  1014  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-11 11:56:19.055  1014  1560 D SettingsProvider: ret = -1
09-11 11:56:19.065  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-11 11:56:19.065  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-11 11:56:19.065  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:19.065  1014  1558 D SettingsProvider: selectionArgs: false
09-11 11:56:19.065  1014  1558 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.065  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.065  1014  1558 D SettingsProvider: ret = -1
,09-11 11:56:19.065  1014  3131 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-11 11:56:19.065  1014  3131 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-11 11:56:19.065  1014  3131 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.065  1014  3131 D SettingsProvider: selectionArgs: false
09-11 11:56:19.065  1014  3131 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.065  1014  3131 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.065  1014  3131 D SettingsProvider: ret = -1
,09-11 11:56:19.065  1014  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-11 11:56:19.065  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:19.065  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.065  1014  1026 D SettingsProvider: selectionArgs: false
,09-11 11:56:19.065  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.065  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-11 11:56:19.065  1014  1026 D SettingsProvider: ret = -1
,09-11 11:56:19.065  1014  1318 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:19.065  1014  1318 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.065  1014  1318 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.065  1014  1318 D SettingsProvider: selectionArgs: false
09-11 11:56:19.065  1014  1318 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.065  1014  1318 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.065  1014  1318 D SettingsProvider: ret = -1
,09-11 11:56:19.075  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:19.075  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.075  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.075  1014  1137 D SettingsProvider: selectionArgs: false
09-11 11:56:19.075  1014  1137 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.075  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.075  1014  1137 D SettingsProvider: ret = -1
,09-11 11:56:19.075  1014  6147 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-11 11:56:19.075  1014  6147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-11 11:56:19.075  1014  6147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:19.075  1014  6147 D SettingsProvider: selectionArgs: false
,09-11 11:56:19.075  1014  6147 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:19.075  1014  6147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-11 11:56:19.075  1014  6147 D SettingsProvider: ret = -1
,09-11 11:56:19.075  1014  3130 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-11 11:56:19.075  1014  3130 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:19.075  1014  3130 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-11 11:56:19.075  1014  3130 D SettingsProvider: selectionArgs: false
09-11 11:56:19.075  1014  3130 D SettingsProvider: selectionArgs: 1002
09-11 11:56:19.075  1014  3130 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:19.075  1014  3130 D SettingsProvider: ret = -1
,09-11 11:56:19.085  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:19.095  1014  1332 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:19.095  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-11 11:56:19.095  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:19.095  1014  1332 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:19.095  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:19.105  1948  7023 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-11 11:56:19.105  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:19.105  1014  1252 I ActivityManager: Killing 5644:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-11 11:56:19.275  1014  3132 I art     : Explicit concurrent mark sweep GC freed 68499(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.408ms total 158.021ms
,09-11 11:56:19.275  1014  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:19.275  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:19.285  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:19.285  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:19.295  1948  7023 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-11 11:56:19.705   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-11 11:56:21.175  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:21.175  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:21.725   290   290 E SMD     : DCD OFF,
,09-11 11:56:21.975  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-11 11:56:21.975  1014  1026 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-11 11:56:21.975  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-11 11:56:21.975  1014  1026 D BatteryService: stay LED for charging
09-11 11:56:21.975  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-11 11:56:21.975  1014  1014 I MotionRecognitionService: Plugged,
09-11 11:56:21.975  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
09-11 11:56:21.975  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-11 11:56:21.975  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-11 11:56:21.985  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-11 11:56:21.985  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-11 11:56:22.015  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:22.015  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:22.015  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-11 11:56:24.175  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:24.175  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20102882 added. We now have 6 listener(s)
,09-11 11:56:24.175  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:24.175  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:24.175  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c50b93 added. We now have 7 listener(s)
,09-11 11:56:24.175  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:24.175  6348  6401 I System.out: IsBluetoothEnabled
,09-11 11:56:24.175  6348  6401 D BluetoothAdapter: disable()
,09-11 11:56:24.175  1014  1252 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-11 11:56:24.175  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:24.185  6348  6401 D BluetoothAdapter: enable()
,09-11 11:56:24.185  1014  1318 W ActivityManager: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-11 11:56:24.185  1014  1318 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-11 11:56:24.185  1014  1318 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-11 11:56:24.185  1014  1318 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:24.185  1014  1318 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:24.185  1014  1318 D SettingsProvider: name = bluetooth_on,
,09-11 11:56:24.195  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-11 11:56:24.195  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:24.195  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-11 11:56:24.195  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-11 11:56:24.215  7007  7007 D BluetoothAdapterState: make
,09-11 11:56:24.225  7007  7007 I bluedroid: init
,09-11 11:56:24.225  7007  7029 I BluetoothAdapterState: Entering OffState
,09-11 11:56:24.225  7007  7007 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-11 11:56:24.225  7007  7007 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-11 11:56:24.225  7007  7007 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-11 11:56:24.225  7007  7007 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-11 11:56:24.225  7007  7007 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-11 11:56:24.225  7007  7007 I bluedroid: get_profile_interface socket
09-11 11:56:24.225  7007  7007 I bluedroid: get_profile_interface map_client
,09-11 11:56:24.225  7007  7032 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-11 11:56:24.235  7007  7007 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-11 11:56:24.235  7007  7032 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-11 11:56:24.235  7007  7032 E BluetoothServiceJni: populateRssiValuesNative
09-11 11:56:24.235  7007  7032 I bluedroid: getModelRssiValues
,09-11 11:56:24.235  7007  7032 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-11 11:56:24.235  7007  7032 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-11 11:56:24.235  7007  7032 D BluetoothAdapterProperties: Name is: A5-1
,09-11 11:56:24.235  1014  1014 D SettingsProvider: name = bluetooth_name
,09-11 11:56:24.245  7007  7007 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:24.245  1014  1559 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-11 11:56:24.245  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.245  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.245  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:24.245  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.245  7007  7015 I bluedroid: config_hci_snoop_log
,09-11 11:56:24.255  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-11 11:56:24.255  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-11 11:56:24.255  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-11 11:56:24.255  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-11 11:56:24.255  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-11 11:56:24.265  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:24.265  7007  7007 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-11 11:56:24.265  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-11 11:56:24.265  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-11 11:56:24.275  7007  7029 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-11 11:56:24.275  7007  7029 D BluetoothAdapterProperties: Setting state to 11
09-11 11:56:24.275  7007  7029 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-11 11:56:24.275  7007  7029 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:24.275  7007  7029 D BluetoothAdapterService: updateAdapterState state is 11
,09-11 11:56:24.275  7007  7029 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:24.275  7007  7029 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-11 11:56:24.275  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:24.275  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-11 11:56:24.285  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-11 11:56:24.285  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:24.285  1171  1171 D BluetoothTile:  getBluetoothState : 11
,09-11 11:56:24.295  1014  4271 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:24.295  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-11 11:56:24.295  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:24.295  7007  7029 D BluetoothSecureManager: getInstant: null
09-11 11:56:24.295  7007  7029 D BluetoothSecureManager: calling getMethod for getService
09-11 11:56:24.295  7007  7029 D BluetoothSecureManager: calling getService
,09-11 11:56:24.295  1819  1819 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-11 11:56:24.295  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:24.305  7007  7029 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1b1c7b58
09-11 11:56:24.305  1014  1560 D BluetoothSecureManagerService: isSecureModeEnabled
,09-11 11:56:24.305  1014  1560 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-11 11:56:24.305  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-11 11:56:24.305  7007  7029 D BtConfig.SecureMode: isSecureModeOn:false
09-11 11:56:24.305  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-11 11:56:24.305  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:24.305  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,09-11 11:56:24.305  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:24.305  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:24.305  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:24.305  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:24.305  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-11 11:56:24.305  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,09-11 11:56:24.305  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:24.315  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-11 11:56:24.315  7007  7029 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-11 11:56:24.315  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:24.315  7007  7029 D BluetoothBondStateMachine: make
,09-11 11:56:24.315  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-11 11:56:24.325  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-11 11:56:24.325  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-11 11:56:24.325  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-11 11:56:24.325  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-11 11:56:24.325  7007  7033 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-11 11:56:24.325  1014  1559 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-11 11:56:24.325  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.325  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.335  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:24.335  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:24.335  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:24.335  1014  1252 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:24.335  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.335  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.335  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.335  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.335  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:24.335  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-11 11:56:24.335  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-11 11:56:24.335  1014  3131 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:24.335  1014  3131 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-11 11:56:24.345  7007  7007 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-11 11:56:24.345  1014  3131 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:24.345  1014  3131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.345  1014  3131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.345  7007  7007 D BtGatt.GattService: Received start request. Starting profile...
09-11 11:56:24.345  7007  7007 D BtGatt.GattService: start()
09-11 11:56:24.345  7007  7007 D BtGatt.GattService: start()
09-11 11:56:24.345  7007  7007 I bluedroid: get_profile_interface gatt
,09-11 11:56:24.345  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:24.345  7007  7007 D BtGatt.AdvertiseManager: advertise manager created
,09-11 11:56:24.345  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-11 11:56:24.345  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-11 11:56:24.345  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-11 11:56:24.345  1014  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:24.345  1014  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.345  1014  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.345  1014  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.345  1014  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.345  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-11 11:56:24.345  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-11 11:56:24.345  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-11 11:56:24.355  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:24.355  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.355  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:24.355  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:24.355  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.355  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-11 11:56:24.355  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-11 11:56:24.355  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-11 11:56:24.365  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:24.365  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.365  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.365  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.365  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.365  7007  7007 D BtGatt.GattService: mStartError = false
,09-11 11:56:24.365  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:24.365  7007  7007 D HeadsetService: Received start request. Starting profile...
,09-11 11:56:24.365  7007  7007 D HeadsetService: start()
,09-11 11:56:24.375  7007  7007 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-11 11:56:24.375  7007  7007 D HeadsetStateMachine: make
,09-11 11:56:24.375  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-11 11:56:24.375  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-11 11:56:24.375  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-11 11:56:24.375  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:24.375  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-11 11:56:24.375  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:24.375  7007  7007 E HeadsetStateMachine: # of Max HF connection is 2
09-11 11:56:24.375  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.375  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.375  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.375  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.385  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:24.385  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-11 11:56:24.385  7007  7029 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-11 11:56:24.385  1014  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:24.385  1014  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.385  1014  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.385  1014  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.385  1014  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.395  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-11 11:56:24.395  1014  1560 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-11 11:56:24.395  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.395  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-11 11:56:24.395  7007  7029 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-11 11:56:24.395  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.395  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.395  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-11 11:56:24.395  1014  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:24.395  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-11 11:56:24.405  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:24.405  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.405  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-11 11:56:24.405  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:24.405  1014  1252 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-11 11:56:24.405  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:24.405  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-11 11:56:24.405  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-11 11:56:24.405  7007  7029 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-11 11:56:24.405  7007  7029 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-11 11:56:24.405  7007  7029 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-11 11:56:24.405  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:24.405  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:24.405  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-11 11:56:24.405  7007  7007 I bluedroid: get_profile_interface handsfree
,09-11 11:56:24.425  7007  7007 I DualScoManager: Instantiating Dual Sco Manager
,09-11 11:56:24.425  7007  7007 I DualScoManager: Set HeadsetServiceHelper
,09-11 11:56:24.425  7007  7007 D BluetoothAtMessage: createCMTIContentObservers
,09-11 11:56:24.425  1014  6147 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-11 11:56:24.425  1014  6147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:24.425  1014  6147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:24.425  1014  6147 D SettingsProvider: selectionArgs: false
,09-11 11:56:24.425  1014  6147 D SettingsProvider: selectionArgs: 1002
,09-11 11:56:24.425  1014  6147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:24.425  1014  6147 D SettingsProvider: ret = -1
,09-11 11:56:24.425  7007  7037 D HeadsetStateMachine: Enter Disconnected: -2
,09-11 11:56:24.435  7007  7007 D HeadsetService: mStartError = false
,09-11 11:56:24.435  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:24.435  7007  7037 D HeadsetStateMachine: Clear mHeadsetBrsf
09-11 11:56:24.435  7007  7037 D HeadsetStateMachine: map size, before remove : 0
09-11 11:56:24.435  7007  7037 D HeadsetStateMachine: map size, after remove: 0
09-11 11:56:24.435  7007  7007 D A2dpService: Received start request. Starting profile...
09-11 11:56:24.435  7007  7007 D A2dpService: start()
,09-11 11:56:24.435  7007  7007 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-11 11:56:24.435  7007  7007 I bluedroid: get_profile_interface avrcp
,09-11 11:56:24.445  7007  7007 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-11 11:56:24.455  7007  7007 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-11 11:56:24.455  7007  7041 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-11 11:56:24.455  7007  7007 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-11 11:56:24.455  7007  7007 D A2dpStateMachine: make
,09-11 11:56:24.465  7007  7007 I bluedroid: get_profile_interface a2dp
,09-11 11:56:24.465  7007  7043 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-11 11:56:24.465  7007  7007 E bt-btif : warning : media task started media_task_refcnt 1 
,09-11 11:56:24.465  7007  7007 D A2dpService: mStartError = false
09-11 11:56:24.465  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:24.465  7007  7042 D A2dpStateMachine: Enter Disconnected: -2
,09-11 11:56:24.465  7007  7007 I BluetoothHidServiceJni: classInitNative: succeeds
,09-11 11:56:24.465  7007  7007 D HidService: Received start request. Starting profile...
09-11 11:56:24.465  7007  7007 D HidService: start()
09-11 11:56:24.465  7007  7007 I bluedroid: get_profile_interface hidhost
09-11 11:56:24.465  7007  7007 D HidService: setHidService(): set to: null
09-11 11:56:24.465  7007  7007 D HidService: mStartError = false
09-11 11:56:24.465  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:24.465  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-11 11:56:24.475  7007  7007 I BluetoothHealthServiceJni: classInitNative: succeeds
09-11 11:56:24.475  7007  7007 D HealthService: Received start request. Starting profile...
09-11 11:56:24.475  7007  7007 D HealthService: start()
,09-11 11:56:24.475  7007  7041 D BluetoothMediaBrowser: no now playing list
09-11 11:56:24.475  7007  7007 I bluedroid: get_profile_interface health
,09-11 11:56:24.475  7007  7007 D HealthService: mStartError = false
09-11 11:56:24.475  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:24.475  7007  7041 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-11 11:56:24.475  7007  7007 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-11 11:56:24.475  7007  7007 D PanService: Received start request. Starting profile...
,09-11 11:56:24.475  7007  7007 D PanService: start()
09-11 11:56:24.475  7007  7007 D BluetoothPanServiceJni: initializeNative(L110): pan
09-11 11:56:24.475  7007  7007 I bluedroid: get_profile_interface pan
,09-11 11:56:24.475  7007  7007 D PanService: mStartError = false
,09-11 11:56:24.475  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
,09-11 11:56:24.485  7007  7007 D BluetoothMapService: Received start request. Starting profile...
,09-11 11:56:24.485  7007  7007 D BluetoothMapService: start()
,09-11 11:56:24.485  7007  7007 D BluetoothMapService: mStartError = false
,09-11 11:56:24.485  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:24.485  7007  7007 D HeadsetStateMachine: Try to query the phonestate on bind
,09-11 11:56:24.485  1427  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,09-11 11:56:24.485  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-11 11:56:24.485  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-11 11:56:24.495  1427  1437 I Telecom : BluetoothPhoneService: Result of Message : true
,09-11 11:56:24.495  7007  7007 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-11 11:56:24.495  7007  7007 D SapService: Received start request. Starting profile...
09-11 11:56:24.495  7007  7007 D SapService: start()
09-11 11:56:24.495  7007  7007 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-11 11:56:24.495  7007  7007 I bluedroid: get_profile_interface sap
09-11 11:56:24.495  7007  7007 D SapService: mStartError = false
09-11 11:56:24.495  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:24.495  7007  7007 D HeadsetStateMachine: Proxy object connected
,09-11 11:56:24.495  7007  7007 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-11 11:56:24.495  7007  7007 D HeadsetPhoneState: sendDeviceDataStateChanged
09-11 11:56:24.495  7007  7037 D HeadsetStateMachine: Disconnected process message: 11
09-11 11:56:24.495  7007  7007 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-11 11:56:24.495  7007  7007 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-11 11:56:24.495  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-11 11:56:24.495  7007  7007 D BluetoothA2dp: Proxy object connected
09-11 11:56:24.495  7007  7007 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-11 11:56:24.495  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-11 11:56:24.495  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-11 11:56:24.495  7007  7037 D HeadsetStateMachine: Disconnected process message: 18
09-11 11:56:24.495  7007  7037 D HeadsetStateMachine: Disconnected process message: 10
09-11 11:56:24.495  7007  7037 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-11 11:56:24.495  7007  7037 D HeadsetStateMachine: Disconnected process message: 11
,09-11 11:56:24.505  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-11 11:56:24.505  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-11 11:56:24.505  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:24.515  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:24.525  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-11 11:56:24.525  7007  7007 E BluetoothAdapterService(449696626): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-11 11:56:24.535  7007  7029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-11 11:56:24.535  7007  7029 I bluedroid: enable
,09-11 11:56:24.535  7007  7047 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-11 11:56:24.535  7007  7029 I bt_hci_bdroid: init
,09-11 11:56:24.535  7007  7029 I bt_vendor: bt-vendor : init
09-11 11:56:24.535  7007  7029 I bt_vendor: bt-vendor : get_bt_soc_type
09-11 11:56:24.535  7007  7029 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-11 11:56:24.535  7007  7029 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-11 11:56:24.535  7007  7029 D bt_userial_mct: userial_init
09-11 11:56:24.535  7007  7029 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-11 11:56:24.535  7007  7029 I bt_vendor: Starting hciattach daemon
09-11 11:56:24.535  7007  7029 I bt_vendor: try to set false
,09-11 11:56:24.535  7007  7029 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-11 11:56:24.535  7007  7029 I bt_vendor: Starting hciattach daemon
09-11 11:56:24.535  7007  7029 I bt_vendor: try to set true
,09-11 11:56:24.555  7051  7051 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-11 11:56:24.605  7057  7057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-11 11:56:24.615  7058  7058 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-11 11:56:24.635  7060  7060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-11 11:56:24.635  7061  7061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-11 11:56:24.645  7062  7062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-11 11:56:24.655  7063  7063 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-11 11:56:24.715   290   290 E SMD     : DCD OFF,
,09-11 11:56:24.915  7066  7066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-11 11:56:24.925  7067  7067 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-11 11:56:24.945  7007  7029 I bt_vendor: bluetooth satus is on
,09-11 11:56:24.945  7007  7049 D bt_userial_mct: userial_open(port:0)
09-11 11:56:24.945  7007  7049 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-11 11:56:24.945  7007  7049 I bt_vendor: Done intiailizing UART,
,09-11 11:56:24.945  7007  7049 I bt_vendor: Done intiailizing UART
09-11 11:56:24.945  7007  7049 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-11 11:56:24.945  7007  7049 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-11 11:56:24.955  7007  7069 D bt_userial_mct: Entering userial_read_thread(),
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_HCI
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_AVDT
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_AVRC
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_A2D
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_BNEP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_BTM
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_GAP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_PAN
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_SAP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_SDP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_GATT
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_SMP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-11 11:56:24.955  7007  7047 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-11 11:56:25.065  7007  7047 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-11 11:56:25.065  7007  7047 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40496e9 
,09-11 11:56:25.065  7007  7047 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40496e9 
,09-11 11:56:25.085  7007  7032 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-11 11:56:25.085  7007  7032 E bt-btif : Calling BTA_HhEnable
,09-11 11:56:25.095  7007  7032 E bt-btif : Adding UUID=0x111F into EIR,
09-11 11:56:25.095  7007  7032 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-11 11:56:25.095  7007  7032 E BluetoothServiceJni: populateRssiValuesNative
09-11 11:56:25.095  7007  7032 I bluedroid: getModelRssiValues
,09-11 11:56:25.095  7007  7032 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-11 11:56:25.095  7007  7032 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-11 11:56:25.095  7007  7032 D BluetoothAdapterProperties: Name is: A5-1
09-11 11:56:25.095  1014  1014 D SettingsProvider: name = bluetooth_name
,09-11 11:56:25.095  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:25.105  7007  7032 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-11 11:56:25.105  7007  7032 D BluetoothAdapterProperties: Scan Mode:20
,09-11 11:56:25.105  7007  7032 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:25.105  7007  7032 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-11 11:56:25.105  7007  7032 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-11 11:56:25.105  7007  7032 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-11 11:56:25.105  7007  7032 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-11 11:56:25.105  7007  7032 E bt-btif : btif_sock_init: !vhci_init
,09-11 11:56:25.105  7007  7032 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-11 11:56:25.115  7007  7032 D IOP_DB_BT: db_open: db_open : handle 3028054032l, read 13894 bytes onto local cache
,09-11 11:56:25.115  7007  7032 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-11 11:56:25.115  7007  7032 D IOP_DB_BT: db_query: result 1
,09-11 11:56:25.115  7007  7032 I         : iop_db_open: iop_db_open status 0
,09-11 11:56:25.115  7007  7069 E bt_mct  : hci lib postload completed
,09-11 11:56:25.115  7007  7032 D bte_conf: Device ID record 1 : primary
,09-11 11:56:25.115  7007  7032 D bte_conf:   vendorId            = 0075
,09-11 11:56:25.115  7007  7032 D bte_conf:   vendorIdSource      = 0001
09-11 11:56:25.115  7007  7032 D bte_conf:   product             = 0100
09-11 11:56:25.115  7007  7032 D bte_conf:   version             = 0200
09-11 11:56:25.115  7007  7032 D bte_conf:   clientExecutableURL = 
09-11 11:56:25.115  7007  7032 D bte_conf:   serviceDescription  = 
09-11 11:56:25.115  7007  7032 D bte_conf:   documentationURL    = 
09-11 11:56:25.115  7007  7032 D bte_conf: bte_load_did_conf no section named DID2.
09-11 11:56:25.115  7007  7032 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-11 11:56:25.115  7007  7029 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-11 11:56:25.115  7007  7029 D BluetoothAdapterProperties: ScanMode =  20
,09-11 11:56:25.125  7007  7029 D BluetoothAdapterProperties: State =  11
,09-11 11:56:25.125  1014  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-11 11:56:25.125  7007  7029 D BluetoothAdapterProperties: Setting state to 12
,09-11 11:56:25.125  7007  7029 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-11 11:56:25.125  1014  1479 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-11 11:56:25.125  1014  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-11 11:56:25.125  1014  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-11 11:56:25.125  1014  1479 D SettingsProvider: selectionArgs: false
09-11 11:56:25.125  1014  1479 D SettingsProvider: selectionArgs: 1002
09-11 11:56:25.125  1014  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-11 11:56:25.125  1014  1479 D SettingsProvider: ret = -1
,09-11 11:56:25.135  7007  7029 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-11 11:56:25.135  7007  7029 D BluetoothAdapterService: updateAdapterState state is 12
09-11 11:56:25.135  7007  7032 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-11 11:56:25.135  7007  7032 D BluetoothAdapterProperties: Scan Mode:21
09-11 11:56:25.135  7007  7032 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-11 11:56:25.135  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:25.135  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.135  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.135  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:25.135  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.145  7007  7029 D BluetoothAdapterService: Autoconnection is available 
09-11 11:56:25.145  7007  7029 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-11 11:56:25.145  7007  7029 D BluetoothAdapterService: starting service from this receiver
,09-11 11:56:25.145  1014  3130 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-11 11:56:25.145  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.145  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.145  1014  3130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.145  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.145  7007  7029 I BluetoothAdapterState: Entering On State from state = 11
,09-11 11:56:25.145  2854  2866 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.145  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:25.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.145  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:25.155  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:25.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.155  2854  2866 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:25.155  1297  6959 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:25.155  1297  6959 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.155  1297  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-11 11:56:25.155  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-11 11:56:25.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.155  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:25.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:25.165  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.165  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-11 11:56:25.165  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.165  7007  7007 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-11 11:56:25.165  7007  7015 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:25.165  1297  1308 D BluetoothPbap: onBluetoothStateChange: up=true
,09-11 11:56:25.165  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-11 11:56:25.165  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.165  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.175  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.175  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.175  1452  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.175  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:25.175  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.175  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.175  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.175  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.175  1452  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:25.175  1014  1043 D BluetoothPan: Binding service...
,09-11 11:56:25.175  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-11 11:56:25.175  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.175  6348  6363 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.175  6348  6363 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.185  7007  7007 I BluetoothPbapService: Handler(): got msg=1
,09-11 11:56:25.185  1297  1297 D BluetoothInputDevice: Proxy object connected
09-11 11:56:25.185  1427  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.185  1297  1297 D HidProfile: Bluetooth service connected
,09-11 11:56:25.185  1014  3131 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-11 11:56:25.185  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:25.185  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.185  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.185  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.185  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.185  1427  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:25.185  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-11 11:56:25.185  1948  2109 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.185  1948  2109 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.195  7007  7074 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-11 11:56:25.195  1438  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.195  1438  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.195  6448  6460 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.195  6448  6460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.195  1297  1297 D BluetoothPbap: Proxy object connected
,09-11 11:56:25.195  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-11 11:56:25.195  1297  1297 D PbapServerProfile: Bluetooth service connected
09-11 11:56:25.195  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-11 11:56:25.195  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
09-11 11:56:25.195  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-11 11:56:25.195  1014  1014 D BluetoothA2dp: Proxy object connected
09-11 11:56:25.195  7007  7074 D BluetoothSocket: bindListen(): myUserId = 0
,09-11 11:56:25.195  7007  7074 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-11 11:56:25.195  1297  1308 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:25.195  1297  1308 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.195  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-11 11:56:25.195  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.195  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.195  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.195  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.195  1297  1297 D BluetoothA2dp: Proxy object connected
09-11 11:56:25.195  1297  1297 D A2dpProfile: Bluetooth service connected
,09-11 11:56:25.205  7007  7074 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-11 11:56:25.205  7007  7074 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:25.205  7007  7074 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:25.205  7007  7074 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c9e29ef
09-11 11:56:25.205  7007  7074 D BluetoothSocket: channel: 19
09-11 11:56:25.205  7007  7074 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-11 11:56:25.205  2854  6960 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-11 11:56:25.205  2854  6960 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.205  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-11 11:56:25.205  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:25.205  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:25.205  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:25.215  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.215  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.215  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.215  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:25.215  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@191ee7d0 added. We now have 8 listener(s)
09-11 11:56:25.215  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:25.215  1427  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.215  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:25.215  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.215  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.215  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.215  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.215  1427  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:25.215  2854  2854 D BluetoothA2dp: Proxy object connected
,09-11 11:56:25.215  1014  3130 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-11 11:56:25.215  7007  7016 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.215  7007  7016 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.215  2854  2869 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.215  2854  2869 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-11 11:56:25.215  1014  3130 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-11 11:56:25.215  1014  3130 D SecContentProvider2: mCursor = null
,09-11 11:56:25.225  1014  3130 D WifiService: setWifiEnabled: false pid=6348, uid=10155
,09-11 11:56:25.225  1014  3130 D SettingsProvider: name = wifi_on
,09-11 11:56:25.225  1297  1306 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.225  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:25.225  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.225  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.225  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.225  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.225  1297  1306 E BluetoothHeadset: BluetoothHeadset service is binded
,09-11 11:56:25.225  1297  6959 D Bluetoothsap: onBluetoothStateChange: up=true
09-11 11:56:25.225  1297  6959 D Bluetoothsap: Binding service...
,09-11 11:56:25.225  1297  1297 D HeadsetProfile: Bluetooth service connected
,09-11 11:56:25.225  1297  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-11 11:56:25.225  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-11 11:56:25.225  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.225  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.235  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.235  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.235  1297  6959 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-11 11:56:25.235  1427  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.235  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-11 11:56:25.235  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.235  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-11 11:56:25.235  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.235  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:25.235  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.235  1427  1445 E BluetoothHeadset: BluetoothHeadset service is binded
09-11 11:56:25.235  1297  1297 D SapProfile: Bluetooth service connected
09-11 11:56:25.235  1297  1297 D Bluetoothsap: getConnectedDevices()
,09-11 11:56:25.235  1297  1308 D BluetoothPan: Binding service...
,09-11 11:56:25.245  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-11 11:56:25.245  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.245  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.245  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.245  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.245  1452  1709 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.245  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:25.245  1452  1709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.245  1297  1297 D BluetoothPan: BluetoothPAN Proxy object connected
09-11 11:56:25.245  1427  2770 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.245  1427  2770 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.245  1297  1306 D BluetoothMap: onBluetoothStateChange: up=true
09-11 11:56:25.245  1297  1297 D PanProfile: Bluetooth service connected
,09-11 11:56:25.245  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-11 11:56:25.245  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-11 11:56:25.245  1014  1027 D SecContentProvider2: mCursor = null
,09-11 11:56:25.245  1014  1027 D WifiService: setWifiEnabled: true pid=6348, uid=10155
09-11 11:56:25.245  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-11 11:56:25.245  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
09-11 11:56:25.245  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6348, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-11 11:56:25.245  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-11 11:56:25.245  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-11 11:56:25.245  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-11 11:56:25.245  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-11 11:56:25.245  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-11 11:56:25.245  1014  1027 D SettingsProvider: name = wifi_on
,09-11 11:56:25.245  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-11 11:56:25.245  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.245  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.245  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:25.245  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-11 11:56:25.245  1171  3601 D BluetoothAdapter: onBluetoothStateChange: up=true
09-11 11:56:25.245  1171  3601 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-11 11:56:25.245  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-11 11:56:25.255  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-11 11:56:25.255  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-11 11:56:25.255  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-11 11:56:25.255  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-11 11:56:25.255  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-11 11:56:25.255  1297  1297 D BluetoothMap: Proxy object connected
09-11 11:56:25.255  1297  1297 D MapProfile: Bluetooth service connected
09-11 11:56:25.255  1297  1297 D BluetoothMap: getConnectedDevices()
,09-11 11:56:25.255  1427  1427 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@b3c501b, true
,09-11 11:56:25.255  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-11 11:56:25.265  1427  1427 D BluetoothHeadset: registerMessageListener
,09-11 11:56:25.265  1819  1819 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-11 11:56:25.265  1171  1171 D BluetoothTile:  onBluetoothStateChange:
09-11 11:56:25.265  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-11 11:56:25.275  1014  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:25.275  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-11 11:56:25.275  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.275  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
09-11 11:56:25.275  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.275  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-11 11:56:25.275  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-11 11:56:25.275  7007  7072 D HeadsetService: registerMessageListener
,09-11 11:56:25.265  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-11 11:56:25.275  7007  7072 D HeadsetService: registerMessageListener
09-11 11:56:25.275  1171  1171 D BluetoothTile:  getBluetoothState : 12
09-11 11:56:25.275  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:25.275  7007  7037 D HeadsetStateMachine: Disconnected process message: 70
,09-11 11:56:25.275  1427  1427 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-11 11:56:25.275  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-11 11:56:25.275  7007  7037 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@df8dcfc
09-11 11:56:25.275  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.275  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:25.275  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:25.275  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:25.285  1014  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-11 11:56:25.285  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-11 11:56:25.285  1014  6147 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-11 11:56:25.285  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-11 11:56:25.285  1427  1427 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-11 11:56:25.285  1427  1427 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-11 11:56:25.285  1297  1297 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-11 11:56:25.285  1297  1297 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-11 11:56:25.285  1297  1297 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-11 11:56:25.285  1297  1297 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-11 11:56:25.285  1171  1739 D BluetoothTile:  handleUpdatestate:false name:null
,09-11 11:56:25.285  7007  7037 D HeadsetStateMachine: Disconnected process message: 9
,09-11 11:56:25.285  7007  7037 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-11 11:56:25.295  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-11 11:56:25.295  7007  7079 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-11 11:56:25.295  1014  1252 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-11 11:56:25.295  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.295  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.295  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.295  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-11 11:56:25.305   285  1074 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-11 11:56:25.305   285  1074 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-11 11:56:25.305   285  1074 V voice   : voice_set_parameters: exit with code(-2)
09-11 11:56:25.305   285  1074 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-11 11:56:25.305   285  1074 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-11 11:56:25.305   285  1074 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-11 11:56:25.305   285  1074 V audio_hw_primary: adev_set_parameters: exit
,09-11 11:56:25.305  7007  7037 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-11 11:56:25.305  7007  7079 D BluetoothSocket: bindListen(): myUserId = 0
,09-11 11:56:25.305  7007  7079 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:25.315  7007  7079 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-11 11:56:25.315  7007  7079 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:25.315  7007  7079 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:25.315  7007  7079 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d330f85
,09-11 11:56:25.315  7007  7079 D BluetoothSocket: channel: 5
09-11 11:56:25.315  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,09-11 11:56:25.315  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,09-11 11:56:25.315  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-11 11:56:25.315  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-11 11:56:25.325  7007  7007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:25.325  7007  7007 D BtConfig.SecureMode: isSecureModeOn:false
,09-11 11:56:25.335  1014  4271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-11 11:56:25.335  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.335  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.335  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:25.335  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-11 11:56:25.365  1014  6147 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-11 11:56:25.365  1948  1948 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-11 11:56:25.365  1014  1318 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-11 11:56:25.365  1014  1318 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-11 11:56:25.365  1014  1318 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.365  1014  1318 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:25.365  1014  1318 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:25.375  1948  7089 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-11 11:56:25.375  1948  1948 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-11 11:56:25.375  7007  7090 D BluetoothSocket: bindListen(): myUserId = 0
,09-11 11:56:25.375  7007  7090 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-11 11:56:25.375  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:25.385  7007  7090 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
09-11 11:56:25.385  7007  7090 D BluetoothSocket: bindListen(), new LocalSocket 
09-11 11:56:25.385  7007  7090 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-11 11:56:25.385  7007  7090 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e9a1f01
09-11 11:56:25.385  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.385  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-11 11:56:25.385  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:25.385  7007  7090 D BluetoothSocket: channel: 12
,09-11 11:56:25.385  7007  7090 I BtOppRfcommListener: Accept thread started.
,09-11 11:56:25.395  1014  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-11 11:56:25.395  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:25.395  1014  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-11 11:56:25.395  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-11 11:56:25.405  1948  7089 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-11 11:56:25.625  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-11 11:56:25.625  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:25.625  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:25.635  1014  1041 D Tethering: interfaceAdded wlan0
,09-11 11:56:25.635  1014  1128 E Tethering: No numeric data
,09-11 11:56:25.635  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:25.635  1014  1128 D Tethering: clearTetheredNotification()
,09-11 11:56:25.635  1014  1041 D Tethering: interfaceAdded p2p0
09-11 11:56:25.645  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:25.635  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
09-11 11:56:25.645  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:25.645  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:25.645  1171  1171 D HotspotTile: updateTetherState():false, false
09-11 11:56:25.645  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:25.645  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-11 11:56:25.645  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:25.645  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:25.645  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:25.655  1014  1122 V NetworkStats: performPollLocked() took 13ms
09-11 11:56:25.655  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:25.655  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:25.655  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:25.655   277  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-11 11:56:25.655   277  1002 D SoftapController: Softap fwReload - Ok
,09-11 11:56:25.665   277  1002 D CommandListener: Setting iface cfg
09-11 11:56:25.665   277  1002 D CommandListener: Trying to bring down wlan0
,09-11 11:56:25.665   277  1002 D CommandListener: Clearing all IP addresses on wlan0
,09-11 11:56:25.665  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-11 11:56:25.675  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-11 11:56:25.675  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-11 11:56:25.675  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:25.675  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-11 11:56:25.675  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:25.675  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:25.675  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:25.675  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:25.685  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:25.685  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-11 11:56:25.685  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:25.685  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:25.685  1171  1171 D HotspotTile: onReceive : 2, 0
,09-11 11:56:25.685  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:25.695  1014  1252 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:25.695  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:25.695  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:25.695  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-11 11:56:25.695  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:25.695  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:25.695  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-11 11:56:25.695  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:25.705  3577  3577 I Hs20UtilService: Starting #19
09-11 11:56:25.705  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
09-11 11:56:25.705  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:25.705  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:25.725  7098  7098 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-11 11:56:25.725  7098  7098 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-11 11:56:25.725  7098  7098 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-11 11:56:25.745  7098  7098 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-11 11:56:25.745   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7098
09-11 11:56:25.745   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-11 11:56:25.745  7098  7098 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-11 11:56:25.745  7098  7098 I wpa_supplicant: ssSupport state is = 1
09-11 11:56:25.745  7098  7098 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-11 11:56:25.745  7098  7098 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-11 11:56:25.745   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7098
09-11 11:56:25.745   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-11 11:56:25.885   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-11 11:56:25.895  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-11 11:56:25.965  7098  7098 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-11 11:56:25.965  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-11 11:56:25.975  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-11 11:56:25.975   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7098
09-11 11:56:25.975   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-11 11:56:25.975  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-11 11:56:25.975  7098  7098 I wpa_supplicant: ssSupport state is = 1,
09-11 11:56:25.975  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:25.975  7098  7098 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:25.975  7098  7098 E wpa_supplicant: SIM READ ERROR
09-11 11:56:25.975  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-11 11:56:25.975  7098  7098 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:25.975  7098  7098 E wpa_supplicant: SIM READ ERROR
09-11 11:56:25.975  7098  7098 I wpa_supplicant: Blacklist: Clear (all) 
09-11 11:56:25.975  7098  7098 I wpa_supplicant: wpa_default_ap_write_once
09-11 11:56:25.975  7098  7098 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-11 11:56:25.975  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:25.975  7098  7098 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-11 11:56:25.975  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-11 11:56:25.975  7098  7098 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-11 11:56:25.975  7098  7098 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
09-11 11:56:25.975  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-11 11:56:25.975  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:25.975  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:25.975  1014  1128 D Tethering: InitialState.processMessage what=4
09-11 11:56:25.975  1014  1128 E Tethering: No numeric data,
09-11 11:56:25.975  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:25.975  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-11 11:56:25.985  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-11 11:56:25.975  1014  1128 D Tethering: clearTetheredNotification()
09-11 11:56:25.985  1171  1171 D HotspotTile: updateTetherState():false, false
09-11 11:56:25.975  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:25.985  1014  1122 V NetworkStats: performPollLocked() took 4ms
09-11 11:56:25.985  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-11 11:56:25.985  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:25.985  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:25.985  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:25.985  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:26.045  1014  2735 D SSRM:n  : SIOP:: AP = 310,
,09-11 11:56:26.065  7098  7098 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-11 11:56:26.275  7098  7098 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-11 11:56:26.275  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-11 11:56:26.285  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-11 11:56:26.285   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7098
09-11 11:56:26.285   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-11 11:56:26.285  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-11 11:56:26.285  7098  7098 I wpa_supplicant: ssSupport state is = 1
09-11 11:56:26.285  7098  7098 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-11 11:56:26.295  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-11 11:56:26.305  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-11 11:56:26.305   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7098
,09-11 11:56:26.305   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-11 11:56:26.305  7098  7098 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-11 11:56:26.305  7098  7098 I wpa_supplicant: ssSupport state is = 1,
09-11 11:56:26.305  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-11 11:56:26.305  7098  7098 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-11 11:56:26.305  7098  7098 E wpa_supplicant: SIM READ ERROR
09-11 11:56:26.305  7098  7098 I wpa_supplicant: wpa_default_ap_write_once
09-11 11:56:26.305  7098  7098 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-11 11:56:26.305  7098  7098 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-11 11:56:26.315  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-11 11:56:26.315  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:26.315  1014  1041 D Tethering: interfaceStatusChanged p2p0, false,
,09-11 11:56:26.315  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,09-11 11:56:26.315  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:26.315  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:26.425  7098  7098 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-11 11:56:26.425  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-11 11:56:26.535  7098  7098 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-11 11:56:26.535  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-11 11:56:26.535  7098  7098 I wpa_supplicant: Skip scan - bUseNetwork false
,09-11 11:56:26.625  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-11 11:56:26.625  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-11 11:56:26.625  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-11 11:56:26.675  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-11 11:56:26.685  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-11 11:56:26.685  7098  7098 I wpa_supplicant: HOTSPOT20_ENABLE called
09-11 11:56:26.685  7098  7098 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-11 11:56:26.685  7098  7098 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-11 11:56:26.685  7098  7098 E wpa_supplicant: SIM READ ERROR
,09-11 11:56:26.685  7098  7098 I wpa_supplicant: Blacklist: Clear (all) 
,09-11 11:56:26.695  7098  7098 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-11 11:56:26.705  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
09-11 11:56:26.705  7098  7098 I wpa_supplicant: Skip scan - bUseNetwork false
,09-11 11:56:26.705  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
09-11 11:56:26.705  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:26.705  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:26.705  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:26.705  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:26.705  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:26.705  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:26.705  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-11 11:56:26.705  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-11 11:56:26.705  1171  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-11 11:56:26.715  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-11 11:56:26.715  1171  1171 D HotspotTile: onReceive : 3, 0
09-11 11:56:26.715  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:26.725  6348  6348 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:26.725  1014  6147 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:26.725  1014  6147 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:26.725  1014  1125 E WifiConfigStore: Not a HS20
09-11 11:56:26.725  1014  6147 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:26.725  1014  6147 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:26.725  1014  6147 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:26.725  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-11 11:56:26.725  3577  3577 I Hs20UtilService: Starting #20
09-11 11:56:26.725  3577  3602 I Hs20UtilService: Message received 5011
,09-11 11:56:26.735  6348  6348 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:26.735  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-11 11:56:26.735  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-11 11:56:26.735  6559  6559 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-11 11:56:26.735  6559  6559 D SecurityLogAgent: StateMachine : Current State = 1
,09-11 11:56:26.745  6559  6559 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-11 11:56:26.745  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-11 11:56:26.745  7098  7098 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-11 11:56:26.745  7098  7098 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-11 11:56:26.745  7098  7098 I wpa_supplicant: reset timer : RESET_TIMER 0
09-11 11:56:26.745  7098  7098 I wpa_supplicant: P2P: Current p2p state = IDLE
09-11 11:56:26.745  7098  7098 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-11 11:56:26.745  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-11 11:56:26.745  7098  7098 I wpa_supplicant: First Scan Start
,09-11 11:56:26.745  7098  7098 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-11 11:56:26.755  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-11 11:56:26.755  6533  6533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-11 11:56:26.755  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-11 11:56:26.755  1014  1125 I WifiNative-HAL: startHal
09-11 11:56:26.755  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ca4388c
09-11 11:56:26.755  1014  1125 I WifiNative-HAL: Could not start hal
,09-11 11:56:26.755  1014  1125 E WifiNative-wlan0: do suspend true
,09-11 11:56:26.755  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-11 11:56:26.755  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-11 11:56:26.755   277  1002 D CommandListener: Setting iface cfg
09-11 11:56:26.755   277  1002 D CommandListener: Trying to bring up p2p0
,09-11 11:56:26.755  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-11 11:56:26.755  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:26.755  1014  1148 I WifiNative-HAL: startHal
,09-11 11:56:26.765  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-11 11:56:26.765  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:26.765  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ddfd9bc
09-11 11:56:26.765  1014  1148 I WifiNative-HAL: Could not start hal
09-11 11:56:26.765  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-11 11:56:26.765  1014  1148 E WifiScanningService: could not start HAL
09-11 11:56:26.765  1014  1124 D WifiP2pService: P2pEnablingState
,09-11 11:56:26.765  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-11 11:56:26.765  1014  1124 D WifiP2pService: P2p socket connection successful
09-11 11:56:26.765  1014  1124 D WifiP2pService: P2pEnabledState
,09-11 11:56:26.765  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-11 11:56:26.765  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-11 11:56:26.765  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-11 11:56:26.765  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-11 11:56:26.765  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:26.765  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-11 11:56:26.765  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-11 11:56:26.765  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-11 11:56:26.765  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-11 11:56:26.765  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-11 11:56:26.765  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:26.765  1014  1044 D WifiDisplayController: disconnect
09-11 11:56:26.765  1014  1044 D WifiDisplayController: updateConnection
09-11 11:56:26.765  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-11 11:56:26.765  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:26.775  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-11 11:56:26.775  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-11 11:56:26.775  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-11 11:56:26.775  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-11 11:56:26.775  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-11 11:56:26.775  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-11 11:56:26.775  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-11 11:56:26.775  1014  6147 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-11 11:56:26.775  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-11 11:56:26.775  7098  7098 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-11 11:56:26.785  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-11 11:56:26.785  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:26.785  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:26.785  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
09-11 11:56:26.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:26.785  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-11 11:56:26.785  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-11 11:56:26.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-11 11:56:26.785  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
09-11 11:56:26.785  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-11 11:56:26.785  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-11 11:56:26.785  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:26.785  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:26.785  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:26.785  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  secondary type: null
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  wps: 0
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  grpcapab: 0
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  devcapab: 0
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  status: 3
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  wfdInfo: null
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-11 11:56:26.785  1014  1044 D WifiDisplayController:  SConnectInfo : null
,09-11 11:56:26.795  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:26.795  6492  6492 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-11 11:56:26.795  6492  6492 D FileShare-Client: Outbound.stopDelayTimer - ,
,09-11 11:56:26.795  6517  6517 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-11 11:56:26.805  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-11 11:56:26.805  1014  1124 D WifiP2pService: InactiveState
,09-11 11:56:26.805  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-11 11:56:26.805  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-11 11:56:26.805  7098  7098 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-11 11:56:26.805  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-11 11:56:26.805  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:27.265  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:27.265  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:27.275  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-11 11:56:27.275  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-11 11:56:27.275  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3889f504 Bundle[{}]
,09-11 11:56:27.275  6348  6401 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-11 11:56:27.275  6348  6401 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-11 11:56:27.285  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-11 11:56:27.285  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-11 11:56:27.285  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-11 11:56:27.285  6348  6401 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-11 11:56:27.285  6348  6401 I System.out: Running OutgoingSocketThread
,09-11 11:56:27.295  6348  7108 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1178)
,09-11 11:56:27.295  6348  7108 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38350
,09-11 11:56:27.295  6348  7108 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-11 11:56:27.725   290   290 E SMD     : DCD OFF
,09-11 11:56:27.935  7098  7098 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
09-11 11:56:27.935  7098  7098 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-11 11:56:27.935  7098  7098 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-11 11:56:27.935  7098  7098 I wpa_supplicant: Trying to associate with  'G700'
09-11 11:56:27.935  7098  7098 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-11 11:56:27.935  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-11 11:56:27.935  1014  7104 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-11 11:56:27.955  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:27.955  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:28.065  7098  7098 E wpa_supplicant: Cmd 35605 not handled
,09-11 11:56:28.065  7098  7098 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:28.065  7098  7098 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-11 11:56:28.065  7098  7098 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-11 11:56:28.065  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:28.065  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:28.065  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-11 11:56:28.065  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:28.065  7098  7098 I wpa_supplicant: Associated with F4.99.3E
09-11 11:56:28.065  7098  7098 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:28.065  7098  7098 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-11 11:56:28.065  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-11 11:56:28.065  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-11 11:56:28.065  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-11 11:56:28.065  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-11 11:56:28.065  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-11 11:56:28.065  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-11 11:56:28.065  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-11 11:56:28.075  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-11 11:56:28.075  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-11 11:56:28.075  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-11 11:56:28.075  7098  7098 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-11 11:56:28.075  7098  7098 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-11 11:56:28.075  7098  7098 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-11 11:56:28.075  1014  1128 E Tethering: No numeric data
09-11 11:56:28.075  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:28.075  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:28.075  1014  1125 D SecContentProvider2: mCursor = null
09-11 11:56:28.075  7098  7098 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-11 11:56:28.075  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-11 11:56:28.075  1014  1128 D Tethering: clearTetheredNotification()
09-11 11:56:28.075  7098  7098 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-11 11:56:28.075  7098  7098 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-11 11:56:28.075  7098  7098 I wpa_supplicant: Blacklist: Clear (temp) 
09-11 11:56:28.075  7098  7098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-11 11:56:28.075  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,09-11 11:56:28.075  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-11 11:56:28.075  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-11 11:56:28.085  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:28.085  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:28.085  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-11 11:56:28.085  1171  1171 D HotspotTile: updateTetherState():false, false
,09-11 11:56:28.085  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:28.085  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:28.085  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:28.085  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:28.095  1014  1122 V NetworkStats: performPollLocked() took 11ms
,09-11 11:56:28.095  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:28.095  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-11 11:56:28.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:28.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:28.095  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-11 11:56:28.105  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-11 11:56:28.105  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:28.105  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-11 11:56:28.105  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:28.105  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:28.105  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:28.105  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:28.105  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-11 11:56:28.105  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-11 11:56:28.105  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:28.115  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:28.115  1014  3130 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-11 11:56:28.115  1014  3130 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:28.115  1014  3130 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:28.115  1014  3130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:28.115  1014  3130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:28.115  3577  3577 I Hs20UtilService: Starting #21
,09-11 11:56:28.115  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:28.125  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:28.125  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-11 11:56:28.125  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-11 11:56:28.125  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-11 11:56:28.125  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-11 11:56:28.125  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-11 11:56:28.135  1297  3003 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-11 11:56:28.135  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-11 11:56:28.145   277  1002 D CommandListener: Setting iface cfg
,09-11 11:56:28.145  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,09-11 11:56:28.155  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-11 11:56:28.155  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:28.165  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:28.165  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:28.165  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:28.165  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:28.165  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:28.165  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:28.165  1014  1125 E WifiNative-wlan0: do suspend false
,09-11 11:56:28.165  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-11 11:56:28.165  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-11 11:56:28.175  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-11 11:56:28.175  1014  1125 D SecContentProvider2: mCursor = null
,09-11 11:56:28.295  6348  6401 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1179)
,09-11 11:56:28.295  6348  6401 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1179)
,09-11 11:56:28.295  6348  6401 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1184)
,09-11 11:56:28.295  6348  6401 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-11 11:56:28.295  6348  6401 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1185)
,09-11 11:56:28.305  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.305  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37aa43c9 added. We now have 2 listener(s)
,09-11 11:56:28.305  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:56:28.305  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:28.305  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.305  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.305  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9c4ace added. We now have 9 listener(s)
09-11 11:56:28.305  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.305  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:28.315  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.315  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-11 11:56:28.315  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-11 11:56:28.315  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:28.325  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.325  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2552b0fc added. We now have 3 listener(s)
,09-11 11:56:28.325  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-11 11:56:28.325  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.325  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:56:28.325  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:28.325  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:56:28.335  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:28.335  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350a5385 added. We now have 10 listener(s)
09-11 11:56:28.335  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.335  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:28.335  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:28.335  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:28.335  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-11 11:56:28.335  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.335  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.335  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:28.335  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37aa43c9 removed from the list
,09-11 11:56:28.335  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.335  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9c4ace removed from the list
,09-11 11:56:28.335  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
,09-11 11:56:28.335  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:28.335  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.335  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.345  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9c4ace not in the list
,09-11 11:56:28.345  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.345  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.345  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350a5385 removed from the list
,09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.345  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.345  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.345  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-11 11:56:28.345  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2552b0fc removed from the list
09-11 11:56:28.345  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.345  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b645da added. We now have 2 listener(s)
,09-11 11:56:28.345  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-11 11:56:28.345  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.355  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.355  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.355  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f805a0b added. We now have 9 listener(s)
09-11 11:56:28.355  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.355  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:28.355  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.355  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:28.365  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:28.365  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:28.365  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.365  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a1a301 added. We now have 3 listener(s)
,09-11 11:56:28.365  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.365  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.365  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:56:28.365  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-11 11:56:28.365  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.365  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-11 11:56:28.365  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3642e5a6 added. We now have 10 listener(s)
09-11 11:56:28.365  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:28.365  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:28.365  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:28.365  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:28.365  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:28.365  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:28.375  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:28.375  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:28.385  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:28.385  7111  7111 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-11 11:56:28.385  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:28.385  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-11 11:56:28.385  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:28.385  7111  7111 I dhcpcd  : version 5.5.6 starting
,09-11 11:56:28.385  7007  7072 D BtGatt.GattService: registerClient() - UUID=dfa0c801-9d9c-45dc-8450-407989825dc1
,09-11 11:56:28.395  7111  7111 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-11 11:56:28.435  7007  7032 D BtGatt.GattService: onClientRegistered() - UUID=dfa0c801-9d9c-45dc-8450-407989825dc1, clientIf=6,
,09-11 11:56:28.435  6348  6363 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,09-11 11:56:28.435  7007  7015 D BtGatt.GattService: start scan with filters
,09-11 11:56:28.445  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-11 11:56:28.445  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:28.445  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:28.445  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-11 11:56:28.445  7007  7036 D BtGatt.ScanManager: handling starting scan
09-11 11:56:28.445  7007  7036 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1acdd372
09-11 11:56:28.445  7111  7111 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-11 11:56:28.445  7111  7111 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-11 11:56:28.445  7111  7111 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-11 11:56:28.445  7111  7111 I dhcpcd  : bssid match
,09-11 11:56:28.445  7111  7111 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
09-11 11:56:28.445  7007  7032 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-11 11:56:28.445  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.445  7007  7036 D BtGatt.ScanManager: allow scan with filters
09-11 11:56:28.445  7007  7036 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-11 11:56:28.445  7007  7036 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-11 11:56:28.445  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:28.445  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:28.445  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:28.445  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-11 11:56:28.445  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.455  7007  7036 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:28.455  7007  7036 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-11 11:56:28.455  7007  7032 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-11 11:56:28.455  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.455  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-11 11:56:28.455  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-11 11:56:28.455  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.465  6348  6401 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-11 11:56:28.465  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:28.465  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-11 11:56:28.465  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.465  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:28.465  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-11 11:56:28.465  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:28.465  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:28.465  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:28.465  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-11 11:56:28.465  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:28.475  7007  7076 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:28.475  7007  7016 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:28.475  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:28.475  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:28.475  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-11 11:56:28.475  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:28.485  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-11 11:56:28.485  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:28.485  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-11 11:56:28.485  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:28.485  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:28.485  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.485  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18b645da removed from the list
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f805a0b removed from the list
09-11 11:56:28.485  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:28.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.485  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.485  7007  7036 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 3
,09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.485  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f805a0b not in the list
09-11 11:56:28.485  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3642e5a6 removed from the list
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.485  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-11 11:56:28.485  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.485  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a1a301 removed from the list
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.485  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a7b632 added. We now have 2 listener(s)
,09-11 11:56:28.485  7007  7036 D BtGatt.ScanManager: filter size is 1
09-11 11:56:28.485  7007  7036 D BtGatt.ScanManager: delete FilterIndex - 3
,09-11 11:56:28.495  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-11 11:56:28.495  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.495  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.495  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.495  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b97ff83 added. We now have 9 listener(s)
09-11 11:56:28.495  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.495  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-11 11:56:28.495  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.495  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-11 11:56:28.495  7007  7036 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:28.495  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-11 11:56:28.495  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.495  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:28.495  7007  7036 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-11 11:56:28.505  7007  7032 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-11 11:56:28.505  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.505  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:28.505  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:28.505  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-11 11:56:28.505  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.505  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.505  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bceb139 added. We now have 3 listener(s)
,09-11 11:56:28.515  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:56:28.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-11 11:56:28.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.515  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c17037e added. We now have 10 listener(s)
,09-11 11:56:28.515  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:28.515  7111  7111 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
09-11 11:56:28.515  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:28.515  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:28.515  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:28.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-11 11:56:28.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:28.515  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:28.525  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:28.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-11 11:56:28.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:28.525  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-11 11:56:28.525  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-11 11:56:28.535  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-11 11:56:28.535  7007  7072 D BtGatt.GattService: registerClient() - UUID=fa1b9e74-8d52-4c4d-ae1a-1bbded5443e8
,09-11 11:56:28.555  7111  7111 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-11 11:56:28.575  7007  7032 D BtGatt.GattService: onClientRegistered() - UUID=fa1b9e74-8d52-4c4d-ae1a-1bbded5443e8, clientIf=6,
09-11 11:56:28.575  6348  6362 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-11 11:56:28.585  7007  7015 D BtGatt.GattService: start scan with filters
,09-11 11:56:28.585  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:28.585  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:28.585  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:28.585  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-11 11:56:28.585  7007  7036 D BtGatt.ScanManager: handling starting scan
,09-11 11:56:28.585  7007  7032 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-11 11:56:28.585  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.585  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:28.585  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:28.585  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-11 11:56:28.585  7007  7036 D BtGatt.ScanManager: allow scan with filters
09-11 11:56:28.585  7007  7036 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-11 11:56:28.585  7007  7036 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6,
,09-11 11:56:28.595  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:28.595  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-11 11:56:28.595  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.595  7007  7036 D BtGatt.ScanManager: Starting BLE batch scan
,09-11 11:56:28.595  7007  7036 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-11 11:56:28.595  7007  7032 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-11 11:56:28.595  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.605  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-11 11:56:28.605  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.605  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,09-11 11:56:28.605  6348  6401 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-11 11:56:28.605  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:28.605  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:28.605  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:28.605  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.605  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.605  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:28.605  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.605  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a7b632 removed from the list
09-11 11:56:28.605  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-11 11:56:28.605  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b97ff83 removed from the list
09-11 11:56:28.605  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:28.605  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.605  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.605  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-11 11:56:28.605  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.605  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.615  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b97ff83 not in the list
,09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:28.615  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:28.615  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:28.615  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-11 11:56:28.625  7007  7076 D BtGatt.GattService: stopScan() - queue size =1
,09-11 11:56:28.625  7007  7072 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:28.635  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:28.635  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:28.635  7007  7036 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 4
,09-11 11:56:28.635  7007  7036 D BtGatt.ScanManager: filter size is 1
09-11 11:56:28.635  7007  7036 D BtGatt.ScanManager: delete FilterIndex - 4
,09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:28.635  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-11 11:56:28.635  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:28.635  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:28.635  7007  7036 D BtGatt.ScanManager: stopping BLe Batch
,09-11 11:56:28.635  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-11 11:56:28.645  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-11 11:56:28.645  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.645  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.645  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c17037e removed from the list
09-11 11:56:28.645  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.645  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.645  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:28.645  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:28.645  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:28.645  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-11 11:56:28.645  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.645  7007  7036 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-11 11:56:28.645  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.645  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.645  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bceb139 removed from the list
,09-11 11:56:28.645  7007  7032 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-11 11:56:28.645  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.645  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.645  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bd98a added. We now have 2 listener(s)
,09-11 11:56:28.645  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-11 11:56:28.645  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.645  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.655  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.655  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45fdbfb added. We now have 9 listener(s)
09-11 11:56:28.655  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.655  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:28.655  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.655  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:28.665  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:28.665  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:28.665  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.665  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34584e71 added. We now have 3 listener(s)
,09-11 11:56:28.665  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.665  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.675  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-11 11:56:28.675  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.675  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.675  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.675  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de60456 added. We now have 10 listener(s)
09-11 11:56:28.675  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:28.675  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-11 11:56:28.675  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-11 11:56:28.675  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-11 11:56:28.675  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-11 11:56:28.675  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-11 11:56:28.675  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-11 11:56:28.685  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-11 11:56:28.685  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-11 11:56:28.695  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-11 11:56:28.695  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-11 11:56:28.695  6348  6401 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-11 11:56:28.695  7007  7015 D BtGatt.GattService: registerClient() - UUID=7f0f7b41-33f3-45af-9f3d-3400ecae91d8
,09-11 11:56:28.745  7007  7032 D BtGatt.GattService: onClientRegistered() - UUID=7f0f7b41-33f3-45af-9f3d-3400ecae91d8, clientIf=6
09-11 11:56:28.745  6348  6359 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-11 11:56:28.745  7007  7016 D BtGatt.GattService: start scan with filters
09-11 11:56:28.745  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-11 11:56:28.745  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-11 11:56:28.745  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-11 11:56:28.745  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: handling starting scan
09-11 11:56:28.745  7007  7032 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-11 11:56:28.745  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: allow scan with filters
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-11 11:56:28.745  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-11 11:56:28.745  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: Starting BLE batch scan
09-11 11:56:28.745  7007  7036 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-11 11:56:28.745  7007  7032 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-11 11:56:28.745  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.745  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:28.745  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-11 11:56:28.745  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-11 11:56:28.755  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-11 11:56:28.755  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.755  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-11 11:56:28.765  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-11 11:56:28.765  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:28.765  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.765  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.765  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bd98a removed from the list
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.765  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45fdbfb removed from the list
09-11 11:56:28.765  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.765  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-11 11:56:28.765  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.765  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45fdbfb not in the list
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-11 11:56:28.765  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-11 11:56:28.765  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-11 11:56:28.765  7007  7076 D BtGatt.GattService: stopScan() - queue size =1
09-11 11:56:28.765  7007  7078 D BtGatt.GattService: unregisterClient() - clientIf=6
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-11 11:56:28.775  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-11 11:56:28.775  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-11 11:56:28.775  7007  7036 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 5
09-11 11:56:28.775  7007  7036 D BtGatt.ScanManager: filter size is 1
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:28.775  7007  7036 D BtGatt.ScanManager: delete FilterIndex - 5
09-11 11:56:28.775  7007  7032 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-11 11:56:28.775  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.775  7007  7036 D BtGatt.ScanManager: stopping BLe Batch
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-11 11:56:28.775  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-11 11:56:28.775  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.775  7007  7032 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-11 11:56:28.775  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-11 11:56:28.785  7007  7036 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de60456 removed from the list
09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.785  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.785  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.785  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34584e71 removed from the list
09-11 11:56:28.785  6348  6348 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-11 11:56:28.785  6348  6348 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cd60fe2 added. We now have 2 listener(s)
09-11 11:56:28.785  7007  7032 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-11 11:56:28.785  7007  7032 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-11 11:56:28.785  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-11 11:56:28.785  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.785  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.785  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac7cf73 added. We now have 9 listener(s)
09-11 11:56:28.785  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-11 11:56:28.785  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-11 11:56:28.795  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-11 11:56:28.805  6348  6401 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-11 11:56:28.805  6348  6401 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-11 11:56:28.805  6348  6401 D io.jxcore.node.ConnectivityMonitor: start: OK
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f615aa9 added. We now have 3 listener(s)
,09-11 11:56:28.805  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.805  6348  6348 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc9482e added. We now have 10 listener(s)
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-11 11:56:28.805  6348  6401 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-11 11:56:28.805  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-11 11:56:28.805  6348  6401 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.805  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cd60fe2 removed from the list
,09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.805  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac7cf73 removed from the list
09-11 11:56:28.805  6348  6401 D io.jxcore.node.ConnectivityMonitor: stop
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.805  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.805  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.805  6348  6401 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac7cf73 not in the list,
09-11 11:56:28.805  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-11 11:56:28.805  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-11 11:56:28.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-11 11:56:28.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-11 11:56:28.815  6348  6401 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc9482e removed from the list
09-11 11:56:28.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-11 11:56:28.815  6348  6401 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-11 11:56:28.815  6348  6401 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-11 11:56:28.815  6348  6401 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-11 11:56:28.815  6348  6401 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f615aa9 removed from the list
,09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-11 11:56:28.815  6348  6401 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-11 11:56:28.815  6348  7146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1192, name: My test thread name)
,09-11 11:56:28.815  6348  7146 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1192, thread name: My test thread name)
09-11 11:56:28.815  6348  7146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-11 11:56:28.815  6348  7147 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1194, name: My test thread name),
09-11 11:56:28.815  6348  7147 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1194, thread name: My test thread name)
09-11 11:56:28.815  6348  7147 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1194, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-11 11:56:28.825  6348  6401 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-11 11:56:28.825  6348  6401 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-11 11:56:28.825  6348  6401 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-11 11:56:28.825  6348  6401 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-11 11:56:28.825  6348  6401 D com.test.thalitest.ThaliTestRunner: Total duration: 23338 ms
09-11 11:56:28.825  6348  6401 I jxcore-log: *Native tests were executed*
09-11 11:56:28.825  6348  6401 I jxcore-log: 
,09-11 11:56:28.825  6348  6401 I jxcore-log: Total number of executed tests:  80
09-11 11:56:28.825  6348  6401 I jxcore-log: 
09-11 11:56:28.825  6348  6401 I jxcore-log: Number of passed tests:  80
09-11 11:56:28.825  6348  6401 I jxcore-log: 
09-11 11:56:28.825  6348  6401 I jxcore-log: Number of failed tests:  0
09-11 11:56:28.825  6348  6401 I jxcore-log: 
,09-11 11:56:28.825  6348  6401 I jxcore-log: Number of ignored tests:  0
09-11 11:56:28.825  6348  6401 I jxcore-log: 
09-11 11:56:28.825  6348  6401 I jxcore-log: Total duration:  23338
09-11 11:56:28.825  6348  6401 I jxcore-log: 
09-11 11:56:28.825  6348  6401 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-11 11:56:28.825  6348  6401 I jxcore-log: ,
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6348 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.835  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-11 11:56:28.835  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
09-11 11:56:28.845  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.845  6348  6401 I jxcore-log: 
,09-11 11:56:28.855  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.855  6348  6401 I jxcore-log: 
09-11 11:56:28.855  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.855  6348  6401 I jxcore-log: 
,09-11 11:56:28.855  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-11 11:56:28.855  6348  6401 I jxcore-log: 
,09-11 11:56:28.975  1014  1125 E WifiNative-wlan0: do suspend true
,09-11 11:56:28.985  6348  6348 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:28.985  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:28.985  6348  6401 I jxcore-log: 
,09-11 11:56:29.005  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-11 11:56:29.005  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-11 11:56:29.005  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-11 11:56:29.015  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:29.015  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.015  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-11 11:56:29.015  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,09-11 11:56:29.015  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.015  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-11 11:56:29.015  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:29.015  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210],
,09-11 11:56:29.015  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:29.015  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-11 11:56:29.015  1014  1127 D ConnectivityService: Adding iface wlan0 to network 504
,09-11 11:56:29.025  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-11 11:56:29.025  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-11 11:56:29.025  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-11 11:56:29.025  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-11 11:56:29.025  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-11 11:56:29.035  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:29.035  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:29.035  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.035  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.035  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:29.035  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:29.045  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:29.045  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:29.045  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:29.045  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:29.045  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:29.045  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-11 11:56:29.045  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-11 11:56:29.045  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-11 11:56:29.045  3577  3577 I Hs20UtilService: Starting #22
,09-11 11:56:29.055  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:29.055  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
09-11 11:56:29.055  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-11 11:56:29.055  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-11 11:56:29.055  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-11 11:56:29.055  1014  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-11 11:56:29.055  1014  1127 D ConnectivityService: LTETest block dns file not exists
09-11 11:56:29.055  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-11 11:56:29.065  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-11 11:56:29.065  1014  1127 E ConnectivityService: updateNetworkInfo()
09-11 11:56:29.065  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-11 11:56:29.065  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-11 11:56:29.065  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-11 11:56:29.065  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-11 11:56:29.065  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.065  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-11 11:56:29.065  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-11 11:56:29.065  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-11 11:56:29.065  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-11 11:56:29.075  1014  7109 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-11 11:56:29.075  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-11 11:56:29.075  1014  1127 D ConnectivityService:    accepting network in place of null
,09-11 11:56:29.075  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-11 11:56:29.075   277   998 D EnterpriseController: uids 1000
09-11 11:56:29.075   277   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-11 11:56:29.075   277   998 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-11 11:56:29.075  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-11 11:56:29.075  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-11 11:56:29.075  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-11 11:56:29.075  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-11 11:56:29.075  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-11 11:56:29.075  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-11 11:56:29.075  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:29.075  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-11 11:56:29.085  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-11 11:56:29.085  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
09-11 11:56:29.085  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:29.085  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.085  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.095  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-11 11:56:29.095  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-11 11:56:29.095  1014  1122 V NetworkStats: updateIfacesLocked()
09-11 11:56:29.095  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-11 11:56:29.095  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.095  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-11 11:56:29.095  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-11 11:56:29.095  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-11 11:56:29.095  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-11 11:56:29.095  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-11 11:56:29.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.095  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-11 11:56:29.095  1171  1718 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-11 11:56:29.095  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-11 11:56:29.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.095  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.095  3846  5025 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-11 11:56:29.095  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.105  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:29.105  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-11 11:56:29.105  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:29.105  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:29.105  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-11 11:56:29.105  3577  3577 I Hs20UtilService: Starting #23
,09-11 11:56:29.105  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.105  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.105  3577  3602 I Hs20UtilService: Message received 5007
,09-11 11:56:29.105  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-11 11:56:29.105  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-11 11:56:29.105  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-11 11:56:29.105  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-11 11:56:29.105  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-11 11:56:29.105  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-11 11:56:29.105  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-11 11:56:29.105  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-11 11:56:29.105  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-11 11:56:29.105  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-11 11:56:29.105  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-11 11:56:29.105  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:29.115  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.115  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:29.125  1014  1560 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-11 11:56:29.125  1014  1560 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-11 11:56:29.125  1014  1560 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:29.125  1014  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:29.125  1014  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-11 11:56:29.125  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-11 11:56:29.125  3577  3577 I Hs20UtilService: Starting #24
,09-11 11:56:29.125  3577  3602 I Hs20UtilService: Message received 5007
09-11 11:56:29.125  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-11 11:56:29.135  1014  1318 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-11 11:56:29.135  1014  1479 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-11 11:56:29.135  1014  1479 D SecContentProvider2: mCursor = null
,09-11 11:56:29.135  1014  3130 D SecContentProvider2: uri = 15 selection = getToastGravity
09-11 11:56:29.135  1014  3130 D SecContentProvider2: mCursor = null
,09-11 11:56:29.135  1014  1137 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-11 11:56:29.135  1014  1137 D SecContentProvider2: mCursor = null
,09-11 11:56:29.135  1014  1559 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-11 11:56:29.135  1014  1559 D SecContentProvider2: mCursor = null
,09-11 11:56:29.145  1014  1027 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-11 11:56:29.145  1014  1027 D SecContentProvider2: mCursor = null
09-11 11:56:29.145  6348  6348 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-11 11:56:29.145  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:29.145  6348  6401 I jxcore-log: 
09-11 11:56:29.145  1014  1560 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-11 11:56:29.145  1014  1560 D SecContentProvider2: mCursor = null
,09-11 11:56:29.165  7148  7148 D AndroidRuntime: ,
09-11 11:56:29.165  7148  7148 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-11 11:56:29.165  7148  7148 D AndroidRuntime: CheckJNI is OFF,
,09-11 11:56:29.165  7148  7148 D AndroidRuntime: readGMSProperty: start
09-11 11:56:29.165  7148  7148 D AndroidRuntime: readGMSProperty: already setted!!
09-11 11:56:29.165  7148  7148 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-11 11:56:29.165  7148  7148 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-11 11:56:29.165  7148  7148 D AndroidRuntime: readGMSProperty: end
09-11 11:56:29.165  7148  7148 D AndroidRuntime: addProductProperty: start
,09-11 11:56:29.175   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-11 11:56:29.185  1014  1558 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-11 11:56:29.185  1171  1171 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-11 11:56:29.195  1014  7109 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-11 11:56:29.245  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 11 Sep 2016 09:56:29 GMT], X-Android-Received-Millis=[1473587789256], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473587789230]}
,09-11 11:56:29.245  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-11 11:56:29.245  1014  7109 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-11 11:56:29.245  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,09-11 11:56:29.245  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-11 11:56:29.245  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-11 11:56:29.245  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-11 11:56:29.245  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-11 11:56:29.245  3846  5025 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
09-11 11:56:29.255  1171  1718 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-11 11:56:29.255  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-11 11:56:29.255  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-11 11:56:29.255  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-11 11:56:29.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-11 11:56:29.265  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-11 11:56:29.285  6348  6348 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-11 11:56:29.285  6348  6401 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-11 11:56:29.285  6348  6401 I jxcore-log: ,
,09-11 11:56:29.335  7148  7148 E AffinityControl: AffinityControl: registerfunction enter
,09-11 11:56:29.355  7148  7148 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-11 11:56:29.375  1014  4271 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-11 11:56:29.375  1014  4271 D PackageManager: START PACKAGE DELETE: observer{995988318}
09-11 11:56:29.375  1014  4271 D PackageManager: pkg{<packageName>}
09-11 11:56:29.375  1014  4271 D PackageManager: user{0}
,09-11 11:56:29.375  1014  4271 D PackageManager: caller{2000}
09-11 11:56:29.375  1014  4271 D PackageManager: flags{2}
09-11 11:56:29.375  1014  4271 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-11 11:56:29.375  1014  4271 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
09-11 11:56:29.375  1014  4271 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-11 11:56:29.375  1014  4271 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-11 11:56:29.375  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-11 11:56:29.375  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-11 11:56:29.375  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-11 11:56:29.375  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-11 11:56:29.375  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-11 11:56:29.375  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-11 11:56:29.375  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-11 11:56:29.375  1014  1039 I ActivityManager: Killing 6348:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-11 11:56:29.395  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{1e9c3b97 u0 com.test.thalitest/.MainActivity t128}
,09-11 11:56:29.405  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,09-11 11:56:29.475  1014  4271 I WindowState: WIN DEATH: Window{37af5177 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-11 11:56:29.475   257  1509 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,09-11 11:56:29.475   257   450 I SurfaceFlinger: id=14 Removed NainActivit (-2/9),
09-11 11:56:29.475   257   448 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-11 11:56:29.475  1014  4271 D InputDispatcher: Focus left window: 6348
,09-11 11:56:29.485  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-11 11:56:29.485  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-11 11:56:29.495  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-11 11:56:29.495  1014  1054 I ActivityManager:   Force finishing activity ActivityRecord{1e9c3b97 u0 com.test.thalitest/.MainActivity t128 f}
,09-11 11:56:29.505  1014  1054 W ActivityManager: Duplicate finish request for ActivityRecord{1e9c3b97 u0 com.test.thalitest/.MainActivity t128 f}
,09-11 11:56:29.515  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-11 11:56:29.545  5807  5807 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 697us total 24.367ms
,09-11 11:56:29.555  3062  3062 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-11 11:56:29.555  1014  1039 D InputDispatcher: Focused application released
,09-11 11:56:29.565  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-11 11:56:29.575  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-11 11:56:29.585  3846  3846 I art     : Explicit concurrent mark sweep GC freed 18571(1126KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 15MB/26MB, paused 1.339ms total 76.066ms
,09-11 11:56:29.585  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-11 11:56:29.595  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-11 11:56:29.595  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-11 11:56:29.595  3062  3062 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-11 11:56:29.595  1819  1819 E SamsungIME: mOCRHelper is null
,09-11 11:56:29.605  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-11 11:56:29.615  1948  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-11 11:56:29.625  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-11 11:56:29.625  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.625  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-11 11:56:29.635  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-11 11:56:29.635  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-11 11:56:29.635  1014  1122 V NetworkStats: performPollLocked() took 14ms
09-11 11:56:29.635  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:29.645  3062  3062 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-11 11:56:29.655  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
09-11 11:56:29.655  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-11 11:56:29.655  1014  1038 W TextServicesManagerService: no available spell checker services found
,09-11 11:56:29.655  3062  3062 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-11 11:56:29.655  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:56:29.655  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:29.665  3605  3605 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Sep 11 11:56:29 GMT+02:00 2016
,09-11 11:56:29.695  6611  6611 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-11 11:56:29.705  1014  4271 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-11 11:56:29.705  1014  4271 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-11 11:56:29.705  1014  4271 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:29.705  1014  4271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:29.705  1014  4271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-11 11:56:29.715  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-11 11:56:29.715  1014  1014 I art     : Explicit concurrent mark sweep GC freed 70562(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 28MB/42MB, paused 3.054ms total 199.249ms
,09-11 11:56:29.725  1014  1054 I art     : WaitForGcToComplete blocked for 164.451ms for cause Explicit
,09-11 11:56:29.755  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-11 11:56:29.755  1014  1046 I PowerManagerService: [PWL] Off : 75s ago
09-11 11:56:29.755  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-11 11:56:29.755  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-11 11:56:29.755  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=23318)
09-11 11:56:29.755  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=7007, ws=null) (elapsedTime=4803)
,09-11 11:56:29.755  3605  3605 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-11 11:56:29.765  1014  1027 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,09-11 11:56:29.765  1014  1027 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-11 11:56:29.775  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-11 11:56:29.775  1014  1491 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-11 11:56:29.775  1014  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-11 11:56:29.775  1014  1479 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-11 11:56:29.775  1014  1479 D SecContentProvider2: mCursor = null
,09-11 11:56:29.775  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.775  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.775  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.775  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:29.785  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-11 11:56:29.785  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-11 11:56:29.785  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-11 11:56:29.795  3605  3605 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-11 11:56:29.805  7169  7169 E Zygote  : MountEmulatedStorage()
09-11 11:56:29.805  7169  7169 E Zygote  : v2
09-11 11:56:29.805  7169  7169 I libpersona: KNOX_SDCARD checking this for 10094
09-11 11:56:29.805  7169  7169 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:29.805  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
09-11 11:56:29.805  1014  1027 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7169 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
09-11 11:56:29.805  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:29.805  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:29.805  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-11 11:56:29.815  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-11 11:56:29.815  3062  3062 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-11 11:56:29.815  3062  3062 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-11 11:56:29.815  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:29.815  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.815  3062  3062 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-11 11:56:29.815  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:29.815  3062  3062 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
09-11 11:56:29.815  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:29.825  3605  3605 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-11 11:56:29.825  3605  3605 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-11 11:56:29.835  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-11 11:56:29.835  7178  7178 E Zygote  : MountEmulatedStorage()
09-11 11:56:29.835  7178  7178 E Zygote  : v2
09-11 11:56:29.835  7178  7178 I libpersona: KNOX_SDCARD checking this for 10044
09-11 11:56:29.835  7178  7178 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:29.835  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:29.845  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-11 11:56:29.845  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:29.845  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7178 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-11 11:56:29.845  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:29.855  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-11 11:56:29.855  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-11 11:56:29.855  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:29.855  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:29.865  7169  7169 D ActivityThread: Added TimaKeyStore provider
09-11 11:56:29.865  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.865  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
09-11 11:56:29.865  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.865  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:29.865  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:29.865  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-11 11:56:29.875  7195  7195 E Zygote  : MountEmulatedStorage(),
09-11 11:56:29.875  7195  7195 E Zygote  : v2
09-11 11:56:29.875  7195  7195 I libpersona: KNOX_SDCARD checking this for 10149
09-11 11:56:29.875  7195  7195 I libpersona: KNOX_SDCARD not a persona,
09-11 11:56:29.875  7195  7195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:29.875  7195  7195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:29.875  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7195 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-11 11:56:29.875  7195  7195 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:29.885  1014  1318 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-11 11:56:29.885  1014  1318 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-11 11:56:29.885  1014  1318 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-11 11:56:29.895  3062  3062 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-11 11:56:29.895  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,09-11 11:56:29.905  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:29.905  7178  7178 D ActivityThread: Added TimaKeyStore provider
09-11 11:56:29.905  6985  7194 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-11 11:56:29.915  7195  7195 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:29.915  7195  7195 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:29.925  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:56:29.925   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-11 11:56:29.925  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-11 11:56:29.935  1014  1026 D InputDispatcher: Focus entered window: 3062
,09-11 11:56:29.945  3062  3062 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-11 11:56:29.945  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-11 11:56:29.945  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-11 11:56:29.955  6985  7194 I art     : Explicit concurrent mark sweep GC freed 601(45KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 3.620ms total 35.077ms
,09-11 11:56:29.965  3062  3062 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-11 11:56:29.985  6126  6144 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-11 11:56:29.985  6126  6144 D BadgeProvider: sendNotify, [notify] : null
09-11 11:56:29.985  6126  6144 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-11 11:56:29.985  6126  6144 D BadgeProvider: update, [BadgeCount] : badgecount=0
,09-11 11:56:29.985  6126  6144 D BadgeProvider: update, [UpdateCount] : 1
,09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-11 11:56:30.005  7178  7178 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-11 11:56:30.005  1014  1026 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-11 11:56:30.025  7169  7169 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-11 11:56:30.025  7169  7169 D elm:15183: ELMEngine.ELMEngine( context ).
,09-11 11:56:30.025  7169  7169 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-11 11:56:30.025  1014  1026 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6348 uid 10155
,09-11 11:56:30.025  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-11 11:56:30.025  1014  1332 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-11 11:56:30.025  1014  1332 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-11 11:56:30.035  3062  3062 V ActivityThread: updateVisibility : ActivityRecord{295b0998 token=android.os.BinderProxy@9174bcf {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-11 11:56:30.035  1014  1332 W ActivityManager: userId = 0, bbcId = -10000
09-11 11:56:30.035  1014  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:30.035  1014  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-11 11:56:30.035  3062  3062 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9174bcf time:154329
,09-11 11:56:30.045  1819  1819 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-11 11:56:30.045  1014  7216 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-11 11:56:30.045  7169  7169 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-11 11:56:30.045  3605  7168 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-11 11:56:30.055  1014  1044 W ActivityManager: mDVFSHelper.release()
09-11 11:56:30.055  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b25f9d2 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:154341
,09-11 11:56:30.055  3605  7168 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-11 11:56:30.055  7195  7195 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-11 11:56:30.055  7195  7195 D ThemeInfoUtil: isCurrentFestival = false
,09-11 11:56:30.055  7169  7169 D elm:15183: ElmAgentService : onCreate()
,09-11 11:56:30.055  7169  7219 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-11 11:56:30.055  7169  7219 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-11 11:56:30.055  7169  7219 D elm:15183: MDMBridge.getInstance()
09-11 11:56:30.055  7169  7219 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-11 11:56:30.075  7169  7219 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-11 11:56:30.075  3605  3605 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-11 11:56:30.075  3219  3219 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-11 11:56:30.075  3219  3219 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-11 11:56:30.075  3219  3219 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-11 11:56:30.075  3219  3219 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:30.075  3219  3219 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:30.075  3219  3219 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:30.075  3219  3219 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:30.075  3219  3219 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:30.075  3219  3219 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-11 11:56:30.085  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-11 11:56:30.085  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.095  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.095  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.095  1014  1054 I art     : Explicit concurrent mark sweep GC freed 12992(1164KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 9.378ms total 362.948ms
,09-11 11:56:30.095  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-11 11:56:30.095  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.105  7222  7222 E Zygote  : MountEmulatedStorage()
,09-11 11:56:30.105  7222  7222 E Zygote  : v2
09-11 11:56:30.105  7222  7222 I libpersona: KNOX_SDCARD checking this for 1000
,09-11 11:56:30.105  7222  7222 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:30.115  1014  1026 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-11 11:56:30.115  7222  7222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.115  7222  7222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-11 11:56:30.115  7222  7222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.135  7169  7169 D elm:15183: ElmAgentService : onDestroy().
,09-11 11:56:30.135  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-11 11:56:30.135  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.135  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.135  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.135  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.155  7239  7239 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.155  7239  7239 I libpersona: KNOX_SDCARD checking this for 10152
09-11 11:56:30.155  7239  7239 E Zygote  : v2
09-11 11:56:30.155  7239  7239 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:30.155  7239  7239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.155  1014  1026 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7239 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-11 11:56:30.155  7239  7239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.165  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-11 11:56:30.165  7239  7239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.165  7222  7222 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.165  7222  7222 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.185  7239  7239 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.185  7239  7239 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.215  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:30.235  1014  1054 D PackageManager: delete codoeFile: 
,09-11 11:56:30.245  7222  7222 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-11 11:56:30.245  1014  1252 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-11 11:56:30.245  7239  7239 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-11 11:56:30.245  1014  1252 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-11 11:56:30.245  1014  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:30.245  1014  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-11 11:56:30.245  1014  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-11 11:56:30.245  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-11 11:56:30.245  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-11 11:56:30.245  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:30.255  1014  6147 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-11 11:56:30.255  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.255  1014  1054 D PackageManager: result of delete: 1{995988318}
,09-11 11:56:30.255  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.255  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.255  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.265  7178  7178 D NearbySource: Nearby Source Create!
,09-11 11:56:30.265  7178  7178 D NearbyContext: Nearby Context Create!
,09-11 11:56:30.265  7148  7148 D AndroidRuntime: Shutting down VM
,09-11 11:56:30.265  7255  7255 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.265  7255  7255 E Zygote  : v2
09-11 11:56:30.265  7255  7255 I libpersona: KNOX_SDCARD checking this for 1000
09-11 11:56:30.265  7255  7255 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.265  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.265  1014  6147 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7255 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-11 11:56:30.275  1014  1491 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-11 11:56:30.275  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.275  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-11 11:56:30.275  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.275  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:30.285  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-11 11:56:30.285  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-11 11:56:30.285  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-11 11:56:30.285  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-11 11:56:30.285  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
09-11 11:56:30.285  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-11 11:56:30.285  1014  1014 D RCPManagerService: PackageReceiver onReceive()
09-11 11:56:30.285  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-11 11:56:30.285  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.285  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-11 11:56:30.285  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:30.295  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-11 11:56:30.295  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.295  1014  6147 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-11 11:56:30.295  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-11 11:56:30.295  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.295  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.295  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.295  1014  6147 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.295  7255  7255 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.315  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-11 11:56:30.315  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-11 11:56:30.315   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-11 11:56:30.315   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
09-11 11:56:30.315  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.315  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-11 11:56:30.315  7271  7271 E Zygote  : MountEmulatedStorage()
,09-11 11:56:30.315  7271  7271 E Zygote  : v2
,09-11 11:56:30.315  7271  7271 I libpersona: KNOX_SDCARD checking this for 10156
09-11 11:56:30.315  7271  7271 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:56:30.315  7271  7271 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.315  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.315  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-11 11:56:30.315  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-11 11:56:30.315  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-11 11:56:30.315  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-11 11:56:30.315  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-11 11:56:30.315  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.325  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-11 11:56:30.325  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-11 11:56:30.325  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-11 11:56:30.325  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-11 11:56:30.325  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-11 11:56:30.325  7178  7178 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-11 11:56:30.325  7178  7178 D SLinkSource: Samsung link source created
09-11 11:56:30.325  7271  7271 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.325  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.325  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-11 11:56:30.325  1014  6147 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7271 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,09-11 11:56:30.335  7271  7271 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.345  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-11 11:56:30.345  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-11 11:56:30.345  1014  2735 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-11 11:56:30.345  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-11 11:56:30.355  1014  1318 I ActivityManager: Killing 6283:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-11 11:56:30.355  1014  1318 I ActivityManager: Killing 5870:com.android.defcontainer/u0a4 (adj 15): empty #31
,09-11 11:56:30.355  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-11 11:56:30.355  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
09-11 11:56:30.355  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-11 11:56:30.355  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
09-11 11:56:30.355  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-11 11:56:30.355  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-11 11:56:30.355  1171  1171 D PanelView: There is/are notification(s) 
,09-11 11:56:30.375  7271  7271 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.375  7271  7271 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.375  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.375  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-11 11:56:30.385  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.385  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-11 11:56:30.385  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-11 11:56:30.385  7255  7255 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-11 11:56:30.385  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-11 11:56:30.385  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-11 11:56:30.385  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-11 11:56:30.395  6594  6594 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-11 11:56:30.395  6594  6594 I PCWCLIENTTRACE_PushUtil: sales region : global
09-11 11:56:30.395  6594  6594 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-11 11:56:30.395  6594  6594 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-11 11:56:30.395  1014  4271 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-11 11:56:30.395  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.395  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.395  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.395  1014  4271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.415  7288  7288 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.415  7288  7288 I libpersona: KNOX_SDCARD checking this for 10032
,09-11 11:56:30.415  7288  7288 E Zygote  : v2
09-11 11:56:30.415  7288  7288 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.415  7288  7288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.415  7288  7288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.415  7288  7288 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.425  1014  4271 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7288 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,09-11 11:56:30.425  1171  1171 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
09-11 11:56:30.425  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
09-11 11:56:30.425  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:56:30.425  1171  1171 D PanelView: There is/are notification(s) 
09-11 11:56:30.425  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-11 11:56:30.435  1014  1558 I ActivityManager: Killing 5599:com.android.vending/u0a28 (adj 15): empty #31
,09-11 11:56:30.445  7271  7271 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-11 11:56:30.445  7271  7271 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-11 11:56:30.445  7255  7255 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-11 11:56:30.455  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,09-11 11:56:30.455  1171  1171 D PanelView: There is/are notification(s) 
09-11 11:56:30.455  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-11 11:56:30.455  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:30.455  7271  7271 I TapandpayWidget:Utils: Clear T&P info.,
,09-11 11:56:30.465  1014  1318 D PersonaManager: isKioskContainerExistOnDevice
09-11 11:56:30.465  1014  1491 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-11 11:56:30.465  1014  1491 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-11 11:56:30.465  7288  7288 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.465  7288  7288 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.465  7178  7287 D ContactProvider: getAllContactInfoList Start
,09-11 11:56:30.475  7271  7271 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-11 11:56:30.485  1014  3131 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-11 11:56:30.485  1014  3131 D SecContentProvider2: mCursor = null
,09-11 11:56:30.485  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,09-11 11:56:30.485  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.485  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.485  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.485  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.485  7148  7148 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-11 11:56:30.505  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-11 11:56:30.505  1014  1054 D PackageManager: userId{-1}
09-11 11:56:30.505  1014  1054 D PackageManager: andCode{true}
,09-11 11:56:30.505  7304  7304 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.505  7304  7304 I libpersona: KNOX_SDCARD checking this for 10160
,09-11 11:56:30.505  7304  7304 E Zygote  : v2
09-11 11:56:30.505  7304  7304 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.505  7304  7304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.515  1014  1491 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7304 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a,
,09-11 11:56:30.515  1171  1171 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-11 11:56:30.515  7304  7304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.515  7304  7304 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.515  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-11 11:56:30.525  1014  1252 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-11 11:56:30.525  7178  7178 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-11 11:56:30.525  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.525  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.525  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.525  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.525  6985  6985 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-11 11:56:30.535  7318  7318 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.535  7318  7318 E Zygote  : v2
09-11 11:56:30.535  7318  7318 I libpersona: KNOX_SDCARD checking this for 10004
09-11 11:56:30.535  7318  7318 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.545  7318  7318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-11 11:56:30.545  7318  7318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:30.545  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7318 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-11 11:56:30.545  7318  7318 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-11 11:56:30.545  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-11 11:56:30.545  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.545  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.545  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.545  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.545  7304  7304 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.555  7304  7304 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.565   312   312 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 21.561ms
,09-11 11:56:30.575  7318  7318 D TimaKeyStoreProvider: TimaSignature is unavailable
09-11 11:56:30.575  7318  7318 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.585  1475  1475 D Launcher.Model: reloadBadges entered.
,09-11 11:56:30.585   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.100ms
,09-11 11:56:30.605   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.658ms
,09-11 11:56:30.615  7336  7336 E Zygote  : MountEmulatedStorage(),
09-11 11:56:30.615  7336  7336 E Zygote  : v2
09-11 11:56:30.615  7336  7336 I libpersona: KNOX_SDCARD checking this for 10100,
09-11 11:56:30.615  7336  7336 I libpersona: KNOX_SDCARD not a persona
09-11 11:56:30.615  1014  1491 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7336 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-11 11:56:30.615  1014  1491 I ActivityManager: Killing 6626:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
09-11 11:56:30.615  1014  1491 I ActivityManager: Killing 6655:com.android.chrome/u0a81 (adj 15): empty #32
,09-11 11:56:30.625  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-11 11:56:30.625  6126  6144 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-11 11:56:30.625  6126  6144 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
09-11 11:56:30.625  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-11 11:56:30.625  6126  6144 E DatabaseUtils: Writing exception to parcel
09-11 11:56:30.625  6126  6144 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
09-11 11:56:30.625  6126  6144 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
09-11 11:56:30.625  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.645  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-11 11:56:30.655  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.655  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.655  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.655  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.655  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-11 11:56:30.655  7304  7304 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-11 11:56:30.655  7336  7336 D ActivityThread: Added TimaKeyStore provider
,09-11 11:56:30.665  7288  7350 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-11 11:56:30.665  1014  1491 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7352 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-11 11:56:30.675  7352  7352 E Zygote  : MountEmulatedStorage()
09-11 11:56:30.675  7352  7352 I libpersona: KNOX_SDCARD checking this for 10046
09-11 11:56:30.675  7352  7352 E Zygote  : v2
09-11 11:56:30.675  7352  7352 I libpersona: KNOX_SDCARD not a persona
,09-11 11:56:30.675  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-11 11:56:30.675  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-11 11:56:30.675  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-11 11:56:30.685  1014  3132 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-11 11:56:30.685  7304  7304 D [0]UMC:UMCContentProvider: @onCreate
,09-11 11:56:30.685  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.685  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.685  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-11 11:56:30.685  1014  3132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-11 11:56:30.695  5387  5387 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,09-11 11:56:30.695  5387  5387 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.,
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	,at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-11 11:56:30.695  5387  5387 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-11 11:56:30.695  5387  5387 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.

```
