#### Test 828946826925cd3_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
,08-31 17:07:52.817  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 17:07:52.817  1017  1030 D BatteryService: level:54, scale:100, status:2, health:2, present:true, voltage: 3868, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 17:07:52.817  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 17:07:52.817  1017  1030 D BatteryService: stay LED for charging
08-31 17:07:52.817  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 17:07:52.827  1017  1017 I MotionRecognitionService: Plugged
08-31 17:07:52.827  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-31 17:07:52.827  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 17:07:52.827  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 17:07:52.827  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 17:07:52.827  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 54
08-31 17:07:52.847  2651  2651 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 17:07:52.847  2651  2754 D HeadsetStateMachine: Disconnected process message: 10
08-31 17:07:52.857  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
08-31 17:07:52.857  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
08-31 17:07:52.857  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
08-31 17:07:53.067   332   332 I ServiceManager: Waiting for service AtCmdFwd...
08-31 17:07:53.087  6672  6672 D AndroidRuntime: 
08-31 17:07:53.087  6672  6672 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 17:07:53.087  6672  6672 D AndroidRuntime: CheckJNI is OFF
08-31 17:07:53.087  6672  6672 D AndroidRuntime: readGMSProperty: start
08-31 17:07:53.087  6672  6672 D AndroidRuntime: readGMSProperty: already setted!!
08-31 17:07:53.087  6672  6672 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 17:07:53.087  6672  6672 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 17:07:53.087  6672  6672 D AndroidRuntime: readGMSProperty: end
08-31 17:07:53.087  6672  6672 D AndroidRuntime: addProductProperty: start
08-31 17:07:53.247  6672  6672 E AffinityControl: AffinityControl: registerfunction enter
08-31 17:07:53.267  6672  6672 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 17:07:53.277  1017  1687 E PersonaManagerService: inState():  stateMachine is null !!
08-31 17:07:53.277  1017  1687 I PersonaManagerService: PersonaId don't exist
08-31 17:07:53.277  1017  1687 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 17:07:53.277  1017  1687 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 17:07:53.287  1017  1687 W ActivityManager: mDVFSHelper.acquire()
08-31 17:07:53.297  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 17:07:53.297  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 17:07:53.307  1017  1687 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:07:53.307  1017  1687 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:07:53.307  1017  1687 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:07:53.307  1017  1687 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:07:53.317  1017  1687 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-31 17:07:53.317  1017  1687 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6683 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 17:07:53.317  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 17:07:53.317  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 17:07:53.317  1017  1687 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 17:07:53.317  1017  1687 D InputDispatcher: Focused application set to: xxxx
08-31 17:07:53.317  6683  6683 I libpersona: KNOX_SDCARD checking this for 10155
08-31 17:07:53.317  1017  1687 D InputDispatcher: Focus left window: 3177
08-31 17:07:53.317  6683  6683 I libpersona: KNOX_SDCARD not a persona
08-31 17:07:53.317  6683  6683 E Zygote  : MountEmulatedStorage()
08-31 17:07:53.317  6683  6683 E Zygote  : v2
08-31 17:07:53.317   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-31 17:07:53.327  6672  6672 D AndroidRuntime: Shutting down VM
08-31 17:07:53.327  6683  6683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:07:53.327  6683  6683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:07:53.327  6683  6683 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 17:07:53.337  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 17:07:53.337  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 17:07:53.347  6683  6683 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 17:07:53.347  6683  6683 D ActivityThread: Added TimaKeyStore provider
08-31 17:07:53.367  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 17:07:53.387  1017  1139 D PersonaManager: isKioskContainerExistOnDevice
08-31 17:07:53.407   258   799 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-31 17:07:53.407   258   433 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-31 17:07:53.407  3177  3177 V ActivityThread: updateVisibility : ActivityRecord{3708c154 token=android.os.BinderProxy@16bf3d3b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-31 17:07:53.487  6683  6683 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-31 17:07:53.507  6683  6683 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7191-7193)
08-31 17:07:53.507  6683  6683 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:07:53.527  6683  6683 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b52fb50}
08-31 17:07:53.527  6683  6683 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:07:53.527  6683  6683 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 17:07:53.527  6672  6672 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 17:07:53.557  6683  6683 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-31 17:07:53.557  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 17:07:53.557  6683  6683 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 17:07:53.577  6683  6683 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-31 17:07:53.577  6683  6683 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-31 17:07:53.577  6683  6683 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-31 17:07:53.587  6683  6683 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 17:07:53.587  6683  6683 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 17:07:53.587  6683  6683 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 17:07:53.587  6683  6683 I Adreno-EGL: Local Branch: 
08-31 17:07:53.587  6683  6683 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 17:07:53.587  6683  6683 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 17:07:53.587  6683  6683 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 17:07:53.707  6683  6709 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-31 17:07:53.757  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:07:53.767  6683  6683 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 17:07:53.777  6683  6683 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 17:07:53.777  6683  6683 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-31 17:07:53.787  6683  6683 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-31 17:07:53.787  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:07:53.787  6683  6683 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:07:53.827  6683  6722 D OpenGLRenderer: Render dirty regions requested: true
08-31 17:07:53.837  1017  2736 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 17:07:53.837  1017  2736 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 17:07:53.837  1017  2736 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 17:07:53.837  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 17:07:53.837  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 17:07:53.847  6683  6683 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 17:07:53.847  6683  6683 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 17:07:53.857   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-31 17:07:53.867  1017  1218 D InputDispatcher: Focus entered window: 6683
08-31 17:07:53.867  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 17:07:53.867  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 17:07:53.867  6683  6683 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 17:07:53.867  6683  6722 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 17:07:53.877  6683  6722 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 17:07:53.877  6683  6722 D OpenGLRenderer: Enabling debug mode 0
08-31 17:07:53.917  6683  6683 V ActivityThread: updateVisibility : ActivityRecord{3d721d7b token=android.os.BinderProxy@30f92d75 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 17:07:53.927  1017  1315 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-31 17:07:53.927  1177  1177 D PanelView: There is/are notification(s) 
08-31 17:07:53.927  1017  6725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 17:07:53.937  1771  1771 I SamsungIME: getCurrentCandidateView
08-31 17:07:53.957  6683  6683 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-31 17:07:53.977  6683  6683 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30f92d75 time:187660
08-31 17:07:53.977  1017  1047 I ActivityManager: Displayed Component not be shown by security: +588ms (total +1m12s546ms)
08-31 17:07:53.977  1017  1047 W ActivityManager: mDVFSHelper.release()
08-31 17:07:53.977  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c7edcc2 u0 com.test.thalitest/.MainActivity t129} time:187664
08-31 17:07:53.987   258   799 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-31 17:07:53.987   258   433 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-31 17:07:54.037  1771  1771 D SamsungIME: Dismiss ExpandCandiate
08-31 17:07:54.037  6683  6683 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6683
08-31 17:07:54.067   332   332 I ServiceManager: Waiting for service AtCmdFwd...
08-31 17:07:54.077   288   288 E SMD     : DCD OFF
08-31 17:07:54.157  6683  6683 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-31 17:07:54.187  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
08-31 17:07:54.227  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
08-31 17:07:54.237  1771  1771 I SamsungIME: KeybaordView init() : load resources
08-31 17:07:54.267  6683  6727 D jxcore_app_log: JniHelper::setJavaVM(0xb79f5328), pthread_self() = -1208645496
08-31 17:07:54.267  1771  1771 I SamsungIME: getCurrentKeyboard
08-31 17:07:54.267  1771  1771 I SamsungIME: getTextKeyboard
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 17:07:54.277  6683  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32c15b6b added. We now have 1 listener(s)
08-31 17:07:54.277  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
08-31 17:07:54.287  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:07:54.287  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:54.287  1771  1771 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-31 17:07:54.287  6683  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 17:07:54.287  6683  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1b5e86 added. We now have 1 listener(s)
,08-31 17:07:54.287  6683  6727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:54.297  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:07:54.297  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 17:07:54.297  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 17:07:54.297  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 17:07:54.297  6683  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 17:07:54.307  6683  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:54.307  6683  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-31 17:07:54.307  6683  6727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:54.307  6683  6727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:54.307  6683  6727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 17:07:54.317  6683  6727 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:54.317  6683  6727 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 17:07:54.317  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:54.317  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:54.347  6683  6683 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 17:07:54.807  1771  6732 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 17:07:54.837  6683  6736 W jxcore-log: Initializing JXcore engine
08-31 17:07:54.837  6683  6736 W jxcore-log: JXcore engine is ready
,08-31 17:07:54.887  1910  1910 E audit   : type=1400 msg=audit(1472656074.887:205): avc:  denied  { ioctl } for  pid=6736 comm="Thread-1154" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 17:07:54.887  1910  1910 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:07:54.887  1910  1910 E audit   : type=1300 msg=audit(1472656074.887:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9e9008f8 items=0 ppid=312 ppcomm=main pid=6736 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1154" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 17:07:54.887  1910  1910 E audit   : type=1320 msg=audit(1472656074.887:205): 
,08-31 17:07:54.897  6683  6736 W jxcore-log: Starting JXcore engine
,08-31 17:07:55.007  6683  6736 W jxcore-log: Platform android,
08-31 17:07:55.007  6683  6736 W jxcore-log: 
08-31 17:07:55.007  6683  6736 W jxcore-log: Process ARCH arm
08-31 17:07:55.007  6683  6736 W jxcore-log: 
,08-31 17:07:55.067   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-31 17:07:55.207  6683  6736 I jxcore-log: JXcore Cordova bridge is ready!
08-31 17:07:55.207  6683  6736 I jxcore-log: 
,08-31 17:07:55.207  6683  6736 W jxcore-log: JXcore engine is started
,08-31 17:07:55.217  6683  6727 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 17:07:55.217  6683  6683 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 17:07:55.857  1017  2758 D SSRM:n  : SIOP:: AP = 310
,08-31 17:07:57.087   288   288 E SMD     : DCD OFF
,08-31 17:08:00.087   288   288 E SMD     : DCD OFF
,08-31 17:08:02.867  1017  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 17:08:02.867  1017  2951 D BatteryService: level:54, scale:100, status:2, health:2, present:true, voltage: 3841, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 17:08:02.867  1017  2951 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 17:08:02.867  1017  2951 D BatteryService: stay LED for charging
08-31 17:08:02.867  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 17:08:02.877  1017  1017 I MotionRecognitionService: Plugged
08-31 17:08:02.877  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 17:08:02.877  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 17:08:02.877  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 17:08:02.877  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 54
08-31 17:08:02.877  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 17:08:02.897  2651  2651 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 17:08:02.897  2651  2754 D HeadsetStateMachine: Disconnected process message: 10
,08-31 17:08:02.897  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:02.897  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
08-31 17:08:02.897  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:03.087   288   288 E SMD     : DCD OFF
,08-31 17:08:03.347  1017  2796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 17:08:03.357  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 17:08:04.717  1017  1343 E Watchdog: !@Sync 6
,08-31 17:08:05.887  1017  2758 D SSRM:n  : SIOP:: AP = 330
,08-31 17:08:06.087   288   288 E SMD     : DCD OFF,
,08-31 17:08:07.257  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 17:08:07.257  6683  6736 I jxcore-log: 
,08-31 17:08:07.257  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 17:08:07.257  6683  6736 I jxcore-log: 
,08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:07.257  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:07.267  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:08:07.267  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 17:08:07.267  6683  6736 I jxcore-log: 
,08-31 17:08:07.267  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 17:08:07.267  6683  6736 I jxcore-log: 
,08-31 17:08:07.907  6683  6736 D executeNativeTests: Running unit tests,
,08-31 17:08:07.987  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:07.987  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b added. We now have 2 listener(s)
,08-31 17:08:07.997  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:08:07.997  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:07.997  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:07.997  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:07.997  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 added. We now have 2 listener(s)
08-31 17:08:07.997  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:08:07.997  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:08:07.997  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:07.997  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:08.007  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:08:08.007  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:08:08.007  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:08.007  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-31 17:08:08.007  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:08:08.007  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 17:08:08.017  6683  6736 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 17:08:08.017  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.017  6683  6736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 17:08:08.017  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 17:08:08.017  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:08:08.017  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:08:08.017  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.027  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.027  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.027  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.027  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:08.027  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b removed from the list
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.027  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 removed from the list
08-31 17:08:08.027  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.027  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.027  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.027  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.027  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.027  6683  6736 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 17:08:08.037  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.037  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.037  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.037  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.037  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.037  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.037  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.037  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.037  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.037  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.037  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.037  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.037  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.037  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.037  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.037  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.037  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.037  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.037  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:08:08.047  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.047  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.047  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.047  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.047  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.047  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:08:08.047  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list,
,08-31 17:08:08.047  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:08:08.047  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.047  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.047  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 17:08:08.047  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.047  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.047  6683  6736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 17:08:08.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:08.057  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:08.057  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.057  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:08.057  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:08.057  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:08:08.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-31 17:08:08.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:08:08.057  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:08.057  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:08.067  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:08:08.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:08:08.077  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:08:08.077  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 17:08:08.077  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage,
08-31 17:08:08.077  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:08:08.077  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 17:08:08.087  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:08:08.097  2651  2742 D BtGatt.GattService: registerClient() - UUID=bde32af8-2b1e-45e3-b9e5-0600c5c95e20
,08-31 17:08:08.137  2651  2741 D BtGatt.GattService: onClientRegistered() - UUID=bde32af8-2b1e-45e3-b9e5-0600c5c95e20, clientIf=6
,08-31 17:08:08.137  6683  6693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 17:08:08.137  2651  5277 D BtGatt.GattService: start scan with filters
,08-31 17:08:08.147  2651  2751 D BtGatt.ScanManager: handling starting scan
,08-31 17:08:08.147  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:08:08.147  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 17:08:08.147  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 17:08:08.147  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:08:08.157  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:08:08.157  2651  2751 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
08-31 17:08:08.157  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 17:08:08.157  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:08.157  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:08:08.157  6683  6736 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:08:08.167  2651  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 17:08:08.167  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.167  2651  2751 D BtGatt.ScanManager: allow scan with filters
,08-31 17:08:08.167  2651  2751 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 17:08:08.167  2651  2751 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 17:08:08.167  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:08:08.167  6683  6736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 17:08:08.167  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:08:08.167  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 17:08:08.167  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:08:08.177  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:08:08.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 17:08:08.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 17:08:08.177  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 17:08:08.177  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 17:08:08.177  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 17:08:08.177  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.177  2651  2751 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 17:08:08.177  2651  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 17:08:08.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 17:08:08.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:08:08.177  2651  5277 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:08:08.187  2651  2742 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 17:08:08.187  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:08:08.187  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 17:08:08.187  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 17:08:08.187  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 17:08:08.187  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:08:08.187  2651  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 17:08:08.187  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.187  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:08:08.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 17:08:08.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 17:08:08.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:08:08.197  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 17:08:08.197  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:08.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.197  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:08.197  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.197  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.197  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.197  6683  6736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 17:08:08.197  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:08:08.197  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:08.197  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:08:08.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:08.207  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:08.207  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:08:08.207  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:08.207  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:08.207  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:08:08.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:08:08.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:08:08.217  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.217  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:08:08.217  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:08:08.227  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:08:08.227  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:08:08.227  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:08:08.227  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:08:08.227  2651  2742 D BtGatt.GattService: registerClient() - UUID=8834701a-f982-487b-a820-be0601cf7cb8
,08-31 17:08:08.237  2651  2751 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 39
,08-31 17:08:08.237  2651  2751 D BtGatt.ScanManager: filter size is 1
,08-31 17:08:08.237  2651  2751 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 17:08:08.247  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 17:08:08.247  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.247  2651  2751 D BtGatt.ScanManager: stopping BLe Batch
,08-31 17:08:08.247  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 17:08:08.247  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.247  2651  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 17:08:08.257  2651  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 17:08:08.257  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.267  2651  2741 D BtGatt.GattService: onClientRegistered() - UUID=8834701a-f982-487b-a820-be0601cf7cb8, clientIf=6
,08-31 17:08:08.267  6683  6693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 17:08:08.267  2651  2663 D BtGatt.GattService: start scan with filters
,08-31 17:08:08.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:08:08.277  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:08:08.277  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:08:08.277  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:08:08.277  2651  2751 D BtGatt.ScanManager: handling starting scan
,08-31 17:08:08.277  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:08.277  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:08.277  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:08:08.277  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:08:08.287  6683  6736 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:08:08.287  2651  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 17:08:08.287  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.287  2651  2751 D BtGatt.ScanManager: allow scan with filters
08-31 17:08:08.287  2651  2751 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 17:08:08.287  2651  2751 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 17:08:08.287  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 17:08:08.287  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.287  2651  2751 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:08:08.287  2651  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 17:08:08.287  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:08:08.287  6683  6736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 17:08:08.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.287  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 17:08:08.287  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.287  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 17:08:08.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 17:08:08.297  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 17:08:08.297  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:08:08.297  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 17:08:08.297  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 17:08:08.297  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:08:08.297  2651  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 17:08:08.297  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.297  2651  5277 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:08:08.297  2651  2742 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:08:08.307  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 17:08:08.307  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:08:08.307  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:08:08.307  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:08:08.307  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:08.307  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:08.307  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.307  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:08.307  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:08.307  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.307  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.307  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:08.307  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.307  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.307  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.317  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.317  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.317  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.317  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.317  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.317  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.317  6683  6736 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 17:08:08.317  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:08.317  2651  2751 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 40
,08-31 17:08:08.327  2651  2751 D BtGatt.ScanManager: filter size is 1
08-31 17:08:08.327  2651  2751 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:08.327  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:08:08.327  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.327  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:08.327  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:08.327  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 17:08:08.327  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:08.327  2651  2751 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:08:08.327  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:08.327  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:08:08.327  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:08:08.327  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.327  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:08:08.337  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:08:08.337  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.337  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:08:08.337  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:08:08.347  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 17:08:08.347  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:08.347  2651  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 17:08:08.347  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 17:08:08.347  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:08:08.347  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 17:08:08.347  2651  2663 D BtGatt.GattService: registerClient() - UUID=4d372b8c-b3ee-4dc8-95cd-3fbd128a4976
08-31 17:08:08.347  2651  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 17:08:08.347  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.397  2651  2741 D BtGatt.GattService: onClientRegistered() - UUID=4d372b8c-b3ee-4dc8-95cd-3fbd128a4976, clientIf=6
,08-31 17:08:08.397  6683  6693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 17:08:08.397  2651  5277 D BtGatt.GattService: start scan with filters
08-31 17:08:08.397  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 17:08:08.397  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:08:08.397  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:08:08.397  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:08:08.397  2651  2751 D BtGatt.ScanManager: handling starting scan
,08-31 17:08:08.397  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:08:08.397  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:08.397  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:08:08.397  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:08:08.397  2651  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 17:08:08.407  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.407  2651  2751 D BtGatt.ScanManager: allow scan with filters
08-31 17:08:08.407  2651  2751 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 17:08:08.407  2651  2751 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 17:08:08.407  6683  6736 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:08:08.407  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:08:08.407  6683  6736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:08:08.407  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:08:08.407  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 17:08:08.407  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:08:08.407  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:08:08.407  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 17:08:08.407  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:08:08.407  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 17:08:08.407  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 17:08:08.407  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.407  2651  2751 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 17:08:08.407  2651  2751 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 17:08:08.417  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:08:08.417  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 17:08:08.417  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:08:08.417  2651  2663 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:08:08.417  2651  5277 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 17:08:08.417  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:08:08.417  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 17:08:08.417  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 17:08:08.417  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 17:08:08.417  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:08:08.417  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:08:08.427  2651  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 17:08:08.427  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 17:08:08.427  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:08.427  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:08:08.427  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 17:08:08.427  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 17:08:08.427  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:08:08.427  6683  6736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:08:08.427  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 17:08:08.427  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:08.427  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.427  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.427  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.427  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:08.427  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.427  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.427  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.427  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.427  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.427  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.437  6683  6736 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 17:08:08.437  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.437  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.437  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.437  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.437  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 17:08:08.437  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.437  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.437  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.437  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.437  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.437  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.437  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.437  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.437  6683  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 17:08:08.437  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.447  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.447  6683  6736 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 17:08:08.447  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.447  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:08:08.447  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:08:08.447  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:08:08.447  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:08:08.447  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.447  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.447  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.447  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.447  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.447  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.457  2651  2751 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 41
08-31 17:08:08.457  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:08:08.457  6683  6736 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 17:08:08.457  2651  2751 D BtGatt.ScanManager: filter size is 1
08-31 17:08:08.457  2651  2751 D BtGatt.ScanManager: delete FilterIndex - 5
08-31 17:08:08.457  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:08:08.457  6683  6736 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-31 17:08:08.457  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:08:08.457  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 17:08:08.457  6683  6736 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:08:08.457  6683  6736 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-31 17:08:08.457  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:08:08.457  6683  6736 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:08:08.457  6683  6736 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 17:08:08.457  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:08:08.457  6683  6736 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 17:08:08.457  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 17:08:08.457  2651  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 17:08:08.457  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:08.457  2651  2751 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:08:08.467  2651  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 17:08:08.467  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-31 17:08:08.467  2651  2751 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
,08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 17:08:08.467  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 17:08:08.467  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 17:08:08.467  6683  6736 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:08:08.467  6683  6736 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 17:08:08.467  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.467  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:08:08.467  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.467  6683  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1218)
08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.467  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.467  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.467  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 17:08:08.467  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.467  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.467  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.467  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.467  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.467  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.467  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.467  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.467  2651  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 17:08:08.467  2651  2741 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.477  6683  6736 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.477  6683  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1218
,08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
,08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 17:08:08.477  6683  6748 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.477  6683  6748 D BluetoothSocket: connect(): myUserId = 0
08-31 17:08:08.477  6683  6748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 17:08:08.477  6683  6736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:08:08.477  6683  6736 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:08:08.477  6683  6736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:08:08.477  6683  6736 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 17:08:08.477  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.477  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.477  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.477  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.477  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.477  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.477  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
08-31 17:08:08.487  2651  2742 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:08.487  6683  6748 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.487  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.487  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.487  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.487  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.487  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.487  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.487  6683  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 17:08:08.487  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:08:08.497  6683  6683 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 17:08:08.497  6683  6683 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 17:08:08.497  6683  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:08.497  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:08.497  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:08.497  6683  6683 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 17:08:08.497  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.497  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.497  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.497  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.497  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.497  6683  6736 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 17:08:08.497  6683  6736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:08:08.497  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:08:08.497  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.497  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.497  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.497  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.497  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.497  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.497  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.507  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.507  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:08.507  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:08.507  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16ce017b not in the list
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:08.507  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:08.507  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a4c4b98 not in the list
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:08:08.507  6683  6736 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:08:08.507  6683  6736 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:08:08.507  6683  6736 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 17:08:08.507  6683  6736 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 17:08:08.507  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:08.507  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32b0e4ba added. We now have 2 listener(s)
08-31 17:08:08.507  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:08.517  6683  6736 D BluetoothAdapter: enable()
08-31 17:08:08.517  6683  6736 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 17:08:08.517  1017  1313 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 17:08:08.517  1017  1313 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 17:08:08.517  1017  1313 D SecContentProvider2: mCursor = null
08-31 17:08:08.517  1017  1313 D WifiService: setWifiEnabled: true pid=6683, uid=10155
08-31 17:08:08.517  1017  1313 W ActivityManager: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:08.517  1017  1313 W WifiService: Failed getting userId using ActivityManagerNative
08-31 17:08:08.517  1017  1313 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:08.517  1017  1313 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 17:08:08.517  1017  1313 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 17:08:08.517  1017  1313 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 17:08:08.517  1017  1313 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 17:08:08.517  1017  1313 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 17:08:08.517  1017  1313 D SettingsProvider: name = wifi_on
08-31 17:08:08.517  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:08.517  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1cde3f6b added. We now have 3 listener(s)
08-31 17:08:08.517  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:08.527  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:08.527  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b5cac8 added. We now have 4 listener(s)
08-31 17:08:08.527  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:08.527  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:08.527  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14e07761 added. We now have 5 listener(s)
08-31 17:08:08.527  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:08.527  1017  2736 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 17:08:08.527  1017  2736 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 17:08:08.527  1017  2736 D SecContentProvider2: mCursor = null
08-31 17:08:08.527  1017  2736 D WifiService: setWifiEnabled: false pid=6683, uid=10155
08-31 17:08:08.527  1017  2736 D SettingsProvider: name = wifi_on
08-31 17:08:08.537  6683  6736 D BluetoothAdapter: disable()
08-31 17:08:08.537  1017  1131 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 17:08:08.537  2091  2091 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 17:08:08.537  2091  2091 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 17:08:08.537  2091  2091 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 17:08:08.537  1017  1139 D SettingsProvider: name = bluetooth_on
08-31 17:08:08.537  2091  2091 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 17:08:08.537  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:08.547  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:08:08.547  2651  2738 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 17:08:08.547  2651  2738 D BluetoothAdapterProperties: Setting state to 13
08-31 17:08:08.547  2651  2738 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 17:08:08.547  2651  2738 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:08.547  2651  2738 D BluetoothAdapterService: updateAdapterState state is 13
08-31 17:08:08.547  1017  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:08.547  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-31 17:08:08.547  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.547  1017  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.547  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:08.547  2651  2651 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 17:08:08.547  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e74aec2, channel: 19, state: LISTENING
08-31 17:08:08.547  1017  3236 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 17:08:08.547  2651  2738 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:08.547  2651  2738 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 17:08:08.547  2651  2738 D BluetoothAdapterService: terminating service from this receiver
08-31 17:08:08.547  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e74aec2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7a9b85e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30f9b4d3mSocket: android.net.LocalSocket@1d9c7810 impl:android.net.LocalSocketImpl@34942f09 fd:FileDescriptor[74]
08-31 17:08:08.547  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d9c7810 impl:android.net.LocalSocketImpl@34942f09 fd:FileDescriptor[74]
,08-31 17:08:08.547  1017  3236 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.547  1017  3236 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.547  1017  3236 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:08.557  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:08.557  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:08:08.557  2651  2738 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 17:08:08.557  2651  2738 D BluetoothAdapterProperties: mDiscovering is false
,08-31 17:08:08.557  1017  1316 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 17:08:08.557  2651  2738 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 17:08:08.557  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.557  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:08.557  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.557  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
08-31 17:08:08.557  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:08.557  1292  1292 D BluetoothPbap: Proxy object disconnected
,08-31 17:08:08.557  1292  1292 D PbapServerProfile: Bluetooth service disconnected
,08-31 17:08:08.557  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.567  1017  1131 E WifiNative-wlan0: do suspend true
,08-31 17:08:08.567  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.567  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 17:08:08.567  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 17:08:08.567  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:08.567  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-31 17:08:08.567  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:08.577  1771  1771 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:08.577  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:08.577  1017  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:08.577  1017  3237 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 17:08:08.577  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 17:08:08.577  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 17:08:08.577  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:08.577  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 17:08:08.587  1017  2736 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:08.587  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:08.587  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:08.587  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:08.587  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-31 17:08:08.587  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:08.587  1017  2736 W ActivityManager: userId = 0, bbcId = -10000,
08-31 17:08:08.587  1017  2736 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:08.587  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:08.597  2651  2741 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 17:08:08.597  2651  2741 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:08:08.597  2651  2738 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 17:08:08.597  2651  2738 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 17:08:08.597  2651  2738 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-31 17:08:08.597  2651  2738 E bt-btif : cmd socket is not created
08-31 17:08:08.597  2651  2738 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 17:08:08.597  2651  5008 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 17:08:08.597  2651  2827 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 17:08:08.597  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 17:08:08.597  2651  2827 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 17:08:08.597  1017  3237 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 17:08:08.597  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:08.607  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:08.607  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:08.607  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:08.607  6683  6748 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@391f6747, channel: -1, state: INIT
08-31 17:08:08.607  6683  6748 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@391f6747, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bc0cb74, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ecc289dmSocket: android.net.LocalSocket@7bb5112 impl:android.net.LocalSocketImpl@236130e3 fd:FileDescriptor[107]
08-31 17:08:08.607  6683  6748 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@7bb5112 impl:android.net.LocalSocketImpl@236130e3 fd:FileDescriptor[107]
,08-31 17:08:08.607  6683  6748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1218)
,08-31 17:08:08.607  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.617  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ea0cb2f, channel: 5, state: LISTENING
08-31 17:08:08.617  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ea0cb2f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a13f55b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1db9053cmSocket: android.net.LocalSocket@fc7b2c5 impl:android.net.LocalSocketImpl@19dd541a fd:FileDescriptor[76]
08-31 17:08:08.617  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fc7b2c5 impl:android.net.LocalSocketImpl@19dd541a fd:FileDescriptor[76]
08-31 17:08:08.617  2651  2651 I BtOppRfcommListener: stopping Accept Thread
08-31 17:08:08.617  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18f8eb4b, channel: 12, state: LISTENING
08-31 17:08:08.617  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18f8eb4b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31eaf0d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@af3928mSocket: android.net.LocalSocket@af5b641 impl:android.net.LocalSocketImpl@3f6c97e6 fd:FileDescriptor[80]
08-31 17:08:08.617  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@af5b641 impl:android.net.LocalSocketImpl@3f6c97e6 fd:FileDescriptor[80]
,08-31 17:08:08.617  2651  5008 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 17:08:08.617  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:08.627  2651  2651 V BluetoothOppManager: cleanUp...
,08-31 17:08:08.627  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:08.627  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:08:08.627  2651  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:08.627  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:08.637  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:08.637  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:08.637  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 17:08:08.647  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
,08-31 17:08:08.647  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:08.647  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:08.647  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 17:08:08.647  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:08.657  6756  6756 E Zygote  : MountEmulatedStorage()
08-31 17:08:08.657  1017  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6756 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-31 17:08:08.657  6756  6756 E Zygote  : v2
08-31 17:08:08.657  6756  6756 I libpersona: KNOX_SDCARD checking this for 10003
08-31 17:08:08.657  6756  6756 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:08.667  6756  6756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:08.667  6756  6756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:08.667  6756  6756 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:08.697  6756  6756 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:08.697  6756  6756 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:08.707  2091  2091 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
,08-31 17:08:08.707  1017  1126 D WifiP2pService: InactiveState{ what=147461 }
08-31 17:08:08.707  1017  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-31 17:08:08.707  1017  1126 D WifiP2pService: DefaultState{ what=147461 }
08-31 17:08:08.707  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-31 17:08:08.707  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 17:08:08.707   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:08:08.717  1933  4416 V NativeCrypto: Read error: ssl=0xb7ef4388: I/O error during system call, Connection timed out
,08-31 17:08:08.717  1017  1133 E ConnectivityService: updateNetworkInfo(),
08-31 17:08:08.717  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:08.717  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 17:08:08.717  1933  4416 V NativeCrypto: SSL shutdown failed: ssl=0xb7ef4388: I/O error during system call, Broken pipe
08-31 17:08:08.717  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-31 17:08:08.727  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:08.727  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 17:08:08.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.727  1933  4416 E GCM     : Wifi connection closed with errorCode 20
,08-31 17:08:08.727  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-31 17:08:08.727  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 17:08:08.727  1017  1030 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-31 17:08:08.727  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:08.727  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:08.727  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation,
,08-31 17:08:08.727  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:08.727  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 17:08:08.727  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-31 17:08:08.727  1017  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 17:08:08.727  1017  2216 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
08-31 17:08:08.727  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 17:08:08.737  1017  2216 I qtaguid : Untagging socket 361
,08-31 17:08:08.737  1017  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 17:08:08.747  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:08.747  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:08.747  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.747  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1,
08-31 17:08:08.747  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:08.747  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.747  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.747  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.747  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-31 17:08:08.747  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 17:08:08.747  1017  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 17:08:08.757  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:08:08.757  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-31 17:08:08.757  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 17:08:08.757  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 17:08:08.757  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 17:08:08.757  6756  6756 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 17:08:08.757  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 17:08:08.757  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:08.757  1017  1047 D WifiDisplayController: disconnect
08-31 17:08:08.757  1017  1047 D WifiDisplayController: updateConnection
08-31 17:08:08.757  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:08.757  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 17:08:08.757  1017  1126 D WifiP2pService: P2pDisablingState,
08-31 17:08:08.757  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-31 17:08:08.767  1017  1131 E WifiNative-wlan0: do suspend true
08-31 17:08:08.767  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 17:08:08.767  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 17:08:08.767  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 17:08:08.767  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 17:08:08.767  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 17:08:08.767  1017  1126 D WifiP2pService: p2p socket connection lost
08-31 17:08:08.767  1017  1126 D WifiP2pService: P2pDisabledState
,08-31 17:08:08.767   278   979 D EnterpriseController: uids 1000
08-31 17:08:08.767   278   979 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 17:08:08.767   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 17:08:08.767  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
08-31 17:08:08.767  1017  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 17:08:08.767  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-31 17:08:08.767  1017  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-31 17:08:08.777  1177  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-31 17:08:08.777  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 17:08:08.777  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 17:08:08.777  1017  2930 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-31 17:08:08.777  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 17:08:08.777  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 17:08:08.777  1017  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:08.777  1017  1133 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:08:08.777  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
08-31 17:08:08.777  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 17:08:08.777  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 17:08:08.777  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:08:08.777   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:08:08.777  3819  6570 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-31 17:08:08.787  1017  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 17:08:08.787  1017  1133 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 17:08:08.787  1017  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 17:08:08.787  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:08.787  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:08.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:08.787  2091  2091 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 17:08:08.787  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:08.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:08.797  1017  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 17:08:08.797  6756  6756 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 17:08:08.797  6756  6756 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 17:08:08.797  6756  6756 D UserAnalysis: Create SecureDbHelper
,08-31 17:08:08.797  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:08.797  1017  1131 D SecContentProvider2: mCursor = null
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:08.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:08.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:08.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-31 17:08:08.797  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:08.807  2651  2827 W bt-btif : ag scb idx 1 not allocated
08-31 17:08:08.807  2651  2827 W bt-btif : ag scb idx 2 not allocated
,08-31 17:08:08.807  2651  2827 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 17:08:08.807  2651  2873 I bt_userial_mct: exiting userial_read_thread
08-31 17:08:08.807  2651  2873 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 17:08:08.807  2651  2741 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 17:08:08.807  2651  2830 I bt_vendor: hw_epilog_process
08-31 17:08:08.807  2651  2741 D bt_userial_mct: userial_close
08-31 17:08:08.807  2651  2741 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0,
08-31 17:08:08.807  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-31 17:08:08.807  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:08.807  1017  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 17:08:08.807  1177  1177 D HotspotTile: onReceive : 0, 0
08-31 17:08:08.807  1017  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 17:08:08.807  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:08:08.807  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:08.807  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:08.807  6756  6756 D IntelligenceServiceApplication: onCreate()
,08-31 17:08:08.807  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 17:08:08.807  1017  1134 D Tethering: MasterInitialState.processMessage what=3
,08-31 17:08:08.807  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 17:08:08.807  1017  1124 V NetworkStats: updateIfacesLocked()
08-31 17:08:08.807  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 17:08:08.807  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 17:08:08.807  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:08.807  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-31 17:08:08.817  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:08:08.817  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.817  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.817  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 17:08:08.817  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:08.817  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-31 17:08:08.817  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 17:08:08.817  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 17:08:08.817  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 17:08:08.817  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 17:08:08.817  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 17:08:08.817  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.817  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.817  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.817  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:08.817  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:08.817  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:08.817  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:08.817  6756  6756 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 17:08:08.827  1017  1124 V NetworkStats: performPollLocked() took 13ms
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:08.827  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-31 17:08:08.827  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:08.827  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:08.827  6756  6756 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 17:08:08.827  1017  2952 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 17:08:08.827  1017  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:08.827  1017  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:08.827  1017  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:08.827  1017  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:08.837  6756  6756 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 17:08:08.847  6782  6782 E Zygote  : MountEmulatedStorage()
08-31 17:08:08.847  6782  6782 I libpersona: KNOX_SDCARD checking this for 10107
08-31 17:08:08.847  6782  6782 E Zygote  : v2
08-31 17:08:08.847  6782  6782 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:08.847  6782  6782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:08.847  6782  6782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:08.847  6782  6782 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 17:08:08.847  1017  2952 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6782 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 17:08:08.857  1017  1029 I ActivityManager: Killing 6395:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31,
,08-31 17:08:08.867  2091  2091 I wpa_supplicant: Blacklist: Clear (all) 
08-31 17:08:08.867  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.867  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:08.867  6782  6782 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:08.867  6782  6782 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:08.907  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.907  2091  2091 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 17:08:08.907  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:08.907  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:08.917  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:08.917  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 17:08:08.917  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-31 17:08:08.917  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.927  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.927  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 17:08:08.927  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.927  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.927  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.927  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.927  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.927  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 17:08:08.937  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.937  2091  2091 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 17:08:08.937  2091  2091 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 17:08:08.937  2091  2091 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 17:08:08.937  2091  2091 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 17:08:08.937  2091  2091 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 17:08:08.937  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.937  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:08.937  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.937  1017  1134 D Tethering: InitialState.processMessage what=4
,08-31 17:08:08.937  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.937  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:08.937  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.937  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.937  1017  1134 E Tethering: No numeric data
,08-31 17:08:08.937  1017  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:08:08.937  1017  1134 D Tethering: clearTetheredNotification()
08-31 17:08:08.937  1017  1131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-31 17:08:08.937  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.947  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.947  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:08.947  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.947  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-31 17:08:08.947  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.947  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 17:08:08.947  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:08.947  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.947  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 17:08:08.947  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 17:08:08.947  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:08.947  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.947  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.947  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:08.947  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 17:08:08.947  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.947  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.947  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.947  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:08.947  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:08.957  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.957  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.957  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 17:08:08.957  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.957  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.957  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-31 17:08:08.957  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 17:08:08.957  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:08.957  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:08.957  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 17:08:08.957  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 17:08:08.967  2651  2741 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 17:08:08.967  2651  2741 I bt_vendor: bluetooth satus is on
08-31 17:08:08.967  2651  2741 I bt_vendor: bt-vendor : resetting BT status
08-31 17:08:08.967  2651  2741 I bt_vendor: Starting hciattach daemon
08-31 17:08:08.967  2651  2741 I bt_vendor: try to set false
,08-31 17:08:08.967  2651  2741 I bt_vendor: Starting hciattach daemon
,08-31 17:08:08.967  2651  2741 I bt_vendor: try to set false
,08-31 17:08:08.967  2651  2741 I bt_vendor: cleanup
08-31 17:08:08.967  2651  2827 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-31 17:08:08.967  2651  2741 I GKI_LINUX: GKI_exit_task 0 done
08-31 17:08:08.967  2651  2741 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 17:08:08.967  2651  2738 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 17:08:08.967  2651  2738 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 17:08:08.967  2651  2738 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-31 17:08:08.967  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-31 17:08:08.967  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 17:08:08.967  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
,08-31 17:08:08.977  1017  2736 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:08.977  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 17:08:08.977  1017  2736 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.977  1017  2736 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.977  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:08.977  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 17:08:08.977  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 17:08:08.977  2651  2651 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:08:08.977  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 17:08:08.977  1017  3237 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:08.977  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 17:08:08.977  2651  2651 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 17:08:08.977  2651  2651 D BtGatt.GattService: stop()
08-31 17:08:08.977  2651  2651 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 17:08:08.977  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.977  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.977  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:08.987  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
08-31 17:08:08.987  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 17:08:08.987  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 17:08:08.987  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 17:08:08.987  2651  2651 D HeadsetService: Received stop request...Stopping profile...
08-31 17:08:08.987  1017  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:08.987  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:08.987  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:08.987  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.987  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:08.987  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 17:08:08.987  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 17:08:08.987  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService,
,08-31 17:08:08.987   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84887c8
,08-31 17:08:08.987  1017  2951 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 17:08:08.987   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 17:08:08.987  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 17:08:08.987   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 17:08:08.997  1017  3237 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:08.987   273   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203206856)
08-31 17:08:08.997  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 17:08:08.987  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.987  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.987  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:08.997  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 17:08:08.997  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:08.997  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 17:08:08.997  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
08-31 17:08:08.997  6683  6683 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 17:08:08.997  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:08.997  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:08.997  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:08.997  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 17:08:08.997  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 17:08:08.997  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 17:08:08.997  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 17:08:08.997  1017  2952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:08.997  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
08-31 17:08:09.007  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.007  1017  2951 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:09.007  1017  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.007  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 17:08:09.007  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:09.007  1017  1315 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:09.007  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:09.007  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 17:08:09.007  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.007  2651  2738 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.007  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.007  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.007  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:09.007  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 17:08:09.007  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:09.007  2651  2738 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 17:08:09.017  1292  1292 D HeadsetProfile: Bluetooth service disconnected
08-31 17:08:09.017  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.017  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.017  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:09.017  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:09.017  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 17:08:09.017  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 17:08:09.017  2651  2738 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 17:08:09.017  2651  2738 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 17:08:09.017  2651  2738 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 17:08:09.017  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-31 17:08:09.017  2651  2651 D A2dpService: Received stop request...Stopping profile...
08-31 17:08:09.017  2651  2759 D A2dpStateMachine: Exit Disconnected: -1
,08-31 17:08:09.027  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
,08-31 17:08:09.027  2903  2903 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:09.027  1292  1292 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:09.027  1292  1292 D A2dpProfile: Bluetooth service disconnected
08-31 17:08:09.027  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:09.027  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 17:08:09.027  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 17:08:09.027  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:09.027  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 17:08:09.027  2651  2651 D HidService: Received stop request...Stopping profile...
08-31 17:08:09.027  2651  2651 D HidService: Stopping Bluetooth HidService
08-31 17:08:09.027  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:08:09.027  2651  2651 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 17:08:09.027  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 17:08:09.027  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
,08-31 17:08:09.037  2651  2651 D HealthService: Received stop request...Stopping profile...
08-31 17:08:09.037  1292  1292 D BluetoothInputDevice: Proxy object disconnected
08-31 17:08:09.037  1292  1292 D HidProfile: Bluetooth service disconnected
08-31 17:08:09.037  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
,08-31 17:08:09.047  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 17:08:09.047  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:08:09.047  2651  2651 D PanService: Received stop request...Stopping profile...
08-31 17:08:09.047  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
,08-31 17:08:09.047  2651  2651 D BluetoothMapService: Received stop request...Stopping profile...
08-31 17:08:09.047  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 17:08:09.047  1292  1292 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 17:08:09.047  1292  1292 D PanProfile: Bluetooth service disconnected
,08-31 17:08:09.047  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
,08-31 17:08:09.047  1292  1292 D BluetoothMap: Proxy object disconnected
08-31 17:08:09.047  1292  1292 D MapProfile: Bluetooth service disconnected
,08-31 17:08:09.047  2651  2651 D SapService: Received stop request...Stopping profile...
,08-31 17:08:09.067   273   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-31 17:08:09.067   273   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 17:08:09.067   273   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203206856) wakelock released: 1, error no: 0
08-31 17:08:09.067   273   318 I rmt_storage: 
,08-31 17:08:09.067   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84887c8,
08-31 17:08:09.067  2651  2651 D SapService: Stopping Bluetooth SapService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b52fb50
08-31 17:08:09.067  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-31 17:08:09.067  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 17:08:09.067  2651  2651 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 17:08:09.067  2651  2760 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 17:08:09.067  2651  2651 I GKI_LINUX: GKI_exit_task 2 done
08-31 17:08:09.067  2651  2651 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 17:08:09.067  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 17:08:09.067  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 17:08:09.067  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 17:08:09.067  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:08:09.067  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 17:08:09.067  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:09.067  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:08:09.067  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 17:08:09.067  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 17:08:09.067  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:09.067  2651  2651 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 17:08:09.077  2651  2651 E BluetoothAdapterService(458423120): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-31 17:08:09.077  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 17:08:09.077  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 17:08:09.077  2091  2091 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 17:08:09.077  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 17:08:09.077  1292  1292 D SapProfile: Bluetooth service disconnected
,08-31 17:08:09.077  2651  2738 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 17:08:09.077  2651  2738 D BluetoothAdapterProperties: Setting state to 10
08-31 17:08:09.077  2651  2738 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 17:08:09.077  2651  2738 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:09.077  2651  2738 D BluetoothAdapterService: updateAdapterState state is 10
08-31 17:08:09.077  1292  1301 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.077  1292  1301 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.077  2651  2738 D BluetoothAdapterService: Autoconnection is available 
08-31 17:08:09.077  2651  2738 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 17:08:09.077  2651  2738 I BluetoothAdapterState: Entering OffState
,08-31 17:08:09.077  6683  6691 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.077  6683  6691 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 17:08:09.077  6683  6691 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 17:08:09.077  6683  6691 D BluetoothLeAdvertiser: Exit stop advertising
08-31 17:08:09.077  6683  6691 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 17:08:09.077  6683  6691 D BluetoothLeScanner: Exiting stopAllScan
08-31 17:08:09.077  1456  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.077  1456  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.087  2651  2742 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:09.087  2903  2924 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.087  2903  2924 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.087  1292  5278 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 17:08:09.087   288   288 E SMD     : DCD OFF
,08-31 17:08:09.087  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:08:09.087  2651  5277 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.087  2651  5277 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.087  1292  1301 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 17:08:09.087  1292  1301 D Bluetoothsap: Unbinding service...
08-31 17:08:09.087  1445  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.087  1445  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.097  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:09.097  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:09.097  2091  2091 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 17:08:09.097  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:09.097  2903  2915 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:08:09.097  1933  2120 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.097  1933  2120 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:09.097  1292  1300 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 17:08:09.107  1292  1301 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 17:08:09.107  1177  3790 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.107  1177  3790 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 17:08:09.107  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.107  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 17:08:09.107  1434  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:09.107  1434  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 17:08:09.107  1292  1300 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:09.107  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 17:08:09.117  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 17:08:09.117  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:09.117  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-31 17:08:09.117  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 17:08:09.127  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF,
08-31 17:08:09.127  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 17:08:09.127  1177  1699 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:09.127  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:09.127  1177  1177 D BluetoothTile:  getBluetoothState : 10,
08-31 17:08:09.127  1177  1699 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:09.127  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:09.127  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:09.127  1771  1771 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-31 17:08:09.127  1017  1218 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:09.137  1933  2125 D BluetoothAdapter: 920390409: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:09.137  1017  3236 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 17:08:09.137  1933  2125 D BluetoothAdapter: 920390409: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:09.137  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 17:08:09.137  1017  1316 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:09.137  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:09.137  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:09.137  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:09.137  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:09.137  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.137  1017  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.137  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:09.147  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:09.147  1017  1492 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-31 17:08:09.147  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-31 17:08:09.147  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.147  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.147  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 17:08:09.147  2651  2741 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 17:08:09.147  2651  2651 I GKI_LINUX: GKI_exit_task 1 done
08-31 17:08:09.147  2651  2651 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-31 17:08:09.147  2651  2651 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 17:08:09.147  2651  2651 I art     : System.exit called, status: 0
08-31 17:08:09.147  2651  2651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 17:08:09.157  1933  1933 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 17:08:09.167  1933  1933 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=251 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332),
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	,at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  1017  3237 I ActivityManager: Killing 5046:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08,:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.k.c(PG:583)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  6782  6782 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMo,de$StrictModeDiskReadViolation: policy=31 violation=2
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:09.187  6782  6782 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:09.187  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 17:08:09.197  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 17:08:09.197  1017  1315 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:09.197  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:09.197  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.197  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.197  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:09.207  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 17:08:09.207  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 17:08:09.207  3674  3674 I Hs20UtilService: Starting #8
08-31 17:08:09.207  3674  3690 I Hs20UtilService: Message received 5007
08-31 17:08:09.207  1017  1131 E WifiConfigStore: setLastSelectedConfiguration -1
08-31 17:08:09.207  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:09.207  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 17:08:09.207  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 17:08:09.207  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:09.207  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 17:08:09.207  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:09.207  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 17:08:09.217  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:09.217  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:09.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:09.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:09.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:09.217  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:09.217  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:09.217  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 17:08:09.217  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:09.217  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 17:08:09.217  1933  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:08:09.217  1177  1177 D HotspotTile: onReceive : 1, 0
08-31 17:08:09.217  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:09.217  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:09.227  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:09.227  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 17:08:09.227  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 17:08:09.227  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 17:08:09.227  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:09.227  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 17:08:09.227  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:09.227  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 17:08:09.227  1017  3236 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-31 17:08:09.237  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.237  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.237  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.237  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.237  6782  6817 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 17:08:09.267  6826  6826 E Zygote  : MountEmulatedStorage()
08-31 17:08:09.267  6826  6826 I libpersona: KNOX_SDCARD checking this for 10068
08-31 17:08:09.267  6826  6826 E Zygote  : v2
08-31 17:08:09.267  6826  6826 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:09.267  6826  6826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:09.267  1017  3236 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6826 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:08:09.267  6826  6826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:09.267  1017  1492 I ActivityManager: Process com.android.bluetooth (pid 2651)(adj 0) has died(42,1092)
08-31 17:08:09.267  6826  6826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 17:08:09.267  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 17:08:09.267  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.267  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.267  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 17:08:09.287  6826  6826 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:09.287  6826  6826 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:09.297  6826  6826 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 17:08:09.307  1933  2121 I art     : Explicit concurrent mark sweep GC freed 51733(2MB) AllocSpace objects, 56(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.500ms total 95.133ms
,08-31 17:08:09.307  1017  1313 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 17:08:09.307  1017  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:09.307  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.307  1017  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.307  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:09.317  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:09.317  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-31 17:08:09.317  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:09.327  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 17:08:09.337  3177  3177 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-31 17:08:09.337  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:09.337  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:09.347  3177  3177 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-31 17:08:09.357  6826  6826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 17:08:09.357  1017  1313 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 17:08:09.357  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.357  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.357  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.357  1017  1313 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.377  6842  6842 E Zygote  : MountEmulatedStorage()
,08-31 17:08:09.377  6842  6842 E Zygote  : v2
08-31 17:08:09.377  6842  6842 I libpersona: KNOX_SDCARD checking this for 10069
08-31 17:08:09.377  6842  6842 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:09.377  6842  6842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:09.377  6842  6842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:09.377  6842  6842 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:09.377  1017  1313 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6842 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:08:09.377  1017  1313 I ActivityManager: Killing 6363:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-31 17:08:09.397  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:09.407  6842  6842 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:09.417  6842  6842 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:09.427  1017  1313 I ActivityManager: Killing 5846:com.android.mms/u0a46 (adj 15): empty #31
,08-31 17:08:09.427  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.427  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.427  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-31 17:08:09.427  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 17:08:09.437  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.437  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.437  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.437  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.467  6858  6858 E Zygote  : MountEmulatedStorage(),
,08-31 17:08:09.467  6858  6858 E Zygote  : v2,
08-31 17:08:09.467  6858  6858 I libpersona: KNOX_SDCARD checking this for 10104
08-31 17:08:09.467  6858  6858 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:09.467  6858  6858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-31 17:08:09.467  1017  1029 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6858 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 17:08:09.477  6858  6858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 17:08:09.477  6858  6858 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 17:08:09.497  6858  6858 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:09.497  6858  6858 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:09.507  1017  1218 D CountryDetector: No listener is left
,08-31 17:08:09.507  6858  6858 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 17:08:09.667  6858  6882 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 17:08:09.667  6858  6882 I Babel   : MmsConfig.loadMmsSettings
08-31 17:08:09.667  6858  6882 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-31 17:08:09.667  6858  6882 I Babel   : MmsConfig.loadFromDatabase
,08-31 17:08:09.687  6858  6882 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-31 17:08:09.687  6858  6882 I Babel   : MmsConfig.loadFromResources
,08-31 17:08:09.687  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-31 17:08:09.687  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 17:08:09.687  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.687  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.687  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 17:08:09.697  6858  6858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:08:09.697  6858  6882 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 17:08:09.697  6858  6882 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-31 17:08:09.737  6858  6858 I Babel_StickerModule: App launched.
,08-31 17:08:09.737  1017  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:09.747  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:09.747  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.747  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.747  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:09.747  3674  3674 I Hs20UtilService: Starting #9
,08-31 17:08:09.747  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:09.747  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:09.747  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 17:08:09.747  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:09.747  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:09.747  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 17:08:09.747  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:09.747  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:09.757   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-31 17:08:09.757   283   283 W QCamera2Factory: getCameraInfo: X
,08-31 17:08:09.757   283  1014 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,08-31 17:08:09.757   283  1014 W QCamera2Factory: getCameraInfo: X
,08-31 17:08:09.767  1017  3237 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:09.767  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:09.767  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.767  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.767  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:09.767  3674  3674 I Hs20UtilService: Starting #10
,08-31 17:08:09.767  1017  3236 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-31 17:08:09.767  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:09.767  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.767  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.767  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.767  1017  3236 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.787  6884  6884 E Zygote  : MountEmulatedStorage(),
08-31 17:08:09.787  6884  6884 E Zygote  : v2
08-31 17:08:09.787  6884  6884 I libpersona: KNOX_SDCARD checking this for 1000
08-31 17:08:09.787  6884  6884 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:09.787  6884  6884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:09.787  6884  6884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:09.787  1017  3236 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-31 17:08:09.787  6884  6884 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:09.807  6884  6884 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:09.807  6884  6884 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:09.807   312   312 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 23.759ms
,08-31 17:08:09.817  1017  1044 D Tethering: interfaceRemoved wlan0
,08-31 17:08:09.817  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 17:08:09.827   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 18.239ms,
,08-31 17:08:09.847   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 17.068ms
,08-31 17:08:09.857  6858  6858 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 17:08:09.857  6858  6858 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 17:08:09.857  6858  6858 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 17:08:09.867  6858  6858 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 17:08:09.867  6858  6858 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 17:08:09.867  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:09.867  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:09.867  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 17:08:09.867  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:09.877  6858  6858 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 17:08:09.877  1017  1139 I ActivityManager: Killing 6023:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-31 17:08:09.877  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.877  1017  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.877  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.877  6858  6858 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 17:08:09.887  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.887  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.887  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.887  6858  6858 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 17:08:09.887  6858  6858 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 17:08:09.887  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.887  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:09.887  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.897  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.897  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:09.897  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.897  6858  6858 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 17:08:09.897  6858  6858 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 17:08:09.897  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.897  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:09.897  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.907  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.907  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.907  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.907  6858  6858 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 17:08:09.907  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.907  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.907  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.907  6858  6858 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 17:08:09.907  6858  6858 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 17:08:09.917  6858  6858 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 17:08:09.917  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.917  6858  6858 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 17:08:09.917  6858  6858 W VideoCapabilities: Unsupported mime video/mp43
,08-31 17:08:09.917  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.917  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.917  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.927  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.927  6858  6858 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 17:08:09.927  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.927  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.927  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.937  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.937  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.937  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.937  6858  6858 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 17:08:09.937  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.937  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.937  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 17:08:09.947  1017  1044 D Tethering: interfaceRemoved p2p0
08-31 17:08:09.947  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 17:08:09.947  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:08:09.947  1017  1316 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 17:08:09.957  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:09.957  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:09.957  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:09.957  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:09.957  6858  6858 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 17:08:09.957  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:09.957  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:09.967  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:09.967  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 17:08:09.967  1017  1218 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 17:08:09.977  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.977  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.977  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:09.977  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:09.987  6901  6901 E Zygote  : MountEmulatedStorage()
08-31 17:08:09.987  6901  6901 I libpersona: KNOX_SDCARD checking this for 1002
08-31 17:08:09.987  6901  6901 E Zygote  : v2
08-31 17:08:09.987  6901  6901 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:09.987  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:09.987  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:09.987  1017  1218 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6901 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-31 17:08:09.987  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 17:08:09.997  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
08-31 17:08:09.997  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-31 17:08:09.997  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:09.997  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:09.997  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 17:08:09.997  1017  1315 I ActivityManager: Killing 5881:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-31 17:08:10.017  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.017  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.027  6901  6901 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 17:08:10.027  6901  6901 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 17:08:10.057  6901  6901 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 17:08:10.097  6901  6901 D BtSettings.ProfileConfig: Adding GattService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding HidService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding HealthService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding PanService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding SapService
08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 17:08:10.107  6901  6901 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 17:08:10.107  6901  6901 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 17:08:10.117  1017  1139 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 17:08:10.117  1017  1139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.117  1017  1139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  1139 D SettingsProvider: selectionArgs: false
08-31 17:08:10.117  1017  1139 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.117  1017  1139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.117  1017  1139 D SettingsProvider: ret = -1
08-31 17:08:10.117  1017  2952 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 17:08:10.117  1017  2952 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:10.117  1017  2952 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  2952 D SettingsProvider: selectionArgs: false
08-31 17:08:10.117  1017  2952 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.117  1017  2952 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.117  1017  2952 D SettingsProvider: ret = -1
,08-31 17:08:10.117  1017  2951 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-31 17:08:10.117  1017  2951 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:10.117  1017  2951 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  2951 D SettingsProvider: selectionArgs: false
,08-31 17:08:10.117  1017  2951 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.117  1017  2951 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:10.117  1017  2951 D SettingsProvider: ret = -1
,08-31 17:08:10.117  1017  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
08-31 17:08:10.117  1017  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.117  1017  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  1218 D SettingsProvider: selectionArgs: false
08-31 17:08:10.117  1017  1218 D SettingsProvider: selectionArgs: 1002
,08-31 17:08:10.117  1017  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.117  1017  1218 D SettingsProvider: ret = -1
08-31 17:08:10.117  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 17:08:10.117  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:10.117  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  1029 D SettingsProvider: selectionArgs: false
08-31 17:08:10.117  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.117  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.117  1017  1029 D SettingsProvider: ret = -1
,08-31 17:08:10.117  1017  1316 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 17:08:10.117  1017  1316 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.117  1017  1316 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.117  1017  1316 D SettingsProvider: selectionArgs: false
08-31 17:08:10.117  1017  1316 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.117  1017  1316 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.117  1017  1316 D SettingsProvider: ret = -1,
08-31 17:08:10.117  1017  1315 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 17:08:10.127  1017  1315 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.127  1017  1315 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.127  1017  1315 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  1315 D SettingsProvider: selectionArgs: 1002
,08-31 17:08:10.127  1017  1315 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.127  1017  1315 D SettingsProvider: ret = -1
,08-31 17:08:10.127  1017  2930 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 17:08:10.127  1017  2930 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.127  1017  2930 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.127  1017  2930 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  2930 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.127  1017  2930 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.127  1017  2930 D SettingsProvider: ret = -1
08-31 17:08:10.127  1017  3237 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:10.127  1017  3237 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.127  1017  3237 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.127  1017  3237 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  3237 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.127  1017  3237 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.127  1017  3237 D SettingsProvider: ret = -1
08-31 17:08:10.127  1017  3236 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:10.127  1017  3236 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.127  1017  3236 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.127  1017  3236 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  3236 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.127  1017  3236 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:10.127  1017  3236 D SettingsProvider: ret = -1
,08-31 17:08:10.127  1017  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-31 17:08:10.127  1017  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:10.127  1017  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 17:08:10.127  1017  1492 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  1492 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.127  1017  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:10.127  1017  1492 D SettingsProvider: ret = -1
08-31 17:08:10.127  1017  1687 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 17:08:10.127  1017  1687 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:10.127  1017  1687 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:10.127  1017  1687 D SettingsProvider: selectionArgs: false
08-31 17:08:10.127  1017  1687 D SettingsProvider: selectionArgs: 1002
08-31 17:08:10.127  1017  1687 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:10.127  1017  1687 D SettingsProvider: ret = -1
,08-31 17:08:10.137  1017  1030 I ActivityManager: Killing 6418:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-31 17:08:10.147  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:10.147  1017  1313 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:10.147  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.147  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.147  1017  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:10.147  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:10.147  1933  6918 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-31 17:08:10.157  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:10.157  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:10.157  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.157  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:10.157  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:10.167  1017  2951 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:10.167  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:10.167  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.167  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:10.167  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:10.167  3674  3674 I Hs20UtilService: Starting #11
,08-31 17:08:10.167  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:10.177  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 17:08:10.177  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:10.177  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:10.177  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:10.177  1017  3238 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:10.177  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.177  1017  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:10.177  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:10.197  5864  5864 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 17:08:10.197  5864  5864 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 17:08:10.197  5864  5864 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 17:08:10.197  5864  5864 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:10.197  1017  2930 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-31 17:08:10.197  1017  2930 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 17:08:10.197  1017  2930 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast,
08-31 17:08:10.197  1933  6918 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
08-31 17:08:10.197  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 17:08:10.197  5864  6919 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-31 17:08:10.197  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.197  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.197  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.217  6921  6921 E Zygote  : MountEmulatedStorage(),
08-31 17:08:10.217  6921  6921 I libpersona: KNOX_SDCARD checking this for 10111
08-31 17:08:10.217  6921  6921 E Zygote  : v2
08-31 17:08:10.217  6921  6921 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:10.217  6921  6921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:10.217  1017  2930 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6921 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:08:10.217  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 17:08:10.217  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.217  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.217  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.217  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.217  6921  6921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-31 17:08:10.227  6921  6921 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 17:08:10.237  6928  6928 E Zygote  : MountEmulatedStorage()
08-31 17:08:10.237  6928  6928 I libpersona: KNOX_SDCARD checking this for 10009
,08-31 17:08:10.237  6928  6928 E Zygote  : v2
08-31 17:08:10.237  6928  6928 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:10.237  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:10.237  1017  1042 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6928 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:08:10.237  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-31 17:08:10.237  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 17:08:10.237  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-31 17:08:10.237  1726  1726 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-31 17:08:10.237  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.237  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.237  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.237  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.257  6947  6947 E Zygote  : MountEmulatedStorage()
08-31 17:08:10.257  6947  6947 E Zygote  : v2
08-31 17:08:10.257  6947  6947 I libpersona: KNOX_SDCARD checking this for 10145,
08-31 17:08:10.257  6947  6947 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:10.257  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:10.257  1017  1042 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6947 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 17:08:10.257  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:10.267  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 17:08:10.267  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.267  6928  6928 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.267  1726  1726 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-31 17:08:10.267  1726  1726 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-31 17:08:10.267  1726  1726 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-31 17:08:10.267  1726  1726 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 17:08:10.277  6921  6921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.277  6921  6921 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.277  1319  1332 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-31 17:08:10.277  1726  1726 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 17:08:10.277  1726  1726 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-31 17:08:10.287  1017  2951 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 17:08:10.287  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.287  6947  6947 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.287  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.287  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.287  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.287  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.307  6966  6966 E Zygote  : MountEmulatedStorage(),
08-31 17:08:10.307  6966  6966 I libpersona: KNOX_SDCARD checking this for 10081
08-31 17:08:10.307  6966  6966 E Zygote  : v2
,08-31 17:08:10.307  6966  6966 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:10.317  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:10.317  1017  2951 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6966 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:08:10.317  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:10.317  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 17:08:10.327  1726  1726 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-31 17:08:10.337  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.347  6966  6966 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.347  6947  6947 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-31 17:08:10.347  6947  6947 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:08:10.347  6947  6947 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 17:08:10.347  6947  6947 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 17:08:10.347  6947  6947 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 17:08:10.357  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 17:08:10 GMT+02:00 2016
,08-31 17:08:10.357  1017  2736 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 17:08:10.357  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.357  1017  2736 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.357  1017  2736 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:10.357  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 17:08:10.367  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 17:08:10.367  1017  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 17:08:10.367  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.367  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.367  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.367  1017  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.377  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 17:08:10.377  3692  3692 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 17:08:10.377  3692  3692 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 17:08:10.377  3692  6981 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 17:08:10.387  3692  6981 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 17:08:10.387  6983  6983 E Zygote  : MountEmulatedStorage()
08-31 17:08:10.387  6983  6983 I libpersona: KNOX_SDCARD checking this for 10034
08-31 17:08:10.387  6983  6983 E Zygote  : v2
08-31 17:08:10.387  6983  6983 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:10.387  6983  6983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-31 17:08:10.387  3692  6981 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 17:08:10.387  3692  6981 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
08-31 17:08:10.387  6983  6983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:10.397  6983  6983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:10.397  1017  1492 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6983 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-31 17:08:10.397  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 17:08:10.417  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.417  1017  1218 D RCPManagerService: exchangeData() failure , invalid userId
08-31 17:08:10.417  6983  6983 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.427  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.427  6921  6921 I MusicStore: Database version: 108
,08-31 17:08:10.447  6983  6983 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 17:08:10.447  1017  1218 I ActivityManager: Killing 6436:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-31 17:08:10.457  1017  3237 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:10.457  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 17:08:10.457  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.457  1017  3237 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:10.457  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:10.467  3255  7006 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-31 17:08:10.477  3255  7006 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 17:08:10.477  3255  7006 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 17:08:10.477  3255  7006 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 17:08:10.477  3255  7006 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 17:08:10.477  4137  4137 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 17:08:10.487  1017  1029 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-31 17:08:10.487  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.487  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:10.487  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 17:08:10.487  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 17:08:10.487  6097  6097 I SA      : [DM] init START
,08-31 17:08:10.487  1017  2930 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.497  6097  6097 I SA      : [DM] This device is not a Vodafone
,08-31 17:08:10.497  6097  6097 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-31 17:08:10.497  6097  6097 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 17:08:10.507  1017  3237 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 17:08:10.507  1017  3237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.507  1017  3237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.507  1017  3237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.507  1017  3237 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.507  6097  6097 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 17:08:10.507  1017  1687 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.507  6097  6097 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-31 17:08:10.507  6097  6097 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-31 17:08:10.507  6097  6097 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-31 17:08:10.507  6097  6097 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-31 17:08:10.507  6097  6097 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-31 17:08:10.517  4137  7010 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 17:08:10.517  1017  3237 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7011 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 17:08:10.517  7011  7011 E Zygote  : MountEmulatedStorage()
08-31 17:08:10.517  7011  7011 I libpersona: KNOX_SDCARD checking this for 10120
08-31 17:08:10.517  7011  7011 E Zygote  : v2
08-31 17:08:10.517  7011  7011 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 17:08:10.517  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-31 17:08:10.517  6097  6097 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 17:08:10.527  6097  6097 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-31 17:08:10.527  6097  6097 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-31 17:08:10.527  6097  6097 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
08-31 17:08:10.527  6097  6097 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-31 17:08:10.527  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:10.527  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 17:08:10.527  6097  6097 I SA      : [SCU] isHaveSA() - false
,08-31 17:08:10.527  6097  6097 I SA      : support phone number id : false
08-31 17:08:10.527  6097  6097 I SA      : [DM] Supports Ref Jpn : true
08-31 17:08:10.527  6097  6097 I SA      : [DM] init END
08-31 17:08:10.527  6097  6097 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-31 17:08:10.537  6097  6097 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 17:08:10.537  6097  6097 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 17:08:10.537  6097  6097 I SA      : [SLFUCHKMGR] constructor called
,08-31 17:08:10.547  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.547  7011  7011 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.547  6097  6097 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 17:08:10.547  6097  6097 I SA      : [OR] == isSIMCardReady false ==
,08-31 17:08:10.557  6097  6097 I SA      : [SCU] == networkStateCheck == false
08-31 17:08:10.557  6097  6097 I SA      : [OR] onReceive END
,08-31 17:08:10.567  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:10.567  7011  7011 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 17:08:10.587  6921  6921 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 17:08:10.587  6921  6921 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 17:08:10.597  1017  2930 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 17:08:10.597  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 17:08:10.597  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.597  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.597  1017  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 17:08:10.597  1017  1315 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.607  1017  2952 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.617  7032  7032 E Zygote  : MountEmulatedStorage()
,08-31 17:08:10.617  7032  7032 I libpersona: KNOX_SDCARD checking this for 10072
08-31 17:08:10.617  7032  7032 E Zygote  : v2
08-31 17:08:10.617  7032  7032 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:10.617  7032  7032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:10.617  1017  2930 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7032 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,08-31 17:08:10.627  7032  7032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 17:08:10.627  7032  7032 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 17:08:10.637  6921  6921 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 17:08:10.647  7032  7032 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:10.647  7032  7032 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.657  1017  1316 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.667  1017  2952 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:10.667  1017  1687 I ActivityManager: Killing 5572:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-31 17:08:10.667  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 17:08:10.667  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:10.667  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:10.667  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:10.677  1017  2736 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-31 17:08:10.677  1017  2736 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.677  1017  2736 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:10.677  1017  2736 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.677  1017  2736 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:10.687  7032  7032 D BadgeProvider: onCreate
,08-31 17:08:10.687  7032  7032 D BadgeProvider: DatabaseHelper
,08-31 17:08:10.697  6921  6921 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
08-31 17:08:10.697  6921  6921 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38a8a5a4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
08-31 17:08:10.697  1017  2736 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7049 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:08:10.697  6921  6921 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 17:08:10.697  6921  6921 D AndroidMusic: GMSCore installation verified
08-31 17:08:10.697  7049  7049 E Zygote  : MountEmulatedStorage(),
08-31 17:08:10.697  1017  2736 I ActivityManager: Killing 5946:com.google.android.apps.docs/u0a91 (adj 15): empty #31
08-31 17:08:10.707  7049  7049 E Zygote  : v2
08-31 17:08:10.707  7049  7049 I libpersona: KNOX_SDCARD checking this for 10159
08-31 17:08:10.707  7049  7049 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:10.707  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:10.707  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:10.707  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-31 17:08:10.747  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 17:08:10.747  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 17:08:10.747  7049  7049 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:10.867  1017  1492 I art     : Explicit concurrent mark sweep GC freed 57981(3MB) AllocSpace objects, 26(464KB) LOS objects, 33% free, 28MB/42MB, paused 2.652ms total 170.940ms
,08-31 17:08:10.867  1017  1218 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 17:08:10.867  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-31 17:08:10.877  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.877  1017  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:10.877  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:10.887  7032  7043 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 17:08:10.897  6921  6921 I ConfigStore: Config Database version: 1
,08-31 17:08:10.907  7032  7043 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 17:08:10.907  7032  7043 D BadgeProvider: sendNotify, [notify] : null
08-31 17:08:10.907  7032  7043 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 17:08:10.907  1479  1479 D Launcher.Model: reloadBadges entered.
08-31 17:08:10.907  7032  7043 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 17:08:10.907  7032  7043 D BadgeProvider: update, [UpdateCount] : 1
,08-31 17:08:10.927  1017  2930 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:10.927  1017  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.927  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:10.927  1017  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:10.927  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:10.927  1017  1315 I ActivityManager: Killing 6130:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-31 17:08:10.937  3819  3819 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 17:08:10.937  3819  4608 I iu.UploadsManager: num queued entries: 0
,08-31 17:08:10.947  3819  4608 I iu.UploadsManager: num updated entries: 0
,08-31 17:08:10.947  3819  4608 I iu.SyncManager: NEXT; no task
,08-31 17:08:10.967  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.967  1017  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 17:08:10.967  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.977  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 17:08:10.987   257   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 17:08:10.987   257   514 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 17:08:10.987  6921  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 17:08:10.997   257   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 17:08:10.997   257   514 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 17:08:10.997  6921  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 17:08:10.997   257   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 17:08:10.997   257   514 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 17:08:10.997  6921  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 17:08:11.007  1017  2952 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-31 17:08:11.007  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-31 17:08:11.007  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.007  1017  2952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:11.007  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.017  1017  1687 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:11.017  1017  1687 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-31 17:08:11.017  1017  1687 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.017  1017  1687 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:11.017  1017  1687 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.027  6538  6538 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:11.027  6538  6538 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 17:08:11.037  6538  6538 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 17:08:11.037  1017  1687 I ActivityManager: Killing 6152:com.samsung.helphub/1000 (adj 15): empty #31
,08-31 17:08:11.047  1017  3237 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:11.057  1017  2951 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:11.057  1017  1687 I AudioService: getStreamVolume 3 index 0
,08-31 17:08:11.057  6921  6921 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-31 17:08:11.067  6921  6921 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-31 17:08:11.087  1017  1492 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:11.087  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 17:08:11.087  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.087  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:11.087  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.087  1017  1218 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:11.087  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-31 17:08:11.087  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.087  1017  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:11.087  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.097  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:11.097  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-31 17:08:11.097  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:11.097  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:11.097  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.097  1017  1316 I ActivityManager: Killing 5930:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-31 17:08:11.107  1017  3238 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-31 17:08:11.117  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 17:08:11.127  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:11.127  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 17:08:11.127  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:11.127  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:11.137  7077  7077 E Zygote  : MountEmulatedStorage(),
08-31 17:08:11.137  7077  7077 E Zygote  : v2
,08-31 17:08:11.137  7077  7077 I libpersona: KNOX_SDCARD checking this for 10002
08-31 17:08:11.137  7077  7077 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:11.137  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:11.137  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:11.137  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:11.147  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7077 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:08:11.177  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:11.177  7077  7077 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:11.197  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-31 17:08:11.197  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 17:08:11.197  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.197  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:11.197  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-31 17:08:11.207  6921  6921 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-31 17:08:11.217  1017  3238 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:11.217  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 17:08:11.217  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:11.217  1017  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:11.217  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:11.237  1017  1218 I ActivityManager: Killing 5537:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-31 17:08:11.247  1017  1218 I ActivityManager: Killing 5117:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
,08-31 17:08:11.247  1017  1029 I ActivityManager: Killing 6047:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-31 17:08:11.257  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 17:08:11.257  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:11.257  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:11.257  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:11.257  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:11.267  7096  7096 E Zygote  : MountEmulatedStorage(),
08-31 17:08:11.277  7096  7096 E Zygote  : v2
08-31 17:08:11.277  7096  7096 I libpersona: KNOX_SDCARD checking this for 1000
08-31 17:08:11.277  7096  7096 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:11.277  1017  1029 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-31 17:08:11.277  7096  7096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:11.277  7096  7096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:11.287  7096  7096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 17:08:11.297   312   312 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 27.251ms,
,08-31 17:08:11.297  7096  7096 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:11.297  7096  7096 D ActivityThread: Added TimaKeyStore provider,
,08-31 17:08:11.317   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.912ms
,08-31 17:08:11.337   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 16.760ms
,08-31 17:08:11.337  7096  7096 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 17:08:11.447  7096  7096 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 17:08:11.447  7096  7096 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 17:08:11.457  7096  7096 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:11.457  7096  7096 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 17:08:11.457  7096  7096 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-31 17:08:11.457  7096  7096 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 17:08:11.457  1017  3237 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,08-31 17:08:11.457  1017  3237 I ActivityManager: Killing 5494:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-31 17:08:11.567  1017  1315 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 17:08:11.567  1017  1315 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 17:08:11.567  1017  1315 D SecContentProvider2: mCursor = null
,08-31 17:08:11.567  1017  1315 D WifiService: setWifiEnabled: true pid=6683, uid=10155
,08-31 17:08:11.567  1017  1315 W ActivityManager: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 17:08:11.567  1017  1315 W WifiService: Failed getting userId using ActivityManagerNative
08-31 17:08:11.567  1017  1315 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:11.567  1017  1315 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 17:08:11.567  1017  1315 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 17:08:11.567  1017  1315 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 17:08:11.567  1017  1315 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 17:08:11.567  1017  1315 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 17:08:11.567  1017  1315 D SettingsProvider: name = wifi_on
,08-31 17:08:11.567  1017  1131 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 17:08:11.937  1017  1044 D Tethering: interfaceAdded wlan0
,08-31 17:08:11.947  1017  1134 E Tethering: No numeric data
,08-31 17:08:11.947  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:11.947  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 17:08:11.947  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:11.947  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:11.957  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:11.957  1017  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:08:11.957  1017  1134 D Tethering: clearTetheredNotification()
,08-31 17:08:11.957  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:11.957  1017  1124 V NetworkStats: performPollLocked() took 7ms
,08-31 17:08:11.957  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 17:08:11.957  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:11.957  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:11.967  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 17:08:11.967  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:11.967  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:11.967  1017  1134 D Tethering: InitialState.processMessage what=4
,08-31 17:08:11.967  1017  1134 E Tethering: No numeric data
,08-31 17:08:11.967  1017  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 17:08:11.967  1017  1134 D Tethering: clearTetheredNotification()
,08-31 17:08:11.977  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:11.977  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:11.977  1017  1044 D Tethering: interfaceAdded p2p0
08-31 17:08:11.977  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:11.977  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:11.977  1177  1177 D HotspotTile: updateTetherState():false, false
08-31 17:08:11.977  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:11.977  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 17:08:11.977  1017  1124 V NetworkStats: performPollLocked() took 9ms
08-31 17:08:11.977  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:11.987  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:11.987  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:11.987  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:11.987  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:11.987  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:11.987   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-31 17:08:11.987   278   983 D SoftapController: Softap fwReload - Ok
,08-31 17:08:11.997   278   983 D CommandListener: Setting iface cfg
08-31 17:08:11.997   278   983 D CommandListener: Trying to bring down wlan0
,08-31 17:08:11.997   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:08:11.997  1017  1131 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 17:08:12.007  1017  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 17:08:12.007  1017  1131 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 17:08:12.007  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:12.007  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:12.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:12.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:12.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:12.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-31 17:08:12.017  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:12.017  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 17:08:12.017  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 17:08:12.017  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:12.017  1177  1177 D HotspotTile: onReceive : 2, 0
08-31 17:08:12.017  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:12.017  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:12.017  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:12.017  1017  1313 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:12.017  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-31 17:08:12.037  1017  1313 W ActivityManager: userId = 0, bbcId = -10000,
08-31 17:08:12.037  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:12.037  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:12.037  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:12.037  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:12.037  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 17:08:12.037  3674  3674 I Hs20UtilService: Starting #12
08-31 17:08:12.037  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:12.037  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:12.057  7120  7120 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-31 17:08:12.057  7120  7120 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 17:08:12.057  7120  7120 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 17:08:12.067  7120  7120 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-31 17:08:12.067   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7120
08-31 17:08:12.067   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 17:08:12.067  7120  7120 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-31 17:08:12.067  7120  7120 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:12.067  7120  7120 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 17:08:12.067  7120  7120 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 17:08:12.077   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7120
08-31 17:08:12.077   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 17:08:12.087   288   288 E SMD     : DCD OFF,
,08-31 17:08:12.217   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-31 17:08:12.227  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-31 17:08:12.287  7120  7120 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 17:08:12.287  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 17:08:12.297  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 17:08:12.297   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7120
08-31 17:08:12.297   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 17:08:12.297  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 17:08:12.297  7120  7120 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:12.297  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 17:08:12.307  7120  7120 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:12.307  7120  7120 E wpa_supplicant: SIM READ ERROR
08-31 17:08:12.307  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 17:08:12.307  7120  7120 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:12.307  7120  7120 E wpa_supplicant: SIM READ ERROR
08-31 17:08:12.307  7120  7120 I wpa_supplicant: Blacklist: Clear (all) 
08-31 17:08:12.307  7120  7120 I wpa_supplicant: wpa_default_ap_write_once,
08-31 17:08:12.307  7120  7120 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 17:08:12.307  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:12.307  7120  7120 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-31 17:08:12.307  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:12.307  7120  7120 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 17:08:12.307  7120  7120 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 17:08:12.317  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:12.317  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:12.317  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:12.417  7120  7120 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 17:08:12.597  7120  7120 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 17:08:12.597  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 17:08:12.607  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 17:08:12.617   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7120
08-31 17:08:12.617   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 17:08:12.617  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-31 17:08:12.617  7120  7120 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:12.617  7120  7120 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 17:08:12.617  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 17:08:12.627  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 17:08:12.627   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7120
08-31 17:08:12.627   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-31 17:08:12.627  7120  7120 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 17:08:12.627  7120  7120 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:12.637  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 17:08:12.627  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:12.627  7120  7120 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:12.627  7120  7120 E wpa_supplicant: SIM READ ERROR
08-31 17:08:12.627  7120  7120 I wpa_supplicant: wpa_default_ap_write_once
08-31 17:08:12.627  7120  7120 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 17:08:12.627  7120  7120 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 17:08:12.627  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:12.627  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:12.637  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 17:08:12.637  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 17:08:12.637  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:12.677  7120  7120 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 17:08:12.677  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 17:08:12.737  7120  7120 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 17:08:12.737  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 17:08:12.737  7120  7120 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-31 17:08:12.937  1017  3236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 17:08:12.937  1017  3236 D BatteryService: level:54, scale:100, status:2, health:2, present:true, voltage: 3833, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 17:08:12.937  1017  3236 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 17:08:12.937  1017  3236 D BatteryService: stay LED for charging,
08-31 17:08:12.937  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 17:08:12.937  1017  1017 I MotionRecognitionService: Plugged,
08-31 17:08:12.937  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 17:08:12.947  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 17:08:12.947  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 17:08:12.947  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 17:08:12.947  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 54
,08-31 17:08:12.967  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 17:08:12.967  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:12.967  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:12.967  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:12.967  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:12.977  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:13.007  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-31 17:08:13.017  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 17:08:13.017  7120  7120 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-31 17:08:13.017  7120  7120 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:13.017  7120  7120 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:13.017  7120  7120 E wpa_supplicant: SIM READ ERROR
08-31 17:08:13.017  7120  7120 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 17:08:13.037  7120  7120 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 17:08:13.047  1017  1131 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 17:08:13.047  7120  7120 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 17:08:13.047  1017  1131 D WifiConfigStore: Loading config and enabling all networks 
,08-31 17:08:13.047  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 17:08:13.047  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:13.047  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:13.047  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:13.057  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 17:08:13.047  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:13.047  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 17:08:13.057  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:13.057  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:13.057  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 17:08:13.057  1177  1177 D HotspotTile: onReceive : 3, 0
,08-31 17:08:13.057  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:13.067  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:13.067  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:13.067  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:13.067  1017  1131 E WifiConfigStore: Not a HS20
,08-31 17:08:13.067  1017  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 17:08:13.067  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:13.067  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:13.067  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:13.067  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:13.077  1017  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 17:08:13.077  1017  2736 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:13.077  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:13.077  1017  2736 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:13.077  1017  2736 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:13.077  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:13.077  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 17:08:13.077  7120  7120 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 17:08:13.077  7120  7120 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 17:08:13.077  7120  7120 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 17:08:13.077  7120  7120 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 17:08:13.077  7120  7120 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 17:08:13.077  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 17:08:13.077  7120  7120 I wpa_supplicant: First Scan Start
08-31 17:08:13.087  7120  7120 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 17:08:13.087  3674  3674 I Hs20UtilService: Starting #13
08-31 17:08:13.087  3674  3690 I Hs20UtilService: Message received 5011,
,08-31 17:08:13.087  1017  1131 D WifiNative-wlan0: Setting external_sim to 1
,08-31 17:08:13.087  6858  6858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:08:13.087  1017  1131 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 17:08:13.087  1017  1131 I WifiNative-HAL: startHal,
08-31 17:08:13.087  1017  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9c95b88c
08-31 17:08:13.087  1017  1131 I WifiNative-HAL: Could not start hal,
,08-31 17:08:13.097  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 17:08:13.097  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 17:08:13.097  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:13.097  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:13.097  1017  1131 E WifiNative-wlan0: do suspend true
,08-31 17:08:13.097  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 17:08:13.097  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
08-31 17:08:13.097   278   983 D CommandListener: Setting iface cfg,
08-31 17:08:13.097   278   983 D CommandListener: Trying to bring up p2p0
08-31 17:08:13.107  1017  1126 D WifiP2pService: P2pEnablingState
08-31 17:08:13.097  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 17:08:13.107  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 17:08:13.107  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 17:08:13.107  1017  1126 D WifiP2pService: P2p socket connection successful
08-31 17:08:13.107  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:13.107  1017  1126 D WifiP2pService: P2pEnabledState
08-31 17:08:13.107  1017  1150 I WifiNative-HAL: startHal
08-31 17:08:13.107  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9db0d9bc
,08-31 17:08:13.107  1017  1150 I WifiNative-HAL: Could not start hal
08-31 17:08:13.107  1017  1150 E WifiScanningService: could not start HAL
08-31 17:08:13.107  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 17:08:13.107  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:13.107  1017  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 17:08:13.107  1017  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 17:08:13.107  1017  1131 E WifiNative-wlan0: invaild command id : 215
,08-31 17:08:13.107  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 17:08:13.107  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 17:08:13.107  1017  1133 E ConnectivityService: updateNetworkInfo()
,08-31 17:08:13.107  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 17:08:13.117  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 17:08:13.117  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 17:08:13.117  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-31 17:08:13.117  1017  1047 D WifiDisplayController: disconnect
08-31 17:08:13.117  1017  1047 D WifiDisplayController: updateConnection
08-31 17:08:13.117  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:13.117  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:13.117  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-31 17:08:13.117  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 17:08:13.117  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 17:08:13.117  1017  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
08-31 17:08:13.117  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:08:13.117  1017  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 17:08:13.117  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 17:08:13.117  1017  1131 E WifiNative-wlan0: invaild command id : 215
08-31 17:08:13.117  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 17:08:13.117  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:13.117  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 17:08:13.117  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:13.127  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 17:08:13.127  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 17:08:13.127  1017  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:13.127  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 17:08:13.127  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:13.127  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:13.127  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 17:08:13.127  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 17:08:13.127  1017  1131 D SecContentProvider2: mCursor = null
08-31 17:08:13.127  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:13.127  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-31 17:08:13.127  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 17:08:13.127  1017  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-31 17:08:13.127  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  secondary type: null
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  wps: 0
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  grpcapab: 0
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  devcapab: 0
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  status: 3
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  wfdInfo: null
,08-31 17:08:13.127  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-31 17:08:13.127  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-31 17:08:13.137  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:13.137  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-31 17:08:13.137  6826  6826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 17:08:13.137  6842  6842 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:13.157  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 17:08:13.157  1017  1126 D WifiP2pService: InactiveState
,08-31 17:08:13.157  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-31 17:08:13.157  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 17:08:13.157  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 17:08:13.157  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-31 17:08:13.157  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 17:08:14.347  7120  7120 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
08-31 17:08:14.347  7120  7120 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-31 17:08:14.347  7120  7120 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-31 17:08:14.347  7120  7120 I wpa_supplicant: Trying to associate with  'G700'
,08-31 17:08:14.347  7120  7120 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-31 17:08:14.357  1017  7127 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-31 17:08:14.357  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 17:08:14.367  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:14.367  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.477  7120  7120 E wpa_supplicant: Cmd 35605 not handled
,08-31 17:08:14.477  7120  7120 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-31 17:08:14.477  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 17:08:14.477  7120  7120 I wpa_supplicant: Associated with F4.99.3E
08-31 17:08:14.477  7120  7120 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 17:08:14.477  7120  7120 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 17:08:14.477  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 17:08:14.477  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 17:08:14.477  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:14.477  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:14.477  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 17:08:14.477  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:14.487  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 17:08:14.487  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 17:08:14.487  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:14.487  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 17:08:14.487  7120  7120 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 17:08:14.487  7120  7120 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 17:08:14.487  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true,
08-31 17:08:14.487  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-31 17:08:14.487  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 17:08:14.487  7120  7120 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 17:08:14.487  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-31 17:08:14.487  7120  7120 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:08:14.487  7120  7120 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 17:08:14.487  7120  7120 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 17:08:14.487  7120  7120 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 17:08:14.487  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030,
,08-31 17:08:14.487  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 17:08:14.487  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 17:08:14.497  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:14.497  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.497  1017  1134 E Tethering: No numeric data
08-31 17:08:14.497  1017  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:08:14.497  1017  1134 D Tethering: clearTetheredNotification()
08-31 17:08:14.497  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 17:08:14.497  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 17:08:14.497  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:14.497  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-31 17:08:14.497  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 17:08:14.497  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:14.497  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:14.507  1017  1124 V NetworkStats: performPollLocked() took 6ms
08-31 17:08:14.507  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:14.507  1017  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 17:08:14.507  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:14.507  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:14.507  1017  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 17:08:14.517  1017  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 17:08:14.517  1017  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 17:08:14.517  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:14.517  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 17:08:14.517  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:14.517  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:14.517  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.517  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.517  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.517  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.527  1017  1687 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:14.527  1017  1687 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:14.527  1017  1687 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:14.527  1017  1687 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:14.527  1017  1687 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:14.527  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:08:14.537  3674  3674 I Hs20UtilService: Starting #14
,08-31 17:08:14.537  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:14.537  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 17:08:14.537  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:14.537  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:08:14.547  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:14.547  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 17:08:14.547  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 17:08:14.547  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:14.547  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:14.557   278   983 D CommandListener: Setting iface cfg
,08-31 17:08:14.557  1017  1131 E WifiStateMachine: Start Dhcp Watchdog 2,
08-31 17:08:14.557  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:14.557  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.567  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 17:08:14.567  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.577  1017  1315 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 17:08:14.577  1017  1315 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 17:08:14.577  1017  1315 D SecContentProvider2: mCursor = null
,08-31 17:08:14.577  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:14.577  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 17:08:14.577  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.577  1017  1315 D WifiService: setWifiEnabled: false pid=6683, uid=10155
08-31 17:08:14.577  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.577  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.577  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.577  1017  1315 D SettingsProvider: name = wifi_on
,08-31 17:08:14.577  1017  1131 E WifiNative-wlan0: do suspend false
,08-31 17:08:14.577  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:14.577  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.587  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-31 17:08:14.587  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 17:08:14.587  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:08:14.607  1017  1131 E WifiNative-wlan0: do suspend true
,08-31 17:08:14.627  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-31 17:08:14.627  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 17:08:14.627  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:14.627  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:14.627  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.627  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.637  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.637   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:08:14.637  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.637  1017  1133 E ConnectivityService: updateNetworkInfo(),
,08-31 17:08:14.637  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:08:14.637  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-31 17:08:14.637   278   983 E Netd    : no such netId 503
,08-31 17:08:14.647  1017  7131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:14.647  1017  1133 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
08-31 17:08:14.647  1017  7131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 17:08:14.647  1017  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 17:08:14.647  1017  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 17:08:14.647  1017  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-31 17:08:14.647  1017  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 17:08:14.647  1017  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 17:08:14.647  1017  1133 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 17:08:14.647  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 17:08:14.657  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:14.657  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:14.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.657  1017  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
08-31 17:08:14.657  1017  3237 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:14.657  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:14.657  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:14.657  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:14.657  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-31 17:08:14.657  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:14.657  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 17:08:14.657  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:14.657  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 17:08:14.657  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 17:08:14.667  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-31 17:08:14.667  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:14.667  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:14.667  3674  3674 I Hs20UtilService: Starting #15
,08-31 17:08:14.667  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:14.667  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:14.667  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:14.667  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:14.667  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:08:14.667  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 17:08:14.667  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 17:08:14.667  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:14.667  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 17:08:14.667  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 17:08:14.667  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 17:08:14.667  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:14.667  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 17:08:14.667  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:14.667  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 17:08:14.667  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:14.667  1017  1047 D WifiDisplayController: disconnect
08-31 17:08:14.667  1017  1047 D WifiDisplayController: updateConnection
08-31 17:08:14.667  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:14.677  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:14.677  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:14.677  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 17:08:14.677  1017  1139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:14.677  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 17:08:14.677  1017  1126 D WifiP2pService: P2pDisablingState
,08-31 17:08:14.677  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 17:08:14.677  1017  1126 D WifiP2pService: p2p socket connection lost
,08-31 17:08:14.677  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 17:08:14.677  1017  1131 E WifiNative-wlan0: do suspend true
08-31 17:08:14.677  1017  1126 D WifiP2pService: P2pDisabledState
08-31 17:08:14.677  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-31 17:08:14.687  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 17:08:14.687  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 17:08:14.687  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 17:08:14.687  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:14.687  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:14.687  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:14.687  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 17:08:14.687  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 17:08:14.697  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:14.697  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:14.697  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 17:08:14.697  6826  6826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 17:08:14.707  6842  6842 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:14.717  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 17:08:14.717  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-31 17:08:14.717   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:08:14.717  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:14.717  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:14.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.717  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.717  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-31 17:08:14.727  7120  7120 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 17:08:14.727  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:14.727  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:14.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.727  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.737  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:14.737  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:14.737  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:14.737  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-31 17:08:14.737  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.737  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.737  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:14.737  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:14.737  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:14.737  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 17:08:14.747  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 17:08:14.747  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:14.747  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:14.747  1017  3238 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:14.747  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:14.747  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:08:14.747  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:14.747  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:14.747  1177  1177 D HotspotTile: onReceive : 0, 0
,08-31 17:08:14.747  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:14.747  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:08:14.747  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:08:14.747  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:14.747  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:14.747  1017  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:14.747  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:14.757  3674  3674 I Hs20UtilService: Starting #16
,08-31 17:08:14.757  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:14.757  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:14.757  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:14.757  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:14.757  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:14.757  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 17:08:14.757  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:14.757  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:14.767  1017  1313 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:14.767  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:14.767  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:14.767  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:14.767  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:14.767  3674  3674 I Hs20UtilService: Starting #17
,08-31 17:08:14.777  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:14.777  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:14.777  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:14.777  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 17:08:14.777  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:14.797  7134  7134 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 17:08:14.797  7134  7134 I dhcpcd  : version 5.5.6 starting
,08-31 17:08:14.797  7134  7134 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 17:08:14.857  7134  7134 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 17:08:14.857  7134  7134 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 17:08:14.857  7134  7134 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 17:08:14.857  7134  7134 I dhcpcd  : bssid match,
08-31 17:08:14.857  7134  7134 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-31 17:08:14.977  7120  7120 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 17:08:14.987  7134  7134 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-31 17:08:15.097   288   288 E SMD     : DCD OFF,
,08-31 17:08:15.107  7134  7134 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-31 17:08:15.107  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 17:08:15.107  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:15.107  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 17:08:15.107  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:15.127  7120  7120 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-31 17:08:15.137  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.137  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:15.137  1017  1134 D Tethering: InitialState.processMessage what=4
08-31 17:08:15.137  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.137  7120  7120 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 17:08:15.137  1017  1131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-31 17:08:15.137  7120  7120 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 17:08:15.137  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.137  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:15.137  1017  1134 E Tethering: No numeric data
,08-31 17:08:15.137  7120  7120 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-31 17:08:15.137  7120  7120 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 17:08:15.147  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.147  1017  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:08:15.147  1017  1134 D Tethering: clearTetheredNotification()
,08-31 17:08:15.157  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.157  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:15.157  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 17:08:15.157  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:15.157  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:15.157  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:15.157  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:15.157  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 17:08:15.157  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:15.177  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 17:08:15.177  1017  1124 V NetworkStats: performPollLocked() took 16ms
08-31 17:08:15.177  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:15.177  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:15.387  7120  7120 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 17:08:15.477  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 17:08:15.477  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.477  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:15.487  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 17:08:15.477  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 17:08:15.477  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:15.477  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 17:08:15.587  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-31 17:08:15.587  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 17:08:15.587  1017  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 17:08:15.597  6858  6858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:08:15.597  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:15.597  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:15.597  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:15.597  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:15.597  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:15.597  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:15.607  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:15.607  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 17:08:15.607  1933  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:08:15.607  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:15.607  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 17:08:15.607  1177  1177 D HotspotTile: onReceive : 1, 0
,08-31 17:08:15.607  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:15.607  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:15.617  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:15.617  1017  3236 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:15.617  1017  3236 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:15.617  1017  3236 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:15.617  1017  3236 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:15.617  1017  3236 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:15.617  3674  3674 I Hs20UtilService: Starting #18
,08-31 17:08:15.617  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:15.627  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:15.627  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 17:08:15.627  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:15.627  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:15.907  1017  2758 D SSRM:n  : SIOP:: AP = 340
,08-31 17:08:16.047  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.047  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:16.047  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.057  1017  3238 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-31 17:08:16.067  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-31 17:08:16.067  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.067  1017  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.067  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.077  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.077  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:16.077  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.087  1017  2952 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:16.087  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-31 17:08:16.097  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.097  1017  2952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.097  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.097  1017  1316 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:16.097  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-31 17:08:16.097  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.097  1017  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.097  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.107  1017  3236 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:16.107  1017  3236 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 17:08:16.107  1017  3236 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.107  1017  3236 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.107  1017  3236 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.117  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-31 17:08:16.117  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-31 17:08:16.117  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.117  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.117  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.147  1017  2951 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:16.147  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:16.157  1017  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.157  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-31 17:08:16.157  1933  1933 D WearableService: callingUid 10012, callindPid: 1933
,08-31 17:08:16.167  1017  2952 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 17:08:16.167  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 17:08:16.167  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:16.167  1017  2952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:16.167  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 17:08:16.187  6921  7162 I MusicLeanback: Conditions not met for autocaching.
,08-31 17:08:16.187  6921  7162 I MusicLeanback: Stop autocaching.
,08-31 17:08:16.207  6921  6921 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-31 17:08:16.207  6921  7167 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-31 17:08:16.297   278   977 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-31 17:08:16.297  1017  1044 D Tethering: interfaceRemoved wlan0,
08-31 17:08:16.297  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 17:08:16.507  1017  1044 D Tethering: interfaceRemoved p2p0
,08-31 17:08:16.507  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 17:08:17.317  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-31 17:08:17.587  6683  6736 D BluetoothAdapter: enable(),
,08-31 17:08:17.597  1017  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-31 17:08:17.597  1017  1492 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-31 17:08:17.597  1017  1492 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 17:08:17.597  1017  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 17:08:17.597  1017  1492 D SettingsProvider: name = bluetooth_on
08-31 17:08:17.597  1017  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 17:08:17.597  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 17:08:17.597  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 17:08:17.607  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-31 17:08:17.607  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 17:08:17.637  6901  6901 D BluetoothAdapterState: make
,08-31 17:08:17.647  6901  6901 I bluedroid: init
,08-31 17:08:17.647  6901  7171 I BluetoothAdapterState: Entering OffState
,08-31 17:08:17.647  6901  6901 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 17:08:17.647  6901  6901 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 17:08:17.647  6901  6901 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 17:08:17.647  6901  6901 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 17:08:17.647  6901  6901 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-31 17:08:17.647  6901  6901 I bluedroid: get_profile_interface socket
08-31 17:08:17.647  6901  6901 I bluedroid: get_profile_interface map_client
08-31 17:08:17.647  6901  7174 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 17:08:17.657  6901  7174 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-31 17:08:17.657  6901  7174 E BluetoothServiceJni: populateRssiValuesNative
08-31 17:08:17.657  6901  7174 I bluedroid: getModelRssiValues
,08-31 17:08:17.657  6901  6901 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-31 17:08:17.657  6901  7174 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 17:08:17.657  6901  7174 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 17:08:17.657  6901  7174 D BluetoothAdapterProperties: Name is: A5-1
,08-31 17:08:17.657  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 17:08:17.667  6901  6901 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:17.667  1017  1313 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 17:08:17.667  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.667  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:17.667  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.667  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.667  6901  6916 I bluedroid: config_hci_snoop_log
,08-31 17:08:17.677  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-31 17:08:17.677  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-31 17:08:17.677  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 17:08:17.677  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 17:08:17.677  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 17:08:17.687  6901  6901 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 17:08:17.687  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 17:08:17.687  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 17:08:17.687  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 17:08:17.687  6901  7171 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 17:08:17.687  6901  7171 D BluetoothAdapterProperties: Setting state to 11
08-31 17:08:17.687  6901  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 17:08:17.697  6901  7171 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:17.697  6901  7171 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 17:08:17.697  6901  7171 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:17.697  6901  7171 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 17:08:17.697  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:17.697  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 17:08:17.707  6901  7171 D BluetoothSecureManager: getInstant: null
08-31 17:08:17.707  6901  7171 D BluetoothSecureManager: calling getMethod for getService
08-31 17:08:17.707  6901  7171 D BluetoothSecureManager: calling getService
,08-31 17:08:17.707  6901  7171 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@7fc0567
,08-31 17:08:17.707  1017  1029 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 17:08:17.707  1017  1029 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 17:08:17.707  6901  7171 D BtConfig.SecureMode: isSecureModeOn:false
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 17:08:17.707  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 17:08:17.707  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 17:08:17.707  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:17.707  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 17:08:17.707  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:17.707  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:17.707  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-31 17:08:17.707  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 17:08:17.707  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 17:08:17.717  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 17:08:17.717  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:17.717  1771  1771 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 17:08:17.717  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 17:08:17.717  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 17:08:17.717  6901  7171 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 17:08:17.717  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 17:08:17.717  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:17.717  1017  2930 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:17.717  1017  3238 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:17.717  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 17:08:17.717  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.717  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 17:08:17.717  6901  7171 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:17.717  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:17.717  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:17.727  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.727  1017  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:17.727  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:17.727  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:17.727  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-31 17:08:17.727  6901  7171 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:17.727  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:17.727  6901  7171 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:17.727  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 17:08:17.727  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 17:08:17.727  6901  7171 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 17:08:17.727  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:17.727  6901  7171 D BluetoothBondStateMachine: make
,08-31 17:08:17.727  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:17.737  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 17:08:17.737  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 17:08:17.737  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 17:08:17.737  6901  7175 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 17:08:17.737  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:17.737  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 17:08:17.737  1017  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 17:08:17.737  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.737  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-31 17:08:17.737  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.737  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.737  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 17:08:17.737  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 17:08:17.737  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 17:08:17.737  1017  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:17.737  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.737  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.737  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.737  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:17.737  6901  6901 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:08:17.747  6901  6901 D BtGatt.GattService: Received start request. Starting profile...
08-31 17:08:17.747  6901  6901 D BtGatt.GattService: start()
08-31 17:08:17.747  6901  6901 D BtGatt.GattService: start()
08-31 17:08:17.747  6901  6901 I bluedroid: get_profile_interface gatt
,08-31 17:08:17.747  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:17.747  6901  6901 D BtGatt.AdvertiseManager: advertise manager created
,08-31 17:08:17.747  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 17:08:17.747  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 17:08:17.747  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 17:08:17.747  1017  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:17.747  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.747  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 17:08:17.747  1017  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:17.747  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.757  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 17:08:17.757  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:17.757  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 17:08:17.757  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:17.757  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.757  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.757  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.757  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.757  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-31 17:08:17.757  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:17.757  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 17:08:17.767  1017  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:17.767  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.767  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.767  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:17.767  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.767  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-31 17:08:17.767  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 17:08:17.767  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 17:08:17.777  1017  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:17.777  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.777  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:17.777  1017  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.777  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.777  6901  6901 D BtGatt.GattService: mStartError = false
08-31 17:08:17.777  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.777  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 17:08:17.777  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:17.777  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:17.777  6901  6901 D HeadsetService: Received start request. Starting profile...
08-31 17:08:17.777  6901  6901 D HeadsetService: start()
08-31 17:08:17.777  1017  2736 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:17.777  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.777  1017  2736 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.777  1017  2736 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.777  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.787  6901  6901 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 17:08:17.787  6901  6901 D HeadsetStateMachine: make
,08-31 17:08:17.787  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 17:08:17.787  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:17.787  6901  7171 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 17:08:17.787  1017  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:17.787  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.787  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.787  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.787  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:17.787  6901  6901 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
08-31 17:08:17.797  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:17.797  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 17:08:17.797  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 17:08:17.797  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 17:08:17.797  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 17:08:17.797  6901  7171 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 17:08:17.797  1017  2951 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 17:08:17.797  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.797  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.797  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.797  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 17:08:17.797  1017  1139 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 17:08:17.797  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 17:08:17.797  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:17.797  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:17.797  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 17:08:17.807  6901  6901 I bluedroid: get_profile_interface handsfree
,08-31 17:08:17.817  6901  6901 I DualScoManager: Instantiating Dual Sco Manager
,08-31 17:08:17.817  6901  6901 I DualScoManager: Set HeadsetServiceHelper
,08-31 17:08:17.817  6901  6901 D BluetoothAtMessage: createCMTIContentObservers
,08-31 17:08:17.817  1017  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 17:08:17.817  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:17.817  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:17.817  1017  1030 D SettingsProvider: selectionArgs: false
,08-31 17:08:17.817  1017  1030 D SettingsProvider: selectionArgs: 1002
08-31 17:08:17.817  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:17.827  1017  1030 D SettingsProvider: ret = -1
,08-31 17:08:17.827  6901  7182 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 17:08:17.827  6901  6901 D HeadsetService: mStartError = false
08-31 17:08:17.827  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.827  6901  6901 D A2dpService: Received start request. Starting profile...
08-31 17:08:17.827  6901  6901 D A2dpService: start()
,08-31 17:08:17.827  6901  7182 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 17:08:17.827  6901  7182 D HeadsetStateMachine: map size, before remove : 0
,08-31 17:08:17.827  6901  7182 D HeadsetStateMachine: map size, after remove: 0
08-31 17:08:17.827  6901  6901 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 17:08:17.827  6901  6901 I bluedroid: get_profile_interface avrcp
,08-31 17:08:17.837  6901  6901 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 17:08:17.847  6901  6901 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 17:08:17.847  6901  7183 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 17:08:17.847  6901  6901 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:08:17.847  6901  6901 D A2dpStateMachine: make
,08-31 17:08:17.857  6901  6901 I bluedroid: get_profile_interface a2dp
08-31 17:08:17.857  6901  7185 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 17:08:17.857  6901  6901 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 17:08:17.857  6901  6901 D A2dpService: mStartError = false
08-31 17:08:17.857  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.857  6901  6901 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 17:08:17.857  6901  7184 D A2dpStateMachine: Enter Disconnected: -2
,08-31 17:08:17.857  6901  6901 D HidService: Received start request. Starting profile...
08-31 17:08:17.857  6901  6901 D HidService: start()
08-31 17:08:17.857  6901  6901 I bluedroid: get_profile_interface hidhost
08-31 17:08:17.857  6901  6901 D HidService: setHidService(): set to: null
08-31 17:08:17.857  6901  6901 D HidService: mStartError = false
08-31 17:08:17.857  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.857  6901  6901 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 17:08:17.857  6901  6901 D HealthService: Received start request. Starting profile...
08-31 17:08:17.857  6901  6901 D HealthService: start()
,08-31 17:08:17.867  6901  6901 I bluedroid: get_profile_interface health
08-31 17:08:17.867  6901  6901 D HealthService: mStartError = false
08-31 17:08:17.867  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.867  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 17:08:17.867  6901  6901 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 17:08:17.867  6901  6901 D PanService: Received start request. Starting profile...
08-31 17:08:17.867  6901  6901 D PanService: start()
08-31 17:08:17.867  6901  6901 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 17:08:17.867  6901  6901 I bluedroid: get_profile_interface pan
,08-31 17:08:17.867  6901  6901 D PanService: mStartError = false
08-31 17:08:17.867  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.867  6901  6901 D BluetoothMapService: Received start request. Starting profile...
08-31 17:08:17.867  6901  6901 D BluetoothMapService: start()
,08-31 17:08:17.877  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:17.877  6901  7183 D BluetoothMediaBrowser: no now playing list
,08-31 17:08:17.877  6901  7183 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 17:08:17.887  6901  6901 D BluetoothMapService: mStartError = false
,08-31 17:08:17.887  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.887  6901  6901 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 17:08:17.887  6901  6901 D SapService: Received start request. Starting profile...
,08-31 17:08:17.887  6901  6901 D SapService: start()
08-31 17:08:17.887  6901  6901 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 17:08:17.887  6901  6901 I bluedroid: get_profile_interface sap
08-31 17:08:17.887  6901  6901 D SapService: mStartError = false
08-31 17:08:17.887  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:17.887  6901  6901 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 17:08:17.887  1434  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 17:08:17.887  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 17:08:17.887  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 17:08:17.897  1434  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 17:08:17.897  6901  6901 D HeadsetStateMachine: Proxy object connected
,08-31 17:08:17.897  6901  6901 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 17:08:17.897  6901  6901 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 17:08:17.897  6901  6901 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 17:08:17.897  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 17:08:17.897  6901  6901 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 17:08:17.897  6901  6901 D BluetoothA2dp: Proxy object connected
08-31 17:08:17.897  6901  6901 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 17:08:17.897  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 17:08:17.897  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 17:08:17.897  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 17:08:17.897  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 17:08:17.897  6901  7182 D HeadsetStateMachine: Disconnected process message: 11
08-31 17:08:17.897  6901  7182 D HeadsetStateMachine: Disconnected process message: 18
08-31 17:08:17.897  6901  7182 D HeadsetStateMachine: Disconnected process message: 10
08-31 17:08:17.897  6901  7182 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-31 17:08:17.897  6901  7182 D HeadsetStateMachine: Disconnected process message: 11
,08-31 17:08:17.897  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:17.927  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 17:08:17.927  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 17:08:17.927  6901  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 17:08:17.927  6901  7171 I bluedroid: enable
,08-31 17:08:17.927  6901  7190 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 17:08:17.927  6901  7171 I bt_hci_bdroid: init
,08-31 17:08:17.937  6901  7171 I bt_vendor: bt-vendor : init
,08-31 17:08:17.937  6901  7171 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 17:08:17.937  6901  7171 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-31 17:08:17.937  6901  7171 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-31 17:08:17.937  6901  7171 D bt_userial_mct: userial_init
,08-31 17:08:17.937  6901  7171 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 17:08:17.937  6901  7171 I bt_vendor: Starting hciattach daemon
,08-31 17:08:17.937  6901  7171 I bt_vendor: try to set false
,08-31 17:08:17.937  6901  7171 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 17:08:17.937  6901  7171 I bt_vendor: Starting hciattach daemon
08-31 17:08:17.937  6901  7171 I bt_vendor: try to set true
,08-31 17:08:17.967  7194  7194 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 17:08:18.027  7200  7200 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 17:08:18.037  7201  7201 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 17:08:18.057  7203  7203 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 17:08:18.057  7204  7204 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 17:08:18.067  7205  7205 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 17:08:18.077  7206  7206 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 17:08:18.097   288   288 E SMD     : DCD OFF
,08-31 17:08:18.317  7209  7209 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-31 17:08:18.327  7210  7210 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 17:08:18.347  6901  7171 I bt_vendor: bluetooth satus is on
,08-31 17:08:18.347  6901  7192 D bt_userial_mct: userial_open(port:0),
08-31 17:08:18.347  6901  7192 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 17:08:18.347  6901  7192 I bt_vendor: Done intiailizing UART,
,08-31 17:08:18.347  6901  7192 I bt_vendor: Done intiailizing UART,
08-31 17:08:18.347  6901  7192 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 17:08:18.347  6901  7192 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 17:08:18.357  6901  7212 D bt_userial_mct: Entering userial_read_thread()
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 17:08:18.357  6901  7190 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 17:08:18.457  6901  7190 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 17:08:18.467  6901  7190 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f416e9 
,08-31 17:08:18.467  6901  7190 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f416e9 
,08-31 17:08:18.477  6901  7174 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 17:08:18.487  6901  7174 E bt-btif : Calling BTA_HhEnable
,08-31 17:08:18.487  6901  7174 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 17:08:18.487  6901  7174 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 17:08:18.487  6901  7174 E BluetoothServiceJni: populateRssiValuesNative
08-31 17:08:18.487  6901  7174 I bluedroid: getModelRssiValues
,08-31 17:08:18.487  6901  7174 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 17:08:18.487  6901  7174 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 17:08:18.487  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 17:08:18.487  6901  7174 D BluetoothAdapterProperties: Name is: A5-1
,08-31 17:08:18.497  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:18.497  6901  7174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 17:08:18.497  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:18.497  6901  7174 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:08:18.497  6901  7174 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:08:18.497  6901  7174 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-31 17:08:18.497  6901  7174 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 17:08:18.497  6901  7174 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 17:08:18.497  6901  7174 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 17:08:18.497  6901  7174 E bt-btif : btif_sock_init: !vhci_init
08-31 17:08:18.497  6901  7174 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 17:08:18.497  6901  7174 D IOP_DB_BT: db_open: db_open : handle 3023245328l, read 13894 bytes onto local cache
,08-31 17:08:18.497  6901  7174 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 17:08:18.507  6901  7174 D IOP_DB_BT: db_query: result 1
08-31 17:08:18.507  6901  7174 I         : iop_db_open: iop_db_open status 0
,08-31 17:08:18.507  6901  7174 D bte_conf: Device ID record 1 : primary
,08-31 17:08:18.507  6901  7174 D bte_conf:   vendorId            = 0075
08-31 17:08:18.507  6901  7174 D bte_conf:   vendorIdSource      = 0001
08-31 17:08:18.507  6901  7174 D bte_conf:   product             = 0100
08-31 17:08:18.507  6901  7174 D bte_conf:   version             = 0200
08-31 17:08:18.507  6901  7174 D bte_conf:   clientExecutableURL = 
08-31 17:08:18.507  6901  7174 D bte_conf:   serviceDescription  = 
08-31 17:08:18.507  6901  7174 D bte_conf:   documentationURL    = 
08-31 17:08:18.507  6901  7174 D bte_conf: bte_load_did_conf no section named DID2.
08-31 17:08:18.507  6901  7174 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 17:08:18.507  6901  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 17:08:18.507  6901  7171 D BluetoothAdapterProperties: ScanMode =  20
08-31 17:08:18.507  6901  7171 D BluetoothAdapterProperties: State =  11
,08-31 17:08:18.507  1017  1313 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 17:08:18.507  6901  7171 D BluetoothAdapterProperties: Setting state to 12
,08-31 17:08:18.507  6901  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 17:08:18.517  6901  7212 E bt_mct  : hci lib postload completed
,08-31 17:08:18.517  6901  7174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 17:08:18.517  6901  7174 D BluetoothAdapterProperties: Scan Mode:21
,08-31 17:08:18.517  6901  7174 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:18.517  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:18.517  1017  2736 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 17:08:18.517  1017  2736 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:18.517  1017  2736 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:18.517  1017  2736 D SettingsProvider: selectionArgs: false
,08-31 17:08:18.517  1017  2736 D SettingsProvider: selectionArgs: 1002
08-31 17:08:18.517  1017  2736 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:18.527  1017  2736 D SettingsProvider: ret = -1
,08-31 17:08:18.527  6901  7171 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 17:08:18.527  6901  7171 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 17:08:18.527  1017  2930 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:18.527  1017  2930 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.527  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.527  1017  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:18.527  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.537  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:18.537  6901  7171 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:18.537  6901  7171 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 17:08:18.537  6901  7171 D BluetoothAdapterService: starting service from this receiver
,08-31 17:08:18.537  1017  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:18.537  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.537  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.537  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.537  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.547  6901  7171 I BluetoothAdapterState: Entering On State from state = 11
,08-31 17:08:18.547  1292  5278 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:18.547  1292  5278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:18.547  6683  6693 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.547  6683  6693 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.547  1456  1913 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:18.547  1456  1913 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:18.547  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:18.557  1434  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.557  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:18.557  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:18.557  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.557  6901  6901 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 17:08:18.557  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.557  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.557  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.567  1434  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:18.567  6901  6910 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.567  6901  6910 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.567  1292  1301 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.567  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:18.567  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.567  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.567  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.567  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 17:08:18.567  1292  1301 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:18.567  2903  2924 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.567  2903  2924 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.567  1292  1300 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 17:08:18.567  6901  6901 I BluetoothPbapService: Handler(): got msg=1
,08-31 17:08:18.577  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 17:08:18.577  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.577  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.577  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.577  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.577  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 17:08:18.577  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:08:18.577  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 17:08:18.577  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 17:08:18.577  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 17:08:18.577  1017  1017 D BluetoothA2dp: Proxy object connected
08-31 17:08:18.577  6901  6916 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 17:08:18.577  6782  6790 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:18.577  6782  6790 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.577  1292  5278 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 17:08:18.577  1292  5278 D Bluetoothsap: Binding service...
,08-31 17:08:18.587  1292  1292 D HeadsetProfile: Bluetooth service connected
,08-31 17:08:18.587  6901  7215 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 17:08:18.587  1292  5278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 17:08:18.587  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 17:08:18.587  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.587  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.587  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.587  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.587  1292  5278 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 17:08:18.587  6901  7215 D BluetoothSocket: bindListen(): myUserId = 0
08-31 17:08:18.587  6901  7215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:18.587  1445  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.587  1445  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.587  1292  1292 D BluetoothPbap: Proxy object connected
08-31 17:08:18.587  1292  1292 D PbapServerProfile: Bluetooth service connected
08-31 17:08:18.587  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 17:08:18.587  1292  1292 D SapProfile: Bluetooth service connected
08-31 17:08:18.587  1292  1292 D Bluetoothsap: getConnectedDevices()
,08-31 17:08:18.587  1456  1688 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.597  6901  7215 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-31 17:08:18.597  6901  7215 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 17:08:18.597  6901  7215 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 17:08:18.597  6901  7215 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a13f55b
08-31 17:08:18.597  6901  7215 D BluetoothSocket: channel: 19
08-31 17:08:18.597  6901  7215 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 17:08:18.597  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:18.597  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.597  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.597  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.597  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.597  1456  1688 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 17:08:18.597  2903  2915 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 17:08:18.597  2903  2915 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.597  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 17:08:18.597  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.597  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.597  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.597  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.607  2903  2903 D BluetoothA2dp: Proxy object connected
,08-31 17:08:18.607  1933  4394 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:18.607  1933  4394 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:18.607  1292  1300 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 17:08:18.607  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 17:08:18.607  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.607  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.607  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:18.607  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.617  1292  1292 D BluetoothInputDevice: Proxy object connected
,08-31 17:08:18.617  1434  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.617  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:18.617  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.617  1292  1292 D HidProfile: Bluetooth service connected
08-31 17:08:18.617  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.617  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.617  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.617  1434  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:18.617  1292  1301 D BluetoothPan: Binding service...
,08-31 17:08:18.617  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 17:08:18.617  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.627  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.627  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.627  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.627  1292  5278 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 17:08:18.627  1292  1292 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 17:08:18.627  1292  1292 D PanProfile: Bluetooth service connected
,08-31 17:08:18.627  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 17:08:18.627  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.627  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.627  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.627  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.627  2903  2924 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.627  1292  1292 D BluetoothMap: Proxy object connected
08-31 17:08:18.627  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:18.627  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.637  1292  1292 D MapProfile: Bluetooth service connected
08-31 17:08:18.637  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.637  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.637  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.637  2903  2924 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 17:08:18.637  1292  1292 D BluetoothMap: getConnectedDevices()
,08-31 17:08:18.637  1177  3789 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.637  1177  3789 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:18.637  1017  1046 D BluetoothPan: Binding service...
08-31 17:08:18.637  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 17:08:18.637  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.637  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:18.637  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:18.637  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 17:08:18.637  1434  1442 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:18.637  1434  1442 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:18.637  1292  1301 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 17:08:18.637  1292  1301 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.637  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 17:08:18.637  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.637  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.637  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.637  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.647  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.647  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:18.647  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 17:08:18.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.647  1292  1292 D BluetoothA2dp: Proxy object connected
08-31 17:08:18.647  1292  1292 D A2dpProfile: Bluetooth service connected
,08-31 17:08:18.647  1434  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:18.647  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:18.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:18.647  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.647  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.647  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.647  1434  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:18.647  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 17:08:18.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 17:08:18.647  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:18.647  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 17:08:18.647  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 17:08:18.657  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 17:08:18.657  1434  1434 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2c1b5e86, true
,08-31 17:08:18.657  1434  1434 D BluetoothHeadset: registerMessageListener
,08-31 17:08:18.657  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 17:08:18.657  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:18.657  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-31 17:08:18.657  1771  1771 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:18.667  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:18.667  1017  1139 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:18.667  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:18.667  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 17:08:18.667  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:18.667  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:18.667  1017  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:18.667  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.667  6901  7065 D HeadsetService: registerMessageListener
08-31 17:08:18.667  6901  7065 D HeadsetService: registerMessageListener
,08-31 17:08:18.667  6901  7182 D HeadsetStateMachine: Disconnected process message: 70
,08-31 17:08:18.667  6901  7182 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ea361f8
08-31 17:08:18.667  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.667  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:18.667  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:18.677  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:18.677  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-31 17:08:18.677  6901  7220 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 17:08:18.677  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:18.677  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 17:08:18.677  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
08-31 17:08:18.677  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 17:08:18.677  1292  1292 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-31 17:08:18.677  1292  1292 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-31 17:08:18.677  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
08-31 17:08:18.677  1292  1292 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 17:08:18.677  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-31 17:08:18.677  1292  1292 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 17:08:18.687  6901  7182 D HeadsetStateMachine: Disconnected process message: 9
,08-31 17:08:18.687  6901  7182 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-31 17:08:18.687  6901  7220 D BluetoothSocket: bindListen(): myUserId = 0
08-31 17:08:18.687  6901  7220 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:18.687  6901  7220 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-31 17:08:18.687  6901  7220 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 17:08:18.687  6901  7220 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 17:08:18.687  6901  7220 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13a76d1
,08-31 17:08:18.687  6901  7220 D BluetoothSocket: channel: 5
,08-31 17:08:18.697   283   683 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 17:08:18.697   283   683 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 17:08:18.697   283   683 V voice   : voice_set_parameters: exit with code(-2)
08-31 17:08:18.697   283   683 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 17:08:18.697   283   683 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 17:08:18.697   283   683 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 17:08:18.697   283   683 V audio_hw_primary: adev_set_parameters: exit
08-31 17:08:18.697  6901  7182 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 17:08:18.697  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:08:18.697  1017  1315 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 17:08:18.697  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.697  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.697  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.697  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:18.707  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:18.707  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:18.717  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:18.717  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 17:08:18.727  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:18.727  6901  6901 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 17:08:18.727  1017  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:18.727  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.727  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.727  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:18.727  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:18.737  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:18.737  1017  1316 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 17:08:18.737  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:18.747  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.747  1017  1316 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:18.747  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:18.747  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:18.747  1933  7226 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 17:08:18.757  1017  1313 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:18.757  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 17:08:18.757  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:18.757  1017  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:18.757  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:18.777  6901  7230 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 17:08:18.777  6901  7230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:18.777  1017  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:18.777  6901  7230 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-31 17:08:18.777  6901  7230 D BluetoothSocket: bindListen(), new LocalSocket 
,08-31 17:08:18.777  6901  7230 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 17:08:18.787  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:18.787  6901  7230 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31eaf0d
08-31 17:08:18.787  6901  7230 D BluetoothSocket: channel: 12
08-31 17:08:18.787  6901  7230 I BtOppRfcommListener: Accept thread started.
,08-31 17:08:18.787  1017  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 17:08:18.787  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:18.797  1933  7226 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 17:08:20.067   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 17:08:20.067   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 17:08:20.607  6683  6736 D BluetoothAdapter: disable()
,08-31 17:08:20.607  1017  3237 D SettingsProvider: name = bluetooth_on
,08-31 17:08:20.607  6901  7171 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 17:08:20.607  6901  7171 D BluetoothAdapterProperties: Setting state to 13
08-31 17:08:20.607  6901  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 17:08:20.607  6901  7171 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:20.607  6901  7171 D BluetoothAdapterService: updateAdapterState state is 13
08-31 17:08:20.617  1017  2951 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:20.617  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 17:08:20.617  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:20.617  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:20.617  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:20.617  6901  7171 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:20.617  6901  7171 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-31 17:08:20.617  6901  7171 D BluetoothAdapterService: terminating service from this receiver
08-31 17:08:20.617  6901  6901 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 17:08:20.617  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:20.617  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-31 17:08:20.617  6901  6901 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e74aec2, channel: 19, state: LISTENING
,08-31 17:08:20.617  6901  6901 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e74aec2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a13f55b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30f9b4d3mSocket: android.net.LocalSocket@1d9c7810 impl:android.net.LocalSocketImpl@34942f09 fd:FileDescriptor[75]
,08-31 17:08:20.627  6901  6901 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d9c7810 impl:android.net.LocalSocketImpl@34942f09 fd:FileDescriptor[75]
,08-31 17:08:20.627  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 17:08:20.627  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 17:08:20.627  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:20.627  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-31 17:08:20.627  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:20.637  1771  1771 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:20.637  1017  3237 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:20.637  1017  3238 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 17:08:20.637  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 17:08:20.637  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:20.647  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 17:08:20.647  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:20.647  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:20.657  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:20.657  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 17:08:20.657  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:20.657  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:20.657  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:08:20.657  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:20.657  1017  2952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:20.657  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:20.667  1017  1139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 17:08:20.667  6901  6901 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3362f50e, channel: 5, state: LISTENING
08-31 17:08:20.667  6901  7171 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 17:08:20.667  6901  7171 D BluetoothAdapterProperties: mDiscovering is false
,08-31 17:08:20.667  6901  6901 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3362f50e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13a76d1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ea0cb2fmSocket: android.net.LocalSocket@1db9053c impl:android.net.LocalSocketImpl@fc7b2c5 fd:FileDescriptor[77]
08-31 17:08:20.667  6901  6901 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1db9053c impl:android.net.LocalSocketImpl@fc7b2c5 fd:FileDescriptor[77]
,08-31 17:08:20.667  6901  6901 I BtOppRfcommListener: stopping Accept Thread
08-31 17:08:20.667  6901  6901 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19dd541a, channel: 12, state: LISTENING
,08-31 17:08:20.667  6901  6901 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19dd541a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31eaf0d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18f8eb4bmSocket: android.net.LocalSocket@af3928 impl:android.net.LocalSocketImpl@af5b641 fd:FileDescriptor[81]
08-31 17:08:20.667  6901  6901 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@af3928 impl:android.net.LocalSocketImpl@af5b641 fd:FileDescriptor[81]
08-31 17:08:20.667  6901  7230 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:08:20.667  6901  7230 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 17:08:20.667  1017  2952 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 17:08:20.667  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:20.667  6901  7171 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 17:08:20.667  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:20.667  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:20.677  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:20.677  1017  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:20.677  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:20.677  6683  6683 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 17:08:20.677  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:20.677  1017  1313 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 17:08:20.677  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:20.677  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:20.687  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:20.687  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:20.697  1292  1292 D BluetoothPbap: Proxy object disconnected
08-31 17:08:20.697  1292  1292 D PbapServerProfile: Bluetooth service disconnected
,08-31 17:08:20.697  6901  7174 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 17:08:20.697  6901  7174 D BluetoothAdapterProperties: Scan Mode:20
,08-31 17:08:20.697  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:20.697  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:20.707  6901  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 17:08:20.707  6901  7171 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 17:08:20.707  6901  7171 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-31 17:08:20.707  6901  7171 E bt-btif : cmd socket is not created
,08-31 17:08:20.707  6901  7171 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 17:08:20.707  6901  7190 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-31 17:08:20.707  6901  7190 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 17:08:20.707  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:20.707  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:08:20.707  6901  7190 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 17:08:20.717  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:20.727  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:20.727  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:20.727  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 17:08:20.737  6901  6901 V BluetoothOppManager: cleanUp...
,08-31 17:08:20.767  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:20.777  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 17:08:20.917  6901  7190 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:08:20.917  6901  7190 W bt-btif : ag scb idx 1 not allocated
,08-31 17:08:20.917  6901  7190 W bt-btif : ag scb idx 2 not allocated,
08-31 17:08:20.917  6901  7190 E bt-btif : BTA AG is already disabled, ignoring ...
,08-31 17:08:20.917  6901  7212 I bt_userial_mct: exiting userial_read_thread
08-31 17:08:20.917  6901  7212 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 17:08:20.917  6901  7174 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 17:08:20.917  6901  7192 I bt_vendor: hw_epilog_process
08-31 17:08:20.917  6901  7174 D bt_userial_mct: userial_close
,08-31 17:08:20.917  6901  7174 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 17:08:21.097   288   288 E SMD     : DCD OFF
,08-31 17:08:21.347  6901  7174 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 17:08:21.347  6901  7174 I bt_vendor: bluetooth satus is on
08-31 17:08:21.347  6901  7174 I bt_vendor: bt-vendor : resetting BT status
08-31 17:08:21.347  6901  7174 I bt_vendor: Starting hciattach daemon
08-31 17:08:21.347  6901  7174 I bt_vendor: try to set false
08-31 17:08:21.347  6901  7174 I bt_vendor: Starting hciattach daemon
,08-31 17:08:21.347  6901  7174 I bt_vendor: try to set false
08-31 17:08:21.347  6901  7174 I bt_vendor: cleanup
,08-31 17:08:21.347  6901  7190 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
08-31 17:08:21.347  6901  7174 I GKI_LINUX: GKI_exit_task 0 done
08-31 17:08:21.347  6901  7174 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
,08-31 17:08:21.347  6901  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-31 17:08:21.347  6901  7171 D BtConfig.SecureMode: isSecureModeOn:false
08-31 17:08:21.347  6901  7171 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-31 17:08:21.347  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 17:08:21.347  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 17:08:21.347  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 17:08:21.357  1017  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:21.357  1017  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.357  1017  1492 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 17:08:21.357  1017  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:21.357  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 17:08:21.357  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 17:08:21.357  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
08-31 17:08:21.357  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 17:08:21.357  1017  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 17:08:21.357  6901  6901 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:08:21.357  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.357  6901  6901 D BtGatt.GattService: Received stop request...Stopping profile...,
08-31 17:08:21.357  6901  6901 D BtGatt.GattService: stop()
08-31 17:08:21.357  6901  6901 D BtGatt.AdvertiseManager: advertise clients cleared,
,08-31 17:08:21.367  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:21.367  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.367  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.367  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-31 17:08:21.367  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:21.367  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 17:08:21.367  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
,08-31 17:08:21.367  6901  6901 D HeadsetService: Received stop request...Stopping profile...
,08-31 17:08:21.377  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.377  1017  2930 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:21.377  1017  2930 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.377  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.377  1017  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.377  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.377  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 17:08:21.377  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:21.377  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 17:08:21.377  1017  2736 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:21.377  1017  2736 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.377  1017  2736 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.377  1017  2736 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.377  1017  2736 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.387  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 17:08:21.387  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:21.387  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 17:08:21.387  1017  3237 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:21.387  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.387  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 17:08:21.387  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.387  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:21.387  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.387  1292  1292 D HeadsetProfile: Bluetooth service disconnected
,08-31 17:08:21.387  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 17:08:21.387  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 17:08:21.387  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 17:08:21.387  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:21.387  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.387  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:21.387  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.387  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.397  1017  1687 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.397  1017  1687 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.397  1017  1687 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.397  1017  1687 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.397  1017  1687 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 17:08:21.397  1017  3238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:21.397  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.397  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:21.397  1017  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:21.397  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 17:08:21.397  6901  7171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 17:08:21.397  6901  7171 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 17:08:21.397  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-31 17:08:21.397  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 17:08:21.397  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:21.397  6901  6901 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 17:08:21.397  6901  7171 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-31 17:08:21.407  6901  6901 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 17:08:21.407  6901  6901 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 17:08:21.407  6901  6901 D A2dpService: Received stop request...Stopping profile...
,08-31 17:08:21.407  6901  7184 D A2dpStateMachine: Exit Disconnected: -1,
,08-31 17:08:21.407  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.407  1017  1017 D BluetoothA2dp: Proxy object disconnected,
08-31 17:08:21.407  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 17:08:21.407  6901  6901 D HidService: Received stop request...Stopping profile...
08-31 17:08:21.407  6901  6901 D HidService: Stopping Bluetooth HidService
08-31 17:08:21.407  6901  6901 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:08:21.407  2903  2903 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:21.417  6901  6901 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 17:08:21.417  6901  6901 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 17:08:21.417  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:21.417  1292  1292 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:21.417  1292  1292 D A2dpProfile: Bluetooth service disconnected
,08-31 17:08:21.417  6901  6901 D HealthService: Received stop request...Stopping profile...
08-31 17:08:21.417  1292  1292 D BluetoothInputDevice: Proxy object disconnected
08-31 17:08:21.417  1292  1292 D HidProfile: Bluetooth service disconnected
08-31 17:08:21.417  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.417  6901  6901 D PanService: Received stop request...Stopping profile...
,08-31 17:08:21.417  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.417  6901  6901 D BluetoothMapService: Received stop request...Stopping profile...
08-31 17:08:21.417  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:08:21.417  1292  1292 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:08:21.417  1292  1292 D PanProfile: Bluetooth service disconnected
,08-31 17:08:21.417  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.427  6901  6901 D SapService: Received stop request...Stopping profile...
08-31 17:08:21.427  6901  6901 D SapService: Stopping Bluetooth SapService
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:21.427  1292  1292 D BluetoothMap: Proxy object disconnected
,08-31 17:08:21.427  1292  1292 D MapProfile: Bluetooth service disconnected
08-31 17:08:21.427  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 17:08:21.427  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 17:08:21.427  6901  6901 D BluetoothA2dp: Proxy object disconnected
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 17:08:21.427  6901  7185 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 17:08:21.427  6901  6901 I GKI_LINUX: GKI_exit_task 2 done
08-31 17:08:21.427  6901  6901 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 17:08:21.427  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 17:08:21.427  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-31 17:08:21.427  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 17:08:21.427  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 17:08:21.427  6901  6901 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:08:21.427  1292  1292 D SapProfile: Bluetooth service disconnected
08-31 17:08:21.427  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 17:08:21.427  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:21.427  6901  6901 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:08:21.427  6901  6901 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 17:08:21.427  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-31 17:08:21.427  6901  6901 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 17:08:21.427  6901  6901 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 17:08:21.437  6901  6901 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-31 17:08:21.437  6901  7171 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-31 17:08:21.437  6901  7171 D BluetoothAdapterProperties: Setting state to 10
08-31 17:08:21.437  6901  6901 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 17:08:21.437  6901  7171 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 17:08:21.437  6901  6901 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 17:08:21.437  6901  7171 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:21.437  6901  7171 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 17:08:21.437  1292  5278 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:21.437  6901  7171 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:21.437  6901  7171 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 17:08:21.437  6901  7171 I BluetoothAdapterState: Entering OffState
08-31 17:08:21.437  1292  5278 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.437  6683  6691 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.437  6683  6691 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.437  6683  6691 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 17:08:21.437  6683  6691 D BluetoothLeAdvertiser: Exit stop advertising
08-31 17:08:21.437  6683  6691 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-31 17:08:21.437  6683  6691 D BluetoothLeScanner: Exiting stopAllScan
,08-31 17:08:21.447  1456  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.447  1456  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.447  6901  7065 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.447  6901  7065 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.447  2903  7070 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.447  2903  7070 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.447  1292  1300 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 17:08:21.447  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:21.447  6901  6916 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:21.447  6782  6791 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.447  6782  6791 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.447  1292  7216 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 17:08:21.447  1292  7216 D Bluetoothsap: Unbinding service...
,08-31 17:08:21.447  1445  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.447  1445  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.457  2903  2924 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1933  2120 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1933  2120 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.457  1292  5278 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1292  1300 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1177  3790 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1177  3790 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.457  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 17:08:21.457  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.457  1434  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 17:08:21.457  1434  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 17:08:21.457  1292  7216 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 17:08:21.467  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-31 17:08:21.467  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 17:08:21.467  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:21.477  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,08-31 17:08:21.477  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 17:08:21.477  6901  7174 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 17:08:21.477  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:21.477  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 17:08:21.477  1177  1699 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:21.477  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:21.477  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-31 17:08:21.477  1177  1699 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:21.477  6901  6901 I GKI_LINUX: GKI_exit_task 1 done,
08-31 17:08:21.477  6901  6901 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 17:08:21.477  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:21.477  1177  1177 D BluetoothAdapter: 18323561: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:21.477  6901  6901 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 17:08:21.477  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:21.477  1017  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 17:08:21.477  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 17:08:21.487  1771  1771 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:21.487  1933  2125 D BluetoothAdapter: 920390409: getState() :  mService = null. Returning STATE_OFF
08-31 17:08:21.487  1933  2125 D BluetoothAdapter: 920390409: getState() :  mService = null. Returning STATE_OFF
,08-31 17:08:21.487  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:21.487  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:21.487  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:21.487  6901  6901 I art     : System.exit called, status: 0
08-31 17:08:21.487  6901  6901 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 17:08:21.487  1017  1313 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 17:08:21.487  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.497  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.497  1017  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:21.497  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:21.497  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 17:08:21.497  1017  1315 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 17:08:21.497  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.497  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:21.497  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:21.507  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:21.517  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:21.517  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:21.527  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:21.527  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 17:08:21.547  1017  1218 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 17:08:21.547  1017  1218 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 17:08:21.557  1017  1218 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-31 17:08:21.557  1017  1218 W BroadcastQueue: android.os.TransactionTooLargeException
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-31 17:08:21.557  1017  1218 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 17:08:21.557  1017  1218 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 17:08:21.557  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:21.557  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:21.557  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:21.557  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:21.577  7245  7245 E Zygote  : MountEmulatedStorage()
08-31 17:08:21.577  7245  7245 I libpersona: KNOX_SDCARD checking this for 1002
08-31 17:08:21.577  7245  7245 E Zygote  : v2
08-31 17:08:21.577  7245  7245 I libpersona: KNOX_SDCARD not a persona
08-31 17:08:21.577  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 17:08:21.577  1017  1218 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7245 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-31 17:08:21.577  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:21.577  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:21.607  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 17:08:21.607  7245  7245 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:21.617  7245  7245 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 17:08:21.617  7245  7245 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 17:08:21.647  7245  7245 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding GattService
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding HidService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding HealthService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding PanService
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding SapService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 17:08:21.677  7245  7245 D BtSettings.ProfileConfig: Adding HidDevService
08-31 17:08:21.677  7245  7245 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 17:08:21.677  1017  1687 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 17:08:21.677  1017  1687 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.677  1017  1687 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 17:08:21.677  1017  1687 D SettingsProvider: selectionArgs: false
08-31 17:08:21.677  1017  1687 D SettingsProvider: selectionArgs: 1002
,08-31 17:08:21.677  1017  1687 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.677  1017  1687 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 17:08:21.687  1017  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1492 D SettingsProvider: selectionArgs: false
08-31 17:08:21.687  1017  1492 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.687  1017  1492 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1315 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 17:08:21.687  1017  1315 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1315 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1315 D SettingsProvider: selectionArgs: false
08-31 17:08:21.687  1017  1315 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  1315 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.687  1017  1315 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 17:08:21.687  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1029 D SettingsProvider: selectionArgs: false
08-31 17:08:21.687  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.687  1017  1029 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  3237 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 17:08:21.687  1017  3237 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:21.687  1017  3237 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  3237 D SettingsProvider: selectionArgs: false
08-31 17:08:21.687  1017  3237 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  3237 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.687  1017  3237 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-31 17:08:21.687  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1030 D SettingsProvider: selectionArgs: false
,08-31 17:08:21.687  1017  1030 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:21.687  1017  1030 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1316 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:21.687  1017  1316 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1316 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1316 D SettingsProvider: selectionArgs: false
,08-31 17:08:21.687  1017  1316 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.687  1017  1316 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:21.687  1017  1316 D SettingsProvider: ret = -1
,08-31 17:08:21.687  1017  1313 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-31 17:08:21.687  1017  1313 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.687  1017  1313 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.687  1017  1313 D SettingsProvider: selectionArgs: false
08-31 17:08:21.687  1017  1313 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.697  1017  1313 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:21.697  1017  1313 D SettingsProvider: ret = -1
,08-31 17:08:21.697  1017  2736 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:21.697  1017  2736 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:21.697  1017  2736 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 17:08:21.697  1017  2736 D SettingsProvider: selectionArgs: false
,08-31 17:08:21.697  1017  2736 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.697  1017  2736 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.697  1017  2736 D SettingsProvider: ret = -1
08-31 17:08:21.697  1017  2951 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:21.697  1017  2951 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 17:08:21.697  1017  2951 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.697  1017  2951 D SettingsProvider: selectionArgs: false
08-31 17:08:21.697  1017  2951 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.697  1017  2951 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.697  1017  2951 D SettingsProvider: ret = -1
,08-31 17:08:21.697  1017  2930 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 17:08:21.697  1017  2930 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.697  1017  2930 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.697  1017  2930 D SettingsProvider: selectionArgs: false
08-31 17:08:21.697  1017  2930 D SettingsProvider: selectionArgs: 1002
,08-31 17:08:21.697  1017  2930 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.697  1017  2930 D SettingsProvider: ret = -1,
08-31 17:08:21.697  1017  3236 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 17:08:21.697  1017  3236 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:21.697  1017  3236 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:21.697  1017  3236 D SettingsProvider: selectionArgs: false
08-31 17:08:21.697  1017  3236 D SettingsProvider: selectionArgs: 1002
08-31 17:08:21.697  1017  3236 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 17:08:21.697  1017  3236 D SettingsProvider: ret = -1
,08-31 17:08:21.707  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:21.707  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 17:08:21.707  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:21.707  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.707  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:21.707  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:21.727  1933  7261 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 17:08:21.867  1017  1316 I art     : Explicit concurrent mark sweep GC freed 69820(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.427ms total 157.311ms
,08-31 17:08:21.877  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:21.877  1017  2930 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:21.877  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:21.877  1017  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:21.877  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:21.887  1933  7261 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 17:08:21.897  1017  1095 V AlarmManager: waitForAlarm result :4
,08-31 17:08:21.907  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-31 17:08:21.907  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
08-31 17:08:21.907  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
08-31 17:08:21.907  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 17:08:21.907  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-31 17:08:21.917  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 17:08:21.927  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 17:08:21.927  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 17:08:21.927  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-31 17:08:21.927  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 17:08:21.947  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 17:08:21.967  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 17:08:21.967  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 17:08:21.987  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 17:08:22.997  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 17:08:22.997  1017  1030 D BatteryService: level:54, scale:100, status:2, health:2, present:true, voltage: 3860, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-31 17:08:22.997  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 17:08:22.997  1017  1030 D BatteryService: stay LED for charging
08-31 17:08:23.007  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 17:08:22.997  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 17:08:23.007  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 17:08:23.007  1017  1017 I MotionRecognitionService: Plugged
08-31 17:08:23.007  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 17:08:23.007  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-31 17:08:23.007  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 54
,08-31 17:08:23.037  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:23.037  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:23.037  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:54 status:2 health:2
,08-31 17:08:23.357  1017  2796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 17:08:23.617  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:08:23.617  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:24.097   288   288 E SMD     : DCD OFF,
,08-31 17:08:24.797  1017  1049 I PowerManagerService: [PWL] Off : 140s ago,
08-31 17:08:24.797  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-31 17:08:24.797  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-31 17:08:24.797  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=15986)
,08-31 17:08:25.937  1017  2758 D SSRM:n  : SIOP:: AP = 330
,08-31 17:08:26.617  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:08:26.617  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fd92ae0 added. We now have 6 listener(s)
,08-31 17:08:26.617  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:08:26.617  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:08:26.617  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c7b199 added. We now have 7 listener(s)
,08-31 17:08:26.617  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:08:26.617  6683  6736 I System.out: IsBluetoothEnabled
,08-31 17:08:26.627  6683  6736 D BluetoothAdapter: disable()
,08-31 17:08:26.627  1017  1315 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-31 17:08:26.627  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:26.627  6683  6736 D BluetoothAdapter: enable()
,08-31 17:08:26.637  1017  2952 W ActivityManager: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 17:08:26.637  1017  2952 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-31 17:08:26.637  1017  2952 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 17:08:26.637  1017  2952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 17:08:26.637  1017  2952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-31 17:08:26.637  1017  2952 D SettingsProvider: name = bluetooth_on
,08-31 17:08:26.647  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 17:08:26.647  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 17:08:26.647  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-31 17:08:26.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 17:08:26.667  7245  7245 D BluetoothAdapterState: make
,08-31 17:08:26.667  7245  7245 I bluedroid: init,
,08-31 17:08:26.677  7245  7269 I BluetoothAdapterState: Entering OffState
,08-31 17:08:26.677  7245  7245 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 17:08:26.677  7245  7245 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 17:08:26.677  7245  7245 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 17:08:26.677  7245  7245 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 17:08:26.677  7245  7245 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-31 17:08:26.677  7245  7245 I bluedroid: get_profile_interface socket
,08-31 17:08:26.677  7245  7245 I bluedroid: get_profile_interface map_client
08-31 17:08:26.677  7245  7272 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 17:08:26.677  7245  7245 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 17:08:26.687  7245  7272 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 17:08:26.687  7245  7245 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:26.687  7245  7272 E BluetoothServiceJni: populateRssiValuesNative
08-31 17:08:26.687  7245  7272 I bluedroid: getModelRssiValues
08-31 17:08:26.687  7245  7272 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 17:08:26.687  7245  7272 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 17:08:26.687  1017  3238 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 17:08:26.687  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.687  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.687  1017  3238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.687  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.697  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 17:08:26.697  7245  7257 I bluedroid: config_hci_snoop_log
,08-31 17:08:26.697  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-31 17:08:26.697  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-31 17:08:26.697  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 17:08:26.697  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 17:08:26.697  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-31 17:08:26.707  7245  7272 D BluetoothAdapterProperties: Name is: A5-1
,08-31 17:08:26.707  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 17:08:26.707  7245  7245 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 17:08:26.707  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 17:08:26.717  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 17:08:26.717  7245  7269 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 17:08:26.717  7245  7269 D BluetoothAdapterProperties: Setting state to 11
,08-31 17:08:26.717  7245  7269 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 17:08:26.727  7245  7269 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-31 17:08:26.727  7245  7269 D BluetoothAdapterService: updateAdapterState state is 11
08-31 17:08:26.727  7245  7269 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:26.727  7245  7269 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 17:08:26.727  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:26.727  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 17:08:26.727  7245  7269 D BluetoothSecureManager: getInstant: null
08-31 17:08:26.727  7245  7269 D BluetoothSecureManager: calling getMethod for getService
08-31 17:08:26.727  7245  7269 D BluetoothSecureManager: calling getService
,08-31 17:08:26.727  7245  7269 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@7fc0567
,08-31 17:08:26.727  1017  1313 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 17:08:26.727  1017  1313 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 17:08:26.727  7245  7269 D BtConfig.SecureMode: isSecureModeOn:false
08-31 17:08:26.727  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 17:08:26.727  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 17:08:26.727  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 17:08:26.737  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 17:08:26.737  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 17:08:26.737  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 17:08:26.737  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 17:08:26.737  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 17:08:26.737  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:26.737  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-31 17:08:26.737  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 17:08:26.737  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:26.737  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 17:08:26.737  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 17:08:26.737  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 17:08:26.737  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:26.747  1771  1771 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 17:08:26.747  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:26.747  1017  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 17:08:26.747  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 17:08:26.747  1017  2951 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 17:08:26.747  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 17:08:26.747  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:26.747  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 17:08:26.747  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:26.747  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 17:08:26.747  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 17:08:26.747  7245  7269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 17:08:26.747  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:26.747  7245  7269 D BluetoothBondStateMachine: make
,08-31 17:08:26.757  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:26.757  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 17:08:26.757  1017  2930 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:26.757  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 17:08:26.757  1017  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-31 17:08:26.757  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 17:08:26.757  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 17:08:26.757  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.757  1017  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:26.757  7245  7273 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 17:08:26.757  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:26.767  1017  2951 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:26.767  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.767  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.767  1017  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.767  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.767  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 17:08:26.767  7245  7245 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:08:26.767  7245  7245 D BtGatt.GattService: Received start request. Starting profile...
08-31 17:08:26.777  7245  7245 D BtGatt.GattService: start()
08-31 17:08:26.777  7245  7245 D BtGatt.GattService: start()
08-31 17:08:26.777  7245  7245 I bluedroid: get_profile_interface gatt
,08-31 17:08:26.777  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:26.777  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 17:08:26.777  7245  7245 D BtGatt.AdvertiseManager: advertise manager created
08-31 17:08:26.777  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 17:08:26.777  1017  1313 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:26.777  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.777  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.777  1017  1313 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.777  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.777  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:26.777  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 17:08:26.777  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 17:08:26.777  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 17:08:26.777  1017  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:26.777  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.777  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.777  1017  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.777  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.787  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 17:08:26.787  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 17:08:26.787  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 17:08:26.787  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:26.787  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 17:08:26.787  1017  1687 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:26.787  1017  1687 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.797  1017  1687 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.797  1017  1687 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.797  1017  1687 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.797  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 17:08:26.797  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 17:08:26.797  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 17:08:26.797  7245  7245 D BtGatt.GattService: mStartError = false
08-31 17:08:26.797  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:26.807  7245  7245 D HeadsetService: Received start request. Starting profile...
,08-31 17:08:26.807  7245  7245 D HeadsetService: start()
,08-31 17:08:26.807  7245  7245 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 17:08:26.807  7245  7245 D HeadsetStateMachine: make
,08-31 17:08:26.807  1017  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:26.807  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.807  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.807  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.807  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.807  7245  7245 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 17:08:26.817  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 17:08:26.817  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 17:08:26.817  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 17:08:26.817  1017  3236 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:26.817  1017  3236 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.817  1017  3236 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:26.817  1017  3236 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.817  1017  3236 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.827  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 17:08:26.827  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 17:08:26.827  7245  7269 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 17:08:26.827  1017  2930 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 17:08:26.827  1017  2930 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.827  1017  2930 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.827  1017  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.827  1017  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.827  1017  1315 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 17:08:26.827  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.827  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 17:08:26.827  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 17:08:26.827  7245  7269 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 17:08:26.827  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.827  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:26.827  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 17:08:26.827  1017  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:26.827  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.827  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.827  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.827  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:26.837  1017  3237 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 17:08:26.837  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 17:08:26.837  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:26.837  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:26.837  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 17:08:26.837  7245  7245 I bluedroid: get_profile_interface handsfree
,08-31 17:08:26.837  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:26.837  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 17:08:26.837  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 17:08:26.837  7245  7269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 17:08:26.837  7245  7269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 17:08:26.837  7245  7269 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 17:08:26.857  7245  7245 I DualScoManager: Instantiating Dual Sco Manager
,08-31 17:08:26.857  7245  7245 I DualScoManager: Set HeadsetServiceHelper
,08-31 17:08:26.857  7245  7245 D BluetoothAtMessage: createCMTIContentObservers
,08-31 17:08:26.857  1017  3238 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 17:08:26.857  1017  3238 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:26.857  1017  3238 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:26.857  1017  3238 D SettingsProvider: selectionArgs: false
,08-31 17:08:26.857  1017  3238 D SettingsProvider: selectionArgs: 1002
08-31 17:08:26.857  1017  3238 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:26.857  1017  3238 D SettingsProvider: ret = -1
,08-31 17:08:26.857  7245  7245 D HeadsetService: mStartError = false
08-31 17:08:26.857  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:26.857  7245  7277 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 17:08:26.867  7245  7245 D A2dpService: Received start request. Starting profile...
,08-31 17:08:26.867  7245  7245 D A2dpService: start()
,08-31 17:08:26.867  7245  7277 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 17:08:26.867  7245  7245 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 17:08:26.867  7245  7277 D HeadsetStateMachine: map size, before remove : 0
,08-31 17:08:26.867  7245  7277 D HeadsetStateMachine: map size, after remove: 0
08-31 17:08:26.867  7245  7245 I bluedroid: get_profile_interface avrcp
,08-31 17:08:26.877  7245  7245 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,08-31 17:08:26.887  7245  7245 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 17:08:26.887  7245  7245 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:08:26.897  7245  7245 D A2dpStateMachine: make
,08-31 17:08:26.897  7245  7282 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 17:08:26.897  7245  7245 I bluedroid: get_profile_interface a2dp
,08-31 17:08:26.897  7245  7284 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 17:08:26.897  7245  7245 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 17:08:26.897  7245  7245 D A2dpService: mStartError = false
08-31 17:08:26.897  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:26.897  7245  7283 D A2dpStateMachine: Enter Disconnected: -2
08-31 17:08:26.907  7245  7245 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 17:08:26.907  7245  7282 D BluetoothMediaBrowser: no now playing list
,08-31 17:08:26.907  7245  7282 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 17:08:26.907  7245  7245 D HidService: Received start request. Starting profile...
08-31 17:08:26.907  7245  7245 D HidService: start()
08-31 17:08:26.907  7245  7245 I bluedroid: get_profile_interface hidhost
08-31 17:08:26.907  7245  7245 D HidService: setHidService(): set to: null
08-31 17:08:26.907  7245  7245 D HidService: mStartError = false
08-31 17:08:26.907  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:26.907  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 17:08:26.907  7245  7245 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 17:08:26.907  7245  7245 D HealthService: Received start request. Starting profile...
08-31 17:08:26.907  7245  7245 D HealthService: start()
,08-31 17:08:26.907  7245  7245 I bluedroid: get_profile_interface health
08-31 17:08:26.907  7245  7245 D HealthService: mStartError = false
08-31 17:08:26.907  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:26.907  7245  7245 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 17:08:26.907  7245  7245 D PanService: Received start request. Starting profile...
08-31 17:08:26.907  7245  7245 D PanService: start()
08-31 17:08:26.907  7245  7245 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 17:08:26.907  7245  7245 I bluedroid: get_profile_interface pan
,08-31 17:08:26.907  7245  7245 D PanService: mStartError = false
,08-31 17:08:26.907  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:26.917  7245  7245 D BluetoothMapService: Received start request. Starting profile...
08-31 17:08:26.917  7245  7245 D BluetoothMapService: start()
,08-31 17:08:26.917  7245  7245 D BluetoothMapService: mStartError = false
,08-31 17:08:26.917  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:26.917  7245  7245 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 17:08:26.917  1434  7218 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 17:08:26.917  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 17:08:26.917  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 17:08:26.917  1434  7218 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 17:08:26.917  7245  7245 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 17:08:26.927  7245  7245 D SapService: Received start request. Starting profile...,
08-31 17:08:26.927  7245  7245 D SapService: start()
08-31 17:08:26.927  7245  7245 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 17:08:26.927  7245  7245 I bluedroid: get_profile_interface sap
08-31 17:08:26.927  7245  7245 D SapService: mStartError = false
,08-31 17:08:26.927  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:26.927  7245  7245 D HeadsetStateMachine: Proxy object connected
08-31 17:08:26.927  7245  7245 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 17:08:26.927  7245  7277 D HeadsetStateMachine: Disconnected process message: 11
08-31 17:08:26.927  7245  7245 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 17:08:26.927  7245  7245 D HeadsetPhoneState: Signal level : previous=0 curr=0,
08-31 17:08:26.927  7245  7245 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 17:08:26.927  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 17:08:26.927  7245  7245 D BluetoothA2dp: Proxy object connected
08-31 17:08:26.927  7245  7245 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 17:08:26.927  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-31 17:08:26.927  7245  7277 D HeadsetStateMachine: Disconnected process message: 18
08-31 17:08:26.927  7245  7277 D HeadsetStateMachine: Disconnected process message: 10
08-31 17:08:26.927  7245  7277 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,08-31 17:08:26.927  7245  7277 D HeadsetStateMachine: Disconnected process message: 11
,08-31 17:08:26.937  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 17:08:26.937  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 17:08:26.937  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 17:08:26.937  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:26.957  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:26.957  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 17:08:26.957  7245  7245 E BluetoothAdapterService(481512014): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 17:08:26.967  7245  7269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 17:08:26.967  7245  7269 I bluedroid: enable
08-31 17:08:26.967  7245  7269 I bt_hci_bdroid: init
,08-31 17:08:26.967  7245  7288 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 17:08:26.967  7245  7269 I bt_vendor: bt-vendor : init
,08-31 17:08:26.967  7245  7269 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 17:08:26.967  7245  7269 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 17:08:26.967  7245  7269 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,08-31 17:08:26.967  7245  7269 D bt_userial_mct: userial_init
,08-31 17:08:26.967  7245  7269 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 17:08:26.967  7245  7269 I bt_vendor: Starting hciattach daemon
08-31 17:08:26.967  7245  7269 I bt_vendor: try to set false
,08-31 17:08:26.967  7245  7269 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 17:08:26.967  7245  7269 I bt_vendor: Starting hciattach daemon
08-31 17:08:26.967  7245  7269 I bt_vendor: try to set true
,08-31 17:08:26.987  7292  7292 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-31 17:08:27.027  7298  7298 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 17:08:27.037  7299  7299 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 17:08:27.057  7301  7301 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 17:08:27.067  7302  7302 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 17:08:27.067  7303  7303 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 17:08:27.077  7304  7304 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 17:08:27.097   288   288 E SMD     : DCD OFF,
,08-31 17:08:27.337  7307  7307 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-31 17:08:27.347  7308  7308 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 17:08:27.377  7245  7269 I bt_vendor: bluetooth satus is on,
08-31 17:08:27.377  7245  7290 D bt_userial_mct: userial_open(port:0)
08-31 17:08:27.377  7245  7290 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 17:08:27.377  7245  7290 I bt_vendor: Done intiailizing UART,
,08-31 17:08:27.377  7245  7290 I bt_vendor: Done intiailizing UART
08-31 17:08:27.377  7245  7290 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 17:08:27.377  7245  7290 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 17:08:27.387  7245  7312 D bt_userial_mct: Entering userial_read_thread()
,08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_HCI,
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_SDP,
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 17:08:27.387  7245  7288 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 17:08:27.477  7245  7288 W bt-l2cap: l2c_link_processs_ble_num_bufs 16,
,08-31 17:08:27.487  7245  7288 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fff6e9 
,08-31 17:08:27.487  7245  7288 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fff6e9 
,08-31 17:08:27.507  7245  7272 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 17:08:27.507  7245  7272 E bt-btif : Calling BTA_HhEnable
,08-31 17:08:27.507  7245  7272 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 17:08:27.507  7245  7272 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 17:08:27.507  7245  7272 E BluetoothServiceJni: populateRssiValuesNative
08-31 17:08:27.507  7245  7272 I bluedroid: getModelRssiValues
,08-31 17:08:27.507  7245  7272 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 17:08:27.507  7245  7272 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 17:08:27.517  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 17:08:27.517  7245  7272 D BluetoothAdapterProperties: Name is: A5-1
,08-31 17:08:27.517  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:27.527  7245  7272 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 17:08:27.527  7245  7272 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:08:27.527  7245  7272 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 17:08:27.527  7245  7272 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-31 17:08:27.527  7245  7272 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 17:08:27.527  7245  7272 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-31 17:08:27.527  7245  7272 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 17:08:27.527  7245  7272 E bt-btif : btif_sock_init: !vhci_init
08-31 17:08:27.527  7245  7272 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 17:08:27.527  7245  7272 D IOP_DB_BT: db_open: db_open : handle 3025625104l, read 13894 bytes onto local cache
08-31 17:08:27.527  7245  7272 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 17:08:27.527  7245  7272 D IOP_DB_BT: db_query: result 1
08-31 17:08:27.527  7245  7272 I         : iop_db_open: iop_db_open status 0
08-31 17:08:27.527  7245  7272 D bte_conf: Device ID record 1 : primary
08-31 17:08:27.527  7245  7272 D bte_conf:   vendorId            = 0075
08-31 17:08:27.527  7245  7272 D bte_conf:   vendorIdSource      = 0001
08-31 17:08:27.527  7245  7272 D bte_conf:   product             = 0100
08-31 17:08:27.527  7245  7272 D bte_conf:   version             = 0200
08-31 17:08:27.527  7245  7272 D bte_conf:   clientExecutableURL = 
08-31 17:08:27.527  7245  7272 D bte_conf:   serviceDescription  = 
08-31 17:08:27.527  7245  7272 D bte_conf:   documentationURL    = 
08-31 17:08:27.527  7245  7272 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 17:08:27.527  7245  7269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 17:08:27.527  7245  7269 D BluetoothAdapterProperties: ScanMode =  20
08-31 17:08:27.527  7245  7269 D BluetoothAdapterProperties: State =  11
,08-31 17:08:27.527  7245  7272 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 17:08:27.527  1017  2930 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 17:08:27.527  7245  7312 E bt_mct  : hci lib postload completed
,08-31 17:08:27.537  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:27.537  7245  7272 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 17:08:27.537  7245  7272 D BluetoothAdapterProperties: Scan Mode:21
08-31 17:08:27.537  7245  7272 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 17:08:27.537  7245  7269 D BluetoothAdapterProperties: Setting state to 12
08-31 17:08:27.537  7245  7269 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 17:08:27.537  1017  1492 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 17:08:27.537  1017  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 17:08:27.537  1017  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 17:08:27.537  1017  1492 D SettingsProvider: selectionArgs: false
08-31 17:08:27.537  1017  1492 D SettingsProvider: selectionArgs: 1002
,08-31 17:08:27.537  1017  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 17:08:27.547  1017  1492 D SettingsProvider: ret = -1
,08-31 17:08:27.547  7245  7269 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 17:08:27.547  7245  7269 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 17:08:27.547  1017  3237 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:27.547  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.547  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.547  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:27.547  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.567  7245  7269 D BluetoothAdapterService: Autoconnection is available 
,08-31 17:08:27.567  7245  7269 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 17:08:27.567  7245  7269 D BluetoothAdapterService: starting service from this receiver
,08-31 17:08:27.567  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:27.567  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.567  1292  1300 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:27.567  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.567  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.567  1292  1300 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.567  6683  7067 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.567  6683  7067 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:27.567  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.577  1456  1764 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:27.577  1456  1764 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.577  7245  7253 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 17:08:27.577  7245  7269 I BluetoothAdapterState: Entering On State from state = 11
,08-31 17:08:27.577  1434  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.577  7245  7245 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 17:08:27.577  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:27.577  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:27.577  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.587  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.587  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.587  1434  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.587  1292  7216 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.587  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 17:08:27.587  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:27.587  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.597  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:27.597  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.597  1292  7216 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.597  2903  2924 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.597  2903  2924 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.597  1292  1301 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 17:08:27.607  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 17:08:27.607  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.607  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.607  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.607  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.607  7245  7245 I BluetoothPbapService: Handler(): got msg=1
,08-31 17:08:27.607  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:08:27.607  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.607  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 17:08:27.607  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 17:08:27.607  6782  6791 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.607  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 17:08:27.607  6782  6791 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:27.607  1292  5278 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 17:08:27.607  1292  5278 D Bluetoothsap: Binding service...
08-31 17:08:27.607  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 17:08:27.607  1292  5278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 17:08:27.607  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 17:08:27.607  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.617  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.617  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.617  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-31 17:08:27.617  1292  5278 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 17:08:27.617  7245  7316 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 17:08:27.617  1445  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:27.617  1292  1292 D HeadsetProfile: Bluetooth service connected
08-31 17:08:27.617  1445  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.617  1292  1292 D BluetoothPbap: Proxy object connected
08-31 17:08:27.617  1292  1292 D PbapServerProfile: Bluetooth service connected
08-31 17:08:27.617  1292  1292 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 17:08:27.617  1292  1292 D SapProfile: Bluetooth service connected
08-31 17:08:27.617  1292  1292 D Bluetoothsap: getConnectedDevices()
,08-31 17:08:27.617  1456  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.627  7245  7316 D BluetoothSocket: bindListen(): myUserId = 0
08-31 17:08:27.627  7245  7316 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:27.627  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:27.627  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:27.627  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.627  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.627  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.627  1456  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.627  7245  7316 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,08-31 17:08:27.627  7245  7316 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 17:08:27.627  7245  7316 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-31 17:08:27.627  2903  2915 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:08:27.627  7245  7316 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a13f55b
08-31 17:08:27.627  7245  7316 D BluetoothSocket: channel: 19
08-31 17:08:27.627  7245  7316 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 17:08:27.627  2903  2915 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.627  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 17:08:27.627  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.637  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.637  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.637  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.637  1933  2115 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.637  2903  2903 D BluetoothA2dp: Proxy object connected
,08-31 17:08:27.637  1933  2115 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:27.637  1292  1300 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 17:08:27.637  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 17:08:27.637  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.637  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.637  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.637  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.647  1292  1292 D BluetoothInputDevice: Proxy object connected
,08-31 17:08:27.647  1292  1292 D HidProfile: Bluetooth service connected
,08-31 17:08:27.647  1434  7218 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.647  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:27.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:27.647  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.647  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.647  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.647  1434  7218 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.647  1292  1301 D BluetoothPan: Binding service...
,08-31 17:08:27.647  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 17:08:27.647  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.647  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.647  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.647  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.657  1292  5278 D BluetoothMap: onBluetoothStateChange: up=true
08-31 17:08:27.657  1292  1292 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 17:08:27.657  1292  1292 D PanProfile: Bluetooth service connected
,08-31 17:08:27.657  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 17:08:27.657  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.657  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.657  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.657  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.657  7245  7278 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 17:08:27.657  7245  7278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.657  1292  1292 D BluetoothMap: Proxy object connected
08-31 17:08:27.657  1292  1292 D MapProfile: Bluetooth service connected
08-31 17:08:27.657  1292  1292 D BluetoothMap: getConnectedDevices()
,08-31 17:08:27.657  2903  2924 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.657  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:27.657  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 17:08:27.657  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.657  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.657  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.657  2903  2924 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.667  1177  2748 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.667  1177  2748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.667  1017  1046 D BluetoothPan: Binding service...
,08-31 17:08:27.667  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 17:08:27.667  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.667  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 17:08:27.667  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 17:08:27.667  1434  1443 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 17:08:27.667  1434  1443 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 17:08:27.667  1292  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:08:27.667  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:27.667  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:27.667  1292  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.667  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 17:08:27.667  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.667  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.667  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.667  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.667  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 17:08:27.667  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:27.667  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 17:08:27.667  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.667  1292  1292 D BluetoothA2dp: Proxy object connected
08-31 17:08:27.667  1434  7218 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 17:08:27.667  1292  1292 D A2dpProfile: Bluetooth service connected
08-31 17:08:27.667  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 17:08:27.667  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 17:08:27.667  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:27.667  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.667  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.667  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.667  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:27.667  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29796c5e added. We now have 8 listener(s)
08-31 17:08:27.667  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:08:27.677  1434  7218 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 17:08:27.677  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 17:08:27.677  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 17:08:27.677  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:27.677  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-31 17:08:27.677  1017  2952 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 17:08:27.677  1017  2952 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 17:08:27.677  1017  2952 D SecContentProvider2: mCursor = null
,08-31 17:08:27.677  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 17:08:27.677  1017  2952 D WifiService: setWifiEnabled: false pid=6683, uid=10155
,08-31 17:08:27.677  1017  2952 D SettingsProvider: name = wifi_on
,08-31 17:08:27.677  1434  1434 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@184347, true
,08-31 17:08:27.677  1434  1434 D BluetoothHeadset: registerMessageListener
,08-31 17:08:27.687  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 17:08:27.687  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:27.687  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 17:08:27.687  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:27.687  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-31 17:08:27.687  1017  3236 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 17:08:27.687  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:27.687  1017  3236 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 17:08:27.687  1017  3236 D SecContentProvider2: mCursor = null
,08-31 17:08:27.687  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:27.697  1017  3236 D WifiService: setWifiEnabled: true pid=6683, uid=10155
08-31 17:08:27.697  1017  3236 W ActivityManager: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 17:08:27.697  1017  3236 W WifiService: Failed getting userId using ActivityManagerNative
08-31 17:08:27.697  1017  3236 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6683, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 17:08:27.697  1017  3236 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 17:08:27.697  1017  3236 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 17:08:27.697  1017  3236 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 17:08:27.697  1017  3236 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 17:08:27.697  1017  3236 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 17:08:27.697  1017  3236 D SettingsProvider: name = wifi_on
,08-31 17:08:27.697  1017  1218 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:27.697  1017  3237 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 17:08:27.697  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 17:08:27.697  1771  1771 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 17:08:27.697  1292  1292 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:08:27.697  1177  1699 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 17:08:27.697  1017  1131 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 17:08:27.707  1017  2951 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:27.707  1017  2951 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.707  7245  7253 D HeadsetService: registerMessageListener
08-31 17:08:27.707  1017  2951 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.707  1017  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:27.707  1017  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 17:08:27.707  7245  7253 D HeadsetService: registerMessageListener
08-31 17:08:27.707  7245  7277 D HeadsetStateMachine: Disconnected process message: 70
08-31 17:08:27.707  7245  7277 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ea361f8
08-31 17:08:27.707  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 17:08:27.707  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:27.707  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:27.717  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 17:08:27.717  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 17:08:27.717  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 17:08:27.717  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:27.717  1292  1292 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-31 17:08:27.717  7245  7277 D HeadsetStateMachine: Disconnected process message: 9
08-31 17:08:27.717  1292  1292 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 17:08:27.717  1292  1292 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 17:08:27.717  7245  7277 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-31 17:08:27.717  1292  1292 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 17:08:27.727  7245  7322 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 17:08:27.727   283  1014 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 17:08:27.727   283  1014 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 17:08:27.727   283  1014 V voice   : voice_set_parameters: exit with code(-2)
,08-31 17:08:27.727  1292  1292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 17:08:27.727   283  1014 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 17:08:27.727   283  1014 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 17:08:27.727   283  1014 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-31 17:08:27.727   283  1014 V audio_hw_primary: adev_set_parameters: exit
08-31 17:08:27.727  7245  7277 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-31 17:08:27.737  1017  1315 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 17:08:27.737  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.737  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.737  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.737  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 17:08:27.737  7245  7322 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 17:08:27.737  7245  7322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:27.737  7245  7322 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
,08-31 17:08:27.737  7245  7322 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 17:08:27.737  7245  7322 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 17:08:27.737  7245  7322 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13a76d1
08-31 17:08:27.737  7245  7322 D BluetoothSocket: channel: 5
,08-31 17:08:27.747  1292  1292 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:08:27.747  1292  1292 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 17:08:27.757  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:08:27.757  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 17:08:27.767  7245  7245 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
,08-31 17:08:27.767  7245  7245 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 17:08:27.767  1017  1316 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 17:08:27.767  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.767  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.777  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:27.777  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 17:08:27.787  1933  1933 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 17:08:27.787  1017  1313 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 17:08:27.787  1017  1313 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:27.787  1017  1313 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:27.787  1017  1313 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:27.787  1017  1313 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:27.797  1933  1933 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 17:08:27.797  1933  7328 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-31 17:08:27.797  1017  2930 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 17:08:27.807  1017  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:27.807  1017  1492 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.807  1017  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:27.807  1017  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:27.817  7245  7332 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 17:08:27.817  7245  7332 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:08:27.817  7245  7332 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 17:08:27.817  7245  7332 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 17:08:27.817  7245  7332 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 17:08:27.817  7245  7332 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31eaf0d
,08-31 17:08:27.817  7245  7332 D BluetoothSocket: channel: 12
08-31 17:08:27.817  7245  7332 I BtOppRfcommListener: Accept thread started.
,08-31 17:08:27.827  1017  1315 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 17:08:27.827  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:27.827  1017  1315 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:27.827  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 17:08:27.837  1933  7328 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 17:08:28.057  1017  1044 D Tethering: interfaceAdded wlan0
,08-31 17:08:28.067  1017  1134 E Tethering: No numeric data
,08-31 17:08:28.067  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:28.067  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:28.067  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:28.067  1017  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-31 17:08:28.067  1017  1134 D Tethering: clearTetheredNotification()
08-31 17:08:28.077  1017  1134 D Tethering: InitialState.processMessage what=4
,08-31 17:08:28.077  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:28.077  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:28.077  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:28.087  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:28.087  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 17:08:28.087  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:28.087  1017  1134 E Tethering: No numeric data
,08-31 17:08:28.087  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:28.087  1017  1124 V NetworkStats: performPollLocked() took 8ms
,08-31 17:08:28.087  1017  1044 D Tethering: interfaceAdded p2p0
08-31 17:08:28.087  1017  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:08:28.097  1017  1134 D Tethering: clearTetheredNotification()
,08-31 17:08:28.097  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 17:08:28.097  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 17:08:28.097  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:28.097  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:28.097  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:28.107  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:28.107  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:28.107  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:28.107  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 17:08:28.107  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 17:08:28.107  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:28.107  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:28.107   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 17:08:28.107   278   983 D SoftapController: Softap fwReload - Ok
,08-31 17:08:28.107  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:28.107  1017  1124 V NetworkStats: performPollLocked() took 15ms
,08-31 17:08:28.117   278   983 D CommandListener: Setting iface cfg
08-31 17:08:28.117   278   983 D CommandListener: Trying to bring down wlan0
08-31 17:08:28.117  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:28.117  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:28.117   278   983 D CommandListener: Clearing all IP addresses on wlan0,
,08-31 17:08:28.117  1017  1131 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 17:08:28.167  7340  7340 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-31 17:08:28.167  7340  7340 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 17:08:28.177  7340  7340 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 17:08:28.187  7340  7340 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 17:08:28.187   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7340
08-31 17:08:28.187   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-31 17:08:28.187  7340  7340 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 17:08:28.187  7340  7340 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:28.187  7340  7340 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 17:08:28.187  7340  7340 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 17:08:28.197   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7340
08-31 17:08:28.197   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-31 17:08:28.227  1017  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 17:08:28.227  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:28.227  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 17:08:28.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.227  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:28.227  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 17:08:28.227  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 17:08:28.237  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:28.237  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 17:08:28.237  1177  1177 D HotspotTile: onReceive : 2, 0
,08-31 17:08:28.237  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:28.247  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:28.247  1017  1687 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:28.247  1017  1687 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:28.247  1017  1687 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:28.247  1017  1687 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:28.247  1017  1687 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:28.247  3674  3674 I Hs20UtilService: Starting #19
08-31 17:08:28.247  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:28.257  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:28.257  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:28.257  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:28.257  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:28.367   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-31 17:08:28.377  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-31 17:08:28.437  7340  7340 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-31 17:08:28.437  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 17:08:28.447  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-31 17:08:28.447   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7340
08-31 17:08:28.447   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-31 17:08:28.457  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 17:08:28.457  7340  7340 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:28.457  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 17:08:28.457  7340  7340 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:28.457  7340  7340 E wpa_supplicant: SIM READ ERROR
08-31 17:08:28.457  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 17:08:28.457  7340  7340 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:28.457  7340  7340 E wpa_supplicant: SIM READ ERROR
08-31 17:08:28.457  7340  7340 I wpa_supplicant: Blacklist: Clear (all) 
08-31 17:08:28.457  7340  7340 I wpa_supplicant: wpa_default_ap_write_once
08-31 17:08:28.457  7340  7340 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-31 17:08:28.457  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:28.457  7340  7340 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 17:08:28.457  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:28.457  7340  7340 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 17:08:28.457  7340  7340 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 17:08:28.457  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 17:08:28.457  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:28.457  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:28.507  7340  7340 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 17:08:28.717  7340  7340 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 17:08:28.717  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 17:08:28.737  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-31 17:08:28.737   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7340,
08-31 17:08:28.737   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-31 17:08:28.737  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 17:08:28.737  7340  7340 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:28.737  7340  7340 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 17:08:28.737  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-31 17:08:28.747  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-31 17:08:28.747   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7340
08-31 17:08:28.747   399   399 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-31 17:08:28.747  7340  7340 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 17:08:28.747  7340  7340 I wpa_supplicant: ssSupport state is = 1
08-31 17:08:28.757  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 17:08:28.747  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 17:08:28.747  7340  7340 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 17:08:28.747  7340  7340 E wpa_supplicant: SIM READ ERROR,
08-31 17:08:28.757  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 17:08:28.747  7340  7340 I wpa_supplicant: wpa_default_ap_write_once
08-31 17:08:28.747  7340  7340 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 17:08:28.747  7340  7340 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-31 17:08:28.757  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:28.757  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 17:08:28.757  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 17:08:28.757  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-31 17:08:28.827  7340  7340 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 17:08:28.827  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 17:08:28.907  7340  7340 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 17:08:28.907  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 17:08:28.907  7340  7340 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-31 17:08:28.917  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-31 17:08:28.917  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 17:08:28.917  7340  7340 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 17:08:28.917  7340  7340 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 17:08:28.917  7340  7340 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 17:08:28.917  7340  7340 E wpa_supplicant: SIM READ ERROR,
08-31 17:08:28.917  7340  7340 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 17:08:28.927  7340  7340 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 17:08:28.937  1017  1131 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 17:08:28.937  7340  7340 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 17:08:28.937  1017  1131 D WifiConfigStore: Loading config and enabling all networks 
,08-31 17:08:28.947  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:28.947  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:28.947  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:28.947  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.947  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.947  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:28.947  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:28.947  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 17:08:28.947  1177  1699 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 17:08:28.947  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:28.947  1292  1292 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:08:28.947  1177  1177 D HotspotTile: onReceive : 3, 0
,08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:28.957  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:28.957  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:28.967  1017  1315 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 17:08:28.967  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:28.967  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:28.967  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:28.967  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:28.967  3674  3674 I Hs20UtilService: Starting #20
,08-31 17:08:28.967  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 17:08:28.977  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:28.977  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
08-31 17:08:28.977  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:28.977  3674  3690 I Hs20UtilService: Message received 5011
,08-31 17:08:28.977  1017  1131 E WifiConfigStore: Not a HS20
,08-31 17:08:28.977  1017  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 17:08:28.977  1017  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 17:08:28.987  1017  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 17:08:28.987  7340  7340 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 17:08:28.987  7340  7340 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 17:08:28.987  7340  7340 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 17:08:28.987  7340  7340 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 17:08:28.987  7340  7340 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 17:08:28.987  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 17:08:28.987  7340  7340 I wpa_supplicant: First Scan Start
,08-31 17:08:28.987  7340  7340 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 17:08:28.997  6858  6858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:08:28.997  1017  1131 D WifiNative-wlan0: Setting external_sim to 1
,08-31 17:08:28.997  1017  1131 D WifiStateMachine: Setting OUI to DA-A1-19
,08-31 17:08:28.997  1017  1131 I WifiNative-HAL: startHal
08-31 17:08:28.997  1017  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9c95b88c
08-31 17:08:28.997  1017  1131 I WifiNative-HAL: Could not start hal
,08-31 17:08:28.997  1017  1131 E WifiNative-wlan0: do suspend true
,08-31 17:08:28.997  1017  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 17:08:29.007  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 17:08:29.007  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:29.007  1017  1150 I WifiNative-HAL: startHal
08-31 17:08:29.007  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9db0d9bc
08-31 17:08:29.007  1017  1150 I WifiNative-HAL: Could not start hal
08-31 17:08:29.007  1017  1150 E WifiScanningService: could not start HAL
08-31 17:08:29.007  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 17:08:29.007  1017  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 17:08:29.007  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-31 17:08:29.007  1017  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 17:08:29.007  1017  1131 E WifiNative-wlan0: invaild command id : 215
,08-31 17:08:29.007   278   983 D CommandListener: Setting iface cfg
08-31 17:08:29.007   278   983 D CommandListener: Trying to bring up p2p0
,08-31 17:08:29.007  1017  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 17:08:29.007  1017  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 17:08:29.007  1017  1131 E WifiNative-wlan0: invaild command id : 215
08-31 17:08:29.007  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 17:08:29.007  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 17:08:29.007  1017  1126 D WifiP2pService: P2pEnablingState
,08-31 17:08:29.007  7340  7340 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 17:08:29.007  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 17:08:29.007  1017  1126 D WifiP2pService: P2p socket connection successful
08-31 17:08:29.007  1017  1126 D WifiP2pService: P2pEnabledState
,08-31 17:08:29.007  7340  7340 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 17:08:29.017  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 17:08:29.017  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:29.017  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 17:08:29.017  7340  7340 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-31 17:08:29.017  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 17:08:29.017  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:29.017  1017  1047 D WifiDisplayController: disconnect
08-31 17:08:29.017  1017  1047 D WifiDisplayController: updateConnection
08-31 17:08:29.017  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 17:08:29.017  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:29.017  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 17:08:29.017  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-31 17:08:29.017  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 17:08:29.017  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 17:08:29.017  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:29.017  1017  1131 D SecContentProvider2: mCursor = null,
08-31 17:08:29.017  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 17:08:29.017  1017  3237 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 17:08:29.017  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 17:08:29.027  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 17:08:29.027  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-31 17:08:29.027  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 17:08:29.027  1017  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
08-31 17:08:29.027  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:29.027  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:29.027  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  secondary type: null
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  wps: 0
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  grpcapab: 0
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  devcapab: 0
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  status: 3
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  wfdInfo: null
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-31 17:08:29.027  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-31 17:08:29.027  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:29.027  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:29.027  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 17:08:29.027  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 17:08:29.037  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 17:08:29.037  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:29.037  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:29.037  6826  6826 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 17:08:29.037  6826  6826 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 17:08:29.047  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 17:08:29.047  1017  1126 D WifiP2pService: InactiveState
,08-31 17:08:29.047  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-31 17:08:29.047  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 17:08:29.047  7340  7340 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 17:08:29.047  6842  6842 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 17:08:29.047  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-31 17:08:29.047  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 17:08:29.077  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 17:08:29.077  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-31 17:08:29.077  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:29.707  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:29.717  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:29.717  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 17:08:29.717  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 17:08:29.717  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@903d880 Bundle[{}]
,08-31 17:08:29.727  6683  6736 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 17:08:29.727  6683  6736 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 17:08:29.727  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 17:08:29.727  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 17:08:29.727  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 17:08:29.727  6683  6736 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 17:08:29.737  6683  6736 I System.out: Running OutgoingSocketThread
,08-31 17:08:29.737  6683  7348 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1249)
,08-31 17:08:29.737  6683  7348 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50491
,08-31 17:08:29.737  6683  7348 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 17:08:30.077   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 17:08:30.097   288   288 E SMD     : DCD OFF
,08-31 17:08:30.107  7340  7340 I wpa_supplicant: nl80211: Received scan results (32 BSSes)
,08-31 17:08:30.107  7340  7340 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 17:08:30.117  7340  7340 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-31 17:08:30.117  7340  7340 I wpa_supplicant: Trying to associate with  'G700'
,08-31 17:08:30.117  7340  7340 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 17:08:30.117  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 17:08:30.117  1017  7346 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 17:08:30.127  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:30.127  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:30.227  7340  7340 E wpa_supplicant: Cmd 35605 not handled
,08-31 17:08:30.227  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:30.227  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-31 17:08:30.227  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-31 17:08:30.227  7340  7340 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-31 17:08:30.227  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:30.227  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:30.227  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:30.227  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 17:08:30.227  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 17:08:30.227  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-31 17:08:30.227  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 17:08:30.227  7340  7340 I wpa_supplicant: Associated with F4.99.3E
08-31 17:08:30.227  7340  7340 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 17:08:30.227  7340  7340 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 17:08:30.227  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 17:08:30.227  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 17:08:30.227  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 17:08:30.227  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 17:08:30.237  1017  1134 E Tethering: No numeric data,
08-31 17:08:30.237  1017  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:08:30.237  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:30.237  1017  1134 D Tethering: clearTetheredNotification()
08-31 17:08:30.237  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-31 17:08:30.237  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:30.237  1177  1177 D HotspotTile: updateTetherState():false, false
08-31 17:08:30.237  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:30.237  1017  1124 V NetworkStats: performPollLocked() took 4ms
08-31 17:08:30.237  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:30.237  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:30.237  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:30.237  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:30.247  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 17:08:30.247  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:30.247  7340  7340 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 17:08:30.247  7340  7340 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 17:08:30.247  7340  7340 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-31 17:08:30.247  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 17:08:30.247  7340  7340 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:08:30.247  7340  7340 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 17:08:30.247  7340  7340 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 17:08:30.247  7340  7340 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 17:08:30.247  7340  7340 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 17:08:30.247  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 17:08:30.257  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:30.257  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:30.257  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-31 17:08:30.257  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 17:08:30.257  1017  1131 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-31 17:08:30.257  1017  1131 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-31 17:08:30.267  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:30.267  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:30.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:30.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:30.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:30.267  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:30.267  1017  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 17:08:30.277  1017  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 17:08:30.277  1017  1133 E ConnectivityService: updateNetworkInfo()
,08-31 17:08:30.277  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:08:30.277  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:08:30.277  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-31 17:08:30.277  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 17:08:30.277  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:30.277  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:30.277  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 17:08:30.277  3674  3674 I Hs20UtilService: Starting #21
,08-31 17:08:30.277  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:30.287  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-31 17:08:30.287  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 17:08:30.287  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 17:08:30.287  1017  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 17:08:30.287  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:30.287  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 17:08:30.287  1292  1292 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 17:08:30.287  1292  3115 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 17:08:30.307   278   983 D CommandListener: Setting iface cfg
,08-31 17:08:30.307  1017  1131 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 17:08:30.307  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 17:08:30.307  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:30.317  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:30.317  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 17:08:30.317  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:30.317  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:30.327  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:30.327  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:30.327  1017  1131 E WifiNative-wlan0: do suspend false
,08-31 17:08:30.327  1017  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 17:08:30.327  1017  1131 D SecContentProvider2: mCursor = null
,08-31 17:08:30.327  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-31 17:08:30.337  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 17:08:30.547  7351  7351 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 17:08:30.547  7351  7351 I dhcpcd  : version 5.5.6 starting
,08-31 17:08:30.557  7351  7351 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 17:08:30.607  7351  7351 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 17:08:30.607  7351  7351 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 17:08:30.607  7351  7351 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 17:08:30.607  7351  7351 I dhcpcd  : bssid match
08-31 17:08:30.607  7351  7351 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-31 17:08:30.667  7351  7351 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-31 17:08:30.737  7351  7351 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
08-31 17:08:30.737  6683  6736 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1250)
08-31 17:08:30.737  6683  6736 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1250),
,08-31 17:08:30.737  6683  6736 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1255)
,08-31 17:08:30.737  6683  6736 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 17:08:30.737  6683  6736 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1256),
,08-31 17:08:30.747  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:30.747  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166bf83f added. We now have 2 listener(s)
,08-31 17:08:30.757  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-31 17:08:30.757  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 17:08:30.757  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-31 17:08:30.757  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:30.757  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3156150c added. We now have 9 listener(s)
08-31 17:08:30.757  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-31 17:08:30.757  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:08:30.757  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:30.767  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:08:30.767  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:30.767  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:30.767  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:30.767  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26bf06a added. We now have 3 listener(s)
,08-31 17:08:30.777  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:30.777  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:30.777  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:30.777  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731d95b added. We now have 10 listener(s)
,08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:30.777  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:30.777  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:30.777  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:08:30.777  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:30.777  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:30.777  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 17:08:30.777  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166bf83f removed from the list
08-31 17:08:30.777  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.777  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3156150c removed from the list
,08-31 17:08:30.777  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:30.777  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.777  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.787  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3156150c not in the list
08-31 17:08:30.787  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731d95b removed from the list
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:30.787  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26bf06a removed from the list
08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d575f8 added. We now have 2 listener(s)
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-31 17:08:30.787  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a4fad1 added. We now have 9 listener(s)
08-31 17:08:30.787  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:30.787  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:08:30.797  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:30.807  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:30.807  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:30.807  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:30.807  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:30.807  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daab037 added. We now have 3 listener(s)
,08-31 17:08:30.807  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:30.807  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:08:30.807  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:08:30.807  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:30.807  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:30.807  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:30.807  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7f9a4 added. We now have 10 listener(s)
08-31 17:08:30.807  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:30.807  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:30.807  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:08:30.807  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:08:30.807  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:30.807  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:08:30.817  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-31 17:08:30.817  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:08:30.827  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:08:30.837  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:08:30.837  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:08:30.837  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:08:30.837  7245  7278 D BtGatt.GattService: registerClient() - UUID=4a4c64f4-f069-41d1-825c-326b285ac622
,08-31 17:08:30.887  7245  7272 D BtGatt.GattService: onClientRegistered() - UUID=4a4c64f4-f069-41d1-825c-326b285ac622, clientIf=6
,08-31 17:08:30.887  6683  6693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 17:08:30.887  7245  7257 D BtGatt.GattService: start scan with filters
08-31 17:08:30.887  7245  7276 D BtGatt.ScanManager: handling starting scan
08-31 17:08:30.887  7245  7276 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cb34a4e
08-31 17:08:30.887  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:08:30.887  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:08:30.887  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:08:30.887  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:08:30.897  7245  7272 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 17:08:30.897  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:30.897  7245  7276 D BtGatt.ScanManager: allow scan with filters
08-31 17:08:30.897  7245  7276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 17:08:30.897  7245  7276 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-31 17:08:30.897  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:08:30.897  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:08:30.897  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 17:08:30.897  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:30.897  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 17:08:30.897  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:30.897  7245  7276 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:08:30.897  7245  7276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,08-31 17:08:30.907  6683  6736 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 17:08:30.907  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-31 17:08:30.907  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 17:08:30.907  7245  7272 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 17:08:30.907  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.907  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:30.907  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 17:08:30.907  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:08:30.907  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:08:30.907  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:08:30.907  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:08:30.907  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:08:30.907  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 17:08:30.907  7245  7317 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:08:30.907  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 17:08:30.907  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:30.907  7245  7320 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:08:30.917  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 17:08:30.917  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:08:30.917  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:08:30.917  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:30.927  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:30.927  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:30.927  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:30.927  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:30.927  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:30.927  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.927  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:30.927  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d575f8 removed from the list
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a4fad1 removed from the list
08-31 17:08:30.927  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:30.927  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:30.927  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.927  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.927  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a4fad1 not in the list
08-31 17:08:30.927  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.927  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7f9a4 removed from the list
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:30.927  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:30.927  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:30.927  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3daab037 removed from the list
,08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 17:08:30.927  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107d0c10 added. We now have 2 listener(s)
,08-31 17:08:30.937  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 17:08:30.937  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:30.937  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:30.937  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:30.937  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b3309 added. We now have 9 listener(s)
,08-31 17:08:30.937  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:30.937  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:08:30.937  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:30.947  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:30.947  7245  7276 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 42
,08-31 17:08:30.947  7245  7276 D BtGatt.ScanManager: filter size is 1
08-31 17:08:30.947  7245  7276 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 17:08:30.947  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 17:08:30.947  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-31 17:08:30.947  7245  7276 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:08:30.947  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:30.947  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:30.947  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:30.947  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8196f2f added. We now have 3 listener(s)
,08-31 17:08:30.957  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:30.957  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:30.957  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 17:08:30.957  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:30.957  7245  7276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 17:08:30.957  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 17:08:30.957  7245  7272 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 17:08:30.957  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:30.957  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-31 17:08:30.957  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:30.957  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:30.957  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@200ed93c added. We now have 10 listener(s),
08-31 17:08:30.957  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:30.957  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:30.957  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:30.957  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:08:30.957  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 17:08:30.957  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:30.957  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:08:30.967  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-31 17:08:30.977  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:08:30.977  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-31 17:08:30.977  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:08:30.977  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:08:30.977  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:08:30.987  7245  7278 D BtGatt.GattService: registerClient() - UUID=681bbade-9e73-420a-a0a5-6887a63b953d
,08-31 17:08:31.027  7245  7272 D BtGatt.GattService: onClientRegistered() - UUID=681bbade-9e73-420a-a0a5-6887a63b953d, clientIf=6
,08-31 17:08:31.027  6683  6693 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 17:08:31.027  7245  7257 D BtGatt.GattService: start scan with filters
,08-31 17:08:31.027  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:08:31.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:08:31.027  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:08:31.027  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 17:08:31.027  7245  7276 D BtGatt.ScanManager: handling starting scan,
,08-31 17:08:31.037  7245  7272 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 17:08:31.037  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.037  7245  7276 D BtGatt.ScanManager: allow scan with filters
,08-31 17:08:31.037  7245  7276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 17:08:31.037  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:08:31.037  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 17:08:31.037  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:31.037  7245  7276 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 17:08:31.037  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 17:08:31.037  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.037  7245  7276 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 17:08:31.037  7245  7276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 17:08:31.047  7245  7272 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 17:08:31.047  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 17:08:31.047  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.047  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 17:08:31.047  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.057  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:31.057  6683  6736 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 17:08:31.057  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:31.057  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:31.057  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.057  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.057  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107d0c10 removed from the list
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.057  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b3309 removed from the list
08-31 17:08:31.057  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:31.057  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 17:08:31.057  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.057  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b3309 not in the list
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:08:31.057  7245  7320 D BtGatt.GattService: stopScan() - queue size =1
,08-31 17:08:31.057  7245  7278 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:08:31.057  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:08:31.057  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 17:08:31.067  7245  7276 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 43
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:31.067  7245  7276 D BtGatt.ScanManager: filter size is 1
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 17:08:31.067  7245  7276 D BtGatt.ScanManager: delete FilterIndex - 4
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.067  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 17:08:31.067  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.067  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@200ed93c removed from the list
08-31 17:08:31.067  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.067  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.067  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.067  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:31.067  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8196f2f removed from the list
,08-31 17:08:31.067  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:31.067  7245  7276 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:08:31.067  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:31.067  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348e4d28 added. We now have 2 listener(s)
,08-31 17:08:31.067  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 17:08:31.067  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 17:08:31.067  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:31.077  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:31.077  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:31.077  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11093a41 added. We now have 9 listener(s)
08-31 17:08:31.077  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:31.077  7245  7276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 17:08:31.077  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:08:31.077   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 17:08:31.077  7245  7272 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 17:08:31.077  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.077  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:31.077  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:08:31.087  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:08:31.087  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:08:31.087  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:31.087  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:31.087  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 17:08:31.087  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd21527 added. We now have 3 listener(s)
,08-31 17:08:31.097  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 17:08:31.097  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:08:31.097  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:31.097  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:08:31.097  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0f13d4 added. We now have 10 listener(s)
08-31 17:08:31.097  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:08:31.097  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:31.097  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 17:08:31.097  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:08:31.097  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:31.097  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:08:31.097  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:08:31.107  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:08:31.107  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 17:08:31.107  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 17:08:31.107  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 17:08:31.107  6683  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 17:08:31.117  7245  7253 D BtGatt.GattService: registerClient() - UUID=8e8c4aa8-5d75-4f1f-a87b-81003fa66303,
,08-31 17:08:31.147  1017  1131 E WifiNative-wlan0: do suspend true
,08-31 17:08:31.157  7245  7272 D BtGatt.GattService: onClientRegistered() - UUID=8e8c4aa8-5d75-4f1f-a87b-81003fa66303, clientIf=6,
08-31 17:08:31.157  6683  6691 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 17:08:31.157  7245  7317 D BtGatt.GattService: start scan with filters
08-31 17:08:31.157  7245  7276 D BtGatt.ScanManager: handling starting scan
,08-31 17:08:31.157  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 17:08:31.157  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 17:08:31.157  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 17:08:31.157  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 17:08:31.157  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 17:08:31.157  7245  7272 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-31 17:08:31.157  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.157  7245  7276 D BtGatt.ScanManager: allow scan with filters
08-31 17:08:31.157  7245  7276 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 17:08:31.157  7245  7276 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 17:08:31.157  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 17:08:31.167  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 17:08:31.167  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.167  7245  7276 D BtGatt.ScanManager: Starting BLE batch scan
08-31 17:08:31.167  7245  7276 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 17:08:31.167  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-31 17:08:31.167  7245  7272 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 17:08:31.167  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.167  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 17:08:31.167  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 17:08:31.167  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.177  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-31 17:08:31.177  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 17:08:31.177  1017  1131 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 17:08:31.177  1017  1131 E WifiStateMachine: VerifyingLinkState enter
,08-31 17:08:31.177  1017  1131 D WifiNative-wlan0: callSECApiInt - ID [210]
08-31 17:08:31.177  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:31.177  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:31.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.177  1017  1133 E ConnectivityService: updateNetworkInfo()
,08-31 17:08:31.177  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:31.177  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:31.177  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:31.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.177  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.177  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 17:08:31.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.177  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348e4d28 removed from the list
08-31 17:08:31.177  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.177  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11093a41 removed from the list
08-31 17:08:31.177  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:31.177  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:08:31.177  1017  1133 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 17:08:31.177  1017  1133 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 17:08:31.187  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 17:08:31.187  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 17:08:31.187  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 17:08:31.187  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 17:08:31.187  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 17:08:31.197  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:31.197  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:31.197  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.197  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.197  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.197  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.197  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:08:31.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 17:08:31.197  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:31.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:31.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.197  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11093a41 not in the list
08-31 17:08:31.197  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:08:31.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 17:08:31.197  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 17:08:31.207  7245  7278 D BtGatt.GattService: stopScan() - queue size =1,
08-31 17:08:31.207  7245  7257 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:31.207  7245  7276 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 44
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.207  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:31.207  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:31.207  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:31.207  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:31.207  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.207  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0f13d4 removed from the list
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.207  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.207  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.207  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cd21527 removed from the list
08-31 17:08:31.217  1017  1131 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 17:08:31.217  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:08:31.217  6683  6683 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start, advertiser: false
08-31 17:08:31.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:08:31.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c339940 added. We now have 2 listener(s)
08-31 17:08:31.217  3674  3674 I Hs20UtilService: Starting #22
08-31 17:08:31.217  3674  3690 I Hs20UtilService: Message received 5007
,08-31 17:08:31.217  6683  6683 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:08:31.217  1017  1133 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-31 17:08:31.217  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:31.217  7245  7276 D BtGatt.ScanManager: filter size is 1
,08-31 17:08:31.217  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-31 17:08:31.217  1017  1133 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-31 17:08:31.217  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:31.217  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:31.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:31.217  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2229f079 added. We now have 9 listener(s)
08-31 17:08:31.217  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:31.217  7245  7276 D BtGatt.ScanManager: delete FilterIndex - 5
08-31 17:08:31.217  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:08:31.227  1017  1133 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-31 17:08:31.227  7245  7272 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 17:08:31.227  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.227  7245  7276 D BtGatt.ScanManager: stopping BLe Batch
08-31 17:08:31.227  1017  1133 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 17:08:31.227  1017  1133 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-31 17:08:31.227  1017  1133 D ConnectivityService: LTETest block dns file not exists
08-31 17:08:31.227  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:08:31.227  1292  1292 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 17:08:31.227  7245  7272 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 17:08:31.227  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 17:08:31.227  7245  7276 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 17:08:31.227  7245  7272 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 17:08:31.227  7245  7272 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 17:08:31.237  1017  1133 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504],
08-31 17:08:31.237  1017  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:08:31.237  6683  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:08:31.237  1017  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 17:08:31.237  1017  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:08:31.237  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:31.237  1017  1133 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-31 17:08:31.237  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 17:08:31.237  1017  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 17:08:31.237  1017  1133 E ConnectivityService: updateNetworkInfo()
08-31 17:08:31.237  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:31.237  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 17:08:31.237  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:08:31.237  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-31 17:08:31.237  1017  7349 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 17:08:31.237   278   979 D EnterpriseController: uids 1000
08-31 17:08:31.237   278   979 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 17:08:31.237   278   979 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-31 17:08:31.237  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 17:08:31.237  1017  1133 D ConnectivityService:    accepting network in place of null
,08-31 17:08:31.237  1017  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 17:08:31.237  1017  1133 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 17:08:31.237  1017  1133 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-31 17:08:31.247  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 17:08:31.247  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 17:08:31.247  1017  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 17:08:31.247  6683  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:08:31.247  6683  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:08:31.247  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 17:08:31.247  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@304a821f added. We now have 3 listener(s)
08-31 17:08:31.247  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:31.247  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 17:08:31.247  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 17:08:31.247  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 17:08:31.247  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-31 17:08:31.247  1017  1017 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-31 17:08:31.247  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.247  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.247  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.247  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.257  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 17:08:31.257  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 17:08:31.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.257  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 17:08:31.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:08:31.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:08:31.267  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:08:31.267  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659096c added. We now have 10 listener(s)
08-31 17:08:31.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:08:31.267  6683  6736 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:08:31.267  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:31.267  6683  6736 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:08:31.267  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.267  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.267  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:08:31.267  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.267  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c339940 removed from the list
08-31 17:08:31.267  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.267  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2229f079 removed from the list
,08-31 17:08:31.267  1017  1133 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 17:08:31.267  1017  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:08:31.277  6683  6683 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:08:31.277  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 17:08:31.277  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 17:08:31.277  1017  1134 D Tethering: MasterInitialState.processMessage what=3
08-31 17:08:31.277  6683  6683 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:08:31.277  1177  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 17:08:31.277  1017  1124 V NetworkStats: updateIfacesLocked()
08-31 17:08:31.277  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.277  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 17:08:31.277  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 17:08:31.277  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:31.277  3819  6570 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 17:08:31.287  6683  6683 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:08:31.287  6683  6736 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:08:31.287  1017  1124 V NetworkStats: performPollLocked() took 5ms
08-31 17:08:31.287  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 17:08:31.287  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 17:08:31.287  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.287  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.287  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 17:08:31.287  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.287  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.287  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.287  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.287  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.287  1017  1139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.287  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:31.287  6683  6736 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2229f079 not in the list
08-31 17:08:31.287  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.287  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:08:31.287  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:08:31.287  6683  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659096c removed from the list
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:08:31.287  6683  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.287  6683  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:08:31.287  6683  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.287  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.287  6683  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@304a821f removed from the list
08-31 17:08:31.287  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:31.287  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:31.287  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:31.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 17:08:31.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 17:08:31.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 17:08:31.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:08:31.287  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 17:08:31.297  6683  6736 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:08:31.297  3674  3674 I Hs20UtilService: Starting #23
08-31 17:08:31.297  3674  3690 I Hs20UtilService: Message received 5007
08-31 17:08:31.297  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:31.297  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:31.297  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:31.297  1292  1292 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 17:08:31.297  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 17:08:31.297  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 17:08:31.297  1292  1292 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 17:08:31.297  1292  1292 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 17:08:31.297  6683  7389 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1263, name: My test thread name)
08-31 17:08:31.297  6683  7389 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1263, thread name: My test thread name)
08-31 17:08:31.297  6683  7389 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1263, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 17:08:31.307  6683  7390 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1265, name: My test thread name)
08-31 17:08:31.307  6683  7390 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1265, thread name: My test thread name)
08-31 17:08:31.307  6683  7390 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1265, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 17:08:31.307  6683  6736 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 17:08:31.307  6683  6736 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 17:08:31.307  6683  6736 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 17:08:31.307  6683  6736 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 17:08:31.307  6683  6736 D com.test.thalitest.ThaliTestRunner: Total duration: 23319 ms
,08-31 17:08:31.307  6683  6736 I jxcore-log: *Native tests were executed*
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: Total number of executed tests:  80
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: Number of passed tests:  80
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: Number of failed tests:  0
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: Number of ignored tests:  0
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: Total duration:  23319
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 17:08:31.307  6683  6736 I jxcore-log: 
08-31 17:08:31.307  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.307  6683  6736 I jxcore-log: 
,08-31 17:08:31.317  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.317  6683  6736 I jxcore-log: 
08-31 17:08:31.317  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.317  6683  6736 I jxcore-log: 
08-31 17:08:31.317  1017  1316 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 17:08:31.317  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 17:08:31.317  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.317  6683  6736 I jxcore-log: 
08-31 17:08:31.317  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:31.317  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:31.317  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 17:08:31.317  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.317  6683  6736 I jxcore-log: 
08-31 17:08:31.317  3674  3674 I Hs20UtilService: Starting #24
08-31 17:08:31.327  3674  3690 I Hs20UtilService: Message received 5007
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  6683  6683 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  1292  1292 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  1292  1292 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.327  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.327  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
,08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  1017  1029 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
,08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
08-31 17:08:31.337  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.337  6683  6736 I jxcore-log: 
,08-31 17:08:31.337  1017  2951 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-31 17:08:31.347  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:08:31.347  6683  6736 I jxcore-log: 
08-31 17:08:31.347  1017  2951 D SecContentProvider2: mCursor = null
08-31 17:08:31.347  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:08:31.347  6683  6736 I jxcore-log: 
,08-31 17:08:31.347  1017  3236 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 17:08:31.347  1017  3236 D SecContentProvider2: mCursor = null
,08-31 17:08:31.347  1017  1313 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 17:08:31.347  1017  1313 D SecContentProvider2: mCursor = null
,08-31 17:08:31.347  1017  1218 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
,08-31 17:08:31.347  1017  1218 D SecContentProvider2: mCursor = null
08-31 17:08:31.347  1017  1492 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 17:08:31.347  1017  1492 D SecContentProvider2: mCursor = null
,08-31 17:08:31.347  1017  2952 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-31 17:08:31.347  1017  2952 D SecContentProvider2: mCursor = null
,08-31 17:08:31.367  1017  7349 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 17:08:31.377   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-31 17:08:31.387  1017  1030 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-31 17:08:31.387  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 17:08:31.427  6683  6683 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:08:31.427  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:08:31.427  6683  6736 I jxcore-log: 
,08-31 17:08:31.437  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 15:08:31 GMT], X-Android-Received-Millis=[1472656111447], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472656111410]},
08-31 17:08:31.437  1017  1133 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-31 17:08:31.437  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 17:08:31.437  1017  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
08-31 17:08:31.437  1017  7349 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 17:08:31.437  1017  1133 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-31 17:08:31.437  1017  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 17:08:31.437  1017  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 17:08:31.437  1177  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 17:08:31.437  3819  6570 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 17:08:31.447  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 17:08:31.447  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 17:08:31.447  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 17:08:31.567  6683  6683 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:08:31.567  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:08:31.567  6683  6736 I jxcore-log: 
,08-31 17:08:31.577  7391  7391 D AndroidRuntime: 
08-31 17:08:31.577  7391  7391 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 17:08:31.587  7391  7391 D AndroidRuntime: CheckJNI is OFF,
08-31 17:08:31.587  7391  7391 D AndroidRuntime: readGMSProperty: start
08-31 17:08:31.587  7391  7391 D AndroidRuntime: readGMSProperty: already setted!!,
08-31 17:08:31.587  7391  7391 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 17:08:31.587  7391  7391 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 17:08:31.587  7391  7391 D AndroidRuntime: readGMSProperty: end
08-31 17:08:31.587  7391  7391 D AndroidRuntime: addProductProperty: start
,08-31 17:08:31.707  7391  7391 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 17:08:31.717  6683  6683 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-31 17:08:31.717  6683  6736 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:08:31.717  6683  6736 I jxcore-log: 
,08-31 17:08:31.737  7391  7391 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-31 17:08:31.747  1017  2930 D PackageManager: START PACKAGE DELETE: observer{50544213}
08-31 17:08:31.747  1017  2930 D PackageManager: pkg{<packageName>}
08-31 17:08:31.747  1017  2930 D PackageManager: user{0}
08-31 17:08:31.747  1017  2930 D PackageManager: caller{2000}
08-31 17:08:31.747  1017  2930 D PackageManager: flags{2}
,08-31 17:08:31.757  1017  2930 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 17:08:31.757  1017  2930 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 17:08:31.757  1017  2930 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 17:08:31.757  1017  2930 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 17:08:31.757  1017  2930 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 17:08:31.757  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-31 17:08:31.757  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 17:08:31.757  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 17:08:31.757  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 17:08:31.757  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-31 17:08:31.757  1017  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
08-31 17:08:31.767  1017  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:31.827  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-31 17:08:31.827  1017  1042 I ActivityManager: Killing 6683:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 17:08:31.887  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{c7edcc2 u0 com.test.thalitest/.MainActivity t129}
,08-31 17:08:31.887  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,08-31 17:08:31.917  1017  1313 I WindowState: WIN DEATH: Window{1a33e422 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 17:08:31.917   258  4472 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-31 17:08:31.917   258   799 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-31 17:08:31.927  1017  1042 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{101da06a u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{25b1dda5 6683 com.test.thalitest/10155/u0 remote:34578f9c}: filter unregistered,
,08-31 17:08:31.927  1017  1313 D InputDispatcher: Focus left window: 6683
,08-31 17:08:31.927   258   433 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-31 17:08:31.937  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 17:08:31.937  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 17:08:31.937  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-31 17:08:31.947  6921  6921 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 17:08:31.947  5864  5864 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 17:08:31.947  5864  5864 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 17:08:31.947  5864  5864 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 17:08:31.947  5864  5864 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:31.957  1017  1057 I ActivityManager:   Force finishing activity ActivityRecord{c7edcc2 u0 com.test.thalitest/.MainActivity t129 f}
08-31 17:08:31.957  1017  1057 W ActivityManager: Duplicate finish request for ActivityRecord{c7edcc2 u0 com.test.thalitest/.MainActivity t129 f}
,08-31 17:08:31.987  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 17:08:31.997  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
08-31 17:08:31.997  1017  2930 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=32
08-31 17:08:31.997  1017  2930 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 17:08:31.997  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:32.007  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-31 17:08:32.017  5706  5706 I art     : Explicit concurrent mark sweep GC freed 1714(89KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 704us total 40.231ms
,08-31 17:08:32.027  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-31 17:08:32.037  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-31 17:08:32.037  3819  3819 I art     : Explicit concurrent mark sweep GC freed 25599(1534KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 15MB/26MB, paused 1.416ms total 81.360ms
,08-31 17:08:32.037  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 17:08:32.037  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,08-31 17:08:32.047  1017  2951 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 17:08:32.047  1017  2951 D SecContentProvider2: mCursor = null
,08-31 17:08:32.047  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-31 17:08:32.057  1771  1771 E SamsungIME: mOCRHelper is null
,08-31 17:08:32.067  1933  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 17:08:32.087   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 17:08:32.087  1017  1042 D InputDispatcher: Focused application released
,08-31 17:08:32.097  1445  1445 D PersonaManager: isKioskContainerExistOnDevice
,08-31 17:08:32.097  3177  3177 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-31 17:08:32.097  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,08-31 17:08:32.097  3177  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:446 
,08-31 17:08:32.097  6921  6921 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-31 17:08:32.107  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 17:08:32.107  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 17:08:32.107  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-31 17:08:32.107  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-31 17:08:32.107  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:32.107  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-31 17:08:32.117  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 17:08:32.117  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 17:08:32.117  1445  1445 D RegisteredServicesCache: empty dynamic service
,08-31 17:08:32.117  1017  1124 V NetworkStats: performPollLocked() took 12ms
08-31 17:08:32.117  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:32.117  1017  1313 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,08-31 17:08:32.137  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-31 17:08:32.147  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.147  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 17:08:32.157  6928  6928 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-31 17:08:32.157  1445  1445 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 17:08:32.167  1445  1445 D PersonaManager: isKioskContainerExistOnDevice
,08-31 17:08:32.167  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
08-31 17:08:32.167  1726  1726 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 17:08:32.177  1017  1017 I art     : Explicit concurrent mark sweep GC freed 73631(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 29MB/43MB, paused 8.710ms total 207.885ms
,08-31 17:08:32.187  1017  1057 I art     : WaitForGcToComplete blocked for 97.742ms for cause Explicit
,08-31 17:08:32.187  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:32.187  1017  1139 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-31 17:08:32.197  1017  2951 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 17:08:32.207  1017  1139 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-31 17:08:32.207  1726  1726 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-31 17:08:32.207  1726  1726 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,08-31 17:08:32.207  1319  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-31 17:08:32.207  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-31 17:08:32.217  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 17:08:32.217  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 17:08:32.217  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-31 17:08:32.227  1726  1726 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-31 17:08:32.227  1726  1726 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 17:08:32.227  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 17:08:32.227  6884  6884 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 17:08:32.227  6884  6884 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 17:08:32.227  3177  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-31 17:08:32.227  1726  1726 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-31 17:08:32.227  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-31 17:08:32.227  1726  1726 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-31 17:08:32.227  3177  3177 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-31 17:08:32.227  3177  3177 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-31 17:08:32.237  6884  6884 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 17:08:32.237  6928  6928 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 17:08:32.237  6928  6928 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 17:08:32.237  6928  6928 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 17:08:32.247  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 17:08:32.247  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 17:08:32.247  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 17:08:32.247  3177  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-31 17:08:32.257  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.267  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.267  1017  1133 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 17:08:32.277  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 17:08:32 GMT+02:00 2016
,08-31 17:08:32.287  1017  1316 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 17:08:32.287  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:32.287  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:32.287  3177  3177 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
08-31 17:08:32.287  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:32.287  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 17:08:32.297  1726  1726 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-31 17:08:32.297   258   258 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-31 17:08:32.297  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 17:08:32.307  1017  2951 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 17:08:32.307  1017  2951 D SecContentProvider2: mCursor = null
,08-31 17:08:32.307  1017  1218 D InputDispatcher: Focus entered window: 3177
,08-31 17:08:32.307  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 17:08:32.307  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 17:08:32.307  3177  3177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 17:08:32.317  1017  3238 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 17:08:32.317  1017  3238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 17:08:32.317  3177  3177 V ActivityThread: updateVisibility : ActivityRecord{3708c154 token=android.os.BinderProxy@16bf3d3b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-31 17:08:32.317  1017  3238 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:32.317  1017  3238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 17:08:32.317  1017  3238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 17:08:32.317  1017  1313 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 17:08:32.317  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 17:08:32.327  1017  1313 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6683 uid 10155
,08-31 17:08:32.327  1017  7406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 17:08:32.357  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-31 17:08:32.357  3177  3177 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16bf3d3b time:226043
,08-31 17:08:32.357  3819  3819 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 17:08:32.357  3819  4608 I iu.UploadsManager: num queued entries: 0
,08-31 17:08:32.357  3819  4608 I iu.UploadsManager: num updated entries: 0
08-31 17:08:32.357   278   979 D EnterpriseController: uids 10012
08-31 17:08:32.357   278   979 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 17:08:32.357   278   979 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,08-31 17:08:32.357  3819  4608 I iu.SyncManager: NEXT; no task
,08-31 17:08:32.367  1771  1771 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-31 17:08:32.377  3692  3692 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 17:08:32.377  3692  3692 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 17:08:32.387  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-31 17:08:32.387  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-31 17:08:32.387  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:32.387  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:32.387  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-31 17:08:32.387  3692  7405 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 17:08:32.387  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 17:08:32.387  3692  7405 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 17:08:32.397  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.397  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.407  1017  1047 W ActivityManager: mDVFSHelper.release()
08-31 17:08:32.407  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c8fb976 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:226090
,08-31 17:08:32.417  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.417  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 17:08:32.417  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:08:32.417  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 17:08:32.417  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 17:08:32.427  3692  7405 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-31 17:08:32.427  3692  7405 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,08-31 17:08:32.427  3692  7405 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,08-31 17:08:32.437  3692  7405 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,08-31 17:08:32.437  3692  7405 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-31 17:08:32.447  6538  6538 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:32.447  6538  6538 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 17:08:32.457  6538  6538 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 17:08:32.457  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 17:08:32.467  6465  6465 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-31 17:08:32.477  1017  1057 I art     : Explicit concurrent mark sweep GC freed 15911(1576KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 4.358ms total 291.978ms
,08-31 17:08:32.487  3255  7419 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-31 17:08:32.487  3255  7419 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-31 17:08:32.487  3255  7419 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 17:08:32.487  4137  4137 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-31 17:08:32.497  6097  6097 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
08-31 17:08:32.497  6097  6097 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-31 17:08:32.497  6097  6097 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 17:08:32.507  1933  7407 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} for uid -1, pid: 1933, getuid(): 10012
,08-31 17:08:32.527  6097  6097 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 17:08:32.527  6097  6097 I SA      : [OR] == isSIMCardReady false ==
,08-31 17:08:32.527  3255  7419 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
08-31 17:08:32.527  6097  6097 I SA      : [SCU] == networkStateCheck == true
,08-31 17:08:32.537  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.537  6097  6097 I SA      : [DM] getCountryCodeFromCSC : PL
08-31 17:08:32.537  6097  6097 I SA      : isChinaCountryCode : false
08-31 17:08:32.537  6097  6097 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 17:08:32.537  6097  6097 I SA      : [OR] == networkStateCheck true ==
,08-31 17:08:32.537  6097  6097 I SA      : [OR] GetMyCountryZoneTask
,08-31 17:08:32.537  6097  6097 I SA      : [OR] onReceive END
,08-31 17:08:32.537  1017  1057 D PackageManager: delete codoeFile: 
,08-31 17:08:32.537  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
08-31 17:08:32.537  6097  7423 I SA      : [SRS] prepareGetMyCountryZone
,08-31 17:08:32.537  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-31 17:08:32.547  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-31 17:08:32.547  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-31 17:08:32.547  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-31 17:08:32.547  3255  7419 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 17:08:32.547  3255  7419 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-31 17:08:32.547  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.547  1017  1017 D RCPManagerService: PackageReceiver onReceive()
08-31 17:08:32.557  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 17:08:32.557  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:32.557  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 17:08:32.557  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 17:08:32.557  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-31 17:08:32.557  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 17:08:32.557  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 17:08:32.557  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-31 17:08:32.557  1017  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-31 17:08:32.557  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 17:08:32.557  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 17:08:32.557  1017  3237 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-31 17:08:32.557  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 17:08:32.557  1017  3237 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
08-31 17:08:32.557  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-31 17:08:32.557  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 17:08:32.557  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-31 17:08:32.567  1017  1057 D PackageManager: result of delete: 1{50544213}
,08-31 17:08:32.567  1017  3237 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:32.567  1017  3237 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 17:08:32.567  1017  3237 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-31 17:08:32.567  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 17:08:32.567  3255  7419 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 17:08:32.567  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 17:08:32.567  1017  2758 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-31 17:08:32.577  6097  7423 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 17:08:32.577  6097  7423 I SA      : [SSP] query invoked
,08-31 17:08:32.577  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 17:08:32.577  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 17:08:32.577  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 17:08:32.577  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 17:08:32.587  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 17:08:32.587  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.587  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 17:08:32.587  3255  7419 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 17:08:32.587  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-31 17:08:32.587  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 17:08:32.587  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 17:08:32.587  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
08-31 17:08:32.587  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.587  1177  1177 D PanelView: There is/are notification(s) 
08-31 17:08:32.597  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 17:08:32.597  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 17:08:32.597  7391  7391 D AndroidRuntime: Shutting down VM
08-31 17:08:32.597  6097  7423 I SA      : [TPMU] GetMccFromDB : null
08-31 17:08:32.597  6097  7423 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 17:08:32.597  6097  7423 I SA      : [LBE] isSupportCheckDomainRegion : false
08-31 17:08:32.597  6097  7423 I SA      : [TPM] isNoProxy(default) : true
08-31 17:08:32.597  1017  3237 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-31 17:08:32.597  1017  3237 D SecContentProvider2: mCursor = null
08-31 17:08:32.607  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 17:08:32.607  1017  1057 D PackageManager: userId{-1}
08-31 17:08:32.607  1017  1057 D PackageManager: andCode{true}
08-31 17:08:32.607  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 17:08:32.607  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 17:08:32.607  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-31 17:08:32.607  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 17:08:32.617  6097  7423 E File    : fail readDirectory() errno=2
,08-31 17:08:32.617  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
,08-31 17:08:32.617  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-31 17:08:32.617  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-31 17:08:32.627  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 17:08:32.667  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-31 17:08:32.667  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
08-31 17:08:32.667  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,08-31 17:08:32.667  1177  1177 D PanelView: There is/are notification(s) 
08-31 17:08:32.667  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 17:08:32.667  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,08-31 17:08:32.667  7096  7096 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:08:32.667  1177  1177 D PanelView: There is/are notification(s) 
08-31 17:08:32.667  7096  7096 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 17:08:32.667  7096  7096 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-31 17:08:32.667  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
08-31 17:08:32.667  7096  7096 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 17:08:32.707  1017  2952 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-31 17:08:32.707  1017  2952 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-31 17:08:32.717  1017  2952 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:32.717  1017  2952 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 17:08:32.717  1017  2952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-31 17:08:32.717  6465  6465 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-31 17:08:32.727  6465  6465 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: exit::IDLE
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-31 17:08:32.727  6465  6465 D InitializeManagerStateMachine: entry::SUCCESS
08-31 17:08:32.727  6465  6465 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-31 17:08:32.737  6465  6465 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-31 17:08:32.737  6465  6465 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-31 17:08:32.737  6465  6465 D InitializeManagerStateMachine: exit::SUCCESS
08-31 17:08:32.737  6465  6465 D InitializeManagerStateMachine: entry::IDLE
,08-31 17:08:32.737  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-31 17:08:32.807  7391  7391 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 17:08:32.817  1017  2952 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,08-31 17:08:32.817  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 17:08:32 GMT+02:00 2016
,08-31 17:08:32.817  1017  1316 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 17:08:32.827  1017  1316 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 17:08:32.827  1017  1316 W ActivityManager: userId = 0, bbcId = -10000
08-31 17:08:32.827  1017  1316 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:32.827  1017  1316 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 17:08:32.827  3692  3692 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 17:08:32.827  1017  2951 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-31 17:08:32.827  1017  2951 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-31 17:08:32.827  1017  2951 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 17:08:32.837  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:32.837  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.837  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.837  1017  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:32.837  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-31 17:08:32.837  3692  3692 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 17:08:32.847  3692  3692 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-31 17:08:32.847  7432  7432 E Zygote  : MountEmulatedStorage()
,08-31 17:08:32.847  7432  7432 E Zygote  : v2
08-31 17:08:32.847  7432  7432 I libpersona: KNOX_SDCARD checking this for 10094
08-31 17:08:32.847  7432  7432 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:32.847  7432  7432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:32.847  1017  2951 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7432 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-31 17:08:32.857  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-31 17:08:32.857  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 17:08:32.857  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.857  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.857  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.857  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:32.857  7432  7432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:32.857  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-31 17:08:32.857  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-31 17:08:32.857  7432  7432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:32.857  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 17:08:32.867  7440  7440 E Zygote  : MountEmulatedStorage()
,08-31 17:08:32.867  7440  7440 E Zygote  : v2
08-31 17:08:32.867  7440  7440 I libpersona: KNOX_SDCARD checking this for 10044
08-31 17:08:32.867  7440  7440 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:32.867  1017  1042 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7440 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-31 17:08:32.867  7440  7440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:32.877  7440  7440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:32.877  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-31 17:08:32.877  7440  7440 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 17:08:32.877  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.877  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 17:08:32.877  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 17:08:32.877  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:32.907  7432  7432 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:32.907  7432  7432 D ActivityThread: Added TimaKeyStore provider
08-31 17:08:32.907  7463  7463 E Zygote  : MountEmulatedStorage()
,08-31 17:08:32.907  7463  7463 E Zygote  : v2
,08-31 17:08:32.907  7463  7463 I libpersona: KNOX_SDCARD checking this for 10149
08-31 17:08:32.907  7463  7463 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:32.907  1017  1042 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7463 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:08:32.917  7463  7463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:32.917  7463  7463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 17:08:32.917  7440  7440 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:32.917  7463  7463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 17:08:32.917  7440  7440 D ActivityThread: Added TimaKeyStore provider
,08-31 17:08:32.947  7463  7463 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 17:08:32.947  7463  7463 D ActivityThread: Added TimaKeyStore provider
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 17:08:32.947  7440  7440 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-31 17:08:32.947  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 17:08:32.947  5830  7447 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-31 17:08:32.957  5830  5830 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/seatbelt.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-31 17:08:32.957  3692  7431 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 17:08:32.957  5830  5830 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-31 17:08:32.957  5830  5830 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM discovered_threats WHERE package_name=?] disk I/O error
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:32.957  3692  7431 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:32.957  3692  7431 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 17:08:32.957  5830  5830 D AndroidRuntime: Shutting down VM
,08-31 17:08:32.957  3692  7431 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-31 17:08:32.957  5830  5830 E AndroidRuntime: FATAL EXCEPTION: main
08-31 17:08:32.957  5830  5830 E AndroidRuntime: Process: com.samsung.android.sm, PID: 5830
08-31 17:08:32.957  5830  5830 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.c(MalwareDatabaseHelper.java:207)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:192)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-31 17:08:32.957  5830  5830 E AndroidRuntime: 	... 9 more
,08-31 17:08:32.967  3692  7431 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-31 17:08:32.967  3692  7431 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 17:08:32.967  3692  3692 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 17:08:32.977  7032  7042 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
08-31 17:08:32.977  7032  7042 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
08-31 17:08:32.977  7032  7042 E DatabaseUtils: Writing exception to parcel
08-31 17:08:32.977  7032  7042 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-31 17:08:32.977  7032  7042 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 17:08:32.987  1017  2951 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-31 17:08:32.997  1017  7479 E DropBoxManagerService: Can't write: system_app_crash
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop203.tmp: open failed: EROFS (Read-only file system)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 17:08:32.997  1017  7479 E DropBoxManagerService: 	... 5 more
,08-31 17:08:33.007  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-31 17:08:33.007  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:33.007  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:33.007  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:33.007  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 17:08:33.017  7432  7432 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-31 17:08:33.017  7432  7432 D elm:15183: ELMEngine.ELMEngine( context ).
08-31 17:08:33.017  7432  7432 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-31 17:08:33.027  7480  7480 E Zygote  : MountEmulatedStorage()
,08-31 17:08:33.027  7480  7480 E Zygote  : v2
08-31 17:08:33.027  7480  7480 I libpersona: KNOX_SDCARD checking this for 1000
08-31 17:08:33.027  7480  7480 I libpersona: KNOX_SDCARD not a persona
,08-31 17:08:33.027  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-31 17:08:33.027  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 17:08:33.027  1017  1315 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-31 17:08:33.027  1017  1315 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 17:08:33.037  1017  1315 W ActivityManager: userId = 0, bbcId = -10000
,08-31 17:08:33.037  7463  7463 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-31 17:08:33.037  7463  7463 D ThemeInfoUtil: isCurrentFestival = false
08-31 17:08:33.037  1017  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 17:08:33.037  1017  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-31 17:08:33.037  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 17:08:33.037  5830  5830 I Process : Sending signal. PID: 5830 SIG: 9
,08-31 17:08:33.037  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
