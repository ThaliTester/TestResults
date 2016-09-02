#### Test 83444050ceb1988_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main,
09-02 19:07:42.023   292   292 E SMD     : DCD OFF
09-02 19:07:42.293  6358  6358 D AndroidRuntime: 
09-02 19:07:42.293  6358  6358 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 19:07:42.293  6358  6358 D AndroidRuntime: CheckJNI is OFF
09-02 19:07:42.293  6358  6358 D AndroidRuntime: readGMSProperty: start
09-02 19:07:42.293  6358  6358 D AndroidRuntime: readGMSProperty: already setted!!
09-02 19:07:42.293  6358  6358 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 19:07:42.293  6358  6358 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 19:07:42.293  6358  6358 D AndroidRuntime: readGMSProperty: end
09-02 19:07:42.293  6358  6358 D AndroidRuntime: addProductProperty: start
--------- beginning of system
09-02 19:07:42.393  1015  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-02 19:07:42.393  1015  1476 D BatteryService: level:95, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 19:07:42.393  1015  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 19:07:42.393  1015  1476 D BatteryService: stay LED for charging
09-02 19:07:42.393  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-02 19:07:42.403  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 19:07:42.403  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 19:07:42.403  1015  1015 I MotionRecognitionService: Plugged
09-02 19:07:42.403  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 19:07:42.403  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
09-02 19:07:42.403  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-02 19:07:42.413  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 19:07:42.413  2648  2750 D HeadsetStateMachine: Disconnected process message: 10
09-02 19:07:42.423  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:07:42.423  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:07:42.423  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:07:42.443  6358  6358 E AffinityControl: AffinityControl: registerfunction enter
09-02 19:07:42.463  6358  6358 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 19:07:42.473  1015  1333 E PersonaManagerService: inState():  stateMachine is null !!
09-02 19:07:42.473  1015  1333 I PersonaManagerService: PersonaId don't exist
09-02 19:07:42.473  1015  1333 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-02 19:07:42.473  1015  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 19:07:42.483  1015  1333 W ActivityManager: mDVFSHelper.acquire()
09-02 19:07:42.493  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-02 19:07:42.493  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-02 19:07:42.493  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:42.493  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:42.493  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:42.493  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:42.513  6369  6369 E Zygote  : MountEmulatedStorage()
09-02 19:07:42.513  6369  6369 E Zygote  : v2
09-02 19:07:42.513  6369  6369 I libpersona: KNOX_SDCARD checking this for 10155
09-02 19:07:42.513  6369  6369 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:42.513  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-02 19:07:42.513  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-02 19:07:42.513   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-02 19:07:42.513  1015  1333 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6369 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:07:42.513  1015  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-02 19:07:42.513  1015  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 19:07:42.513  6369  6369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:07:42.523  6369  6369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:07:42.523  6369  6369 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-02 19:07:42.533  1015  1333 D InputDispatcher: Focused application set to: xxxx
09-02 19:07:42.533  1015  1333 D InputDispatcher: Focus left window: 3127
09-02 19:07:42.543  6358  6358 D AndroidRuntime: Shutting down VM
09-02 19:07:42.543  6369  6369 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:07:42.553  6369  6369 D ActivityThread: Added TimaKeyStore provider
09-02 19:07:42.563  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-02 19:07:42.563  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 19:07:42.563  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 19:07:42.573  1015  2729 D PersonaManager: isKioskContainerExistOnDevice
09-02 19:07:42.603   257  1095 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-02 19:07:42.613   257  1819 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-02 19:07:42.613  3127  3127 V ActivityThread: updateVisibility : ActivityRecord{297d574 token=android.os.BinderProxy@17396bdb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-02 19:07:42.683  6369  6369 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-02 19:07:42.703  6369  6369 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6751-6753)
09-02 19:07:42.703  6369  6369 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:07:42.723  6369  6369 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d460970}
09-02 19:07:42.723  6369  6369 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:07:42.723  6369  6369 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 19:07:42.743  6358  6358 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 19:07:42.753  6369  6369 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 19:07:42.763  6369  6369 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-02 19:07:42.763  6369  6369 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 19:07:42.783  6369  6369 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-02 19:07:42.783  6369  6369 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-02 19:07:42.783  6369  6369 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-02 19:07:42.783  6369  6369 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 19:07:42.783  6369  6369 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 19:07:42.783  6369  6369 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 19:07:42.783  6369  6369 I Adreno-EGL: Local Branch: 
09-02 19:07:42.783  6369  6369 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 19:07:42.783  6369  6369 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 19:07:42.783  6369  6369 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 19:07:42.803  1015  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:07:42.923  6369  6396 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-02 19:07:42.963  6369  6369 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:42.983  6369  6369 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 19:07:42.983  6369  6369 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-02 19:07:42.993  6369  6369 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-02 19:07:42.993  6369  6369 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-02 19:07:43.003  6369  6369 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:43.003  6369  6369 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:43.043  6369  6409 D OpenGLRenderer: Render dirty regions requested: true
,09-02 19:07:43.053  1015  3046 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 19:07:43.053  1015  3046 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 19:07:43.053  1015  3046 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-02 19:07:43.053  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 19:07:43.053  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 19:07:43.063  6369  6369 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-02 19:07:43.063  6369  6369 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-02 19:07:43.073   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-02 19:07:43.083  1015  2729 D InputDispatcher: Focus entered window: 6369
,09-02 19:07:43.083  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 19:07:43.083  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 19:07:43.083  6369  6369 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-02 19:07:43.093  6369  6409 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 19:07:43.093  6369  6409 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-02 19:07:43.093  6369  6409 D OpenGLRenderer: Enabling debug mode 0
,09-02 19:07:43.123  6369  6369 V ActivityThread: updateVisibility : ActivityRecord{396cac1b token=android.os.BinderProxy@8df3315 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-02 19:07:43.153  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 19:07:43.153  1174  1174 D PanelView: There is/are notification(s) ,
09-02 19:07:43.153  1015  6412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:07:43.163  1802  1802 I SamsungIME: getCurrentCandidateView,
,09-02 19:07:43.173  1015  1045 I ActivityManager: Displayed Component not be shown by security: +594ms (total +1m2s200ms)
,09-02 19:07:43.173  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2140c8eb u0 com.test.thalitest/.MainActivity t129} time:177223
09-02 19:07:43.173  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-02 19:07:43.183   257   438 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-02 19:07:43.183   257  1819 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-02 19:07:43.183  6369  6369 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-02 19:07:43.183  6369  6369 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8df3315 time:177239
,09-02 19:07:43.233  6369  6369 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6369
,09-02 19:07:43.263  1802  1802 D SamsungIME: Dismiss ExpandCandiate
,09-02 19:07:43.343  6369  6369 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 19:07:43.403  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 19:07:43.443  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 19:07:43.453  6369  6414 D jxcore_app_log: JniHelper::setJavaVM(0xb79dc328), pthread_self() = -1208747880
,09-02 19:07:43.453  1802  1802 I SamsungIME: KeybaordView init() : load resources
,09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
,09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-02 19:07:43.463  6369  6414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4cd20b added. We now have 1 listener(s)
,09-02 19:07:43.473  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-02 19:07:43.473  6369  6414 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:07:43.473  6369  6414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:43.473  6369  6414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 19:07:43.483  6369  6414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f3bda6 added. We now have 1 listener(s)
,09-02 19:07:43.483  6369  6414 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:43.483  1802  1802 I SamsungIME: getCurrentKeyboard,
09-02 19:07:43.483  1802  1802 I SamsungIME: getTextKeyboard
09-02 19:07:43.483  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:43.483  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-02 19:07:43.483  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 19:07:43.483  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 19:07:43.483  6369  6414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 19:07:43.493  6369  6414 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:43.493  6369  6414 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-02 19:07:43.503  1802  1802 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 19:07:43.503  6369  6414 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:43.503  6369  6414 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:43.513  6369  6414 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 19:07:43.513  6369  6414 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:43.513  6369  6414 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:07:43.513  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:43.513  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:43.543  6369  6369 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 19:07:44.013  1802  6420 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 19:07:44.093  6369  6423 W jxcore-log: Initializing JXcore engine
09-02 19:07:44.093  6369  6423 W jxcore-log: JXcore engine is ready
,09-02 19:07:44.143  1925  1925 E audit   : type=1400 msg=audit(1472836064.143:205): avc:  denied  { ioctl } for  pid=6423 comm="Thread-1088" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-02 19:07:44.143  1925  1925 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:07:44.143  1925  1925 E audit   : type=1300 msg=audit(1472836064.143:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9d4008f8 items=0 ppid=310 ppcomm=main pid=6423 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1088" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-02 19:07:44.143  1925  1925 E audit   : type=1320 msg=audit(1472836064.143:205): 
,09-02 19:07:44.153  6369  6423 W jxcore-log: Starting JXcore engine
,09-02 19:07:44.263  6369  6423 W jxcore-log: Platform android,
09-02 19:07:44.263  6369  6423 W jxcore-log: 
09-02 19:07:44.263  6369  6423 W jxcore-log: Process ARCH arm
09-02 19:07:44.263  6369  6423 W jxcore-log: 
,09-02 19:07:44.463  6369  6423 I jxcore-log: JXcore Cordova bridge is ready!,
09-02 19:07:44.463  6369  6423 I jxcore-log: 
09-02 19:07:44.463  6369  6423 W jxcore-log: JXcore engine is started
,09-02 19:07:44.473  6369  6414 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,09-02 19:07:44.473  6369  6369 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 19:07:44.783  1015  2736 D SSRM:n  : SIOP:: AP = 300
,09-02 19:07:45.023   292   292 E SMD     : DCD OFF
,09-02 19:07:48.023   292   292 E SMD     : DCD OFF,
,09-02 19:07:49.433  1015  1047 I PowerManagerService: [PWL] Off : 105s ago
,09-02 19:07:50.003   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:51.003   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:51.023   292   292 E SMD     : DCD OFF,
,09-02 19:07:52.003   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:52.453  1015  2960 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:07:52.453  1015  2960 D BatteryService: level:95, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-02 19:07:52.453  1015  2960 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 19:07:52.453  1015  2960 D BatteryService: stay LED for charging
09-02 19:07:52.453  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:07:52.463  1015  1015 I MotionRecognitionService: Plugged
09-02 19:07:52.463  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 19:07:52.463  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 19:07:52.463  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 19:07:52.463  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 19:07:52.463  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
,09-02 19:07:52.473  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 19:07:52.473  2648  2750 D HeadsetStateMachine: Disconnected process message: 10
,09-02 19:07:52.483  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:07:52.493  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:07:52.493  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:07:52.543  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-02 19:07:53.003   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:54.003   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:54.023   292   292 E SMD     : DCD OFF,
,09-02 19:07:54.803  1015  2736 D SSRM:n  : SIOP:: AP = 320
,09-02 19:07:55.003   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-02 19:07:56.363  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-02 19:07:56.363  6369  6423 I jxcore-log: 
,09-02 19:07:56.363  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-02 19:07:56.363  6369  6423 I jxcore-log: 
,09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.373  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.373  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 19:07:56.373  6369  6423 I jxcore-log: 
,09-02 19:07:56.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 19:07:56.383  6369  6423 I jxcore-log: 
,09-02 19:07:57.023   292   292 E SMD     : DCD OFF,
,09-02 19:07:57.063  6369  6423 D executeNativeTests: Running unit tests
,09-02 19:07:57.143  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:57.143  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b added. We now have 2 listener(s)
,09-02 19:07:57.143  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:07:57.143  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:57.143  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:57.143  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:57.143  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 added. We now have 2 listener(s)
09-02 19:07:57.143  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:57.143  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:57.143  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.153  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:57.153  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.153  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:57.153  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.153  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:07:57.153  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:07:57.153  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 19:07:57.153  6369  6423 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 19:07:57.163  6369  6423 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:57.163  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:57.163  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:57.163  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.163  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.163  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.163  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:57.163  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b removed from the list
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.163  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 removed from the list
,09-02 19:07:57.163  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:57.163  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.163  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.163  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.163  6369  6423 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 19:07:57.163  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.163  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.163  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.163  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.163  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.163  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.163  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.163  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.163  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.173  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:07:57.173  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.173  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.173  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.173  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.173  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.173  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.173  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.173  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.173  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.173  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.173  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.173  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.173  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.183  6369  6423 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 19:07:57.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.183  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:57.183  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:57.183  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:57.183  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:57.183  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:57.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:57.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:57.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:57.193  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:57.193  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:57.203  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:57.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-02 19:07:57.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage,
09-02 19:07:57.203  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:07:57.203  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 19:07:57.213  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:57.213  2648  2964 D BtGatt.GattService: registerClient() - UUID=89cb2ebe-18f3-4982-8b1f-0ca6bb89eab7
,09-02 19:07:57.273  2648  2735 D BtGatt.GattService: onClientRegistered() - UUID=89cb2ebe-18f3-4982-8b1f-0ca6bb89eab7, clientIf=6,
,09-02 19:07:57.273  6369  6377 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:07:57.273  2648  2657 D BtGatt.GattService: start scan with filters
,09-02 19:07:57.273  2648  2746 D BtGatt.ScanManager: handling starting scan
,09-02 19:07:57.283  2648  2746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970,
09-02 19:07:57.283  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-02 19:07:57.283  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:57.283  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:57.283  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 19:07:57.283  2648  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:07:57.283  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.283  2648  2746 D BtGatt.ScanManager: allow scan with filters
09-02 19:07:57.283  2648  2746 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:07:57.283  2648  2746 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-02 19:07:57.293  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-02 19:07:57.293  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.293  2648  2746 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:57.293  2648  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:07:57.293  2648  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:07:57.293  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 19:07:57.293  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.303  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:57.303  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 19:07:57.303  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.313  6369  6423 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:07:57.313  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:57.313  6369  6423 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:07:57.323  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.323  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:57.323  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:57.323  2648  2657 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:07:57.323  2648  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:57.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:07:57.323  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:57.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:57.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:57.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:57.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:57.333  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.333  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:57.333  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.333  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.333  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.333  6369  6423 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 19:07:57.333  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.333  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:57.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.343  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:57.343  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:57.343  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:57.343  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.343  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:57.343  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:57.343  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:57.343  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:57.343  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:57.353  2648  2746 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 24
,09-02 19:07:57.353  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.353  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:57.353  2648  2746 D BtGatt.ScanManager: filter size is 1
09-02 19:07:57.353  2648  2746 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 19:07:57.363  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:57.363  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:57.363  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 19:07:57.363  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.363  2648  2746 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:07:57.363  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 19:07:57.363  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:57.363  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:57.373  2648  3005 D BtGatt.GattService: registerClient() - UUID=8181eaa4-b1ba-47c7-9009-dd4cd6709716
,09-02 19:07:57.373  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 19:07:57.373  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.373  2648  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:07:57.383  2648  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:07:57.383  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.423  2648  2735 D BtGatt.GattService: onClientRegistered() - UUID=8181eaa4-b1ba-47c7-9009-dd4cd6709716, clientIf=6
,09-02 19:07:57.423  6369  6377 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:07:57.423  2648  2657 D BtGatt.GattService: start scan with filters
,09-02 19:07:57.423  2648  2746 D BtGatt.ScanManager: handling starting scan
,09-02 19:07:57.423  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 19:07:57.423  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:57.423  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 19:07:57.423  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:57.423  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.423  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.423  2648  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 19:07:57.423  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.423  2648  2746 D BtGatt.ScanManager: allow scan with filters
,09-02 19:07:57.423  2648  2746 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:07:57.423  2648  2746 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-02 19:07:57.423  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:57.423  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:57.433  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 19:07:57.433  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.433  2648  2746 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:57.433  2648  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:07:57.433  6369  6423 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:07:57.433  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:57.433  6369  6423 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:07:57.433  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.433  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:57.433  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:57.433  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:57.433  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 19:07:57.443  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:57.443  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:57.443  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:57.443  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:57.443  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:57.443  2648  2657 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:57.443  2648  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:07:57.443  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.443  2648  3006 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:07:57.443  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 19:07:57.443  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:07:57.443  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 19:07:57.443  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.443  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:57.443  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:57.443  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.453  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:57.453  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.453  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.453  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.453  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.453  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.453  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:57.453  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.453  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.453  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.453  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.453  6369  6423 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 19:07:57.463  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.463  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:57.473  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:57.473  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:57.473  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:57.473  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:57.473  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:57.473  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:57.473  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:57.473  2648  2746 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 25
,09-02 19:07:57.473  2648  2746 D BtGatt.ScanManager: filter size is 1
09-02 19:07:57.473  2648  2746 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 19:07:57.473  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.473  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.473  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:57.483  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:07:57.483  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.483  2648  2746 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:07:57.483  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 19:07:57.483  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.483  2648  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:07:57.483  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:57.493  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:57.493  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:07:57.493  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:57.493  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:57.493  2648  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 19:07:57.493  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.493  2648  2657 D BtGatt.GattService: registerClient() - UUID=3334ec95-71ba-478d-abed-d0f141b136e3
,09-02 19:07:57.543  2648  2735 D BtGatt.GattService: onClientRegistered() - UUID=3334ec95-71ba-478d-abed-d0f141b136e3, clientIf=6
,09-02 19:07:57.543  6369  6378 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 19:07:57.543  2648  3006 D BtGatt.GattService: start scan with filters
,09-02 19:07:57.543  2648  2746 D BtGatt.ScanManager: handling starting scan
09-02 19:07:57.543  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:57.543  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:57.543  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:57.543  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:57.543  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.543  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:57.543  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:57.543  2648  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 19:07:57.553  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.553  2648  2746 D BtGatt.ScanManager: allow scan with filters
09-02 19:07:57.553  2648  2746 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:07:57.553  2648  2746 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 19:07:57.553  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-02 19:07:57.553  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 19:07:57.553  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.553  2648  2746 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:07:57.553  2648  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:07:57.563  6369  6423 I io.jxcore.node.ConnectionHelper: start: OK
09-02 19:07:57.563  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.563  6369  6423 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:57.563  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.563  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:57.563  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:57.563  2648  2964 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:57.563  2648  3005 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 19:07:57.563  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:57.563  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:07:57.573  2648  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:07:57.573  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.573  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:57.573  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:07:57.573  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:07:57.573  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:57.573  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:57.583  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-02 19:07:57.583  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.583  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.583  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.583  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:57.583  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:57.583  6369  6423 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:57.583  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.583  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.583  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.583  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.583  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:57.583  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
,09-02 19:07:57.583  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.583  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.583  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.583  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.593  6369  6423 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 19:07:57.593  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
,09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.593  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.593  2648  2746 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 26
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.593  2648  2746 D BtGatt.ScanManager: filter size is 1
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.593  2648  2746 D BtGatt.ScanManager: delete FilterIndex - 5
09-02 19:07:57.593  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-02 19:07:57.593  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.593  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.593  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.593  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.593  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.593  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.593  6369  6423 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 19:07:57.593  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.593  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.603  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop,
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
,09-02 19:07:57.603  6369  6423 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 19:07:57.603  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.603  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.603  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
,09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.603  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.603  2648  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.603  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.603  2648  2746 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:07:57.603  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:57.603  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:07:57.603  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 19:07:57.603  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.603  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.603  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.603  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.603  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.603  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.603  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.603  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.613  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.613  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:57.613  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.613  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.613  2648  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:07:57.613  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:57.613  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:57.613  6369  6423 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:07:57.613  2648  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:07:57.613  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:57.613  6369  6423 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:07:57.613  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:07:57.613  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 19:07:57.613  6369  6423 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:57.613  6369  6423 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 19:07:57.613  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:57.613  6369  6423 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:57.613  6369  6423 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 19:07:57.613  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:57.613  6369  6423 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:57.613  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 19:07:57.613  2648  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 19:07:57.613  2648  2735 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 19:07:57.623  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 19:07:57.623  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 19:07:57.623  6369  6423 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:57.623  6369  6423 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 19:07:57.623  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.623  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.623  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.623  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.623  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.623  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 19:07:57.623  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.623  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.623  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.623  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.623  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.623  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.623  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.623  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6423 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6434 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1152
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1152)
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 19:07:57.633  6369  6433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1152)
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 19:07:57.633  6369  6423 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:57.633  6369  6423 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:07:57.633  6369  6423 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:07:57.633  6369  6423 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 19:07:57.633  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.633  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.633  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.633  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.633  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.633  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.643  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.643  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.643  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:57.643  6369  6369 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.643  6369  6369 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:57.643  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.643  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:57.643  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.643  6369  6435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 19:07:57.643  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.643  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.643  6369  6435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.643  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.643  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.643  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.643  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.643  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6369 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.653  6369  6423 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 19:07:57.653  6369  6423 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:57.653  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:57.653  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.653  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.653  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.653  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.653  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.653  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.653  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.653  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.653  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.653  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.653  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.663  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.663  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:57.663  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:57.663  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:57.663  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.663  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.663  6369  6423 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379e901b not in the list
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.663  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:57.663  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.663  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.663  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:57.663  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:57.663  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:57.663  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4dc5b8 not in the list
09-02 19:07:57.663  6369  6423 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:57.663  6369  6423 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:57.663  6369  6423 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 19:07:57.663  6369  6423 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:07:57.663  6369  6423 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:07:57.663  6369  6423 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 19:07:57.663  6369  6423 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 19:07:57.673  6369  6423 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 19:07:57.673  6369  6423 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 19:07:57.673  6369  6423 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 19:07:57.673  6369  6423 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 19:07:57.673  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:57.673  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e2991da added. We now have 2 listener(s)
09-02 19:07:57.673  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:57.673  6369  6423 D BluetoothAdapter: enable()
09-02 19:07:57.673  6369  6423 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 19:07:57.673  1015  3046 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 19:07:57.673  1015  3046 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:07:57.673  1015  3046 D SecContentProvider2: mCursor = null
09-02 19:07:57.673  1015  3046 D WifiService: setWifiEnabled: true pid=6369, uid=10155
09-02 19:07:57.673  1015  3046 W ActivityManager: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:07:57.683  1015  3046 W WifiService: Failed getting userId using ActivityManagerNative
09-02 19:07:57.683  1015  3046 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:07:57.683  1015  3046 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 19:07:57.683  1015  3046 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:07:57.683  1015  3046 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:07:57.683  1015  3046 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:07:57.683  1015  3046 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 19:07:57.683  1015  3046 D SettingsProvider: name = wifi_on
09-02 19:07:57.683  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:57.683  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1abfb60b added. We now have 3 listener(s)
09-02 19:07:57.683  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:57.683  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:57.683  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@249a0ce8 added. We now have 4 listener(s)
09-02 19:07:57.683  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:57.693  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:57.693  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28f65f01 added. We now have 5 listener(s)
09-02 19:07:57.693  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:57.693  1015  1138 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 19:07:57.693  1015  1138 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:07:57.693  1015  1138 D SecContentProvider2: mCursor = null
,09-02 19:07:57.693  1015  1138 D WifiService: setWifiEnabled: false pid=6369, uid=10155
,09-02 19:07:57.693  1015  1138 D SettingsProvider: name = wifi_on
,09-02 19:07:57.703  1015  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 19:07:57.703  6369  6423 D BluetoothAdapter: disable()
09-02 19:07:57.703  1973  1973 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:07:57.703  1973  1973 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-02 19:07:57.703  1015  1218 D SettingsProvider: name = bluetooth_on
09-02 19:07:57.703  1973  1973 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:07:57.703  1973  1973 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 19:07:57.703  1015  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:07:57.713  2648  2730 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-02 19:07:57.713  2648  2730 D BluetoothAdapterProperties: Setting state to 13
09-02 19:07:57.713  2648  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 19:07:57.713  2648  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:07:57.713  2648  2730 D BluetoothAdapterService: updateAdapterState state is 13
,09-02 19:07:57.713  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:57.713  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:57.713  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:07:57.713  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.713  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.713  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:57.713  2648  2648 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-02 19:07:57.713  2648  2730 D BluetoothAdapterService: Autoconnection is available 
09-02 19:07:57.713  2648  2730 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 19:07:57.713  2648  2730 D BluetoothAdapterService: terminating service from this receiver
,09-02 19:07:57.713  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.723  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:57.723  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@80267e2, channel: 19, state: LISTENING
09-02 19:07:57.723  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@80267e2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bf5318a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f794773mSocket: android.net.LocalSocket@105aa630 impl:android.net.LocalSocketImpl@e5b92a9 fd:FileDescriptor[74]
09-02 19:07:57.723  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@105aa630 impl:android.net.LocalSocketImpl@e5b92a9 fd:FileDescriptor[74]
,09-02 19:07:57.723  1015  1129 E WifiNative-wlan0: do suspend true
09-02 19:07:57.723  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:57.723  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-02 19:07:57.723  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.723  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:57.723  1015  1218 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:07:57.723  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.723  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:57.723  2648  2730 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:07:57.723  2648  2730 D BluetoothAdapterProperties: mDiscovering is false
09-02 19:07:57.723  1015  1493 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:07:57.723  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:57.723  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-02 19:07:57.723  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:57.723  2648  2730 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 19:07:57.733  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.733  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:07:57.733  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:07:57.733  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:57.733  1174  1174 D BluetoothTile:  getBluetoothState : 13
09-02 19:07:57.733  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:07:57.733  1802  1802 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:07:57.743  1015  3213 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:07:57.743  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:07:57.743  1015  1218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 19:07:57.743  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:07:57.743  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:57.743  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:07:57.753  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:57.753  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:57.753  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 19:07:57.753  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:57.753  2648  2735 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:07:57.753  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:07:57.753  2648  2735 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:57.753  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:07:57.763  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 19:07:57.763  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:57.763  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:57.763  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:07:57.763  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 19:07:57.763  1015  3169 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:07:57.763  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-02 19:07:57.763  2648  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-02 19:07:57.763  2648  2730 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-02 19:07:57.763  2648  2730 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-02 19:07:57.763  2648  2730 E bt-btif : cmd socket is not created
,09-02 19:07:57.763  2648  5025 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 19:07:57.763  2648  2827 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 19:07:57.763  2648  2827 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 19:07:57.763  2648  2730 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 19:07:57.773  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.773  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:07:57.773  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:57.773  2648  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 19:07:57.773  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:57.773  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:57.773  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.773  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:07:57.783  1312  1312 D BluetoothPbap: Proxy object disconnected
09-02 19:07:57.783  1312  1312 D PbapServerProfile: Bluetooth service disconnected
,09-02 19:07:57.783  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b63202e, channel: 5, state: LISTENING
09-02 19:07:57.793  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b63202e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273a53fb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e96e7cfmSocket: android.net.LocalSocket@29fbf55c impl:android.net.LocalSocketImpl@631b065 fd:FileDescriptor[76]
09-02 19:07:57.793  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29fbf55c impl:android.net.LocalSocketImpl@631b065 fd:FileDescriptor[76]
,09-02 19:07:57.793  2648  2648 I BtOppRfcommListener: stopping Accept Thread
09-02 19:07:57.793  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a05113a, channel: 12, state: LISTENING
,09-02 19:07:57.793  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a05113a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@91918ad, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c4431ebmSocket: android.net.LocalSocket@27010b48 impl:android.net.LocalSocketImpl@2e91ede1 fd:FileDescriptor[79]
,09-02 19:07:57.793  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27010b48 impl:android.net.LocalSocketImpl@2e91ede1 fd:FileDescriptor[79]
,09-02 19:07:57.793  2648  5025 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 19:07:57.793  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:57.793  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:07:57.803  2648  2648 V BluetoothOppManager: cleanUp...
,09-02 19:07:57.803  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:57.803  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 19:07:57.803  1015  1218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-02 19:07:57.803  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.803  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.803  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.803  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.823  6442  6442 E Zygote  : MountEmulatedStorage(),
,09-02 19:07:57.823  6442  6442 E Zygote  : v2,
09-02 19:07:57.823  6442  6442 I libpersona: KNOX_SDCARD checking this for 10003,
09-02 19:07:57.823  6442  6442 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:57.823  1015  1218 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6442 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,09-02 19:07:57.833  6442  6442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 19:07:57.833  6442  6442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:07:57.843  6442  6442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 19:07:57.873  6442  6442 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.873  6442  6442 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.903  6442  6442 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-02 19:07:57.943  6442  6442 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-02 19:07:57.943  6442  6442 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-02 19:07:57.943  6442  6442 D UserAnalysis: Create SecureDbHelper
,09-02 19:07:57.953  6442  6442 D IntelligenceServiceApplication: onCreate()
,09-02 19:07:57.953  1015  3213 I ActivityManager: Killing 5101:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-02 19:07:57.963  1015  2960 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 19:07:57.963  6442  6442 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:57.963  2648  2827 W bt-btif : ag scb idx 1 not allocated
09-02 19:07:57.963  2648  2827 W bt-btif : ag scb idx 2 not allocated
09-02 19:07:57.963  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.963  2648  2827 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 19:07:57.963  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.963  2648  2947 I bt_userial_mct: exiting userial_read_thread
09-02 19:07:57.963  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.963  2648  2947 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 19:07:57.963  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.973  2648  2735 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 19:07:57.973  2648  2830 I bt_vendor: hw_epilog_process
,09-02 19:07:57.973  2648  2735 D bt_userial_mct: userial_close
09-02 19:07:57.973  2648  2735 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 19:07:57.983  6461  6461 E Zygote  : MountEmulatedStorage(),
09-02 19:07:57.983  1015  2960 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6461 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
09-02 19:07:57.983  6461  6461 E Zygote  : v2
,09-02 19:07:57.983  6461  6461 I libpersona: KNOX_SDCARD checking this for 10107
,09-02 19:07:57.983  6461  6461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:07:57.983  6461  6461 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:57.993  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-02 19:07:57.993  6461  6461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:07:57.993  6442  6442 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-02 19:07:57.993  6461  6461 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-02 19:07:58.003  6442  6442 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 19:07:58.013  6461  6461 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.013  6461  6461 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.153  6369  6369 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:07:58.203  1015  3213 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-02 19:07:58.203  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-02 19:07:58.213  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.213  1015  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.213  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.213  1944  1944 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 19:07:58.213  1944  1944 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.k.c(PG:583)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  6461  6461 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:58.263  6461  6461 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:58.263  1015  1138 I ActivityManager: Killing 5546:com.google.android.partnersetup/u0a15 (adj 15): empty #31
09-02 19:07:58.273  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:58.273  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-02 19:07:58.283  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 19:07:58.283  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.283  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.283  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.313  2648  2735 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 19:07:58.313  2648  2735 I bt_vendor: bluetooth satus is on
09-02 19:07:58.313  2648  2735 I bt_vendor: bt-vendor : resetting BT status
09-02 19:07:58.313  2648  2735 I bt_vendor: Starting hciattach daemon
09-02 19:07:58.313  2648  2735 I bt_vendor: try to set false
09-02 19:07:58.313  2648  2735 I bt_vendor: Starting hciattach daemon
09-02 19:07:58.313  2648  2735 I bt_vendor: try to set false
09-02 19:07:58.313  2648  2735 I bt_vendor: cleanup
09-02 19:07:58.313  2648  2827 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 19:07:58.313  2648  2735 I GKI_LINUX: GKI_exit_task 0 done
09-02 19:07:58.313  2648  2735 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 19:07:58.323  6461  6478 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-02 19:07:58.323  2648  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 19:07:58.323  2648  2730 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:07:58.323  2648  2730 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-02 19:07:58.323  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 19:07:58.323  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 19:07:58.333  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-02 19:07:58.333  1015  3045 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:58.333  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-02 19:07:58.333  1015  3045 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.333  1015  3045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.333  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:07:58.333  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:07:58.333  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:07:58.333  2648  2648 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 19:07:58.333  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-02 19:07:58.333  2648  2648 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 19:07:58.333  2648  2648 D BtGatt.GattService: stop()
09-02 19:07:58.333  2648  2648 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 19:07:58.333  1015  3046 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:58.333  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 19:07:58.343  1015  3046 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.343  1015  3046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.343  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:07:58.343  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 19:07:58.343  1015  3213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 19:07:58.343  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 19:07:58.343  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 19:07:58.343  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.343  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.343  1015  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.343  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.343  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:58.343  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.343  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.343  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.343  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.343  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-02 19:07:58.353  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:07:58.353  2648  2648 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:07:58.353  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:07:58.353  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
09-02 19:07:58.353  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:58.353  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.353  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.353  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.353  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.353  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:07:58.353  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:07:58.353  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 19:07:58.353  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:07:58.353  1312  1312 D HeadsetProfile: Bluetooth service disconnected
09-02 19:07:58.353  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:58.353  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.353  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.353  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.353  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.353  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 19:07:58.353  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 19:07:58.363  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:07:58.363  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:58.363  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.363  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.363  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.363  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.363  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.363  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 19:07:58.363  2648  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:07:58.363  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:58.363  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.363  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.363  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.363  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.363  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 19:07:58.363  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 19:07:58.363  2648  2730 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:07:58.373  1015  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:58.373  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.373  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.373  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.373  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:07:58.373  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:07:58.373  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-02 19:07:58.373  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-02 19:07:58.373  2648  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 19:07:58.373  2648  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-02 19:07:58.373  2648  2730 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-02 19:07:58.383  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-02 19:07:58.383  2648  2648 D A2dpService: Received stop request...Stopping profile...
,09-02 19:07:58.383  2648  2757 D A2dpStateMachine: Exit Disconnected: -1
,09-02 19:07:58.383  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.383  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:58.383  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 19:07:58.383  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-02 19:07:58.383  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:07:58.383  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 19:07:58.383  2888  2888 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:58.383  1312  1312 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:58.383  1312  1312 D A2dpProfile: Bluetooth service disconnected
09-02 19:07:58.383  2648  2648 D HidService: Received stop request...Stopping profile...
09-02 19:07:58.383  2648  2648 D HidService: Stopping Bluetooth HidService
09-02 19:07:58.383  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-02 19:07:58.383  2648  2648 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-02 19:07:58.383  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-02 19:07:58.393  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.393  1312  1312 D BluetoothInputDevice: Proxy object disconnected
,09-02 19:07:58.393  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:07:58.393  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 19:07:58.393  2648  2648 D HealthService: Received stop request...Stopping profile...
,09-02 19:07:58.393  1312  1312 D HidProfile: Bluetooth service disconnected
,09-02 19:07:58.393  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.393  2648  2648 D PanService: Received stop request...Stopping profile...
,09-02 19:07:58.403  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.403  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 19:07:58.403  2648  2648 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 19:07:58.403  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:07:58.403  1312  1312 D PanProfile: Bluetooth service disconnected
,09-02 19:07:58.403  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:07:58.403  1312  1312 D BluetoothMap: Proxy object disconnected
,09-02 19:07:58.403  1312  1312 D MapProfile: Bluetooth service disconnected
,09-02 19:07:58.403  2648  2648 D SapService: Received stop request...Stopping profile...
,09-02 19:07:58.403  2648  2648 D SapService: Stopping Bluetooth SapService
09-02 19:07:58.403  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
09-02 19:07:58.413  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 19:07:58.413  1312  1312 D SapProfile: Bluetooth service disconnected
09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-02 19:07:58.413  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 19:07:58.413  2648  2648 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 19:07:58.413  2648  2758 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 19:07:58.413  2648  2648 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:07:58.413  2648  2648 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-02 19:07:58.413  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 19:07:58.413  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:07:58.413  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 19:07:58.413  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.413  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:07:58.413  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-02 19:07:58.413  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 19:07:58.413  2648  2648 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-02 19:07:58.413  2648  2648 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-02 19:07:58.413  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##,
09-02 19:07:58.413  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-02 19:07:58.413  2648  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-02 19:07:58.413  2648  2730 D BluetoothAdapterProperties: Setting state to 10
09-02 19:07:58.413  2648  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:07:58.413  2648  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:07:58.413  2648  2730 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 19:07:58.413  2648  2730 D BluetoothAdapterService: Autoconnection is available 
09-02 19:07:58.413  2648  2730 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 19:07:58.413  2648  2730 I BluetoothAdapterState: Entering OffState
,09-02 19:07:58.413  1440  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:58.413  1440  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  2648  2964 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  2648  2964 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  1312  1326 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  1312  1326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  1312  1330 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:07:58.423  1431  1439 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  1431  1439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  1944  2118 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  1944  2118 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  1174  1187 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  1174  1187 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  6461  6473 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.423  6461  6473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.423  2888  2904 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:58.433  2888  2909 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.433  2888  2909 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.433  1312  1338 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:58.433  2648  2658 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:58.433  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.433  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.433  1454  1467 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.433  1454  1467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:58.433  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:58.433  1312  1330 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 19:07:58.433  6369  6377 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:58.433  6369  6377 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:58.433  6369  6377 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-02 19:07:58.433  6369  6377 D BluetoothLeAdvertiser: Exit stop advertising
09-02 19:07:58.433  6369  6377 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 19:07:58.443  6369  6377 D BluetoothLeScanner: Exiting stopAllScan
09-02 19:07:58.443  1312  1338 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:07:58.443  1312  1326 D Bluetoothsap: onBluetoothStateChange: up=false
,09-02 19:07:58.443  1312  1326 D Bluetoothsap: Unbinding service...
,09-02 19:07:58.443  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-02 19:07:58.443  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 19:07:58.453  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:58.453  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-02 19:07:58.453  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:07:58.453  2648  2735 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 19:07:58.453  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
09-02 19:07:58.453  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:07:58.453  1174  1722 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:07:58.453  2648  2648 I GKI_LINUX: GKI_exit_task 1 done
09-02 19:07:58.453  2648  2648 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-02 19:07:58.453  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:58.453  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-02 19:07:58.453  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:07:58.453  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:07:58.453  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
09-02 19:07:58.453  1174  1722 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:07:58.463  1015  1493 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 19:07:58.463  2648  2648 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 19:07:58.463  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:07:58.463  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:58.463  1802  1802 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 19:07:58.463  1944  2124 D BluetoothAdapter: 233686329: getState() :  mService = null. Returning STATE_OFF
09-02 19:07:58.463  1944  2124 D BluetoothAdapter: 233686329: getState() :  mService = null. Returning STATE_OFF
,09-02 19:07:58.463  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:58.463  2648  2648 I art     : System.exit called, status: 0
09-02 19:07:58.463  2648  2648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 19:07:58.463  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:58.463  1015  3046 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:07:58.463  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.463  1015  3046 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.463  1015  3046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.463  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.473  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:07:58.473  1015  3044 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:07:58.473  1015  3044 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.473  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.473  1015  3044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.473  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:07:58.483  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:58.483  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:07:58.483  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:58.483  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 19:07:58.493  1015  2960 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 19:07:58.493  1015  2960 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 19:07:58.493  1015  2960 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-02 19:07:58.493  1015  2960 W BroadcastQueue: android.os.TransactionTooLargeException
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-02 19:07:58.493  1015  2960 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:07:58.493  1015  2960 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-02 19:07:58.493  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.493  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.493  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.493  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.513  1015  2960 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6491 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 19:07:58.513  6491  6491 E Zygote  : MountEmulatedStorage()
09-02 19:07:58.513  6491  6491 E Zygote  : v2
09-02 19:07:58.513  6491  6491 I libpersona: KNOX_SDCARD checking this for 1002
09-02 19:07:58.513  6491  6491 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.513  6491  6491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:07:58.513  6491  6491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:07:58.513  6491  6491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 19:07:58.523   278   972 D CommandListener: Clearing all IP addresses on wlan0,
09-02 19:07:58.523  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
09-02 19:07:58.523  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:07:58.523  1944  4421 V NativeCrypto: Read error: ssl=0xb7ebc7d0: I/O error during system call, Connection timed out
09-02 19:07:58.523  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:58.523  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:07:58.523  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.533  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-02 19:07:58.533  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:07:58.533  1015  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:58.533  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:07:58.533  1015  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-02 19:07:58.533  1015  1124 D WifiP2pService: InactiveState{ what=131204 },
09-02 19:07:58.533  1015  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 19:07:58.533  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 19:07:58.533  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-02 19:07:58.543  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 19:07:58.553  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 19:07:58.553  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:58.553  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,09-02 19:07:58.553  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:07:58.553  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.553  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-02 19:07:58.553  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:58.553  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.553  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:58.553  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:58.563  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:07:58.563  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-02 19:07:58.563  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 19:07:58.563  1015  1124 D WifiP2pService: P2pDisablingState
09-02 19:07:58.563  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:07:58.563  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:07:58.563  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 },
09-02 19:07:58.563  1015  1129 E WifiNative-wlan0: do suspend true
09-02 19:07:58.563  1015  1124 D WifiP2pService: p2p socket connection lost
09-02 19:07:58.563  1015  1124 D WifiP2pService: P2pDisabledState
09-02 19:07:58.563  6491  6491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.573  6491  6491 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.573  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
09-02 19:07:58.573  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 19:07:58.573  1015  1045 D WifiDisplayController: disconnect
09-02 19:07:58.573  1015  1045 D WifiDisplayController: updateConnection
,09-02 19:07:58.573  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:07:58.573  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:07:58.573  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 19:07:58.583  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 19:07:58.583  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:07:58.583  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:07:58.583  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:07:58.583  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:07:58.583  1015  1333 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:07:58.583  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:07:58.593  6491  6491 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 19:07:58.593  6491  6491 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:07:58.623  6491  6491 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 19:07:58.643  1944  4421 I art     : Explicit concurrent mark sweep GC freed 61280(3MB) AllocSpace objects, 61(2MB) LOS objects, 39% free, 14MB/24MB, paused 1.354ms total 110.784ms
,09-02 19:07:58.643  1944  4421 V NativeCrypto: SSL shutdown failed: ssl=0xb7ebc7d0: I/O error during system call, Broken pipe
,09-02 19:07:58.643  1944  4421 E GCM     : Wifi connection closed with errorCode 20
,09-02 19:07:58.643  1015  1028 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-02 19:07:58.643  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:58.643  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:58.643  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 19:07:58.643  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:58.643  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-02 19:07:58.643  1015  2154 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 19:07:58.643  1015  2154 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,09-02 19:07:58.653  1015  2154 I qtaguid : Untagging socket 360
,09-02 19:07:58.653  1015  2154 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding GattService
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding HeadsetService
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding A2dpService
09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding HidService
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding HealthService
09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding PanService
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding SapService
,09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-02 19:07:58.653  6491  6491 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-02 19:07:58.663  6491  6491 D BtSettings.ProfileConfig: Adding SapClientService
09-02 19:07:58.663  6491  6491 D BtSettings.ProfileConfig: Adding HidDevService
,09-02 19:07:58.663  6491  6491 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-02 19:07:58.663  1015  3045 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 19:07:58.663  1015  3045 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.663  1015  3045 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.663  1015  3045 D SettingsProvider: selectionArgs: false
09-02 19:07:58.663  1015  3045 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.663  1015  3045 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.663  1015  3045 D SettingsProvider: ret = -1
,09-02 19:07:58.663  1015  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-02 19:07:58.663  1015  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.663  1015  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.663  1015  1493 D SettingsProvider: selectionArgs: false
09-02 19:07:58.663  1015  1493 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.663  1015  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.663  1015  1493 D SettingsProvider: ret = -1
,09-02 19:07:58.663  1015  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-02 19:07:58.663  1015  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.663  1015  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:07:58.663  1015  1218 D SettingsProvider: selectionArgs: false
09-02 19:07:58.663  1015  1218 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.663  1015  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.663  1015  1218 D SettingsProvider: ret = -1
,09-02 19:07:58.663  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-02 19:07:58.663  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.663  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:07:58.663  1015  1477 D SettingsProvider: selectionArgs: false
09-02 19:07:58.663  1015  1477 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.663  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.663  1015  1477 D SettingsProvider: ret = -1
,09-02 19:07:58.663  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 19:07:58.663  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.663  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.663  1015  1027 D SettingsProvider: selectionArgs: false
09-02 19:07:58.663  1015  1027 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.663  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  1027 D SettingsProvider: ret = -1
09-02 19:07:58.673  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-02 19:07:58.673  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.673  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.673  1015  1028 D SettingsProvider: selectionArgs: false
09-02 19:07:58.673  1015  1028 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.673  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  1028 D SettingsProvider: ret = -1
,09-02 19:07:58.673  1015  3046 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 19:07:58.673  1015  3046 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.673  1015  3046 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.673  1015  3046 D SettingsProvider: selectionArgs: false
09-02 19:07:58.673  1015  3046 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.673  1015  3046 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  3046 D SettingsProvider: ret = -1
,09-02 19:07:58.673  1015  3046 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-02 19:07:58.673  1015  3046 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 19:07:58.673  1015  3046 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:07:58.673  1015  3046 D SettingsProvider: selectionArgs: false
,09-02 19:07:58.673  1015  3046 D SettingsProvider: selectionArgs: 1002
,09-02 19:07:58.673  1015  3046 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  3046 D SettingsProvider: ret = -1
,09-02 19:07:58.673  1015  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:07:58.673  1015  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.673  1015  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:07:58.673  1015  1218 D SettingsProvider: selectionArgs: false
09-02 19:07:58.673  1015  1218 D SettingsProvider: selectionArgs: 1002
,09-02 19:07:58.673  1015  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 19:07:58.673  1015  1218 D SettingsProvider: ret = -1
,09-02 19:07:58.673  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
,09-02 19:07:58.673  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-02 19:07:58.673  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.673  1015  1476 D SettingsProvider: selectionArgs: false
,09-02 19:07:58.673  1015  1476 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.673  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  1476 D SettingsProvider: ret = -1
,09-02 19:07:58.673  1015  3213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 19:07:58.673  1015  3213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.673  1015  3213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.673  1015  3213 D SettingsProvider: selectionArgs: false
,09-02 19:07:58.673  1015  3213 D SettingsProvider: selectionArgs: 1002
09-02 19:07:58.673  1015  3213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.673  1015  3213 D SettingsProvider: ret = -1
09-02 19:07:58.683  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
09-02 19:07:58.683  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:07:58.683  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:07:58.683  1015  1027 D SettingsProvider: selectionArgs: false
09-02 19:07:58.683  1015  1027 D SettingsProvider: selectionArgs: 1002,
09-02 19:07:58.683  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:07:58.683  1015  1027 D SettingsProvider: ret = -1
,09-02 19:07:58.693  1015  2960 I ActivityManager: Killing 5637:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-02 19:07:58.693  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:58.693  1015  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:07:58.693  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.693  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.693  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:07:58.693  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.703  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:07:58.703  1944  6513 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 19:07:58.713  1015  1333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:07:58.713  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.713  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:07:58.713  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.723  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:07:58.723  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:07:58.723  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.723  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.723  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:58.723  3635  3635 I Hs20UtilService: Starting #8
,09-02 19:07:58.723  3635  3663 I Hs20UtilService: Message received 5007
,09-02 19:07:58.723  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:07:58.723  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:07:58.723  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:07:58.733  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-02 19:07:58.733  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:58.733  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:07:58.733  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,09-02 19:07:58.733  1015  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:07:58.733  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.733  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.733  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-02 19:07:58.743  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 19:07:58.743  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:07:58.743  1944  6513 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 19:07:58.743  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:07:58.743  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,09-02 19:07:58.743  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:58.743  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:07:58.743  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:07:58.743  1015  3213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-02 19:07:58.743  1015  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.743  1015  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.743  1015  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.743  1015  3213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.763  6514  6514 E Zygote  : MountEmulatedStorage()
09-02 19:07:58.763  6514  6514 E Zygote  : v2
09-02 19:07:58.763  6514  6514 I libpersona: KNOX_SDCARD checking this for 10068
09-02 19:07:58.763  6514  6514 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.763  1015  3213 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6514 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:58.763  6514  6514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:07:58.763  6514  6514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:07:58.763  6514  6514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.773  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.783  6514  6514 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.803  6514  6514 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:07:58.813  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:07:58.823  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 19:07:58.853  6514  6514 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:07:58.853  1015  3044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-02 19:07:58.853  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.853  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.853  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.853  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.873  1015  3044 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6529 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:58.873  6529  6529 E Zygote  : MountEmulatedStorage()
09-02 19:07:58.873  6529  6529 E Zygote  : v2
09-02 19:07:58.873  6529  6529 I libpersona: KNOX_SDCARD checking this for 10069
09-02 19:07:58.873  6529  6529 I libpersona: KNOX_SDCARD not a persona,
09-02 19:07:58.873  6529  6529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:07:58.873  6529  6529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:07:58.873  6529  6529 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 19:07:58.893  6529  6529 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.893  6529  6529 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.913  6529  6529 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:07:58.923  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.923  1015  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:07:58.923  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-02 19:07:58.923  1015  3044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-02 19:07:58.923  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.923  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.923  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.923  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.943  6544  6544 E Zygote  : MountEmulatedStorage(),
,09-02 19:07:58.943  6544  6544 E Zygote  : v2
,09-02 19:07:58.943  6544  6544 I libpersona: KNOX_SDCARD checking this for 10104
09-02 19:07:58.943  6544  6544 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.943  1015  3044 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6544 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,09-02 19:07:58.943  1015  3044 I ActivityManager: Killing 5844:com.sec.pcw.device/1000 (adj 15): empty #31,
,09-02 19:07:58.953  6544  6544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:07:58.953  6544  6544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:07:58.953  6544  6544 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.973  6544  6544 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.973  6544  6544 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.993  6544  6544 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 19:07:59.163  6544  6567 I Babel   : MmsConfig: mnc/mcc: 0/0
09-02 19:07:59.163  6544  6567 I Babel   : MmsConfig.loadMmsSettings
09-02 19:07:59.163  6544  6567 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-02 19:07:59.163  6544  6567 I Babel   : MmsConfig.loadFromDatabase
,09-02 19:07:59.173  6544  6567 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-02 19:07:59.173  6544  6567 I Babel   : MmsConfig.loadFromResources
,09-02 19:07:59.173  1015  1493 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-02 19:07:59.173  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-02 19:07:59.173  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.173  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:59.173  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 19:07:59.173  6544  6567 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 19:07:59.183  6544  6567 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-02 19:07:59.183  6544  6544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:59.233  6544  6544 I Babel_StickerModule: App launched.
,09-02 19:07:59.243   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-02 19:07:59.243   283   283 W QCamera2Factory: getCameraInfo: X
,09-02 19:07:59.253   283  1013 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,09-02 19:07:59.253   283  1013 W QCamera2Factory: getCameraInfo: X
,09-02 19:07:59.263  6544  6544 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:59.263  6544  6544 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 19:07:59.263  6544  6544 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 19:07:59.273  6544  6544 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-02 19:07:59.273  6544  6544 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-02 19:07:59.273  6544  6544 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-02 19:07:59.273  6544  6544 W AudioCapabilities: Unsupported mime audio/x-ima
,09-02 19:07:59.273  6544  6544 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 19:07:59.283  6544  6544 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 19:07:59.283  6544  6544 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 19:07:59.293  6544  6544 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 19:07:59.293  6544  6544 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-02 19:07:59.293  6544  6544 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 19:07:59.303  6544  6544 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 19:07:59.303  6544  6544 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-02 19:07:59.303  6544  6544 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-02 19:07:59.303  6544  6544 W VideoCapabilities: Unsupported mime video/mp43
,09-02 19:07:59.313  6544  6544 W VideoCapabilities: Unsupported mime video/sorenson
,09-02 19:07:59.313  6544  6544 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-02 19:07:59.333  6544  6544 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 19:07:59.353  1015  3169 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-02 19:07:59.353  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-02 19:07:59.353  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.353  1015  3169 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:59.353  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 19:07:59.363  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-02 19:07:59.363  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-02 19:07:59.363  1015  1333 I ActivityManager: Killing 5161:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-02 19:07:59.373  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:07:59.373  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:07:59.373  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.373  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.373  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.373  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.373   278   968 D EnterpriseController: uids 1000
09-02 19:07:59.373   278   968 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 19:07:59.373   278   968 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-02 19:07:59.373   278   972 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:07:59.373  1015  1131 E NetdConnector: NDC Command {53 network destroy 502} took too long (844ms)
,09-02 19:07:59.373  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-02 19:07:59.373  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-02 19:07:59.373  1015  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-02 19:07:59.383  1015  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-02 19:07:59.383  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 19:07:59.383  1973  1973 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:07:59.383  3789  6260 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-02 19:07:59.383  1174  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-02 19:07:59.383  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
09-02 19:07:59.383  1015  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:59.383  1015  2154 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:59.383  1015  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} },
09-02 19:07:59.383  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:07:59.383  1015  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-02 19:07:59.383  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:07:59.383  1015  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 19:07:59.383  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 19:07:59.393  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:07:59.393  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:07:59.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.393  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.393  1015  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 19:07:59.393  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:07:59.393  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:07:59.393  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-02 19:07:59.393  1015  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-02 19:07:59.403  1015  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-02 19:07:59.403  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:07:59.403  1015  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:59.403  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:07:59.403  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:59.403  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:07:59.403  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.403  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.403  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.403  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.403  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.403  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.403  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 19:07:59.403  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.403  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:07:59.403  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:59.413  1174  1174 D HotspotTile: onReceive : 0, 0
,09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:59.413  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:59.413  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:59.413  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:59.413  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:59.413  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:59.413  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:59.413  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-02 19:07:59.413  1015  1133 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:07:59.413  1015  1122 V NetworkStats: updateIfacesLocked()
09-02 19:07:59.413  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.413  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:07:59.413  1015  3045 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:07:59.413  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:07:59.413  1015  3045 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.413  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:07:59.413  1015  3045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.413  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:59.423  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 19:07:59.423  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 19:07:59.423  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.423  3635  3635 I Hs20UtilService: Starting #9
,09-02 19:07:59.423  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.423  1015  1122 V NetworkStats: performPollLocked() took 9ms
09-02 19:07:59.423  3635  3663 I Hs20UtilService: Message received 5007
,09-02 19:07:59.423  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.423  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.423  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 19:07:59.423  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:07:59.423  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.423  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.433  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:07:59.433  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:07:59.433  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:07:59.433  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:07:59.433  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:59.433  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:07:59.433  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:07:59.433  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.433  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.443  1015  3046 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:07:59.443  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:07:59.443  1015  3046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.443  1015  3046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.443  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:59.453  3635  3635 I Hs20UtilService: Starting #10
,09-02 19:07:59.453  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:07:59.453  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-02 19:07:59.453  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.453  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.453  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.453  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.463  1015  1028 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-02 19:07:59.463  6573  6573 E Zygote  : MountEmulatedStorage()
09-02 19:07:59.463  6573  6573 E Zygote  : v2
09-02 19:07:59.463  6573  6573 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:07:59.463  6573  6573 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:59.473  6573  6573 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:07:59.473  6573  6573 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:07:59.473  6573  6573 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:59.483  1973  1973 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:07:59.503  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:59.503  6573  6573 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:59.513  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.513  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.513  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.523  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.523  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.523  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.523  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.523  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.523  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.523  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.523  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.523  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.523  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.533  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.533  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.543  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.543  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.543  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:59.543  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:59.553  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:07:59.553  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 19:07:59.553  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:07:59.553  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:07:59.563  1015  1138 I ActivityManager: Killing 5863:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-02 19:07:59.563  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.563  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:59.563  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.573  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.573  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.573  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.573  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.573  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.573  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.583  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.583  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.583  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.583  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.593  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:07:59.593  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:59.593  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.593  1973  1973 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 19:07:59.593  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:07:59.593  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:07:59.593  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:07:59.593  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.593  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.593  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.603  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.603  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.603  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-02 19:07:59.603  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.603  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.613  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-02 19:07:59.613  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.613  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:59.613  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:59.613  1973  1973 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-02 19:07:59.613  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.613  1973  1973 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-02 19:07:59.613  1973  1973 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-02 19:07:59.613  1973  1973 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 19:07:59.613  1973  1973 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-02 19:07:59.613  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.613  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:07:59.623  1015  1133 D Tethering: InitialState.processMessage what=4
,09-02 19:07:59.623  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.623  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.623  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:07:59.623  1015  1133 E Tethering: No numeric data
,09-02 19:07:59.623  1015  1129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-02 19:07:59.623  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:07:59.623  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:07:59.623  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.623  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:07:59.623  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:07:59.623  1015  1133 D Tethering: clearTetheredNotification()
09-02 19:07:59.623  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:59.623  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:07:59.633  1015  1122 V NetworkStats: performPollLocked() took 5ms
09-02 19:07:59.633  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.633  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.633  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.633  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:07:59.633  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.633  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.683   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8da57c8
09-02 19:07:59.683   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-02 19:07:59.683   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
09-02 19:07:59.683   271   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1193650888)
,09-02 19:07:59.723   271   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-02 19:07:59.723   271   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-02 19:07:59.723   271   313 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1193650888) wakelock released: 1, error no: 0
09-02 19:07:59.723   271   313 I rmt_storage: 
,09-02 19:07:59.723   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8da57c8,
,09-02 19:07:59.803  1973  1973 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 19:07:59.863  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:07:59.863  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:07:59.863  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:07:59.863  1973  1973 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-02 19:07:59.893  1015  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:59.903  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:59.903  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-02 19:07:59.923  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:59.933  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:59.933  3127  3127 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-02 19:07:59.933  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-02 19:07:59.933  3127  3127 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-02 19:07:59.933  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.933  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.933  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.933  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.953  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6604 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 19:07:59.953  6604  6604 E Zygote  : MountEmulatedStorage(),
09-02 19:07:59.953  6604  6604 E Zygote  : v2
,09-02 19:07:59.953  6604  6604 I libpersona: KNOX_SDCARD checking this for 1000
,09-02 19:07:59.953  6604  6604 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:59.973  6604  6604 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:07:59.973  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-02 19:07:59.973  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:07:59.973  1015  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 19:07:59.973  6604  6604 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:07:59.973  6604  6604 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:07:59.973  6544  6544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:59.983  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:59.983  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:07:59.983  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.983  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:59.983  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.983  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:59.983  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.983  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-02 19:07:59.983  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:07:59.983   310   310 I art     : Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.200ms total 32.376ms
,09-02 19:07:59.983  6604  6604 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:07:59.993  6604  6604 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:59.993  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.993  1174  1174 D HotspotTile: onReceive : 1, 0
,09-02 19:07:59.993  1944  2124 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:59.993  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:59.993  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:00.003  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:00.003   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 17.440ms,
,09-02 19:08:00.023  6604  6604 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-02 19:08:00.023  6604  6604 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-02 19:08:00.023  6604  6604 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-02 19:08:00.023   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 17.009ms
,09-02 19:08:00.033   292   292 E SMD     : DCD OFF
,09-02 19:08:00.033  6604  6604 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 19:08:00.033  6604  6604 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-02 19:08:00.033  6604  6604 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 19:08:00.033  6604  6604 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:00.033  1015  1218 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-02 19:08:00.033  1015  1218 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-02 19:08:00.033  6604  6619 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-02 19:08:00.033  1015  1218 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
09-02 19:08:00.033  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.033  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.033  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.033  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.053  6621  6621 E Zygote  : MountEmulatedStorage(),
09-02 19:08:00.053  1015  1218 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6621 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:08:00.053  6621  6621 E Zygote  : v2
09-02 19:08:00.053  6621  6621 I libpersona: KNOX_SDCARD checking this for 10111
09-02 19:08:00.053  6621  6621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:08:00.053  6621  6621 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:00.053  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-02 19:08:00.053  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.053  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.053  6621  6621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:00.053  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.053  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.053  6621  6621 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.073  6630  6630 E Zygote  : MountEmulatedStorage(),
09-02 19:08:00.073  6630  6630 E Zygote  : v2
09-02 19:08:00.073  6630  6630 I libpersona: KNOX_SDCARD checking this for 10009
09-02 19:08:00.073  6630  6630 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.073  6630  6630 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.073  1015  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6630 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:00.073  6630  6630 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:00.073  6630  6630 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-02 19:08:00.073  1015  1040 I ActivityManager: Killing 5571:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31,
09-02 19:08:00.083  1723  1723 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-02 19:08:00.083  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-02 19:08:00.083  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 19:08:00.083  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.083  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.083  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 19:08:00.083  6621  6621 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-02 19:08:00.093  6621  6621 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.103  6650  6650 E Zygote  : MountEmulatedStorage()
,09-02 19:08:00.103  6650  6650 E Zygote  : v2
09-02 19:08:00.103  6650  6650 I libpersona: KNOX_SDCARD checking this for 10145
09-02 19:08:00.103  6650  6650 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.103  6650  6650 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.103  6650  6650 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:08:00.103  6650  6650 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.103  1015  1040 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6650 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,09-02 19:08:00.113  6630  6630 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:00.113  6630  6630 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.123  1723  1723 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-02 19:08:00.123  1723  1723 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-02 19:08:00.123  1723  1723 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-02 19:08:00.123  1723  1723 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 19:08:00.123  1723  1723 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 19:08:00.133  1723  1723 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-02 19:08:00.133  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-02 19:08:00.133  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.133  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.133  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.133  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.143  6650  6650 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.143  6650  6650 D ActivityThread: Added TimaKeyStore provider
09-02 19:08:00.143  1295  1631 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,09-02 19:08:00.163  6667  6667 E Zygote  : MountEmulatedStorage(),
,09-02 19:08:00.163  1015  1027 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6667 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:08:00.163  6667  6667 E Zygote  : v2
09-02 19:08:00.163  6667  6667 I libpersona: KNOX_SDCARD checking this for 10081
09-02 19:08:00.163  6667  6667 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:00.163  6667  6667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.173  6667  6667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:00.173  6667  6667 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.193  1723  1723 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-02 19:08:00.203  6667  6667 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.203  6667  6667 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.203  6650  6650 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-02 19:08:00.203  6650  6650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:00.203  6650  6650 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:00.203  6650  6650 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:00.203  6650  6650 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:00.223  6621  6621 I MusicStore: Database version: 108
,09-02 19:08:00.243  1015  2729 I ActivityManager: Killing 5877:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-02 19:08:00.253  3670  3670 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 19:08:00 GMT+02:00 2016
,09-02 19:08:00.253  1015  2933 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 19:08:00.253  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.253  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.253  1015  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:00.253  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 19:08:00.253  1015  3213 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:00.263  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 19:08:00.263  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.263  1015  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.263  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.263  3670  3670 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-02 19:08:00.273  1015  1333 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-02 19:08:00.273  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.273  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.273  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.273  1015  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.283  3670  3670 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-02 19:08:00.293  1015  1333 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6689 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,09-02 19:08:00.293  3670  3670 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-02 19:08:00.293  6689  6689 E Zygote  : MountEmulatedStorage()
09-02 19:08:00.293  6689  6689 E Zygote  : v2
,09-02 19:08:00.293  6689  6689 I libpersona: KNOX_SDCARD checking this for 10034
09-02 19:08:00.293  6689  6689 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.293  6689  6689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.293  6689  6689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:08:00.293  6689  6689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.303  3670  3670 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 19:08:00.303  3670  6688 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 19:08:00.313  3670  6688 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 19:08:00.313  1015  1218 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.323  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.323  6689  6689 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.333  3670  6688 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-02 19:08:00.333  3670  6688 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-02 19:08:00.333  1015  2960 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.343  3670  3670 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-02 19:08:00.343  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-02 19:08:00.353  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.353  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.353  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.353  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.363  6708  6708 E Zygote  : MountEmulatedStorage()
09-02 19:08:00.363  6708  6708 I libpersona: KNOX_SDCARD checking this for 10113
09-02 19:08:00.363  6708  6708 E Zygote  : v2
09-02 19:08:00.363  6708  6708 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.363  6708  6708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.363  1015  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6708 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:00.363  6708  6708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:00.363  6708  6708 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.383  6689  6689 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-02 19:08:00.383  1015  3169 I ActivityManager: Killing 5605:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-02 19:08:00.393  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.403  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.403  6708  6708 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.403  6621  6621 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-02 19:08:00.413  1015  2729 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.413  6621  6621 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 19:08:00.423  3215  6726 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-02 19:08:00.423  3215  6726 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-02 19:08:00.433  1015  1042 D Tethering: interfaceRemoved wlan0
,09-02 19:08:00.433  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 19:08:00.433  3215  6726 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-02 19:08:00.433  3215  6726 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-02 19:08:00.433  3215  6726 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-02 19:08:00.443  5911  5911 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-02 19:08:00.453  1015  3044 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-02 19:08:00.453  1015  3044 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.453  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.453  1015  3044 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-02 19:08:00.453  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-02 19:08:00.463  6093  6093 I SA      : [DM] init START
,09-02 19:08:00.463  6093  6093 I SA      : [DM] This device is not a Vodafone
,09-02 19:08:00.483  5911  6728 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-02 19:08:00.483  6093  6093 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 19:08:00.483  6093  6093 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-02 19:08:00.493  6002  6014 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-02 19:08:00.493  6093  6093 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-02 19:08:00.493  6093  6093 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-02 19:08:00.493  6093  6093 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-02 19:08:00.493  6093  6093 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-02 19:08:00.493  6093  6093 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-02 19:08:00.503  6093  6093 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-02 19:08:00.513  6621  6621 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-02 19:08:00.513  1015  2729 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.523  6002  6014 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-02 19:08:00.523  6002  6014 D BadgeProvider: sendNotify, [notify] : null
09-02 19:08:00.523  6002  6014 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-02 19:08:00.523  6002  6014 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 19:08:00.523  6002  6014 D BadgeProvider: update, [UpdateCount] : 1
,09-02 19:08:00.523  1478  1478 D Launcher.Model: reloadBadges entered.
,09-02 19:08:00.523  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.523  6093  6093 I SA      : [SCU] isHaveSA() - false
09-02 19:08:00.523  6093  6093 I SA      : support phone number id : false
09-02 19:08:00.523  6093  6093 I SA      : [DM] Supports Ref Jpn : true
09-02 19:08:00.523  6093  6093 I SA      : [DM] init END
,09-02 19:08:00.523  6093  6093 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-02 19:08:00.523  6093  6093 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-02 19:08:00.523  6093  6093 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 19:08:00.543  6093  6093 I SA      : [SLFUCHKMGR] constructor called
,09-02 19:08:00.543  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.553  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:00.563  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:00.563  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:00.563  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:00.563  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:00.563  1015  1042 D Tethering: interfaceRemoved p2p0
,09-02 19:08:00.563  1015  3046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-02 19:08:00.563  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 19:08:00.563  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.563  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.563  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.563  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.563  6621  6621 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 19:08:00.573  6093  6093 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 19:08:00.573  6093  6093 I SA      : [OR] == isSIMCardReady false ==,
09-02 19:08:00.583  6621  6621 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@80a31c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
,09-02 19:08:00.583  6621  6621 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-02 19:08:00.583  6736  6736 I libpersona: KNOX_SDCARD checking this for 10159
,09-02 19:08:00.583  6621  6621 D AndroidMusic: GMSCore installation verified
09-02 19:08:00.583  6736  6736 I libpersona: KNOX_SDCARD not a persona,
09-02 19:08:00.583  6736  6736 E Zygote  : MountEmulatedStorage()
09-02 19:08:00.583  6736  6736 E Zygote  : v2
09-02 19:08:00.593  1015  3046 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6736 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:08:00.583  6736  6736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:08:00.583  6736  6736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:00.583  6736  6736 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-02 19:08:00.593  6093  6093 I SA      : [SCU] == networkStateCheck == false
,09-02 19:08:00.593  6093  6093 I SA      : [OR] onReceive END
,09-02 19:08:00.593  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:00.613  6736  6736 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.613  6736  6736 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.643  1015  2933 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:00.643  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-02 19:08:00.643  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.643  1015  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.643  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.663  6621  6621 I ConfigStore: Config Database version: 1
,09-02 19:08:00.663  1015  2960 I ActivityManager: Killing 5929:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-02 19:08:00.673  1015  2933 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:00.673  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.673  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:00.673  1015  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.673  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:00.683  3789  3789 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 19:08:00.693  3789  4614 I iu.UploadsManager: num queued entries: 0
,09-02 19:08:00.693  3789  4614 I iu.UploadsManager: num updated entries: 0
,09-02 19:08:00.693  3789  4614 I iu.SyncManager: NEXT; no task
,09-02 19:08:00.723  1015  3045 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 19:08:00.723  1015  3045 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:08:00.723  1015  3045 D SecContentProvider2: mCursor = null
,09-02 19:08:00.723  1015  3045 W WifiService: Failed getting userId using ActivityManagerNative,
09-02 19:08:00.723  1015  3045 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:00.723  1015  3045 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 19:08:00.723  1015  3045 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:08:00.723  1015  3045 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:08:00.723  1015  3045 W WifiService: ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:08:00.723  1015  3045 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 19:08:00.723  1015  3045 D WifiService: setWifiEnabled: true pid=6369, uid=10155
09-02 19:08:00.723  1015  3045 D SettingsProvider: name = wifi_on
,09-02 19:08:00.723  1015  3045 W ActivityManager: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:08:00.743  1015  3213 I art     : Explicit concurrent mark sweep GC freed 68213(4MB) AllocSpace objects, 32(560KB) LOS objects, 33% free, 27MB/41MB, paused 5.569ms total 220.469ms
,09-02 19:08:00.763  1015  2729 I ActivityManager: Killing 5827:com.android.mms/u0a46 (adj 15): empty #31
,09-02 19:08:00.773   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 19:08:00.773   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:00.783  6708  6754 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 19:08:00.783   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 19:08:00.783   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:00.783  6708  6754 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 19:08:00.793   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 19:08:00.793   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:00.793  6621  6621 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-02 19:08:00.793   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 19:08:00.793   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:00.793  6621  6621 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-02 19:08:00.803   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-02 19:08:00.803   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:00.803  6621  6621 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
09-02 19:08:00.803   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 19:08:00.803   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 19:08:00.803  6708  6758 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
09-02 19:08:00.803   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 19:08:00.803   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 19:08:00.803  1015  2729 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-02 19:08:00.803  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.803  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:00.803  6708  6758 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 19:08:00.813  1015  2729 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.813  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.823  1015  1333 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 19:08:00.823  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-02 19:08:00.823  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.823  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.823  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.853  1015  2933 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:00.853  1015  3169 D CountryDetector: No listener is left
,09-02 19:08:00.863  1015  2729 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:00.863  1015  3169 I AudioService: getStreamVolume 3 index 0
,09-02 19:08:00.873  6621  6621 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-02 19:08:00.883  6621  6621 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-02 19:08:00.903  1015  2933 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:00.903  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 19:08:00.903  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.903  1015  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.903  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.903  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.903  1015  3045 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-02 19:08:00.903  1015  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 19:08:00.903  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.903  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.903  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.903  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.913  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.913  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.913  1015  1477 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 19:08:00.913  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.913  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:00.913  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.913  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:00.913  1015  2729 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:00.923  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-02 19:08:00.933  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.933  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.933  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.933  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.943  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6776 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:00.943  6776  6776 E Zygote  : MountEmulatedStorage()
,09-02 19:08:00.943  6776  6776 E Zygote  : v2
09-02 19:08:00.943  6776  6776 I libpersona: KNOX_SDCARD checking this for 10002
,09-02 19:08:00.943  6776  6776 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.943  6776  6776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:00.953  6776  6776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:00.953  6776  6776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.963  1015  3044 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-02 19:08:00.963  1015  3044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-02 19:08:00.963  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:00.963  1015  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.963  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-02 19:08:00.973  6776  6776 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.973  6776  6776 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.973  1015  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:00.973  6621  6621 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-02 19:08:00.973  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.973  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:00.973  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 19:08:00.983  1015  1138 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:00.983  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 19:08:00.983  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.983  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:00.993  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:01.003  6708  6708 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-02 19:08:01.013  6708  6708 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5064-5065)
09-02 19:08:01.013  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 19:08:01.023  1015  1028 I ActivityManager: Killing 6021:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-02 19:08:01.023  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {631b065}
,09-02 19:08:01.023  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:08:01.023  6708  6708 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 19:08:01.033  1015  3046 I ActivityManager: Killing 6038:com.wsomacp/u0a25 (adj 15): empty #31
,09-02 19:08:01.043  1015  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-02 19:08:01.043  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.043  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.043  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.043  1015  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.043  6708  6708 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 19:08:01.043  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:08:01.053  6708  6708 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 19:08:01.053  6797  6797 E Zygote  : MountEmulatedStorage()
,09-02 19:08:01.053  6797  6797 E Zygote  : v2
09-02 19:08:01.053  6797  6797 I libpersona: KNOX_SDCARD checking this for 1000
,09-02 19:08:01.053  6797  6797 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:01.053  6797  6797 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-02 19:08:01.053  1015  1477 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6797 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,09-02 19:08:01.063  6797  6797 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:08:01.063  6797  6797 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:01.083  6797  6797 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:01.083  6797  6797 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:01.083  6708  6708 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-02 19:08:01.083  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-02 19:08:01.083  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-02 19:08:01.093  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 19:08:01.093  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 19:08:01.093  6708  6708 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 19:08:01.093  6708  6708 I Adreno-EGL: Local Branch: 
09-02 19:08:01.093  6708  6708 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 19:08:01.093  6708  6708 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 19:08:01.093  6708  6708 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 19:08:01.123  6797  6797 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-02 19:08:01.153  6708  6823 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 19:08:01.153  6708  6708 I NSApplication: Starting up...
,09-02 19:08:01.163  1015  2960 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-02 19:08:01.173  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.173  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.173  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.173  1015  2960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.183  6828  6828 E Zygote  : MountEmulatedStorage(),
09-02 19:08:01.183  6828  6828 E Zygote  : v2,
,09-02 19:08:01.183  6828  6828 I libpersona: KNOX_SDCARD checking this for 10120
09-02 19:08:01.183  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:08:01.183  6828  6828 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:01.183  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:01.183  1015  2960 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6828 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:08:01.183  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-02 19:08:01.183  1015  2960 I ActivityManager: Killing 5951:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
09-02 19:08:01.183  1015  2960 I ActivityManager: Killing 6056:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
,09-02 19:08:01.213  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:01.213  6828  6828 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:01.223  6828  6828 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 19:08:01.233  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 19:08:01.233  1015  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 19:08:01.263  6797  6797 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-02 19:08:01.273  6797  6797 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-02 19:08:01.273  6797  6797 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:01.283  6797  6797 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 19:08:01.283  6797  6797 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-02 19:08:01.283  6797  6797 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-02 19:08:01.283  1015  1027 I ActivityManager: Killing 5894:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-02 19:08:01.543  1015  1218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-02 19:08:01.543  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.543  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.543  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.543  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.563  1015  1218 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6855 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-02 19:08:01.563  6855  6855 E Zygote  : MountEmulatedStorage()
09-02 19:08:01.563  6855  6855 E Zygote  : v2
09-02 19:08:01.563  6855  6855 I libpersona: KNOX_SDCARD checking this for 10125
09-02 19:08:01.563  6855  6855 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:01.563  1015  1218 I ActivityManager: Killing 6135:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
09-02 19:08:01.563  6855  6855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:01.563  6855  6855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:01.563  6855  6855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:01.583  6855  6855 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:01.583  6855  6855 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:01.593   310   310 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 31.008ms
,09-02 19:08:01.593  1015  1042 D Tethering: interfaceAdded wlan0
,09-02 19:08:01.593  1015  1133 E Tethering: No numeric data
09-02 19:08:01.593  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:01.593  1015  1133 D Tethering: clearTetheredNotification()
,09-02 19:08:01.603  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:01.603  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:01.603  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:01.603  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:01.603  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.603  1015  1133 D Tethering: InitialState.processMessage what=4
,09-02 19:08:01.603  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:01.603  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:01.603  1015  1133 E Tethering: No numeric data
09-02 19:08:01.603  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:01.603  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:08:01.603  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.603  1015  1122 V NetworkStats: performPollLocked() took 4ms
,09-02 19:08:01.603  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:08:01.603  1015  1133 D Tethering: clearTetheredNotification()
,09-02 19:08:01.603  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:01.603   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.846ms
,09-02 19:08:01.603  1174  1174 D HotspotTile: updateTetherState():false, false
09-02 19:08:01.603  1015  1042 D Tethering: interfaceAdded p2p0
,09-02 19:08:01.603  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-02 19:08:01.613  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:01.613  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:01.613  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:01.613  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.613  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:01.613   278   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 19:08:01.613   278   972 D SoftapController: Softap fwReload - Ok
,09-02 19:08:01.613  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.613  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.613  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:01.613  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:01.623   278   972 D CommandListener: Setting iface cfg
09-02 19:08:01.623   278   972 D CommandListener: Trying to bring down wlan0
,09-02 19:08:01.623   278   972 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:08:01.623  1015  1122 V NetworkStats: performPollLocked() took 4ms
09-02 19:08:01.623  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.623  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.623  6855  6855 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:01.623  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:01.623  6855  6855 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 19:08:01.623  6855  6855 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:08:01.623  1015  1129 E WifiHW  : supplicant_name : p2p_supplicant,
09-02 19:08:01.623   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 18.514ms
,09-02 19:08:01.633  6855  6855 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
09-02 19:08:01.633  6855  6855 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-02 19:08:01.643  6855  6855 I QuickConnect: PeriphStartReceiver.onReceive - no need to start,
09-02 19:08:01.643  1015  1027 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-02 19:08:01.643  1015  1027 I ActivityManager: Killing 6157:com.samsung.helphub/1000 (adj 15): empty #31
,09-02 19:08:01.653  1015  3169 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:01.653  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:01.653  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:01.653  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:01.653  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:01.653  3635  3635 I Hs20UtilService: Starting #11
,09-02 19:08:01.653  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:01.653  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:01.653  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:01.653  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:01.653  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:01.683  6871  6871 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 19:08:01.683  6871  6871 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 19:08:01.683  6871  6871 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 19:08:01.693  6871  6871 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-02 19:08:01.693   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6871,
09-02 19:08:01.693   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 19:08:01.693  6871  6871 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 19:08:01.693  6871  6871 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:01.693  6871  6871 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-02 19:08:01.693  6871  6871 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-02 19:08:01.693   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6871
09-02 19:08:01.693   404   404 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-02 19:08:01.723  1015  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-02 19:08:01.733  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:08:01.733  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:01.733  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:01.733  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:08:01.733  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:01.733  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:01.733  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:08:01.733  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:01.733  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:01.733  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-02 19:08:01.733  1174  1174 D HotspotTile: onReceive : 2, 0
,09-02 19:08:01.743  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 19:08:01.743  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 19:08:01.743  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-02 19:08:01.743  1015  3169 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:01.743  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:01.753  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:01.753  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:01.753  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:01.753  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:01.753  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:01.753  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:01.753  3635  3635 I Hs20UtilService: Starting #12
,09-02 19:08:01.753  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-02 19:08:01.753  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:01.853   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-02 19:08:01.853  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-02 19:08:01.923  6871  6871 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:01.923  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 19:08:01.933  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 19:08:01.933   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6871
09-02 19:08:01.933   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 19:08:01.933  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:01.933  6871  6871 I wpa_supplicant: ssSupport state is = 1,
09-02 19:08:01.933  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:01.933  6871  6871 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 19:08:01.933  6871  6871 E wpa_supplicant: SIM READ ERROR
09-02 19:08:01.933  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:01.933  6871  6871 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:01.933  6871  6871 E wpa_supplicant: SIM READ ERROR
09-02 19:08:01.933  6871  6871 I wpa_supplicant: Blacklist: Clear (all) 
09-02 19:08:01.933  6871  6871 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:01.933  6871  6871 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:01.933  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:01.933  6871  6871 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-02 19:08:01.933  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:01.933  6871  6871 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-02 19:08:01.943  6871  6871 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:08:01.943  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:08:01.943  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:01.943  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:01.983  6871  6871 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-02 19:08:02.233  6871  6871 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-02 19:08:02.233  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-02 19:08:02.243  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-02 19:08:02.253   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6871
09-02 19:08:02.253   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 19:08:02.253  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:02.253  6871  6871 I wpa_supplicant: ssSupport state is = 1,
09-02 19:08:02.253  6871  6871 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:02.253  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 19:08:02.263  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 19:08:02.263   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6871
09-02 19:08:02.263   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-02 19:08:02.263  6871  6871 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:02.263  6871  6871 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:02.263  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-02 19:08:02.263  6871  6871 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:02.263  6871  6871 E wpa_supplicant: SIM READ ERROR
,09-02 19:08:02.263  6871  6871 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:02.263  6871  6871 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:02.263  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.263  6871  6871 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 19:08:02.263  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.263  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:02.273  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.273  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.273  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:02.423  6871  6871 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-02 19:08:02.423  6871  6871 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 19:08:02.493  6871  6871 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-02 19:08:02.493  6871  6871 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 19:08:02.493  6871  6871 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:02.503  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-02 19:08:02.503  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:02.503  6871  6871 I wpa_supplicant: HOTSPOT20_ENABLE called
09-02 19:08:02.503  6871  6871 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:02.503  6871  6871 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 19:08:02.503  6871  6871 E wpa_supplicant: SIM READ ERROR
09-02 19:08:02.503  6871  6871 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:02.523  1015  1493 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:08:02.523  1015  1493 D BatteryService: level:95, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 19:08:02.523  1015  1493 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 19:08:02.523  1015  1493 D BatteryService: stay LED for charging
09-02 19:08:02.523  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:08:02.523  1015  1015 I MotionRecognitionService: Plugged
09-02 19:08:02.533  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 19:08:02.533  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-02 19:08:02.533  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 19:08:02.533  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 19:08:02.533  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
,09-02 19:08:02.553  6871  6871 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-02 19:08:02.563  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:08:02.563  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:08:02.563  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:08:02.563  1015  1129 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-02 19:08:02.573  6871  6871 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:02.573  1015  1129 D WifiConfigStore: Loading config and enabling all networks ,
,09-02 19:08:02.573  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.573  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:02.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.573  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.573  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:02.573  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-02 19:08:02.583  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:02.583  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:02.583  1174  1174 D HotspotTile: onReceive : 3, 0,
09-02 19:08:02.583  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:02.583  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:02.583  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:02.583  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:02.583  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:02.583  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:02.583  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:02.593  1015  2933 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:02.583  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:02.593  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:02.593  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:02.593  1015  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:02.593  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:02.593  1015  1129 E WifiConfigStore: Not a HS20
,09-02 19:08:02.593  3635  3635 I Hs20UtilService: Starting #13
09-02 19:08:02.593  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:02.593  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:02.593  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:02.593  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:02.593  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-02 19:08:02.593  1015  1129 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 19:08:02.603  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.603  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.603  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:02.613  1015  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 19:08:02.613  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-02 19:08:02.613  6871  6871 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 19:08:02.613  6871  6871 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-02 19:08:02.613  6871  6871 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:08:02.613  6871  6871 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:08:02.613  6871  6871 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 19:08:02.613  6871  6871 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 19:08:02.613  6871  6871 I wpa_supplicant: First Scan Start
09-02 19:08:02.613  6871  6871 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-02 19:08:02.613  1015  1129 D WifiNative-wlan0: Setting external_sim to 1
09-02 19:08:02.613  1015  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:08:02.613  1015  1129 I WifiNative-HAL: startHal
09-02 19:08:02.613  1015  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9ccab88c
09-02 19:08:02.613  1015  1129 I WifiNative-HAL: Could not start hal
09-02 19:08:02.613  6544  6544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:02.623  1015  1129 E WifiNative-wlan0: do suspend true
,09-02 19:08:02.623  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 19:08:02.623  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 19:08:02.623  1015  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 19:08:02.623  1015  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:02.623  1015  1129 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:02.623   278   972 D CommandListener: Setting iface cfg
09-02 19:08:02.623   278   972 D CommandListener: Trying to bring up p2p0
09-02 19:08:02.623  1015  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-02 19:08:02.623  1015  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:02.623  1015  1129 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:02.623  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,09-02 19:08:02.623  1015  1124 D WifiP2pService: P2pEnablingState,
09-02 19:08:02.623  6871  6871 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 19:08:02.623  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-02 19:08:02.623  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3,
09-02 19:08:02.623  1015  1124 D WifiP2pService: P2p socket connection successful
09-02 19:08:02.623  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:02.623  1015  1124 D WifiP2pService: P2pEnabledState
09-02 19:08:02.623  1015  1149 I WifiNative-HAL: startHal
09-02 19:08:02.633  6871  6871 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 19:08:02.633  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-02 19:08:02.633  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 19:08:02.633  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:02.633  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e0659bc
09-02 19:08:02.633  1015  1149 I WifiNative-HAL: Could not start hal
09-02 19:08:02.633  1015  1149 E WifiScanningService: could not start HAL
09-02 19:08:02.633  6871  6871 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-02 19:08:02.633  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:02.633  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 19:08:02.633  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-02 19:08:02.633  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:02.633  1015  1045 D WifiDisplayController: disconnect
09-02 19:08:02.633  1015  1045 D WifiDisplayController: updateConnection
09-02 19:08:02.633  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:02.633  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 19:08:02.633  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.633  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:02.643  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:08:02.643  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.643  1015  3213 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:02.643  1015  1129 D SecContentProvider2: mCursor = null
09-02 19:08:02.643  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 19:08:02.643  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-02 19:08:02.643  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:02.643  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-02 19:08:02.643  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:02.643  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:02.643  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:08:02.653  1015  1124 D WifiP2pService: DeviceAddress: 7e:96:ac,
09-02 19:08:02.653  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  secondary type: null
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  wps: 0
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  grpcapab: 0
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  devcapab: 0
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  status: 3
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  wfdInfo: null
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-02 19:08:02.653  1015  1045 D WifiDisplayController:  SConnectInfo : null
09-02 19:08:02.653  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:08:02.653  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:02.653  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:02.653  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:02.653  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:02.653  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:02.653  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:02.653  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-02 19:08:02.653  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 19:08:02.653  6514  6514 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:02.663  6529  6529 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:02.673  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 19:08:02.673  1015  1124 D WifiP2pService: InactiveState
09-02 19:08:02.673  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-02 19:08:02.673  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:02.673  6871  6871 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:02.673  1015  1124 D WifiP2pService: InactiveState{ what=143376 },
09-02 19:08:02.673  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:02.803  1015  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:08:03.033   292   292 E SMD     : DCD OFF
,09-02 19:08:03.743  1015  2933 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:08:03.743  1015  2933 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:08:03.743  1015  2933 D SecContentProvider2: mCursor = null,
,09-02 19:08:03.743  1015  2933 D WifiService: setWifiEnabled: false pid=6369, uid=10155
,09-02 19:08:03.743  1015  2933 D SettingsProvider: name = wifi_on
,09-02 19:08:03.753  6871  6871 I wpa_supplicant: nl80211: Received scan results (35 BSSes),
09-02 19:08:03.753  6871  6871 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-02 19:08:03.763  1015  1027 I ActivityManager: Killing 5528:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-02 19:08:03.763  6871  6871 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 19:08:03.763  6871  6871 I wpa_supplicant: Trying to associate with  'G700'
09-02 19:08:03.763  6871  6871 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-02 19:08:03.763  1015  6876 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-02 19:08:03.763  6871  6871 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-02 19:08:03.763  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,09-02 19:08:03.763  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-02 19:08:03.773  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1,
09-02 19:08:03.773  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
09-02 19:08:03.773  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-02 19:08:03.773  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-02 19:08:03.773  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:03.773  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:03.783  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:03.783  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:03.783  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:03.783  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:08:03.783  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:08:03.783  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:03.793  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:03.793  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 19:08:03.793  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:03.793  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
09-02 19:08:03.793  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:03.793  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:03.793  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 19:08:03.793  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:03.793  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-02 19:08:03.793  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:03.793  1015  1045 D WifiDisplayController: disconnect
09-02 19:08:03.793  1015  1045 D WifiDisplayController: updateConnection
,09-02 19:08:03.793  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:03.793  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:03.793  1015  1124 D WifiP2pService: P2pDisablingState,
09-02 19:08:03.793  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-02 19:08:03.793  1015  1124 D WifiP2pService: p2p socket connection lost
09-02 19:08:03.803   278   972 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:08:03.803  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-02 19:08:03.803  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:03.803  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-02 19:08:03.803  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 19:08:03.803  1015  1124 D WifiP2pService: P2pDisabledState
,09-02 19:08:03.803  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:03.803  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:08:03.803  1015  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 19:08:03.803  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 19:08:03.803  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 19:08:03.803  6514  6514 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:03.813  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:08:03.813  6871  6871 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:08:03.813  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:03.813  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:03.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:03.833  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:03.833  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:03.833  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.833  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.833  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.833  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.833  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:03.833  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-02 19:08:03.833  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:03.833  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:03.833  1174  1174 D HotspotTile: onReceive : 0, 0
,09-02 19:08:03.833  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:03.833  6529  6529 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-02 19:08:03.833  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:03.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:03.833  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:03.833  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:03.843  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:03.843  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:03.843  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:03.843  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:03.843  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 19:08:03.843  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:03.843  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:03.853  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:08:03.853  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:03.853  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:03.853  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:03.853  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:03.853  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 19:08:03.853  6514  6514 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:03.863  6529  6529 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:03.873  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:03.873  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:03.873  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:03.873  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:03.873  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:03.873  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.873  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.873  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:03.873  3635  3635 I Hs20UtilService: Starting #14
,09-02 19:08:03.873  3635  3663 I Hs20UtilService: Message received 5007
,09-02 19:08:03.873  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:03.873  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.873  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:03.883  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.883  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.883  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:03.883  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 19:08:03.883  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:03.883  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-02 19:08:03.883  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:08:03.883  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:03.883  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:03.883  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:03.883  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:03.883  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:03.883  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:03.883  1015  1133 E Tethering: No numeric data
,09-02 19:08:03.883  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:03.883  1015  1133 D Tethering: clearTetheredNotification()
,09-02 19:08:03.893  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:03.893  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:03.893  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:03.893  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:08:03.893  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:03.893  1015  1122 V NetworkStats: performPollLocked() took 4ms
09-02 19:08:03.893  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:03.893  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:03.893  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:03.893  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:03.893  1015  3213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:03.903  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:03.903  1015  3213 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:03.903  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:03.903  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:03.903  3635  3635 I Hs20UtilService: Starting #15
,09-02 19:08:03.903  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:03.903  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:03.913  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:03.913  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:03.913  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:04.023  6871  6871 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:04.113  6871  6871 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 19:08:04.113  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:04.113  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:04.113  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:04.143  6871  6871 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=00.00.00 reason=3 locally_generated=1
,09-02 19:08:04.143  6871  6871 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED,
09-02 19:08:04.143  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.143  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.143  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:04.143  1015  1133 D Tethering: InitialState.processMessage what=4
,09-02 19:08:04.143  1015  1129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-02 19:08:04.143  6871  6871 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
,09-02 19:08:04.143  6871  6871 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-02 19:08:04.143  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:04.143  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.143  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:04.143  1015  1133 E Tethering: No numeric data
,09-02 19:08:04.143  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-02 19:08:04.143  1015  1133 D Tethering: clearTetheredNotification(),
,09-02 19:08:04.153  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 19:08:04.153  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:04.153  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:08:04.153  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-02 19:08:04.153  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-02 19:08:04.153  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:08:04.153  1015  1122 V NetworkStats: performPollLocked() took 8ms
,09-02 19:08:04.153  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:04.163  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 19:08:04.163  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:04.333  1015  1093 V AlarmManager: waitForAlarm result :4,
,09-02 19:08:04.333  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-02 19:08:04.333  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>,
09-02 19:08:04.333  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###,
,09-02 19:08:04.343  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
,09-02 19:08:04.343  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 19:08:04.353  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-02 19:08:04.353  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,09-02 19:08:04.363  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:04.363  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-02 19:08:04.363  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,09-02 19:08:04.383  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:04.383  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:04.413  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:04.423  6871  6871 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:04.423  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:04.543  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.543  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.543  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:04.543  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.543  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:04.543  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:04.543  6871  6871 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-02 19:08:04.643  1015  1339 E Watchdog: !@Sync 6
,09-02 19:08:04.663  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-02 19:08:04.663  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:04.663  1015  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 19:08:04.663  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:04.663  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:04.663  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:04.663  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:04.663  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:04.663  1174  1174 D HotspotTile: onReceive : 1, 0
09-02 19:08:04.663  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:04.663  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:04.663  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:04.663  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:04.663  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-02 19:08:04.663  6544  6544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:04.663  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:04.673  1944  2124 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:04.673  1015  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:04.673  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:04.673  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:04.673  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:04.673  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:04.673  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:04.673  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:04.673  3635  3635 I Hs20UtilService: Starting #16,
09-02 19:08:04.673  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:04.683  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:04.683  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:04.683  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:04.683  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:04.823  1015  2736 D SSRM:n  : SIOP:: AP = 330
,09-02 19:08:05.463  1015  1042 D Tethering: interfaceRemoved wlan0
,09-02 19:08:05.463  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 19:08:05.743  1015  1042 D Tethering: interfaceRemoved p2p0
,09-02 19:08:05.743  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 19:08:05.783  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-02 19:08:05.783  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.793  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.793  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.793  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 19:08:05.803  6708  6756 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-02 19:08:05.853  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.853  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.853  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.863  1015  2729 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-02 19:08:05.863  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.863  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.863  1015  2729 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.863  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.873  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.873  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.873  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.883  1015  1218 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-02 19:08:05.883  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.883  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.883  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:05.883  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.893  1015  3046 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:05.893  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.893  1015  3046 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.893  1015  3046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:05.893  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.893  1015  3045 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:05.903  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 19:08:05.903  1015  3045 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.903  1015  3045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.903  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.913  1015  3044 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-02 19:08:05.913  1015  3044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
09-02 19:08:05.913  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.913  1015  3044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.913  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.933  1015  2729 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:05.933  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.933  1015  2729 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:05.933  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-02 19:08:05.943  1944  1944 D WearableService: callingUid 10012, callindPid: 1944
,09-02 19:08:05.963  1015  1218 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-02 19:08:05.963  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-02 19:08:05.963  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.963  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:05.963  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-02 19:08:05.973  6621  6887 I MusicLeanback: Conditions not met for autocaching.
,09-02 19:08:05.973  6621  6887 I MusicLeanback: Stop autocaching.
,09-02 19:08:05.993  6621  6621 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-02 19:08:06.003  6621  6892 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-02 19:08:06.033   292   292 E SMD     : DCD OFF
,09-02 19:08:06.573  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 19:08:06.763  6369  6423 D BluetoothAdapter: enable()
,09-02 19:08:06.763  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:08:06.763  1015  1028 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-02 19:08:06.763  1015  1028 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:08:06.763  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:06.763  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:06.763  1015  1028 D SettingsProvider: name = bluetooth_on,
,09-02 19:08:06.773  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-02 19:08:06.773  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:06.773  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,09-02 19:08:06.773  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-02 19:08:06.803  6491  6491 D BluetoothAdapterState: make
,09-02 19:08:06.813  6491  6491 I bluedroid: init
,09-02 19:08:06.813  6491  6894 I BluetoothAdapterState: Entering OffState
,09-02 19:08:06.823  6491  6491 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-02 19:08:06.823  6491  6491 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 19:08:06.823  6491  6491 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 19:08:06.823  6491  6491 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 19:08:06.823  6491  6491 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-02 19:08:06.823  6491  6491 I bluedroid: get_profile_interface socket
09-02 19:08:06.823  6491  6491 I bluedroid: get_profile_interface map_client
,09-02 19:08:06.823  6491  6897 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-02 19:08:06.823  6491  6491 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-02 19:08:06.833  6491  6897 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-02 19:08:06.833  6491  6897 E BluetoothServiceJni: populateRssiValuesNative
,09-02 19:08:06.833  6491  6897 I bluedroid: getModelRssiValues
09-02 19:08:06.833  6491  6897 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 19:08:06.833  6491  6897 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:06.833  6491  6897 D BluetoothAdapterProperties: Name is: A5-1
,09-02 19:08:06.833  1015  1015 D SettingsProvider: name = bluetooth_name
,09-02 19:08:06.833  6491  6491 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 19:08:06.833  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:06.833  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.833  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
09-02 19:08:06.833  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:06.833  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.843  6491  6503 I bluedroid: config_hci_snoop_log
,09-02 19:08:06.843  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-02 19:08:06.843  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-02 19:08:06.843  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 19:08:06.843  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 19:08:06.843  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 19:08:06.853  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:06.853  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:06.853  6491  6491 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-02 19:08:06.863  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 19:08:06.873  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 19:08:06.873  6491  6894 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-02 19:08:06.873  6491  6894 D BluetoothAdapterProperties: Setting state to 11
09-02 19:08:06.873  6491  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:08:06.873  6491  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:06.873  6491  6894 D BluetoothAdapterService: updateAdapterState state is 11
,09-02 19:08:06.873  6491  6894 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:08:06.873  6491  6894 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 19:08:06.873  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:06.873  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-02 19:08:06.873  6491  6894 D BluetoothSecureManager: getInstant: null
09-02 19:08:06.873  6491  6894 D BluetoothSecureManager: calling getMethod for getService
09-02 19:08:06.873  6491  6894 D BluetoothSecureManager: calling getService
,09-02 19:08:06.873  6491  6894 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@32937607
,09-02 19:08:06.873  1015  1476 D BluetoothSecureManagerService: isSecureModeEnabled
09-02 19:08:06.873  1015  1476 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-02 19:08:06.873  6491  6894 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:08:06.873  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:08:06.883  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 19:08:06.883  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:06.883  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 19:08:06.883  1802  1802 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 19:08:06.883  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 19:08:06.883  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:06.893  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:06.893  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:06.893  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 19:08:06.893  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:06.893  1015  2960 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:06.893  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:06.893  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 19:08:06.893  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:06.893  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 19:08:06.893  6491  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-02 19:08:06.893  6491  6894 D BluetoothBondStateMachine: make
09-02 19:08:06.893  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:06.893  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:08:06.903  1015  1138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:08:06.903  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-02 19:08:06.903  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:06.903  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 19:08:06.903  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 19:08:06.903  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 19:08:06.903  6491  6899 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 19:08:06.903  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:06.903  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.903  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:06.903  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:06.913  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:06.913  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:06.913  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.913  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:06.913  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:06.913  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.913  6491  6491 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:08:06.913  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:08:06.913  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:06.913  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:06.913  6491  6491 D BtGatt.GattService: Received start request. Starting profile...
09-02 19:08:06.913  6491  6491 D BtGatt.GattService: start()
09-02 19:08:06.913  6491  6491 D BtGatt.GattService: start()
09-02 19:08:06.913  6491  6491 I bluedroid: get_profile_interface gatt
,09-02 19:08:06.913  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:06.913  6491  6491 D BtGatt.AdvertiseManager: advertise manager created
,09-02 19:08:06.923  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:06.923  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-02 19:08:06.923  1015  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:06.923  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.923  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:06.933  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:06.933  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.933  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:06.933  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:06.933  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:06.943  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:06.943  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.943  6491  6491 D BtGatt.GattService: mStartError = false
09-02 19:08:06.943  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:06.943  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.943  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.943  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.943  6491  6491 D HeadsetService: Received start request. Starting profile...
,09-02 19:08:06.943  6491  6491 D HeadsetService: start()
,09-02 19:08:06.943  6491  6491 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 19:08:06.943  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-02 19:08:06.943  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:06.943  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:08:06.943  6491  6491 D HeadsetStateMachine: make
,09-02 19:08:06.953  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:06.953  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.953  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.953  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.953  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.953  6491  6491 E HeadsetStateMachine: # of Max HF connection is 2
,09-02 19:08:06.963  1015  1333 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 19:08:06.963  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.963  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.963  1015  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.963  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:06.963  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:08:06.963  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:06.963  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:08:06.963  1015  3169 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:06.963  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.963  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.963  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.963  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.973  1015  2729 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-02 19:08:06.973  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.973  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 19:08:06.973  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:06.973  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-02 19:08:06.973  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.973  1015  2729 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.973  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:06.973  6491  6491 I bluedroid: get_profile_interface handsfree
,09-02 19:08:06.973  1015  1333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:06.973  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.973  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:06.973  1015  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.973  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.973  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:06.973  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:06.973  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:06.973  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:06.973  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.983  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.983  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.983  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:08:06.983  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:08:06.983  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:06.983  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.983  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:06.983  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.983  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:06.983  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:06.983  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:06.983  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 19:08:06.983  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:06.983  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:06.983  6491  6894 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 19:08:06.993  6491  6491 I DualScoManager: Instantiating Dual Sco Manager,
,09-02 19:08:06.993  6491  6491 I DualScoManager: Set HeadsetServiceHelper
09-02 19:08:06.993  6491  6491 D BluetoothAtMessage: createCMTIContentObservers
09-02 19:08:06.993  1015  3169 D SettingsProvider: name = bluetooth_hfp_allowed_bvra,
09-02 19:08:06.993  1015  3169 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 19:08:06.993  1015  3169 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:06.993  1015  3169 D SettingsProvider: selectionArgs: false
09-02 19:08:06.993  1015  3169 D SettingsProvider: selectionArgs: 1002
09-02 19:08:06.993  1015  3169 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:06.993  1015  3169 D SettingsProvider: ret = -1
09-02 19:08:06.993  6491  6903 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 19:08:07.003  6491  6491 D HeadsetService: mStartError = false
09-02 19:08:07.003  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:07.003  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-02 19:08:07.003  6491  6903 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-02 19:08:07.003  6491  6903 D HeadsetStateMachine: map size, before remove : 0
09-02 19:08:07.003  6491  6903 D HeadsetStateMachine: map size, after remove: 0
,09-02 19:08:07.003  6491  6491 D A2dpService: Received start request. Starting profile...
,09-02 19:08:07.003  6491  6491 D A2dpService: start()
,09-02 19:08:07.003  6491  6491 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 19:08:07.003  6491  6491 I bluedroid: get_profile_interface avrcp
,09-02 19:08:07.013  6491  6491 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 19:08:07.023  6491  6491 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 19:08:07.023  6491  6907 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-02 19:08:07.033  6491  6491 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-02 19:08:07.033  6491  6491 D A2dpStateMachine: make
,09-02 19:08:07.033  6491  6491 I bluedroid: get_profile_interface a2dp
,09-02 19:08:07.033  6491  6909 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
09-02 19:08:07.033  6491  6491 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 19:08:07.033  6491  6491 D A2dpService: mStartError = false,
09-02 19:08:07.033  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:07.033  6491  6908 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:08:07.033  6491  6491 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 19:08:07.043  6491  6491 D HidService: Received start request. Starting profile...
09-02 19:08:07.043  6491  6491 D HidService: start()
09-02 19:08:07.043  6491  6491 I bluedroid: get_profile_interface hidhost
09-02 19:08:07.043  6491  6491 D HidService: setHidService(): set to: null
09-02 19:08:07.043  6491  6491 D HidService: mStartError = false
09-02 19:08:07.043  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:07.043  6491  6491 D HeadsetStateMachine: Try to query the phonestate on bind
,09-02 19:08:07.043  1431  1439 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 19:08:07.043  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-02 19:08:07.043  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 19:08:07.053  1431  1439 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 19:08:07.053  6491  6491 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 19:08:07.053  6491  6491 D HealthService: Received start request. Starting profile...
09-02 19:08:07.053  6491  6491 D HealthService: start()
,09-02 19:08:07.053  6491  6907 D BluetoothMediaBrowser: no now playing list
,09-02 19:08:07.053  6491  6907 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-02 19:08:07.053  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:07.063  6491  6491 I bluedroid: get_profile_interface health
,09-02 19:08:07.063  6491  6491 D HealthService: mStartError = false
09-02 19:08:07.063  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:07.063  6491  6491 D HeadsetStateMachine: Proxy object connected
,09-02 19:08:07.063  6491  6491 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 19:08:07.063  6491  6491 D PanService: Received start request. Starting profile...
09-02 19:08:07.063  6491  6491 D PanService: start()
09-02 19:08:07.063  6491  6491 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:08:07.063  6491  6491 I bluedroid: get_profile_interface pan
09-02 19:08:07.063  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:07.063  6491  6491 D PanService: mStartError = false
09-02 19:08:07.063  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:07.063  6491  6491 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-02 19:08:07.063  6491  6903 D HeadsetStateMachine: Disconnected process message: 11
,09-02 19:08:07.073  6491  6491 D BluetoothMapService: Received start request. Starting profile...,
09-02 19:08:07.073  6491  6491 D BluetoothMapService: start()
,09-02 19:08:07.073  6491  6491 D BluetoothMapService: mStartError = false
,09-02 19:08:07.073  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:07.073  6491  6491 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 19:08:07.073  6491  6491 D SapService: Received start request. Starting profile...
,09-02 19:08:07.073  6491  6491 D SapService: start()
09-02 19:08:07.073  6491  6491 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-02 19:08:07.083  6491  6491 I bluedroid: get_profile_interface sap
,09-02 19:08:07.083  6491  6491 D SapService: mStartError = false
,09-02 19:08:07.083  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:07.083  6491  6491 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-02 19:08:07.083  6491  6491 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 19:08:07.083  6491  6903 D HeadsetStateMachine: Disconnected process message: 18
09-02 19:08:07.083  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-02 19:08:07.083  6491  6491 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 19:08:07.083  6491  6491 D BluetoothA2dp: Proxy object connected
09-02 19:08:07.083  6491  6491 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-02 19:08:07.083  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 19:08:07.083  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-02 19:08:07.083  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-02 19:08:07.083  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-02 19:08:07.083  6491  6903 D HeadsetStateMachine: Disconnected process message: 10
,09-02 19:08:07.083  6491  6903 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 19:08:07.083  6491  6903 D HeadsetStateMachine: Disconnected process message: 11
,09-02 19:08:07.113  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 19:08:07.113  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 19:08:07.113  6491  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 19:08:07.113  6491  6894 I bluedroid: enable
,09-02 19:08:07.113  6491  6894 I bt_hci_bdroid: init
,09-02 19:08:07.113  6491  6914 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-02 19:08:07.113  6491  6894 I bt_vendor: bt-vendor : init
,09-02 19:08:07.113  6491  6894 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 19:08:07.113  6491  6894 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 19:08:07.113  6491  6894 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,09-02 19:08:07.123  6491  6894 D bt_userial_mct: userial_init
09-02 19:08:07.123  6491  6894 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 19:08:07.123  6491  6894 I bt_vendor: Starting hciattach daemon
09-02 19:08:07.123  6491  6894 I bt_vendor: try to set false
,09-02 19:08:07.123  6491  6894 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-02 19:08:07.123  6491  6894 I bt_vendor: Starting hciattach daemon
09-02 19:08:07.123  6491  6894 I bt_vendor: try to set true
,09-02 19:08:07.143  6919  6919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-02 19:08:07.193  6925  6925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-02 19:08:07.193  6926  6926 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 19:08:07.213  6928  6928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 19:08:07.223  6929  6929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-02 19:08:07.233  6930  6930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 19:08:07.243  6931  6931 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-02 19:08:07.493  6934  6934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-02 19:08:07.503  6935  6935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 19:08:07.533  6491  6894 I bt_vendor: bluetooth satus is on,
09-02 19:08:07.533  6491  6916 D bt_userial_mct: userial_open(port:0)
09-02 19:08:07.533  6491  6916 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-02 19:08:07.533  6491  6916 I bt_vendor: Done intiailizing UART,
,09-02 19:08:07.533  6491  6916 I bt_vendor: Done intiailizing UART,
09-02 19:08:07.533  6491  6916 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 19:08:07.533  6491  6916 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 19:08:07.543  6491  6937 D bt_userial_mct: Entering userial_read_thread(),
,09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_A2D,
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_BTM,
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_SAP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_GATT,
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 19:08:07.543  6491  6914 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 19:08:07.643  6491  6914 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 19:08:07.643  6491  6914 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40c36e9 
,09-02 19:08:07.653  6491  6914 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40c36e9 
,09-02 19:08:07.663  6491  6897 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 19:08:07.663  6491  6897 E bt-btif : Calling BTA_HhEnable
,09-02 19:08:07.673  6491  6897 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 19:08:07.673  6491  6897 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-02 19:08:07.673  6491  6897 E BluetoothServiceJni: populateRssiValuesNative
,09-02 19:08:07.673  6491  6897 I bluedroid: getModelRssiValues
,09-02 19:08:07.673  6491  6897 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-02 19:08:07.673  6491  6897 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:07.673  1015  1015 D SettingsProvider: name = bluetooth_name
,09-02 19:08:07.673  6491  6897 D BluetoothAdapterProperties: Name is: A5-1
,09-02 19:08:07.683  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:07.683  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:07.683  6491  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 19:08:07.693  6491  6897 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:07.693  6491  6897 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:08:07.693  6491  6897 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-02 19:08:07.693  6491  6897 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-02 19:08:07.693  6491  6897 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-02 19:08:07.693  6491  6897 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-02 19:08:07.693  6491  6897 E bt-btif : btif_sock_init: !vhci_init
09-02 19:08:07.693  6491  6897 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-02 19:08:07.693  6491  6897 D IOP_DB_BT: db_open: db_open : handle 3026419728l, read 13894 bytes onto local cache
09-02 19:08:07.693  6491  6897 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-02 19:08:07.693  6491  6897 D IOP_DB_BT: db_query: result 1
09-02 19:08:07.693  6491  6897 I         : iop_db_open: iop_db_open status 0
09-02 19:08:07.693  6491  6897 D bte_conf: Device ID record 1 : primary
09-02 19:08:07.693  6491  6897 D bte_conf:   vendorId            = 0075
09-02 19:08:07.693  6491  6897 D bte_conf:   vendorIdSource      = 0001
09-02 19:08:07.693  6491  6897 D bte_conf:   product             = 0100
09-02 19:08:07.693  6491  6897 D bte_conf:   version             = 0200
09-02 19:08:07.693  6491  6897 D bte_conf:   clientExecutableURL = 
09-02 19:08:07.693  6491  6897 D bte_conf:   serviceDescription  = 
09-02 19:08:07.693  6491  6897 D bte_conf:   documentationURL    = 
09-02 19:08:07.693  6491  6897 D bte_conf: bte_load_did_conf no section named DID2.
,09-02 19:08:07.693  6491  6897 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 19:08:07.693  6491  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 19:08:07.693  6491  6894 D BluetoothAdapterProperties: ScanMode =  20
,09-02 19:08:07.693  6491  6894 D BluetoothAdapterProperties: State =  11
,09-02 19:08:07.693  1015  3213 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:08:07.703  6491  6894 D BluetoothAdapterProperties: Setting state to 12
,09-02 19:08:07.703  6491  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 19:08:07.703  6491  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:07.703  6491  6897 D BluetoothAdapterProperties: Scan Mode:21
,09-02 19:08:07.703  6491  6897 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:08:07.703  6491  6937 E bt_mct  : hci lib postload completed
,09-02 19:08:07.713  1015  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-02 19:08:07.713  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:07.713  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:08:07.713  1015  1027 D SettingsProvider: selectionArgs: false
09-02 19:08:07.713  1015  1027 D SettingsProvider: selectionArgs: 1002
09-02 19:08:07.713  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:07.713  1015  1027 D SettingsProvider: ret = -1
,09-02 19:08:07.713  6491  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:07.713  6491  6894 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:07.713  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:07.713  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:07.713  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.713  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.713  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.713  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:07.713  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:07.723  6491  6894 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:07.723  6491  6894 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-02 19:08:07.723  6491  6894 D BluetoothAdapterService: starting service from this receiver
,09-02 19:08:07.723  1015  2729 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:07.723  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.723  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.723  1015  2729 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:07.723  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.733  1312  1326 D BluetoothPan: Binding service...
,09-02 19:08:07.733  6491  6894 I BluetoothAdapterState: Entering On State from state = 11
,09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:07.743  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:07.743  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-02 19:08:07.743  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.743  6491  6491 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 19:08:07.743  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.743  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:07.743  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.743  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.743  1440  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.743  1440  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.743  6491  6500 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:07.743  1312  1330 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.743  1312  1330 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.753  1312  1338 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:08:07.753  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-02 19:08:07.753  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.753  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.753  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.753  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.753  1454  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.753  6491  6491 I BluetoothPbapService: Handler(): got msg=1
,09-02 19:08:07.763  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.763  1015  3045 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-02 19:08:07.763  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.763  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.763  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.763  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.763  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 19:08:07.763  1312  1312 D PanProfile: Bluetooth service connected
,09-02 19:08:07.763  1454  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.763  1431  1449 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.773  1431  1449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.773  6491  6941 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 19:08:07.773  1944  2114 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.773  1944  2114 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.773  1174  3757 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.773  1174  3757 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.773  6461  6476 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:07.773  6461  6476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.773  2888  2909 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:07.773  2888  2909 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.783  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 19:08:07.783  6491  6941 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 19:08:07.783  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:07.783  6491  6941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:08:07.783  1312  1312 D BluetoothMap: Proxy object connected
09-02 19:08:07.783  1312  1312 D MapProfile: Bluetooth service connected
09-02 19:08:07.783  1312  1312 D BluetoothMap: getConnectedDevices()
,09-02 19:08:07.783  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.783  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.783  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-02 19:08:07.783  2888  2909 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.783  2888  2909 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.783  2888  2888 D BluetoothA2dp: Proxy object connected
09-02 19:08:07.783  1312  1338 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:07.783  1312  1338 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 19:08:07.783  6491  6941 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-02 19:08:07.783  6491  6941 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:07.783  6491  6941 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:07.783  6491  6941 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273a53fb
,09-02 19:08:07.783  6491  6941 D BluetoothSocket: channel: 19
09-02 19:08:07.783  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:07.783  6491  6941 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-02 19:08:07.783  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.783  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.783  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.783  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.783  1312  1312 D BluetoothA2dp: Proxy object connected
09-02 19:08:07.783  1312  1312 D A2dpProfile: Bluetooth service connected
,09-02 19:08:07.793  1431  6487 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.793  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:07.793  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.793  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.793  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.793  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.793  1431  6487 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.793  6491  6503 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.793  6491  6503 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.793  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.793  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.793  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.793  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.803  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.803  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.803  1312  1330 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.803  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.803  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.803  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.803  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.803  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.803  1312  1312 D HeadsetProfile: Bluetooth service connected
,09-02 19:08:07.803  1312  1330 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.803  1454  1685 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.803  1454  1685 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.813  1431  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.813  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.813  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.813  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.813  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.813  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.813  1431  1449 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.813  1431  6487 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.813  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.813  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.823  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.823  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.823  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.823  1431  6487 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:07.823  2888  2904 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:07.823  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:07.823  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:07.823  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.823  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.823  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-02 19:08:07.823  2888  2904 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:07.823  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:07.823  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 19:08:07.823  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:07.823  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:07.833  1015  1015 D BluetoothA2dp: Proxy object connected
09-02 19:08:07.833  1312  1338 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:08:07.833  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 19:08:07.833  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-02 19:08:07.833  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.833  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.833  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.833  6369  6377 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:07.833  6369  6377 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:07.833  1312  1330 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 19:08:07.833  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-02 19:08:07.833  1312  1312 D BluetoothPbap: Proxy object connected
09-02 19:08:07.833  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-02 19:08:07.833  1312  1312 D PbapServerProfile: Bluetooth service connected
,09-02 19:08:07.833  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.833  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.833  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.833  1312  1338 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 19:08:07.833  1312  1338 D Bluetoothsap: Binding service...
,09-02 19:08:07.843  1312  1312 D BluetoothInputDevice: Proxy object connected,
,09-02 19:08:07.843  1312  1312 D HidProfile: Bluetooth service connected
09-02 19:08:07.843  1312  1338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 19:08:07.843  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 19:08:07.843  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-02 19:08:07.843  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.843  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.843  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.843  1312  1338 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 19:08:07.843  1015  1044 D BluetoothPan: Binding service...
,09-02 19:08:07.843  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 19:08:07.843  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-02 19:08:07.843  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:08:07.843  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 19:08:07.843  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-02 19:08:07.843  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-02 19:08:07.843  1312  1312 D SapProfile: Bluetooth service connected
09-02 19:08:07.843  1312  1312 D Bluetoothsap: getConnectedDevices()
,09-02 19:08:07.843  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:07.843  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-02 19:08:07.843  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:07.853  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@8f3bda6, true
,09-02 19:08:07.853  1802  1802 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:07.853  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:08:07.853  1431  1431 D BluetoothHeadset: registerMessageListener
,09-02 19:08:07.853  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:07.863  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:07.853  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:07.863  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-02 19:08:07.863  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:07.863  1015  3046 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:07.863  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.863  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:07.863  1015  3046 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.863  1015  3046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:07.863  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 19:08:07.863  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:07.863  6491  6503 D HeadsetService: registerMessageListener
,09-02 19:08:07.863  6491  6503 D HeadsetService: registerMessageListener
,09-02 19:08:07.873  6491  6903 D HeadsetStateMachine: Disconnected process message: 70
,09-02 19:08:07.873  6491  6903 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@288e6c18
09-02 19:08:07.873  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 19:08:07.873  1312  1312 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-02 19:08:07.873  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 19:08:07.873  1312  1312 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 19:08:07.873  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 19:08:07.873  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 19:08:07.873  1015  3213 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:07.873  1015  3169 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-02 19:08:07.873  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 19:08:07.873  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 19:08:07.873  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:07.873  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-02 19:08:07.873  6491  6944 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 19:08:07.873  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:07.873  6491  6903 D HeadsetStateMachine: Disconnected process message: 9
,09-02 19:08:07.873  6491  6903 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 19:08:07.873  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:07.883   283  1013 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-02 19:08:07.883  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:08:07.883  6491  6944 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:07.883  6491  6944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:07.883  1015  3213 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:08:07.883  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-02 19:08:07.883   283  1013 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 19:08:07.883   283  1013 V voice   : voice_set_parameters: exit with code(-2)
09-02 19:08:07.883   283  1013 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 19:08:07.883   283  1013 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 19:08:07.883   283  1013 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 19:08:07.883   283  1013 V audio_hw_primary: adev_set_parameters: exit
09-02 19:08:07.883  6491  6903 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 19:08:07.883  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.883  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.883  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:07.893  6491  6944 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-02 19:08:07.893  6491  6944 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:07.893  6491  6944 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:07.893  6491  6944 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c238671
09-02 19:08:07.893  6491  6944 D BluetoothSocket: channel: 5
,09-02 19:08:07.903  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:07.903  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:07.903  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:07.903  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 19:08:07.913  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:07.913  6491  6491 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 19:08:07.913  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-02 19:08:07.913  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.913  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:07.913  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:07.913  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:07.943  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:07.943  1015  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:08:07.943  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:07.943  1015  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:07.943  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:07.943  1015  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:07.943  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:07.953  6491  6954 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:07.953  6491  6954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:07.953  6491  6954 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-02 19:08:07.953  6491  6954 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:07.953  6491  6954 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:07.953  6491  6954 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@91918ad
09-02 19:08:07.953  6491  6954 D BluetoothSocket: channel: 12
09-02 19:08:07.953  6491  6954 I BtOppRfcommListener: Accept thread started.
,09-02 19:08:07.953  1944  6955 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-02 19:08:07.953  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:08.103  1015  1333 I art     : Explicit concurrent mark sweep GC freed 55444(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.407ms total 142.527ms
,09-02 19:08:08.103  1015  1333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:08.103  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.103  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:08.103  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:08.113  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:08.123  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:08.123  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:08.123  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:08.133  1944  6955 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-02 19:08:09.033   292   292 E SMD     : DCD OFF,
,09-02 19:08:09.783  6369  6423 D BluetoothAdapter: disable()
,09-02 19:08:09.783  1015  1493 D SettingsProvider: name = bluetooth_on
,09-02 19:08:09.783  6491  6894 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-02 19:08:09.783  6491  6894 D BluetoothAdapterProperties: Setting state to 13
,09-02 19:08:09.783  6491  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 19:08:09.783  6491  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:09.783  6491  6894 D BluetoothAdapterService: updateAdapterState state is 13
,09-02 19:08:09.783  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:09.783  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:09.783  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:09.783  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:09.783  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:09.793  6491  6894 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:08:09.793  6491  6894 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 19:08:09.793  6491  6894 D BluetoothAdapterService: terminating service from this receiver
,09-02 19:08:09.793  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:09.793  6491  6491 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-02 19:08:09.793  6491  6491 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@80267e2, channel: 19, state: LISTENING
09-02 19:08:09.793  6491  6491 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@80267e2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273a53fb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f794773mSocket: android.net.LocalSocket@105aa630 impl:android.net.LocalSocketImpl@e5b92a9 fd:FileDescriptor[75]
,09-02 19:08:09.793  6491  6491 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@105aa630 impl:android.net.LocalSocketImpl@e5b92a9 fd:FileDescriptor[75]
,09-02 19:08:09.793  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:09.793  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:09.793  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:09.793  6491  6894 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:08:09.793  6491  6894 D BluetoothAdapterProperties: mDiscovering is false
09-02 19:08:09.793  1015  3213 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:08:09.793  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:09.793  6491  6894 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 19:08:09.793  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-02 19:08:09.803  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:08:09.803  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:09.813  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:09.813  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
09-02 19:08:09.813  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-02 19:08:09.813  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:09.813  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:08:09.813  1802  1802 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:09.813  1015  2729 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:09.823  1015  3046 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 19:08:09.823  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 19:08:09.823  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:09.823  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:09.823  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:09.823  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:09.823  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:09.833  1015  2960 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:09.833  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:08:09.833  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:09.833  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:09.833  6491  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:09.833  6491  6897 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:09.843  6369  6369 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:09.843  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:09.843  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:09.843  1015  2960 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:09.843  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:09.843  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:09.843  1015  1477 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:08:09.843  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:09.843  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:09.843  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-02 19:08:09.843  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings,
,09-02 19:08:09.843  6491  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-02 19:08:09.843  6491  6894 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1,
09-02 19:08:09.853  6491  6894 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-02 19:08:09.853  6491  6894 E bt-btif : BTM_SEC_CLR[17]: id 57
,09-02 19:08:09.853  6491  6894 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:08:09.853  6491  6914 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 19:08:09.853  6491  6914 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 19:08:09.853  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:09.853  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:08:09.853  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 19:08:09.853  6491  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:08:09.853  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:09.853  6491  6954 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 19:08:09.863  1312  1312 D BluetoothPbap: Proxy object disconnected
09-02 19:08:09.863  1312  1312 D PbapServerProfile: Bluetooth service disconnected
,09-02 19:08:09.863  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:09.863  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:09.873  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:09.873  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 19:08:09.883  6491  6491 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b63202e, channel: 5, state: LISTENING
,09-02 19:08:09.883  6491  6491 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b63202e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c238671, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e96e7cfmSocket: android.net.LocalSocket@29fbf55c impl:android.net.LocalSocketImpl@631b065 fd:FileDescriptor[77]
09-02 19:08:09.883  6491  6491 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29fbf55c impl:android.net.LocalSocketImpl@631b065 fd:FileDescriptor[77]
,09-02 19:08:09.883  6491  6491 I BtOppRfcommListener: stopping Accept Thread
09-02 19:08:09.883  6491  6491 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a05113a, channel: 12, state: LISTENING
09-02 19:08:09.883  6491  6491 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a05113a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@91918ad, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c4431ebmSocket: android.net.LocalSocket@27010b48 impl:android.net.LocalSocketImpl@2e91ede1 fd:FileDescriptor[79]
09-02 19:08:09.883  6491  6491 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27010b48 impl:android.net.LocalSocketImpl@2e91ede1 fd:FileDescriptor[79]
,09-02 19:08:09.883  6491  6954 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 19:08:09.893  6491  6491 V BluetoothOppManager: cleanUp...
,09-02 19:08:09.903  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:09.903  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:08:10.053  6491  6914 W bt-btif : ag scb idx 1 not allocated
09-02 19:08:10.053  6491  6914 W bt-btif : ag scb idx 2 not allocated
09-02 19:08:10.053  6491  6914 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 19:08:10.053  6491  6937 I bt_userial_mct: exiting userial_read_thread
09-02 19:08:10.053  6491  6937 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 19:08:10.053  6491  6897 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 19:08:10.053  6491  6916 I bt_vendor: hw_epilog_process
09-02 19:08:10.053  6491  6897 D bt_userial_mct: userial_close
09-02 19:08:10.053  6491  6897 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 19:08:10.423  6491  6897 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 19:08:10.423  6491  6897 I bt_vendor: bluetooth satus is on
09-02 19:08:10.423  6491  6897 I bt_vendor: bt-vendor : resetting BT status
09-02 19:08:10.423  6491  6897 I bt_vendor: Starting hciattach daemon
,09-02 19:08:10.423  6491  6897 I bt_vendor: try to set false
,09-02 19:08:10.423  6491  6897 I bt_vendor: Starting hciattach daemon
,09-02 19:08:10.423  6491  6897 I bt_vendor: try to set false
,09-02 19:08:10.423  6491  6897 I bt_vendor: cleanup
,09-02 19:08:10.423  6491  6914 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-02 19:08:10.423  6491  6897 I GKI_LINUX: GKI_exit_task 0 done
,09-02 19:08:10.423  6491  6897 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-02 19:08:10.423  6491  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-02 19:08:10.423  6491  6894 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 19:08:10.423  6491  6894 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-02 19:08:10.423  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-02 19:08:10.423  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
,09-02 19:08:10.423  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-02 19:08:10.423  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.433  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.433  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-02 19:08:10.433  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.433  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:08:10.433  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-02 19:08:10.433  6491  6491 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:08:10.433  6491  6491 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 19:08:10.433  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.433  6491  6491 D BtGatt.GattService: stop()
09-02 19:08:10.433  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.433  6491  6491 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 19:08:10.433  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:10.433  1015  2960 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.433  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.433  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:10.433  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService,
09-02 19:08:10.433  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 19:08:10.433  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
09-02 19:08:10.443  1015  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:10.433  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:10.443  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-02 19:08:10.433  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.433  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 19:08:10.433  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:08:10.433  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:08:10.443  6491  6491 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:08:10.443  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.443  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:10.443  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:10.443  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-02 19:08:10.443  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:08:10.443  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:08:10.443  1015  2729 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:10.443  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.443  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.453  1015  2729 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.453  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:10.453  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.453  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 19:08:10.453  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-02 19:08:10.453  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 19:08:10.453  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:08:10.453  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.453  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.453  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:10.453  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.453  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:10.453  1312  1312 D HeadsetProfile: Bluetooth service disconnected
,09-02 19:08:10.453  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.453  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.453  6491  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:10.453  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.453  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.463  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:10.463  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.463  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:08:10.463  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:10.463  1015  2933 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:08:10.463  1015  2933 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-02 19:08:10.463  1015  2933 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:10.463  1015  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.463  1015  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:10.463  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:10.463  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:10.463  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 19:08:10.463  6491  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:10.463  6491  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:10.463  6491  6894 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 19:08:10.463  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-02 19:08:10.463  6491  6491 D A2dpService: Received stop request...Stopping profile...
,09-02 19:08:10.463  6491  6908 D A2dpStateMachine: Exit Disconnected: -1
,09-02 19:08:10.463  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.473  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-02 19:08:10.473  1312  1312 D BluetoothA2dp: Proxy object disconnected
09-02 19:08:10.473  6491  6491 D HidService: Received stop request...Stopping profile...
09-02 19:08:10.473  6491  6491 D HidService: Stopping Bluetooth HidService
09-02 19:08:10.473  6491  6491 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:08:10.473  6491  6491 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 19:08:10.473  6491  6491 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:08:10.473  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.473  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 19:08:10.473  1312  1312 D A2dpProfile: Bluetooth service disconnected
,09-02 19:08:10.473  1312  1312 D BluetoothInputDevice: Proxy object disconnected
09-02 19:08:10.473  1312  1312 D HidProfile: Bluetooth service disconnected
,09-02 19:08:10.473  6491  6491 D HealthService: Received stop request...Stopping profile...
09-02 19:08:10.473  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.473  2888  2888 D BluetoothA2dp: Proxy object disconnected
,09-02 19:08:10.473  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-02 19:08:10.473  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:08:10.473  6491  6491 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 19:08:10.473  6491  6491 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:08:10.473  6491  6491 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 19:08:10.483  6491  6491 D PanService: Received stop request...Stopping profile...
,09-02 19:08:10.483  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.483  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 19:08:10.483  6491  6491 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 19:08:10.483  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 19:08:10.483  1312  1312 D PanProfile: Bluetooth service disconnected
,09-02 19:08:10.483  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.483  6491  6491 D SapService: Received stop request...Stopping profile...
,09-02 19:08:10.483  6491  6491 D SapService: Stopping Bluetooth SapService
09-02 19:08:10.483  6491  6491 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1023556e
,09-02 19:08:10.483  1312  1312 D BluetoothMap: Proxy object disconnected
09-02 19:08:10.483  1312  1312 D MapProfile: Bluetooth service disconnected
,09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
09-02 19:08:10.493  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 19:08:10.493  6491  6491 D BluetoothA2dp: Proxy object disconnected
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-02 19:08:10.493  6491  6909 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-02 19:08:10.493  6491  6491 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:08:10.493  6491  6491 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-02 19:08:10.493  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:10.493  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.493  1312  1312 D SapProfile: Bluetooth service disconnected
,09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 19:08:10.493  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.493  6491  6491 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:08:10.493  6491  6491 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 19:08:10.493  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:10.493  6491  6491 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:08:10.493  6491  6491 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-02 19:08:10.493  6491  6491 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:10.493  6491  6491 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-02 19:08:10.493  6491  6491 E BluetoothAdapterService(270751086): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 19:08:10.493  6491  6491 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 19:08:10.493  6491  6491 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-02 19:08:10.493  6491  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-02 19:08:10.503  6491  6894 D BluetoothAdapterProperties: Setting state to 10
09-02 19:08:10.503  6491  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:08:10.503  6491  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:10.503  6491  6894 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 19:08:10.503  6491  6894 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:08:10.503  6491  6894 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,09-02 19:08:10.503  6491  6894 I BluetoothAdapterState: Entering OffState
,09-02 19:08:10.503  1440  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.503  1440  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.503  6491  6943 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:10.503  1312  1330 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.503  1312  1330 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.503  1312  1338 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:08:10.503  1431  6487 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.503  1431  6487 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.503  1944  1961 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  1944  1961 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.513  1174  1894 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  1174  1894 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.513  6461  6476 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  6461  6476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.513  2888  2909 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:10.513  2888  2904 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  2888  2904 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.513  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:10.513  6491  6945 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  6491  6945 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.513  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.513  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.523  1454  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.523  1454  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.523  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:10.523  1312  1338 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 19:08:10.523  6369  6377 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:10.523  6369  6377 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:10.523  6369  6377 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-02 19:08:10.523  6369  6377 D BluetoothLeAdvertiser: Exit stop advertising
09-02 19:08:10.523  6369  6377 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 19:08:10.523  6369  6377 D BluetoothLeScanner: Exiting stopAllScan
09-02 19:08:10.523  1312  1326 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:08:10.523  1312  1330 D Bluetoothsap: onBluetoothStateChange: up=false
,09-02 19:08:10.523  1312  1330 D Bluetoothsap: Unbinding service...
,09-02 19:08:10.523  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-02 19:08:10.533  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 19:08:10.533  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:10.533  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-02 19:08:10.533  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:10.543  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:08:10.543  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:10.543  1174  1722 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:08:10.543  6491  6897 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating,
09-02 19:08:10.543  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:10.543  1174  1174 D BluetoothTile:  getBluetoothState : 10
,09-02 19:08:10.543  1174  1722 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
09-02 19:08:10.543  6491  6491 I GKI_LINUX: GKI_exit_task 1 done
09-02 19:08:10.543  6491  6491 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-02 19:08:10.543  6491  6491 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 19:08:10.543  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
09-02 19:08:10.543  1174  1174 D BluetoothAdapter: 361040905: getState() :  mService = null. Returning STATE_OFF
,09-02 19:08:10.543  1015  3044 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:10.543  1015  1493 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:08:10.543  1802  1802 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 19:08:10.543  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:08:10.543  6491  6491 I art     : System.exit called, status: 0
09-02 19:08:10.543  6491  6491 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 19:08:10.543  1944  2124 D BluetoothAdapter: 233686329: getState() :  mService = null. Returning STATE_OFF
09-02 19:08:10.543  1944  2124 D BluetoothAdapter: 233686329: getState() :  mService = null. Returning STATE_OFF
,09-02 19:08:10.553  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:10.553  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:10.553  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:10.553  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:08:10.553  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.553  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.553  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:10.553  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:10.563  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:10.563  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:08:10.563  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.563  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.563  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:10.563  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:10.573  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:10.573  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:10.573  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:10.573  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 19:08:10.663  1015  1138 I ActivityManager: Process com.android.bluetooth (pid 6491)(adj 0) has died(64,1078)
,09-02 19:08:10.673  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:10.673  1015  1333 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:10.673  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:10.673  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:10.673  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:10.673  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:10.683  1944  6971 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 19:08:10.683  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:10.693  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:10.693  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:10.693  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:10.693  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:10.703  1944  6971 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 19:08:12.043   292   292 E SMD     : DCD OFF
,09-02 19:08:12.583  1015  2933 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:08:12.583  1015  2933 D BatteryService: level:95, scale:100, status:2, health:2, present:true, voltage: 4250, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-02 19:08:12.583  1015  2933 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 19:08:12.583  1015  2933 D BatteryService: stay LED for charging
09-02 19:08:12.583  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:08:12.593  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 19:08:12.593  1015  1015 I MotionRecognitionService: Plugged
09-02 19:08:12.593  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 19:08:12.593  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-02 19:08:12.593  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 19:08:12.593  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
,09-02 19:08:12.613  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:08:12.613  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:08:12.613  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:08:12.783  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:08:12.783  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:14.843  1015  2736 D SSRM:n  : SIOP:: AP = 320
,09-02 19:08:15.043   292   292 E SMD     : DCD OFF,
,09-02 19:08:15.793  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:15.793  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36b1a7e7 added. We now have 6 listener(s)
,09-02 19:08:15.793  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:15.793  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:15.793  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e770f94 added. We now have 7 listener(s)
,09-02 19:08:15.793  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:15.793  6369  6423 I System.out: IsBluetoothEnabled
,09-02 19:08:15.793  6369  6423 D BluetoothAdapter: disable()
,09-02 19:08:15.803  1015  1476 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-02 19:08:15.803  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:15.803  6369  6423 D BluetoothAdapter: enable()
,09-02 19:08:15.803  1015  1218 W ActivityManager: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:08:15.803  1015  1218 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-02 19:08:15.803  1015  1218 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:08:15.803  1015  1218 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:15.813  1015  1218 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:15.813  1015  1218 D SettingsProvider: name = bluetooth_on
,09-02 19:08:15.813  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:15.813  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:15.813  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-02 19:08:15.813  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-02 19:08:15.823  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:15.823  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:15.823  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:15.823  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:15.843  6977  6977 E Zygote  : MountEmulatedStorage()
09-02 19:08:15.843  6977  6977 I libpersona: KNOX_SDCARD checking this for 1002
09-02 19:08:15.843  6977  6977 E Zygote  : v2
09-02 19:08:15.843  6977  6977 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:15.843  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6977 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 19:08:15.843  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:15.853  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-02 19:08:15.853  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 19:08:15.883  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:15.883  6977  6977 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:15.903  6977  6977 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 19:08:15.903  6977  6977 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:08:15.933  6977  6977 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding GattService
,09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding HeadsetService
,09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding A2dpService
,09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding HidService
,09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding HealthService
09-02 19:08:15.973  6977  6977 D BtSettings.ProfileConfig: Adding PanService
,09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding SapService
,09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding SapClientService
09-02 19:08:15.983  6977  6977 D BtSettings.ProfileConfig: Adding HidDevService
,09-02 19:08:15.983  6977  6977 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-02 19:08:15.983  1015  1138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 19:08:15.983  1015  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.983  1015  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.983  1015  1138 D SettingsProvider: selectionArgs: false
09-02 19:08:15.983  1015  1138 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.983  1015  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.983  1015  1138 D SettingsProvider: ret = -1
,09-02 19:08:15.983  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 19:08:15.983  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.983  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.983  1015  1028 D SettingsProvider: selectionArgs: false
,09-02 19:08:15.983  1015  1028 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.983  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.983  1015  1028 D SettingsProvider: ret = -1
,09-02 19:08:15.983  1015  3045 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:15.993  1015  3045 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  3045 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  3045 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  3045 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  3045 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  3045 D SettingsProvider: ret = -1
,09-02 19:08:15.993  1015  1333 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-02 19:08:15.993  1015  1333 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  1333 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  1333 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  1333 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  1333 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  1333 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  3046 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 19:08:15.993  1015  3046 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 19:08:15.993  1015  3046 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:08:15.993  1015  3046 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  3046 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  3046 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  3046 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  2960 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-02 19:08:15.993  1015  2960 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  2960 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-02 19:08:15.993  1015  2960 D SettingsProvider: selectionArgs: false,
09-02 19:08:15.993  1015  2960 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  2960 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 19:08:15.993  1015  2960 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  2729 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
09-02 19:08:15.993  1015  2729 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  2729 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  2729 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  2729 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  2729 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  2729 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  1493 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-02 19:08:15.993  1015  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  1493 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  1493 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  1493 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:15.993  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 19:08:15.993  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  1027 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  1027 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  1027 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  3169 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:15.993  1015  3169 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  3169 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-02 19:08:15.993  1015  3169 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  3169 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  3169 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  3169 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  3213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 19:08:15.993  1015  3213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 19:08:15.993  1015  3213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:15.993  1015  3213 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  3213 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  3213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  3213 D SettingsProvider: ret = -1
09-02 19:08:15.993  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-02 19:08:15.993  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:15.993  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 19:08:15.993  1015  1476 D SettingsProvider: selectionArgs: false
09-02 19:08:15.993  1015  1476 D SettingsProvider: selectionArgs: 1002
09-02 19:08:15.993  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:15.993  1015  1476 D SettingsProvider: ret = -1
,09-02 19:08:16.013  6977  6977 D BluetoothAdapterState: make
,09-02 19:08:16.013  6977  6977 I bluedroid: init
,09-02 19:08:16.013  6977  6992 I BluetoothAdapterState: Entering OffState
,09-02 19:08:16.013  6977  6977 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-02 19:08:16.013  6977  6977 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 19:08:16.013  6977  6977 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 19:08:16.013  6977  6977 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 19:08:16.013  6977  6977 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-02 19:08:16.023  6977  6977 I bluedroid: get_profile_interface socket
09-02 19:08:16.023  6977  6977 I bluedroid: get_profile_interface map_client
09-02 19:08:16.023  6977  6995 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-02 19:08:16.023  6977  6995 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-02 19:08:16.023  6977  6995 E BluetoothServiceJni: populateRssiValuesNative
09-02 19:08:16.023  6977  6995 I bluedroid: getModelRssiValues
09-02 19:08:16.023  6977  6995 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 19:08:16.023  6977  6995 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:16.023  6977  6977 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-02 19:08:16.023  1015  1015 D SettingsProvider: name = bluetooth_name
,09-02 19:08:16.023  6977  6995 D BluetoothAdapterProperties: Name is: A5-1
,09-02 19:08:16.033  6977  6977 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.033  1015  1493 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
09-02 19:08:16.033  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.033  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.033  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.033  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.033  6977  6985 I bluedroid: config_hci_snoop_log
,09-02 19:08:16.033  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-02 19:08:16.033  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-02 19:08:16.033  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 19:08:16.033  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 19:08:16.033  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 19:08:16.043  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:16.043  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:16.043  6977  6977 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-02 19:08:16.043  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 19:08:16.043  6977  6992 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-02 19:08:16.043  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 19:08:16.043  6977  6992 D BluetoothAdapterProperties: Setting state to 11
09-02 19:08:16.053  6977  6992 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:08:16.053  6977  6992 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:16.053  6977  6992 D BluetoothAdapterService: updateAdapterState state is 11
,09-02 19:08:16.053  6977  6992 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:16.053  6977  6992 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 19:08:16.053  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:16.053  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-02 19:08:16.053  6977  6992 D BluetoothSecureManager: getInstant: null
,09-02 19:08:16.053  6977  6992 D BluetoothSecureManager: calling getMethod for getService
09-02 19:08:16.053  6977  6992 D BluetoothSecureManager: calling getService
,09-02 19:08:16.063  6977  6992 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1b0ca446
,09-02 19:08:16.063  1015  1028 D BluetoothSecureManagerService: isSecureModeEnabled
09-02 19:08:16.063  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 19:08:16.063  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:16.063  1174  1174 D BluetoothTile:  getBluetoothState : 11
09-02 19:08:16.063  1015  1028 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-02 19:08:16.063  6977  6992 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-02 19:08:16.063  1802  1802 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:16.063  6977  6992 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:16.063  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 19:08:16.063  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:16.073  6977  6992 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:16.073  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 19:08:16.073  6977  6992 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-02 19:08:16.073  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:16.073  1015  2729 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:16.073  1015  2960 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:08:16.073  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:08:16.073  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
09-02 19:08:16.073  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:08:16.083  1015  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:08:16.083  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.083  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.083  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:16.083  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:16.083  6977  6992 D BluetoothBondStateMachine: make
,09-02 19:08:16.083  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 19:08:16.083  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 19:08:16.083  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 19:08:16.083  6977  6998 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 19:08:16.093  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:16.093  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.093  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.093  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.093  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.093  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.093  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:08:16.093  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:16.093  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:16.093  6977  6977 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:08:16.103  6977  6977 D BtGatt.GattService: Received start request. Starting profile...
09-02 19:08:16.103  6977  6977 D BtGatt.GattService: start()
09-02 19:08:16.103  6977  6977 D BtGatt.GattService: start()
09-02 19:08:16.103  6977  6977 I bluedroid: get_profile_interface gatt
,09-02 19:08:16.103  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:16.103  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
09-02 19:08:16.103  6977  6977 D BtGatt.AdvertiseManager: advertise manager created
09-02 19:08:16.103  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-02 19:08:16.103  1015  3169 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.103  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.103  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.103  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.103  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.113  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 19:08:16.113  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:16.113  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:16.113  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.113  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:16.113  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.113  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.113  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.113  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-02 19:08:16.113  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:16.123  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:08:16.123  6977  6977 D BtGatt.GattService: mStartError = false
09-02 19:08:16.123  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.123  1015  3213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.123  6977  6977 D HeadsetService: Received start request. Starting profile...
09-02 19:08:16.123  6977  6977 D HeadsetService: start()
09-02 19:08:16.123  1015  3213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.123  6977  6977 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:08:16.123  6977  6977 D HeadsetStateMachine: make
,09-02 19:08:16.123  1015  3213 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.123  1015  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:16.123  1015  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.133  6977  6977 E HeadsetStateMachine: # of Max HF connection is 2
,09-02 19:08:16.133  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-02 19:08:16.133  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:16.133  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:08:16.133  1015  2729 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.133  1015  2729 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.133  1015  2729 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.133  1015  2729 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.133  1015  2729 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.133  1015  1493 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-02 19:08:16.143  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 19:08:16.143  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:16.143  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-02 19:08:16.143  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.143  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.143  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:16.143  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:16.143  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.143  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.143  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.143  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.143  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.143  1015  1333 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-02 19:08:16.153  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-02 19:08:16.153  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:16.153  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:16.153  6977  6992 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:16.153  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.153  1015  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.153  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-02 19:08:16.153  1015  3045 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:16.153  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.153  6977  6977 I bluedroid: get_profile_interface handsfree
09-02 19:08:16.153  1015  3045 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.153  1015  3045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.153  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.153  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 19:08:16.153  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 19:08:16.153  6977  6992 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:08:16.153  1015  3169 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.163  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.163  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.163  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.163  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:16.163  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:16.163  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:16.163  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 19:08:16.163  6977  6992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 19:08:16.163  6977  6992 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:16.163  6977  6992 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 19:08:16.173  6977  6977 I DualScoManager: Instantiating Dual Sco Manager
,09-02 19:08:16.173  6977  6977 I DualScoManager: Set HeadsetServiceHelper
,09-02 19:08:16.173  6977  6977 D BluetoothAtMessage: createCMTIContentObservers
,09-02 19:08:16.173  1015  2960 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-02 19:08:16.173  1015  2960 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:16.173  1015  2960 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:16.173  1015  2960 D SettingsProvider: selectionArgs: false
09-02 19:08:16.173  1015  2960 D SettingsProvider: selectionArgs: 1002
,09-02 19:08:16.173  1015  2960 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:16.173  1015  2960 D SettingsProvider: ret = -1
,09-02 19:08:16.183  6977  7002 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 19:08:16.183  6977  6977 D HeadsetService: mStartError = false
09-02 19:08:16.183  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.183  6977  6977 D A2dpService: Received start request. Starting profile...
,09-02 19:08:16.183  6977  6977 D A2dpService: start()
09-02 19:08:16.183  6977  7002 D HeadsetStateMachine: Clear mHeadsetBrsf
09-02 19:08:16.183  6977  7002 D HeadsetStateMachine: map size, before remove : 0
,09-02 19:08:16.183  6977  7002 D HeadsetStateMachine: map size, after remove: 0
,09-02 19:08:16.183  6977  6977 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 19:08:16.183  6977  6977 I bluedroid: get_profile_interface avrcp
,09-02 19:08:16.193  6977  6977 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 19:08:16.203  6977  6977 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 19:08:16.203  6977  7006 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,09-02 19:08:16.213  6977  6977 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 19:08:16.213  6977  6977 D A2dpStateMachine: make
,09-02 19:08:16.213  6977  6977 I bluedroid: get_profile_interface a2dp
,09-02 19:08:16.213  6977  7008 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-02 19:08:16.213  6977  6977 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 19:08:16.213  6977  6977 D A2dpService: mStartError = false
09-02 19:08:16.213  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.213  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-02 19:08:16.213  6977  6977 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 19:08:16.223  6977  7007 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:08:16.223  6977  6977 D HidService: Received start request. Starting profile...
09-02 19:08:16.223  6977  6977 D HidService: start()
09-02 19:08:16.223  6977  6977 I bluedroid: get_profile_interface hidhost
09-02 19:08:16.223  6977  6977 D HidService: setHidService(): set to: null
09-02 19:08:16.223  6977  6977 D HidService: mStartError = false
09-02 19:08:16.223  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.223  6977  6977 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 19:08:16.223  6977  6977 D HealthService: Received start request. Starting profile...
,09-02 19:08:16.223  6977  6977 D HealthService: start()
,09-02 19:08:16.223  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:16.223  6977  6977 I bluedroid: get_profile_interface health
09-02 19:08:16.223  6977  6977 D HealthService: mStartError = false
09-02 19:08:16.223  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.233  6977  6977 D HeadsetStateMachine: Try to query the phonestate on bind
09-02 19:08:16.233  1431  6487 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 19:08:16.233  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-02 19:08:16.233  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 19:08:16.233  6977  7006 D BluetoothMediaBrowser: no now playing list
09-02 19:08:16.233  6977  7006 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-02 19:08:16.233  1431  6487 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 19:08:16.233  6977  6977 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 19:08:16.233  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:16.233  6977  6977 D PanService: Received start request. Starting profile...
09-02 19:08:16.233  6977  6977 D PanService: start()
09-02 19:08:16.233  6977  6977 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:08:16.233  6977  6977 I bluedroid: get_profile_interface pan
,09-02 19:08:16.233  6977  6977 D PanService: mStartError = false
09-02 19:08:16.233  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:16.233  6977  6977 D HeadsetStateMachine: Proxy object connected
,09-02 19:08:16.233  6977  6977 D BluetoothMapService: Received start request. Starting profile...
,09-02 19:08:16.233  6977  6977 D BluetoothMapService: start()
,09-02 19:08:16.243  6977  6977 D BluetoothMapService: mStartError = false
09-02 19:08:16.243  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
09-02 19:08:16.243  6977  6977 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-02 19:08:16.243  6977  6977 D HeadsetPhoneState: sendDeviceDataStateChanged
09-02 19:08:16.243  6977  7002 D HeadsetStateMachine: Disconnected process message: 11
09-02 19:08:16.243  6977  7002 D HeadsetStateMachine: Disconnected process message: 18
09-02 19:08:16.243  6977  6977 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 19:08:16.243  6977  6977 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 19:08:16.243  6977  6977 D SapService: Received start request. Starting profile...
09-02 19:08:16.243  6977  6977 D SapService: start()
09-02 19:08:16.243  6977  6977 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 19:08:16.243  6977  6977 I bluedroid: get_profile_interface sap
09-02 19:08:16.243  6977  6977 D SapService: mStartError = false
09-02 19:08:16.243  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
09-02 19:08:16.243  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 19:08:16.243  6977  6977 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 19:08:16.243  6977  6977 D BluetoothA2dp: Proxy object connected
09-02 19:08:16.243  6977  6977 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 19:08:16.243  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-02 19:08:16.243  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 19:08:16.243  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-02 19:08:16.243  6977  7002 D HeadsetStateMachine: Disconnected process message: 10
09-02 19:08:16.243  6977  7002 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:08:16.243  6977  7002 D HeadsetStateMachine: Disconnected process message: 11
,09-02 19:08:16.243  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-02 19:08:16.263  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 19:08:16.263  6977  6977 E BluetoothAdapterService(491129200): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 19:08:16.273  6977  6992 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 19:08:16.273  6977  6992 I bluedroid: enable
,09-02 19:08:16.273  6977  6992 I bt_hci_bdroid: init
,09-02 19:08:16.273  6977  7012 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-02 19:08:16.273  6977  6992 I bt_vendor: bt-vendor : init
,09-02 19:08:16.273  6977  6992 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 19:08:16.273  6977  6992 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-02 19:08:16.273  6977  6992 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-02 19:08:16.273  6977  6992 D bt_userial_mct: userial_init
,09-02 19:08:16.273  6977  6992 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 19:08:16.273  6977  6992 I bt_vendor: Starting hciattach daemon
,09-02 19:08:16.273  6977  6992 I bt_vendor: try to set false
,09-02 19:08:16.273  6977  6992 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 19:08:16.273  6977  6992 I bt_vendor: Starting hciattach daemon
,09-02 19:08:16.273  6977  6992 I bt_vendor: try to set true
,09-02 19:08:16.293  7016  7016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-02 19:08:16.343  7022  7022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-02 19:08:16.353  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 19:08:16.363  7025  7025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 19:08:16.373  7026  7026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-02 19:08:16.383  7027  7027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 19:08:16.393  7028  7028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-02 19:08:16.633  7031  7031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-02 19:08:16.643  7032  7032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 19:08:16.683  6977  6992 I bt_vendor: bluetooth satus is on
,09-02 19:08:16.683  6977  7014 D bt_userial_mct: userial_open(port:0)
09-02 19:08:16.683  6977  7014 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 19:08:16.683  6977  7014 I bt_vendor: Done intiailizing UART,
,09-02 19:08:16.683  6977  7014 I bt_vendor: Done intiailizing UART,
09-02 19:08:16.683  6977  7014 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-02 19:08:16.683  6977  7014 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 19:08:16.693  6977  7034 D bt_userial_mct: Entering userial_read_thread()
,09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_SAP
,09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 19:08:16.693  6977  7012 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 19:08:16.703  6977  7012 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 19:08:16.703  6977  7012 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 19:08:16.703  6977  7012 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 19:08:16.803  6977  7012 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 19:08:16.803  6977  7012 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40c36e9 
,09-02 19:08:16.803  6977  7012 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40c36e9 
,09-02 19:08:16.833  6977  6995 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 19:08:16.833  6977  6995 E bt-btif : Calling BTA_HhEnable
,09-02 19:08:16.833  6977  6995 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 19:08:16.833  6977  6995 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-02 19:08:16.833  6977  6995 E BluetoothServiceJni: populateRssiValuesNative
09-02 19:08:16.833  6977  6995 I bluedroid: getModelRssiValues
,09-02 19:08:16.833  6977  6995 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 19:08:16.833  6977  6995 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:16.833  1015  1015 D SettingsProvider: name = bluetooth_name
,09-02 19:08:16.833  6977  6995 D BluetoothAdapterProperties: Name is: A5-1
,09-02 19:08:16.843  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 19:08:16.843  6977  6995 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:16.843  6977  6995 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:16.843  6977  6995 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:08:16.843  6977  6995 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-02 19:08:16.843  6977  6995 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-02 19:08:16.843  6977  6995 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-02 19:08:16.843  6977  6995 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-02 19:08:16.843  6977  7034 E bt_mct  : hci lib postload completed
09-02 19:08:16.843  6977  6995 E bt-btif : btif_sock_init: !vhci_init
,09-02 19:08:16.853  6977  6995 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-02 19:08:16.853  6977  6995 D IOP_DB_BT: db_open: db_open : handle 3028574224l, read 13894 bytes onto local cache
,09-02 19:08:16.853  6977  6995 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-02 19:08:16.853  6977  6995 D IOP_DB_BT: db_query: result 1
09-02 19:08:16.853  6977  6995 I         : iop_db_open: iop_db_open status 0
,09-02 19:08:16.853  6977  6995 D bte_conf: Device ID record 1 : primary
09-02 19:08:16.853  6977  6995 D bte_conf:   vendorId            = 0075
09-02 19:08:16.853  6977  6995 D bte_conf:   vendorIdSource      = 0001
09-02 19:08:16.853  6977  6995 D bte_conf:   product             = 0100
09-02 19:08:16.853  6977  6995 D bte_conf:   version             = 0200
09-02 19:08:16.853  6977  6995 D bte_conf:   clientExecutableURL = 
09-02 19:08:16.853  6977  6995 D bte_conf:   serviceDescription  = 
09-02 19:08:16.853  6977  6995 D bte_conf:   documentationURL    = 
09-02 19:08:16.853  6977  6995 D bte_conf: bte_load_did_conf no section named DID2.
,09-02 19:08:16.853  6977  6995 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 19:08:16.853  6977  6992 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 19:08:16.853  6977  6992 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:08:16.853  6977  6992 D BluetoothAdapterProperties: State =  11
,09-02 19:08:16.863  1015  1333 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:08:16.863  6977  6992 D BluetoothAdapterProperties: Setting state to 12
,09-02 19:08:16.863  6977  6992 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 19:08:16.863  1015  2960 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-02 19:08:16.863  1015  2960 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:16.863  1015  2960 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:16.863  1015  2960 D SettingsProvider: selectionArgs: false
09-02 19:08:16.863  1015  2960 D SettingsProvider: selectionArgs: 1002
09-02 19:08:16.863  1015  2960 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:16.863  1015  2960 D SettingsProvider: ret = -1
09-02 19:08:16.863  6977  6992 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:16.863  6977  6992 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 19:08:16.863  1015  3045 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:16.863  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.873  1015  3045 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.873  1015  3045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.873  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.873  6977  6992 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:16.873  6977  6992 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-02 19:08:16.873  6977  6992 D BluetoothAdapterService: starting service from this receiver
,09-02 19:08:16.873  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:16.873  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.873  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.873  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.873  1312  1338 D BluetoothPan: Binding service...
09-02 19:08:16.873  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.873  6977  6992 I BluetoothAdapterState: Entering On State from state = 11
,09-02 19:08:16.883  6977  6995 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:16.883  6977  6995 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:08:16.883  6977  6995 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:08:16.883  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 19:08:16.883  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.883  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.883  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.883  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:16.883  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:16.893  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:16.893  1440  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:16.893  1440  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.893  1312  1326 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.893  1312  1326 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:16.893  6977  6996 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:16.893  1312  1330 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:08:16.903  6977  6977 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 19:08:16.903  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-02 19:08:16.903  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.903  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.903  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.903  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.903  1454  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.903  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:16.903  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.913  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.913  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.913  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.913  1454  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.913  1431  1439 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.913  1431  1439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.913  1944  2114 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.913  1944  2114 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.913  1174  3756 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:16.913  1174  3756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.923  6977  6977 I BluetoothPbapService: Handler(): got msg=1
09-02 19:08:16.923  6461  6473 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.923  6461  6473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.923  2888  6942 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:16.923  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:08:16.923  1312  1312 D PanProfile: Bluetooth service connected
,09-02 19:08:16.923  1015  1218 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:16.923  2888  6942 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.923  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:16.923  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:16.923  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.923  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.923  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.923  2888  6942 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.923  2888  6942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.923  2888  2888 D BluetoothA2dp: Proxy object connected
09-02 19:08:16.923  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:16.923  1312  1326 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.933  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:16.933  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.933  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.933  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.933  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.933  6977  7037 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 19:08:16.933  1431  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.933  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.933  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.933  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.933  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.933  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.933  1431  1449 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:16.933  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.933  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.933  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.933  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.933  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.933  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.933  1312  1326 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.933  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.933  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.943  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.943  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.943  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-02 19:08:16.943  1312  1312 D BluetoothA2dp: Proxy object connected
09-02 19:08:16.943  1312  1312 D A2dpProfile: Bluetooth service connected
,09-02 19:08:16.943  1312  1326 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.943  1454  2436 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:16.943  1454  2436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.943  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.943  6977  7037 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:16.943  6977  7037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:16.943  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.943  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.943  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.943  1312  1312 D BluetoothMap: Proxy object connected
09-02 19:08:16.943  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.943  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 19:08:16.943  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.943  1312  1312 D MapProfile: Bluetooth service connected
09-02 19:08:16.943  1312  1312 D BluetoothMap: getConnectedDevices()
09-02 19:08:16.943  6977  7037 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-02 19:08:16.943  6977  7037 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:16.943  6977  7037 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:16.943  6977  7037 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2167dff5
,09-02 19:08:16.943  6977  7037 D BluetoothSocket: channel: 19
09-02 19:08:16.943  6977  7037 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-02 19:08:16.943  1431  6487 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.953  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.953  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.953  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.953  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.953  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 19:08:16.953  1431  6487 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.953  1312  1312 D HeadsetProfile: Bluetooth service connected
,09-02 19:08:16.953  2888  2909 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:16.953  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:16.953  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:16.953  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.953  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.953  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.953  2888  2909 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:16.953  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:16.953  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 19:08:16.953  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:16.953  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.953  1015  1015 D BluetoothA2dp: Proxy object connected
,09-02 19:08:16.953  1312  1338 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 19:08:16.953  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 19:08:16.953  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.963  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.963  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.963  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.963  1312  1312 D BluetoothPbap: Proxy object connected
09-02 19:08:16.963  1312  1312 D PbapServerProfile: Bluetooth service connected
09-02 19:08:16.963  6369  6378 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.963  6369  6378 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:16.963  1312  1326 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 19:08:16.963  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-02 19:08:16.963  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.963  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.963  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.963  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.963  6977  6986 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:16.963  6977  6986 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:16.963  1312  1330 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 19:08:16.963  1312  1330 D Bluetoothsap: Binding service...
,09-02 19:08:16.963  1312  1312 D BluetoothInputDevice: Proxy object connected
09-02 19:08:16.963  1312  1312 D HidProfile: Bluetooth service connected
,09-02 19:08:16.963  1312  1330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 19:08:16.963  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 19:08:16.973  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.973  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.973  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:16.973  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:16.973  1312  1330 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-02 19:08:16.973  1015  1044 D BluetoothPan: Binding service...
,09-02 19:08:16.973  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-02 19:08:16.973  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.973  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 19:08:16.973  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 19:08:16.973  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 19:08:16.973  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-02 19:08:16.973  1312  1312 D SapProfile: Bluetooth service connected
09-02 19:08:16.973  1312  1312 D Bluetoothsap: getConnectedDevices()
,09-02 19:08:16.973  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:16.973  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-02 19:08:16.973  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:16.983  1174  1174 D BluetoothTile:  onBluetoothStateChange:,
09-02 19:08:16.983  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@27f483e7, true
09-02 19:08:16.983  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 19:08:16.983  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:16.983  1174  1174 D BluetoothTile:  getBluetoothState : 12,
,09-02 19:08:16.983  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:16.983  1431  1431 D BluetoothHeadset: registerMessageListener
,09-02 19:08:16.993  1802  1802 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:16.993  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:16.993  1174  1722 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:16.993  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:16.993  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:16.993  1015  1333 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:16.993  1015  1333 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 19:08:16.993  1015  1333 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:16.993  1015  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:17.003  1015  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:17.003  1015  2933 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:17.003  6977  7040 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 19:08:17.003  6977  6986 D HeadsetService: registerMessageListener
,09-02 19:08:17.003  1015  3044 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 19:08:17.003  6977  6986 D HeadsetService: registerMessageListener
,09-02 19:08:17.003  6977  7002 D HeadsetStateMachine: Disconnected process message: 70
09-02 19:08:17.003  6977  7002 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@bf5318a
,09-02 19:08:17.003  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:17.003  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 19:08:17.003  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 19:08:17.003  1312  1312 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-02 19:08:17.003  1312  1312 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 19:08:17.003  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 19:08:17.013  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 19:08:17.013  6977  7040 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:17.013  6977  7040 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:17.013  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 19:08:17.013  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 19:08:17.013  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-02 19:08:17.013  6977  7002 D HeadsetStateMachine: Disconnected process message: 9
,09-02 19:08:17.013  6977  7002 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 19:08:17.013  6977  7040 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-02 19:08:17.013  6977  7040 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:17.013  6977  7040 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:17.013  6977  7040 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273a53fb
,09-02 19:08:17.013  6977  7040 D BluetoothSocket: channel: 5
,09-02 19:08:17.013  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:17.023  1015  3169 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:08:17.023  1015  3169 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:17.023  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:17.023  1015  3169 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:17.023  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:17.023   283   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-02 19:08:17.023   283   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-02 19:08:17.023   283   693 V voice   : voice_set_parameters: exit with code(-2)
,09-02 19:08:17.023   283   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-02 19:08:17.023   283   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 19:08:17.023   283   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 19:08:17.023   283   693 V audio_hw_primary: adev_set_parameters: exit
,09-02 19:08:17.023  6977  7002 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 19:08:17.033  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:17.033  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:17.043  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:17.043  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 19:08:17.043  6977  6977 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:17.043  6977  6977 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 19:08:17.053  1015  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:17.053  1015  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 19:08:17.053  1015  1493 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:17.053  1015  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:17.053  1015  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:17.073  1944  1944 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:17.073  1015  2960 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 19:08:17.073  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:17.073  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:17.073  1015  2960 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:17.073  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:17.083  1015  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:17.083  1944  1944 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 19:08:17.093  1944  7047 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 19:08:17.093  1015  3169 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:17.093  1015  3169 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:17.093  1015  3169 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:17.093  1015  3169 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:08:17.103  6977  7050 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 19:08:17.103  6977  7050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:17.113  6977  7050 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-02 19:08:17.113  6977  7050 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:17.113  6977  7050 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:17.113  6977  7050 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@91918ad
09-02 19:08:17.113  6977  7050 D BluetoothSocket: channel: 12
09-02 19:08:17.113  6977  7050 I BtOppRfcommListener: Accept thread started.
,09-02 19:08:17.113  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:17.113  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:17.113  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:17.113  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-02 19:08:17.123  1944  7047 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:17.823  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:17.823  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:17.823  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:17.823  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe8ea3d added. We now have 8 listener(s)
09-02 19:08:17.823  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:17.833  1015  1218 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:08:17.833  1015  1218 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 19:08:17.833  1015  1218 D SecContentProvider2: mCursor = null
,09-02 19:08:17.833  1015  1218 D WifiService: setWifiEnabled: false pid=6369, uid=10155
,09-02 19:08:17.833  1015  1218 D SettingsProvider: name = wifi_on
,09-02 19:08:17.833  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:17.833  1015  3046 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 19:08:17.833  1015  3046 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:08:17.833  1015  3046 D SecContentProvider2: mCursor = null
,09-02 19:08:17.843  1015  3046 D WifiService: setWifiEnabled: true pid=6369, uid=10155
,09-02 19:08:17.843  1015  3046 W WifiService: Failed getting userId using ActivityManagerNative
09-02 19:08:17.843  1015  3046 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:17.843  1015  3046 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-02 19:08:17.843  1015  3046 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:08:17.843  1015  3046 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:08:17.843  1015  3046 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:08:17.843  1015  3046 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 19:08:17.843  1015  3046 W ActivityManager: Permission Denial: getCurrentUser() from pid=6369, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
09-02 19:08:17.843  1015  3046 D SettingsProvider: name = wifi_on
,09-02 19:08:17.843  1015  1129 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 19:08:18.043   292   292 E SMD     : DCD OFF
,09-02 19:08:18.213  1015  1042 D Tethering: interfaceAdded wlan0
,09-02 19:08:18.213  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:08:18.213  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-02 19:08:18.213  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:18.223  1015  1133 E Tethering: No numeric data
,09-02 19:08:18.223  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:18.223  1015  1133 D Tethering: clearTetheredNotification()
09-02 19:08:18.223  1015  1133 D Tethering: InitialState.processMessage what=4
,09-02 19:08:18.233  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:18.233  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.233   278   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 19:08:18.233   278   972 D SoftapController: Softap fwReload - Ok
09-02 19:08:18.233  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-02 19:08:18.233  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-02 19:08:18.233  1015  1042 D Tethering: interfaceAdded p2p0
09-02 19:08:18.233  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:18.233  1015  1133 E Tethering: No numeric data
09-02 19:08:18.233  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:08:18.233  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
09-02 19:08:18.243  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:18.233   278   972 D CommandListener: Setting iface cfg
09-02 19:08:18.233   278   972 D CommandListener: Trying to bring down wlan0,
,09-02 19:08:18.243  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:18.243  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:08:18.243  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:08:18.243  1015  1133 D Tethering: clearTetheredNotification()
,09-02 19:08:18.243   278   972 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:08:18.253  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.253  1015  1122 V NetworkStats: performPollLocked() took 22ms
09-02 19:08:18.253  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:18.253  1174  1174 D HotspotTile: updateTetherState():false, false
,09-02 19:08:18.253  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:18.253  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.253  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-02 19:08:18.253  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-02 19:08:18.263  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.263  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.263  1015  1129 E WifiHW  : supplicant_name : p2p_supplicant,
09-02 19:08:18.263  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.263  1015  1122 V NetworkStats: performPollLocked() took 6ms
,09-02 19:08:18.263  1015  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-02 19:08:18.273  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.273  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.273  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:18.273  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:18.273  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:18.283  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:18.273  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:08:18.283  1174  1174 D HotspotTile: onReceive : 2, 0
,09-02 19:08:18.273  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:18.273  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:08:18.273  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.273  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:18.273  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-02 19:08:18.283  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:18.283  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:18.293  1015  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:18.293  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:18.293  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:18.293  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:18.293  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:18.293  3635  3635 I Hs20UtilService: Starting #17
,09-02 19:08:18.293  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:18.303  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:18.303  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 19:08:18.303  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:18.303  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:18.313  7064  7064 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-02 19:08:18.313  7064  7064 I wpa_supplicant: Successfully initialized wpa_supplicant
09-02 19:08:18.313  7064  7064 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 19:08:18.323  7064  7064 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-02 19:08:18.333   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7064
09-02 19:08:18.333   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 19:08:18.333  7064  7064 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 19:08:18.333  7064  7064 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:18.333  7064  7064 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 19:08:18.333  7064  7064 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-02 19:08:18.333   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7064,
09-02 19:08:18.333   404   404 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-02 19:08:18.463   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-02 19:08:18.473  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-02 19:08:18.543  7064  7064 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:18.543  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 19:08:18.553  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-02 19:08:18.553   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7064
09-02 19:08:18.553   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,09-02 19:08:18.553  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 19:08:18.553  7064  7064 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:18.553  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:18.553  7064  7064 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 19:08:18.553  7064  7064 E wpa_supplicant: SIM READ ERROR
09-02 19:08:18.553  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:18.553  7064  7064 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:18.553  7064  7064 E wpa_supplicant: SIM READ ERROR
09-02 19:08:18.553  7064  7064 I wpa_supplicant: Blacklist: Clear (all) ,
09-02 19:08:18.553  7064  7064 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:18.553  7064  7064 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:18.553  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:18.553  7064  7064 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,09-02 19:08:18.553  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:18.553  7064  7064 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 19:08:18.553  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-02 19:08:18.553  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 19:08:18.553  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:18.553  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:18.633  7064  7064 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-02 19:08:19.263  7064  7064 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-02 19:08:19.263  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 19:08:19.273  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-02 19:08:19.283   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7064
09-02 19:08:19.283   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-02 19:08:19.283  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 19:08:19.283  7064  7064 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:19.283  7064  7064 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-02 19:08:19.283  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-02 19:08:19.293  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-02 19:08:19.293   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7064
09-02 19:08:19.293   404   404 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-02 19:08:19.293  7064  7064 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-02 19:08:19.293  7064  7064 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:19.293  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-02 19:08:19.293  7064  7064 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:19.293  7064  7064 E wpa_supplicant: SIM READ ERROR
09-02 19:08:19.293  7064  7064 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:19.293  7064  7064 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-02 19:08:19.293  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 19:08:19.303  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:19.303  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:19.303  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:19.373  7064  7064 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-02 19:08:19.373  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=,
,09-02 19:08:19.433  7064  7064 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-02 19:08:19.433  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-02 19:08:19.433  7064  7064 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:19.443  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-02 19:08:19.443  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:19.443  7064  7064 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-02 19:08:19.443  7064  7064 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-02 19:08:19.453  7064  7064 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 19:08:19.453  7064  7064 E wpa_supplicant: SIM READ ERROR
,09-02 19:08:19.453  7064  7064 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:19.463  7064  7064 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-02 19:08:19.473  1015  1129 D WifiNative-wlan0: callSECApiInt - ID [210],
09-02 19:08:19.473  7064  7064 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:19.473  1015  1129 D WifiConfigStore: Loading config and enabling all networks 
,09-02 19:08:19.473  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.473  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:19.473  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:19.473  1174  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:19.473  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.473  1174  1174 D HotspotTile: onReceive : 3, 0
09-02 19:08:19.473  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.473  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.473  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.473  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:19.473  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-02 19:08:19.483  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:19.483  6369  6369 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:19.493  1015  3046 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:19.493  1015  3046 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:19.493  6369  6369 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:19.493  1015  3046 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:19.493  1015  3046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:19.493  1015  3046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
09-02 19:08:19.493  1015  1129 E WifiConfigStore: Not a HS20
09-02 19:08:19.493  3635  3635 I Hs20UtilService: Starting #18
09-02 19:08:19.493  1015  1129 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 19:08:19.493  3635  3663 I Hs20UtilService: Message received 5011
,09-02 19:08:19.493  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:19.493  6573  6573 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:19.493  6573  6573 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:19.493  6573  6573 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:19.493  1015  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 19:08:19.493  1015  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 19:08:19.493  7064  7064 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 19:08:19.503  7064  7064 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 19:08:19.503  7064  7064 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:08:19.503  7064  7064 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:08:19.503  7064  7064 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 19:08:19.503  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 19:08:19.503  7064  7064 I wpa_supplicant: First Scan Start
09-02 19:08:19.503  7064  7064 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 19:08:19.503  1015  1129 D WifiNative-wlan0: Setting external_sim to 1
,09-02 19:08:19.503  1015  1129 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:08:19.503  1015  1129 I WifiNative-HAL: startHal
09-02 19:08:19.503  1015  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9ccab88c
09-02 19:08:19.503  1015  1129 I WifiNative-HAL: Could not start hal
,09-02 19:08:19.503  6544  6544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:19.513  1015  1129 E WifiNative-wlan0: do suspend true
,09-02 19:08:19.513  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 19:08:19.513  1015  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 19:08:19.513  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 19:08:19.513  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:19.513  1015  1149 I WifiNative-HAL: startHal
09-02 19:08:19.513   278   972 D CommandListener: Setting iface cfg
09-02 19:08:19.513  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e0659bc
09-02 19:08:19.513  1015  1149 I WifiNative-HAL: Could not start hal
09-02 19:08:19.513  1015  1149 E WifiScanningService: could not start HAL
09-02 19:08:19.513   278   972 D CommandListener: Trying to bring up p2p0
09-02 19:08:19.513  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-02 19:08:19.513  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:19.513  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 19:08:19.513  1015  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 19:08:19.513  1015  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:19.513  1015  1129 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:19.513  1015  1124 D WifiP2pService: P2pEnablingState
,09-02 19:08:19.513  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-02 19:08:19.513  1015  1124 D WifiP2pService: P2p socket connection successful
09-02 19:08:19.513  1015  1124 D WifiP2pService: P2pEnabledState
,09-02 19:08:19.513  1015  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-02 19:08:19.523  1015  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:19.523  1015  1129 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:19.523  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 19:08:19.523  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:19.523  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 19:08:19.523  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:19.523  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-02 19:08:19.523  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 19:08:19.523  1015  1045 D WifiDisplayController: disconnect
,09-02 19:08:19.523  1015  1045 D WifiDisplayController: updateConnection
09-02 19:08:19.523  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:19.523  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 19:08:19.523  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:19.533  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 19:08:19.533  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:19.533  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:19.533  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-02 19:08:19.533  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:19.533  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:08:19.533  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 19:08:19.533  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:19.533  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:08:19.533  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-02 19:08:19.533  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:19.533  1015  1129 D SecContentProvider2: mCursor = null
09-02 19:08:19.533  1015  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
09-02 19:08:19.533  1015  3045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:19.533  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:08:19.533  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  secondary type: null
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  wps: 0
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  grpcapab: 0
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  devcapab: 0
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  status: 3
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  wfdInfo: null
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  GOdeviceName: null
,09-02 19:08:19.533  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-02 19:08:19.533  1015  1045 D WifiDisplayController:  SConnectInfo : null
09-02 19:08:19.533  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:19.533  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:19.533  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:19.543  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:08:19.543  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-02 19:08:19.543  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:08:19.543  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:19.543  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:19.553  6514  6514 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 19:08:19.553  6514  6514 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:19.553  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 19:08:19.553  1015  1124 D WifiP2pService: InactiveState
,09-02 19:08:19.553  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-02 19:08:19.553  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
09-02 19:08:19.553  6529  6529 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:19.553  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:19.563  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-02 19:08:19.563  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:19.863  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:19.863  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:19.873  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 19:08:19.873  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 19:08:19.873  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3b66aea0 Bundle[{}]
,09-02 19:08:19.873  6369  6423 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:08:19.873  6369  6423 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 19:08:19.883  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 19:08:19.883  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 19:08:19.883  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 19:08:19.883  6369  6423 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 19:08:19.883  6369  6423 I System.out: Running OutgoingSocketThread
,09-02 19:08:19.893  6369  7071 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1182)
,09-02 19:08:19.893  6369  7071 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 59956
,09-02 19:08:19.893  6369  7071 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 19:08:20.003   331   331 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-02 19:08:20.003   331   331 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-02 19:08:20.653  7064  7064 I wpa_supplicant: nl80211: Received scan results (38 BSSes),
,09-02 19:08:20.653  7064  7064 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 19:08:20.653  7064  7064 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 19:08:20.653  7064  7064 I wpa_supplicant: Trying to associate with  'G700'
09-02 19:08:20.653  7064  7064 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-02 19:08:20.653  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-02 19:08:20.653  1015  7069 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-02 19:08:20.673  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:20.673  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:20.763  7064  7064 E wpa_supplicant: Cmd 35605 not handled
,09-02 19:08:20.763  7064  7064 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:20.763  7064  7064 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-02 19:08:20.773  7064  7064 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-02 19:08:20.773  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-02 19:08:20.773  7064  7064 I wpa_supplicant: Associated with F4.99.3E
09-02 19:08:20.773  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:20.773  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:20.773  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:20.773  7064  7064 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:20.773  7064  7064 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 19:08:20.773  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-02 19:08:20.773  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:20.773  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:20.773  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:20.773  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:08:20.773  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-02 19:08:20.773  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:20.773  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 19:08:20.773  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:20.773  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-02 19:08:20.783  1015  1133 E Tethering: No numeric data
,09-02 19:08:20.783  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:20.783  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:20.783  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:20.783  1015  1133 D Tethering: clearTetheredNotification()
,09-02 19:08:20.783  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-02 19:08:20.783  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:20.783  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:08:20.783  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,09-02 19:08:20.783  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:20.783  1174  1174 D HotspotTile: updateTetherState():false, false
09-02 19:08:20.793  7064  7064 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:20.793  1015  1122 V NetworkStats: performPollLocked() took 6ms
09-02 19:08:20.793  7064  7064 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-02 19:08:20.793  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:20.793  7064  7064 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-02 19:08:20.793  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:20.793  7064  7064 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:08:20.793  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 19:08:20.793  7064  7064 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-02 19:08:20.793  7064  7064 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-02 19:08:20.793  7064  7064 I wpa_supplicant: Blacklist: Clear (temp) 
09-02 19:08:20.793  7064  7064 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-02 19:08:20.793  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:20.793  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-02 19:08:20.793  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:20.793  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:20.793  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:20.793  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:20.803  1015  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 19:08:20.813  1015  1129 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-02 19:08:20.813  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:08:20.813  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:20.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:20.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:20.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:20.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:20.823  1015  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
09-02 19:08:20.823  1015  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-02 19:08:20.823  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:08:20.823  1015  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 19:08:20.823  1015  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:08:20.823  1015  3045 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:20.823  1015  3045 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:20.823  1015  3045 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:20.823  1015  3045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:20.823  1015  3045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:20.833  3635  3635 I Hs20UtilService: Starting #19
,09-02 19:08:20.833  3635  3663 I Hs20UtilService: Message received 5007
09-02 19:08:20.833  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:08:20.833  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:20.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:20.833  1015  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-02 19:08:20.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:20.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:20.833  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:20.843  1312  3091 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:20.853   278   972 D CommandListener: Setting iface cfg,
,09-02 19:08:20.853  1015  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,09-02 19:08:20.853  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:20.853  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:20.863  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:20.863  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:20.863  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:20.863  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:20.863  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:20.863  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:20.873  1015  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:20.873  1015  1129 D SecContentProvider2: mCursor = null
,09-02 19:08:20.883  1015  1129 E WifiNative-wlan0: do suspend false
,09-02 19:08:20.883  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-02 19:08:20.883  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:08:20.893  6369  6423 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1183)
,09-02 19:08:20.893  6369  6423 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1183)
,09-02 19:08:20.893  6369  6423 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1188)
,09-02 19:08:20.893  6369  6423 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 19:08:20.893  6369  6423 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1189)
,09-02 19:08:20.893  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:08:20.893  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b88232 added. We now have 2 listener(s)
,09-02 19:08:20.903  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:08:20.903  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:08:20.903  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:08:20.903  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:20.903  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be6db83 added. We now have 9 listener(s)
09-02 19:08:20.903  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:20.903  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:20.903  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:20.913  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:20.913  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:20.913  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:20.913  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:20.913  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47eed39 added. We now have 3 listener(s)
,09-02 19:08:20.913  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:20.913  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:20.913  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:08:20.913  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:08:20.913  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:08:20.913  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:20.913  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9688f7e added. We now have 10 listener(s)
09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:20.923  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:20.923  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:20.923  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:20.923  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b88232 removed from the list
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be6db83 removed from the list
,09-02 19:08:20.923  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:20.923  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 19:08:20.923  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be6db83 not in the list
09-02 19:08:20.923  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9688f7e removed from the list
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:20.923  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47eed39 removed from the list
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b1acdf added. We now have 2 listener(s)
,09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 19:08:20.923  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fccbd2c added. We now have 9 listener(s)
09-02 19:08:20.923  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:20.923  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:20.933  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:20.933  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:20.933  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-02 19:08:20.933  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:20.933  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:20.933  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167a258a added. We now have 3 listener(s)
,09-02 19:08:20.933  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:20.933  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:20.943  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-02 19:08:20.943  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:20.943  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:20.943  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 19:08:20.943  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2e37fb added. We now have 10 listener(s)
09-02 19:08:20.943  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:20.943  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:08:20.943  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:20.943  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:20.943  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:20.943  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:08:20.943  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:20.943  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:08:20.943  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:08:20.953  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-02 19:08:20.953  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:20.953  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:20.953  6977  6997 D BtGatt.GattService: registerClient() - UUID=a24a8fa1-7a03-4e3f-b1fa-143230ae6ba4,
,09-02 19:08:20.993  6977  6995 D BtGatt.GattService: onClientRegistered() - UUID=a24a8fa1-7a03-4e3f-b1fa-143230ae6ba4, clientIf=6
,09-02 19:08:21.003  6369  6377 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:08:21.003  6977  6986 D BtGatt.GattService: start scan with filters
,09-02 19:08:21.003  6977  7001 D BtGatt.ScanManager: handling starting scan
,09-02 19:08:21.003  6977  7001 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d460970
,09-02 19:08:21.013  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:08:21.013  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:08:21.013  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:08:21.013  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:08:21.013  6977  6995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:08:21.013  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.013  6977  7001 D BtGatt.ScanManager: allow scan with filters
09-02 19:08:21.013  6977  7001 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 19:08:21.013  6977  7001 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6,
,09-02 19:08:21.013  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:08:21.013  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-02 19:08:21.013  6977  7001 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:08:21.013  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:21.013  6977  7001 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:08:21.023  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-02 19:08:21.023  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:21.023  6977  6995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:21.023  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.023  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:08:21.023  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:08:21.023  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.033  6369  6423 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:08:21.033  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:21.033  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
,09-02 19:08:21.033  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 19:08:21.033  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-02 19:08:21.033  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,09-02 19:08:21.033  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:08:21.033  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:08:21.033  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:08:21.033  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:08:21.033  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 19:08:21.043  6977  7039 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:08:21.043  6977  6997 D BtGatt.GattService: unregisterClient() - clientIf=6
09-02 19:08:21.043   292   292 E SMD     : DCD OFF
09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:08:21.043  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:08:21.043  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:08:21.043  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:08:21.043  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:08:21.053  6977  7001 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27
09-02 19:08:21.053  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:21.053  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:08:21.053  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:21.053  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:21.053  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:21.053  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:21.053  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.053  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.053  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.053  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b1acdf removed from the list
09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.053  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fccbd2c removed from the list
09-02 19:08:21.053  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:21.053  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.053  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:21.053  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:21.053  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.053  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fccbd2c not in the list
09-02 19:08:21.053  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.053  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.053  6977  7001 D BtGatt.ScanManager: filter size is 1
09-02 19:08:21.053  6977  7001 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 19:08:21.063  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 19:08:21.063  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.063  6977  7001 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:08:21.063  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:21.063  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.063  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2e37fb removed from the list
09-02 19:08:21.063  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.063  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.063  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:21.063  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167a258a removed from the list
,09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1e58d7 added. We now have 2 listener(s)
,09-02 19:08:21.063  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:08:21.063  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:08:21.063  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:08:21.063  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.063  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:21.063  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224785c4 added. We now have 9 listener(s)
09-02 19:08:21.063  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:21.073  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:08:21.073  6977  7001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:08:21.073  6977  6995 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:08:21.073  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.073  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:21.073  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:21.083  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:21.083  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:08:21.083  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:21.083  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17b1dbe2 added. We now have 3 listener(s)
,09-02 19:08:21.083  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 19:08:21.083  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:21.083  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:21.083  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:21.083  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a85ab73 added. We now have 10 listener(s)
09-02 19:08:21.083  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:21.083  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:08:21.083  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:21.083  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:21.083  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:21.083  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:21.083  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:08:21.083  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:21.093  7077  7077 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
09-02 19:08:21.103  7077  7077 I dhcpcd  : version 5.5.6 starting
,09-02 19:08:21.103  7077  7077 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-02 19:08:21.103  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-02 19:08:21.103  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:08:21.113  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-02 19:08:21.113  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:21.113  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:21.123  6977  7039 D BtGatt.GattService: registerClient() - UUID=c3925b34-c8ce-4fa3-96a5-ee1d4c59484d
,09-02 19:08:21.133  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.133  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.163  7077  7077 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-02 19:08:21.163  7077  7077 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-02 19:08:21.163  7077  7077 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-02 19:08:21.163  7077  7077 I dhcpcd  : bssid match
09-02 19:08:21.163  7077  7077 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
09-02 19:08:21.163  6977  6995 D BtGatt.GattService: onClientRegistered() - UUID=c3925b34-c8ce-4fa3-96a5-ee1d4c59484d, clientIf=6
09-02 19:08:21.163  6369  6377 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:08:21.163  6977  6996 D BtGatt.GattService: start scan with filters
09-02 19:08:21.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:08:21.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-02 19:08:21.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 19:08:21.163  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: handling starting scan
,09-02 19:08:21.163  6977  6995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:08:21.163  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: allow scan with filters
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-02 19:08:21.163  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:08:21.163  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-02 19:08:21.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:08:21.163  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:08:21.163  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:08:21.163  6977  7001 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:08:21.173  6977  6995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:21.173  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.173  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:08:21.173  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:08:21.173  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.183  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:21.183  6369  6423 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-02 19:08:21.183  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:21.183  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:21.183  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.183  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.183  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1e58d7 removed from the list
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.183  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224785c4 removed from the list
09-02 19:08:21.183  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:21.183  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 19:08:21.183  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:21.183  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224785c4 not in the list
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:08:21.183  6977  7039 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:08:21.183  6977  6996 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:21.183  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-02 19:08:21.183  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:21.193  6977  7001 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:21.193  6977  7001 D BtGatt.ScanManager: filter size is 1
09-02 19:08:21.193  6977  7001 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:21.193  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:21.193  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a85ab73 removed from the list
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:08:21.193  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.193  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17b1dbe2 removed from the list
,09-02 19:08:21.193  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:08:21.193  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.193  6977  7001 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38058bcf added. We now have 2 listener(s)
,09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:21.193  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0fc95c added. We now have 9 listener(s)
09-02 19:08:21.193  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:21.193  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:08:21.193  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.193  6977  7001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:08:21.193  6977  6995 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 19:08:21.193  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:21.203  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:21.203  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:21.203  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:21.203  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:21.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:21.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19af053a added. We now have 3 listener(s)
,09-02 19:08:21.203  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.203  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.203  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-02 19:08:21.203  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:21.203  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:21.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:21.203  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f915eb added. We now have 10 listener(s)
09-02 19:08:21.203  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:21.203  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:21.203  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:21.203  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:21.203  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:21.203  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:08:21.213  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:21.213  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:08:21.213  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:08:21.213  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:08:21.213  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:21.213  6369  6423 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:21.223  6977  6985 D BtGatt.GattService: registerClient() - UUID=66b292c5-4a99-44a9-be6f-210e20c24c01,
,09-02 19:08:21.253  7077  7077 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-02 19:08:21.263  6977  6995 D BtGatt.GattService: onClientRegistered() - UUID=66b292c5-4a99-44a9-be6f-210e20c24c01, clientIf=6
,09-02 19:08:21.263  6369  6377 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:08:21.263  6977  7039 D BtGatt.GattService: start scan with filters
,09-02 19:08:21.263  6977  7001 D BtGatt.ScanManager: handling starting scan
,09-02 19:08:21.263  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 19:08:21.263  6977  6995 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 19:08:21.263  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.263  6977  7001 D BtGatt.ScanManager: allow scan with filters
09-02 19:08:21.263  6977  7001 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 19:08:21.263  6977  7001 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 19:08:21.263  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 19:08:21.273  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:08:21.273  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:08:21.273  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:08:21.273  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.273  6977  7001 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:08:21.273  6977  7001 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:08:21.273  6977  6995 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:21.273  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-02 19:08:21.273  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-02 19:08:21.273  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:08:21.273  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:08:21.273  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 19:08:21.273  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.273  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:08:21.293  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:08:21.293  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:21.293  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.293  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.293  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38058bcf removed from the list
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.293  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0fc95c removed from the list
09-02 19:08:21.293  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:21.293  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 19:08:21.293  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.293  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0fc95c not in the list
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:08:21.293  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:08:21.293  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:08:21.293  6977  6986 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:08:21.293  6977  6996 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:08:21.293  6977  7001 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,09-02 19:08:21.293  6977  7001 D BtGatt.ScanManager: filter size is 1
09-02 19:08:21.293  6977  7001 D BtGatt.ScanManager: delete FilterIndex - 5
09-02 19:08:21.303  6977  6995 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:08:21.303  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:21.303  6977  7001 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:08:21.303  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:08:21.303  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:08:21.303  6369  6423 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:08:21.303  6977  6995 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:08:21.313  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.313  6977  7001 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:08:21.313  6977  6995 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.313  6977  6995 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f915eb removed from the list
09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.313  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19af053a removed from the list
,09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5125c7 added. We now have 2 listener(s)
09-02 19:08:21.313  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:08:21.313  6369  6369 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:21.313  6369  6369 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:21.313  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9e7f4 added. We now have 9 listener(s)
09-02 19:08:21.313  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:21.313  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:21.323  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:21.323  6369  6423 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:21.323  6369  6423 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:21.323  6369  6423 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b4d0192 added. We now have 3 listener(s)
,09-02 19:08:21.333  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.333  6369  6369 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f305763 added. We now have 10 listener(s)
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:21.333  6369  6423 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:21.333  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:21.333  6369  6423 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:21.333  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5125c7 removed from the list
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9e7f4 removed from the list
09-02 19:08:21.333  6369  6423 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:21.333  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:21.333  6369  6423 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9e7f4 not in the list
09-02 19:08:21.333  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f305763 removed from the list
09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:08:21.333  6369  6423 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:21.333  6369  6423 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:21.333  6369  6423 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:21.333  6369  6423 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b4d0192 removed from the list
,09-02 19:08:21.333  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-02 19:08:21.333  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-02 19:08:21.333  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-02 19:08:21.343  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:08:21.343  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-02 19:08:21.343  6369  6423 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:21.343  6369  7086 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1196, name: My test thread name)
,09-02 19:08:21.343  6369  7086 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1196, thread name: My test thread name)
,09-02 19:08:21.343  6369  7086 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:08:21.353  7077  7077 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-02 19:08:21.353  6369  7087 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1198, name: My test thread name)
09-02 19:08:21.353  6369  7087 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1198, thread name: My test thread name)
09-02 19:08:21.353  6369  7087 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1198, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:08:21.353  6369  6423 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-02 19:08:21.353  6369  6423 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-02 19:08:21.353  6369  6423 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 19:08:21.353  6369  6423 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-02 19:08:21.353  6369  6423 D com.test.thalitest.ThaliTestRunner: Total duration: 24217 ms
09-02 19:08:21.353  6369  6423 I jxcore-log: *Native tests were executed*
09-02 19:08:21.353  6369  6423 I jxcore-log: ,
09-02 19:08:21.353  6369  6423 I jxcore-log: Total number of executed tests:  80
09-02 19:08:21.353  6369  6423 I jxcore-log: ,
09-02 19:08:21.353  6369  6423 I jxcore-log: Number of passed tests:  80
09-02 19:08:21.353  6369  6423 I jxcore-log: 
,09-02 19:08:21.353  6369  6423 I jxcore-log: Number of failed tests:  0
09-02 19:08:21.353  6369  6423 I jxcore-log: 
09-02 19:08:21.353  6369  6423 I jxcore-log: Number of ignored tests:  0,
09-02 19:08:21.353  6369  6423 I jxcore-log: 
09-02 19:08:21.353  6369  6423 I jxcore-log: Total duration:  24217
09-02 19:08:21.353  6369  6423 I jxcore-log: 
,09-02 19:08:21.353  6369  6423 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 19:08:21.353  6369  6423 I jxcore-log: 
,09-02 19:08:21.363  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.363  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
,09-02 19:08:21.373  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:21.373  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6369 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
,09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.383  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.383  6369  6423 I jxcore-log: 
09-02 19:08:21.393  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.393  6369  6423 I jxcore-log: 
,09-02 19:08:21.393  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-02 19:08:21.393  6369  6423 I jxcore-log: 
09-02 19:08:21.393  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.393  6369  6423 I jxcore-log: 
09-02 19:08:21.393  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:21.393  6369  6423 I jxcore-log: 
,09-02 19:08:21.553  6369  6369 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-02 19:08:21.553  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:21.553  6369  6423 I jxcore-log: 
,09-02 19:08:21.623  7096  7096 D AndroidRuntime: ,
09-02 19:08:21.623  7096  7096 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 19:08:21.623  7096  7096 D AndroidRuntime: CheckJNI is OFF,
09-02 19:08:21.623  7096  7096 D AndroidRuntime: readGMSProperty: start
09-02 19:08:21.623  7096  7096 D AndroidRuntime: readGMSProperty: already setted!!,
09-02 19:08:21.623  7096  7096 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 19:08:21.623  7096  7096 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 19:08:21.623  7096  7096 D AndroidRuntime: readGMSProperty: end
09-02 19:08:21.623  7096  7096 D AndroidRuntime: addProductProperty: start
,09-02 19:08:21.693  6369  6369 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-02 19:08:21.693  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:21.693  6369  6423 I jxcore-log: 
,09-02 19:08:21.703  1015  1129 E WifiNative-wlan0: do suspend true
,09-02 19:08:21.733  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-02 19:08:21.733  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:08:21.733  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:21.733  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:21.743  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:21.743  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.743  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.743  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.743  1015  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 19:08:21.743  1015  1129 E WifiStateMachine: VerifyingLinkState enter
,09-02 19:08:21.743  1015  1129 D WifiNative-wlan0: callSECApiInt - ID [210],
09-02 19:08:21.743  1015  1131 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:21.743  1015  1131 D ConnectivityService: Adding iface wlan0 to network 503
09-02 19:08:21.743  1015  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-02 19:08:21.753  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-02 19:08:21.753  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 19:08:21.753  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 19:08:21.753  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 19:08:21.753  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 19:08:21.763  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:21.763  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:21.763  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.763  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.763  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.763  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:21.763  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:21.773  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:21.773  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:21.773  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:21.773  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:21.773  1015  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-02 19:08:21.773  3635  3635 I Hs20UtilService: Starting #20
,09-02 19:08:21.773  3635  3663 I Hs20UtilService: Message received 5007
,09-02 19:08:21.773  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-02 19:08:21.773  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 19:08:21.793  1015  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-02 19:08:21.793  7096  7096 E AffinityControl: AffinityControl: registerfunction enter
09-02 19:08:21.793  1015  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-02 19:08:21.793  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:08:21.793  1015  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503,
,09-02 19:08:21.793  1015  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 19:08:21.793  1015  1131 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
09-02 19:08:21.793  1015  1131 D ConnectivityService: LTETest block dns file not exists
,09-02 19:08:21.793  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:21.793  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:21.793  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.793  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.793  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.793  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:21.803  1015  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
09-02 19:08:21.803  1015  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 19:08:21.803  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:08:21.803  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-02 19:08:21.803  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-02 19:08:21.803  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-02 19:08:21.813  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:08:21.813  1015  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.813  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:21.813  1015  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:08:21.813  1015  1131 E ConnectivityService: updateNetworkInfo()
09-02 19:08:21.813  1015  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.813  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:08:21.813  1015  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.813  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:21.813  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-02 19:08:21.813  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:21.813  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-02 19:08:21.813  1015  7072 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 19:08:21.813  1015  2960 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:21.813  1015  2960 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:21.813   278   968 D EnterpriseController: uids 1000
09-02 19:08:21.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.813   278   968 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-02 19:08:21.813   278   968 D Netd    : getNetworkForDns: using netid 503 for uid 1000
09-02 19:08:21.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.813  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.813  6369  6369 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:08:21.813  1015  2960 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:21.813  7096  7096 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 19:08:21.813  1015  2960 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:21.813  1015  2960 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:21.813  6369  6423 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:21.813  6369  6423 I jxcore-log: 
09-02 19:08:21.823  3635  3635 I Hs20UtilService: Starting #21
,09-02 19:08:21.823  3635  3663 I Hs20UtilService: Message received 5007
09-02 19:08:21.823  1015  1131 D ConnectivityService:    accepting network in place of null
09-02 19:08:21.823  1015  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 19:08:21.823  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:08:21.823  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 19:08:21.823  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:08:21.823  1015  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 19:08:21.823  1015  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-02 19:08:21.823  1015  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 19:08:21.833  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:08:21.833  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:21.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-02 19:08:21.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:21.833  1015  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-02 19:08:21.833  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,09-02 19:08:21.833  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 19:08:21.833  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
09-02 19:08:21.833  1015  1133 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:08:21.843  1015  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.843  1015  1122 V NetworkStats: updateIfacesLocked()
09-02 19:08:21.843  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.843  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:21.843  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-02 19:08:21.843  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:21.843  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:21.843  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-02 19:08:21.843  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
09-02 19:08:21.843  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 19:08:21.843  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-02 19:08:21.843  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 19:08:21.843  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-02 19:08:21.843  1174  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:08:21.843  3789  6260 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:08:21.843  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.843  1015  1122 V NetworkStats: performPollLocked() took 7ms
,09-02 19:08:21.843  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:21.853  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.853  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 19:08:21.853  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:21.853  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.853  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.853  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:21.853  1015  3169 D PackageManager: START PACKAGE DELETE: observer{993897679}
09-02 19:08:21.853  1015  3169 D PackageManager: pkg{<packageName>}
09-02 19:08:21.853  1015  3169 D PackageManager: user{0}
,09-02 19:08:21.853  1015  3169 D PackageManager: caller{2000}
09-02 19:08:21.853  1015  3169 D PackageManager: flags{2}
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:21.853  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.853  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:21.853  1015  3169 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-02 19:08:21.853  1015  3169 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-02 19:08:21.853  1015  3169 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-02 19:08:21.853  1015  3169 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-02 19:08:21.853  1015  3169 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-02 19:08:21.853  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-02 19:08:21.853  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-02 19:08:21.853  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-02 19:08:21.853  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-02 19:08:21.853  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-02 19:08:21.853  1015  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-02 19:08:21.853  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-02 19:08:21.853  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:21.853  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:21.853  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:21.853  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:21.863  3635  3635 I Hs20UtilService: Starting #22
,09-02 19:08:21.863  3635  3663 I Hs20UtilService: Message received 5007
,09-02 19:08:21.863  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:08:21.863  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 19:08:21.873  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-02 19:08:21.873  1015  1040 I ActivityManager: Killing 6369:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-02 19:08:21.913  1015  1096 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9,
09-02 19:08:21.913  1015  1096 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
09-02 19:08:21.913  1015  7072 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 19:08:21.913  1015  3213 W InputDispatcher: Attempted to unregister already unregistered input channel
09-02 19:08:21.913  1015  3213 I WindowState: WIN DEATH: Window{28bd18cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 19:08:21.913   257  1819 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
09-02 19:08:21.913   257   438 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,09-02 19:08:21.923  1015  3213 D InputDispatcher: Focus left window: 6369
,09-02 19:08:21.933  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-02 19:08:21.933  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 19:08:21.973  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:08:21 GMT], X-Android-Received-Millis=[1472836101983], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472836101955]}
09-02 19:08:21.973  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 19:08:21.973  1015  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-02 19:08:21.973  1015  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.973  1015  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-02 19:08:21.973  1015  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-02 19:08:21.973  1015  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-02 19:08:21.973  1174  1701 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:08:21.973  1015  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 19:08:21.973  3789  6260 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 19:08:21.993  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{2140c8eb u0 com.test.thalitest/.MainActivity t129}
,09-02 19:08:21.993  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,09-02 19:08:22.003  1015  3045 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-02 19:08:22.003  1015  3046 W ActivityManager: Spurious death for ProcessRecord{3b03d65c 6369:com.test.thalitest/u0a155}, curProc for 6369: null
,09-02 19:08:22.003  1015  1476 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-02 19:08:22.003  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-02 19:08:22.003  1015  1476 D SecContentProvider2: mCursor = null
09-02 19:08:22.003  1015  1054 I ActivityManager:   Force finishing activity ActivityRecord{2140c8eb u0 com.test.thalitest/.MainActivity t129 f}
09-02 19:08:22.003  1015  1054 W ActivityManager: Duplicate finish request for ActivityRecord{2140c8eb u0 com.test.thalitest/.MainActivity t129 f}
,09-02 19:08:22.013  1015  3213 D SecContentProvider2: uri = 15 selection = getToastGravity
09-02 19:08:22.013  1015  3213 D SecContentProvider2: mCursor = null
,09-02 19:08:22.033  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-02 19:08:22.033  1015  3169 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-02 19:08:22.033  1015  3169 D SecContentProvider2: mCursor = null
,09-02 19:08:22.033  1015  1493 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-02 19:08:22.033  1015  1493 D SecContentProvider2: mCursor = null
,09-02 19:08:22.033  1015  1028 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-02 19:08:22.033  1015  1028 D SecContentProvider2: mCursor = null
,09-02 19:08:22.043  1015  1138 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-02 19:08:22.043  1015  1138 D SecContentProvider2: mCursor = null
,09-02 19:08:22.063  5739  5739 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.749ms total 37.995ms
,09-02 19:08:22.063  3127  3127 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-02 19:08:22.063  1015  1040 D InputDispatcher: Focused application released
,09-02 19:08:22.073  4823  4823 I art     : Explicit concurrent mark sweep GC freed 98(15KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 681us total 32.907ms
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 19:08:22.083  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:22.083  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
09-02 19:08:22.083  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:22.083  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:22.093   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-02 19:08:22.093  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-02 19:08:22.103  1015  2960 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-02 19:08:22.103  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-02 19:08:22.103  3127  3127 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-02 19:08:22.113  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 19:08:22.113  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-02 19:08:22.113  3789  3789 I art     : Explicit concurrent mark sweep GC freed 24869(1489KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 15MB/26MB, paused 1.363ms total 100.440ms
,09-02 19:08:22.133  1802  1802 E SamsungIME: mOCRHelper is null
,09-02 19:08:22.133  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 19:08:22.153  3127  3127 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-02 19:08:22.163  3670  3670 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 19:08:22 GMT+02:00 2016
,09-02 19:08:22.163  1944  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 19:08:22.163  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-02 19:08:22.163  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-02 19:08:22.163  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-02 19:08:22.173  3127  3127 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-02 19:08:22.173  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-02 19:08:22.173  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:22.173  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-02 19:08:22.183  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.183  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:08:22.183  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:22.193  1015  1122 V NetworkStats: performPollLocked() took 22ms
,09-02 19:08:22.193  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:22.193  1015  1138 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 19:08:22.193  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:22.203  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:22.203  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:22.203  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 19:08:22.213  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.213  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-02 19:08:22.213  3670  3670 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-02 19:08:22.223  1015  3044 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44,
09-02 19:08:22.223  1015  3044 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-02 19:08:22.223  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:22.223  1015  3044 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-02 19:08:22.223  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.223  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.223  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.223  1015  3044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.233  1015  1015 I art     : Explicit concurrent mark sweep GC freed 74264(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 28MB/42MB, paused 5.971ms total 200.377ms
,09-02 19:08:22.233  1015  2933 I art     : WaitForGcToComplete blocked for 73.727ms for cause Explicit
,09-02 19:08:22.233  7127  7127 E Zygote  : MountEmulatedStorage()
09-02 19:08:22.233  7127  7127 E Zygote  : v2
09-02 19:08:22.233  7127  7127 I libpersona: KNOX_SDCARD checking this for 10094
,09-02 19:08:22.233  7127  7127 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.243  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-02 19:08:22.243  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:22.243  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.253  1015  3044 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7127 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-02 19:08:22.253  3670  3670 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-02 19:08:22.263  1440  1440 D RegisteredServicesCache: empty dynamic service,
,09-02 19:08:22.273  3670  3670 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 19:08:22.273  1015  1138 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-02 19:08:22.273  1015  1138 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-02 19:08:22.283  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-02 19:08:22.293  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0,
,09-02 19:08:22.293  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,09-02 19:08:22.293  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:22.293  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.293  7127  7127 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.293  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.293  3670  3670 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 19:08:22.303  3127  3127 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-02 19:08:22.303  3127  3127 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-02 19:08:22.303  3127  3127 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-02 19:08:22.303  3127  3127 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-02 19:08:22.313  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 19:08:22.313  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
09-02 19:08:22.313  1015  3045 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 19:08:22.323  1015  3045 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 19:08:22.323  1015  3045 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 19:08:22.323  3127  3127 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-02 19:08:22.323  1015  1493 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-02 19:08:22.323  1015  1493 D SecContentProvider2: mCursor = null
,09-02 19:08:22.323   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-02 19:08:22.333  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-02 19:08:22.333  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-02 19:08:22.333  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:22.333  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:22.333  1015  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:22.333  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-02 19:08:22.343  1015  3213 D InputDispatcher: Focus entered window: 3127
,09-02 19:08:22.343  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 19:08:22.343  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 19:08:22.343  3127  3127 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 19:08:22.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.343  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.353  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest,
,09-02 19:08:22.363  7143  7143 E Zygote  : MountEmulatedStorage(),
09-02 19:08:22.363  7143  7143 E Zygote  : v2
09-02 19:08:22.363  7143  7143 I libpersona: KNOX_SDCARD checking this for 10044,
09-02 19:08:22.363  7143  7143 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.363  7143  7143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-02 19:08:22.363  1015  1040 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7143 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-02 19:08:22.373  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 19:08:22.373  7143  7143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:22.373  7143  7143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.373  1015  1027 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6369 uid 10155
09-02 19:08:22.373  1015  7149 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-02 19:08:22.383  1802  1802 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-02 19:08:22.393  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast,
,09-02 19:08:22.393  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.393  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.393  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.393  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.433  3127  3127 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17396bdb time:216480,
,09-02 19:08:22.433  7161  7161 E Zygote  : MountEmulatedStorage()
09-02 19:08:22.433  7161  7161 E Zygote  : v2
09-02 19:08:22.433  7161  7161 I libpersona: KNOX_SDCARD checking this for 10149
09-02 19:08:22.433  7161  7161 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.433  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-02 19:08:22.433  1015  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7161 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:08:22.433  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:22.433  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.443  1015  2933 I art     : Explicit concurrent mark sweep GC freed 12098(1392KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 4.158ms total 212.838ms
,09-02 19:08:22.453  7143  7143 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.453  7143  7143 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.453  7127  7127 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-02 19:08:22.453  7127  7127 D elm:15183: ELMEngine.ELMEngine( context ).
09-02 19:08:22.453  7127  7127 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-02 19:08:22.453  1015  1054 I art     : WaitForGcToComplete blocked for 298.322ms for cause Explicit
,09-02 19:08:22.463  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:22.463  1015  1477 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-02 19:08:22.463  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-02 19:08:22.463  7161  7161 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.463  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:22.463  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:22.463  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-02 19:08:22.473  7127  7127 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-02 19:08:22.473  7127  7127 D elm:15183: ElmAgentService : onCreate()
,09-02 19:08:22.473  7127  7177 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-02 19:08:22.473  7127  7177 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-02 19:08:22.473  7127  7177 D elm:15183: MDMBridge.getInstance()
09-02 19:08:22.473  7127  7177 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 19:08:22.503  7127  7177 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 19:08:22.503  3127  3127 V ActivityThread: updateVisibility : ActivityRecord{297d574 token=android.os.BinderProxy@17396bdb {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-02 19:08:22.513  3127  3127 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-02 19:08:22.523  4823  4823 I art     : Explicit concurrent mark sweep GC freed 394(21KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 3.458ms total 47.262ms
,09-02 19:08:22.523  4823  7153 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-02 19:08:22.523  6621  6621 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-02 19:08:22.533  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 19:08:22.543  7143  7143 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:22.543  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-02 19:08:22.563  3670  7126 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-02 19:08:22.563  3670  7126 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-02 19:08:22.563  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-02 19:08:22.563  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.573  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29179886 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:216622
,09-02 19:08:22.603  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.603  3360  3360 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-02 19:08:22.613  7127  7127 D elm:15183: ElmAgentService : onDestroy().
,09-02 19:08:22.613  3360  3360 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-02 19:08:22.613  3360  3360 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-02 19:08:22.613  3360  3360 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:22.613  3360  3360 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:22.613  3360  3360 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:22.613  3360  3360 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:22.613  3360  3360 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:22.613  3360  3360 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 19:08:22.623  3670  3670 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-02 19:08:22.643  6002  6016 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-02 19:08:22.643  6002  6016 D BadgeProvider: sendNotify, [notify] : null
09-02 19:08:22.643  6002  6016 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-02 19:08:22.643  6002  6016 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 19:08:22.643  6002  6016 D BadgeProvider: update, [UpdateCount] : 1
,09-02 19:08:22.643  1015  3045 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:08:22.643  1015  3045 D BatteryService: level:95, scale:100, status:2, health:2, present:true, voltage: 4185, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-02 19:08:22.643  1015  3045 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-02 19:08:22.643  1015  3045 D BatteryService: stay LED for charging
,09-02 19:08:22.653  1015  3046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-02 19:08:22.653  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.653  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.653  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.653  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.653  7161  7161 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-02 19:08:22.653  7161  7161 D ThemeInfoUtil: isCurrentFestival = false
,09-02 19:08:22.663  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.663  7180  7180 E Zygote  : MountEmulatedStorage()
,09-02 19:08:22.663  7180  7180 E Zygote  : v2
09-02 19:08:22.663  7180  7180 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:08:22.663  7180  7180 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.663  7180  7180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:22.673  7180  7180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:22.673  7180  7180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:08:22.673  1015  3046 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 19:08:22.673  1015  3046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-02 19:08:22.683  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.683  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.683  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.683  1015  3046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.693  7191  7191 E Zygote  : MountEmulatedStorage(),
09-02 19:08:22.693  7191  7191 E Zygote  : v2
09-02 19:08:22.693  7191  7191 I libpersona: KNOX_SDCARD checking this for 10152,
09-02 19:08:22.693  7191  7191 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:22.693  1015  3046 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7191 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
09-02 19:08:22.693  1015  3046 I ActivityManager: Killing 6204:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-02 19:08:22.693  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:22.703  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:22.703  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.713  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-02 19:08:22.713  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:22.713  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:22.723  7180  7180 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.723  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:22.723  7180  7180 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.723  7191  7191 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.723  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.723  1015  1015 D RCPManagerService: PackageReceiver onReceive()
09-02 19:08:22.723  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-02 19:08:22.723  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-02 19:08:22.723  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-02 19:08:22.733  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-02 19:08:22.733  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-02 19:08:22.753  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-02 19:08:22.753  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-02 19:08:22.753  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-02 19:08:22.753  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-02 19:08:22.753  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-02 19:08:22.753  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 19:08:22.763  1015  1054 I art     : Explicit concurrent mark sweep GC freed 8178(459KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 9.889ms total 301.508ms
,09-02 19:08:22.763  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 19:08:22.763  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 19:08:22.763  1015  2736 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-02 19:08:22.773  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
,09-02 19:08:22.773  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-02 19:08:22.773  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 19:08:22.783  7143  7143 D NearbySource: Nearby Source Create!
,09-02 19:08:22.783  7143  7143 D NearbyContext: Nearby Context Create!
,09-02 19:08:22.793  1015  1493 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:22.803  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-02 19:08:22.803  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 19:08:22.803  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-02 19:08:22.803  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-02 19:08:22.803  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:08:22.803  1174  1174 D PanelView: There is/are notification(s) 
,09-02 19:08:22.813  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 19:08:22.813  1015  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:08:22.813  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 19:08:22.813  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 19:08:22.813  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 95
,09-02 19:08:22.813  7191  7191 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-02 19:08:22.813  7180  7180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-02 19:08:22.833  6977  6977 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 19:08:22.833  6977  7002 D HeadsetStateMachine: Disconnected process message: 10
,09-02 19:08:22.833   256   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-02 19:08:22.833   256   521 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:22.833  7143  7143 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-02 19:08:22.833  7143  7143 D SLinkSource: Samsung link source created
09-02 19:08:22.833  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-02 19:08:22.833  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-02 19:08:22.833  1015  1054 D PackageManager: delete codoeFile: 
,09-02 19:08:22.843  1015  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-02 19:08:22.843  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:22.843  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:22.843  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-02 19:08:22.843  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:08:22.843  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
09-02 19:08:22.843  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:95 status:2 health:2
,09-02 19:08:22.843  6604  6604 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-02 19:08:22.843  6604  6604 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 19:08:22.843  6604  6604 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 19:08:22.843  6604  6604 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-02 19:08:22.853  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-02 19:08:22.853  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.853  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.853  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.853  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.853  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-02 19:08:22.853  1015  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-02 19:08:22.863  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.863  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.863  1015  1054 D PackageManager: result of delete: 1{993897679}
,09-02 19:08:22.863  6977  6993 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 19:08:22.873  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-02 19:08:22.873  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-02 19:08:22.873  7212  7212 E Zygote  : MountEmulatedStorage(),
09-02 19:08:22.873  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:22.873  1015  2933 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7212 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-02 19:08:22.883  7096  7096 D AndroidRuntime: Shutting down VM
09-02 19:08:22.883  7212  7212 E Zygote  : v2
09-02 19:08:22.883  7212  7212 I libpersona: KNOX_SDCARD checking this for 10032
09-02 19:08:22.883  7212  7212 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.883  7212  7212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:22.883  7212  7212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:22.883  7212  7212 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.883  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-02 19:08:22.893  1015  3045 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 19:08:22.893  1015  3045 D SecContentProvider2: mCursor = null
09-02 19:08:22.893  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:22.893  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 19:08:22.893  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.893  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.893  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.893  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:22.893  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-02 19:08:22.893  1015  1054 D PackageManager: userId{-1}
09-02 19:08:22.893  1015  1054 D PackageManager: andCode{true}
,09-02 19:08:22.893  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:22.893  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 19:08:22.903  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:22.903  7222  7222 E Zygote  : MountEmulatedStorage()
09-02 19:08:22.903  7222  7222 E Zygote  : v2
09-02 19:08:22.903  7222  7222 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:08:22.903  7222  7222 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:22.903  7222  7222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:22.913  1015  2933 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-02 19:08:22.913  7222  7222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:22.913  1015  3044 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-02 19:08:22.913  1015  3044 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
09-02 19:08:22.913  7212  7212 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.913  1015  3044 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:22.913  1015  3044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:22.913  1015  3044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-02 19:08:22.913  7222  7222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.913  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-02 19:08:22.923  1015  1015 I MotionRecognitionService: Plugged
09-02 19:08:22.923  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 19:08:22.923  7212  7212 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.923  1174  1174 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
09-02 19:08:22.923  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
09-02 19:08:22.923  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
09-02 19:08:22.923  1174  1174 D PanelView: There is/are notification(s) 
09-02 19:08:22.923  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-02 19:08:22.923  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:22.923  1174  1174 D PanelView: There is/are notification(s) 
09-02 19:08:22.923  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
09-02 19:08:22.933  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-02 19:08:22.933  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-02 19:08:22.933  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.933  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.933  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.933  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-02 19:08:22.933  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:22.933  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:22.953  7222  7222 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.953  7245  7245 E Zygote  : MountEmulatedStorage()
09-02 19:08:22.953  7245  7245 E Zygote  : v2
09-02 19:08:22.953  7245  7245 I libpersona: KNOX_SDCARD checking this for 10156
09-02 19:08:22.953  7245  7245 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:22.953  7222  7222 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.953  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:22.953  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:22.953  1015  2933 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7245 uid=10156 gids={50156, 9997} abi=armeabi-v7a
09-02 19:08:22.953  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:22.973  7222  7222 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:22.983  1015  3169 I ActivityManager: Killing 5658:com.android.vending/u0a28 (adj 15): empty #31
,09-02 19:08:22.983  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:22.983  1015  3213 I ActivityManager: Killing 6275:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,09-02 19:08:22.983  7245  7245 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:22.993  7143  7244 D ContactProvider: getAllContactInfoList Start
,09-02 19:08:22.993  1015  3046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:22.993  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-02 19:08:23.003  1015  3044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:23.003  7143  7143 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-02 19:08:23.013  7222  7222 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-02 19:08:23.013  1015  1138 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-02 19:08:23.013  1015  1138 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-02 19:08:23.013  7245  7245 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-02 19:08:23.013  7245  7245 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-02 19:08:23.023  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-02 19:08:23.023  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.023  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.023  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.023  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:23.033  7245  7245 I TapandpayWidget:Utils: Clear T&P info.,
,09-02 19:08:23.033  7262  7262 E Zygote  : MountEmulatedStorage(),
09-02 19:08:23.033  7262  7262 E Zygote  : v2
09-02 19:08:23.033  7262  7262 I libpersona: KNOX_SDCARD checking this for 10091
09-02 19:08:23.033  7262  7262 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:23.043  7262  7262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:23.043  7245  7245 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-02 19:08:23.043  1015  2933 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7262 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:23.043  1015  2933 I ActivityManager: Killing 6667:com.android.chrome/u0a81 (adj 15): empty #31
,09-02 19:08:23.043  7262  7262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:23.043  7262  7262 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:08:23.043  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-02 19:08:23.043  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.043  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.043  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.043  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:23.063  7275  7275 E Zygote  : MountEmulatedStorage()
09-02 19:08:23.063  7275  7275 E Zygote  : v2
09-02 19:08:23.063  7275  7275 I libpersona: KNOX_SDCARD checking this for 10046
09-02 19:08:23.063  7275  7275 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:23.063  7275  7275 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:23.063  7275  7275 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:23.063  7275  7275 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-02 19:08:23.073  1015  2933 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7275 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-02 19:08:23.073  1015  2933 I ActivityManager: Killing 6630:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,09-02 19:08:23.073  1015  2933 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,09-02 19:08:23.083  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 19:08:23.083  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.083  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.083  1015  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:23.093  7262  7262 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:23.093  4823  4823 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
09-02 19:08:23.093  7262  7262 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:23.093  7275  7275 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:23.093  7275  7275 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:23.093  7212  7284 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-02 19:08:23.093   310   310 I art     : Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 27.740ms
,09-02 19:08:23.093  7096  7096 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 19:08:23.113  7212  7284 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-02 19:08:23.113   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 19.033ms
,09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:23.123  7212  7284 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:08:23.133   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 815us total 17.274ms
,09-02 19:08:23.133  7212  7284 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:23.133  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.133  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:23.143  7212  7284 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 19:08:23.143  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.143  7212  7284 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-02 19:08:23.143  7294  7294 E Zygote  : MountEmulatedStorage()
09-02 19:08:23.143  7294  7294 I libpersona: KNOX_SDCARD checking this for 10160
09-02 19:08:23.143  7294  7294 E Zygote  : v2
09-02 19:08:23.143  7294  7294 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:23.143  7294  7294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:23.143  7294  7294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-02 19:08:23.153  7294  7294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:23.153  1015  2933 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7294 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 19:08:23.153  7212  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 19:08:23.153  1015  2933 I ActivityManager: Killing 6689:com.sec.android.soagent/u0a34 (adj 15): empty #31
,09-02 19:08:23.163  1015  1027 I ActivityManager: Killing 6544:com.google.android.talk/u0a104 (adj 15): empty #31
09-02 19:08:23.163  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:23.163  7212  7284 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 19:08:23.163  7212  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:23.163  7143  7244 D ContactProvider: getAllContactInfoList End
,09-02 19:08:23.173  7143  7244 I syncContacts: thread: 1178, sync time = 222
,09-02 19:08:23.183  7294  7294 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:23.193  7294  7294 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:23.193  6002  6016 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-02 19:08:23.193  6002  6016 D BadgeProvider: sendNotify, [notify] : null
,09-02 19:08:23.193  6002  6016 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-02 19:08:23.193  6002  6016 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 19:08:23.193  6002  6016 D BadgeProvider: update, [UpdateCount] : 1
,09-02 19:08:23.203  7212  7284 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-02 19:08:23.203  7212  7284 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:23.203  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.203  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.203  7212  7284 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:08:23.203  7275  7275 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-02 19:08:23.213  7275  7275 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.213  7275  7275 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.213  7275  7275 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.213  7275  7275 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 19:08:23.213  7275  7275 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-02 19:08:23.213  1478  1478 D Launcher.Model: reloadBadges entered.
09-02 19:08:23.213  1478  1478 D Launcher.Model: reloadBadges entered.
,09-02 19:08:23.223  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-02 19:08:23.223  7212  7284 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-02 19:08:23.223  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.223  7212  7284 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 19:08:23.223  7212  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:23.223  7294  7294 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-02 19:08:23.223  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.223  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.223  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:23.223  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:23.233  7212  7284 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-02 19:08:23.233  7212  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:23.233  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.233  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.233  7212  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:23.243  7212  7284 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-02 19:08:23.243  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-02 19:08:23.253  1015  1028 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7310 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:23.253  7310  7310 E Zygote  : MountEmulatedStorage()
09-02 19:08:23.253  7310  7310 I libpersona: KNOX_SDCARD checking this for 10035
09-02 19:08:23.253  7310  7310 E Zygote  : v2
09-02 19:08:23.253  7310  7310 I libpersona: KNOX_SDCARD not a persona,
,09-02 19:08:23.253  7294  7294 D [0]UMC:UMCContentProvider: @onCreate
,09-02 19:08:23.253  7310  7310 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-02 19:08:23.263  7310  7310 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-02 19:08:23.263  7310  7310 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 19:08:23.263  7275  7275 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-02 19:08:23.263  7294  7294 D [0]UMC:Core: onCreate(): 
,09-02 19:08:23.273  7294  7294 D [0]UMC:Core: @isManagedProfileUser
09-02 19:08:23.273  7294  7294 D [0]UMC:Core: userId: 0
,09-02 19:08:23.273  7294  7294 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
09-02 19:08:23.273  7294  7294 D [0]UMC:Core: userInfo.isManagedProfile() : false
,09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:23.283  7212  7284 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:08:23.293  7310  7310 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:23.293  7310  7310 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:23.303  7294  7294 D [0]UMC:DeviceInfo: USA==US==
,09-02 19:08:23.303  7212  7284 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-02 19:08:23.303  7212  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:23.313  7262  7262 E PhotosPlugin: Loading PhotosPlugin
,09-02 19:08:23.313  7212  7284 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found

```
