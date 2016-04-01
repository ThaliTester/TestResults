#### Test 648991491c812df_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
04-01 09:12:55.238  3363  3829 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 09:12:55.238  3363  3829 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 09:12:55.238  3363  3829 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,04-01 09:12:55.238  3363  3363 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 09:12:55.248  3363  3829 D BatteryService: stay LED for fully charged
04-01 09:12:55.248  3363  3363 I MotionRecognitionService: Plugged
04-01 09:12:55.248  3363  3363 D MotionRecognitionService:   cableConnection= 1
04-01 09:12:55.248  3363  3363 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
--------- beginning of main
04-01 09:12:55.263  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:12:55.248  3363  3363 D MotionRecognitionService: skip setTransmitPower. 
04-01 09:12:55.263  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:12:55.263  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
04-01 09:12:55.283  5932  5932 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 09:12:55.283  5932  6061 D HeadsetStateMachine: Disconnected process message: 10
04-01 09:12:55.293  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:12:55.293  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 09:12:55.293  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 09:12:55.293  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 09:12:55.683 11653 11653 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 09:12:55.688 11653 11653 D AndroidRuntime: CheckJNI is OFF
04-01 09:12:55.688 11653 11653 D AndroidRuntime: readGMSProperty: start
04-01 09:12:55.688 11653 11653 D AndroidRuntime: readGMSProperty: already setted!!
04-01 09:12:55.688 11653 11653 D AndroidRuntime: propertySet: couldn't set property (it is from app)
04-01 09:12:55.688 11653 11653 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
04-01 09:12:55.688 11653 11653 D AndroidRuntime: readGMSProperty: end
04-01 09:12:55.688 11653 11653 D AndroidRuntime: addProductProperty: start
04-01 09:12:55.908 11653 11653 E AffinityControl: AffinityControl: registerfunction enter
04-01 09:12:55.928 11653 11653 D AndroidRuntime: Calling main entry com.android.commands.am.Am
04-01 09:12:55.943  3363  6568 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
04-01 09:12:55.953  3363  6568 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
04-01 09:12:55.988  3363  6568 W ActivityManager: mDVFSHelper.acquire()
04-01 09:12:55.993  3363  6568 V WindowManager: addAppToken: AppWindowToken{632aa01 token=Token{393ca3e8 ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
04-01 09:12:55.998  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:55.998  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:55.998  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:55.998  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:56.003  3363  3578 D PhoneWindow: *FMB* installDecor mIsFloating : false
04-01 09:12:56.003  3363  3578 D PhoneWindow: *FMB* installDecor flags : -2122120936
04-01 09:12:56.003  3363  3578 D SecWifiDisplayUtil: Metadata value : none
04-01 09:12:56.008  3363  3578 V WindowManager: Adding window Window{17fe0800 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{31f7a058 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
04-01 09:12:56.013 11674 11674 E Zygote  : MountEmulatedStorage()
04-01 09:12:56.013 11674 11674 E Zygote  : v2
04-01 09:12:56.013 11674 11674 I libpersona: KNOX_SDCARD checking this for 10011
04-01 09:12:56.013 11674 11674 I libpersona: KNOX_SDCARD not a persona
04-01 09:12:56.018 11674 11674 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 09:12:56.018  3363  6568 I ActivityManager: Start proc 11674:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
04-01 09:12:56.018  3363  6568 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
04-01 09:12:56.018  3363  6568 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
04-01 09:12:56.018  3363  6568 D InputDispatcher: Focused application set to: xxxx
04-01 09:12:56.023  3363  6568 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
04-01 09:12:56.023  3363  6568 D InputDispatcher: Focus left window: 6717
04-01 09:12:56.023 11653 11653 D AndroidRuntime: Shutting down VM
04-01 09:12:56.023 11674 11674 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:12:56.023  3363  3578 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
04-01 09:12:56.023  3363  3578 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
04-01 09:12:56.023 11674 11674 E Zygote  : accessInfo : 0
04-01 09:12:56.028  2862  2862 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
04-01 09:12:56.028 11674 11674 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
04-01 09:12:56.043 11674 11674 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 09:12:56.048 11674 11674 D ActivityThread: Added TimaKeyStore provider
04-01 09:12:56.048  3363  3578 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3363 uid:1000
04-01 09:12:56.048  3363  3578 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 09:12:56.048  3363  3578 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3363 uid:1000
04-01 09:12:56.048  3363  3578 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 09:12:56.048  3363  3597 D PowerManagerService: setKeyboardVisibility: false
04-01 09:12:56.053  3363  3576 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{17fe0800 u0 d0 Starting com.test.thalitest}
04-01 09:12:56.053  3363  3597 D ActivityManager:  Launching com.test.thalitest, updated priority
04-01 09:12:56.063  3363  3597 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42}
04-01 09:12:56.083  2862  3001 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
04-01 09:12:56.083  2862  3003 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
04-01 09:12:56.088  6717  6717 V ActivityThread: updateVisibility : ActivityRecord{11a253c token=android.os.BinderProxy@e88b8d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
04-01 09:12:56.223  3363  6155 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,04-01 09:12:56.263 11674 11674 D SecWifiDisplayUtil: Metadata value : none
,04-01 09:12:56.308 11674 11674 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,04-01 09:12:56.318 11674 11674 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6176-6177)
04-01 09:12:56.318 11674 11674 I LibraryLoader: Expected native library version number "",actual native library version number ""
,04-01 09:12:56.333 11674 11674 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11f1ce9c}
,04-01 09:12:56.333 11674 11674 I LibraryLoader: Expected native library version number "",actual native library version number ""
04-01 09:12:56.333 11674 11674 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,04-01 09:12:56.338 11674 11690 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,04-01 09:12:56.358 11674 11674 I BrowserStartupController: Initializing chromium process, singleProcess=true
,04-01 09:12:56.358 11674 11674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:12:56.358 11674 11674 E SysUtils: ApplicationContext is null in ApplicationStatus
,04-01 09:12:56.373 11674 11674 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,04-01 09:12:56.373 11674 11674 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
04-01 09:12:56.373 11674 11674 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,04-01 09:12:56.433 11674 11713 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,04-01 09:12:56.458 11674 11674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:12:56.473 11674 11674 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 09:12:56.478 11674 11674 D PhoneWindow: *FMB* installDecor mIsFloating : false
04-01 09:12:56.478 11674 11674 D PhoneWindow: *FMB* installDecor flags : -2139027200
,04-01 09:12:56.483 11674 11674 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,04-01 09:12:56.488 11674 11674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
04-01 09:12:56.488 11674 11674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,04-01 09:12:56.513  3363  6155 D SSRM:n  : SIOP:: AP = 260, PST = 270 (W:14), CUR = 41, LCD = 0
,04-01 09:12:56.528 11674 11726 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 09:12:56.533  3363  4011 V WindowManager: Adding window Window{10293ce1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{17fe0800 u0 d0 Starting com.test.thalitest})
,04-01 09:12:56.538  3363  3391 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
04-01 09:12:56.538  3363  3391 D KnoxTimeoutHandler: postActiveUserChange for user 0
04-01 09:12:56.538  3363  3391 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
04-01 09:12:56.538  3363  3363 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,04-01 09:12:56.538  3363  3363 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,04-01 09:12:56.538  3363  3363 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
04-01 09:12:56.538  3363  3363 I EnterpriseSharedDevicePolicy: Get Result: -1
04-01 09:12:56.538  3363  3363 I EnterpriseSharedDevicePolicy: status: false
04-01 09:12:56.538  3363  3363 D PersonaManagerService: getPersonasForUser(): returning null!
04-01 09:12:56.538  3363  3363 I KnoxTimeoutHandler: Shared devices show user statefalse
,04-01 09:12:56.548 11674 11674 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
04-01 09:12:56.548 11674 11674 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,04-01 09:12:56.553 11674 11674 D SecWifiDisplayUtil: Metadata value : none
,04-01 09:12:56.558  2862  2862 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,04-01 09:12:56.558  3363  3389 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,04-01 09:12:56.578  3363  3389 D InputDispatcher: Focus entered window: 11674
,04-01 09:12:56.583  3363  3578 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3363 uid:1000
04-01 09:12:56.583  3363  3578 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 09:12:56.583  3363  3578 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3363 uid:1000
04-01 09:12:56.583  3363  3578 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
04-01 09:12:56.588 11674 11674 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
04-01 09:12:56.588 11674 11726 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 09:12:56.588 11674 11726 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae830c10 ,&mEglDisplay = 1 , &mEglConfig = -1266835184 
,04-01 09:12:56.588 11674 11726 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
04-01 09:12:56.588 11674 11726 D OpenGLRenderer: Enabling debug mode 0
,04-01 09:12:56.593 11674 11726 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,04-01 09:12:56.593 11674 11674 V ActivityThread: updateVisibility : ActivityRecord{12ac7364 token=android.os.BinderProxy@1db89cf6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,04-01 09:12:56.668  3363  4013 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,04-01 09:12:56.668  3363  3578 I ActivityManager: Displayed Component not be shown by security: +476ms (total +1m17s16ms)
,04-01 09:12:56.673  3724  3724 D PanelView: There is/are notification(s) 
,04-01 09:12:56.673  3363  3578 W ActivityManager: mDVFSHelper.release()
04-01 09:12:56.673  3363  3578 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42} time:176531
,04-01 09:12:56.678  2862  9474 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,04-01 09:12:56.678  2862  3003 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,04-01 09:12:56.703 11674 11674 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-01 09:12:56.703 11674 11674 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1db89cf6 time:176564
,04-01 09:12:56.733 11674 11674 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11674
,04-01 09:12:56.873 11674 11674 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 09:12:56.953 11674 11730 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626345856
,04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 09:12:56.958 11674 11730 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d1c03d added. We now have 1 listener(s)
,04-01 09:12:56.963 11674 11730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,04-01 09:12:56.963 11674 11730 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,04-01 09:12:56.968 11674 11730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-01 09:12:56.968 11674 11730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-01 09:12:56.968 11674 11690 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 09:12:56.968 11674 11730 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2046df00 added. We now have 1 listener(s)
04-01 09:12:56.973 11674 11730 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 09:12:56.973 11674 11730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,04-01 09:12:56.978 11674 11730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
04-01 09:12:56.978 11674 11730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
04-01 09:12:56.978 11674 11730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
04-01 09:12:56.978 11674 11730 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,04-01 09:12:56.978 11674 11730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-01 09:12:56.983 11674 11730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:12:56.988 11674 11730 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 09:12:56.988 11674 11730 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 09:12:56.988 11674 11730 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-01 09:12:56.988 11674 11730 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 09:12:56.988 11674 11674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 09:12:56.993 11674 11674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 09:12:57.018 11674 11674 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 09:12:57.393 11674 11736 W jxcore-log: Initializing JXcore engine
04-01 09:12:57.393 11674 11736 W jxcore-log: JXcore engine is ready
,04-01 09:12:57.418  4822  4822 E auditd  : In denial and Property audit_ondenial is set to 1 
,04-01 09:12:57.423  4822  4822 E audit   : type=1400 msg=audit(1459494777.418:196): avc:  denied  { ioctl } for  pid=11736 comm="Thread-1583" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5138 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-01 09:12:57.423  3363  3574 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
04-01 09:12:57.423  4822  4822 E audit   :  SEPF_SM-N910C_5.1.1_0038
04-01 09:12:57.423  4822  4822 E audit   : type=1300 msg=audit(1459494777.418:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=961008d8 items=0 ppid=2903 ppcomm=main pid=11736 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1583" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
04-01 09:12:57.423  4822  4822 E audit   : type=1320 msg=audit(1459494777.418:196): 
,04-01 09:12:57.423  3363  3574 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,04-01 09:12:57.423  3363  3574 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,04-01 09:12:57.423  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:57.423  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:57.428 11674 11736 W jxcore-log: Starting JXcore engine
04-01 09:12:57.423  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:12:57.423  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:12:57.438 11737 11737 E Zygote  : MountEmulatedStorage()
04-01 09:12:57.438 11737 11737 E Zygote  : v2
04-01 09:12:57.438 11737 11737 I libpersona: KNOX_SDCARD checking this for 1000
04-01 09:12:57.438 11737 11737 I libpersona: KNOX_SDCARD not a persona
,04-01 09:12:57.438 11737 11737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:12:57.443  3363  3571 I ActivityManager: Start proc 11737:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,04-01 09:12:57.443 11737 11737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,04-01 09:12:57.443 11737 11737 E Zygote  : accessInfo : 0
,04-01 09:12:57.443 11737 11737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:12:57.463 11737 11737 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 09:12:57.463 11737 11737 D ActivityThread: Added TimaKeyStore provider
,04-01 09:12:57.468  3363  4451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25ce9bd5 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{28316fea 11737:com.samsung.android.securitylogagent/1000}
,04-01 09:12:57.478 11674 11736 W jxcore-log: Platform android
04-01 09:12:57.478 11674 11736 W jxcore-log: 
04-01 09:12:57.478 11674 11736 W jxcore-log: Process ARCH arm
04-01 09:12:57.478 11674 11736 W jxcore-log: 
,04-01 09:12:57.488 11737 11737 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,04-01 09:12:57.488 11737 11737 D SecurityLogAgent:  SeDenialReceiver : File path = null
,04-01 09:12:57.488  3363  3982 I ActivityManager: Killing 10500:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,04-01 09:12:57.573 11674 11736 I jxcore-log: JXcore Cordova bridge is ready!
04-01 09:12:57.573 11674 11736 I jxcore-log: 
04-01 09:12:57.573 11674 11736 W jxcore-log: JXcore engine is started
,04-01 09:12:57.578 11674 11730 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 09:12:57.583 11674 11674 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 09:12:59.003  3363  3689 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,04-01 09:12:59.293  3363  3617 V AlarmManager: waitForAlarm result :4
,04-01 09:12:59.293  3363  3363 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,04-01 09:12:59.298  3363  3363 V AlarmManagerEXT: <AppSync3 Whitelist>
04-01 09:12:59.298  3363  3363 V AlarmManagerEXT: (AppSync) ### 0 added ###
,04-01 09:12:59.298  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
04-01 09:12:59.298  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
04-01 09:12:59.298  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,04-01 09:12:59.298  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,04-01 09:12:59.303  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,04-01 09:12:59.303  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
04-01 09:12:59.303  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,04-01 09:12:59.308  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,04-01 09:12:59.333  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.333  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.333  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.333  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.338  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.338  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:12:59.343  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:13:00.293  3363  3617 V AlarmManager: waitForAlarm result :8
,04-01 09:13:03.328 11674 11736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 09:13:03.328 11674 11736 I jxcore-log: 
,04-01 09:13:03.328 11674 11736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 09:13:03.328 11674 11736 I jxcore-log: 
,04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 09:13:03.333 11674 11736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 09:13:03.333 11674 11736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-01 09:13:03.333 11674 11736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 09:13:03.333 11674 11736 I jxcore-log: 
,04-01 09:13:03.333 11674 11736 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 09:13:03.333 11674 11736 I jxcore-log: 
,04-01 09:13:03.658 11674 11736 I jxcore-log: Unit Test app is loaded
04-01 09:13:03.658 11674 11736 I jxcore-log: 
,04-01 09:13:03.663 11674 11736 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 09:13:03.663 11674 11736 I jxcore-log: 
,04-01 09:13:03.668 11674 11674 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 09:13:03.668 11674 11736 I jxcore-log: My device name is: samsung-SM-N910C
04-01 09:13:03.668 11674 11736 I jxcore-log: 
,04-01 09:13:05.343  3363  4227 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 09:13:05.343  3363  4227 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 09:13:05.343  3363  4227 D BatteryService: online:4, current avg:-79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-219
,04-01 09:13:05.343  3363  4227 D BatteryService: stay LED for fully charged
04-01 09:13:05.343  3363  3363 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 09:13:05.348  3363  3363 I MotionRecognitionService: Plugged
04-01 09:13:05.348  3363  3363 D MotionRecognitionService:   cableConnection= 1
04-01 09:13:05.348  3363  3363 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
04-01 09:13:05.348  3363  3363 D MotionRecognitionService: skip setTransmitPower. 
,04-01 09:13:05.348  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:13:05.348  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:13:05.348  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
04-01 09:13:05.353  5932  5932 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 09:13:05.353  5932  6061 D HeadsetStateMachine: Disconnected process message: 10
,04-01 09:13:05.368  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 09:13:05.368  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 09:13:05.368  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
04-01 09:13:05.368  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:06.033 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 09:13:06.033 11674 11736 I jxcore-log: 
,04-01 09:13:06.043  3363  3589 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,04-01 09:13:06.058  3363  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,04-01 09:13:06.243 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 09:13:06.243 11674 11736 I jxcore-log: 
,04-01 09:13:06.248 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 09:13:06.248 11674 11736 I jxcore-log: 
,04-01 09:13:06.253 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 09:13:06.253 11674 11736 I jxcore-log: 
,04-01 09:13:06.258 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 09:13:06.258 11674 11736 I jxcore-log: 
,04-01 09:13:06.263 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 09:13:06.263 11674 11736 I jxcore-log: 
,04-01 09:13:06.518  3363  6155 D SSRM:n  : SIOP:: AP = 290, PST = 267 (W:10), CUR = -79, LCD = 0
,04-01 09:13:07.473 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 09:13:07.473 11674 11736 I jxcore-log: 
,04-01 09:13:07.488 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 09:13:07.488 11674 11736 I jxcore-log: 
,04-01 09:13:07.493 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 09:13:07.493 11674 11736 I jxcore-log: 
,04-01 09:13:07.643 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 09:13:07.643 11674 11736 I jxcore-log: 
,04-01 09:13:07.683 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 09:13:07.683 11674 11736 I jxcore-log: 
,04-01 09:13:07.713 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 09:13:07.713 11674 11736 I jxcore-log: 
,04-01 09:13:07.718 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 09:13:07.718 11674 11736 I jxcore-log: 
,04-01 09:13:07.723 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 09:13:07.723 11674 11736 I jxcore-log: 
,04-01 09:13:07.723 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 09:13:07.723 11674 11736 I jxcore-log: 
,04-01 09:13:07.728 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 09:13:07.728 11674 11736 I jxcore-log: 
,04-01 09:13:07.738 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 09:13:07.738 11674 11736 I jxcore-log: 
,04-01 09:13:07.748 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 09:13:07.748 11674 11736 I jxcore-log: 
,04-01 09:13:07.798 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 09:13:07.798 11674 11736 I jxcore-log: 
,04-01 09:13:07.798 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 09:13:07.798 11674 11736 I jxcore-log: 
,04-01 09:13:07.813 11674 11736 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 09:13:07.813 11674 11736 I jxcore-log: 
,04-01 09:13:07.818 11674 11736 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,04-01 09:13:07.818 11674 11736 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
04-01 09:13:07.818 11674 11736 I jxcore-log: 
,04-01 09:13:10.283  3363  6196 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,04-01 09:13:12.933  3363  3860 E Watchdog: !@Sync 6 [04-01 09:13:12.932]
,04-01 09:13:15.488  3363  3597 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 09:13:15.488  3363  3597 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 09:13:15.488  3363  3597 D BatteryService: online:4, current avg:-30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,04-01 09:13:15.488  3363  3363 D BatteryService: Sending ACTION_BATTERY_CHANGED.
04-01 09:13:15.493  3363  3597 D BatteryService: stay LED for fully charged
,04-01 09:13:15.498  3363  3363 I MotionRecognitionService: Plugged
04-01 09:13:15.498  3363  3363 D MotionRecognitionService:   cableConnection= 1,
04-01 09:13:15.498  3363  3363 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 09:13:15.498  3363  3363 D MotionRecognitionService: skip setTransmitPower. 
04-01 09:13:15.508  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:13:15.508  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
04-01 09:13:15.508  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
04-01 09:13:15.533  5932  5932 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 09:13:15.533  5932  6061 D HeadsetStateMachine: Disconnected process message: 10
,04-01 09:13:15.543  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 09:13:15.543  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:15.543  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:15.543  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:16.153  2895  4805 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,04-01 09:13:16.423  3363  3580 I PowerManagerService: [PWL] Off : 140s ago
,04-01 09:13:16.543  3363  6155 D SSRM:n  : SIOP:: AP = 280, PST = 265 (W:10), CUR = -30, LCD = 0
,04-01 09:13:25.623  3363  3391 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
04-01 09:13:25.623  3363  3391 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
04-01 09:13:25.623  3363  3391 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,04-01 09:13:25.623  3363  3363 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,04-01 09:13:25.633  3363  3391 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
04-01 09:13:25.633  3363  3391 D BatteryService: stay LED for fully charged,
,04-01 09:13:25.638  3363  3363 I MotionRecognitionService: Plugged
,04-01 09:13:25.638  3363  3363 D MotionRecognitionService:   cableConnection= 1
,04-01 09:13:25.638  3363  3363 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,04-01 09:13:25.638  3363  3363 D MotionRecognitionService: skip setTransmitPower. 
,04-01 09:13:25.648  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 09:13:25.648  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,04-01 09:13:25.648  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate,
,04-01 09:13:25.668  5932  5932 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
04-01 09:13:25.668  5932  6061 D HeadsetStateMachine: Disconnected process message: 10
,04-01 09:13:25.678  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,04-01 09:13:25.683  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:25.683  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:25.683  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,04-01 09:13:26.568  3363  6155 D SSRM:n  : SIOP:: AP = 270, PST = 266 (W:10), CUR = 16, LCD = 0
,04-01 09:13:29.458 11674 11736 I jxcore-log: TAP version 13
04-01 09:13:29.458 11674 11736 I jxcore-log: 
,04-01 09:13:29.463 11674 11736 I jxcore-log: # setup
04-01 09:13:29.463 11674 11736 I jxcore-log: 
,04-01 09:13:29.583 11674 11736 I jxcore-log: # name
04-01 09:13:29.583 11674 11736 I jxcore-log: 
,04-01 09:13:30.163 11674 11736 I jxcore-log: ok 1 sane
04-01 09:13:30.163 11674 11736 I jxcore-log: 
,04-01 09:13:30.173 11674 11736 I jxcore-log: # teardown
04-01 09:13:30.173 11674 11736 I jxcore-log: 
,04-01 09:13:30.283  3363  6196 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,04-01 09:13:30.728 11674 11736 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 09:13:30.728 11674 11736 I jxcore-log: 
,04-01 09:13:31.183 11805 11805 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 09:13:31.188 11805 11805 D AndroidRuntime: CheckJNI is OFF
,04-01 09:13:31.188 11805 11805 D AndroidRuntime: readGMSProperty: start
04-01 09:13:31.188 11805 11805 D AndroidRuntime: readGMSProperty: already setted!!
04-01 09:13:31.188 11805 11805 D AndroidRuntime: propertySet: couldn't set property (it is from app)
04-01 09:13:31.188 11805 11805 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
04-01 09:13:31.188 11805 11805 D AndroidRuntime: readGMSProperty: end
04-01 09:13:31.188 11805 11805 D AndroidRuntime: addProductProperty: start
,04-01 09:13:31.283 11805 11805 E AffinityControl: AffinityControl: registerfunction enter
,04-01 09:13:31.298 11805 11805 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 09:13:31.308  3363  4227 D PackageManager: START PACKAGE DELETE: observer{90841169}
04-01 09:13:31.308  3363  4227 D PackageManager: pkg{<packageName>}
04-01 09:13:31.308  3363  4227 D PackageManager: user{0}
04-01 09:13:31.308  3363  4227 D PackageManager: caller{2000}
04-01 09:13:31.308  3363  4227 D PackageManager: flags{2}
,04-01 09:13:31.308  3363  4227 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
04-01 09:13:31.308  3363  4227 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
04-01 09:13:31.308  3363  3589 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,04-01 09:13:31.308  3363  4227 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
04-01 09:13:31.308  3363  4227 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
04-01 09:13:31.308  3363  4227 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
04-01 09:13:31.313  3363  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,04-01 09:13:31.313  3363  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
04-01 09:13:31.313  3363  3589 D ApplicationPolicy: getApplicationUninstallationEnabled
04-01 09:13:31.313  3363  3589 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
04-01 09:13:31.313  3363  3589 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,04-01 09:13:31.318  3363  3571 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,04-01 09:13:31.318  3363  3571 I ActivityManager: Killing 11674:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,04-01 09:13:31.328  3363  3571 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42}
,04-01 09:13:31.333  3363  3571 W ActivityManager: mDVFSHelper.acquire()
,04-01 09:13:31.448  3363  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,04-01 09:13:31.448  3363  3589 W PackageSettings: Skipping PackageSetting{a4772b com.example.hello/10691} due to missing metadata
,04-01 09:13:31.468  3363  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,04-01 09:13:31.473  3363  3571 D PowerManagerService: setKeyboardVisibility: false
04-01 09:13:31.473  3363  3571 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{19f98a9f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,04-01 09:13:31.478  3363  4011 I WindowState: WIN DEATH: Window{10293ce1 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
04-01 09:13:31.478  2862  3001 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,04-01 09:13:31.478  2862  3003 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,04-01 09:13:31.483  3363  4011 D InputDispatcher: Focus left window: 11674
,04-01 09:13:31.483  3363  4011 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,04-01 09:13:31.483  2862  3690 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,04-01 09:13:31.493  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
04-01 09:13:31.498  3363  3589 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
04-01 09:13:31.498  3363  3578 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3363 uid:1000
04-01 09:13:31.498  3363  3589 I ActivityManager:   Force finishing activity 3 ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42 f}
04-01 09:13:31.498  3363  3578 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 09:13:31.498  3363  3589 W ActivityManager: Duplicate finish request for ActivityRecord{1e82490b u0 com.test.thalitest/.MainActivity t42 f}
04-01 09:13:31.498  3363  3578 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3363 uid:1000
04-01 09:13:31.498  3363  3578 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,04-01 09:13:31.518  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,04-01 09:13:31.533  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,04-01 09:13:31.543  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,04-01 09:13:31.548  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,04-01 09:13:31.558  4113  4113 I art     : Explicit concurrent mark sweep GC freed 14136(919KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 1.554ms total 50.080ms
,04-01 09:13:31.558  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,04-01 09:13:31.568  3363  3589 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,04-01 09:13:31.573  3917  3917 I art     : Explicit concurrent mark sweep GC freed 1688(88KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 596us total 29.554ms
,04-01 09:13:31.583  4014  4014 I art     : Explicit concurrent mark sweep GC freed 16039(921KB) AllocSpace objects, 9(1362KB) LOS objects, 12% free, 56MB/64MB, paused 546us total 35.679ms
,04-01 09:13:31.583  9579  9579 I art     : Explicit concurrent mark sweep GC freed 21978(1222KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 801us total 47.198ms
,04-01 09:13:31.588  3363  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
,04-01 09:13:31.593  3363  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
,04-01 09:13:31.593  4667  4667 I art     : Explicit concurrent mark sweep GC freed 5544(319KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 535us total 80.410ms
,04-01 09:13:31.593  3363  3571 D InputDispatcher: Focused application released
04-01 09:13:31.598  6717  6717 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,04-01 09:13:31.603  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(648/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,04-01 09:13:31.603  6717  6717 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 android.content.ContextWrapper.sendBroadcast:392 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:651 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:171 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:451 
,04-01 09:13:31.623  3363  3630 I InputReader: Reconfiguring input devices.  changes=0x00000010
04-01 09:13:31.623  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,04-01 09:13:31.628  4493  4493 E SamsungIME: mOCRHelper is null
,04-01 09:13:31.628  4416  4820 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-01 09:13:31.638 10945 10945 D LWLocationManager: getDeviceLocationId :  id = -100
,04-01 09:13:31.638 10945 10945 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,04-01 09:13:31.648  3363  3650 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 09:13:31.648  3363  3650 V NetworkStats: removeUidsLocked() for UIDs [10011]
04-01 09:13:31.648  3363  3650 V NetworkStats: performPollLocked(flags=0x3)
,04-01 09:13:31.658  3363  3650 V NetworkStats: performPollLocked() took 9ms
04-01 09:13:31.658  3363  3650 D NtpTrustedTime: currentTimeMillis() cache hit
,04-01 09:13:31.658  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.658  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.658  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.658  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:31.663  5650  5673 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
04-01 09:13:31.663  5650  5673 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,04-01 09:13:31.673 11833 11833 E Zygote  : MountEmulatedStorage()
,04-01 09:13:31.678 11833 11833 E Zygote  : v2
04-01 09:13:31.678 11833 11833 I libpersona: KNOX_SDCARD checking this for 10063
04-01 09:13:31.678 11833 11833 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:31.678 11833 11833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:31.678  3363  3571 I ActivityManager: Start proc 11833:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,04-01 09:13:31.683 11833 11833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:31.683 11833 11833 E Zygote  : accessInfo : 0
04-01 09:13:31.683  3363  4012 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
04-01 09:13:31.683 11833 11833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:31.713  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,04-01 09:13:31.718  3979  3979 D RegisteredServicesCache: empty dynamic service
,04-01 09:13:31.728 11833 11833 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 09:13:31.728 11833 11833 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:31.738  3363  3363 I art     : Explicit concurrent mark sweep GC freed 57063(4MB) AllocSpace objects, 64(1024KB) LOS objects, 33% free, 32MB/48MB, paused 13.520ms total 173.576ms
,04-01 09:13:31.743  3363  3589 I art     : WaitForGcToComplete blocked for 150.275ms for cause Explicit
,04-01 09:13:31.743  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,04-01 09:13:31.748  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,04-01 09:13:31.758  3363  4013 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dff4790 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{16df8889 11833:com.samsung.android.app.vrsetupwizardstub/u0a63}
,04-01 09:13:31.768  3979  3979 D RegisteredComponentCache: Collect Tech packages for Knox
,04-01 09:13:31.778  3363  4013 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
04-01 09:13:31.778  3363  4013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,04-01 09:13:31.783  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,04-01 09:13:31.793  3363  3651 D NtpTrustedTime: currentTimeMillis() cache hit
04-01 09:13:31.793  3363  3651 D NtpTrustedTime: currentTimeMillis() cache hit
,04-01 09:13:31.798  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,04-01 09:13:31.803  3363  3389 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,04-01 09:13:31.803  6717  6717 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,04-01 09:13:31.808  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
,04-01 09:13:31.808  6717  6717 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,04-01 09:13:31.808  6717  6717 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,04-01 09:13:31.808  3363  4440 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
04-01 09:13:31.808  3363  4440 D KnoxTimeoutHandler: postActiveUserChange for user 0
04-01 09:13:31.808  3363  4440 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,04-01 09:13:31.813  2862  2862 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
04-01 09:13:31.813 11833 11833 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
04-01 09:13:31.813 11833 11833 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
04-01 09:13:31.813 11833 11833 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,04-01 09:13:31.813  3363  3982 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
04-01 09:13:31.813  3363  3576 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{31f7a058 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
04-01 09:13:31.813  3363  6568 I ActivityManager: Killing 10462:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,04-01 09:13:31.818  3363  6568 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dff4790 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{21c5e4e6 7154:com.samsung.klmsagent/u0a21}
,04-01 09:13:31.818  7154  7154 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Apr 01 09:13:31 GMT+02:00 2016
,04-01 09:13:31.818  3363  4451 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,04-01 09:13:31.823  3363  3982 D InputDispatcher: Focus entered window: 6717
,04-01 09:13:31.823  3363  3578 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3363 uid:1000
04-01 09:13:31.823  3363  3578 D PointerIcon: setMouseCustomIcon IconType is same.101
04-01 09:13:31.823  3363  3578 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3363 uid:1000
04-01 09:13:31.823  3363  3578 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,04-01 09:13:31.823  6717  6717 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,04-01 09:13:31.828  6717  9475 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,04-01 09:13:31.828  6717  6717 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,04-01 09:13:31.833  7154  7154 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,04-01 09:13:31.833  7154  7154 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
04-01 09:13:31.833  7154  7154 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,04-01 09:13:31.838  7154  7154 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
04-01 09:13:31.838  7154 11849 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : MDMBridge.getInstance()
04-01 09:13:31.838  7154 11849 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
04-01 09:13:31.843  3363  3389 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
,04-01 09:13:31.843  3363  3389 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,04-01 09:13:31.843  7154 11849 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,04-01 09:13:31.848  7154 11849 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
04-01 09:13:31.848  3363  3389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dff4790 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{6f4e01 6888:com.samsung.aasaservice/1000}
,04-01 09:13:31.853  6888  6888 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,04-01 09:13:31.853  6888  6888 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,04-01 09:13:31.853  7154 11849 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
04-01 09:13:31.853  6888  6888 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
04-01 09:13:31.853  6888  6888 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:31.853  6888  6888 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
04-01 09:13:31.853  6888  6888 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:13:31.853  6888  6888 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:13:31.853  6888  6888 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
04-01 09:13:31.853  6888  6888 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,04-01 09:13:31.853  7154 11849 E KLMS-2.5.262: : arr si null
,04-01 09:13:31.863  7154 11849 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,04-01 09:13:31.863  7154 11849 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
04-01 09:13:31.863  7154 11849 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
04-01 09:13:31.863  3363  3571 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver}
04-01 09:13:31.863  3363  3571 W BroadcastQueue: android.os.DeadObjectException
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:511)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:1109)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:404)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1510)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:221)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:31.863  3363  3571 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
04-01 09:13:31.863  7154 11849 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,04-01 09:13:31.873  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.873  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.873  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.873  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:31.888 11850 11850 E Zygote  : MountEmulatedStorage()
04-01 09:13:31.888 11850 11850 E Zygote  : v2
04-01 09:13:31.888 11850 11850 I libpersona: KNOX_SDCARD checking this for 10042
04-01 09:13:31.888 11850 11850 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:31.888 11850 11850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:31.888  3363  3571 I ActivityManager: Start proc 11850:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,04-01 09:13:31.893 11850 11850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,04-01 09:13:31.893 11850 11850 E Zygote  : accessInfo : 0
,04-01 09:13:31.893 11850 11850 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,04-01 09:13:31.898  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.898  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.898  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.898  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:31.918 11865 11865 E Zygote  : MountEmulatedStorage()
04-01 09:13:31.918 11865 11865 E Zygote  : v2
04-01 09:13:31.918 11865 11865 I libpersona: KNOX_SDCARD checking this for 1000
04-01 09:13:31.918 11865 11865 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:31.918  3363  3589 I art     : Explicit concurrent mark sweep GC freed 12604(1107KB) AllocSpace objects, 3(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.466ms total 177.318ms
04-01 09:13:31.918  3363  3571 I ActivityManager: Start proc 11865:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
04-01 09:13:31.918 11865 11865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:31.923  3363  3597 W ActivityManager: Spurious death for ProcessRecord{2f5b88b3 11850:com.samsung.android.sdk.samsunglink/u0a42}, curProc for 10462: null
,04-01 09:13:31.928 11850 11850 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 09:13:31.928  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.928  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.928  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:31.928  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:31.928 11865 11865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:31.928 10945 11839 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,04-01 09:13:31.928 11865 11865 E Zygote  : accessInfo : 0
04-01 09:13:31.933 11865 11865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:31.933 11850 11850 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:31.943 11874 11874 E Zygote  : MountEmulatedStorage()
04-01 09:13:31.943 11874 11874 I libpersona: KNOX_SDCARD checking this for 1000
04-01 09:13:31.943 11874 11874 E Zygote  : v2
04-01 09:13:31.943 11874 11874 I libpersona: KNOX_SDCARD not a persona
04-01 09:13:31.948 11874 11874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 09:13:31.948  3363  3571 I ActivityManager: Start proc 11874:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
04-01 09:13:31.948 11874 11874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:31.948 11874 11874 E Zygote  : accessInfo : 0
04-01 09:13:31.953 11874 11874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:31.958  3363  4011 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{4d4b93e u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2f5b88b3 11850:com.samsung.android.sdk.samsunglink/u0a42}
,04-01 09:13:31.963  7154 11849 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
,04-01 09:13:31.963  7154 11849 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
,04-01 09:13:31.963  7154 11849 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
04-01 09:13:31.963  7154 11849 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,04-01 09:13:31.968  3363  3389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3dff4790 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{48d2dda 3363:system/1000}
,04-01 09:13:31.973 11865 11865 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 09:13:31.973 11865 11865 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:31.978 11874 11874 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 09:13:31.978 11874 11874 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:31.978  7154 11849 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
04-01 09:13:31.978  7154 11849 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
04-01 09:13:31.978  7154 11849 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
04-01 09:13:31.978  7154 11849 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,04-01 09:13:31.983  3363  4012 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,04-01 09:13:31.983  3363  4012 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11674 uid 10011
04-01 09:13:31.983  3363  3589 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
04-01 09:13:31.983  3363  3589 D PackageManager: delete codoeFile: 
,04-01 09:13:31.988 11850 11850 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
04-01 09:13:31.988 11850 11850 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,04-01 09:13:31.988  3363  3589 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
04-01 09:13:31.988  4493  4493 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,04-01 09:13:31.993  3363  3589 I AASA_removePackage: UID=10011 Target=com.test.thalitest
04-01 09:13:31.993  3363  3391 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2f7f38ab u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3bb16b08 11865:com.samsung.android.sm/1000}
,04-01 09:13:31.993  3363  3589 D PackageManager: result of delete: 1{90841169}
,04-01 09:13:32.003 11805 11805 I art     : System.exit called, status: 0
04-01 09:13:32.003 11805 11805 I AndroidRuntime: VM exiting with result code 0.
,04-01 09:13:32.008  3363  3589 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
04-01 09:13:32.008  3363  3589 D PackageManager: userId{-1}
04-01 09:13:32.008  3363  3589 D PackageManager: andCode{true}
,04-01 09:13:32.008  3363  4451 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3762fb4 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{151357dd 11874:com.sec.android.app.popupuireceiver/1000}
,04-01 09:13:32.008  6717  6717 V ActivityThread: updateVisibility : ActivityRecord{11a253c token=android.os.BinderProxy@e88b8d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
04-01 09:13:32.013  6717  6717 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e88b8d time:211870
04-01 09:13:32.013 10945 11839 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
04-01 09:13:32.013 10945 11839 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
04-01 09:13:32.013 10945 11839 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
04-01 09:13:32.013 10945 11839 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,04-01 09:13:32.013 11865 11865 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,04-01 09:13:32.018  7154  7154 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,04-01 09:13:32.023  3363  3566 D EnterpriseDeviceManagerService: Package has changed for user 0
04-01 09:13:32.023  3363  3566 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
04-01 09:13:32.023  3363  3566 W TextServicesManagerService: no available spell checker services found
,04-01 09:13:32.023  3363  3578 W ActivityManager: mDVFSHelper.release()
04-01 09:13:32.023  3363  3578 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19f98a9f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:211882
,04-01 09:13:32.043 11874 11874 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,04-01 09:13:32.048 10188 11898 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,04-01 09:13:32.048 10188 11898 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
04-01 09:13:32.053 10188 11898 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,04-01 09:13:32.053 10188 11898 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
04-01 09:13:32.053  3363  3958 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,04-01 09:13:32.053 10188 11898 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,04-01 09:13:32.053 10188 11898 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,04-01 09:13:32.053  3363  4011 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,04-01 09:13:32.058 11874 11874 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,04-01 09:13:32.058  3363  3597 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,04-01 09:13:32.063 11874 11874 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
,04-01 09:13:32.063 11874 11874 D PopupuiReceiver: Action package removed
,04-01 09:13:32.073  3363  4451 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3762fb4 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{18a78038 10872:com.samsung.android.snote/u0a160}
,04-01 09:13:32.078  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.078  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.078  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.078  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:32.093 11901 11901 E Zygote  : MountEmulatedStorage()
04-01 09:13:32.093 11901 11901 E Zygote  : v2
04-01 09:13:32.093 11901 11901 I libpersona: KNOX_SDCARD checking this for 10183
04-01 09:13:32.093 11901 11901 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:32.093 11901 11901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:32.098  3363  3983 I ActivityManager: Start proc 11901:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
04-01 09:13:32.098 11901 11901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:32.098 11865 11865 I art     : Explicit concurrent mark sweep GC freed 6841(325KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1733KB/3MB, paused 657us total 14.466ms
04-01 09:13:32.098 11901 11901 E Zygote  : accessInfo : 0
04-01 09:13:32.098  3363  3983 I ActivityManager: Killing 10358:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,04-01 09:13:32.098 11901 11901 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:32.113  3363  4440 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2f7f38ab u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3bb16b08 11865:com.samsung.android.sm/1000}
,04-01 09:13:32.118  3363  4440 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2f7f38ab u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3bb16b08 11865:com.samsung.android.sm/1000}
,04-01 09:13:32.128  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.128  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.128  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.128  3363  3983 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:32.128 11850 11850 I SL_DEBUG: isLoggable:: isProductShip = 1
04-01 09:13:32.128 11901 11901 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 09:13:32.133 11850 11850 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
04-01 09:13:32.133 11901 11901 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:32.138 11865 11915 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,04-01 09:13:32.148 11923 11923 E Zygote  : MountEmulatedStorage()
04-01 09:13:32.148 11923 11923 E Zygote  : v2
04-01 09:13:32.148 11923 11923 I libpersona: KNOX_SDCARD checking this for 1000
04-01 09:13:32.148 11923 11923 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:32.153  3363  3983 I ActivityManager: Start proc 11923:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,04-01 09:13:32.153 11923 11923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:32.153  3363  3983 I ActivityManager: Killing 10607:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,04-01 09:13:32.158 11923 11923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,04-01 09:13:32.158 11923 11923 E Zygote  : accessInfo : 0
,04-01 09:13:32.158 11923 11923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:32.168  3363  3566 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,04-01 09:13:32.168  3363  3389 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3762fb4 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2219d5ac 11901:com.samsung.android.provider.shootingmodeprovider/u0a183}
,04-01 09:13:32.168 11122 11131 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.168 11122 11131 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,04-01 09:13:32.178 11122 11131 E DatabaseUtils: Writing exception to parcel
04-01 09:13:32.178 11122 11131 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: #################################################################
04-01 09:13:32.178 11122 11131 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	(disk I/O error (code 6922))
04-01 09:13:32.178 11122 11131 E DatabaseUtils: #################################################################
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
04-01 09:13:32.178 11122 11131 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,04-01 09:13:32.183 11923 11923 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 09:13:32.188 11923 11923 D ActivityThread: Added TimaKeyStore provider
04-01 09:13:32.193  3363  3566 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
04-01 09:13:32.193  3363  3566 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
04-01 09:13:32.193  3363  3566 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
04-01 09:13:32.193  3363  3566 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
04-01 09:13:32.203  3363  3391 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2f7f38ab u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3b52a99d 11923:com.samsung.android.app.assistantmenu/1000}
04-01 09:13:32.213  3363  3363 D RCPManagerService: PackageReceiver onReceive()
04-01 09:13:32.213  3363  3363 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
04-01 09:13:32.213  3363  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
04-01 09:13:32.213  3363  3602 D UsbHostManager: displayNotification : [02h,02h,01h]
04-01 09:13:32.213  3363  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
04-01 09:13:32.213  3363  3602 D UsbHostManager: displayNotification : [0ah,00h,00h]
04-01 09:13:32.213  3363  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
04-01 09:13:32.213  3363  3602 D UsbHostManager: displayNotification : [02h,0dh,00h]
,04-01 09:13:32.213  3363  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
04-01 09:13:32.218  3363  3363 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
04-01 09:13:32.218  3363  3363 I OTPFW   : PackageRemovalReceiver::onReceive Enter
04-01 09:13:32.218  3363  3602 D UsbHostManager: displayNotification : [0ah,00h,01h]
04-01 09:13:32.218  3363  3363 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
04-01 09:13:32.218  3363  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
04-01 09:13:32.223  3363  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
04-01 09:13:32.223  3363  3692 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
04-01 09:13:32.223  3363  3363 I OTPFW   : ProvisionData::getAllEntries Enter
04-01 09:13:32.228  3363  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
04-01 09:13:32.228  3363  3602 D UsbHostManager: displayNotification : [09h,00h,00h]
04-01 09:13:32.228  3363  3566 D UsbSettingsManager: clearDefaults: com.test.thalitest
04-01 09:13:32.228  3363  3566 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
04-01 09:13:32.228  3363  3566 W libprocessgroup: failed to open /acct/uid_10042/pid_10462/cgroup.procs: No such file or directory
04-01 09:13:32.228  3363  3363 E OTPFW   : ProvisionData::getAllEntries Table is empty
04-01 09:13:32.233  4014  4014 E Launcher.Model: onPackageRemoved :com.test.thalitest
04-01 09:13:32.243  4014  4065 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.243  4014  4065 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
04-01 09:13:32.243 11901 11901 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: #################################################################
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: #################################################################
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
04-01 09:13:32.248 11901 11901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
04-01 09:13:32.248 11901 11901 D AndroidRuntime: Shutting down VM
04-01 09:13:32.248 11901 11901 E AndroidRuntime: FATAL EXCEPTION: main
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 11901
04-01 09:13:32.248 11901 11901 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E AndroidRuntime: #################################################################
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E AndroidRuntime: #################################################################
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E AndroidRuntime: #################################################################
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.248 11901 11901 E AndroidRuntime: #################################################################
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
04-01 09:13:32.248 11901 11901 E AndroidRuntime: 	... 11 more
04-01 09:13:32.253  3363  4013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
04-01 09:13:32.253  4014  4065 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
04-01 09:13:32.253  4014  4065 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4014
04-01 09:13:32.253  4014  4065 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:488)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:586)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:590)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:533)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2432)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.253  4014  4065 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-01 09:13:32.253 11923 11923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
04-01 09:13:32.258  3363  3829 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
04-01 09:13:32.258  3363  3829 I ActivityManager: Killing 10640:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: Can't write: system_app_crash
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:32.263  3363 11945 E DropBoxManagerService: 	... 5 more
04-01 09:13:32.263  3363 11945 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
04-01 09:13:32.268  3363  3597 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
04-01 09:13:32.268  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.268 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.268  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.268 11865 11919 E SQLiteLog: (6922) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
04-01 09:13:32.268  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.268  3363  3571 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.268 11923 11946 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: #################################################################
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: #################################################################
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.273 11923 11946 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.273 11923 11946 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.273 11923 11946 W System.err: #################################################################
04-01 09:13:32.273 11923 11946 W System.err: Error Code : 0 (SQLITE_OK)
04-01 09:13:32.273 11923 11946 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
04-01 09:13:32.273 11923 11946 W System.err: #################################################################
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
04-01 09:13:32.273  3363  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
04-01 09:13:32.273  3363  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
04-01 09:13:32.273 11923 11946 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-01 09:13:32.273 11923 11946 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
04-01 09:13:32.273 11923 11946 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.273 11923 11946 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.288 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.288 11865 11919 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
04-01 09:13:32.293 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.293 11865 11919 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
04-01 09:13:32.293 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.293 11865 11919 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
04-01 09:13:32.298 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.298 11865 11919 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,04-01 09:13:32.298 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.298 11865 11919 E SQLiteLog: (6922) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,04-01 09:13:32.298 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.298 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:183)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-01 09:13:32.303 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.303 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.303 11948 11948 I libpersona: KNOX_SDCARD checking this for 10190,
04-01 09:13:32.303 11948 11948 E Zygote  : MountEmulatedStorage()
,04-01 09:13:32.303 11948 11948 I libpersona: KNOX_SDCARD not a persona
04-01 09:13:32.303 11948 11948 E Zygote  : v2
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Error inserting name=now value=Fri Apr 01 09:13:32 GMT+02:00 2016
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
,04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:184)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.303 11865 11919 E SQLiteDatabase: ,	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.308 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,04-01 09:13:32.308 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-01 09:13:32.308 11948 11948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
04-01 09:13:32.308 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,04-01 09:13:32.308 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
04-01 09:13:32.308 11865 11919 E SQLi,teDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.308 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.308 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,04-01 09:13:32.308 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Error inserting name=DBVersion value=2003
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609),
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-01 09:13:32.313 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.313 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
,04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.313 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.313 11948 11948 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:32.318 11948 11948 E Zygote  : accessInfo : 0
04-01 09:13:32.318 11948 11948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:32.318 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.318 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error inserting name=UT enabled value=false
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.323 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,04-01 09:13:32.328  3363  3571 I ActivityManager: Start proc 11948:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
04-01 09:13:32.323 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error inserting name=AFP Enabled value=true,
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922),
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	,(disk I/O error (code 6922))
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.323 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.343  3363  4451 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.323 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.343  3363  4451 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.d,atabase.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.323 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.343  3363  4451 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.328 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.343  3363  4451 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.328 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteS,tatement.java:86)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.328 11865 11919 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.328 11865 11919 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Error inserting name=status value=successfully initialized
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	(disk I/O error (code 6922))
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: #################################################################
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
04-01 09:13:32.328 11865 11919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 09:13:32.348  3363  3630 I EventHub: Removing device '/dev/input/event10' due to inotify event
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: Can't write: system_app_crash
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 09:13:32.363  3363 11957 E DropBoxManagerService: 	... 5 more
04-01 09:13:32.363  2903  2903 I art     : Explicit concurrent mark sweep GC freed 8770(373KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 424us total 32.238ms
04-01 09:13:32.363  3363 11957 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop228.tmp
04-01 09:13:32.378  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 983us total 17.054ms
04-01 09:13:32.383  3363  3630 I EventHub: Removing device '/dev/input/event7' due to inotify event
,04-01 09:13:32.388 11865 11922 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.388 11865 11922 E SQLiteLog: (6922) statement aborts at 16: [DELETE FROM AppFreezer WHERE package_name = 'com.test.thalitest'] disk I/O error
04-01 09:13:32.388 11948 11948 D TimaKeyStoreProvider: TimaSignature is unavailable
04-01 09:13:32.393 11948 11948 D ActivityThread: Added TimaKeyStore provider
04-01 09:13:32.398  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 414us total 16.058ms
04-01 09:13:32.398  2860  3073 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
04-01 09:13:32.398  2860  3073 W Vold    : Returning OperationFailed - no handler for errno 0
04-01 09:13:32.403 11850 11850 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
04-01 09:13:32.408 11850 11850 D SecWifiDisplayUtil: Metadata value : none
,04-01 09:13:32.428  3363  3630 I EventHub: Removing device '/dev/input/event8' due to inotify event
,04-01 09:13:32.433 11967 11967 E Zygote  : MountEmulatedStorage()
04-01 09:13:32.433 11967 11967 E Zygote  : v2
04-01 09:13:32.433 11967 11967 I libpersona: KNOX_SDCARD checking this for 1000
04-01 09:13:32.433 11967 11967 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:32.433 11967 11967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:32.438 11967 11967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
04-01 09:13:32.438 11967 11967 E Zygote  : accessInfo : 0
04-01 09:13:32.438  3363  4451 I ActivityManager: Start proc 11967:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
04-01 09:13:32.443 11967 11967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:32.448  3363  3597 W ActivityManager:   Force finishing activity 1 com.sec.android.app.launcher/com.android.launcher2.Launcher
,04-01 09:13:32.458  4014  4014 D MenuAppsGridFragment: onDestroyView
,04-01 09:13:32.458  4014  4014 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
,04-01 09:13:32.468  3363  3630 I EventHub: Removing device '/dev/input/event9' due to inotify event
,04-01 09:13:32.473 11967 11967 D TimaKeyStoreProvider: TimaSignature is unavailable,
04-01 09:13:32.473 11967 11967 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:32.483  3363  3983 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3762fb4 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{27862b41 11948:com.sec.android.widgetapp.tapandpay/u0a190}
,04-01 09:13:32.488  4014  4014 D Launcher.HomeView: onDestroyView
,04-01 09:13:32.488 11901 11901 I Process : Sending signal. PID: 11901 SIG: 9
,04-01 09:13:32.508  3363  4440 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2f7f38ab u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2a9468e6 11967:com.sec.knox.bridge/1000}
,04-01 09:13:32.508  3363  3630 I EventHub: Removing device '/dev/input/event11' due to inotify event
04-01 09:13:32.508  3363  3982 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,04-01 09:13:32.533  4014  4065 I Process : Sending signal. PID: 4014 SIG: 9
,04-01 09:13:32.533  4014  4014 D Launcher: onDestroy, Launcher: 479934600
,04-01 09:13:32.538  3363  4451 I ActivityManager: Killing 10570:com.sec.android.automotive.drivelink/u0a102 (adj 15): emptyCount ##31
,04-01 09:13:32.553  2860  3073 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
04-01 09:13:32.553  2860  3073 W Vold    : Returning OperationFailed - no handler for errno 0
,04-01 09:13:32.558 11850 11850 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
04-01 09:13:32.558  3363  3630 I EventHub: Removing device '/dev/input/event12' due to inotify event
04-01 09:13:32.558 11967 11967 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,04-01 09:13:32.573  3363  3597 I ActivityManager: Process com.samsung.android.provider.shootingmodeprovider (pid 11901)(adj 9) has died(289,1466)
,04-01 09:13:32.578 11948 11948 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
04-01 09:13:32.578 11948 11948 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,04-01 09:13:32.588 11948 11948 I TapandpayWidget:Utils: Clear T&P info.
,04-01 09:13:32.593 10945 10959 W art     : Suspending all threads took: 6.664ms
,04-01 09:13:32.603 11948 11948 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
04-01 09:13:32.603  3363  3958 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
04-01 09:13:32.603 11967 11967 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,04-01 09:13:32.613  3363  3630 I EventHub: Removing device '/dev/input/event13' due to inotify event
,04-01 09:13:32.613  3363  3983 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
04-01 09:13:32.613  3363  3983 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,04-01 09:13:32.628  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.628  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.628  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.628  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:32.658 11865 11865 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,04-01 09:13:32.668  3363  3630 I EventHub: Removing device '/dev/input/event14' due to inotify event
04-01 09:13:32.668 11986 11986 E Zygote  : MountEmulatedStorage()
04-01 09:13:32.668 11986 11986 E Zygote  : v2
04-01 09:13:32.668 11986 11986 I libpersona: KNOX_SDCARD checking this for 10193
04-01 09:13:32.668 11986 11986 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:32.673 11986 11986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:32.678 11986 11986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,04-01 09:13:32.678 11986 11986 E Zygote  : accessInfo : 0
04-01 09:13:32.678  3363  6568 I ActivityManager: Start proc 11986:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
,04-01 09:13:32.683 11986 11986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,04-01 09:13:32.718  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.718  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.718  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
04-01 09:13:32.718  3363  6568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,04-01 09:13:32.718 11122 11139 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
04-01 09:13:32.718 11122 11139 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,04-01 09:13:32.723 11122 11139 E DatabaseUtils: Writing exception to parcel
04-01 09:13:32.723 11122 11139 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: #################################################################
04-01 09:13:32.723 11122 11139 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	(disk I/O error (code 6922))
04-01 09:13:32.723 11122 11139 E DatabaseUtils: #################################################################
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
04-01 09:13:32.723 11122 11139 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,04-01 09:13:32.728  3363  3958 I WindowState: WIN DEATH: Window{b725266 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,04-01 09:13:32.743 11986 11986 D TimaKeyStoreProvider: TimaSignature is unavailable
,04-01 09:13:32.743 11986 11986 D ActivityThread: Added TimaKeyStore provider
,04-01 09:13:32.768 12002 12002 E Zygote  : MountEmulatedStorage()
,04-01 09:13:32.768 12002 12002 E Zygote  : v2
,04-01 09:13:32.768 12002 12002 I libpersona: KNOX_SDCARD checking this for 10101
04-01 09:13:32.768 12002 12002 I libpersona: KNOX_SDCARD not a persona
,04-01 09:13:32.773 12002 12002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,04-01 09:13:32.778  3363  6568 I ActivityManager: Start proc 12002:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-01 09:13:32.783  3363  6568 I ActivityManager: Killing 10735:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
```
