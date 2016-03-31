#### Test 64746945aaa3c62_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-31 10:12:35.393  3420  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:12:35.393  3420  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:12:35.393  3420  4339 D BatteryService: online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-31 10:12:35.398  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:12:35.403  3420  3420 I MotionRecognitionService: Plugged
03-31 10:12:35.403  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:12:35.403  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:12:35.403  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
03-31 10:12:35.403  3420  4339 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-31 10:12:35.403  3420  4339 D BatteryService: stay LED for fully charged
--------- beginning of main
03-31 10:12:35.413  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:35.413  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:35.413  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 10:12:35.428  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:12:35.428  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
03-31 10:12:35.438  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:35.438  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:35.438  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:35.443  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:35.873 11137 11137 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 10:12:35.878 11137 11137 D AndroidRuntime: CheckJNI is OFF
03-31 10:12:35.878 11137 11137 D AndroidRuntime: readGMSProperty: start
03-31 10:12:35.878 11137 11137 D AndroidRuntime: readGMSProperty: already setted!!
03-31 10:12:35.878 11137 11137 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 10:12:35.878 11137 11137 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 10:12:35.878 11137 11137 D AndroidRuntime: readGMSProperty: end
03-31 10:12:35.878 11137 11137 D AndroidRuntime: addProductProperty: start
03-31 10:12:36.083 11137 11137 E AffinityControl: AffinityControl: registerfunction enter
03-31 10:12:36.113 11137 11137 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 10:12:36.123  3420  3977 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-31 10:12:36.128  3420  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 10:12:36.143  3420  3977 W ActivityManager: mDVFSHelper.acquire()
03-31 10:12:36.148  3420  3977 V WindowManager: addAppToken: AppWindowToken{307f917a token=Token{68109a5 ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-31 10:12:36.153  3420  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:36.153  3420  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:36.153  3420  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:36.153  3420  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:36.158  3420  3583 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 10:12:36.158  3420  3583 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-31 10:12:36.158  3420  3583 D SecWifiDisplayUtil: Metadata value : none
03-31 10:12:36.163  3420  3583 V WindowManager: Adding window Window{997c85d u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{145d7706 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-31 10:12:36.168 11157 11157 E Zygote  : MountEmulatedStorage()
03-31 10:12:36.168 11157 11157 E Zygote  : v2
03-31 10:12:36.168 11157 11157 I libpersona: KNOX_SDCARD checking this for 10011
03-31 10:12:36.168 11157 11157 I libpersona: KNOX_SDCARD not a persona
03-31 10:12:36.173 11157 11157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:12:36.178  3420  3977 I ActivityManager: Start proc 11157:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-31 10:12:36.178  3420  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 10:12:36.178  3420  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 10:12:36.178  3420  3977 D InputDispatcher: Focused application set to: xxxx
03-31 10:12:36.178  3420  3977 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 10:12:36.178 11157 11157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:12:36.178  3420  3977 D InputDispatcher: Focus left window: 6551
03-31 10:12:36.178  3420  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 10:12:36.178  3420  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 10:12:36.178 11137 11137 D AndroidRuntime: Shutting down VM
03-31 10:12:36.178 11157 11157 E Zygote  : accessInfo : 0
03-31 10:12:36.183  2860  2860 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-31 10:12:36.183 11157 11157 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 10:12:36.198  3420  3619 V AlarmManager: waitForAlarm result :4
03-31 10:12:36.203  3420  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3420 uid:1000
03-31 10:12:36.203  3420  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:12:36.203  3420  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3420 uid:1000
03-31 10:12:36.203  3420  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 10:12:36.208 11157 11157 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:12:36.208 11157 11157 D ActivityThread: Added TimaKeyStore provider
03-31 10:12:36.213  3420  3836 D PowerManagerService: setKeyboardVisibility: false
03-31 10:12:36.213  3420  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{997c85d u0 d0 Starting com.test.thalitest}
03-31 10:12:36.213  3420  3836 D ActivityManager:  Launching com.test.thalitest, updated priority
03-31 10:12:36.223  3420  3836 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42}
03-31 10:12:36.243  2860  3591 I SurfaceFlinger: id=12 Removed YUIInstallC (5/9)
03-31 10:12:36.243  2860  4626 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-31 10:12:36.248  6551  6551 V ActivityThread: updateVisibility : ActivityRecord{13372791 token=android.os.BinderProxy@132af37f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,03-31 10:12:36.403  3420  6131 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 10:12:36.438 11157 11157 D SecWifiDisplayUtil: Metadata value : none
,03-31 10:12:36.483 11157 11157 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-31 10:12:36.493 11157 11157 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6086-6088)
03-31 10:12:36.493 11157 11157 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 10:12:36.508 11157 11157 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f1a1d56}
,03-31 10:12:36.508 11157 11157 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 10:12:36.508 11157 11157 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-31 10:12:36.513 11157 11173 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-31 10:12:36.528 11157 11157 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 10:12:36.528 11157 11157 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:12:36.533 11157 11157 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 10:12:36.548 11157 11157 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-31 10:12:36.548 11157 11157 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-31 10:12:36.548 11157 11157 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-31 10:12:36.608  3420  6131 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:14), CUR = 62, LCD = 0
,03-31 10:12:36.613 11157 11196 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-31 10:12:36.643 11157 11157 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:12:36.658 11157 11157 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 10:12:36.663 11157 11157 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 10:12:36.663 11157 11157 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-31 10:12:36.668 11157 11157 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-31 10:12:36.673 11157 11157 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 10:12:36.673 11157 11157 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 10:12:36.738 11157 11209 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 10:12:36.748  3420  3977 V WindowManager: Adding window Window{2413bd0b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{997c85d u0 d0 Starting com.test.thalitest})
,03-31 10:12:36.758  3420  4008 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 10:12:36.758  3420  4008 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 10:12:36.758  3420  4008 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 10:12:36.758  3420  3420 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 10:12:36.758  3420  3420 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled,
,03-31 10:12:36.758  3420  3420 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service,
03-31 10:12:36.763  3420  3420 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 10:12:36.763  3420  3420 I EnterpriseSharedDevicePolicy: Get Result: -1
,03-31 10:12:36.763  3420  3420 I EnterpriseSharedDevicePolicy: status: false
03-31 10:12:36.763  3420  3420 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 10:12:36.773 11157 11157 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
03-31 10:12:36.773 11157 11157 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-31 10:12:36.778 11157 11157 D SecWifiDisplayUtil: Metadata value : none
,03-31 10:12:36.788  2860  2860 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-31 10:12:36.788  3420  3460 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 10:12:36.798  3420  3460 D InputDispatcher: Focus entered window: 11157
,03-31 10:12:36.803  3420  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3420 uid:1000
03-31 10:12:36.803  3420  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:12:36.803  3420  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3420 uid:1000
03-31 10:12:36.803  3420  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 10:12:36.803 11157 11157 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 10:12:36.803 11157 11209 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 10:12:36.803 11157 11209 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae42fd90 ,&mEglDisplay = 1 , &mEglConfig = -1266859760 
,03-31 10:12:36.808 11157 11209 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-31 10:12:36.808 11157 11209 D OpenGLRenderer: Enabling debug mode 0
,03-31 10:12:36.808 11157 11209 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 10:12:36.808 11157 11157 V ActivityThread: updateVisibility : ActivityRecord{dac91de token=android.os.BinderProxy@26077460 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-31 10:12:36.878  3420  4008 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 10:12:36.883  3420  3583 I ActivityManager: Displayed Component not be shown by security: +515ms (total +1m27s606ms)
,03-31 10:12:36.883  3420  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42} time:186479
03-31 10:12:36.883  3420  3583 W ActivityManager: mDVFSHelper.release()
,03-31 10:12:36.888  3726  3726 D PanelView: There is/are notification(s) 
,03-31 10:12:36.888  2860  4627 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-31 10:12:36.888  2860  3015 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-31 10:12:36.913 11157 11157 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 10:12:36.918 11157 11157 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26077460 time:186510
,03-31 10:12:36.943 11157 11157 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11157
,03-31 10:12:37.048 11157 11157 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 10:12:37.118 11157 11213 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626304896
,03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 10:12:37.123 11157 11213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1efa46af added. We now have 1 listener(s)
,03-31 10:12:37.128 11157 11213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-31 10:12:37.128 11157 11213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 10:12:37.128 11157 11213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 10:12:37.128 11157 11213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 10:12:37.133 11157 11173 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 10:12:37.133 11157 11213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d53a59a added. We now have 1 listener(s)
03-31 10:12:37.133 11157 11213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 10:12:37.138 11157 11213 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 10:12:37.138 11157 11213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 10:12:37.138 11157 11213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 10:12:37.143 11157 11213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 10:12:37.143 11157 11213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 10:12:37.143 11157 11213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:12:37.143 11157 11213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:12:37.148 11157 11213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:12:37.148 11157 11213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 10:12:37.148 11157 11213 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 10:12:37.153 11157 11157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 10:12:37.153 11157 11213 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 10:12:37.153 11157 11157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 10:12:37.208 11157 11157 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 10:12:37.558 11157 11220 W jxcore-log: Initializing JXcore engine
03-31 10:12:37.558 11157 11220 W jxcore-log: JXcore engine is ready
,03-31 10:12:37.583  4799  4799 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-31 10:12:37.583  4799  4799 E audit   : type=1400 msg=audit(1459411957.583:196): avc:  denied  { ioctl } for  pid=11220 comm="Thread-1544" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2337 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 10:12:37.583  3420  3579 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-31 10:12:37.583  4799  4799 E audit   :  SEPF_SM-N910C_5.1.1_0038
,03-31 10:12:37.583  4799  4799 E audit   : type=1300 msg=audit(1459411957.583:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=974008d8 items=0 ppid=2901 ppcomm=main pid=11220 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1544" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-31 10:12:37.583  4799  4799 E audit   : type=1320 msg=audit(1459411957.583:196): 
,03-31 10:12:37.588  3420  3579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,03-31 10:12:37.588  3420  3579 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-31 10:12:37.588  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:37.588  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:37.588  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:12:37.588  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:12:37.593 11157 11220 W jxcore-log: Starting JXcore engine
,03-31 10:12:37.598 11221 11221 E Zygote  : MountEmulatedStorage()
03-31 10:12:37.598 11221 11221 E Zygote  : v2
03-31 10:12:37.603 11221 11221 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:12:37.603 11221 11221 I libpersona: KNOX_SDCARD not a persona
,03-31 10:12:37.603 11221 11221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:12:37.603  3420  3574 I ActivityManager: Start proc 11221:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-31 10:12:37.603 11221 11221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:12:37.608 11221 11221 E Zygote  : accessInfo : 0
,03-31 10:12:37.608 11221 11221 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 10:12:37.623 11221 11221 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:12:37.623 11221 11221 D ActivityThread: Added TimaKeyStore provider
,03-31 10:12:37.628  3420  3836 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61703df u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{3874c82c 11221:com.samsung.android.securitylogagent/1000}
,03-31 10:12:37.643 11157 11220 W jxcore-log: Platform android
03-31 10:12:37.643 11157 11220 W jxcore-log: 
03-31 10:12:37.643 11157 11220 W jxcore-log: Process ARCH arm
03-31 10:12:37.643 11157 11220 W jxcore-log: 
,03-31 10:12:37.648 11221 11221 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-31 10:12:37.648 11221 11221 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-31 10:12:37.653  3420  4361 I ActivityManager: Killing 10149:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-31 10:12:37.738 11157 11220 I jxcore-log: JXcore Cordova bridge is ready!
03-31 10:12:37.738 11157 11220 I jxcore-log: 
03-31 10:12:37.738 11157 11220 W jxcore-log: JXcore engine is started
,03-31 10:12:37.748 11157 11213 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 10:12:37.748 11157 11157 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 10:12:39.158  3420  3692 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-31 10:12:40.708  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:12:43.113  3420  3863 E Watchdog: !@Sync 6 [03-31 10:12:43.117]
,03-31 10:12:43.558 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:12:43.558 11157 11220 I jxcore-log: 
,03-31 10:12:43.563 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:12:43.563 11157 11220 I jxcore-log: 
,03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:12:43.563 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:12:43.563 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:12:43.568 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:12:43.568 11157 11220 I jxcore-log: 
,03-31 10:12:43.568 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:12:43.568 11157 11220 I jxcore-log: 
,03-31 10:12:43.898 11157 11220 I jxcore-log: Unit Test app is loaded
03-31 10:12:43.898 11157 11220 I jxcore-log: 
,03-31 10:12:43.898 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:12:43.898 11157 11220 I jxcore-log: 
,03-31 10:12:43.903 11157 11157 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 10:12:43.903 11157 11220 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 10:12:43.903 11157 11220 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 10:12:43.903 11157 11220 I jxcore-log: 
,03-31 10:12:43.908 11157 11220 I jxcore-log: My device name is: samsung-SM-N910C
03-31 10:12:43.908 11157 11220 I jxcore-log: 
,03-31 10:12:45.508  3420  4340 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:12:45.508  3420  4340 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:12:45.508  3420  4340 D BatteryService: online:4, current avg:-80, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-213
03-31 10:12:45.508  3420  4340 D BatteryService: stay LED for fully charged
03-31 10:12:45.508  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:12:45.513  3420  3420 I MotionRecognitionService: Plugged
03-31 10:12:45.513  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:12:45.513  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:12:45.513  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:12:45.513  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:45.513  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:45.513  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:12:45.518  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:12:45.518  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:12:45.533  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:12:45.533  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:45.533  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:45.533  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:12:46.198  3420  3592 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-31 10:12:46.208  3420  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 10:12:46.308 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 10:12:46.308 11157 11220 I jxcore-log: 
,03-31 10:12:46.373  2891  4811 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 10:12:46.523 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 10:12:46.523 11157 11220 I jxcore-log: 
,03-31 10:12:46.528 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 10:12:46.528 11157 11220 I jxcore-log: 
,03-31 10:12:46.528 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 10:12:46.528 11157 11220 I jxcore-log: 
,03-31 10:12:46.553 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 10:12:46.553 11157 11220 I jxcore-log: 
,03-31 10:12:46.558 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 10:12:46.558 11157 11220 I jxcore-log: 
,03-31 10:12:46.563 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 10:12:46.563 11157 11220 I jxcore-log: 
,03-31 10:12:46.618  3420  6131 D SSRM:n  : SIOP:: AP = 300, PST = 281 (W:10), CUR = -80, LCD = 0
,03-31 10:12:47.793 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 10:12:47.793 11157 11220 I jxcore-log: 
,03-31 10:12:47.803 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 10:12:47.803 11157 11220 I jxcore-log: 
,03-31 10:12:47.808 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 10:12:47.808 11157 11220 I jxcore-log: 
,03-31 10:12:47.963 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 10:12:47.963 11157 11220 I jxcore-log: 
,03-31 10:12:48.003 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 10:12:48.003 11157 11220 I jxcore-log: 
,03-31 10:12:48.038 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 10:12:48.038 11157 11220 I jxcore-log: 
,03-31 10:12:48.038 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 10:12:48.038 11157 11220 I jxcore-log: 
,03-31 10:12:48.043 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 10:12:48.043 11157 11220 I jxcore-log: 
,03-31 10:12:48.048 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 10:12:48.048 11157 11220 I jxcore-log: 
,03-31 10:12:48.048 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 10:12:48.048 11157 11220 I jxcore-log: 
,03-31 10:12:48.058 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 10:12:48.058 11157 11220 I jxcore-log: 
,03-31 10:12:48.073 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 10:12:48.073 11157 11220 I jxcore-log: 
,03-31 10:12:48.123 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 10:12:48.123 11157 11220 I jxcore-log: 
,03-31 10:12:48.123 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 10:12:48.123 11157 11220 I jxcore-log: 
,03-31 10:12:48.138 11157 11220 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 10:12:48.138 11157 11220 I jxcore-log: 
,03-31 10:12:55.658  3420  3977 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:12:55.658  3420  3977 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:12:55.658  3420  3977 D BatteryService: online:4, current avg:-18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
,03-31 10:12:55.658  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-31 10:12:55.668  3420  3420 I MotionRecognitionService: Plugged
03-31 10:12:55.668  3420  3420 D MotionRecognitionService:   cableConnection= 1,
03-31 10:12:55.668  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 10:12:55.668  3420  3420 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:12:55.673  3420  3977 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 18ms,
03-31 10:12:55.678  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:12:55.673  3420  3977 D BatteryService: stay LED for fully charged,
,03-31 10:12:55.678  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:12:55.678  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 10:12:55.703  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:12:55.703  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:12:55.713  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:12:55.713  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:55.713  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:12:55.713  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:12:56.298  3420  3585 I PowerManagerService: [PWL] Off : 140s ago
,03-31 10:12:56.643  3420  6131 D SSRM:n  : SIOP:: AP = 300, PST = 279 (W:10), CUR = -18, LCD = 0
,03-31 10:12:59.993  3420  3619 V AlarmManager: waitForAlarm result :8
,03-31 10:13:00.713  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:13:00.893 11157 11220 I jxcore-log: TAP version 13
03-31 10:13:00.893 11157 11220 I jxcore-log: 
,03-31 10:13:00.893 11157 11220 I jxcore-log: # setup
03-31 10:13:00.893 11157 11220 I jxcore-log: 
,03-31 10:13:00.978 11157 11220 I jxcore-log: # 1. calling createNativeListener directly rejects
03-31 10:13:00.978 11157 11220 I jxcore-log: 
,03-31 10:13:01.508 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:01.508 11157 11220 I jxcore-log: 
,03-31 10:13:01.518 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 33463
03-31 10:13:01.518 11157 11220 I jxcore-log: 
,03-31 10:13:01.533 11157 11220 I jxcore-log: ok 1 Should throw
03-31 10:13:01.533 11157 11220 I jxcore-log: 
,03-31 10:13:01.533 11157 11220 I jxcore-log: # teardown
03-31 10:13:01.533 11157 11220 I jxcore-log: 
,03-31 10:13:01.688 11157 11220 I jxcore-log: # setup
03-31 10:13:01.688 11157 11220 I jxcore-log: 
,03-31 10:13:01.768 11157 11220 I jxcore-log: # 2. emits incomingConnectionState
03-31 10:13:01.768 11157 11220 I jxcore-log: 
,03-31 10:13:01.878 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:01.878 11157 11220 I jxcore-log: 
,03-31 10:13:01.883 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 59997
03-31 10:13:01.883 11157 11220 I jxcore-log: 
,03-31 10:13:01.893 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:01.893 11157 11220 I jxcore-log: 
,03-31 10:13:01.903 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:01.903 11157 11220 I jxcore-log: 
,03-31 10:13:01.913 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:01.913 11157 11220 I jxcore-log: 
,03-31 10:13:01.923 11157 11220 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-31 10:13:01.923 11157 11220 I jxcore-log: 
,03-31 10:13:01.948 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:01.948 11157 11220 I jxcore-log: 
,03-31 10:13:01.948 11157 11220 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-31 10:13:01.948 11157 11220 I jxcore-log: 
,03-31 10:13:01.963 11157 11220 I jxcore-log: # teardown
03-31 10:13:01.963 11157 11220 I jxcore-log: 
,03-31 10:13:02.018 11157 11220 I jxcore-log: # setup
03-31 10:13:02.018 11157 11220 I jxcore-log: 
,03-31 10:13:02.228 11157 11220 I jxcore-log: # 3. emits routerPortConnectionFailed
03-31 10:13:02.228 11157 11220 I jxcore-log: 
,03-31 10:13:02.398 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:02.398 11157 11220 I jxcore-log: 
,03-31 10:13:02.403 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 45293
03-31 10:13:02.403 11157 11220 I jxcore-log: 
,03-31 10:13:02.413 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:02.413 11157 11220 I jxcore-log: 
,03-31 10:13:02.418 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:02.418 11157 11220 I jxcore-log: 
,03-31 10:13:02.418 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:02.418 11157 11220 I jxcore-log: 
,03-31 10:13:02.453 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.453 11157 11220 I jxcore-log: 
,03-31 10:13:02.458 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.458 11157 11220 I jxcore-log: 
,03-31 10:13:02.468 11157 11220 I jxcore-log: DEBUG createNativeListener: 
03-31 10:13:02.468 11157 11220 I jxcore-log: 
,03-31 10:13:02.468 11157 11220 I jxcore-log: ok 4 tried to connect to right port
03-31 10:13:02.468 11157 11220 I jxcore-log: 
,03-31 10:13:02.473 11157 11220 I jxcore-log: ok 5 failed due to refused connection
03-31 10:13:02.473 11157 11220 I jxcore-log: 
,03-31 10:13:02.473 11157 11220 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-31 10:13:02.473 11157 11220 I jxcore-log: 
,03-31 10:13:02.478 11157 11220 I jxcore-log: # teardown
03-31 10:13:02.478 11157 11220 I jxcore-log: 
,03-31 10:13:02.483 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:02.483 11157 11220 I jxcore-log: 
,03-31 10:13:02.583 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:02.583 11157 11220 I jxcore-log: 
,03-31 10:13:02.588 11157 11220 I jxcore-log: # setup
03-31 10:13:02.588 11157 11220 I jxcore-log: 
,03-31 10:13:02.593 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:02.593 11157 11220 I jxcore-log: 
,03-31 10:13:02.738 11157 11220 I jxcore-log: # 4. native server connections all up
03-31 10:13:02.738 11157 11220 I jxcore-log: 
,03-31 10:13:02.838 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:02.838 11157 11220 I jxcore-log: 
,03-31 10:13:02.843 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 41625
03-31 10:13:02.843 11157 11220 I jxcore-log: 
,03-31 10:13:02.858 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:02.858 11157 11220 I jxcore-log: 
,03-31 10:13:02.863 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:02.863 11157 11220 I jxcore-log: 
,03-31 10:13:02.863 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:02.863 11157 11220 I jxcore-log: 
,03-31 10:13:02.898 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.898 11157 11220 I jxcore-log: 
,03-31 10:13:02.903 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.903 11157 11220 I jxcore-log: 
,03-31 10:13:02.913 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:02.913 11157 11220 I jxcore-log: 
,03-31 10:13:02.918 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:02.918 11157 11220 I jxcore-log: 
,03-31 10:13:02.958 11157 11220 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-31 10:13:02.958 11157 11220 I jxcore-log: 
,03-31 10:13:02.963 11157 11220 I jxcore-log: ok 8 Send/recvd #1 should be same
03-31 10:13:02.963 11157 11220 I jxcore-log: 
,03-31 10:13:02.968 11157 11220 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-31 10:13:02.968 11157 11220 I jxcore-log: 
,03-31 10:13:02.968 11157 11220 I jxcore-log: ok 10 Send/recvd #2 should be same
03-31 10:13:02.968 11157 11220 I jxcore-log: 
,03-31 10:13:02.973 11157 11220 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-31 10:13:02.973 11157 11220 I jxcore-log: 
,03-31 10:13:02.983 11157 11220 I jxcore-log: # teardown
03-31 10:13:02.983 11157 11220 I jxcore-log: 
,03-31 10:13:03.093 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:03.093 11157 11220 I jxcore-log: 
,03-31 10:13:03.098 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:03.098 11157 11220 I jxcore-log: 
,03-31 10:13:03.103 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:03.103 11157 11220 I jxcore-log: 
,03-31 10:13:03.113 11157 11220 I jxcore-log: # setup
03-31 10:13:03.113 11157 11220 I jxcore-log: 
,03-31 10:13:03.113 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:03.113 11157 11220 I jxcore-log: 
,03-31 10:13:03.238 11157 11220 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-31 10:13:03.238 11157 11220 I jxcore-log: 
,03-31 10:13:03.448 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:03.448 11157 11220 I jxcore-log: 
,03-31 10:13:03.453 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 42733
03-31 10:13:03.453 11157 11220 I jxcore-log: 
,03-31 10:13:03.463 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:03.463 11157 11220 I jxcore-log: 
,03-31 10:13:03.468 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:03.468 11157 11220 I jxcore-log: 
,03-31 10:13:03.473 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:03.473 11157 11220 I jxcore-log: 
,03-31 10:13:03.488 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:03.488 11157 11220 I jxcore-log: 
,03-31 10:13:03.493 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:03.493 11157 11220 I jxcore-log: 
,03-31 10:13:03.508 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:03.508 11157 11220 I jxcore-log: 
,03-31 10:13:03.528 11157 11220 I jxcore-log: ok 12 socket shouldn't close until after stream
03-31 10:13:03.528 11157 11220 I jxcore-log: 
,03-31 10:13:03.528 11157 11220 I jxcore-log: ok 13 incoming remains open
03-31 10:13:03.528 11157 11220 I jxcore-log: 
,03-31 10:13:03.538 11157 11220 I jxcore-log: # teardown
03-31 10:13:03.538 11157 11220 I jxcore-log: 
,03-31 10:13:03.603 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:03.603 11157 11220 I jxcore-log: 
,03-31 10:13:03.608 11157 11220 I jxcore-log: # setup
03-31 10:13:03.608 11157 11220 I jxcore-log: 
,03-31 10:13:03.608 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:03.608 11157 11220 I jxcore-log: 
,03-31 10:13:03.748 11157 11220 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-31 10:13:03.748 11157 11220 I jxcore-log: 
,03-31 10:13:03.848 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:03.848 11157 11220 I jxcore-log: 
,03-31 10:13:03.853 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 44032
03-31 10:13:03.853 11157 11220 I jxcore-log: 
,03-31 10:13:03.863 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:03.863 11157 11220 I jxcore-log: 
,03-31 10:13:03.863 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:03.863 11157 11220 I jxcore-log: 
,03-31 10:13:03.868 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:03.868 11157 11220 I jxcore-log: 
,03-31 10:13:03.883 11157 11220 I jxcore-log: ok 14 we should not have gotten an error
03-31 10:13:03.883 11157 11220 I jxcore-log: 
,03-31 10:13:03.888 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:03.888 11157 11220 I jxcore-log: 
,03-31 10:13:03.898 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:03.898 11157 11220 I jxcore-log: 
,03-31 10:13:03.913 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:03.913 11157 11220 I jxcore-log: 
,03-31 10:13:03.918 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:03.918 11157 11220 I jxcore-log: 
,03-31 10:13:03.928 11157 11220 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-31 10:13:03.928 11157 11220 I jxcore-log: 
,03-31 10:13:03.928 11157 11220 I jxcore-log: ok 16 incoming is cleaned up
03-31 10:13:03.928 11157 11220 I jxcore-log: 
,03-31 10:13:03.933 11157 11220 I jxcore-log: # teardown
03-31 10:13:03.933 11157 11220 I jxcore-log: 
,03-31 10:13:04.063 11157 11220 I jxcore-log: # setup
03-31 10:13:04.063 11157 11220 I jxcore-log: 
,03-31 10:13:04.208 11157 11220 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-31 10:13:04.208 11157 11220 I jxcore-log: 
,03-31 10:13:04.318 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:04.318 11157 11220 I jxcore-log: 
,03-31 10:13:04.328 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 45263
03-31 10:13:04.328 11157 11220 I jxcore-log: 
,03-31 10:13:04.338 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:04.338 11157 11220 I jxcore-log: 
,03-31 10:13:04.343 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:04.343 11157 11220 I jxcore-log: 
,03-31 10:13:04.348 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:04.348 11157 11220 I jxcore-log: 
,03-31 10:13:04.363 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:04.363 11157 11220 I jxcore-log: 
,03-31 10:13:04.368 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:04.368 11157 11220 I jxcore-log: 
,03-31 10:13:04.383 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:04.383 11157 11220 I jxcore-log: 
,03-31 10:13:04.398 11157 11220 I jxcore-log: ok 17 stream was closed
03-31 10:13:04.398 11157 11220 I jxcore-log: 
,03-31 10:13:04.398 11157 11220 I jxcore-log: ok 18 incoming should survive
03-31 10:13:04.398 11157 11220 I jxcore-log: 
,03-31 10:13:04.403 11157 11220 I jxcore-log: ok 19 mux should have no streams
03-31 10:13:04.403 11157 11220 I jxcore-log: 
,03-31 10:13:04.408 11157 11220 I jxcore-log: # teardown
03-31 10:13:04.408 11157 11220 I jxcore-log: 
,03-31 10:13:04.493 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:04.493 11157 11220 I jxcore-log: 
,03-31 10:13:04.498 11157 11220 I jxcore-log: # setup
03-31 10:13:04.498 11157 11220 I jxcore-log: 
,03-31 10:13:04.503 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:04.503 11157 11220 I jxcore-log: 
,03-31 10:13:04.658 11157 11220 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-31 10:13:04.658 11157 11220 I jxcore-log: 
,03-31 10:13:04.748 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:04.748 11157 11220 I jxcore-log: 
,03-31 10:13:04.758 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 38388
03-31 10:13:04.758 11157 11220 I jxcore-log: 
,03-31 10:13:04.768 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:04.768 11157 11220 I jxcore-log: 
,03-31 10:13:04.773 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:04.773 11157 11220 I jxcore-log: 
,03-31 10:13:04.778 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:04.778 11157 11220 I jxcore-log: 
,03-31 10:13:04.793 11157 11220 I jxcore-log: ok 20 we should not have gotten an error
03-31 10:13:04.793 11157 11220 I jxcore-log: 
,03-31 10:13:04.803 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:04.803 11157 11220 I jxcore-log: 
,03-31 10:13:04.803 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:04.803 11157 11220 I jxcore-log: 
,03-31 10:13:04.818 11157 11220 I jxcore-log: ok 21 Buffers are identical
03-31 10:13:04.818 11157 11220 I jxcore-log: 
,03-31 10:13:04.818 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:04.818 11157 11220 I jxcore-log: 
,03-31 10:13:04.823 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:04.823 11157 11220 I jxcore-log: 
,03-31 10:13:04.828 11157 11220 I jxcore-log: ok 22 native server is nulled out
03-31 10:13:04.828 11157 11220 I jxcore-log: 
,03-31 10:13:04.828 11157 11220 I jxcore-log: ok 23 native server should be closed
03-31 10:13:04.828 11157 11220 I jxcore-log: 
,03-31 10:13:04.833 11157 11220 I jxcore-log: ok 24 incoming has been removed
03-31 10:13:04.833 11157 11220 I jxcore-log: 
03-31 10:13:04.833 11157 11220 I jxcore-log: ok 25 Incoming should be done
03-31 10:13:04.833 11157 11220 I jxcore-log: 
,03-31 10:13:04.833 11157 11220 I jxcore-log: ok 26 The mux object should be closed
03-31 10:13:04.833 11157 11220 I jxcore-log: 
,03-31 10:13:04.833 11157 11220 I jxcore-log: ok 27 The mux stream should be closed
03-31 10:13:04.833 11157 11220 I jxcore-log: 
,03-31 10:13:04.833 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:04.833 11157 11220 I jxcore-log: 
,03-31 10:13:04.853 11157 11220 I jxcore-log: # teardown
03-31 10:13:04.853 11157 11220 I jxcore-log: 
,03-31 10:13:04.928 11157 11220 I jxcore-log: # setup
03-31 10:13:04.928 11157 11220 I jxcore-log: 
,03-31 10:13:05.103 11157 11220 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely,
03-31 10:13:05.103 11157 11220 I jxcore-log: 
,03-31 10:13:05.218 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:05.218 11157 11220 I jxcore-log: 
,03-31 10:13:05.228 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 60151
03-31 10:13:05.228 11157 11220 I jxcore-log: 
,03-31 10:13:05.258 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.258 11157 11220 I jxcore-log: 
,03-31 10:13:05.258 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.258 11157 11220 I jxcore-log: 
,03-31 10:13:05.263 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.263 11157 11220 I jxcore-log: 
,03-31 10:13:05.268 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.268 11157 11220 I jxcore-log: 
,03-31 10:13:05.268 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.268 11157 11220 I jxcore-log: 
,03-31 10:13:05.273 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.273 11157 11220 I jxcore-log: 
,03-31 10:13:05.278 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.278 11157 11220 I jxcore-log: 
,03-31 10:13:05.278 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.278 11157 11220 I jxcore-log: 
,03-31 10:13:05.283 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.283 11157 11220 I jxcore-log: 
,03-31 10:13:05.283 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.283 11157 11220 I jxcore-log: 
,03-31 10:13:05.288 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.288 11157 11220 I jxcore-log: 
,03-31 10:13:05.288 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.288 11157 11220 I jxcore-log: 
,03-31 10:13:05.293 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.293 11157 11220 I jxcore-log: 
,03-31 10:13:05.298 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.298 11157 11220 I jxcore-log: 
,03-31 10:13:05.298 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.298 11157 11220 I jxcore-log: 
,03-31 10:13:05.303 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.303 11157 11220 I jxcore-log: 
,03-31 10:13:05.303 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.303 11157 11220 I jxcore-log: 
,03-31 10:13:05.308 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.308 11157 11220 I jxcore-log: 
,03-31 10:13:05.308 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.308 11157 11220 I jxcore-log: 
,03-31 10:13:05.308 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.308 11157 11220 I jxcore-log: 
,03-31 10:13:05.313 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.313 11157 11220 I jxcore-log: 
,03-31 10:13:05.313 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.313 11157 11220 I jxcore-log: 
,03-31 10:13:05.318 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.318 11157 11220 I jxcore-log: 
,03-31 10:13:05.318 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.318 11157 11220 I jxcore-log: 
,03-31 10:13:05.323 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.323 11157 11220 I jxcore-log: 
,03-31 10:13:05.323 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.323 11157 11220 I jxcore-log: 
,03-31 10:13:05.323 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.323 11157 11220 I jxcore-log: 
,03-31 10:13:05.328 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:05.328 11157 11220 I jxcore-log: 
,03-31 10:13:05.328 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:05.328 11157 11220 I jxcore-log: 
,03-31 10:13:05.328 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:05.328 11157 11220 I jxcore-log: 
,03-31 10:13:05.443 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.443 11157 11220 I jxcore-log: 
,03-31 10:13:05.448 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.448 11157 11220 I jxcore-log: 
,03-31 10:13:05.448 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.448 11157 11220 I jxcore-log: 
,03-31 10:13:05.448 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.448 11157 11220 I jxcore-log: 
,03-31 10:13:05.453 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.453 11157 11220 I jxcore-log: 
,03-31 10:13:05.453 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.453 11157 11220 I jxcore-log: 
,03-31 10:13:05.453 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.453 11157 11220 I jxcore-log: 
,03-31 10:13:05.458 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.458 11157 11220 I jxcore-log: 
,03-31 10:13:05.458 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.458 11157 11220 I jxcore-log: 
,03-31 10:13:05.463 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.463 11157 11220 I jxcore-log: 
,03-31 10:13:05.463 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.463 11157 11220 I jxcore-log: 
,03-31 10:13:05.463 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.463 11157 11220 I jxcore-log: 
,03-31 10:13:05.468 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.468 11157 11220 I jxcore-log: 
,03-31 10:13:05.468 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.468 11157 11220 I jxcore-log: 
,03-31 10:13:05.468 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.468 11157 11220 I jxcore-log: 
,03-31 10:13:05.473 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.473 11157 11220 I jxcore-log: 
,03-31 10:13:05.473 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.473 11157 11220 I jxcore-log: 
,03-31 10:13:05.473 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.473 11157 11220 I jxcore-log: 
,03-31 10:13:05.473 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.473 11157 11220 I jxcore-log: 
,03-31 10:13:05.478 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.478 11157 11220 I jxcore-log: 
,03-31 10:13:05.478 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.478 11157 11220 I jxcore-log: 
,03-31 10:13:05.483 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.483 11157 11220 I jxcore-log: 
,03-31 10:13:05.483 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.483 11157 11220 I jxcore-log: 
,03-31 10:13:05.483 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.483 11157 11220 I jxcore-log: 
,03-31 10:13:05.483 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.483 11157 11220 I jxcore-log: 
,03-31 10:13:05.488 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.488 11157 11220 I jxcore-log: 
,03-31 10:13:05.488 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.488 11157 11220 I jxcore-log: 
,03-31 10:13:05.488 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.488 11157 11220 I jxcore-log: 
,03-31 10:13:05.488 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.488 11157 11220 I jxcore-log: 
,03-31 10:13:05.493 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.493 11157 11220 I jxcore-log: 
,03-31 10:13:05.493 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.493 11157 11220 I jxcore-log: 
,03-31 10:13:05.493 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.493 11157 11220 I jxcore-log: 
,03-31 10:13:05.493 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.493 11157 11220 I jxcore-log: 
,03-31 10:13:05.498 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.498 11157 11220 I jxcore-log: 
,03-31 10:13:05.498 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.498 11157 11220 I jxcore-log: 
,03-31 10:13:05.498 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.498 11157 11220 I jxcore-log: 
,03-31 10:13:05.498 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.498 11157 11220 I jxcore-log: 
,03-31 10:13:05.498 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.498 11157 11220 I jxcore-log: 
,03-31 10:13:05.503 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.503 11157 11220 I jxcore-log: 
,03-31 10:13:05.503 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.503 11157 11220 I jxcore-log: 
,03-31 10:13:05.503 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.503 11157 11220 I jxcore-log: 
,03-31 10:13:05.503 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.503 11157 11220 I jxcore-log: 
,03-31 10:13:05.508 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.508 11157 11220 I jxcore-log: 
,03-31 10:13:05.508 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.508 11157 11220 I jxcore-log: 
,03-31 10:13:05.508 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.508 11157 11220 I jxcore-log: 
,03-31 10:13:05.508 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.508 11157 11220 I jxcore-log: 
,03-31 10:13:05.513 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.513 11157 11220 I jxcore-log: 
,03-31 10:13:05.513 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.513 11157 11220 I jxcore-log: 
,03-31 10:13:05.523 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.523 11157 11220 I jxcore-log: 
,03-31 10:13:05.523 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.523 11157 11220 I jxcore-log: 
,03-31 10:13:05.523 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.523 11157 11220 I jxcore-log: 
,03-31 10:13:05.523 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.523 11157 11220 I jxcore-log: 
,03-31 10:13:05.528 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.528 11157 11220 I jxcore-log: 
,03-31 10:13:05.528 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.528 11157 11220 I jxcore-log: 
,03-31 10:13:05.528 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.528 11157 11220 I jxcore-log: 
,03-31 10:13:05.528 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.528 11157 11220 I jxcore-log: 
,03-31 10:13:05.533 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.533 11157 11220 I jxcore-log: 
,03-31 10:13:05.533 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.533 11157 11220 I jxcore-log: 
,03-31 10:13:05.533 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.533 11157 11220 I jxcore-log: 
,03-31 10:13:05.538 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.538 11157 11220 I jxcore-log: 
,03-31 10:13:05.538 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.538 11157 11220 I jxcore-log: 
,03-31 10:13:05.538 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.538 11157 11220 I jxcore-log: 
,03-31 10:13:05.538 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.538 11157 11220 I jxcore-log: 
,03-31 10:13:05.538 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.538 11157 11220 I jxcore-log: 
,03-31 10:13:05.543 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.543 11157 11220 I jxcore-log: 
,03-31 10:13:05.543 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.543 11157 11220 I jxcore-log: 
,03-31 10:13:05.543 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.543 11157 11220 I jxcore-log: 
,03-31 10:13:05.548 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.548 11157 11220 I jxcore-log: 
,03-31 10:13:05.548 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.548 11157 11220 I jxcore-log: 
,03-31 10:13:05.548 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.548 11157 11220 I jxcore-log: 
,03-31 10:13:05.548 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.548 11157 11220 I jxcore-log: 
,03-31 10:13:05.548 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.548 11157 11220 I jxcore-log: 
,03-31 10:13:05.553 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.553 11157 11220 I jxcore-log: 
,03-31 10:13:05.553 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.553 11157 11220 I jxcore-log: 
,03-31 10:13:05.553 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.553 11157 11220 I jxcore-log: 
,03-31 10:13:05.553 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.553 11157 11220 I jxcore-log: ,
03-31 10:13:05.558 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.558 11157 11220 I jxcore-log: 
,03-31 10:13:05.558 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.558 11157 11220 I jxcore-log: 
,03-31 10:13:05.558 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:05.558 11157 11220 I jxcore-log: 
,03-31 10:13:05.558 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:05.558 11157 11220 I jxcore-log: 
,03-31 10:13:05.618 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.618 11157 11220 I jxcore-log: 
,03-31 10:13:05.618 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.618 11157 11220 I jxcore-log: 
,03-31 10:13:05.618 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.618 11157 11220 I jxcore-log: 
,03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.623 11157 11220 I jxcore-log: 
03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.623 11157 11220 I jxcore-log: 
,03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.623 11157 11220 I jxcore-log: 
03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.623 11157 11220 I jxcore-log: 
,03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.623 11157 11220 I jxcore-log: 
03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.623 11157 11220 I jxcore-log: 
03-31 10:13:05.623 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.623 11157 11220 I jxcore-log: 
,03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628 11157 11220 I jxcore-log: 
,03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628 11157 11220 I jxcore-log: 
03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628 11157 11220 I jxcore-log: 
,03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628 11157 11220 I jxcore-log: 
,03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.628 11157 11220 I jxcore-log: 
03-31 10:13:05.628 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.628 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.633 11157 11220 I jxcore-log: 
03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.633 11157 11220 I jxcore-log: 
,03-31 10:13:05.633 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.633 11157 11220 I jxcore-log: 
03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
,03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
,03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.638 11157 11220 I jxcore-log: 
,03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
,03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.638 11157 11220 I jxcore-log: 
,03-31 10:13:05.638 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.638 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
,03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
,03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
,03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.643 11157 11220 I jxcore-log: 
03-31 10:13:05.643 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.643 11157 11220 I jxcore-log: 
,03-31 10:13:05.648 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.648 11157 11220 I jxcore-log: 
03-31 10:13:05.648 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.648 11157 11220 I jxcore-log: 
,03-31 10:13:05.648 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:05.648 11157 11220 I jxcore-log: 
03-31 10:13:05.648 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:05.648 11157 11220 I jxcore-log: 
,03-31 10:13:05.648 11157 11220 I jxcore-log: ok 28 native server is nulled out
03-31 10:13:05.648 11157 11220 I jxcore-log: 
,03-31 10:13:05.648 11157 11220 I jxcore-log: ok 29 native server should be closed
03-31 10:13:05.648 11157 11220 I jxcore-log: 
03-31 10:13:05.648 11157 11220 I jxcore-log: ok 30 incoming has been removed
03-31 10:13:05.648 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
,03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
,03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
,03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
03-31 10:13:05.653 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:05.653 11157 11220 I jxcore-log: 
,03-31 10:13:05.738 11157 11220 I jxcore-log: # teardown
03-31 10:13:05.738 11157 11220 I jxcore-log: 
,03-31 10:13:05.793  3420  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:13:05.798  3420  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:05.798  3420  3836 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:86
03-31 10:13:05.798  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 10:13:05.798  3420  3836 D BatteryService: stay LED for fully charged
,03-31 10:13:05.808  3420  3420 I MotionRecognitionService: Plugged
,03-31 10:13:05.808  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:13:05.808  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:13:05.808  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:05.818  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:05.818  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:05.823  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:05.838  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:13:05.838  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:05.848  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:05.848  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:05.853  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:05.853  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:05.883 11157 11220 I jxcore-log: # setup
03-31 10:13:05.883 11157 11220 I jxcore-log: 
,03-31 10:13:06.008 11157 11220 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-31 10:13:06.008 11157 11220 I jxcore-log: 
,03-31 10:13:06.098 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:06.098 11157 11220 I jxcore-log: 
,03-31 10:13:06.108 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 53149
03-31 10:13:06.108 11157 11220 I jxcore-log: 
,03-31 10:13:06.118 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:06.118 11157 11220 I jxcore-log: 
,03-31 10:13:06.123 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:06.123 11157 11220 I jxcore-log: 
,03-31 10:13:06.128 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:06.128 11157 11220 I jxcore-log: 
,03-31 10:13:06.138 11157 11220 I jxcore-log: ok 31 we should not have gotten an error
03-31 10:13:06.138 11157 11220 I jxcore-log: 
,03-31 10:13:06.143 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:06.143 11157 11220 I jxcore-log: 
,03-31 10:13:06.143 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:06.143 11157 11220 I jxcore-log: 
,03-31 10:13:06.153 11157 11220 I jxcore-log: ok 32 Buffers are identical
03-31 10:13:06.153 11157 11220 I jxcore-log: 
,03-31 10:13:06.158 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:06.158 11157 11220 I jxcore-log: 
,03-31 10:13:06.158 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:06.158 11157 11220 I jxcore-log: 
,03-31 10:13:06.173 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:06.173 11157 11220 I jxcore-log: 
,03-31 10:13:06.178 11157 11220 I jxcore-log: ok 33 server should be fine
03-31 10:13:06.178 11157 11220 I jxcore-log: 
,03-31 10:13:06.178 11157 11220 I jxcore-log: ok 34 server should be open
03-31 10:13:06.178 11157 11220 I jxcore-log: 
,03-31 10:13:06.178 11157 11220 I jxcore-log: ok 35 incoming has been removed
03-31 10:13:06.178 11157 11220 I jxcore-log: 
,03-31 10:13:06.183 11157 11220 I jxcore-log: ok 36 The mux object should be closed
03-31 10:13:06.183 11157 11220 I jxcore-log: 
,03-31 10:13:06.183 11157 11220 I jxcore-log: ok 37 The mux stream should be closed
03-31 10:13:06.183 11157 11220 I jxcore-log: 
,03-31 10:13:06.193 11157 11220 I jxcore-log: # teardown
03-31 10:13:06.193 11157 11220 I jxcore-log: 
,03-31 10:13:06.263 11157 11220 I jxcore-log: # setup
03-31 10:13:06.263 11157 11220 I jxcore-log: 
,03-31 10:13:06.408 11157 11220 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-31 10:13:06.408 11157 11220 I jxcore-log: 
,03-31 10:13:06.488 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:06.488 11157 11220 I jxcore-log: 
,03-31 10:13:06.498 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 58159
03-31 10:13:06.498 11157 11220 I jxcore-log: 
,03-31 10:13:06.503 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:13:06.503 11157 11220 I jxcore-log: 
,03-31 10:13:06.508 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:13:06.508 11157 11220 I jxcore-log: 
,03-31 10:13:06.508 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:13:06.508 11157 11220 I jxcore-log: 
,03-31 10:13:06.518 11157 11220 I jxcore-log: ok 38 we should not have gotten an error
03-31 10:13:06.518 11157 11220 I jxcore-log: 
,03-31 10:13:06.523 11157 11220 I jxcore-log: DEBUG createNativeListener: new stream: 
03-31 10:13:06.523 11157 11220 I jxcore-log: 
,03-31 10:13:06.528 11157 11220 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-31 10:13:06.528 11157 11220 I jxcore-log: 
,03-31 10:13:06.538 11157 11220 I jxcore-log: ok 39 Buffers are identical
03-31 10:13:06.538 11157 11220 I jxcore-log: 
,03-31 10:13:06.543 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-31 10:13:06.543 11157 11220 I jxcore-log: 
,03-31 10:13:06.548 11157 11220 I jxcore-log: DEBUG createNativeListener: stream close:
03-31 10:13:06.548 11157 11220 I jxcore-log: 
,03-31 10:13:06.548 11157 11220 I jxcore-log: DEBUG createNativeListener: mux close
03-31 10:13:06.548 11157 11220 I jxcore-log: 
,03-31 10:13:06.553 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-31 10:13:06.553 11157 11220 I jxcore-log: 
,03-31 10:13:06.553 11157 11220 I jxcore-log: ok 40 server should be fine
03-31 10:13:06.553 11157 11220 I jxcore-log: 
,03-31 10:13:06.558 11157 11220 I jxcore-log: ok 41 server should be open
03-31 10:13:06.558 11157 11220 I jxcore-log: 
03-31 10:13:06.558 11157 11220 I jxcore-log: ok 42 incoming has been removed
03-31 10:13:06.558 11157 11220 I jxcore-log: 
,03-31 10:13:06.558 11157 11220 I jxcore-log: ok 43 The mux object should be closed
03-31 10:13:06.558 11157 11220 I jxcore-log: 
03-31 10:13:06.558 11157 11220 I jxcore-log: ok 44 The mux stream should be closed
03-31 10:13:06.558 11157 11220 I jxcore-log: 
,03-31 10:13:06.568 11157 11220 I jxcore-log: # teardown
03-31 10:13:06.568 11157 11220 I jxcore-log: 
,03-31 10:13:06.703  3420  6131 D SSRM:n  : SIOP:: AP = 290, PST = 280 (W:10), CUR = 36, LCD = 0
,03-31 10:13:06.718 11157 11220 I jxcore-log: # setup
03-31 10:13:06.718 11157 11220 I jxcore-log: 
,03-31 10:13:06.838 11157 11220 I jxcore-log: # 12. closeAll can close even when connections open
03-31 10:13:06.838 11157 11220 I jxcore-log: 
,03-31 10:13:06.973 11157 11220 I jxcore-log: ok 45 not possible to connect to the server anymore
03-31 10:13:06.973 11157 11220 I jxcore-log: 
,03-31 10:13:06.983 11157 11220 I jxcore-log: # teardown
03-31 10:13:06.983 11157 11220 I jxcore-log: 
,03-31 10:13:07.068 11157 11220 I jxcore-log: # setup
03-31 10:13:07.068 11157 11220 I jxcore-log: 
,03-31 10:13:07.218 11157 11220 I jxcore-log: # 13. closeAll with promise
03-31 10:13:07.218 11157 11220 I jxcore-log: 
,03-31 10:13:07.663 11157 11220 I jxcore-log: ok 46 not possible to connect to the server anymore
03-31 10:13:07.663 11157 11220 I jxcore-log: 
,03-31 10:13:07.673 11157 11220 I jxcore-log: # teardown
03-31 10:13:07.673 11157 11220 I jxcore-log: 
,03-31 10:13:08.293 11157 11220 I jxcore-log: # setup
03-31 10:13:08.293 11157 11220 I jxcore-log: 
,03-31 10:13:08.423 11157 11220 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-31 10:13:08.423 11157 11220 I jxcore-log: 
,03-31 10:13:08.503 11157 11220 I jxcore-log: ok 47 Got the right error
03-31 10:13:08.503 11157 11220 I jxcore-log: 
,03-31 10:13:08.508 11157 11220 I jxcore-log: # teardown
03-31 10:13:08.508 11157 11220 I jxcore-log: 
,03-31 10:13:08.668 11157 11220 I jxcore-log: # setup
03-31 10:13:08.668 11157 11220 I jxcore-log: 
,03-31 10:13:08.798 11157 11220 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-31 10:13:08.798 11157 11220 I jxcore-log: 
,03-31 10:13:08.893 11157 11220 I jxcore-log: # teardown
03-31 10:13:08.893 11157 11220 I jxcore-log: 
,03-31 10:13:09.108 11157 11220 I jxcore-log: # setup
03-31 10:13:09.108 11157 11220 I jxcore-log: 
,03-31 10:13:09.303 11157 11220 I jxcore-log: # 16. multiplex can send data
03-31 10:13:09.303 11157 11220 I jxcore-log: 
,03-31 10:13:09.543 11157 11220 I jxcore-log: ok 48 String should be length:200
03-31 10:13:09.543 11157 11220 I jxcore-log: 
,03-31 10:13:09.553 11157 11220 I jxcore-log: # teardown
03-31 10:13:09.553 11157 11220 I jxcore-log: 
,03-31 10:13:09.693 11157 11220 I jxcore-log: # setup
03-31 10:13:09.693 11157 11220 I jxcore-log: 
,03-31 10:13:09.808 11157 11220 I jxcore-log: # 17. enqueue and run in order
03-31 10:13:09.808 11157 11220 I jxcore-log: 
,03-31 10:13:10.068 11157 11220 I jxcore-log: ok 49 firstPromise setTimeout
03-31 10:13:10.068 11157 11220 I jxcore-log: 
,03-31 10:13:10.078 11157 11220 I jxcore-log: ok 50 firstPromise result
03-31 10:13:10.078 11157 11220 I jxcore-log: 
,03-31 10:13:10.083 11157 11220 I jxcore-log: ok 51 firstPromise testValue
03-31 10:13:10.083 11157 11220 I jxcore-log: 
,03-31 10:13:10.188 11157 11220 I jxcore-log: ok 52 secondPromise setTimeout
03-31 10:13:10.188 11157 11220 I jxcore-log: 
,03-31 10:13:10.198 11157 11220 I jxcore-log: ok 53 secondPromise result
03-31 10:13:10.198 11157 11220 I jxcore-log: 
,03-31 10:13:10.208 11157 11220 I jxcore-log: ok 54 secondPromise testValue
03-31 10:13:10.208 11157 11220 I jxcore-log: 
,03-31 10:13:10.213 11157 11220 I jxcore-log: ok 55 thirdPromise in promise
03-31 10:13:10.213 11157 11220 I jxcore-log: 
,03-31 10:13:10.218 11157 11220 I jxcore-log: ok 56 thirdPromise result
03-31 10:13:10.218 11157 11220 I jxcore-log: 
,03-31 10:13:10.223 11157 11220 I jxcore-log: ok 57 thirdPromise testValue
03-31 10:13:10.223 11157 11220 I jxcore-log: 
,03-31 10:13:10.233 11157 11220 I jxcore-log: # teardown
03-31 10:13:10.233 11157 11220 I jxcore-log: 
,03-31 10:13:10.403 11157 11220 I jxcore-log: # setup
03-31 10:13:10.403 11157 11220 I jxcore-log: 
,03-31 10:13:10.618 11157 11220 I jxcore-log: # 18. enqueueAtTop and run backwards
03-31 10:13:10.618 11157 11220 I jxcore-log: 
,03-31 10:13:10.743 11157 11220 I jxcore-log: ok 58 thirdPromise - first to run
03-31 10:13:10.743 11157 11220 I jxcore-log: 
,03-31 10:13:10.748 11157 11220 I jxcore-log: ok 59 thirdPromise - in resolve
03-31 10:13:10.748 11157 11220 I jxcore-log: 
,03-31 10:13:10.748 11157 11220 I jxcore-log: ok 60 secondPromise - second to run
03-31 10:13:10.748 11157 11220 I jxcore-log: 
,03-31 10:13:10.753 11157 11220 I jxcore-log: ok 61 secondPromise - in catch
03-31 10:13:10.753 11157 11220 I jxcore-log: 
,03-31 10:13:10.758 11157 11220 I jxcore-log: ok 62 firstPromise - third to run
03-31 10:13:10.758 11157 11220 I jxcore-log: 
,03-31 10:13:10.758 11157 11220 I jxcore-log: ok 63 firstPromise - in then
03-31 10:13:10.758 11157 11220 I jxcore-log: 
,03-31 10:13:10.763 11157 11220 I jxcore-log: ok 64 testing promises
03-31 10:13:10.763 11157 11220 I jxcore-log: 
,03-31 10:13:10.763 11157 11220 I jxcore-log: # teardown
03-31 10:13:10.763 11157 11220 I jxcore-log: 
,03-31 10:13:11.013 11157 11220 I jxcore-log: # setup
03-31 10:13:11.013 11157 11220 I jxcore-log: 
,03-31 10:13:11.188 11157 11220 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-31 10:13:11.188 11157 11220 I jxcore-log: 
,03-31 10:13:11.533 11157 11220 I jxcore-log: ok 65 fourth
03-31 10:13:11.533 11157 11220 I jxcore-log: 
,03-31 10:13:11.538 11157 11220 I jxcore-log: ok 66 fourth
03-31 10:13:11.538 11157 11220 I jxcore-log: 
,03-31 10:13:11.538 11157 11220 I jxcore-log: ok 67 second
03-31 10:13:11.538 11157 11220 I jxcore-log: 
,03-31 10:13:11.543 11157 11220 I jxcore-log: ok 68 secondPromise - in then
03-31 10:13:11.543 11157 11220 I jxcore-log: 
,03-31 10:13:11.653 11157 11220 I jxcore-log: ok 69 first
03-31 10:13:11.653 11157 11220 I jxcore-log: 
,03-31 10:13:11.658 11157 11220 I jxcore-log: ok 70 firstPromise - in catch
03-31 10:13:11.658 11157 11220 I jxcore-log: 
,03-31 10:13:11.668 11157 11220 I jxcore-log: ok 71 third
03-31 10:13:11.668 11157 11220 I jxcore-log: 
,03-31 10:13:11.673 11157 11220 I jxcore-log: ok 72 thirdPromise - in then
03-31 10:13:11.673 11157 11220 I jxcore-log: 
,03-31 10:13:11.673 11157 11220 I jxcore-log: ok 73 testingPromises
03-31 10:13:11.673 11157 11220 I jxcore-log: 
,03-31 10:13:11.683 11157 11220 I jxcore-log: # teardown
03-31 10:13:11.683 11157 11220 I jxcore-log: 
,03-31 10:13:12.433 11157 11220 I jxcore-log: # setup
03-31 10:13:12.433 11157 11220 I jxcore-log: 
,03-31 10:13:12.593 11157 11220 I jxcore-log: # 20. queues handled independently
03-31 10:13:12.593 11157 11220 I jxcore-log: 
,03-31 10:13:13.113  3420  3863 E Watchdog: !@Sync 7 [03-31 10:13:13.118]
,03-31 10:13:13.303 11157 11220 I jxcore-log: ok 74 all short operations completed before the long resolves
03-31 10:13:13.303 11157 11220 I jxcore-log: 
,03-31 10:13:13.313 11157 11220 I jxcore-log: # teardown
03-31 10:13:13.313 11157 11220 I jxcore-log: 
,03-31 10:13:13.853 11157 11220 I jxcore-log: # setup
03-31 10:13:13.853 11157 11220 I jxcore-log: 
,03-31 10:13:14.398 11157 11220 I jxcore-log: # 21. basic
03-31 10:13:14.398 11157 11220 I jxcore-log: 
,03-31 10:13:14.568 11157 11220 I jxcore-log: ok 75 sane
03-31 10:13:14.568 11157 11220 I jxcore-log: 
,03-31 10:13:14.578 11157 11220 I jxcore-log: # teardown
03-31 10:13:14.578 11157 11220 I jxcore-log: 
,03-31 10:13:14.678 11157 11220 I jxcore-log: # setup
03-31 10:13:14.678 11157 11220 I jxcore-log: 
,03-31 10:13:14.833 11157 11220 I jxcore-log: # 22. another
03-31 10:13:14.833 11157 11220 I jxcore-log: 
,03-31 10:13:15.003 11157 11220 I jxcore-log: ok 76 sane
03-31 10:13:15.003 11157 11220 I jxcore-log: 
,03-31 10:13:15.018 11157 11220 I jxcore-log: # teardown
03-31 10:13:15.018 11157 11220 I jxcore-log: 
,03-31 10:13:15.653 11157 11220 I jxcore-log: # setup
03-31 10:13:15.653 11157 11220 I jxcore-log: 
,03-31 10:13:15.933  3420  4008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:13:15.933  3420  4008 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:15.933  3420  4008 D BatteryService: online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
,03-31 10:13:15.938  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:13:15.948  3420  4008 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
,03-31 10:13:15.948  3420  4008 D BatteryService: stay LED for fully charged,
03-31 10:13:15.948  3420  3420 I MotionRecognitionService: Plugged,
03-31 10:13:15.948  3420  3420 D MotionRecognitionService:   cableConnection= 1,
,03-31 10:13:15.948  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:13:15.948  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:15.963  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:15.963  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:15.963  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:15.973  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:13:15.973  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:15.988  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:15.988  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:15.988  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:15.988  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:16.568 11157 11220 I jxcore-log: # 23. can pass data in setup
03-31 10:13:16.568 11157 11220 I jxcore-log: 
,03-31 10:13:16.703 11157 11220 I jxcore-log: ok 77 test participant has uuid
03-31 10:13:16.703 11157 11220 I jxcore-log: 
,03-31 10:13:16.708 11157 11220 I jxcore-log: ok 78 participant data matches
03-31 10:13:16.708 11157 11220 I jxcore-log: 
,03-31 10:13:16.713 11157 11220 I jxcore-log: ok 79 test participant has uuid
03-31 10:13:16.713 11157 11220 I jxcore-log: 
,03-31 10:13:16.718 11157 11220 I jxcore-log: ok 80 participant data matches
03-31 10:13:16.718 11157 11220 I jxcore-log: 
,03-31 10:13:16.723 11157 11220 I jxcore-log: ok 81 test participant has uuid
03-31 10:13:16.723 11157 11220 I jxcore-log: 
,03-31 10:13:16.723  3420  6131 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:10), CUR = 55, LCD = 0
,03-31 10:13:16.728 11157 11220 I jxcore-log: ok 82 participant data matches
03-31 10:13:16.728 11157 11220 I jxcore-log: 
,03-31 10:13:16.728 11157 11220 I jxcore-log: ok 83 own UUID is found from the participants list
03-31 10:13:16.728 11157 11220 I jxcore-log: 
,03-31 10:13:16.733 11157 11220 I jxcore-log: # teardown
03-31 10:13:16.733 11157 11220 I jxcore-log: 
,03-31 10:13:17.073 11157 11220 I jxcore-log: # setup
03-31 10:13:17.073 11157 11220 I jxcore-log: 
,03-31 10:13:17.458 11157 11220 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-31 10:13:17.458 11157 11220 I jxcore-log: 
,03-31 10:13:18.808 11157 11220 I jxcore-log: ok 84 specific error should be returned
03-31 10:13:18.808 11157 11220 I jxcore-log: 
,03-31 10:13:18.813 11157 11220 I jxcore-log: # teardown
03-31 10:13:18.813 11157 11220 I jxcore-log: 
,03-31 10:13:20.713  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:13:20.748 11157 11220 I jxcore-log: ok 85 error should be null
03-31 10:13:20.748 11157 11220 I jxcore-log: 
,03-31 10:13:20.753 11157 11220 I jxcore-log: ok 86 error should be null
03-31 10:13:20.753 11157 11220 I jxcore-log: 
,03-31 10:13:20.753 11157 11220 I jxcore-log: # setup
03-31 10:13:20.753 11157 11220 I jxcore-log: 
,03-31 10:13:22.263 11157 11220 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-31 10:13:22.263 11157 11220 I jxcore-log: 
,03-31 10:13:23.918 11157 11220 I jxcore-log: ok 87 specific error should be returned
03-31 10:13:23.918 11157 11220 I jxcore-log: 
,03-31 10:13:23.923 11157 11220 I jxcore-log: # teardown
03-31 10:13:23.923 11157 11220 I jxcore-log: 
,03-31 10:13:25.208 11157 11220 I jxcore-log: ok 88 error should be null
03-31 10:13:25.208 11157 11220 I jxcore-log: 
,03-31 10:13:25.208 11157 11220 I jxcore-log: ok 89 error should be null
03-31 10:13:25.208 11157 11220 I jxcore-log: 
,03-31 10:13:25.213 11157 11220 I jxcore-log: # setup
03-31 10:13:25.213 11157 11220 I jxcore-log: 
,03-31 10:13:26.073  3420  3463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:13:26.073  3420  3463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:26.073  3420  3463 D BatteryService: online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,03-31 10:13:26.078  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:13:26.083  3420  3420 I MotionRecognitionService: Plugged,
03-31 10:13:26.083  3420  3420 D MotionRecognitionService:   cableConnection= 1
,03-31 10:13:26.083  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 10:13:26.083  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:26.083  3420  3463 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
,03-31 10:13:26.083  3420  3463 D BatteryService: stay LED for fully charged,
,03-31 10:13:26.098  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:13:26.098  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 10:13:26.098  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:26.118  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:13:26.118  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:26.128  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:26.128  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:26.128  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:26.128  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:26.758  3420  6131 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:12), CUR = 59, LCD = 0,
,03-31 10:13:26.873 11157 11220 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-31 10:13:26.873 11157 11220 I jxcore-log: 
,03-31 10:13:27.358 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:27.358 11157 11220 I jxcore-log: 
,03-31 10:13:27.363 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 40348
03-31 10:13:27.363 11157 11220 I jxcore-log: 
,03-31 10:13:27.368 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:27.368 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:27.368 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:27.378 11157 11220 I jxcore-log: ok 90 error should be null
03-31 10:13:27.378 11157 11220 I jxcore-log: 
,03-31 10:13:27.378 11157 11220 I jxcore-log: ok 91 error should be null
03-31 10:13:27.378 11157 11220 I jxcore-log: 
,03-31 10:13:27.378 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:27.378 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:27.378 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:27.383 11157 11220 I jxcore-log: ok 92 error should be null
03-31 10:13:27.383 11157 11220 I jxcore-log: 
,03-31 10:13:27.383 11157 11220 I jxcore-log: ok 93 error should be null
03-31 10:13:27.383 11157 11220 I jxcore-log: 
,03-31 10:13:27.388 11157 11220 I jxcore-log: # teardown
03-31 10:13:27.388 11157 11220 I jxcore-log: 
,03-31 10:13:28.628 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:28.633 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:28.633 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:28.643 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:28.643 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:28.643 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:28.653 11157 11220 I jxcore-log: ok 94 error should be null
03-31 10:13:28.653 11157 11220 I jxcore-log: 
,03-31 10:13:28.653 11157 11220 I jxcore-log: ok 95 error should be null
03-31 10:13:28.653 11157 11220 I jxcore-log: 
,03-31 10:13:28.658 11157 11220 I jxcore-log: # setup,
03-31 10:13:28.658 11157 11220 I jxcore-log: 
,03-31 10:13:28.848 11157 11220 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-31 10:13:28.848 11157 11220 I jxcore-log: 
,03-31 10:13:29.503 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:29.503 11157 11220 I jxcore-log: 
,03-31 10:13:29.508 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 49733
03-31 10:13:29.508 11157 11220 I jxcore-log: 
,03-31 10:13:29.528 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-31 10:13:29.528 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:29.528 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:29.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-31 10:13:29.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:29.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:29.533 11157 11220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:29.543 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:29.548 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:13:29.548 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:29.548 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:29.548 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:29.553  5920  5933 D BtGatt.GattService: registerClient() - UUID=1d97347a-47ea-441e-ae4f-3bb835308743
,03-31 10:13:29.598  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=1d97347a-47ea-441e-ae4f-3bb835308743, clientIf=6
,03-31 10:13:29.603 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:29.603  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:29.648  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
,03-31 10:13:29.663  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:29.663  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:29.663  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:29.668  5920  6014 D BtGatt.ScanManager: isFilteringSupported
,03-31 10:13:29.668  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:29.673  5920  6014 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f1a1d56
,03-31 10:13:29.673 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-31 10:13:29.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:29.673 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:29.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-31 10:13:29.673 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:29.673 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:29.673 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:29.678 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:29.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:13:29.688 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-31 10:13:29.688 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:29.688 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:29.693 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK,
,03-31 10:13:29.693  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:29.693  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:29.693  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:29.693  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 10:13:29.698  5920  6014 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-31 10:13:29.698  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:29.698  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:29.698  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:29.703  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:13:29.703  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:29.703  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 10:13:29.708  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:29.708  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 10:13:29.718 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:29.718 11157 11220 I jxcore-log: 
,03-31 10:13:29.723 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:29.723 11157 11220 I jxcore-log: 
,03-31 10:13:29.723 11157 11220 I jxcore-log: ok 96 error should be null
03-31 10:13:29.723 11157 11220 I jxcore-log: 
,03-31 10:13:29.728 11157 11220 I jxcore-log: ok 97 error should be null
03-31 10:13:29.728 11157 11220 I jxcore-log: 
,03-31 10:13:29.733 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-31 10:13:29.733 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:29.733 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:29.733 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:29.733 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:29.738 11157 11220 I jxcore-log: ok 98 error should be null
03-31 10:13:29.738 11157 11220 I jxcore-log: 
,03-31 10:13:29.738 11157 11220 I jxcore-log: ok 99 error should be null
03-31 10:13:29.738 11157 11220 I jxcore-log: 
,03-31 10:13:29.748 11157 11220 I jxcore-log: # teardown
03-31 10:13:29.748 11157 11220 I jxcore-log: 
,03-31 10:13:30.493 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:30.493 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:30.493 11157 11220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 10:13:30.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:30.493 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:30.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:30.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:13:30.498 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:13:30.498 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:30.503  5920  5931 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:30.503  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:30.503  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 10:13:30.503  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:30.503  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:30.508  5920  6014 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 10:13:30.508  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:30.508  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:13:30.508  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:30.513  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:30.518  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:30.518  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:30.518 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 10:13:30.518 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:30.518 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:13:30.518 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:13:30.518 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:13:30.518 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:13:30.523 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:30.523 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-31 10:13:30.523 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:30.523 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:30.523 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:30.523 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 10:13:30.523 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:30.523 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:30.533 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:30.543 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 10:13:30.543 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:30.543 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:30.548 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-31 10:13:30.548 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:30.548 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:30.548 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:30.553 11157 11220 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:30.553 11157 11220 I jxcore-log: 
,03-31 10:13:30.553 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:30.553 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:30.553 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:30.558 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:30.558 11157 11220 I jxcore-log: 
,03-31 10:13:30.558 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:30.558 11157 11220 I jxcore-log: 
,03-31 10:13:30.563 11157 11220 I jxcore-log: ok 100 error should be null
03-31 10:13:30.563 11157 11220 I jxcore-log: 
,03-31 10:13:30.568 11157 11220 I jxcore-log: ok 101 error should be null
03-31 10:13:30.568 11157 11220 I jxcore-log: 
,03-31 10:13:30.573 11157 11220 I jxcore-log: # setup
03-31 10:13:30.573 11157 11220 I jxcore-log: 
,03-31 10:13:30.733 11157 11220 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-31 10:13:30.733 11157 11220 I jxcore-log: 
,03-31 10:13:32.043 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:32.043 11157 11220 I jxcore-log: 
,03-31 10:13:32.053 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 41009
03-31 10:13:32.053 11157 11220 I jxcore-log: 
,03-31 10:13:32.078 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 41009, start advertisements: true
,03-31 10:13:32.078 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:32.078 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 10:13:32.078 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:32.083 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:32.083 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:32.083 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:32.083 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:32.088  5920  5933 D BtGatt.GattService: registerClient() - UUID=02f63937-a780-48bd-94d1-c4ecd11df851
,03-31 10:13:32.128  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=02f63937-a780-48bd-94d1-c4ecd11df851, clientIf=6
,03-31 10:13:32.128 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:32.128  5920  5931 D BtGatt.GattService: start scan with filters
,03-31 10:13:32.143  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 24
,03-31 10:13:32.143 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:32.143 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:32.143 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:32.143 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:32.143 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:32.143  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:32.143  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:32.143  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:32.143 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:32.143 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:32.143 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:32.143 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:32.143 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:32.143 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:32.143 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:32.148  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 10:13:32.148  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:32.148  5920  6017 D BtGatt.GattService: registerClient() - UUID=72d81274-7a18-49b2-84e5-569810228d3e
03-31 10:13:32.148  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:32.148  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:32.148  5920  6014 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-31 10:13:32.148  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:32.148  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:32.148  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:32.148  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:13:32.153  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:32.153  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:32.153  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 10:13:32.153  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:32.193  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=72d81274-7a18-49b2-84e5-569810228d3e, clientIf=7
,03-31 10:13:32.193 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:32.258  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 20
,03-31 10:13:32.273  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:32.273  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:32.273  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:32.278  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:13:32.283  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:32.288  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:32.288  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:32.293  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:13:32.293  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 10:13:32.293  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:13:32.293 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:32.298 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:32.298 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:32.298 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:32.298 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 10:13:32.303 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:32.303 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:13:32.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-31 10:13:32.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:13:32.308 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:13:32.308 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:32.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:32.308 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:32.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:32.308 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:32.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:32.308 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:32.308 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:32.308 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:32.308 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:32.308 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:32.308 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:32.308 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:32.318 11157 11502 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 10:13:32.323 11157 11502 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:32.333 11157 11502 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]}
,03-31 10:13:32.333 11157 11502 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:13:32.333 11157 11502 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 10:13:32.333 11157 11502 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cbf9b0
03-31 10:13:32.333 11157 11502 D BluetoothSocket: channel: 6
,03-31 10:13:32.333 11157 11502 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:32.338 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:32.338 11157 11220 I jxcore-log: 
,03-31 10:13:32.338 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:32.338 11157 11220 I jxcore-log: 
,03-31 10:13:32.343 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:32.343 11157 11220 I jxcore-log: 
,03-31 10:13:32.348 11157 11220 I jxcore-log: ok 102 error should be null
03-31 10:13:32.348 11157 11220 I jxcore-log: 
,03-31 10:13:32.348 11157 11220 I jxcore-log: ok 103 error should be null
03-31 10:13:32.348 11157 11220 I jxcore-log: 
,03-31 10:13:32.358 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 41009, start advertisements: true
,03-31 10:13:32.358 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:32.358 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 10:13:32.358 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:32.358 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:32.373 11157 11220 I jxcore-log: ok 104 error should be null
03-31 10:13:32.373 11157 11220 I jxcore-log: 
,03-31 10:13:32.378 11157 11220 I jxcore-log: ok 105 error should be null
03-31 10:13:32.378 11157 11220 I jxcore-log: 
,03-31 10:13:32.383 11157 11220 I jxcore-log: # teardown
03-31 10:13:32.383 11157 11220 I jxcore-log: 
,03-31 10:13:33.158  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:33.173  5920  5920 D BtGatt.ScanManager: awakened up at time 242767
,03-31 10:13:33.183  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:33.188  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:33.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:33.188  5920  5987 D BtGatt.GattService: current time is 242783649819
03-31 10:13:33.188  5920  5987 D BtGatt.GattService: Batch record : [-64, -93, 80, -9, -120, 75, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -42, -10, -22, 53, 40, 78, 1, -128, -76, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 10:13:33.198  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:33.203  5920  5987 D ScanRecord: parseFromBytes,
,03-31 10:13:33.213  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 10:13:33.213  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 10:13:33.213  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 10:13:33.243  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 10:13:33.248  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:33.248  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:33.248  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=4E:28:35:EA:F6:D6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=242734111653}
03-31 10:13:33.248  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:33.248  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=4B:88:F7:50:A3:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=242734111653}
03-31 10:13:33.248  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:33.248  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
03-31 10:13:33.248 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:33.248 11157 11167 D ScanRecord: parseFromBytes
,03-31 10:13:33.253 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-31 10:13:33.258 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
,03-31 10:13:33.258 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 10:13:33.258 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-31 10:13:33.258  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.263  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 10:13:33.263 11157 11220 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 10:13:33.263 11157 11220 I jxcore-log: 
,03-31 10:13:33.268 11157 11220 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 10:13:33.268 11157 11220 I jxcore-log: 
,03-31 10:13:33.273  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 10:13:33.278 11157 11220 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-31 10:13:33.278 11157 11220 I jxcore-log: 
,03-31 10:13:33.278 11157 11220 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-31 10:13:33.278 11157 11220 I jxcore-log: 
,03-31 10:13:33.313  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.313  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.318  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.318  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.323  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.323  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.343  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:13:33.598 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:33.598 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:33.598 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 10:13:33.603 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:33.603 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 10:13:33.603 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2288f14f, channel: 6, state: LISTENING
,03-31 10:13:33.608 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2288f14f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cbf9b0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1fef00dcmSocket: android.net.LocalSocket@312e95e5 impl:android.net.LocalSocketImpl@369fc8ba fd:FileDescriptor[114]
,03-31 10:13:33.608 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@312e95e5 impl:android.net.LocalSocketImpl@369fc8ba fd:FileDescriptor[114]
,03-31 10:13:33.608 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:33.608 11157 11502 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:33.608 11157 11502 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:33.608 11157 11502 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-31 10:13:33.613 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:13:33.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:33.613 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:33.613 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:13:33.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:33.618 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:33.618 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:33.618 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:33.618 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:33.618  5920  5931 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:33.623  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:33.623  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 4
03-31 10:13:33.623  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:33.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:33.623  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:33.628  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 10:13:33.628  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:13:33.628  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:33.628  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:33.633  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:33.633  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:33.633  5920  5987 D BtGatt.GattService: current time is 243226974445
03-31 10:13:33.633  5920  5987 D BtGatt.GattService: Batch record : [-42, -10, -22, 53, 40, 78, 1, -128, -79, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -64, -93, 80, -9, -120, 75, 1, -128, -69, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-31 10:13:33.633  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:33.633  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:33.633  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:33.633  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:33.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 10:13:33.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 10:13:33.638 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-31 10:13:33.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-31 10:13:33.638 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:33.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-31 10:13:33.638 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:33.643  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:33.643  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:33.643  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:33.643  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 10:13:33.643  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:33.643  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:13:33.648  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:33.653 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:33.653 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:33.653 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:33.653 11157 11220 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:13:33.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-31 10:13:33.653 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:33.653 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:33.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:33.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:33.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:33.658 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:13:33.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:13:33.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:33.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:33.668 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:33.668 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:33.668 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:33.678 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:33.678 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:33.678 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:33.688 11157 11220 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:33.688 11157 11220 I jxcore-log: 
,03-31 10:13:33.688 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
,03-31 10:13:33.688 11157 11220 I jxcore-log: 
,03-31 10:13:33.693 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:33.693 11157 11220 I jxcore-log: 
,03-31 10:13:33.693 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:33.693 11157 11220 I jxcore-log: 
,03-31 10:13:33.698 11157 11220 I jxcore-log: ok 106 error should be null
03-31 10:13:33.698 11157 11220 I jxcore-log: 
,03-31 10:13:33.703 11157 11220 I jxcore-log: ok 107 error should be null
03-31 10:13:33.703 11157 11220 I jxcore-log: 
,03-31 10:13:33.708 11157 11220 I jxcore-log: # setup
03-31 10:13:33.708 11157 11220 I jxcore-log: 
,03-31 10:13:33.833 11157 11220 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-31 10:13:33.833 11157 11220 I jxcore-log: 
,03-31 10:13:34.083 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:34.083 11157 11220 I jxcore-log: 
,03-31 10:13:34.088 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 38703
03-31 10:13:34.088 11157 11220 I jxcore-log: 
,03-31 10:13:34.098 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.098 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.098 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.103 11157 11220 I jxcore-log: ok 108 error should be null
03-31 10:13:34.103 11157 11220 I jxcore-log: 
,03-31 10:13:34.103 11157 11220 I jxcore-log: ok 109 error should be null
03-31 10:13:34.103 11157 11220 I jxcore-log: 
,03-31 10:13:34.108 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.108 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.108 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.113 11157 11220 I jxcore-log: ok 110 error should be null
03-31 10:13:34.113 11157 11220 I jxcore-log: 
,03-31 10:13:34.113 11157 11220 I jxcore-log: ok 111 error should be null
03-31 10:13:34.113 11157 11220 I jxcore-log: 
,03-31 10:13:34.123 11157 11220 I jxcore-log: # teardown
03-31 10:13:34.123 11157 11220 I jxcore-log: 
,03-31 10:13:34.208 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:34.208 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:34.208 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.213 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:34.213 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:34.213 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.218 11157 11220 I jxcore-log: ok 112 error should be null
03-31 10:13:34.218 11157 11220 I jxcore-log: 
,03-31 10:13:34.223 11157 11220 I jxcore-log: ok 113 error should be null
03-31 10:13:34.223 11157 11220 I jxcore-log: 
,03-31 10:13:34.233 11157 11220 I jxcore-log: # setup
03-31 10:13:34.233 11157 11220 I jxcore-log: 
,03-31 10:13:34.318 11157 11220 I jxcore-log: # 30. #start should fail if called twice in a row
03-31 10:13:34.318 11157 11220 I jxcore-log: 
,03-31 10:13:34.533 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:34.533 11157 11220 I jxcore-log: 
,03-31 10:13:34.538 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 46896
03-31 10:13:34.538 11157 11220 I jxcore-log: 
,03-31 10:13:34.543 11157 11220 I jxcore-log: ok 114 first call should succeed
03-31 10:13:34.543 11157 11220 I jxcore-log: 
,03-31 10:13:34.543 11157 11220 I jxcore-log: ok 115 first call should succeed
03-31 10:13:34.543 11157 11220 I jxcore-log: 
,03-31 10:13:34.548 11157 11220 I jxcore-log: ok 116 specific error should be returned
03-31 10:13:34.548 11157 11220 I jxcore-log: 
,03-31 10:13:34.553 11157 11220 I jxcore-log: # teardown
03-31 10:13:34.553 11157 11220 I jxcore-log: 
,03-31 10:13:34.733 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:34.743 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:34.743 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.748 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:34.748 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:34.753 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:34.763 11157 11220 I jxcore-log: ok 117 error should be null
03-31 10:13:34.763 11157 11220 I jxcore-log: 
,03-31 10:13:34.773 11157 11220 I jxcore-log: ok 118 error should be null
03-31 10:13:34.773 11157 11220 I jxcore-log: 
,03-31 10:13:34.778 11157 11220 I jxcore-log: # setup
03-31 10:13:34.778 11157 11220 I jxcore-log: 
,03-31 10:13:34.918 11157 11220 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-31 10:13:34.918 11157 11220 I jxcore-log: 
,03-31 10:13:35.103 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:13:35.103 11157 11220 I jxcore-log: 
,03-31 10:13:35.108 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 50858
03-31 10:13:35.108 11157 11220 I jxcore-log: 
,03-31 10:13:35.118 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 41009, start advertisements: false
,03-31 10:13:35.123 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:35.123 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:35.123 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:35.123 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:35.123 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:35.128 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:35.128  5920  6017 D BtGatt.GattService: registerClient() - UUID=e4f69b5a-27ed-4fde-8b02-73fe1fc045b0
,03-31 10:13:35.173  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=e4f69b5a-27ed-4fde-8b02-73fe1fc045b0, clientIf=6
,03-31 10:13:35.173 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:35.173  5920  5933 D BtGatt.GattService: start scan with filters
,03-31 10:13:35.188  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 25
,03-31 10:13:35.188 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:35.188 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:35.188 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 10:13:35.188 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:35.188  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:35.188  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:35.188 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:35.188  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:35.188 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:35.188 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:35.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:35.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:13:35.193 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:35.193 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:35.193 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:35.193  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-31 10:13:35.193  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:35.193 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:35.193  5920  6014 D BtGatt.ScanManager: allow scan with filters
,03-31 10:13:35.193  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:35.193  5920  6014 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6,
03-31 10:13:35.193  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:35.193  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:35.193  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:35.193  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:35.198  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:35.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:35.198 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:35.198 11157 11220 I jxcore-log: 
03-31 10:13:35.198  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:35.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:35.203 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:35.203 11157 11220 I jxcore-log: 
,03-31 10:13:35.218 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 50858, start advertisements: true
,03-31 10:13:35.223 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:35.223 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:35.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:35.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:35.223 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 10:13:35.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:35.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:35.223 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:35.223 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:35.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:35.228 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:35.233  5920  5933 D BtGatt.GattService: registerClient() - UUID=4cb9ddf3-22b3-4ce9-b993-c293f2a3eb37
,03-31 10:13:35.273  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=4cb9ddf3-22b3-4ce9-b993-c293f2a3eb37, clientIf=7
,03-31 10:13:35.273 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:35.293  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 21
,03-31 10:13:35.293  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:35.293  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:35.293  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:35.298  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:13:35.298  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:35.308  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:35.308  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:35.308  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:13:35.313  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 10:13:35.313  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:13:35.313 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:35.313 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-31 10:13:35.313 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:35.313 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 10:13:35.313 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:35.313 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:35.313 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 10:13:35.318 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:35.318 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:13:35.318 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-31 10:13:35.323 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:35.323 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:13:35.323 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:35.323 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:35.323 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:13:35.323 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:35.323 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:35.323 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:35.323 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:35.323 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:35.333 11157 11540 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 10:13:35.333 11157 11540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:35.338 11157 11540 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[114]},
03-31 10:13:35.338 11157 11540 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 10:13:35.338 11157 11540 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 10:13:35.338 11157 11540 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1bf1b686
,03-31 10:13:35.338 11157 11540 D BluetoothSocket: channel: 6,
,03-31 10:13:35.338 11157 11540 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:35.348 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:35.348 11157 11220 I jxcore-log: 
,03-31 10:13:35.358 11157 11220 I jxcore-log: ok 119 called only once
03-31 10:13:35.358 11157 11220 I jxcore-log: 
,03-31 10:13:35.358 11157 11220 I jxcore-log: ok 120 discovery state matches
03-31 10:13:35.358 11157 11220 I jxcore-log: 
,03-31 10:13:35.358 11157 11220 I jxcore-log: ok 121 advertising state matches
03-31 10:13:35.358 11157 11220 I jxcore-log: 
,03-31 10:13:35.368 11157 11220 I jxcore-log: # teardown
03-31 10:13:35.368 11157 11220 I jxcore-log: 
,03-31 10:13:35.713 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:35.713 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 10:13:35.713 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 10:13:35.718 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:13:35.718 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-31 10:13:35.718 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d2bbb47, channel: 6, state: LISTENING
,03-31 10:13:35.718 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d2bbb47, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1bf1b686, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e988f74mSocket: android.net.LocalSocket@a629c9d impl:android.net.LocalSocketImpl@3622b512 fd:FileDescriptor[114]
,03-31 10:13:35.718 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a629c9d impl:android.net.LocalSocketImpl@3622b512 fd:FileDescriptor[114]
,03-31 10:13:35.723 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:35.723 11157 11540 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:35.723 11157 11540 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:35.723 11157 11540 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:35.723 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:13:35.723 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:13:35.723 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:35.723 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:13:35.723 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:35.723 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:35.723 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:35.723 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:35.723 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:35.728  5920  5931 D BtGatt.GattService: stopScan() - queue size =1,
,03-31 10:13:35.733  5920  6014 D BtGatt.ScanManager: filter size is 1,
,03-31 10:13:35.733  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 5
,03-31 10:13:35.733  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 10:13:35.733  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:13:35.733  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:35.733  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-31 10:13:35.733  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 10:13:35.733  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-31 10:13:35.738  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:35.738  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:35.738  5920  5987 D BtGatt.GattService: current time is 245331815820,
03-31 10:13:35.738  5920  5987 D BtGatt.GattService: Batch record : [-14, -36, 53, 107, 119, 113, 1, -128, -76, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 85, -73, 47, 36, -30, 72, 1, -128, -68, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-31 10:13:35.738  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-31 10:13:35.738  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:35.738  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:35.738  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:35.743  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:35.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:35.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:35.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:35.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 10:13:35.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:35.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:35.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:35.748  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:35.748  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 10:13:35.748  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:35.748  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:13:35.753  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:35.753  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:13:35.753  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:13:35.753 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:35.758 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-31 10:13:35.758 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-31 10:13:35.758 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:35.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:35.758 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:35.758 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:35.758 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:35.758 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:35.758 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:13:35.763 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-31 10:13:35.768 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:35.768 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:35.768 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:35.773 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:35.773 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:35.773 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:35.773 11157 11220 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.773 11157 11220 I jxcore-log: 
03-31 10:13:35.783 11157 11220 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:35.783 11157 11220 I jxcore-log: 
03-31 10:13:35.788 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:35.788 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:35.788 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:35.793 11157 11220 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-31 10:13:35.793 11157 11220 I jxcore-log: 
,03-31 10:13:35.793 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:35.793 11157 11220 I jxcore-log: 
03-31 10:13:35.798 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.798 11157 11220 I jxcore-log: 
,03-31 10:13:35.798 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:35.798 11157 11220 I jxcore-log: 
,03-31 10:13:35.803 11157 11220 I jxcore-log: ok 122 error should be null
03-31 10:13:35.803 11157 11220 I jxcore-log: 
,03-31 10:13:35.803 11157 11220 I jxcore-log: ok 123 error should be null
03-31 10:13:35.803 11157 11220 I jxcore-log: 
,03-31 10:13:35.808 11157 11220 I jxcore-log: # setup
03-31 10:13:35.808 11157 11220 I jxcore-log: 
,03-31 10:13:35.958 11157 11220 I jxcore-log: # 32. does not send duplicate availability changes
03-31 10:13:35.958 11157 11220 I jxcore-log: 
,03-31 10:13:36.223  3420  3748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:13:36.223  3420  3748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:36.223  3420  3748 D BatteryService: online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
03-31 10:13:36.223  3420  3748 D BatteryService: stay LED for fully charged
03-31 10:13:36.223  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:13:36.228  3420  3420 I MotionRecognitionService: Plugged
,03-31 10:13:36.228  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:13:36.228  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:13:36.228  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:36.233  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:13:36.233  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:36.238  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:36.248  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:13:36.248  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:36.263  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:36.263  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:36.263  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:36.263  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:36.298  3420  3585 I PowerManagerService: [PWL] Off : 180s ago
,03-31 10:13:36.793  3420  6131 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:12), CUR = 58, LCD = 0
,03-31 10:13:36.958 11157 11220 I jxcore-log: ok 124 should be called once
03-31 10:13:36.958 11157 11220 I jxcore-log: 
,03-31 10:13:36.963 11157 11220 I jxcore-log: ok 125 should not have been called more than once
03-31 10:13:36.963 11157 11220 I jxcore-log: 
,03-31 10:13:36.968 11157 11220 I jxcore-log: # teardown
03-31 10:13:36.968 11157 11220 I jxcore-log: 
,03-31 10:13:37.168 11157 11220 I jxcore-log: ok 126 error should be null
03-31 10:13:37.168 11157 11220 I jxcore-log: 
,03-31 10:13:37.168 11157 11220 I jxcore-log: ok 127 error should be null
03-31 10:13:37.168 11157 11220 I jxcore-log: 
,03-31 10:13:37.178 11157 11220 I jxcore-log: # setup
03-31 10:13:37.178 11157 11220 I jxcore-log: 
,03-31 10:13:37.413 11157 11220 I jxcore-log: # 33. can get the network status
03-31 10:13:37.413 11157 11220 I jxcore-log: 
,03-31 10:13:37.528 11157 11220 I jxcore-log: ok 128 network status should have certain non-empty properties
03-31 10:13:37.528 11157 11220 I jxcore-log: 
,03-31 10:13:37.538 11157 11220 I jxcore-log: # teardown
03-31 10:13:37.538 11157 11220 I jxcore-log: 
,03-31 10:13:37.848 11157 11220 I jxcore-log: ok 129 error should be null
03-31 10:13:37.848 11157 11220 I jxcore-log: 
,03-31 10:13:37.853 11157 11220 I jxcore-log: ok 130 error should be null
03-31 10:13:37.853 11157 11220 I jxcore-log: 
,03-31 10:13:37.863 11157 11220 I jxcore-log: # setup
03-31 10:13:37.863 11157 11220 I jxcore-log: 
,03-31 10:13:38.028 11157 11220 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-31 10:13:38.028 11157 11220 I jxcore-log: 
,03-31 10:13:38.258 11157 11220 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-31 10:13:38.258 11157 11220 I jxcore-log: 
,03-31 10:13:38.288 11157 11220 I jxcore-log: ok 131 host address should match
03-31 10:13:38.288 11157 11220 I jxcore-log: 
,03-31 10:13:38.288 11157 11220 I jxcore-log: ok 132 port should match
03-31 10:13:38.288 11157 11220 I jxcore-log: 
,03-31 10:13:40.258 11157 11220 I jxcore-log: ok 133 host address should be null
03-31 10:13:40.258 11157 11220 I jxcore-log: 
,03-31 10:13:40.258 11157 11220 I jxcore-log: ok 134 port should should be null
03-31 10:13:40.258 11157 11220 I jxcore-log: 
,03-31 10:13:40.273 11157 11220 I jxcore-log: # teardown
03-31 10:13:40.273 11157 11220 I jxcore-log: 
,03-31 10:13:40.398 11157 11220 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-31 10:13:40.398 11157 11220 I jxcore-log: 
,03-31 10:13:40.408 11157 11220 I jxcore-log: ok 135 error should be null
03-31 10:13:40.408 11157 11220 I jxcore-log: 
,03-31 10:13:40.408 11157 11220 I jxcore-log: ok 136 error should be null
03-31 10:13:40.408 11157 11220 I jxcore-log: 
,03-31 10:13:40.413 11157 11220 I jxcore-log: # setup
03-31 10:13:40.413 11157 11220 I jxcore-log: 
,03-31 10:13:40.718  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:13:40.868 11157 11220 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-31 10:13:40.868 11157 11220 I jxcore-log: 
,03-31 10:13:41.118 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 50858, start advertisements: false
,03-31 10:13:41.118 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:41.118 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:41.123 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:41.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:41.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:41.128 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:41.133  5920  5933 D BtGatt.GattService: registerClient() - UUID=2cdf42e0-b974-43bc-84b1-f79096284cb6
,03-31 10:13:41.178  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=2cdf42e0-b974-43bc-84b1-f79096284cb6, clientIf=6
03-31 10:13:41.178 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:41.178  5920  5931 D BtGatt.GattService: start scan with filters
,03-31 10:13:41.188  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 26
,03-31 10:13:41.188  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:41.188  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:41.188  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:41.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:41.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:41.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:41.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:41.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:41.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:41.193 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:41.198  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 10:13:41.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:41.198  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:41.198  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 10:13:41.198  5920  6014 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-31 10:13:41.203  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 10:13:41.203  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:13:41.203  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:41.203  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:41.203  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:41.203  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:41.208  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:41.208  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:41.213 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:41.213 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:41.213 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:41.213 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:41.213 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:41.213 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:41.218 11157 11220 I jxcore-log: ok 137 Can call startListeningForAdvertisements without error,
03-31 10:13:41.218 11157 11220 I jxcore-log: 
03-31 10:13:41.218 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:13:41.218 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:41.218 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:41.218 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:41.223  5920  6017 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:13:41.223  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:41.223  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 6
03-31 10:13:41.223  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:41.228  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:41.228  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:41.228  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:41.228 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:41.228 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:41.228 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:41.228 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:13:41.228 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:13:41.228 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:13:41.228 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:41.228 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:41.228 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:41.228  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:13:41.228  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:41.228  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:41.228 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:41.228 11157 11220 I jxcore-log: 
,03-31 10:13:41.233  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:41.233  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:41.233 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:41.233 11157 11220 I jxcore-log: 
,03-31 10:13:41.233 11157 11220 I jxcore-log: ok 138 Can call stopListeningForAdvertisements without error
03-31 10:13:41.233 11157 11220 I jxcore-log: 
,03-31 10:13:41.238 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:41.238 11157 11220 I jxcore-log: 
,03-31 10:13:41.243 11157 11220 I jxcore-log: # teardown
03-31 10:13:41.243 11157 11220 I jxcore-log: 
,03-31 10:13:41.428 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:41.428 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:13:41.428 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:41.438 11157 11220 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:41.438 11157 11220 I jxcore-log: 
,03-31 10:13:41.438 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:41.443 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:41.443 11157 11220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 10:13:41.443 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:41.443 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:41.443 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:41.443 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:41.443 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:13:41.448 11157 11220 D BluetoothLeScanner: could not find callback wrapper
,03-31 10:13:41.448 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:41.448 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-31 10:13:41.453 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 10:13:41.453 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:41.453 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-31 10:13:41.453 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:41.458 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 10:13:41.458 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:41.458 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:41.468 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-31 10:13:41.473 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:41.473 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:13:41.478 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:41.478 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:41.483 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:41.483 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:41.483 11157 11220 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:41.483 11157 11220 I jxcore-log: 
,03-31 10:13:41.493 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:41.493 11157 11220 I jxcore-log: 
,03-31 10:13:41.493 11157 11220 I jxcore-log: # setup
03-31 10:13:41.493 11157 11220 I jxcore-log: 
,03-31 10:13:41.808 11157 11220 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-31 10:13:41.808 11157 11220 I jxcore-log: 
,03-31 10:13:42.088 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 50858, start advertisements: false
,03-31 10:13:42.088 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:42.088 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:42.093 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:13:42.098 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:42.098 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:42.098 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:42.103  5920  5931 D BtGatt.GattService: registerClient() - UUID=77046c13-1da7-4211-926b-dacf2c4fc9d5
,03-31 10:13:42.148  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=77046c13-1da7-4211-926b-dacf2c4fc9d5, clientIf=6
03-31 10:13:42.148 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:42.153  5920  5933 D BtGatt.GattService: start scan with filters
,03-31 10:13:42.178  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27
,03-31 10:13:42.178  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:42.178  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:42.178  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:42.183  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:42.183  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:42.183  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:42.183  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:42.183  5920  6014 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-31 10:13:42.188  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:42.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:42.188  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:42.188  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:13:42.198  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:42.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:42.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:42.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:42.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:42.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:42.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:42.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:13:42.198 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:42.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:42.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-31 10:13:42.208  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 10:13:42.208  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:42.213 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:13:42.213 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:42.213 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:42.213 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:42.213 11157 11220 I jxcore-log: ok 141 Can call startListeningForAdvertisements without error
03-31 10:13:42.213 11157 11220 I jxcore-log: 
,03-31 10:13:42.218 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 50858, start advertisements: false
,03-31 10:13:42.223 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:42.223 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:13:42.223 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:42.223 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:42.223 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:42.223 11157 11220 I jxcore-log: 
,03-31 10:13:42.228 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:42.228 11157 11220 I jxcore-log: 
,03-31 10:13:42.228 11157 11220 I jxcore-log: ok 142 Can call startListeningForAdvertisements twice without error
03-31 10:13:42.228 11157 11220 I jxcore-log: 
,03-31 10:13:42.238 11157 11220 I jxcore-log: # teardown
03-31 10:13:42.238 11157 11220 I jxcore-log: 
,03-31 10:13:42.613 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:42.613 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:42.618 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:42.618 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:42.618  5920  6017 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:42.623  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:42.623  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 7
03-31 10:13:42.623  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:42.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:42.623  5920  6014 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 10:13:42.628  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 10:13:42.628  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:42.628  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:42.628  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:42.633  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:42.633  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:42.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-31 10:13:42.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:42.638 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:42.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:13:42.638 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-31 10:13:42.638 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:42.638 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-31 10:13:42.638 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-31 10:13:42.638 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:42.643 11157 11220 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:42.643 11157 11220 I jxcore-log: 
,03-31 10:13:42.643 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:42.648 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:42.648 11157 11220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 10:13:42.648 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:13:42.648 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:42.648 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:42.648 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:13:42.648 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:13:42.648 11157 11220 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:42.648 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:42.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:42.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:42.653 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:42.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:13:42.653 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:42.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:42.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:42.653 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:42.663 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:42.668 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:42.668 11157 11220 I jxcore-log: 
,03-31 10:13:42.673 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:42.673 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:13:42.678 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:42.678 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:42.678 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:42.683 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:42.683 11157 11220 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:42.683 11157 11220 I jxcore-log: 
,03-31 10:13:42.693 11157 11220 I jxcore-log: # setup
03-31 10:13:42.693 11157 11220 I jxcore-log: 
,03-31 10:13:42.693 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:42.693 11157 11220 I jxcore-log: 
,03-31 10:13:43.063 11157 11220 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-31 10:13:43.063 11157 11220 I jxcore-log: 
,03-31 10:13:43.118  3420  3863 E Watchdog: !@Sync 8 [03-31 10:13:43.125]
,03-31 10:13:44.323 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 10:13:44.323 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:44.323 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:44.323 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:44.328 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:44.328 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:44.328 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:44.328 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:44.333  5920  6017 D BtGatt.GattService: registerClient() - UUID=c2929f44-f526-4f7e-883a-70950d73943d
,03-31 10:13:44.378  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=c2929f44-f526-4f7e-883a-70950d73943d, clientIf=6
,03-31 10:13:44.378 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:44.378  5920  5933 D BtGatt.GattService: start scan with filters
,03-31 10:13:44.393  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
,03-31 10:13:44.393 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:44.393 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:44.393 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:44.393  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:44.393 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:44.393  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:44.393 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:44.393  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:44.393 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:44.393 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 10:13:44.393 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:44.393 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:44.393 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:44.393 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:44.393 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:44.398  5920  6017 D BtGatt.GattService: registerClient() - UUID=bebc8ccf-faeb-4a4d-9b0d-54623b46dd35
,03-31 10:13:44.398  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:44.398  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:44.398  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:44.398  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:44.398  5920  6014 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-31 10:13:44.398  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 10:13:44.398  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:44.398  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:44.398  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:13:44.403  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 10:13:44.403  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:44.403  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-31 10:13:44.403  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:44.438  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=bebc8ccf-faeb-4a4d-9b0d-54623b46dd35, clientIf=7
,03-31 10:13:44.438 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:44.458  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 22
,03-31 10:13:44.458  5920  6013 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:44.458  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:44.458  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:44.458  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:13:44.458  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:44.463  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:44.463  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:44.463  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 10:13:44.463  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 10:13:44.463  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:13:44.468 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:44.468 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:44.473 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:44.473 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:44.473 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:44.473 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:44.473 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:13:44.473 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:44.478 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:44.478 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:13:44.478 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:44.478 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:44.478 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:44.478 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:44.478 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:44.478 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:44.478 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 10:13:44.478 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:44.478 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:44.478 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:44.478 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:44.478 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:44.478 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:44.478 11157 11617 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:13:44.478 11157 11617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:44.483 11157 11617 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-31 10:13:44.483 11157 11617 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:13:44.483 11157 11617 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:13:44.483 11157 11617 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33e1f9f8
03-31 10:13:44.483 11157 11617 D BluetoothSocket: channel: 6
03-31 10:13:44.483 11157 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:44.483 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:44.483 11157 11220 I jxcore-log: 
,03-31 10:13:44.488 11157 11220 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListening without error
03-31 10:13:44.488 11157 11220 I jxcore-log: 
,03-31 10:13:44.488 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:44.488 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:44.488 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:44.488 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:44.488 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:44.488 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f312ed1, channel: 6, state: LISTENING
03-31 10:13:44.488 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f312ed1, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33e1f9f8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2adacd36mSocket: android.net.LocalSocket@17740437 impl:android.net.LocalSocketImpl@f38bda4 fd:FileDescriptor[92]
03-31 10:13:44.488 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17740437 impl:android.net.LocalSocketImpl@f38bda4 fd:FileDescriptor[92]
03-31 10:13:44.488 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:44.488 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:44.488 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:44.488 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:44.488 11157 11617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:44.488 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:44.488 11157 11617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:44.488 11157 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:44.488 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:44.488 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:44.493  5920  5933 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:44.493  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:44.493  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 8
03-31 10:13:44.493  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:13:44.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:44.493  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:44.493  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:44.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:44.493  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:44.493 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:44.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:13:44.493 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:44.493 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:13:44.493 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:13:44.498  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:44.498  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:13:44.498  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:44.498  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:44.498  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:44.498  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:44.498  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:13:44.498  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:44.498  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:44.498  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:44.498  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:13:44.503  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:44.503 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-31 10:13:44.503 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:44.503 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:44.503 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:44.503 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:44.503 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:44.503 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:44.503 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:44.503 11157 11220 I jxcore-log: 
03-31 10:13:44.508 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:44.508 11157 11220 I jxcore-log: 
,03-31 10:13:44.508 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:44.513 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:44.513 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:44.513 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:44.513 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:44.513 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:44.518 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:13:44.518 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:44.518 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:44.518 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:44.518 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:44.518 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:13:44.518 11157 11220 I jxcore-log: ok 146 Can call stopAdvertisingAndListening without error
03-31 10:13:44.518 11157 11220 I jxcore-log: 
,03-31 10:13:44.523 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:44.523 11157 11220 I jxcore-log: 
,03-31 10:13:44.528 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:44.528 11157 11220 I jxcore-log: 
,03-31 10:13:44.528 11157 11220 I jxcore-log: # teardown
03-31 10:13:44.528 11157 11220 I jxcore-log: 
,03-31 10:13:44.533 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:44.533 11157 11220 I jxcore-log: 
,03-31 10:13:44.703 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,03-31 10:13:44.708 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-31 10:13:44.713 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:44.728 11157 11220 I jxcore-log: ok 147 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:44.728 11157 11220 I jxcore-log: 
,03-31 10:13:44.733 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:44.738 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:13:44.738 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-31 10:13:44.748 11157 11220 I jxcore-log: ok 148 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:44.748 11157 11220 I jxcore-log: 
,03-31 10:13:44.763 11157 11220 I jxcore-log: # setup
03-31 10:13:44.763 11157 11220 I jxcore-log: 
,03-31 10:13:45.053 11157 11220 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-31 10:13:45.053 11157 11220 I jxcore-log: 
,03-31 10:13:45.413 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 10:13:45.418 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:45.418 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:45.418 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:45.423 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:45.423 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:45.423 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:45.423 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:45.428  5920  5931 D BtGatt.GattService: registerClient() - UUID=261c3872-7f67-499b-9840-4ffa224ada5e
,03-31 10:13:45.473  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=261c3872-7f67-499b-9840-4ffa224ada5e, clientIf=6
03-31 10:13:45.473 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:45.483  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:45.503  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,03-31 10:13:45.503  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:45.503  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:45.503  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:45.513  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:45.513  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:45.513  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:45.513  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:45.513  5920  6014 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-31 10:13:45.513  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:45.513  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:45.513  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:45.513  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:13:45.518  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:45.518  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:45.523  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:45.523  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:45.528 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:45.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:45.528 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:45.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:45.528 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:45.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:45.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:45.528 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:45.528 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:45.528 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:45.528 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:45.528 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:45.533  5920  5933 D BtGatt.GattService: registerClient() - UUID=08242375-8153-4283-8c2d-d3c05d7ef758
,03-31 10:13:45.573  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=08242375-8153-4283-8c2d-d3c05d7ef758, clientIf=7
,03-31 10:13:45.573 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:45.588  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 23
03-31 10:13:45.588  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:45.588  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:45.588  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:45.588  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:13:45.588  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:45.593  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:45.593  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:45.598  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 10:13:45.598  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:13:45.598  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:13:45.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:45.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:45.603 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:45.603 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:45.603 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:45.603 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:45.603 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:13:45.603 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:45.603 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:45.603 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-31 10:13:45.603 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:45.603 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:13:45.603 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:45.608 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:45.608 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:45.608 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-31 10:13:45.608 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:45.608 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:45.608 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:45.608 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:45.608 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:45.608 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:45.608 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:13:45.608 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:45.608 11157 11220 I jxcore-log: 
03-31 10:13:45.608 11157 11632 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:13:45.608 11157 11632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:45.613 11157 11220 I jxcore-log: ok 149 Can call startUpdateAdvertisingAndListening without error
03-31 10:13:45.613 11157 11220 I jxcore-log: 
,03-31 10:13:45.613 11157 11632 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]},
03-31 10:13:45.613 11157 11632 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:13:45.613 11157 11632 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:13:45.613 11157 11632 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29161010
03-31 10:13:45.613 11157 11632 D BluetoothSocket: channel: 6
,03-31 10:13:45.613 11157 11632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:45.618 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
03-31 10:13:45.618 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:45.618 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:13:45.618 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:45.618 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:45.618 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:45.618 11157 11220 I jxcore-log: 
,03-31 10:13:45.623 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:45.623 11157 11220 I jxcore-log: 
,03-31 10:13:45.623 11157 11220 I jxcore-log: ok 150 Can call startUpdateAdvertisingAndListening twice without error
03-31 10:13:45.623 11157 11220 I jxcore-log: 
,03-31 10:13:45.633 11157 11220 I jxcore-log: # teardown
03-31 10:13:45.633 11157 11220 I jxcore-log: 
,03-31 10:13:46.243 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:46.243 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:46.248 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-31 10:13:46.248 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:46.248  5920  5931 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:46.248  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:46.248  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 9
,03-31 10:13:46.253  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:46.253  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.253  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:46.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:46.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:13:46.253 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:46.253  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:46.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-31 10:13:46.253 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:46.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:46.253 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:13:46.253 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:46.253 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:46.258  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:13:46.258  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.258  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:46.258  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:46.258  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.258  5920  5987 D BtGatt.GattService: current time is 255854546154
03-31 10:13:46.258  5920  5987 D BtGatt.GattService: Batch record : [-106, -94, -6, -48, 62, 98, 1, -128, -58, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -29, -15, -79, 31, 67, 119, 1, -128, -70, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-31 10:13:46.258  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:46.258  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:46.263  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:46.263  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:46.263  3420  3574 W ProcessCpuTracker: Skipping unknown process pid 11635
,03-31 10:13:46.263 11157 11220 I jxcore-log: ok 151 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:46.263 11157 11220 I jxcore-log: 
,03-31 10:13:46.263 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:13:46.263 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:46.263 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:13:46.263 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:46.263 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:46.263 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33a9e709, channel: 6, state: LISTENING
03-31 10:13:46.263 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33a9e709, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29161010, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3db24d0emSocket: android.net.LocalSocket@3f39432f impl:android.net.LocalSocketImpl@3341d3c fd:FileDescriptor[92]
,03-31 10:13:46.263 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f39432f impl:android.net.LocalSocketImpl@3341d3c fd:FileDescriptor[92]
03-31 10:13:46.263 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:46.263 11157 11632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:46.263 11157 11632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:46.263 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:46.263 11157 11632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:46.263 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:46.263 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:13:46.263 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:46.263 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:46.263 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:46.263 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:13:46.268 11157 11220 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:46.268 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:46.268 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:13:46.268  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:46.268  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:46.268  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:13:46.268  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 10:13:46.273  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 10:13:46.273  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:13:46.273  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:46.273 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:46.273 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 10:13:46.273 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:46.273 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:46.273 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:13:46.273 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:46.273 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:46.278 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:46.278 11157 11220 I jxcore-log: 
,03-31 10:13:46.278 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:46.283 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:46.288 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:46.288 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:46.288 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:13:46.288 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:46.288 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:46.288 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:46.288 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:46.288 11157 11220 I jxcore-log: ok 152 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:46.288 11157 11220 I jxcore-log: 
,03-31 10:13:46.298 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:46.298 11157 11220 I jxcore-log: 
,03-31 10:13:46.298 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:46.298 11157 11220 I jxcore-log: 
,03-31 10:13:46.313 11157 11220 I jxcore-log: # setup
03-31 10:13:46.313 11157 11220 I jxcore-log: 
,03-31 10:13:46.373  3420  4008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:13:46.373  2891  4811 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
03-31 10:13:46.373  3420  4008 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:46.373  3420  4008 D BatteryService: online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
03-31 10:13:46.373  3420  4008 D BatteryService: stay LED for fully charged
03-31 10:13:46.373  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:13:46.378  3420  3420 I MotionRecognitionService: Plugged
03-31 10:13:46.378  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:13:46.378  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:13:46.378  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:46.378  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:46.378  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:46.378  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:46.383  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:46.388  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:13:46.388  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:46.398  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:46.403  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:46.403  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:46.578 11157 11220 I jxcore-log: # 39. peerAvailabilityChange is called
03-31 10:13:46.578 11157 11220 I jxcore-log: 
,03-31 10:13:46.738 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-31 10:13:46.738 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:46.738 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 10:13:46.738 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:46.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:46.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:46.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:46.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:46.753  5920  5931 D BtGatt.GattService: registerClient() - UUID=9d8acce2-79e1-4bd3-a544-fa8d335ad6b8
,03-31 10:13:46.793  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=9d8acce2-79e1-4bd3-a544-fa8d335ad6b8, clientIf=6
,03-31 10:13:46.793 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:46.793  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:46.808  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,03-31 10:13:46.808 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:46.808 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:46.808 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:46.808 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:46.808 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:46.808  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:46.808 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:46.808  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:46.808  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:46.808 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:46.808 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:46.808 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:46.808 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:46.808 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:13:46.808 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:13:46.813  5920  5933 D BtGatt.GattService: registerClient() - UUID=9d0fd609-4986-4381-8f92-3ffc2ccbd919
03-31 10:13:46.813  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:46.813  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.813  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:46.813  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:46.813  5920  6014 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-31 10:13:46.813  3420  6131 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:12), CUR = 57, LCD = 0
03-31 10:13:46.813  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:46.813  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.813  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:46.813  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:46.818  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:46.818  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:46.818  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:46.818  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:46.853  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=9d0fd609-4986-4381-8f92-3ffc2ccbd919, clientIf=7
,03-31 10:13:46.853 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:46.878  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 24
,03-31 10:13:46.878  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:46.878  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:46.878  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:46.883  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:13:46.883  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:46.888  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:46.893  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:46.893  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 10:13:46.893  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:13:46.893  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:13:46.893 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:46.893 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:13:46.903 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-31 10:13:46.903 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:46.903 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:13:46.903 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:46.903 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-31 10:13:46.903 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-31 10:13:46.903 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:13:46.903 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-31 10:13:46.903 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK,
03-31 10:13:46.903 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
,03-31 10:13:46.908 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:46.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-31 10:13:46.908 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:46.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:46.908 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:46.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:46.908 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:46.908 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 10:13:46.908 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:46.908 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:46.908 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:46.908 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:46.908 11157 11220 I jxcore-log: 
03-31 10:13:46.923 11157 11220 I jxcore-log: ok 153 Can call startUpdateAdvertisingAndListeningwithout error
03-31 10:13:46.923 11157 11220 I jxcore-log: 
,03-31 10:13:46.933 11157 11655 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:13:46.933 11157 11655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:46.938 11157 11655 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-31 10:13:46.938 11157 11655 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:13:46.938 11157 11655 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:13:46.938 11157 11655 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec3d128
03-31 10:13:46.938 11157 11655 D BluetoothSocket: channel: 6
03-31 10:13:46.938 11157 11655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:46.943 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-31 10:13:46.943 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:46.943 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-31 10:13:46.943 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:13:46.943 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:46.948 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:46.948 11157 11220 I jxcore-log: 
,03-31 10:13:46.948 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:46.948 11157 11220 I jxcore-log: 
,03-31 10:13:46.953 11157 11220 I jxcore-log: ok 154 Can call startListeningForAdvertisements without error
03-31 10:13:46.953 11157 11220 I jxcore-log: 
,03-31 10:13:47.818  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:47.833  5920  5920 D BtGatt.ScanManager: awakened up at time 257427
,03-31 10:13:47.838  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:47.848  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: current time is 257443487613
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: Batch record : [-10, -82, -109, -51, -89, 77, 1, -128, -55, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -56, 40, -2, 24, 117, 119, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:47.848  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:47.848  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=77:75:18:FE:28:C8, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=257393710988}
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=4D:A7:CD:93:AE:F6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=257443710988}
03-31 10:13:47.848  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:47.853 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:47.853 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:47.853 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 10:13:47.853 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-31 10:13:47.853 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-31 10:13:47.853 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
,03-31 10:13:47.863 11157 11220 I jxcore-log: ok 155 peers must be an array,
03-31 10:13:47.863 11157 11220 I jxcore-log: 
03-31 10:13:47.863 11157 11220 I jxcore-log: ok 156 peers must not be zero-length
03-31 10:13:47.863 11157 11220 I jxcore-log: 
03-31 10:13:47.863 11157 11220 I jxcore-log: ok 157 peer must have peerIdentifier
03-31 10:13:47.863 11157 11220 I jxcore-log: 
,03-31 10:13:47.863 11157 11220 I jxcore-log: ok 158 peerIdentifier must be a string
03-31 10:13:47.863 11157 11220 I jxcore-log: 
,03-31 10:13:47.873 11157 11220 I jxcore-log: ok 159 peer must have peerAvailable
03-31 10:13:47.873 11157 11220 I jxcore-log: 
,03-31 10:13:47.878 11157 11220 I jxcore-log: ok 160 peer must have pleaseConnect
03-31 10:13:47.878 11157 11220 I jxcore-log: 
,03-31 10:13:47.888 11157 11220 I jxcore-log: # teardown
03-31 10:13:47.888 11157 11220 I jxcore-log: 
,03-31 10:13:48.198 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:13:48.198 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-31 10:13:48.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:13:48.203 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:13:48.203  5920  6017 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:48.203  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:48.203  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 10
03-31 10:13:48.208  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:48.208  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:48.208  5920  6014 D BtGatt.ScanManager: stopping BLe Batch,
,03-31 10:13:48.213  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 10:13:48.213  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:48.213  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:48.213  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:48.218  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:48.218  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:48.218  5920  5987 D BtGatt.GattService: current time is 257811353155
03-31 10:13:48.218  5920  5987 D BtGatt.GattService: Batch record : [-56, 40, -2, 24, 117, 119, 1, -128, -76, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -10, -82, -109, -51, -89, 77, 1, -128, -61, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:48.218  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:48.218  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:48.218  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:48.218  5920  5987 D ScanRecord: parseFromBytes,
03-31 10:13:48.223 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:48.223 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:48.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:13:48.223 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-31 10:13:48.223 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:13:48.223 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 10:13:48.223 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-31 10:13:48.228 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:13:48.228 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:13:48.228 11157 11220 I jxcore-log: ok 161 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:13:48.228 11157 11220 I jxcore-log: 
,03-31 10:13:48.233 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:13:48.233 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:13:48.233 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-31 10:13:48.233 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:13:48.233 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:13:48.233 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15986927, channel: 6, state: LISTENING
,03-31 10:13:48.233 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15986927, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec3d128, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d18d7d4mSocket: android.net.LocalSocket@374ead7d impl:android.net.LocalSocketImpl@310a2472 fd:FileDescriptor[92]
03-31 10:13:48.233 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@374ead7d impl:android.net.LocalSocketImpl@310a2472 fd:FileDescriptor[92]
,03-31 10:13:48.238 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:48.238 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:13:48.238 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:13:48.238 11157 11655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:13:48.238 11157 11655 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:13:48.238 11157 11655 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:13:48.238 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:13:48.238 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:13:48.238 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:13:48.238 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:13:48.238 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-31 10:13:48.243 11157 11220 D BluetoothLeScanner: could not find callback wrapper
03-31 10:13:48.243 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:48.243 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:13:48.243  5920  6013 D BtGatt.AdvertiseManager: message : 1
,03-31 10:13:48.243  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:48.243  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:13:48.243  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 10:13:48.248  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:48.248  5920  5987 D BtGatt.GattService: Client app is not null!
,03-31 10:13:48.248  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 10:13:48.248 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:48.248 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:48.248 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:13:48.248 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:13:48.248 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:13:48.248 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:48.248 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:13:48.248 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:13:48.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:13:48.253 11157 11220 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:13:48.253 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:13:48.253 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:48.253 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:48.253 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:13:48.253 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:13:48.253 11157 11220 I jxcore-log: 
,03-31 10:13:48.258 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:13:48.258 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:48.258 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:48.258 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:13:48.263 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:13:48.263 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:13:48.263 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:48.263 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:13:48.263 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:13:48.263 11157 11220 I jxcore-log: ok 162 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:13:48.263 11157 11220 I jxcore-log: 
,03-31 10:13:48.278 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:48.278 11157 11220 I jxcore-log: 
,03-31 10:13:48.278 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:13:48.278 11157 11220 I jxcore-log: 
,03-31 10:13:48.283 11157 11220 I jxcore-log: # setup
03-31 10:13:48.283 11157 11220 I jxcore-log: 
,03-31 10:13:48.388 11157 11220 I jxcore-log: # 40. Can connect to a remote peer
03-31 10:13:48.388 11157 11220 I jxcore-log: 
,03-31 10:13:48.543 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 42930, start advertisements: true
,03-31 10:13:48.543 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-31 10:13:48.548 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-31 10:13:48.548 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:13:48.553 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:13:48.553 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:48.553 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:48.553 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:48.558  5920  5931 D BtGatt.GattService: registerClient() - UUID=be3931fe-e697-46d2-8cbc-75e1ce1abf3c
,03-31 10:13:48.598  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=be3931fe-e697-46d2-8cbc-75e1ce1abf3c, clientIf=6
,03-31 10:13:48.598 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:48.598  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:48.613  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,03-31 10:13:48.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:48.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:48.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:13:48.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:13:48.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:48.613  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:48.613  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:48.613  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:48.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:48.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:48.613 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:13:48.613 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:48.613 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:48.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:48.613 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:48.613  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:48.613  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:48.613  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:48.613  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:48.613  5920  6014 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-31 10:13:48.618  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-31 10:13:48.618  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:48.618  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:48.618  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:48.618  5920  5933 D BtGatt.GattService: registerClient() - UUID=4f8c388c-3bc5-4ee3-8c26-82001e91d5b6
,03-31 10:13:48.618  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-31 10:13:48.618  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:48.623  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:48.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:48.658  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=4f8c388c-3bc5-4ee3-8c26-82001e91d5b6, clientIf=7
,03-31 10:13:48.663 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:48.693  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 25
,03-31 10:13:48.698  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:48.698  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:48.698  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:48.713  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:13:48.713  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:48.728  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:48.733  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising,
,03-31 10:13:48.743  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-31 10:13:48.748  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:13:48.748  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 10:13:48.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:13:48.753 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
03-31 10:13:48.753 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:13:48.753 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:13:48.753 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-31 10:13:48.753 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:13:48.758 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:13:48.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:13:48.758 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:13:48.758 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:13:48.763 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 10:13:48.763 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:13:48.763 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:48.763 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 10:13:48.763 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:13:48.763 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:13:48.763 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:13:48.763 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:13:48.763 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
03-31 10:13:48.763 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:13:48.763 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:13:48.763 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-31 10:13:48.763 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:13:48.763 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-31 10:13:48.763 11157 11220 I jxcore-log: 
03-31 10:13:48.773 11157 11676 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:13:48.773 11157 11676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:48.778 11157 11676 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
,03-31 10:13:48.778 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:13:48.778 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:13:48.778 11157 11676 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36d215be
,03-31 10:13:48.778 11157 11676 D BluetoothSocket: channel: 6,
03-31 10:13:48.778 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:13:48.783 11157 11220 I jxcore-log: ok 163 Can call startUpdateAdvertisingAndListening without error,
03-31 10:13:48.783 11157 11220 I jxcore-log: 
,03-31 10:13:48.788 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 42930, start advertisements: false
,03-31 10:13:48.788 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:13:48.788 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 10:13:48.788 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:13:48.788 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:13:48.793 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:13:48.793 11157 11220 I jxcore-log: 
,03-31 10:13:48.793 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:13:48.793 11157 11220 I jxcore-log: 
,03-31 10:13:48.798 11157 11220 I jxcore-log: ok 164 Can call startListeningForAdvertisements without error
03-31 10:13:48.798 11157 11220 I jxcore-log: 
,03-31 10:13:49.623  3420  3619 V AlarmManager: waitForAlarm result :4,
,03-31 10:13:49.633  5920  5920 D BtGatt.ScanManager: awakened up at time 259229
,03-31 10:13:49.643  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:49.653  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:49.653  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:49.653  5920  5987 D BtGatt.GattService: current time is 259248912738
03-31 10:13:49.653  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -75, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 48, -115, -80, -116, -20, 108, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:49.653  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:49.653  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:49.653  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:49.653  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:49.658  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-75, mTimestampNanos=259199086238}
03-31 10:13:49.658  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:49.658  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=259199086238}
03-31 10:13:49.658  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:49.658 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:49.658 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:49.658 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-31 10:13:49.658 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
,03-31 10:13:49.658 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: ,
03-31 10:13:49.658 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 10:13:49.668 11157 11220 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-31 10:13:49.668 11157 11220 I jxcore-log: 
,03-31 10:13:49.678 11157 11220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-31 10:13:49.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-31 10:13:49.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-31 10:13:49.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 10:13:49.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-31 10:13:49.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-31 10:13:49.683 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
,03-31 10:13:49.683 11157 11220 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-31 10:13:49.683 11157 11679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1551)
,03-31 10:13:49.688 11157 11220 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}]
03-31 10:13:49.688 11157 11220 I jxcore-log: 
,03-31 10:13:49.693 11157 11679 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-31 10:13:49.693 11157 11679 D BluetoothSocket: connect(): myUserId = 0
03-31 10:13:49.693 11157 11679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:49.693  5920  6017 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-31 10:13:49.693  5920  6100 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:49.693  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 10:13:49.693  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 10:13:49.693  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-31 10:13:49.693 11157 11679 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-31 10:13:49.693  5920  6100 D IOP_DB_BT: db_query_execute: result 1
03-31 10:13:49.698  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 10:13:50.293  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
03-31 10:13:50.293  5920  6100 W bt-btif : bta_dm_acl_change(), event : 4
03-31 10:13:50.293  5920  6100 W bt-btif : scb return value : 1
,03-31 10:13:50.438  5920  6100 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:50.438  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:13:50.463  5920  6100 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:50.463  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 10:13:50.463  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-31 10:13:50.463  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 10:13:50.463  5920  6100 D IOP_DB_BT: db_query_execute: result 1
03-31 10:13:50.463  5920  6100 W bt-btif : bta_dm_acl_change(), event : 0
03-31 10:13:50.463  5920  6100 W bt-btif : info:x10
03-31 10:13:50.468  5920  5987 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-31 10:13:50.468  5920  5987 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-31 10:13:50.468  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
03-31 10:13:50.473  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 10:13:50.648  5920  6100 W bt-sdp  : process_service_search_attr_rsp
,03-31 10:13:50.673  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:50.678  5920  5920 D BtGatt.ScanManager: awakened up at time 260273
03-31 10:13:50.688  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:50.693  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: current time is 260285425072
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 48, -115, -80, -116, -20, 108, 1, -128, -55, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:50.693  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:50.693  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=260285676113}
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=260235676113}
03-31 10:13:50.693  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:50.693 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:50.698 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:50.698 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 10:13:50.698 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:51.513  5920  5987 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 10:13:51.528  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 10:13:51.543  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 10:13:51.543  5920  5987 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-31 10:13:51.548  3420  3977 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 10:13:51.553  5920  5987 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 10:13:51.553  5920  5987 W bt-btif : btif_dm_ssp_reply: accept=1
03-31 10:13:51.558  5920  6011 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-31 10:13:51.563  5920  6011 D BtConfig.SecureMode: isSecureModeOn:false
03-31 10:13:51.563  5920  6011 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 10:13:51.588  3420  3574 W ProcessCpuTracker: Skipping unknown process pid 11685
,03-31 10:13:51.588  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 10:13:51.588  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:51.593  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 10:13:51.593  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-31 10:13:51.593  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-31 10:13:51.593  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 10:13:51.598  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
,03-31 10:13:51.598  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14296db u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{29db6182 10080:com.android.settings/1000}
03-31 10:13:51.598  3420  3651 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:13:51.603  3726  4797 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 10:13:51.603 10080 10080 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 10:13:51.613 10232 11688 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:51.613 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 10:13:51.613  3420  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14296db u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:51.618 10232 10232 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:51.618 10232 10232 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11,
,03-31 10:13:51.623  3420  4340 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14296db u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102},
,03-31 10:13:51.623  3420  4008 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:13:51.633 10232 11689 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:51.633 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
03-31 10:13:51.633  3420  4340 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14296db u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{35e94ebd 10422:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 10:13:51.643 10422 10422 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 10:13:51.648 10422 10422 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:51.648 10422 10422 D GMHFPReceiver: jangil::setProperties()
,03-31 10:13:51.648 10422 10422 D GMHFPReceiver: jangil::printBTStatus()
,03-31 10:13:51.653  3420  3463 D SettingsProvider: name = Wearable0001
03-31 10:13:51.653  3420  3463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:51.653  3420  3463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:51.653  3420  3463 D SettingsProvider: selectionArgs: false
03-31 10:13:51.653  3420  3463 D SettingsProvider: selectionArgs: 10121
03-31 10:13:51.653  3420  3463 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:51.653  3420  3463 D SettingsProvider: ret = -1
,03-31 10:13:51.658  3420  3463 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 10:13:51.663 10422 10422 D GMHFPReceiver: ::::::::Wearable0001::false
03-31 10:13:51.663  3420  3977 D SettingsProvider: name = Wearable0002
,03-31 10:13:51.663  3420  3977 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:51.663  3420  3977 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:51.663  3420  3977 D SettingsProvider: selectionArgs: false
03-31 10:13:51.663  3420  3977 D SettingsProvider: selectionArgs: 10121
,03-31 10:13:51.663  3420  3977 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:51.663  3420  3977 D SettingsProvider: ret = -1
,03-31 10:13:51.668  3420  3977 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-31 10:13:51.668  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 10:13:51.668 10422 10422 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 10:13:51.678  3420  3748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14296db u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{33d4484d 4388:com.google.android.gms.persistent/u0a14}
,03-31 10:13:51.688  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-31 10:13:51.703  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:51.708  5920  5920 D BtGatt.ScanManager: awakened up at time 261301
,03-31 10:13:51.708  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:51.713  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-31 10:13:51.713  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: current time is 261305500197
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: Batch record : [48, -115, -80, -116, -20, 108, 1, -128, -55, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -58, 91, 20, -32, -98, 113, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 10:13:51.713  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:51.713  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=261255641822}
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=261055641822}
03-31 10:13:51.713  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:51.713 11157 11169 D ScanRecord: parseFromBytes
,03-31 10:13:51.713 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:51.713 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:51.713 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:13:51.748 10422 10422 D GMHFPReceiver: onServiceConnected() : 1
,03-31 10:13:51.748 10422 10422 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_execute: result 1
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 10:13:51.983  5920  6100 D IOP_DB_BT: db_query_execute: result 1
,03-31 10:13:52.023  5920  5987 W bt-btif : btif_dm_auth_cmpl_evt
,03-31 10:13:52.033  5920  5987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 10:13:52.063  5920  5987 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-31 10:13:52.068  5920  6011 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-31 10:13:52.073  3420  4339 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 10:13:52.078  5920  6011 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
,03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11,
03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-31 10:13:52.083  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-31 10:13:52.078  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 10:13:52.088  3726  4797 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 10:13:52.093  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82b0653 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{29db6182 10080:com.android.settings/1000}
03-31 10:13:52.093 10080 10080 D BluetoothNotiBroadcastReceiver: onReceive
03-31 10:13:52.093  3420  3460 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 10:13:52.093  5920  6011 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 10:13:52.113  3420  4340 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82b0653 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:52.118  5920  6011 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@33ce4ddd
,03-31 10:13:52.123  3420  3748 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
,03-31 10:13:52.123  3420  3748 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:52.123  3420  3748 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:52.123  3420  3748 D SettingsProvider: selectionArgs: false
03-31 10:13:52.123  3420  3748 D SettingsProvider: selectionArgs: 1002
03-31 10:13:52.123  3420  3748 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:52.123  3420  3748 D SettingsProvider: ret = -1
,03-31 10:13:52.128  5920  6011 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
03-31 10:13:52.133  3420  4361 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-31 10:13:52.133  3420  4361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:52.133  3420  4361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:52.133  3420  4361 D SettingsProvider: selectionArgs: false
03-31 10:13:52.133  3420  4361 D SettingsProvider: selectionArgs: 1002
03-31 10:13:52.133  3420  4361 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:52.133  3420  4361 D SettingsProvider: ret = -1
,03-31 10:13:52.138  3420  3833 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-31 10:13:52.138  3420  3833 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:52.138  3420  3833 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:52.138  3420  3833 D SettingsProvider: selectionArgs: false
03-31 10:13:52.138  3420  3833 D SettingsProvider: selectionArgs: 1002
03-31 10:13:52.138  3420  3833 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:52.138  3420  3833 D SettingsProvider: ret = -1
03-31 10:13:52.138  5920  6011 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-31 10:13:52.143 10232 10232 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:52.148 10232 10232 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-31 10:13:52.153  3420  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82b0653 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:52.158  3420  4339 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:13:52.168  3420  3748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82b0653 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{35e94ebd 10422:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 10:13:52.173 10232 11701 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:52.173 10232 11701 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:52.183 10422 10422 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 10:13:52.188 10422 10422 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:52.188 10422 10422 D GMHFPReceiver: jangil::setProperties()
,03-31 10:13:52.188 10422 10422 D GMHFPReceiver: jangil::printBTStatus()
,03-31 10:13:52.193  3420  3460 D SettingsProvider: name = Wearable0001
03-31 10:13:52.193  3420  3460 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:52.193  3420  3460 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:52.193  3420  3460 D SettingsProvider: selectionArgs: false
03-31 10:13:52.193  3420  3460 D SettingsProvider: selectionArgs: 10121
03-31 10:13:52.193  3420  3460 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:52.193  3420  3460 D SettingsProvider: ret = -1
,03-31 10:13:52.193 10422 10422 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 10:13:52.198  3420  4339 D SettingsProvider: name = Wearable0002
03-31 10:13:52.198  3420  4339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:52.198  3420  4339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:52.198  3420  4339 D SettingsProvider: selectionArgs: false
03-31 10:13:52.198  3420  4339 D SettingsProvider: selectionArgs: 10121
03-31 10:13:52.198  3420  4339 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:52.198  3420  4339 D SettingsProvider: ret = -1
,03-31 10:13:52.198 10422 10422 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 10:13:52.208  3420  3748 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82b0653 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{33d4484d 4388:com.google.android.gms.persistent/u0a14}
,03-31 10:13:52.243  5920  6100 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:13:52.243  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:13:52.248  5920  6100 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:52.248  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
,03-31 10:13:52.248  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-31 10:13:52.248  5920  6100 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-31 10:13:52.248  5920  6100 D IOP_DB_BT: db_query_execute: result 1
03-31 10:13:52.248  5920  6100 W bt-btif : bta_dm_acl_change(), event : 0
03-31 10:13:52.248  5920  6100 W bt-btif : info:x10
03-31 10:13:52.248  5920  5987 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-31 10:13:52.248  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
03-31 10:13:52.248  5920  5987 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-31 10:13:52.288 10422 10422 D GMHFPReceiver: onServiceConnected() : 1
,03-31 10:13:52.288 10422 10422 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 10:13:52.308  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 10:13:52.378  5920  6100 E bt-btm  : btm_sec_encrypt_change collision_start_time is not 0, it 2147457828
03-31 10:13:52.378  5920  6100 E bt-btm  : return here let's wait the timer is expired...
,03-31 10:13:52.718  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:52.728  5920  5920 D BtGatt.ScanManager: awakened up at time 262322
03-31 10:13:52.733  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-31 10:13:52.743  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: current time is 262335198988
,03-31 10:13:52.743  5920  5987 D BtGatt.GattService: Batch record : [48, -115, -80, -116, -20, 108, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -58, 91, 20, -32, -98, 113, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-31 10:13:52.743  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:52.743  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=262185370863}
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=262285370863}
03-31 10:13:52.743  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:52.743 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:52.743 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:52.743 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 10:13:52.743 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:13:52.833  5920  6100 E bt-btm  : btm_sec_encrypt_change collision_start_time is not 0, it 2147457828
03-31 10:13:52.833  5920  6100 E bt-btm  : return here let's wait the timer is expired...
03-31 10:13:52.833  5920  6100 E bt-btm  : tBTM_SEC_DEV:0xb35540d8 rs_disc_pending=1
03-31 10:13:52.833  5920  6100 W bt-btif : bta_dm_acl_change(), event : 3
03-31 10:13:52.833  5920  6100 W bt-btif : bta_dm_check_av:0
03-31 10:13:52.833  5920  5987 W bt-btif : btif_dm_cback : unhandled event (14)
,03-31 10:13:53.473  5920  5984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,03-31 10:13:53.613  5920  5987 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-31 10:13:53.628  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 10:13:53.638  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 10:13:53.638  5920  5987 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
03-31 10:13:53.648  3420  4361 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 10:13:53.648  5920  5987 E bt-btif : check_cod: remote_cod = 0x5a020c
03-31 10:13:53.648  5920  5987 W bt-btif : btif_dm_ssp_reply: accept=1
,03-31 10:13:53.663  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED,
03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,03-31 10:13:53.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 10:13:53.673  5920  6011 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11,
,03-31 10:13:53.683  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e570bc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{29db6182 10080:com.android.settings/1000},
03-31 10:13:53.683 10080 10080 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 10:13:53.683  3420  3748 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 10:13:53.683  5920  6011 D BtConfig.SecureMode: isSecureModeOn:false
03-31 10:13:53.683  5920  6011 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-31 10:13:53.688  3726  4797 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 10:13:53.693 10232 11716 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:53.693 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 10:13:53.693  3420  4361 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e570bc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:53.693 10232 10232 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:53.698 10232 10232 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
,03-31 10:13:53.703  3420  4340 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e570bc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:53.703  3420  4339 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:13:53.708 10232 11717 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-31 10:13:53.713 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-31 10:13:53.713  3420  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e570bc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{35e94ebd 10422:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 10:13:53.713 10422 10422 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 10:13:53.713 10422 10422 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:53.718 10422 10422 D GMHFPReceiver: jangil::setProperties()
,03-31 10:13:53.723 10422 10422 D GMHFPReceiver: jangil::printBTStatus()
,03-31 10:13:53.723  3420  3651 D SettingsProvider: name = Wearable0001
03-31 10:13:53.723  3420  3651 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:53.723  3420  3651 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:53.723  3420  3651 D SettingsProvider: selectionArgs: false
03-31 10:13:53.723  3420  3651 D SettingsProvider: selectionArgs: 10121
03-31 10:13:53.723  3420  3651 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:53.723  3420  3651 D SettingsProvider: ret = -1
03-31 10:13:53.723 10422 10422 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 10:13:53.723  3420  4361 D SettingsProvider: name = Wearable0002
,03-31 10:13:53.723  3420  4361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:53.723  3420  4361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:53.723  3420  4361 D SettingsProvider: selectionArgs: false
03-31 10:13:53.723  3420  4361 D SettingsProvider: selectionArgs: 10121
03-31 10:13:53.723  3420  4361 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:53.723  3420  4361 D SettingsProvider: ret = -1
,03-31 10:13:53.723 10422 10422 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 10:13:53.728  3420  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4e570bc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{33d4484d 4388:com.google.android.gms.persistent/u0a14}
,03-31 10:13:53.753  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:53.753  5920  5920 D BtGatt.ScanManager: awakened up at time 263348
,03-31 10:13:53.753  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:53.758  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:53.758  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: current time is 263352548905
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 48, -115, -80, -116, -20, 108, 1, -128, -52, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:53.758  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:53.758  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:53.758  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-52, mTimestampNanos=263302723239}
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=263252723239}
03-31 10:13:53.758  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:53.758 11157 11169 D ScanRecord: parseFromBytes
03-31 10:13:53.758 11157 11169 D ScanRecord: parseFromBytes
,03-31 10:13:53.763 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:13:53.763 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:53.818 10422 10422 D GMHFPReceiver: onServiceConnected() : 1
,03-31 10:13:53.818 10422 10422 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 10:13:53.898  5920  5987 W bt-btif : btif_dm_auth_cmpl_evt,
03-31 10:13:53.898  5920  5987 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-31 10:13:53.938  5920  5987 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
03-31 10:13:53.938  5920  6011 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-31 10:13:53.953  3420  3748 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
,03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10,
03-31 10:13:53.993  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-31 10:13:53.998  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
,03-31 10:13:54.008  5920  6011 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10,
,03-31 10:13:54.023  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1429a766 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{29db6182 10080:com.android.settings/1000}
,03-31 10:13:54.023  5920  6011 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 10:13:54.028  5920  6011 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@33ce4ddd
,03-31 10:13:54.028  3420  3833 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-31 10:13:54.028  3420  3833 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:54.028  3420  3833 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:54.028  3420  3833 D SettingsProvider: selectionArgs: false
03-31 10:13:54.028  3420  3833 D SettingsProvider: selectionArgs: 1002
03-31 10:13:54.028  3420  3833 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:54.033  3420  3833 D SettingsProvider: ret = -1
,03-31 10:13:54.033  5920  6011 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
03-31 10:13:54.033  3420  4360 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-31 10:13:54.033  3420  4360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
03-31 10:13:54.033  3420  4360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:54.033  3420  4360 D SettingsProvider: selectionArgs: false
,03-31 10:13:54.033  3420  4360 D SettingsProvider: selectionArgs: 1002
03-31 10:13:54.033  3420  4360 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:54.033  3420  4360 D SettingsProvider: ret = -1
,03-31 10:13:54.038  3420  3748 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61,
03-31 10:13:54.038  3420  3748 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:54.038  3420  3748 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-31 10:13:54.038  3420  3748 D SettingsProvider: selectionArgs: false
03-31 10:13:54.038  3420  3748 D SettingsProvider: selectionArgs: 1002
,03-31 10:13:54.038  3420  3748 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-31 10:13:54.038  3420  3748 D SettingsProvider: ret = -1
,03-31 10:13:54.043  5920  6011 I BluetoothBondStateMachine: StableState(): Entering Off State,
03-31 10:13:54.043 10080 10080 D BluetoothNotiBroadcastReceiver: onReceive
,03-31 10:13:54.053  3420  4361 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1429a766 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:54.058  3420  3460 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:13:54.068 10232 10232 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:54.068 10232 10232 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-31 10:13:54.073  3420  4008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1429a766 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{22a0fdea 10232:com.sec.android.automotive.drivelink/u0a102}
,03-31 10:13:54.078 10232 11721 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:54.083  3420  3977 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-31 10:13:54.083  3726  4797 D BluetoothTile:  handleUpdatestate:false name:null
,03-31 10:13:54.088 10232 11721 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-31 10:13:54.088  3420  4008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1429a766 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{35e94ebd 10422:com.samsung.android.app.watchmanagerstub/u0a121}
,03-31 10:13:54.093 10422 10422 E BluetoothHeadset: BTStateChangeCB is registed
,03-31 10:13:54.093 10422 10422 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-31 10:13:54.093 10422 10422 D GMHFPReceiver: jangil::setProperties()
,03-31 10:13:54.098 10422 10422 D GMHFPReceiver: jangil::printBTStatus()
,03-31 10:13:54.098  3420  3836 D SettingsProvider: name = Wearable0001
03-31 10:13:54.098  3420  3836 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:54.098  3420  3836 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:54.098  3420  3836 D SettingsProvider: selectionArgs: false
03-31 10:13:54.098  3420  3836 D SettingsProvider: selectionArgs: 10121
03-31 10:13:54.098  3420  3836 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:54.098  3420  3836 D SettingsProvider: ret = -1
03-31 10:13:54.098 10422 10422 D GMHFPReceiver: ::::::::Wearable0001::false
,03-31 10:13:54.098  3420  4339 D SettingsProvider: name = Wearable0002
03-31 10:13:54.098  3420  4339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-31 10:13:54.098  3420  4339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-31 10:13:54.098  3420  4339 D SettingsProvider: selectionArgs: false
03-31 10:13:54.098  3420  4339 D SettingsProvider: selectionArgs: 10121
03-31 10:13:54.098  3420  4339 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-31 10:13:54.098  3420  4339 D SettingsProvider: ret = -1
,03-31 10:13:54.098 10422 10422 D GMHFPReceiver: ::::::::Wearable0002::false
,03-31 10:13:54.103  3420  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1429a766 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{33d4484d 4388:com.google.android.gms.persistent/u0a14}
,03-31 10:13:54.203 10422 10422 D GMHFPReceiver: onServiceConnected() : 1
,03-31 10:13:54.203 10422 10422 D GMHFPReceiver: mBluetoothHeadset = true
,03-31 10:13:54.458  5920  6100 W bt-btif : new conn_srvc id:26, app_id:255
03-31 10:13:54.458  5920  6100 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 10:13:54.458  5920  6100 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 10:13:54.463 11157 11676 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@23caefed
,03-31 10:13:54.473  5920  5931 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 10:13:54.473 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
,03-31 10:13:54.488 11157 11676 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:13:54.493 11157 11676 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 10:13:54.498 11157 11676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1552)
,03-31 10:13:54.498 11157 11676 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10d08e22, channel: 6, state: LISTENING
,03-31 10:13:54.498 11157 11676 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10d08e22, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36d215be, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@46710b3mSocket: android.net.LocalSocket@246ad670 impl:android.net.LocalSocketImpl@19739de9 fd:FileDescriptor[93]
,03-31 10:13:54.498 11157 11676 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@246ad670 impl:android.net.LocalSocketImpl@19739de9 fd:FileDescriptor[93]
,03-31 10:13:54.503 11157 11676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:13:54.503 11157 11676 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 10:13:54.508 11157 11676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:13:54.508 11157 11676 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,03-31 10:13:54.508 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 10:13:54.513 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-31 10:13:54.513 11157 11676 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b8d6a6e
03-31 10:13:54.513 11157 11676 D BluetoothSocket: channel: 6
,03-31 10:13:54.513 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:54.513 11157 11728 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1552)
,03-31 10:13:54.738  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:54.738  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:54.738  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:54.743  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:54.743 11157 11728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1552)
,03-31 10:13:54.753 11157 11728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 10:13:54.753  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:54.758  3420  3619 V AlarmManager: waitForAlarm result :4
03-31 10:13:54.758  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:54.758  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:13:54.758  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:13:54.768  5920  5920 D BtGatt.ScanManager: awakened up at time 264360
03-31 10:13:54.773  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:54.773  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:54.778  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: current time is 264370221697
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 48, -115, -80, -116, -20, 108, 1, -128, -52, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:54.778  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:54.778  5920  5987 D ScanRecord: parseFromBytes
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=6C:EC:8C:B0:8D:30, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-52, mTimestampNanos=264270401614}
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=71:9E:E0:14:5B:C6, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=264270401614}
03-31 10:13:54.778  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:54.778 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:54.778 11157 11167 D ScanRecord: parseFromBytes
03-31 10:13:54.778 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-31 10:13:54.778 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:54.788 11157 11728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1552),
,03-31 10:13:54.788 11157 11728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1552
03-31 10:13:54.788 11157 11728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1552)
,03-31 10:13:54.788 11157 11728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:13:54.793 11157 11157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:13:54.793 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:13:54.793 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2,
,03-31 10:13:54.808 11157 11728 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1552),
,03-31 10:13:54.813 11157 11157 D BluetoothSocket: getInputStream(): myUserId = 0,
03-31 10:13:54.813 11157 11157 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 10:13:54.813 11157 11157 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 10:13:54.818 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:13:54.823 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:13:54.823  5920  6013 D BtGatt.AdvertiseManager: message : 1
,03-31 10:13:54.823  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:54.823  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:54.828  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:13:54.828  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 10:13:54.828  5920  5987 D BtGatt.GattService: Client app is not null!
,03-31 10:13:54.833  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-31 10:13:54.833 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:13:54.833 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:54.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:13:54.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:54.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:13:54.838 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:54.838 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:54.838 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:13:54.838 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:13:54.843  5920  5933 D BtGatt.GattService: registerClient() - UUID=d6f35355-fb49-45eb-8487-7ed1aba207b1
,03-31 10:13:54.853 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10d08e22, channel: 6, state: CLOSED
,03-31 10:13:54.853 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15986927, channel: 6, state: CLOSED
,03-31 10:13:54.853 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33a9e709, channel: 6, state: CLOSED
,03-31 10:13:54.858 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f312ed1, channel: 6, state: CLOSED
,03-31 10:13:54.858 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2288f14f, channel: 6, state: CLOSED
,03-31 10:13:54.858 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d2bbb47, channel: 6, state: CLOSED
,03-31 10:13:54.883  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=d6f35355-fb49-45eb-8487-7ed1aba207b1, clientIf=7
,03-31 10:13:54.888 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:54.898  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 26
,03-31 10:13:54.898  5920  6013 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:54.898  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
,03-31 10:13:54.898  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:54.898  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:13:54.898  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:54.903  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:54.903  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:54.903  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:13:54.903  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:13:54.903  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 10:13:54.903 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:54.908  5920  5933 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:54.908  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:54.908  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 11
03-31 10:13:54.908  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:54.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:54.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:54.908 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:54.908 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:54.908 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:54.908  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:54.908  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:54.908  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:13:54.908 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:13:54.908  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 10:13:54.908  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:54.908  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:54.913  5920  6017 D BtGatt.GattService: registerClient() - UUID=8fbb6587-be7b-4643-8ce2-a2c400a0aefb
,03-31 10:13:54.913  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:13:54.913  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:54.913  5920  5987 D BtGatt.GattService: current time is 264507481864
03-31 10:13:54.913  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -66, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 48, -115, -80, -116, -20, 108, 1, -128, -52, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:13:54.913  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:54.913  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:54.913  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:13:54.913  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:54.953  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=8fbb6587-be7b-4643-8ce2-a2c400a0aefb, clientIf=6
03-31 10:13:54.953 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:54.953  5920  5933 D BtGatt.GattService: start scan with filters
,03-31 10:13:54.973  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
,03-31 10:13:54.983  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:54.983  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:54.983  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:13:54.983  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:54.983  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:54.988  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:54.988  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:54.988  5920  6014 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
,03-31 10:13:54.988  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:54.988  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:54.988  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:54.988  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:54.993  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:54.993  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:54.993  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:54.993  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:55.003 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:13:55.003 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:13:55.008  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:13:55.008  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:13:55.008  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:55.008  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:13:55.008  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:55.008  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:13:55.008  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:13:55.008 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:13:55.008 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
03-31 10:13:55.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:13:55.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:13:55.013 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 10:13:55.013 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:13:55.013 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:55.013 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:13:55.013 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-31 10:13:55.018  5920  5931 D BtGatt.GattService: registerClient() - UUID=aecba2e6-daf6-4702-bc88-69197c4dc174
,03-31 10:13:55.063  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=aecba2e6-daf6-4702-bc88-69197c4dc174, clientIf=7
,03-31 10:13:55.063 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:55.083  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 27
,03-31 10:13:55.083  5920  6013 D BtGatt.AdvertiseManager: message : 0
03-31 10:13:55.083  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:55.083  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:55.083  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:13:55.083  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:55.088  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:55.088  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:55.088  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 10:13:55.088  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:13:55.088  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 10:13:55.088 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:55.093  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:13:55.093  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:55.093  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 12
03-31 10:13:55.093  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:55.093 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:13:55.093 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:55.093 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:55.093 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:13:55.093 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:13:55.093 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:55.093  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:55.093  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.093  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:55.098  5920  5931 D BtGatt.GattService: registerClient() - UUID=a87c4c48-e4c6-45e5-b757-7233cdfd2b18
,03-31 10:13:55.098  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:13:55.098  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.098  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:55.098  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:55.098  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:55.138  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=a87c4c48-e4c6-45e5-b757-7233cdfd2b18, clientIf=6
,03-31 10:13:55.143 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:13:55.143  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:55.183  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 33
,03-31 10:13:55.183 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:13:55.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:13:55.183  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:55.183  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:13:55.183  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:55.188  5920  6013 D BtGatt.AdvertiseManager: message : 1
,03-31 10:13:55.193  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-31 10:13:55.198  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:13:55.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.198  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:55.198  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-31 10:13:55.198  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:13:55.198  5920  6014 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
,03-31 10:13:55.208  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,03-31 10:13:55.208  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 10:13:55.208  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:13:55.208  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:13:55.208  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,03-31 10:13:55.208  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:13:55.208  5920  5987 D BtGatt.GattService: Client app is not null!,
03-31 10:13:55.218  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:13:55.228  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
,03-31 10:13:55.228  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:13:55.228  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:55.228  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 10:13:55.233 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 10:13:55.233 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
,03-31 10:13:55.233 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
,03-31 10:13:55.233 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,03-31 10:13:55.233 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
,03-31 10:13:55.233 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
,03-31 10:13:55.233 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-31 10:13:55.233 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-31 10:13:55.233 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-31 10:13:55.258  5920  5931 D BtGatt.GattService: registerClient() - UUID=28c900b8-41ee-4abf-89b4-83e26cc36843,
,03-31 10:13:55.303  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=28c900b8-41ee-4abf-89b4-83e26cc36843, clientIf=7,
,03-31 10:13:55.303 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:13:55.358  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 28
,03-31 10:13:55.358  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:13:55.363  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:13:55.363  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:13:55.368  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:13:55.368  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:13:55.373  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:13:55.378  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:13:55.378  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:13:55.383  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 10:13:55.383  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 10:13:55.388 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-31 10:13:55.388  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:13:55.388  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:13:55.388  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 13
03-31 10:13:55.388  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:13:55.388 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:13:55.388 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:13:55.388 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:13:55.388 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:13:55.388 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:13:55.388 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:13:55.388  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:13:55.388  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.393  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:13:55.393  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 10:13:55.393  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.393  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:55.398  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-31 10:13:55.398  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.398  5920  5987 D BtGatt.GattService: current time is 264990521655
03-31 10:13:55.398  5920  5987 D BtGatt.GattService: Batch record : [-58, 91, 20, -32, -98, 113, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:13:55.398  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:13:55.398  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:13:55.398  5920  5931 D BtGatt.GattService: registerClient() - UUID=58b5c0c9-942c-46e1-98bd-32d450c74112
,03-31 10:13:55.438  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=58b5c0c9-942c-46e1-98bd-32d450c74112, clientIf=6
,03-31 10:13:55.438 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:13:55.438  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:13:55.453  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 34
,03-31 10:13:55.453 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-31 10:13:55.453 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:13:55.453 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 10:13:55.453 11157 11157 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 10:13:55.453 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:55.453 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:13:55.453 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:13:55.453 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:13:55.453 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-31 10:13:55.453  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:13:55.453  5920  6014 D BtGatt.ScanManager: isFilteringSupported
,03-31 10:13:55.453  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:13:55.453 11157 11756 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1553)
,03-31 10:13:55.453  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-31 10:13:55.453  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:55.453  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:13:55.453  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:13:55.453  5920  6014 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-31 10:13:55.458  2872  3479 D EnterpriseController: netId is 0
03-31 10:13:55.458  2872  3479 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-31 10:13:55.458  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:13:55.458  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.458  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:13:55.458  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:13:55.458  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:13:55.458  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:13:55.463  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:13:55.463  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:55.468 11157 11756 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 42930,
03-31 10:13:55.468 11157 11756 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...,
,03-31 10:13:55.468 11157 11756 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:13:55.468 11157 11756 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:13:55.468 11157 11758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Sender)
,03-31 10:13:55.468 11157 11756 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1553)
03-31 10:13:55.473 11157 11756 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1553)
,03-31 10:13:55.473 11157 11759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1555, name: Receiver)
,03-31 10:13:56.463  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:56.468  5920  5920 D BtGatt.ScanManager: awakened up at time 266063
03-31 10:13:56.478  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:56.478  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:56.478  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:56.528  3420  4008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:13:56.533  3420  4008 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:13:56.533  3420  4008 D BatteryService: online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-31 10:13:56.533  3420  4008 D BatteryService: stay LED for fully charged
03-31 10:13:56.533  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:13:56.533  3420  3420 I MotionRecognitionService: Plugged
03-31 10:13:56.533  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:13:56.533  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:13:56.533  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:13:56.538  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:56.538  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:13:56.538  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:13:56.543  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:13:56.543  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:13:56.558  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:13:56.558  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:56.558  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:13:56.558  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:13:56.818  3420  6131 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:12), CUR = 57, LCD = 0
,03-31 10:13:57.483  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:57.498  5920  5920 D BtGatt.ScanManager: awakened up at time 267092
,03-31 10:13:57.503  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:57.508  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:57.508  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:58.518  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:58.533  5920  5920 D BtGatt.ScanManager: awakened up at time 268128
,03-31 10:13:58.543  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:13:58.543  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:13:58.543  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:59.433  5920  6100 W bt-btif : new conn_srvc id:26, app_id:255
03-31 10:13:59.433  5920  6100 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-31 10:13:59.433  5920  6100 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 10:13:59.438 11157 11676 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1529bf7a
,03-31 10:13:59.443  5920  6100 W bt-btif : new conn_srvc id:26, app_id:1,
03-31 10:13:59.443  5920  6100 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-31 10:13:59.443  5920  6100 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
,03-31 10:13:59.443  5920  6100 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-31 10:13:59.453  5920  5933 E BluetoothRemoteDevices: setRfcommConnected true
03-31 10:13:59.458 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-31 10:13:59.458  5920 11743 E BluetoothRemoteDevices: setRfcommConnected true
03-31 10:13:59.463 11157 11679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1551)
03-31 10:13:59.463 11157 11679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1551)
,03-31 10:13:59.468 11157 11676 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:13:59.473 11157 11679 D BluetoothSocket: getInputStream(): myUserId = 0
03-31 10:13:59.478 11157 11676 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 10:13:59.478 11157 11676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1556)
03-31 10:13:59.478 11157 11676 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d79e32b, channel: 6, state: LISTENING
,03-31 10:13:59.478 11157 11676 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d79e32b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b8d6a6e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e5f0388mSocket: android.net.LocalSocket@4b82121 impl:android.net.LocalSocketImpl@1d045946 fd:FileDescriptor[113]
03-31 10:13:59.478 11157 11676 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4b82121 impl:android.net.LocalSocketImpl@1d045946 fd:FileDescriptor[113]
03-31 10:13:59.478 11157 11676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:13:59.483 11157 11773 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1556)
03-31 10:13:59.483 11157 11676 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:13:59.483 11157 11676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-31 10:13:59.483 11157 11679 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 10:13:59.483 11157 11679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1557)
03-31 10:13:59.483 11157 11679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1557)
03-31 10:13:59.483 11157 11679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1551)
03-31 10:13:59.488 11157 11676 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
03-31 10:13:59.488 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket 
,03-31 10:13:59.488 11157 11676 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:13:59.488 11157 11676 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318707
03-31 10:13:59.488 11157 11676 D BluetoothSocket: channel: 6
03-31 10:13:59.488 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-31 10:13:59.488 11157 11775 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1557)
,03-31 10:13:59.553  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:13:59.563  5920  5920 D BtGatt.ScanManager: awakened up at time 269157
,03-31 10:13:59.563  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:13:59.568  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-31 10:13:59.568  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:13:59.738  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:59.743  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:59.743  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:59.743  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:59.743 11157 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1556)
,03-31 10:13:59.753 11157 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-31 10:13:59.758  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:59.758  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:59.758  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:59.758  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:13:59.763 11157 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1556)
03-31 10:13:59.763 11157 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1556
,03-31 10:13:59.763 11157 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1556)
03-31 10:13:59.763 11157 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 10:13:59.763 11157 11157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-31 10:13:59.763 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51],
03-31 10:13:59.763 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:59.773 11157 11157 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-31 10:13:59.778 11157 11157 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-31 10:13:59.778 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 10:13:59.778 11157 11157 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-31 10:13:59.778 11157 11773 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1556),
03-31 10:13:59.783 11157 11781 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1558)
,03-31 10:13:59.783  2872  3479 D EnterpriseController: netId is 0
03-31 10:13:59.783  2872  3479 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 10:13:59.788 11157 11781 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 42930
,03-31 10:13:59.793 11157 11781 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-31 10:13:59.793 11157 11781 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 10:13:59.793 11157 11781 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:13:59.793 11157 11781 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1558)
,03-31 10:13:59.793 11157 11781 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1558)
,03-31 10:13:59.798 11157 11783 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1559, name: Sender)
,03-31 10:13:59.798 11157 11784 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1560, name: Receiver)
,03-31 10:13:59.858  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:13:59.858 11157 11775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1557)
03-31 10:13:59.858  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:59.858  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-31 10:13:59.858  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:13:59.858 11157 11775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-31 10:13:59.858 11157 11775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1551)
03-31 10:13:59.858 11157 11775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1551)
03-31 10:13:59.858 11157 11775 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1557)
03-31 10:13:59.858 11157 11157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-31 10:13:59.858 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-31 10:13:59.858 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-31 10:13:59.863 11157 11157 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:13:59.868 11157 11157 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 10:13:59.868 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-31 10:13:59.868 11157 11157 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 3
03-31 10:13:59.868 11157 11788 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1561)
,03-31 10:13:59.868 11157 11788 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47412
03-31 10:13:59.868 11157 11788 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-31 10:13:59.868 11157 11788 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 47412 (peer ID: F8:95:C7:87:3C:51)
03-31 10:13:59.873 11157 11788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-31 10:13:59.873 11157 11220 I jxcore-log: INFO testThaliMobileNative: 
03-31 10:13:59.873 11157 11220 I jxcore-log: 
,03-31 10:13:59.878 11157 11220 I jxcore-log: ok 165 Must have listeningPort
03-31 10:13:59.878 11157 11220 I jxcore-log: 
,03-31 10:13:59.878 11157 11220 I jxcore-log: ok 166 listeningPort must be a number
03-31 10:13:59.878 11157 11220 I jxcore-log: 
,03-31 10:13:59.878 11157 11220 I jxcore-log: ok 167 Connection must have clientPort
03-31 10:13:59.878 11157 11220 I jxcore-log: 
03-31 10:13:59.878 11157 11220 I jxcore-log: ok 168 clientPort must be a number
03-31 10:13:59.878 11157 11220 I jxcore-log: 
,03-31 10:13:59.878 11157 11220 I jxcore-log: ok 169 Connection must have serverPort
03-31 10:13:59.878 11157 11220 I jxcore-log: 
03-31 10:13:59.883 11157 11220 I jxcore-log: ok 170 serverPort must be a number
03-31 10:13:59.883 11157 11220 I jxcore-log: 
,03-31 10:13:59.883 11157 11220 I jxcore-log: ok 171 forward connection must have clientPort == 0
03-31 10:13:59.883 11157 11220 I jxcore-log: 
,03-31 10:13:59.883 11157 11220 I jxcore-log: ok 172 forward connection must have serverPort == 0
03-31 10:13:59.883 11157 11220 I jxcore-log: 
,03-31 10:13:59.893 11157 11220 I jxcore-log: # teardown
03-31 10:13:59.893 11157 11220 I jxcore-log: 
,03-31 10:13:59.993  3420  3619 V AlarmManager: waitForAlarm result :8
,03-31 10:14:00.043 11157 11758 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1554, thread name: Sender),
,03-31 10:14:00.043 11157 11758 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 10:14:00.043 11157 11758 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-31 10:14:00.043 11157 11758 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1553
03-31 10:14:00.043 11157 11758 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1553)
03-31 10:14:00.043 11157 11758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179cc3d2, channel: 6, state: CONNECTED
,03-31 10:14:00.043 11157 11758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@179cc3d2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17d58ca3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1fd8bba0mSocket: android.net.LocalSocket@1632d359 impl:android.net.LocalSocketImpl@3fdf4b1e fd:FileDescriptor[92]
03-31 10:14:00.043 11157 11758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1632d359 impl:android.net.LocalSocketImpl@3fdf4b1e fd:FileDescriptor[92]
03-31 10:14:00.043 11157 11759 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1555, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:00.043 11157 11759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1555, name: Receiver)
03-31 10:14:00.048 11157 11758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179cc3d2, channel: 6, state: CLOSED
03-31 10:14:00.048 11157 11758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179cc3d2, channel: 6, state: CLOSED
03-31 10:14:00.048 11157 11758 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-31 10:14:00.048 11157 11758 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...,
03-31 10:14:00.048 11157 11758 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1555
03-31 10:14:00.048 11157 11758 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 10:14:00.048 11157 11758 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-31 10:14:00.048 11157 11758 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1553),
03-31 10:14:00.048 11157 11758 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1553)
03-31 10:14:00.048 11157 11758 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
03-31 10:14:00.048 11157 11783 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1559, thread name: Sender),
03-31 10:14:00.048 11157 11783 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-31 10:14:00.048 11157 11783 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-31 10:14:00.048 11157 11783 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1558
03-31 10:14:00.048 11157 11783 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1558)
03-31 10:14:00.048 11157 11783 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a4fff, channel: 6, state: CONNECTED
03-31 10:14:00.048 11157 11783 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@322a4fff, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e9df1cc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38b44c15mSocket: android.net.LocalSocket@130fb2a impl:android.net.LocalSocketImpl@1added1b fd:FileDescriptor[115]
03-31 10:14:00.053 11157 11783 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@130fb2a impl:android.net.LocalSocketImpl@1added1b fd:FileDescriptor[115],
03-31 10:14:00.053 11157 11784 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1560, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:00.053 11157 11784 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1560, name: Receiver)
03-31 10:14:00.053 11157 11783 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a4fff, channel: 6, state: CLOSED,
03-31 10:14:00.053 11157 11783 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a4fff, channel: 6, state: CLOSED,
,03-31 10:14:00.053 11157 11783 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
,03-31 10:14:00.053 11157 11783 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-31 10:14:00.053 11157 11783 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1560
03-31 10:14:00.053 11157 11783 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...,
,03-31 10:14:00.053 11157 11783 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1559
03-31 10:14:00.053 11157 11783 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1558)
03-31 10:14:00.053 11157 11783 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1558)
03-31 10:14:00.058 11157 11783 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 10:14:00.058 11157 11783 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1559, name: Sender)
03-31 10:14:00.063 11157 11758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Sender)
03-31 10:14:00.068 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:00.068 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:00.068 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:14:00.068 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:00.073  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:00.073  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:00.073  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 14
03-31 10:14:00.073  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 10:14:00.073  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:00.073  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:00.078  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:00.078  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:00.078  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:00.078  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:00.078  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:00.078  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:00.083 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-31 10:14:00.083 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-31 10:14:00.083 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:00.083 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:00.083 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:00.083 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:00.083 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:00.083 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:00.083 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:14:00.098 11157 11220 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 10:14:00.098 11157 11220 I jxcore-log: 
,03-31 10:14:00.098 11157 11220 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 10:14:00.098 11157 11220 I jxcore-log: 
,03-31 10:14:00.098 11157 11220 I jxcore-log: ok 173 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:14:00.098 11157 11220 I jxcore-log: 
,03-31 10:14:00.103 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:00.103 11157 11220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-31 10:14:00.103 11157 11220 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1561)
03-31 10:14:00.103 11157 11220 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1561)
,03-31 10:14:00.103 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c9e5eb8, channel: 7, state: CONNECTED
03-31 10:14:00.103 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c9e5eb8, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a9a9491, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@263b9ff6mSocket: android.net.LocalSocket@20643ff7 impl:android.net.LocalSocketImpl@636ae64 fd:FileDescriptor[112]
03-31 10:14:00.103 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20643ff7 impl:android.net.LocalSocketImpl@636ae64 fd:FileDescriptor[112]
,03-31 10:14:00.103  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:14:00.103  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:00.103  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:14:00.108  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:00.108 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c9e5eb8, channel: 7, state: CLOSED
03-31 10:14:00.108 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c9e5eb8, channel: 7, state: CLOSED
,03-31 10:14:00.108 11157 11220 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:00.108 11157 11220 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1561)
03-31 10:14:00.108 11157 11220 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1561)
,03-31 10:14:00.108 11157 11788 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1561)
03-31 10:14:00.108 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:00.108 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:00.108 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:14:00.108 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:00.113 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13c2e8cd, channel: 6, state: LISTENING
03-31 10:14:00.113 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13c2e8cd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@318707, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2879c582mSocket: android.net.LocalSocket@1a92e493 impl:android.net.LocalSocketImpl@2ee24cd0 fd:FileDescriptor[116]
03-31 10:14:00.113 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a92e493 impl:android.net.LocalSocketImpl@2ee24cd0 fd:FileDescriptor[116]
,03-31 10:14:00.113 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-31 10:14:00.113 11157 11676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:00.113 11157 11676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:00.113 11157 11676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:00.113 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:14:00.113 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:14:00.113 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:00.113 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:14:00.118 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:00.118 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:00.118 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:00.118 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:14:00.118 11157 11220 D BluetoothLeScanner: could not find callback wrapper,
03-31 10:14:00.118 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:00.118 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:14:00.123  5920  6013 D BtGatt.AdvertiseManager: message : 1,
,03-31 10:14:00.123  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:00.123  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:14:00.123  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-31 10:14:00.123  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-31 10:14:00.123  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:14:00.128  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:14:00.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:00.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:00.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:00.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
,03-31 10:14:00.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:00.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:00.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:00.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:00.133 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:14:00.133 11157 11220 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:14:00.133 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:00.133 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:00.133 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:00.133 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:00.133 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:00.133 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:00.143 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:00.148 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:00.148 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:00.148 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:00.148 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:00.148 11157 11220 I jxcore-log: 
,03-31 10:14:00.153 11157 11220 I jxcore-log: ok 174 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:14:00.153 11157 11220 I jxcore-log: 
,03-31 10:14:00.153 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:00.153 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:00.158 11157 11220 I jxcore-log: # setup
03-31 10:14:00.158 11157 11220 I jxcore-log: 
,03-31 10:14:00.163 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:00.163 11157 11220 I jxcore-log: 
03-31 10:14:00.163  5920  6100 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
03-31 10:14:00.163  5920  6100 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 10:14:00.163 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:00.163 11157 11220 I jxcore-log: 
,03-31 10:14:00.398  5920  6100 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-31 10:14:00.408  5920  6100 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
03-31 10:14:00.408  5920  6100 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-31 10:14:00.723  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:14:01.383 11157 11220 I jxcore-log: # 41. Can shift large amounts of data
03-31 10:14:01.383 11157 11220 I jxcore-log: 
,03-31 10:14:01.533  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:14:01.533  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:01.533  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-31 10:14:01.533  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:01.663 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 43167, start advertisements: true
,03-31 10:14:01.663 11157 11220 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 10:14:01.663 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:01.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:01.673 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:01.678 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:01.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:01.683 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:01.683 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:01.683 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:01.688 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:14:01.688 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:01.688 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:01.688 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:01.693  5920  5931 D BtGatt.GattService: registerClient() - UUID=4dc9750d-2876-462b-aa31-923d0d8bdde5
,03-31 10:14:01.733  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=4dc9750d-2876-462b-aa31-923d0d8bdde5, clientIf=6
,03-31 10:14:01.733 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:01.733  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:14:01.748  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 35
,03-31 10:14:01.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:01.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:01.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-31 10:14:01.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:01.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:01.748  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:01.748  5920  6014 D BtGatt.ScanManager: isFilteringSupported
,03-31 10:14:01.748  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:01.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:01.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:01.748 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:01.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:01.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:14:01.753 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:01.753 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:01.753  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:01.753  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:01.753  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:01.753  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:01.753  5920  6014 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
,03-31 10:14:01.753  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 10:14:01.753  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:01.758  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:01.758  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:01.758  5920  6017 D BtGatt.GattService: registerClient() - UUID=57b08bdc-0f7a-45a2-9881-f0d6d980122e
,03-31 10:14:01.758  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:01.758  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:01.763  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:01.763  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:01.798  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=57b08bdc-0f7a-45a2-9881-f0d6d980122e, clientIf=7,
03-31 10:14:01.803 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:14:01.818  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 29
,03-31 10:14:01.818  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:01.818  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:01.818  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:14:01.823  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:14:01.823  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:14:01.828  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:01.833  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:01.838  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:01.838  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:14:01.838  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:14:01.838 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:01.838 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:01.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:01.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:01.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:01.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:01.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:14:01.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:01.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:01.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-31 10:14:01.843 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-31 10:14:01.843 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:01.843 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:01.843 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 10:14:01.843 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:01.843 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:01.843 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:01.843 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:01.843 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-31 10:14:01.843 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:01.843 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:14:01.843 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-31 10:14:01.848 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:01.848 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:01.848 11157 11220 I jxcore-log: 
,03-31 10:14:01.853 11157 11806 D BluetoothSocket: bindListen(): myUserId = 0,
03-31 10:14:01.853 11157 11806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:01.858 11157 11806 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-31 10:14:01.858 11157 11806 D BluetoothSocket: bindListen(), new LocalSocket ,
03-31 10:14:01.858 11157 11806 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:14:01.858 11157 11806 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@246765fc
03-31 10:14:01.858 11157 11806 D BluetoothSocket: channel: 6,
03-31 10:14:01.858 11157 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:01.863 11157 11220 I jxcore-log: ok 175 Can call startUpdateAdvertisingAndListening without error,
03-31 10:14:01.863 11157 11220 I jxcore-log: 
,03-31 10:14:01.868 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 43167, start advertisements: false
,03-31 10:14:01.868 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:01.868 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-31 10:14:01.868 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:01.868 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:01.868 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:01.868 11157 11220 I jxcore-log: 
,03-31 10:14:01.873 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:01.873 11157 11220 I jxcore-log: 
,03-31 10:14:01.873 11157 11220 I jxcore-log: ok 176 Can call startListeningForAdvertisements without error
03-31 10:14:01.873 11157 11220 I jxcore-log: 
,03-31 10:14:02.763  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:02.783  5920  5920 D BtGatt.ScanManager: awakened up at time 272377
,03-31 10:14:02.788  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:14:02.798  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:14:02.798  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: current time is 272392586198
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: Batch record : [-49, -106, -99, 28, -117, 71, 1, -128, -54, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -45, 45, -19, -88, -8, 71, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:14:02.798  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:02.798  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=47:8B:1C:9D:96:CF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=272042776531}
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=47:F8:A8:ED:2D:D3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=272392776531}
03-31 10:14:02.798  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:02.798 11157 11167 D ScanRecord: parseFromBytes
03-31 10:14:02.798 11157 11167 D ScanRecord: parseFromBytes
03-31 10:14:02.803 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-31 10:14:02.803 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-31 10:14:02.803 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-31 10:14:02.803 11157 11157 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-31 10:14:02.823 11157 11220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61,
03-31 10:14:02.823 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 10:14:02.828  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 10:14:02.828  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 10:14:02.828  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 10:14:02.838  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
03-31 10:14:02.838 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-31 10:14:02.838 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-31 10:14:02.838 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-31 10:14:02.838 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
03-31 10:14:02.838 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
03-31 10:14:02.838 11157 11220 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,03-31 10:14:02.843 11157 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 1563)
,03-31 10:14:02.843  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 10:14:02.848 11157 11813 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-31 10:14:02.848 11157 11813 D BluetoothSocket: connect(): myUserId = 0
03-31 10:14:02.848 11157 11813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:02.853  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-31 10:14:02.853  5920  5933 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 10:14:02.853  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-31 10:14:02.853 11157 11813 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-31 10:14:02.858  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
,03-31 10:14:02.888  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.893  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.898  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.898  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.903  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.903  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:02.903  5920  6100 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
03-31 10:14:02.903  5920  6100 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x45
,03-31 10:14:02.923  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 10:14:03.188  5920  6100 W bt-sdp  : process_service_search_attr_rsp
,03-31 10:14:03.813  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:03.818  5920  5920 D BtGatt.ScanManager: awakened up at time 273412
03-31 10:14:03.823  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:03.823  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:14:03.828  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: current time is 273420346115
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: Batch record : [-49, -106, -99, 28, -117, 71, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -45, 45, -19, -88, -8, 71, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:14:03.828  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:03.828  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=47:F8:A8:ED:2D:D3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=273370593531}
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: result: ScanResult{mDevice=47:8B:1C:9D:96:CF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=273370593531}
03-31 10:14:03.828  5920  5987 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:03.828 11157 11169 D ScanRecord: parseFromBytes
03-31 10:14:03.828 11157 11169 D ScanRecord: parseFromBytes
03-31 10:14:03.828 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-31 10:14:03.828 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:14:04.248  5920  6100 W bt-btif : new conn_srvc id:26, app_id:1
,03-31 10:14:04.253  5920  5931 E BluetoothRemoteDevices: setRfcommConnected true
,03-31 10:14:04.268 11157 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1563),
,03-31 10:14:04.273 11157 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1563)
,03-31 10:14:04.283 11157 11813 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:14:04.288 11157 11813 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 10:14:04.288 11157 11813 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1564)
03-31 10:14:04.288 11157 11813 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1564)
03-31 10:14:04.288 11157 11813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1563),
03-31 10:14:04.288 11157 11823 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1564)
,03-31 10:14:04.443  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:04.448  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:04.448  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:04.448  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:04.603  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:04.603  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:04.603  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:04.608  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:04.608 11157 11823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1564)
03-31 10:14:04.608 11157 11823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:CF:C5:D9:E5:61]
,03-31 10:14:04.613 11157 11823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1563),
03-31 10:14:04.618 11157 11823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:CF:C5:D9:E5:61] (thread ID: 1563),
,03-31 10:14:04.623 11157 11157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61],
03-31 10:14:04.623 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:14:04.623 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:14:04.628 11157 11823 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1564),
,03-31 10:14:04.638 11157 11157 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-31 10:14:04.643 11157 11157 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 10:14:04.643 11157 11157 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-31 10:14:04.643 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:04.648 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:04.653  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:04.653  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:04.653  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:14:04.653  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:14:04.658  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:14:04.658  5920  5987 D BtGatt.GattService: Client app is not null!
,03-31 10:14:04.658  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 10:14:04.663 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:04.663 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:14:04.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:04.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:04.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 10:14:04.663 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:04.663 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.663 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.663 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:04.673  5920  5933 D BtGatt.GattService: registerClient() - UUID=d40164e0-52be-4598-9364-93bd2f3dbdc5,
,03-31 10:14:04.713  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=d40164e0-52be-4598-9364-93bd2f3dbdc5, clientIf=7
,03-31 10:14:04.713 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:14:04.728  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 30
,03-31 10:14:04.728  5920  6013 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:04.728  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:04.728  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:14:04.728  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:14:04.728  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:14:04.733  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:04.733  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:04.733  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:04.733  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:14:04.733  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-31 10:14:04.733 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:04.738  5920  6017 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:04.738  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:04.738  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 15
,03-31 10:14:04.738  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:04.738 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:04.738 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.738 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:04.738 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:04.738 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:04.738 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:04.738  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:04.738  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.738  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:04.743  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-31 10:14:04.743  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.743  5920  5933 D BtGatt.GattService: registerClient() - UUID=4d71bf5e-2619-4306-9d50-9e60999191f2
03-31 10:14:04.743  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:14:04.743  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=5
,03-31 10:14:04.743  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: current time is 274340090365
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: Batch record : [-49, -106, -99, 28, -117, 71, 1, -128, -62, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -45, 45, -19, -88, -8, 71, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 8, -77, 94, -107, 109, 110, 1, -128, -54, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 3, 56, -30, 35, 48, 113, 1, -128, -67, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, -101, -93, -56, 79, 31, 76, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 10:14:04.748  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:04.748  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:14:04.748  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:14:04.748  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:04.748  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-31 10:14:04.748  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:14:04.783  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=4d71bf5e-2619-4306-9d50-9e60999191f2, clientIf=6
,03-31 10:14:04.783 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:04.783  5920 11743 D BtGatt.GattService: start scan with filters
,03-31 10:14:04.803  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 36
,03-31 10:14:04.803 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:04.803 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:04.803 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:04.808 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-31 10:14:04.808  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:04.808  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:04.808  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:04.808  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:04.813  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:04.813  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:14:04.813  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:04.813  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.813  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:04.813  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:04.813  5920  6014 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-31 10:14:04.818  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
03-31 10:14:04.818  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:04.818  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:04.818  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:04.818  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:04.823  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 10:14:04.823  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:14:04.823  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:14:04.823 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:04.823  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:04.823  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.823 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 10:14:04.828 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:04.828 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:04.828 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:04.828 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:04.828 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.828 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:04.828 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:04.828  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:04.828  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:04.838  5920  5933 D BtGatt.GattService: registerClient() - UUID=d3d3e7d8-74d6-4083-94ab-1afad859c3d2,
,03-31 10:14:04.883  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=d3d3e7d8-74d6-4083-94ab-1afad859c3d2, clientIf=7
,03-31 10:14:04.883 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:14:04.908  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 31
,03-31 10:14:04.908  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:04.913  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:04.913  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:14:04.918  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:14:04.918  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:14:04.923  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:04.928  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:04.928  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:04.933  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
,03-31 10:14:04.933  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 10:14:04.933 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-31 10:14:04.938  5920 11743 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:14:04.938  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:04.938  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 3
03-31 10:14:04.938  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-31 10:14:04.938  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:14:04.938  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:04.943  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:04.943  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.943  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:04.943  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:04.943  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:04.943  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:04.948 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:04.948 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:04.948 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:04.948 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:04.948 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:04.948 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:04.953  5920  5933 D BtGatt.GattService: registerClient() - UUID=103f1039-5a49-4898-944d-c6f9b0f27f0b
,03-31 10:14:04.993  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=103f1039-5a49-4898-944d-c6f9b0f27f0b, clientIf=6
,03-31 10:14:04.993 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:04.993  5920  6017 D BtGatt.GattService: start scan with filters
,03-31 10:14:05.008  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 37
,03-31 10:14:05.008 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-31 10:14:05.008  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:05.008  5920  6014 D BtGatt.ScanManager: isFilteringSupported
,03-31 10:14:05.008  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:05.008 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:05.008  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:05.008  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:05.008  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:05.008  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:05.008  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:14:05.013  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:05.013  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:05.013  5920  6014 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-31 10:14:05.013  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:14:05.013  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 10:14:05.013  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.013  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:05.013  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:05.013  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:14:05.013  5920  5987 D BtGatt.GattService: Client app is not null!
,03-31 10:14:05.018  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:14:05.018  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:05.018  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.018  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:05.018  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.018 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:05.018 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-31 10:14:05.018 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-31 10:14:05.018 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:05.018 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:05.018 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:05.018 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:14:05.023 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:05.023 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:05.033  5920  5933 D BtGatt.GattService: registerClient() - UUID=aa40133f-2ee5-4879-af55-d60e677e26b3,
,03-31 10:14:05.048 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c9e5eb8, channel: 7, state: CLOSED
,03-31 10:14:05.048 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179cc3d2, channel: 6, state: CLOSED
03-31 10:14:05.048 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d79e32b, channel: 6, state: CLOSED
03-31 10:14:05.048 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@322a4fff, channel: 6, state: CLOSED
03-31 10:14:05.048 11157 11166 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13c2e8cd, channel: 6, state: CLOSED
,03-31 10:14:05.073  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=aa40133f-2ee5-4879-af55-d60e677e26b3, clientIf=7,
,03-31 10:14:05.073 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-31 10:14:05.093  5920  6017 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 32
,03-31 10:14:05.093  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:05.098  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:05.098  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:14:05.098  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:14:05.098  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:14:05.108  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:05.108  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:05.113  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:05.113  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-31 10:14:05.113  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-31 10:14:05.113 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:05.118  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:05.118  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:05.118  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 4
03-31 10:14:05.118  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:05.118  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:05.118  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:05.118  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:05.123  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:05.123  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.123 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:05.123 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:05.123 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:05.123 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:05.123 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:05.123 11157 11157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-31 10:14:05.123  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:05.123  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-31 10:14:05.123  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.123  5920  5987 D BtGatt.GattService: current time is 274719684823
03-31 10:14:05.123  5920  5987 D BtGatt.GattService: Batch record : [-45, 45, -19, -88, -8, 71, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-31 10:14:05.123  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:05.123  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:05.128  5920  5931 D BtGatt.GattService: registerClient() - UUID=e898b5af-ec12-4f9f-9ae1-df473144fb19
,03-31 10:14:05.173  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=e898b5af-ec12-4f9f-9ae1-df473144fb19, clientIf=6
,03-31 10:14:05.173 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:05.173  5920 11743 D BtGatt.GattService: start scan with filters
,03-31 10:14:05.183  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 38
,03-31 10:14:05.183 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:05.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:05.183  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:05.183  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:05.183  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:05.183 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
03-31 10:14:05.183 11157 11157 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-31 10:14:05.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:05.183 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:05.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:05.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:05.183 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:14:05.183 11157 11847 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1565)
03-31 10:14:05.183 11157 11847 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37212
03-31 10:14:05.183 11157 11847 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-31 10:14:05.183 11157 11847 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37212 (peer ID: F8:CF:C5:D9:E5:61)
03-31 10:14:05.183  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:05.183  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.183 11157 11847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:CF:C5:D9:E5:61" removed
03-31 10:14:05.183  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:05.183  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:05.183  5920  6014 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-31 10:14:05.188  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:05.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.188  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:05.188  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:05.188 11157 11220 I jxcore-log: INFO testThaliMobileNative: 
03-31 10:14:05.188 11157 11220 I jxcore-log: 
,03-31 10:14:05.188  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:05.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:05.188 11157 11220 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-31 10:14:05.188 11157 11220 I jxcore-log: 
,03-31 10:14:05.188  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:05.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:05.193 11157 11847 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 37212
03-31 10:14:05.193 11157 11847 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-31 10:14:05.193 11157 11847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:05.193 11157 11847 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:05.193 11157 11847 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1565)
03-31 10:14:05.193 11157 11847 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1565)
,03-31 10:14:05.193 11157 11848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1566, name: Sender)
,03-31 10:14:05.193 11157 11849 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1567, name: Receiver)
,03-31 10:14:05.193 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-31 10:14:05.193 11157 11220 I jxcore-log: 
,03-31 10:14:05.198  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:05.198  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:05.198  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:05.198  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:05.228  5920  6100 W bt-btif : new conn_srvc id:26, app_id:255
,03-31 10:14:05.228 11157 11806 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@26e9f2a6
,03-31 10:14:05.228  5920  5933 E BluetoothRemoteDevices: setRfcommConnected true
03-31 10:14:05.228 11157 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-31 10:14:05.228 11157 11806 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:14:05.238 11157 11806 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-31 10:14:05.243 11157 11806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1568)
03-31 10:14:05.243 11157 11806 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2bef14e7, channel: 6, state: LISTENING
,03-31 10:14:05.243 11157 11806 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2bef14e7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@246765fc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ed47894mSocket: android.net.LocalSocket@33ac9f3d impl:android.net.LocalSocketImpl@3f329332 fd:FileDescriptor[93]
03-31 10:14:05.243 11157 11806 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33ac9f3d impl:android.net.LocalSocketImpl@3f329332 fd:FileDescriptor[93]
03-31 10:14:05.243 11157 11850 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1568)
03-31 10:14:05.243 11157 11806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:14:05.253 11157 11806 D BluetoothSocket: bindListen(): myUserId = 0
,03-31 10:14:05.253 11157 11806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:05.253 11157 11806 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,03-31 10:14:05.253 11157 11806 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:14:05.253 11157 11806 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:14:05.258 11157 11806 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c0e1883
03-31 10:14:05.258 11157 11806 D BluetoothSocket: channel: 6
03-31 10:14:05.258 11157 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:05.308 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:05.308 11157 11220 I jxcore-log: 
,03-31 10:14:05.393 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:05.393 11157 11220 I jxcore-log: 
,03-31 10:14:05.453 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:05.453 11157 11220 I jxcore-log: 
,03-31 10:14:05.533 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:05.533 11157 11220 I jxcore-log: 
,03-31 10:14:05.603 11157 11220 I jxcore-log: INFO testThaliMobileNative: forwardData
03-31 10:14:05.603 11157 11220 I jxcore-log: 
,03-31 10:14:05.613 11157 11220 I jxcore-log: ok 177 received should match sent forward
03-31 10:14:05.613 11157 11220 I jxcore-log: 
,03-31 10:14:05.628 11157 11220 I jxcore-log: # teardown
03-31 10:14:05.628 11157 11220 I jxcore-log: 
,03-31 10:14:05.653  5920  6100 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 10:14:05.653  5920  6100 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 10:14:05.653  5920  6100 W bt-btif : bta_dm_acl_change(), event : 1
03-31 10:14:05.653  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 10:14:05.653  5920  5987 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-31 10:14:05.658  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-31 10:14:05.663  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-31 10:14:05.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 10:14:05.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-31 10:14:05.668  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED,
,03-31 10:14:05.683  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ee0b616 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{23c256f 5920:com.android.bluetooth/1002}
,03-31 10:14:05.683  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-31 10:14:05.688  5920  5920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f1a1d56
03-31 10:14:05.688  5920  5920 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 10:14:05.688  3420  4340 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-31 10:14:05.688  3420  4339 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:14:05.693  3420  4361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-31 10:14:05.698 10232 11856 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-31 10:14:05.698  5920  5920 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-31 10:14:05.703  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:05.703  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:05.703  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:05.703  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:05.713 11858 11858 E Zygote  : MountEmulatedStorage()
03-31 10:14:05.713 11858 11858 E Zygote  : v2
03-31 10:14:05.713 11858 11858 I libpersona: KNOX_SDCARD checking this for 10036
03-31 10:14:05.713 11858 11858 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:05.718 11858 11858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:05.718 11858 11858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:05.718  3420  3833 I ActivityManager: Start proc 11858:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
03-31 10:14:05.718 11858 11858 E Zygote  : accessInfo : 0
,03-31 10:14:05.718 11858 11858 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-31 10:14:05.723 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-31 10:14:05.723 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 10:14:05.728 10232 10232 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
,03-31 10:14:05.728 10232 10232 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 10:14:05.743 11858 11858 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:05.743 11858 11858 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:05.753  3420  4361 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ee0b616 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:05.763 11858 11858 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:05.833 11157 11850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1568)
,03-31 10:14:05.833 11157 11850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:14:05.833 11157 11850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1568)
03-31 10:14:05.833 11157 11850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1568
03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:05.833 11157 11850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1568)
03-31 10:14:05.833 11157 11850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:14:05.833 11157 11850 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1568)
03-31 10:14:05.833  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:05.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:14:05.833 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-31 10:14:05.838 11157 11157 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-31 10:14:05.838 11157 11157 D BluetoothSocket: getInputStream(): myUserId = 0
,03-31 10:14:05.843 11157 11157 D BluetoothSocket: getOutputStream(): myUserId = 0
03-31 10:14:05.843 11157 11157 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
,03-31 10:14:05.843 11157 11157 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-31 10:14:05.843 11157 11883 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1569)
,03-31 10:14:05.843  2872  3479 D EnterpriseController: netId is 0
03-31 10:14:05.843  2872  3479 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-31 10:14:05.848 11157 11883 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 43167,
03-31 10:14:05.848 11157 11883 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-31 10:14:05.848 11157 11883 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-31 10:14:05.848 11157 11883 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-31 10:14:05.848 11157 11887 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1570, name: Sender)
03-31 10:14:05.848 11157 11883 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1569)
03-31 10:14:05.848 11157 11883 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1569)
,03-31 10:14:05.848 11157 11888 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1571, name: Receiver)
,03-31 10:14:05.853 11858 11858 D HealthConsole: Service for HealthDataConsole is connected
,03-31 10:14:05.858  3420  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ee0b616 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:05.878 11858 11858 D HealthConsole: Service for HealthDataConsole is connected
,03-31 10:14:05.878  3420  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ee0b616 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:05.888  3420  3460 I ActivityManager: Killing 10125:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-31 10:14:05.893  3420  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1ee0b616 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{13fc4307 4129:com.google.android.googlequicksearchbox:search/u0a64},
,03-31 10:14:05.908  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-31 10:14:05.913  4129  4129 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-31 10:14:06.063  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:06.063  5920  6100 D IOP_DB_BT: db_query: result 1,
03-31 10:14:06.063  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.063  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.083  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:06.083  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.083  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.088  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.133  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.133  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.133  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.133  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.138  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.138  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.138  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.138  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.188  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:06.193  5920  5920 D BtGatt.ScanManager: awakened up at time 275786
,03-31 10:14:06.193  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:14:06.193  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:06.193  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.208  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.283  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61,
03-31 10:14:06.283  5920  6100 D IOP_DB_BT: db_query: result 1,
03-31 10:14:06.283  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.283  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.298  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.298  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.298  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-31 10:14:06.298  5920  6100 D IOP_DB_BT: db_query: result 1,
,03-31 10:14:06.348  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.348  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.348  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.348  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.363  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.368  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:06.368  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:06.368  5920  6100 D IOP_DB_BT: db_query: result 1
,03-31 10:14:06.673  3420  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 10:14:06.678  3420  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:14:06.678  3420  3651 D BatteryService: online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,03-31 10:14:06.678  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:14:06.688  3420  3420 I MotionRecognitionService: Plugged
03-31 10:14:06.688  3420  3420 D MotionRecognitionService:   cableConnection= 1,
03-31 10:14:06.688  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 10:14:06.688  3420  3420 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 10:14:06.693  3420  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,03-31 10:14:06.693  3420  3651 D BatteryService: stay LED for fully charged
,03-31 10:14:06.703  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:14:06.703  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 10:14:06.703  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:14:06.723  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 10:14:06.723  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:14:06.733  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:14:06.733  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:14:06.733  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:14:06.733  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:14:06.868  3420  6131 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:14), CUR = 55, LCD = 0
,03-31 10:14:07.198  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:07.208  5920  5920 D BtGatt.ScanManager: awakened up at time 276802
03-31 10:14:07.213  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:07.213  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:07.213  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:07.618  5920  6100 E bt-btm  : tBTM_SEC_DEV:0xb355429c rs_disc_pending=0
03-31 10:14:07.618  5920  6100 W bt-btif : bta_dm_acl_change(), event : 3
03-31 10:14:07.618  5920  6100 W bt-btif : bta_dm_check_av:0
,03-31 10:14:07.618  5920  5987 W bt-btif : btif_dm_cback : unhandled event (14),
,03-31 10:14:08.228  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:08.243  5920  5920 D BtGatt.ScanManager: awakened up at time 277838
03-31 10:14:08.253  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:08.253  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:08.253  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:08.533  5920  6100 W bt-btif : dm_pm_timer expires
03-31 10:14:08.533  5920  6100 W bt-btif : dm_pm_timer expires 0
03-31 10:14:08.533  5920  6100 W bt-btif : proc dm_pm_timer expires
,03-31 10:14:08.623  5920  6100 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:08.623  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:08.623  5920  6100 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-31 10:14:08.623  5920  6100 D IOP_DB_BT: db_query: result 1
03-31 10:14:08.623  5920  6282 W bt-btif : invalid rfc slot id: 16
03-31 10:14:08.623 11157 11849 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1567, thread name: Receiver): bt socket closed, read return: -1
03-31 10:14:08.623 11157 11849 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-31 10:14:08.623 11157 11849 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-31 10:14:08.623 11157 11849 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
,03-31 10:14:08.628  5920  6282 W bt-btif : invalid rfc slot id: 15,
03-31 10:14:08.633 11157 11888 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1571, thread name: Receiver): bt socket closed, read return: -1
,03-31 10:14:08.633 11157 11888 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected,
,03-31 10:14:08.633 11157 11888 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1,
03-31 10:14:08.633 11157 11849 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1565)
03-31 10:14:08.633 11157 11849 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1565)
03-31 10:14:08.633 11157 11849 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1948f239, channel: 5, state: CONNECTED
,03-31 10:14:08.643 11157 11849 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1948f239, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ef2b07e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e8fb9dfmSocket: android.net.LocalSocket@1f4e462c impl:android.net.LocalSocketImpl@1fbd78f5 fd:FileDescriptor[112]
03-31 10:14:08.643 11157 11849 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f4e462c impl:android.net.LocalSocketImpl@1fbd78f5 fd:FileDescriptor[112]
03-31 10:14:08.643 11157 11849 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1948f239, channel: 5, state: CLOSED,
,03-31 10:14:08.643 11157 11849 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1948f239, channel: 5, state: CLOSED
03-31 10:14:08.643 11157 11849 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:08.643 11157 11849 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
,03-31 10:14:08.643 11157 11849 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1567,
03-31 10:14:08.643 11157 11849 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-31 10:14:08.643 11157 11849 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1566
03-31 10:14:08.643 11157 11849 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1565)
03-31 10:14:08.643 11157 11848 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1566, thread name: Sender): Socket closed
03-31 10:14:08.643 11157 11848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1566, name: Sender)
03-31 10:14:08.648 11157 11849 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1565)
,03-31 10:14:08.648 11157 11849 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-31 10:14:08.653 11157 11888 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1569
03-31 10:14:08.653 11157 11888 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1569)
03-31 10:14:08.653 11157 11888 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@105568a, channel: 6, state: CONNECTED
03-31 10:14:08.653 11157 11888 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@105568a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@86014fb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c6f9918mSocket: android.net.LocalSocket@cb9af71 impl:android.net.LocalSocketImpl@20ea5156 fd:FileDescriptor[115]
03-31 10:14:08.653 11157 11888 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@cb9af71 impl:android.net.LocalSocketImpl@20ea5156 fd:FileDescriptor[115]
03-31 10:14:08.653 11157 11888 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@105568a, channel: 6, state: CLOSED
03-31 10:14:08.653 11157 11888 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@105568a, channel: 6, state: CLOSED
03-31 10:14:08.653 11157 11888 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-31 10:14:08.653 11157 11888 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-31 10:14:08.653 11157 11888 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1571
03-31 10:14:08.653 11157 11888 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-31 10:14:08.653 11157 11888 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1570
03-31 10:14:08.653 11157 11888 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1569)
03-31 10:14:08.653 11157 11887 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1570, thread name: Sender): Socket closed
03-31 10:14:08.653 11157 11887 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1570, name: Sender)
03-31 10:14:08.658 11157 11888 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1569)
03-31 10:14:08.658 11157 11888 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-31 10:14:08.658 11157 11888 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1571, name: Receiver)
03-31 10:14:08.658 11157 11849 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1567, name: Receiver)
,03-31 10:14:08.663 11157 11220 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-31 10:14:08.663 11157 11220 I jxcore-log: 
03-31 10:14:08.663 11157 11220 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-31 10:14:08.663 11157 11220 I jxcore-log: 
,03-31 10:14:09.258  3420  3619 V AlarmManager: waitForAlarm result :4
,03-31 10:14:09.273  5920  5920 D BtGatt.ScanManager: awakened up at time 278866
,03-31 10:14:09.278  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:09.283  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:09.283  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:09.368 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:09.368 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:09.368 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-31 10:14:09.368 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:09.373  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:09.373  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:09.373  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 5
,03-31 10:14:09.373  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-31 10:14:09.373  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:09.373  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:09.373 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:09.373  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:09.373 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:14:09.373 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:09.373 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:09.373 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:09.373 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:09.378 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:09.378 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-31 10:14:09.378 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:09.378 11157 11220 I jxcore-log: ok 178 Should be able to call stopListeningForAdvertisments in teardown
03-31 10:14:09.378 11157 11220 I jxcore-log: 
,03-31 10:14:09.378  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:09.378  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:09.378 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:09.378  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:09.378 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:09.378 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:09.378 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:14:09.378 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:09.378 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@271105d7, channel: 6, state: LISTENING
03-31 10:14:09.378 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@271105d7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c0e1883, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d512ec4mSocket: android.net.LocalSocket@3768d1ad impl:android.net.LocalSocketImpl@20522ce2 fd:FileDescriptor[116]
03-31 10:14:09.378 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3768d1ad impl:android.net.LocalSocketImpl@20522ce2 fd:FileDescriptor[116]
03-31 10:14:09.378 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:09.378 11157 11806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:09.378 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:14:09.378 11157 11806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:09.378 11157 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:09.378 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:09.378 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:09.378 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:09.378 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-31 10:14:09.378  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:09.378  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:09.378 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:14:09.378 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:09.383 11157 11220 D BluetoothLeScanner: could not find callback wrapper
03-31 10:14:09.383 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:09.383 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:09.383  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:09.383  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:09.383  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:14:09.383  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:14:09.383  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:14:09.383  5920  5987 D BtGatt.GattService: Client app is not null!
,03-31 10:14:09.388  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:09.388 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:09.388 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:09.388 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:09.388 11157 11220 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-31 10:14:09.388 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:09.388 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:09.388 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:09.388 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:14:09.393 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:09.393 11157 11220 I jxcore-log: 
,03-31 10:14:09.393 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:09.398 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-31 10:14:09.398 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:09.398 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:09.403 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:14:09.403 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:09.403 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:09.403 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:09.403 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:09.408 11157 11220 I jxcore-log: ok 179 Should be able to call stopAdvertisingAndListening in teardown
03-31 10:14:09.408 11157 11220 I jxcore-log: 
,03-31 10:14:09.413 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:09.413 11157 11220 I jxcore-log: 
,03-31 10:14:09.413 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:09.413 11157 11220 I jxcore-log: 
,03-31 10:14:09.418 11157 11220 I jxcore-log: # setup
03-31 10:14:09.418 11157 11220 I jxcore-log: 
,03-31 10:14:09.633 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:09.633 11157 11220 I jxcore-log: 
,03-31 10:14:09.638 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:09.638 11157 11220 I jxcore-log: 
,03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:09.648 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:09.653 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:09.653 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:09.653 11157 11220 I jxcore-log: 
,03-31 10:14:09.658 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:09.658 11157 11220 I jxcore-log: 
,03-31 10:14:09.663 11157 11220 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-31 10:14:09.663 11157 11220 I jxcore-log: 
,03-31 10:14:09.663 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:09.663 11157 11220 I jxcore-log: 
,03-31 10:14:10.518 11157 11220 I jxcore-log: ok 180 specific error should be returned
03-31 10:14:10.518 11157 11220 I jxcore-log: 
,03-31 10:14:10.523 11157 11220 I jxcore-log: # teardown
03-31 10:14:10.523 11157 11220 I jxcore-log: 
,03-31 10:14:10.673 11157 11220 I jxcore-log: ok 181 must be stopped
03-31 10:14:10.673 11157 11220 I jxcore-log: 
,03-31 10:14:10.678 11157 11220 I jxcore-log: # setup
03-31 10:14:10.678 11157 11220 I jxcore-log: 
,03-31 10:14:10.898 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:10.898 11157 11220 I jxcore-log: 
,03-31 10:14:10.898 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:10.898 11157 11220 I jxcore-log: 
,03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:10.918 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:10.918 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:10.923 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:10.923 11157 11220 I jxcore-log: 
,03-31 10:14:10.923 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:10.923 11157 11220 I jxcore-log: 
,03-31 10:14:10.928 11157 11220 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-31 10:14:10.928 11157 11220 I jxcore-log: 
,03-31 10:14:10.933 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:10.933 11157 11220 I jxcore-log: 
,03-31 10:14:11.168 11157 11220 I jxcore-log: ok 182 specific error should be returned
03-31 10:14:11.168 11157 11220 I jxcore-log: 
,03-31 10:14:11.178 11157 11220 I jxcore-log: # teardown
03-31 10:14:11.178 11157 11220 I jxcore-log: 
,03-31 10:14:11.938 11157 11220 I jxcore-log: ok 183 must be stopped
03-31 10:14:11.938 11157 11220 I jxcore-log: 
,03-31 10:14:11.943 11157 11220 I jxcore-log: # setup
03-31 10:14:11.943 11157 11220 I jxcore-log: 
,03-31 10:14:12.583 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:12.583 11157 11220 I jxcore-log: 
,03-31 10:14:12.583 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:12.583 11157 11220 I jxcore-log: 
,03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:12.593 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:12.598 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:12.603 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:12.603 11157 11220 I jxcore-log: 
,03-31 10:14:12.603 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:12.603 11157 11220 I jxcore-log: 
,03-31 10:14:12.608 11157 11220 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-31 10:14:12.608 11157 11220 I jxcore-log: 
,03-31 10:14:12.613 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:12.613 11157 11220 I jxcore-log: 
,03-31 10:14:12.638  5920  6100 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-31 10:14:12.638  5920  6100 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-31 10:14:12.638  5920  6100 W bt-btif : bta_dm_acl_change(), event : 1
03-31 10:14:12.638  5920  6100 W bt-btif : bta_dm_acl_change(), event : 2
,03-31 10:14:12.638  5920  5987 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
,03-31 10:14:12.648  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-31 10:14:12.648  5920  5987 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-31 10:14:12.648  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-31 10:14:12.648  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-31 10:14:12.648  3420  3420 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-31 10:14:12.653  3420  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6157720 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{23c256f 5920:com.android.bluetooth/1002}
,03-31 10:14:12.658  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
03-31 10:14:12.658  3420  4011 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-31 10:14:12.658  5920  5920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f1a1d56
03-31 10:14:12.658  5920  5920 D BtConfig.SecureMode: isSecureModeOn:false
,03-31 10:14:12.658  3420  3651 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-31 10:14:12.668 10232 11937 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-31 10:14:12.673  3420  4340 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-31 10:14:12.673  5920  5920 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-31 10:14:12.673 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-31 10:14:12.673 10232 10232 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-31 10:14:12.678 10232 10232 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-31 10:14:12.678 10232 10232 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-31 10:14:12.678  3420  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6157720 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:12.688  3420  3460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6157720 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:12.698  3420  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6157720 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{117c0184 11858:com.sec.android.app.shealth/u0a36}
,03-31 10:14:12.708  3420  3977 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6157720 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{13fc4307 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-31 10:14:12.713  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-31 10:14:12.713  4129  4129 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-31 10:14:13.123  3420  3863 E Watchdog: !@Sync 9 [03-31 10:14:13.127]
,03-31 10:14:13.378 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:13.378 11157 11220 I jxcore-log: 
,03-31 10:14:13.388 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 46967
03-31 10:14:13.388 11157 11220 I jxcore-log: 
,03-31 10:14:13.393 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:13.393 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.393 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.398 11157 11220 I jxcore-log: ok 184 no errors
03-31 10:14:13.398 11157 11220 I jxcore-log: 
,03-31 10:14:13.403 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:13.403 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.403 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.408 11157 11220 I jxcore-log: ok 185 still no errors
03-31 10:14:13.408 11157 11220 I jxcore-log: 
,03-31 10:14:13.413 11157 11220 I jxcore-log: # teardown
03-31 10:14:13.413 11157 11220 I jxcore-log: 
,03-31 10:14:13.563 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:13.563 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:13.563 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.568 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:13.568 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:13.568 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:13.578 11157 11220 I jxcore-log: ok 186 must be stopped
03-31 10:14:13.578 11157 11220 I jxcore-log: 
,03-31 10:14:13.593 11157 11220 I jxcore-log: # setup
03-31 10:14:13.593 11157 11220 I jxcore-log: 
,03-31 10:14:13.713 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:13.713 11157 11220 I jxcore-log: 
,03-31 10:14:13.733 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:13.733 11157 11220 I jxcore-log: 
,03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:13.743 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:13.748 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:13.753 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:13.753 11157 11220 I jxcore-log: 
,03-31 10:14:13.758 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:13.758 11157 11220 I jxcore-log: 
,03-31 10:14:13.763 11157 11220 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-31 10:14:13.763 11157 11220 I jxcore-log: 
,03-31 10:14:13.763 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:13.763 11157 11220 I jxcore-log: 
,03-31 10:14:13.978 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:13.978 11157 11220 I jxcore-log: 
,03-31 10:14:13.983 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 51475
03-31 10:14:13.983 11157 11220 I jxcore-log: 
,03-31 10:14:13.988 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 43167, start advertisements: false
,03-31 10:14:13.988 11157 11220 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-31 10:14:13.988 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:13.993 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-31 10:14:13.998 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:14.003 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:14.003 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.008 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:14:14.008 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:14:14.008 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:14:14.013 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:14:14.013 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:14.018  5920  6017 D BtGatt.GattService: registerClient() - UUID=b5edcdd8-ad96-4008-9744-48006e38ece8
,03-31 10:14:14.063  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=b5edcdd8-ad96-4008-9744-48006e38ece8, clientIf=6
,03-31 10:14:14.063 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:14.063  5920 11743 D BtGatt.GattService: start scan with filters
,03-31 10:14:14.078  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 39
,03-31 10:14:14.078 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:14.078 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:14.078 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:14.078 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:14.078 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:14.078  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:14.078  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:14.078  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:14.078 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:14.078 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:14.078 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:14.083 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:14.083 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:14.083 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:14:14.083 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:14.083 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:14.083  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:14.083  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.083  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:14.083  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:14.083  5920  6014 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-31 10:14:14.083 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.083 11157 11220 I jxcore-log: 
,03-31 10:14:14.083  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:14.083  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:14.083  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:14.083  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:14:14.083 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.083 11157 11220 I jxcore-log: 
,03-31 10:14:14.088  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-31 10:14:14.088  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:14.088 11157 11220 I jxcore-log: ok 187 no errors
03-31 10:14:14.088 11157 11220 I jxcore-log: 
,03-31 10:14:14.088  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:14.088  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.093 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 43167, start advertisements: false,
03-31 10:14:14.093 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.093 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:14.093 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:14.093 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.093 11157 11220 I jxcore-log: ok 188 still no errors
03-31 10:14:14.093 11157 11220 I jxcore-log: 
,03-31 10:14:14.103 11157 11220 I jxcore-log: # teardown
03-31 10:14:14.103 11157 11220 I jxcore-log: 
,03-31 10:14:14.283 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-31 10:14:14.283 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-31 10:14:14.283 11157 11220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-31 10:14:14.283 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:14:14.283 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:14.283 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:14.283 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:14.288 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:14.288 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:14.288  5920  5933 D BtGatt.GattService: stopScan() - queue size =1,
03-31 10:14:14.293  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:14.293  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 6
03-31 10:14:14.293  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-31 10:14:14.293  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-31 10:14:14.293  5920  6014 D BtGatt.ScanManager: stopping BLe Batch,
03-31 10:14:14.298  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 10:14:14.298  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:14:14.298  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:14.298  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:14.298  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:14:14.303  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:14.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-31 10:14:14.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-31 10:14:14.303 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:14.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:14:14.303 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:14:14.303 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:14.308 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:14.308 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:14.308 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:14.308 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:14.308 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:14.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:14.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:14.308 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-31 10:14:14.318 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:14.323 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:14.323 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:14.323 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-31 10:14:14.333 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:14:14.333 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:14.333 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:14.333 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:14.333 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:14.333 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:14.333 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:14.343 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:14.343 11157 11220 I jxcore-log: 
,03-31 10:14:14.343 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:14.343 11157 11220 I jxcore-log: 
,03-31 10:14:14.348 11157 11220 I jxcore-log: ok 189 must be stopped
03-31 10:14:14.348 11157 11220 I jxcore-log: 
,03-31 10:14:14.358 11157 11220 I jxcore-log: # setup
03-31 10:14:14.358 11157 11220 I jxcore-log: 
,03-31 10:14:14.523 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:14.523 11157 11220 I jxcore-log: 
,03-31 10:14:14.528 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:14.528 11157 11220 I jxcore-log: 
,03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:14.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:14.538 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:14.543 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:14.543 11157 11220 I jxcore-log: 
,03-31 10:14:14.548 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:14.548 11157 11220 I jxcore-log: 
,03-31 10:14:14.553 11157 11220 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-31 10:14:14.553 11157 11220 I jxcore-log: 
,03-31 10:14:14.553 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:14.553 11157 11220 I jxcore-log: 
,03-31 10:14:14.728 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:14.728 11157 11220 I jxcore-log: 
,03-31 10:14:14.728 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 55821
03-31 10:14:14.728 11157 11220 I jxcore-log: 
,03-31 10:14:14.738 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 55821, start advertisements: true
,03-31 10:14:14.738 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.738 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:14.738 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:14.738 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:14:14.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:14.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-31 10:14:14.743 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:14.748  5920  6017 D BtGatt.GattService: registerClient() - UUID=86f4e58e-a7c5-4106-a817-e65955123f25
,03-31 10:14:14.793  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=86f4e58e-a7c5-4106-a817-e65955123f25, clientIf=6
03-31 10:14:14.793 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:14:14.793  5920 11743 D BtGatt.GattService: start scan with filters
,03-31 10:14:14.823  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 40
,03-31 10:14:14.823  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:14.823  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:14.823  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:14:14.828  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:14.828  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.828  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:14.828  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:14.828  5920  6014 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-31 10:14:14.833  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:14.833  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.833  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
,03-31 10:14:14.833  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:14:14.838  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:14.838  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.838  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-31 10:14:14.838  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:14.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-31 10:14:14.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:14.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:14.843 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-31 10:14:14.843 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:14.848 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:14.848 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:14.848 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:14.848 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-31 10:14:14.848 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:14.848 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-31 10:14:14.848 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:14.848  5920  5931 D BtGatt.GattService: registerClient() - UUID=bcd975fa-f184-45a0-a0b7-b921b80c3a1e
,03-31 10:14:14.893  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=bcd975fa-f184-45a0-a0b7-b921b80c3a1e, clientIf=7,
03-31 10:14:14.893 11157 11169 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-31 10:14:14.908  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 33,
,03-31 10:14:14.908  5920  6013 D BtGatt.AdvertiseManager: message : 0,
03-31 10:14:14.908  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:14.908  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
03-31 10:14:14.908  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:14:14.908  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-31 10:14:14.913  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:14.918  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:14.918  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:14.923  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:14:14.923  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 10:14:14.923 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:14.923 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:14:14.923 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:14.923 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:14.923 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:14.923 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 10:14:14.928 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:14:14.928 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:14.928 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:14.928 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:14.928 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:14.928 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:14.928 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:14.928 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-31 10:14:14.928 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:14.928 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:14.928 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:14.928 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:14.928 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:14.928 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:14.928 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:14:14.928 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:14.928 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.928 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.928 11157 11220 I jxcore-log: 
,03-31 10:14:14.933 11157 11964 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:14:14.933 11157 11964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:14.933 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:14.933 11157 11220 I jxcore-log: 
,03-31 10:14:14.933 11157 11964 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-31 10:14:14.933 11157 11964 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:14:14.933 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:14.933 11157 11220 I jxcore-log: 
03-31 10:14:14.933 11157 11964 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:14:14.933 11157 11964 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@259f8965
03-31 10:14:14.933 11157 11964 D BluetoothSocket: channel: 6
03-31 10:14:14.933 11157 11964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:14.933 11157 11220 I jxcore-log: ok 190 no errors
03-31 10:14:14.933 11157 11220 I jxcore-log: 
,03-31 10:14:14.938 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 55821, start advertisements: true
,03-31 10:14:14.938 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:14.938 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:14.938 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:14:14.938 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:14.943 11157 11220 I jxcore-log: ok 191 still no errors
03-31 10:14:14.943 11157 11220 I jxcore-log: 
,03-31 10:14:14.948 11157 11220 I jxcore-log: # teardown
03-31 10:14:14.948 11157 11220 I jxcore-log: 
,03-31 10:14:15.168 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-31 10:14:15.168 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-31 10:14:15.168 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections,
,03-31 10:14:15.168 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-31 10:14:15.168 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,03-31 10:14:15.168 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9e8763a, channel: 6, state: LISTENING,
,03-31 10:14:15.168 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9e8763a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@259f8965, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36dc32ebmSocket: android.net.LocalSocket@77848 impl:android.net.LocalSocketImpl@198456e1 fd:FileDescriptor[112],
,03-31 10:14:15.168 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@77848 impl:android.net.LocalSocketImpl@198456e1 fd:FileDescriptor[112],
,03-31 10:14:15.168 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-31 10:14:15.173 11157 11964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
,03-31 10:14:15.173 11157 11964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
,03-31 10:14:15.173 11157 11964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:15.173 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-31 10:14:15.173 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-31 10:14:15.173 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
,03-31 10:14:15.173 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-31 10:14:15.173 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:15.173 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:15.173 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:14:15.173 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:15.173 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:15.178  5920  6017 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:15.178  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:15.178  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 7
,03-31 10:14:15.183  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:15.183  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:15.183  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:15.188  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:15.188  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:15.188  5920 11743 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:15.188  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-31 10:14:15.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:15.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:15.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:15.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:15.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-31 10:14:15.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-31 10:14:15.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-31 10:14:15.193  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-31 10:14:15.193  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:15.193  5920  5987 D BtGatt.GattService: current time is 284787831658
,03-31 10:14:15.193  5920  5987 D BtGatt.GattService: Batch record : [-126, -74, -2, 9, 66, 121, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -1, -91, 53, -16, 29, 104, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
03-31 10:14:15.193  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-31 10:14:15.193  5920  5987 D ScanRecord: parseFromBytes
,03-31 10:14:15.193  5920  5987 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-31 10:14:15.193  5920  5987 D ScanRecord: parseFromBytes
03-31 10:14:15.198  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:15.198  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:15.198  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:14:15.203  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-31 10:14:15.203  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:14:15.203  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-31 10:14:15.203  5920  6017 D BtGatt.GattService: unregisterClient() - clientIf=7
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-31 10:14:15.208 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:15.208 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:15.208 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-31 10:14:15.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:15.213 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.213 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:15.213 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:15.213 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:15.213 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:15.218 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-31 10:14:15.223 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-31 10:14:15.223 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:15.223 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:15.223 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:15.223 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:15.223 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-31 10:14:15.233 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:15.233 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:15.233 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:15.238 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:15.238 11157 11220 I jxcore-log: 
,03-31 10:14:15.238 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:15.238 11157 11220 I jxcore-log: 
03-31 10:14:15.238 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:15.238 11157 11220 I jxcore-log: 
,03-31 10:14:15.253 11157 11220 I jxcore-log: ok 192 must be stopped
03-31 10:14:15.253 11157 11220 I jxcore-log: 
,03-31 10:14:15.288 11157 11220 I jxcore-log: # setup
03-31 10:14:15.288 11157 11220 I jxcore-log: 
,03-31 10:14:15.438 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:15.438 11157 11220 I jxcore-log: 
,03-31 10:14:15.438 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:15.438 11157 11220 I jxcore-log: 
,03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:15.448 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:15.453 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:15.458 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:15.458 11157 11220 I jxcore-log: 
,03-31 10:14:15.458 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:15.458 11157 11220 I jxcore-log: 
,03-31 10:14:15.463 11157 11220 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-31 10:14:15.463 11157 11220 I jxcore-log: 
,03-31 10:14:15.468 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:15.468 11157 11220 I jxcore-log: 
,03-31 10:14:15.643 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:15.643 11157 11220 I jxcore-log: 
,03-31 10:14:15.648 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 54236
03-31 10:14:15.648 11157 11220 I jxcore-log: 
,03-31 10:14:15.653 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:15.653 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.653 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.658 11157 11220 I jxcore-log: ok 193 no errors
03-31 10:14:15.658 11157 11220 I jxcore-log: 
,03-31 10:14:15.658 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:15.658 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.658 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.663 11157 11220 I jxcore-log: ok 194 still no errors
03-31 10:14:15.663 11157 11220 I jxcore-log: 
,03-31 10:14:15.673 11157 11220 I jxcore-log: # teardown
03-31 10:14:15.673 11157 11220 I jxcore-log: 
,03-31 10:14:15.743 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:15.743 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:15.743 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.743 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:15.743 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:15.743 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:15.753 11157 11220 I jxcore-log: ok 195 must be stopped
03-31 10:14:15.753 11157 11220 I jxcore-log: 
,03-31 10:14:15.758 11157 11220 I jxcore-log: # setup
03-31 10:14:15.758 11157 11220 I jxcore-log: 
,03-31 10:14:15.868 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:15.868 11157 11220 I jxcore-log: 
,03-31 10:14:15.873 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:15.873 11157 11220 I jxcore-log: 
,03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:15.883 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:15.883 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:15.888 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:15.888 11157 11220 I jxcore-log: 
,03-31 10:14:15.888 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:15.888 11157 11220 I jxcore-log: 
,03-31 10:14:15.893 11157 11220 I jxcore-log: # 48. can get the network status before starting
03-31 10:14:15.893 11157 11220 I jxcore-log: 
,03-31 10:14:15.898 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:15.898 11157 11220 I jxcore-log: 
,03-31 10:14:16.043 11157 11220 I jxcore-log: ok 196 network status should have certain non-empty properties
03-31 10:14:16.043 11157 11220 I jxcore-log: 
,03-31 10:14:16.053 11157 11220 I jxcore-log: # teardown
03-31 10:14:16.053 11157 11220 I jxcore-log: 
,03-31 10:14:16.168 11157 11220 I jxcore-log: ok 197 must be stopped
03-31 10:14:16.168 11157 11220 I jxcore-log: 
,03-31 10:14:16.173 11157 11220 I jxcore-log: # setup
03-31 10:14:16.173 11157 11220 I jxcore-log: 
,03-31 10:14:16.323 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:16.323 11157 11220 I jxcore-log: 
,03-31 10:14:16.323 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:16.323 11157 11220 I jxcore-log: 
,03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:16.333 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:16.338 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:16.343 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:16.343 11157 11220 I jxcore-log: 
,03-31 10:14:16.348 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:16.348 11157 11220 I jxcore-log: 
,03-31 10:14:16.353 11157 11220 I jxcore-log: # 49. error returned with bad router
03-31 10:14:16.353 11157 11220 I jxcore-log: 
,03-31 10:14:16.353 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:16.353 11157 11220 I jxcore-log: 
,03-31 10:14:16.498 11157 11220 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-31 10:14:16.498 11157 11220 I jxcore-log: 
,03-31 10:14:16.503 11157 11220 I jxcore-log: ok 198 specific error expected
03-31 10:14:16.503 11157 11220 I jxcore-log: 
,03-31 10:14:16.508 11157 11220 I jxcore-log: # teardown
03-31 10:14:16.508 11157 11220 I jxcore-log: 
,03-31 10:14:16.608 11157 11220 I jxcore-log: ok 199 must be stopped
03-31 10:14:16.608 11157 11220 I jxcore-log: 
,03-31 10:14:16.613 11157 11220 I jxcore-log: # setup
03-31 10:14:16.613 11157 11220 I jxcore-log: 
,03-31 10:14:16.738 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:16.738 11157 11220 I jxcore-log: 
,03-31 10:14:16.748 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:16.748 11157 11220 I jxcore-log: 
,03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:16.758 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:16.763 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:16.768 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:16.768 11157 11220 I jxcore-log: 
,03-31 10:14:16.773 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:16.773 11157 11220 I jxcore-log: 
,03-31 10:14:16.783 11157 11220 I jxcore-log: # 50. all services are stopped when we call stop
03-31 10:14:16.783 11157 11220 I jxcore-log: 
,03-31 10:14:16.783 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:16.783 11157 11220 I jxcore-log: 
,03-31 10:14:16.808  3420  3463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 10:14:16.808  3420  3463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 10:14:16.808  3420  3463 D BatteryService: online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
03-31 10:14:16.808  3420  3463 D BatteryService: stay LED for fully charged
03-31 10:14:16.808  3420  3420 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 10:14:16.813  3420  3420 I MotionRecognitionService: Plugged
03-31 10:14:16.813  3420  3420 D MotionRecognitionService:   cableConnection= 1
03-31 10:14:16.813  3420  3420 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 10:14:16.813  3420  3420 D MotionRecognitionService: skip setTransmitPower. 
,03-31 10:14:16.813  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:14:16.813  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 10:14:16.813  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 10:14:16.823  5920  5920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 10:14:16.823  5920  6015 D HeadsetStateMachine: Disconnected process message: 10
,03-31 10:14:16.838  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 10:14:16.838  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:14:16.838  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 10:14:16.838  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 10:14:16.893  3420  6131 D SSRM:n  : SIOP:: AP = 270, PST = 279 (W:14), CUR = 52, LCD = 0
,03-31 10:14:16.918 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:16.918 11157 11220 I jxcore-log: 
,03-31 10:14:16.923 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 45155
03-31 10:14:16.923 11157 11220 I jxcore-log: 
,03-31 10:14:16.933 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 55821, start advertisements: false
,03-31 10:14:16.933 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:16.933 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:14:16.933 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:14:16.938 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:14:16.938 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:16.938 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:16.943  5920 11743 D BtGatt.GattService: registerClient() - UUID=0fd37ced-bb6a-4f8f-9168-d402a067e0f7
,03-31 10:14:16.988  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=0fd37ced-bb6a-4f8f-9168-d402a067e0f7, clientIf=6
03-31 10:14:16.988 11157 11169 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-31 10:14:16.988  5920  5931 D BtGatt.GattService: start scan with filters
,03-31 10:14:16.998  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 41
,03-31 10:14:16.998  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:16.998  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:16.998  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
,03-31 10:14:17.003  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:17.003  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:17.003  5920  6014 D BtGatt.ScanManager: allow scan with filters
03-31 10:14:17.003  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:17.003  5920  6014 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-31 10:14:17.008  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:17.008  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:17.008  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:17.008  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:17.008  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:17.008  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:17.013  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:17.013  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:17.018 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:17.018 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:17.018 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:17.018 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:17.018 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:17.018 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:17.018 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:17.023 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:17.023 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:17.023 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:17.023 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:17.023 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:17.023 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
,03-31 10:14:17.023 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:17.023 11157 11220 I jxcore-log: 
,03-31 10:14:17.028 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:17.028 11157 11220 I jxcore-log: 
,03-31 10:14:17.033 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 45155, start advertisements: true
03-31 10:14:17.033 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:17.033 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:17.033 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:17.033 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-31 10:14:17.033 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-31 10:14:17.033 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:17.033 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:17.033 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:17.033 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:17.033 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:17.033 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:17.038  5920  5931 D BtGatt.GattService: registerClient() - UUID=e6d6067a-dee0-496c-823c-cab991122706
,03-31 10:14:17.078  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=e6d6067a-dee0-496c-823c-cab991122706, clientIf=7
,03-31 10:14:17.078 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:14:17.098  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 34
,03-31 10:14:17.098  5920  6013 D BtGatt.AdvertiseManager: message : 0
,03-31 10:14:17.103  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:17.103  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
,03-31 10:14:17.108  5920  6013 D BtGatt.AdvertiseManager: starting advertising
,03-31 10:14:17.108  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-31 10:14:17.113  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-31 10:14:17.113  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
,03-31 10:14:17.118  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-31 10:14:17.118  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:14:17.118  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 10:14:17.118 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-31 10:14:17.118 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:17.118 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-31 10:14:17.118 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:17.118 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:17.118 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:17.118 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-31 10:14:17.123 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:14:17.123 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:17.123 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:17.123 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:17.123 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-31 10:14:17.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-31 10:14:17.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:17.128 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-31 10:14:17.128 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:17.133 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:17.133 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:17.133 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-31 10:14:17.133 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-31 10:14:17.138 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:17.138 11157 11220 I jxcore-log: 
,03-31 10:14:17.138 11157 12006 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:14:17.138 11157 12006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:17.143 11157 12006 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-31 10:14:17.143 11157 12006 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:14:17.143 11157 12006 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:14:17.143 11157 12006 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@268e801d
03-31 10:14:17.143 11157 12006 D BluetoothSocket: channel: 6
,03-31 10:14:17.143 11157 12006 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:17.148 11157 11220 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-31 10:14:17.148 11157 11220 I jxcore-log: 
,03-31 10:14:17.153 11157 11220 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-31 10:14:17.153 11157 11220 I jxcore-log: 
,03-31 10:14:17.153 11157 11220 I jxcore-log: DEBUG createNativeListener: new mux
03-31 10:14:17.153 11157 11220 I jxcore-log: 
,03-31 10:14:17.163 11157 11220 I jxcore-log: ok 200 connection to servers manager should succeed after starting
03-31 10:14:17.163 11157 11220 I jxcore-log: 
,03-31 10:14:17.188 11157 11220 I jxcore-log: ok 201 connection to router server should succeed after starting
03-31 10:14:17.188 11157 11220 I jxcore-log: 
,03-31 10:14:17.188 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:17.188 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:17.188 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:17.188 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-31 10:14:17.188 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:17.188 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9239292, channel: 6, state: LISTENING
03-31 10:14:17.188 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9239292, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@268e801d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29ba1463mSocket: android.net.LocalSocket@1e030860 impl:android.net.LocalSocketImpl@e180119 fd:FileDescriptor[112]
03-31 10:14:17.188 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e030860 impl:android.net.LocalSocketImpl@e180119 fd:FileDescriptor[112]
03-31 10:14:17.188 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-31 10:14:17.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:17.193 11157 12006 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:17.193 11157 12006 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:17.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:17.193 11157 12006 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:17.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-31 10:14:17.193 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:17.193 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-31 10:14:17.193 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:17.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:17.193 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:17.193 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-31 10:14:17.193  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:17.193  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:17.193  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 8
03-31 10:14:17.193  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:17.198  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:17.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:17.198  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:17.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:17.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:17.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-31 10:14:17.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:17.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-31 10:14:17.198 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:17.198 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-31 10:14:17.198  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:17.198  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:17.198  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:17.198  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:17.198  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:17.198  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-31 10:14:17.203  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 10:14:17.203  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:17.203  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:17.203  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 10:14:17.203  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:14:17.203  5920  5933 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-31 10:14:17.203 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:17.203 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:17.203 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:17.203 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:17.203 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:17.203 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:17.203 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:17.203 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-31 10:14:17.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:17.208 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:17.208 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:17.208 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:17.208 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:17.208 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:17.208 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:17.208 11157 11220 I jxcore-log: DEBUG createNativeListener: incoming socket close,
03-31 10:14:17.208 11157 11220 I jxcore-log: 
03-31 10:14:17.213 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:17.213 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:17.213 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:17.213 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:17.218 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:17.218 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:17.218 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-31 10:14:17.223 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-31 10:14:17.223 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:17.223 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:17.228 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:17.228 11157 11220 I jxcore-log: 
,03-31 10:14:17.228 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:17.228 11157 11220 I jxcore-log: 
,03-31 10:14:17.233 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-31 10:14:17.233 11157 11220 I jxcore-log: 
,03-31 10:14:17.238 11157 11220 I jxcore-log: ok 202 is stopped after calling stop
03-31 10:14:17.238 11157 11220 I jxcore-log: 
,03-31 10:14:17.243 11157 11220 I jxcore-log: ok 203 connection to servers manager should fail after stopping
03-31 10:14:17.243 11157 11220 I jxcore-log: 
,03-31 10:14:17.248 11157 11220 I jxcore-log: ok 204 connection to router server should fail after stopping
03-31 10:14:17.248 11157 11220 I jxcore-log: 
,03-31 10:14:17.253 11157 11220 I jxcore-log: # teardown
03-31 10:14:17.253 11157 11220 I jxcore-log: 
,03-31 10:14:17.673 11157 11220 I jxcore-log: ok 205 must be stopped
03-31 10:14:17.673 11157 11220 I jxcore-log: 
,03-31 10:14:17.678 11157 11220 I jxcore-log: # setup
03-31 10:14:17.678 11157 11220 I jxcore-log: 
,03-31 10:14:17.773 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:17.773 11157 11220 I jxcore-log: 
,03-31 10:14:17.778 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:17.778 11157 11220 I jxcore-log: 
,03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:17.788 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:17.788 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:17.793 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:17.793 11157 11220 I jxcore-log: 
,03-31 10:14:17.798 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:17.798 11157 11220 I jxcore-log: 
,03-31 10:14:17.798 11157 11220 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-31 10:14:17.798 11157 11220 I jxcore-log: 
,03-31 10:14:17.803 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:17.803 11157 11220 I jxcore-log: 
,03-31 10:14:18.043 11157 11220 I jxcore-log: ok 206 called with right arguments
03-31 10:14:18.043 11157 11220 I jxcore-log: 
,03-31 10:14:18.048 11157 11220 I jxcore-log: # teardown
03-31 10:14:18.048 11157 11220 I jxcore-log: 
,03-31 10:14:18.243 11157 11220 I jxcore-log: ok 207 must be stopped
03-31 10:14:18.243 11157 11220 I jxcore-log: 
,03-31 10:14:18.248 11157 11220 I jxcore-log: # setup
03-31 10:14:18.248 11157 11220 I jxcore-log: 
,03-31 10:14:18.528 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:18.528 11157 11220 I jxcore-log: 
,03-31 10:14:18.528 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:18.528 11157 11220 I jxcore-log: 
,03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:18.538 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:18.543 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:18.548 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:18.548 11157 11220 I jxcore-log: 
,03-31 10:14:18.548 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:18.548 11157 11220 I jxcore-log: 
,03-31 10:14:18.553 11157 11220 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-31 10:14:18.553 11157 11220 I jxcore-log: 
,03-31 10:14:18.558 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:18.558 11157 11220 I jxcore-log: 
,03-31 10:14:18.808 11157 11220 I jxcore-log: ok 208 called with right arguments
03-31 10:14:18.808 11157 11220 I jxcore-log: 
,03-31 10:14:18.813 11157 11220 I jxcore-log: # teardown
03-31 10:14:18.813 11157 11220 I jxcore-log: 
,03-31 10:14:19.848 11157 11220 I jxcore-log: ok 209 must be stopped
03-31 10:14:19.848 11157 11220 I jxcore-log: 
,03-31 10:14:19.858 11157 11220 I jxcore-log: # setup
03-31 10:14:19.858 11157 11220 I jxcore-log: 
,03-31 10:14:20.028 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:20.028 11157 11220 I jxcore-log: 
,03-31 10:14:20.033 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:20.033 11157 11220 I jxcore-log: 
,03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:20.043 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:20.043 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:20.048 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:20.048 11157 11220 I jxcore-log: 
,03-31 10:14:20.053 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:20.053 11157 11220 I jxcore-log: 
,03-31 10:14:20.058 11157 11220 I jxcore-log: # 53. make sure we actually call kill connections properly
03-31 10:14:20.058 11157 11220 I jxcore-log: 
,03-31 10:14:20.058 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:20.058 11157 11220 I jxcore-log: 
,03-31 10:14:20.698 11157 11220 I jxcore-log: ok 210 specific error expected
03-31 10:14:20.698 11157 11220 I jxcore-log: 
,03-31 10:14:20.703 11157 11220 I jxcore-log: # teardown
03-31 10:14:20.703 11157 11220 I jxcore-log: 
,03-31 10:14:20.728  3420  6162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 10:14:20.843 11157 11220 I jxcore-log: ok 211 must be stopped
03-31 10:14:20.843 11157 11220 I jxcore-log: 
,03-31 10:14:20.848 11157 11220 I jxcore-log: # setup
03-31 10:14:20.848 11157 11220 I jxcore-log: 
,03-31 10:14:21.208 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:21.208 11157 11220 I jxcore-log: 
,03-31 10:14:21.213 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:21.213 11157 11220 I jxcore-log: 
,03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:21.223 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:21.223 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:21.228 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:21.228 11157 11220 I jxcore-log: 
,03-31 10:14:21.233 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:21.233 11157 11220 I jxcore-log: 
,03-31 10:14:21.233 11157 11220 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-31 10:14:21.233 11157 11220 I jxcore-log: 
,03-31 10:14:21.238 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:21.238 11157 11220 I jxcore-log: 
,03-31 10:14:21.303  3420  3585 I PowerManagerService: [PWL] Off : 225s ago
,03-31 10:14:22.213 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:22.213 11157 11220 I jxcore-log: 
,03-31 10:14:22.218 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 45399
03-31 10:14:22.218 11157 11220 I jxcore-log: 
,03-31 10:14:22.228 11157 11220 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":42348,"error":{}}
03-31 10:14:22.228 11157 11220 I jxcore-log: 
,03-31 10:14:22.233 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:22.233 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:22.233 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:22.238 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:22.238 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:22.238 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:22.253 11157 11220 I jxcore-log: ok 212 failure reason is as expected
03-31 10:14:22.253 11157 11220 I jxcore-log: 
,03-31 10:14:22.253 11157 11220 I jxcore-log: ok 213 error description is as expected
03-31 10:14:22.253 11157 11220 I jxcore-log: 
,03-31 10:14:22.253 11157 11220 I jxcore-log: ok 214 must be stopped
03-31 10:14:22.253 11157 11220 I jxcore-log: 
,03-31 10:14:22.263 11157 11220 I jxcore-log: # teardown
03-31 10:14:22.263 11157 11220 I jxcore-log: 
,03-31 10:14:22.353 11157 11220 I jxcore-log: ok 215 must be stopped
03-31 10:14:22.353 11157 11220 I jxcore-log: 
,03-31 10:14:22.353 11157 11220 I jxcore-log: # setup
03-31 10:14:22.353 11157 11220 I jxcore-log: 
,03-31 10:14:23.113 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:23.113 11157 11220 I jxcore-log: 
,03-31 10:14:23.118 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:23.118 11157 11220 I jxcore-log: 
,03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:23.128 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:23.128 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:23.133 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:23.133 11157 11220 I jxcore-log: 
,03-31 10:14:23.138 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:23.138 11157 11220 I jxcore-log: 
,03-31 10:14:23.138 11157 11220 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-31 10:14:23.138 11157 11220 I jxcore-log: 
,03-31 10:14:23.143 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:23.143 11157 11220 I jxcore-log: 
,03-31 10:14:23.368 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:23.368 11157 11220 I jxcore-log: 
,03-31 10:14:23.373 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 41987
03-31 10:14:23.373 11157 11220 I jxcore-log: 
,03-31 10:14:23.378 11157 11220 I jxcore-log: ok 216 peerIdentifier matches
03-31 10:14:23.378 11157 11220 I jxcore-log: 
,03-31 10:14:23.378 11157 11220 I jxcore-log: ok 217 error description matches
03-31 10:14:23.378 11157 11220 I jxcore-log: 
,03-31 10:14:23.383 11157 11220 I jxcore-log: # teardown
03-31 10:14:23.383 11157 11220 I jxcore-log: 
,03-31 10:14:24.053 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:24.058 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.058 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.058 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:24.063 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.063 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.068 11157 11220 I jxcore-log: ok 218 must be stopped
03-31 10:14:24.068 11157 11220 I jxcore-log: 
,03-31 10:14:24.078 11157 11220 I jxcore-log: # setup
03-31 10:14:24.078 11157 11220 I jxcore-log: 
,03-31 10:14:24.268 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 10:14:24.268 11157 11220 I jxcore-log: 
,03-31 10:14:24.278 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 10:14:24.278 11157 11220 I jxcore-log: 
,03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 10:14:24.283 11157 11220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 10:14:24.288 11157 11220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 10:14:24.293 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 10:14:24.293 11157 11220 I jxcore-log: 
,03-31 10:14:24.298 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 10:14:24.298 11157 11220 I jxcore-log: 
,03-31 10:14:24.308 11157 11220 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-31 10:14:24.308 11157 11220 I jxcore-log: 
,03-31 10:14:24.313 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 10:14:24.313 11157 11220 I jxcore-log: 
,03-31 10:14:24.523 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:24.523 11157 11220 I jxcore-log: 
,03-31 10:14:24.528 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 52892
03-31 10:14:24.528 11157 11220 I jxcore-log: 
,03-31 10:14:24.533 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 45155, start advertisements: false
,03-31 10:14:24.533 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:24.533 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-31 10:14:24.533 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-31 10:14:24.538 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-31 10:14:24.538 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:24.538 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:24.543  5920  6017 D BtGatt.GattService: registerClient() - UUID=a625e082-e039-4b40-ae2e-1c14f4959fae
,03-31 10:14:24.583  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=a625e082-e039-4b40-ae2e-1c14f4959fae, clientIf=6
,03-31 10:14:24.583 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:24.588  5920 11743 D BtGatt.GattService: start scan with filters
,03-31 10:14:24.593  5920 11743 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 42
,03-31 10:14:24.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:24.598 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:24.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:24.598 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:24.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:24.598  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:24.598  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:24.598  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:24.598 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-31 10:14:24.598 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.598 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:24.598 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:24.598 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-31 10:14:24.598 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.598 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-31 10:14:24.603 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.603 11157 11220 I jxcore-log: 
,03-31 10:14:24.603 11157 11220 I jxcore-log: ok 219 discoveryActive matches
03-31 10:14:24.603 11157 11220 I jxcore-log: 
,03-31 10:14:24.603 11157 11220 I jxcore-log: ok 220 advertisingActive matches
03-31 10:14:24.603 11157 11220 I jxcore-log: 
,03-31 10:14:24.608  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-31 10:14:24.608  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.608  5920  6014 D BtGatt.ScanManager: allow scan with filters
,03-31 10:14:24.608  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:24.608  5920  6014 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-31 10:14:24.608 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.608 11157 11220 I jxcore-log: 
03-31 10:14:24.608  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-31 10:14:24.608  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.608  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:24.608  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-31 10:14:24.608 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-31 10:14:24.608 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.608 11157 11220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-31 10:14:24.608 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:24.608 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:24.608 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:24.608 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-31 10:14:24.608 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:24.608 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-31 10:14:24.608  5920  6017 D BtGatt.GattService: stopScan() - queue size =1
03-31 10:14:24.613  5920 11743 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:24.613  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:24.613  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-31 10:14:24.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-31 10:14:24.613 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:24.613  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:24.613  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.613 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:24.618 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:24.618 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:24.618 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.618 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:24.618  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:24.618  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 9
,03-31 10:14:24.623  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-31 10:14:24.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:24.623  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
,03-31 10:14:24.623  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-31 10:14:24.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.623  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:24.623 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:24.623  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:24.623  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:24.628 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-31 10:14:24.628 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-31 10:14:24.633 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:24.633 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-31 10:14:24.633 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.633 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.633 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:24.633 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-31 10:14:24.633 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.633 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.638 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.638 11157 11220 I jxcore-log: 
,03-31 10:14:24.638 11157 11220 I jxcore-log: ok 221 discoveryActive matches
03-31 10:14:24.638 11157 11220 I jxcore-log: 
,03-31 10:14:24.638 11157 11220 I jxcore-log: ok 222 advertisingActive matches
03-31 10:14:24.638 11157 11220 I jxcore-log: 
,03-31 10:14:24.643 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.643 11157 11220 I jxcore-log: 
,03-31 10:14:24.658 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:24.658 11157 11220 I jxcore-log: 
,03-31 10:14:24.663 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 55826
03-31 10:14:24.663 11157 11220 I jxcore-log: 
,03-31 10:14:24.668 11157 11220 I io.jxcore.node.ConnectionHelper: start: Port number: 55826, start advertisements: true
03-31 10:14:24.668 11157 11220 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-31 10:14:24.668 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:24.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-31 10:14:24.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-31 10:14:24.668 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-31 10:14:24.668 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-31 10:14:24.668 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-31 10:14:24.673  5920  6017 D BtGatt.GattService: registerClient() - UUID=29b79be1-0970-43e2-aa5b-d353f400bb5f
,03-31 10:14:24.713  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=29b79be1-0970-43e2-aa5b-d353f400bb5f, clientIf=6
,03-31 10:14:24.713 11157 11167 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-31 10:14:24.713  5920  5931 D BtGatt.GattService: start scan with filters
,03-31 10:14:24.738  3420  3440 I art     : Background partial concurrent mark sweep GC freed 49442(3MB) AllocSpace objects, 60(3MB) LOS objects, 33% free, 29MB/44MB, paused 6.145ms total 152.643ms
,03-31 10:14:24.743  5920  5931 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 43
,03-31 10:14:24.743  5920  6014 D BtGatt.ScanManager: handling starting scan
03-31 10:14:24.743  5920  6014 D BtGatt.ScanManager: isFilteringSupported
03-31 10:14:24.743  5920  6014 D BluetoothAdapter: setting StandAloneBleMode
03-31 10:14:24.743 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-31 10:14:24.743 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-31 10:14:24.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-31 10:14:24.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-31 10:14:24.748 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.748 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-31 10:14:24.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-31 10:14:24.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-31 10:14:24.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-31 10:14:24.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:24.748 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-31 10:14:24.748 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-31 10:14:24.748  5920  5987 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-31 10:14:24.748  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-31 10:14:24.748  5920  6014 D BtGatt.ScanManager: allow scan with filters
,03-31 10:14:24.748  5920  6014 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-31 10:14:24.748  5920  6014 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
,03-31 10:14:24.753  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-31 10:14:24.753  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.753  5920  6014 D BtGatt.ScanManager: Starting BLE batch scan
03-31 10:14:24.753  5920  6014 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-31 10:14:24.758  5920  5987 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-31 10:14:24.758  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.763  5920  5931 D BtGatt.GattService: registerClient() - UUID=c4a43e80-49e7-451d-a6e6-36188e7f4a86
03-31 10:14:24.763  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-31 10:14:24.763  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:24.803  5920  5987 D BtGatt.GattService: onClientRegistered() - UUID=c4a43e80-49e7-451d-a6e6-36188e7f4a86, clientIf=7
,03-31 10:14:24.803 11157 11167 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-31 10:14:24.823  5920  5933 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 35
03-31 10:14:24.823  5920  6013 D BtGatt.AdvertiseManager: message : 0
03-31 10:14:24.823  5920  6013 D BtGatt.AdvertiseManager: number of adv instance running0
03-31 10:14:24.823  5920  6013 D BtGatt.AdvertiseManager: size of list is =0
03-31 10:14:24.823  5920  6013 D BtGatt.AdvertiseManager: starting advertising
03-31 10:14:24.823  5920  6013 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-31 10:14:24.828  5920  5987 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-31 10:14:24.828  5920  6013 D BtGatt.AdvertiseManager: starting multi advertising
03-31 10:14:24.828  5920  5987 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-31 10:14:24.828  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-31 10:14:24.828  5920  6013 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-31 10:14:24.828 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-31 10:14:24.828 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-31 10:14:24.833 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.833 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-31 10:14:24.833 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-31 10:14:24.833 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.833 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-31 10:14:24.833 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-31 10:14:24.833 11157 11220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-31 10:14:24.833 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-31 10:14:24.833 11157 11220 I io.jxcore.node.ConnectionHelper: start: OK
03-31 10:14:24.833 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-31 10:14:24.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-31 10:14:24.833 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-31 10:14:24.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-31 10:14:24.833 11157 11157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-31 10:14:24.833 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-31 10:14:24.833 11157 11157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:24.833 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-31 10:14:24.833 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-31 10:14:24.833 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.833 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-31 10:14:24.833 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-31 10:14:24.838 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.838 11157 11220 I jxcore-log: 
03-31 10:14:24.838 11157 12070 D BluetoothSocket: bindListen(): myUserId = 0
03-31 10:14:24.838 11157 12070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-31 10:14:24.838 11157 12070 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-31 10:14:24.838 11157 12070 D BluetoothSocket: bindListen(), new LocalSocket 
03-31 10:14:24.838 11157 12070 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-31 10:14:24.838 11157 12070 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aad8378
03-31 10:14:24.838 11157 12070 D BluetoothSocket: channel: 6
03-31 10:14:24.838 11157 12070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-31 10:14:24.843 11157 11220 I jxcore-log: not ok 223 discoveryActive matches
03-31 10:14:24.843 11157 11220 I jxcore-log: 
,03-31 10:14:24.843 11157 11220 I jxcore-log:   ---
03-31 10:14:24.843 11157 11220 I jxcore-log: 
03-31 10:14:24.843 11157 11220 I jxcore-log:     operator: equal
03-31 10:14:24.843 11157 11220 I jxcore-log: 
03-31 10:14:24.843 11157 11220 I jxcore-log:     expected: false
03-31 10:14:24.843 11157 11220 I jxcore-log: 
03-31 10:14:24.843 11157 11220 I jxcore-log:     actual:   true
03-31 10:14:24.843 11157 11220 I jxcore-log: 
03-31 10:14:24.843 11157 11220 I jxcore-log:   ...
03-31 10:14:24.843 11157 11220 I jxcore-log: 
,03-31 10:14:24.848 11157 11220 I jxcore-log: not ok 224 advertisingActive matches
03-31 10:14:24.848 11157 11220 I jxcore-log: 
,03-31 10:14:24.848 11157 11220 I jxcore-log:   ---
03-31 10:14:24.848 11157 11220 I jxcore-log: 
03-31 10:14:24.848 11157 11220 I jxcore-log:     operator: equal
03-31 10:14:24.848 11157 11220 I jxcore-log: 
03-31 10:14:24.848 11157 11220 I jxcore-log:     expected: true
03-31 10:14:24.848 11157 11220 I jxcore-log: 
03-31 10:14:24.848 11157 11220 I jxcore-log:     actual:   false
03-31 10:14:24.848 11157 11220 I jxcore-log: 
03-31 10:14:24.848 11157 11220 I jxcore-log:   ...
03-31 10:14:24.848 11157 11220 I jxcore-log: 
,03-31 10:14:24.853 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-31 10:14:24.853 11157 11220 I jxcore-log: 
,03-31 10:14:24.853 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-31 10:14:24.853 11157 11220 I jxcore-log: 
,03-31 10:14:24.858 11157 11220 I jxcore-log: not ok 225 discoveryActive matches
03-31 10:14:24.858 11157 11220 I jxcore-log: 
,03-31 10:14:24.858 11157 11220 I jxcore-log:   ---
03-31 10:14:24.858 11157 11220 I jxcore-log: 
03-31 10:14:24.858 11157 11220 I jxcore-log:     operator: equal
03-31 10:14:24.858 11157 11220 I jxcore-log: 
03-31 10:14:24.858 11157 11220 I jxcore-log:     expected: false
03-31 10:14:24.858 11157 11220 I jxcore-log: 
03-31 10:14:24.858 11157 11220 I jxcore-log:     actual:   true
03-31 10:14:24.858 11157 11220 I jxcore-log: 
03-31 10:14:24.858 11157 11220 I jxcore-log:   ...
03-31 10:14:24.858 11157 11220 I jxcore-log: 
,03-31 10:14:24.863 11157 11220 I jxcore-log: not ok 226 advertisingActive matches
03-31 10:14:24.863 11157 11220 I jxcore-log: 
,03-31 10:14:24.863 11157 11220 I jxcore-log:   ---
03-31 10:14:24.863 11157 11220 I jxcore-log: 
03-31 10:14:24.863 11157 11220 I jxcore-log:     operator: equal
03-31 10:14:24.863 11157 11220 I jxcore-log: 
03-31 10:14:24.863 11157 11220 I jxcore-log:     expected: false
03-31 10:14:24.863 11157 11220 I jxcore-log: 
03-31 10:14:24.863 11157 11220 I jxcore-log:     actual:   true
03-31 10:14:24.863 11157 11220 I jxcore-log: 
03-31 10:14:24.863 11157 11220 I jxcore-log:   ...
03-31 10:14:24.863 11157 11220 I jxcore-log: 
,03-31 10:14:24.863 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-31 10:14:24.863 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-31 10:14:24.863 11157 11220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-31 10:14:24.863 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-31 10:14:24.863 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-31 10:14:24.863 11157 11220 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30bfba51, channel: 6, state: LISTENING
03-31 10:14:24.863 11157 11220 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30bfba51, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aad8378, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@180d32b6mSocket: android.net.LocalSocket@31d63bb7 impl:android.net.LocalSocketImpl@24f35f24 fd:FileDescriptor[112]
,03-31 10:14:24.863 11157 11220 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31d63bb7 impl:android.net.LocalSocketImpl@24f35f24 fd:FileDescriptor[112]
03-31 10:14:24.863 11157 11220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-31 10:14:24.863 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-31 10:14:24.863 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-31 10:14:24.863 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-31 10:14:24.863 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-31 10:14:24.863 11157 12070 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-31 10:14:24.863 11157 12070 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-31 10:14:24.863 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-31 10:14:24.863 11157 12070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-31 10:14:24.863 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-31 10:14:24.868  5920 11743 D BtGatt.GattService: stopScan() - queue size =1
,03-31 10:14:24.868  5920  6014 D BtGatt.ScanManager: filter size is 1
03-31 10:14:24.868  5920  6014 D BtGatt.ScanManager: delete FilterIndex - 10
,03-31 10:14:24.868  5920  5931 D BtGatt.GattService: unregisterClient() - clientIf=6
03-31 10:14:24.868  5920  5987 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-31 10:14:24.868  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-31 10:14:24.868  5920  6014 D BtGatt.ScanManager: stopping BLe Batch
03-31 10:14:24.868 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-31 10:14:24.868 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.868 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-31 10:14:24.868 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-31 10:14:24.868 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-31 10:14:24.868 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:24.868 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-31 10:14:24.873  5920  5987 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-31 10:14:24.873  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:24.873  5920  6013 D BtGatt.AdvertiseManager: message : 1
03-31 10:14:24.873  5920  6014 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-31 10:14:24.873  5920  6013 D BtGatt.AdvertiseManager: stop advertise for client 7
03-31 10:14:24.873  5920  6013 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-31 10:14:24.873  5920  6013 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-31 10:14:24.873  5920  5987 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-31 10:14:24.873  5920  5987 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-31 10:14:24.873  5920  5987 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-31 10:14:24.873  5920  5987 D BtGatt.GattService: Client app is not null!
03-31 10:14:24.878  5920 11743 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-31 10:14:24.878 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-31 10:14:24.878 11157 11220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-31 10:14:24.878 11157 11220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-31 10:14:24.878 11157 11220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-31 10:14:24.878 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-31 10:14:24.878 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 10:14:24.878 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-31 10:14:24.883 11157 11157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-31 10:14:24.888 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-31 10:14:24.888 11157 11157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-31 10:14:24.888 11157 11157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-31 10:14:24.888 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-31 10:14:24.888 11157 11157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-31 10:14:24.888 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-31 10:14:24.893 11157 11157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-31 10:14:24.893 11157 11157 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-31 10:14:24.893 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-31 10:14:24.893 11157 11157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-31 10:14:24.893 11157 11157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-31 10:14:24.893 11157 11220 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-31 10:14:24.893 11157 11220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-31 10:14:24.893 11157 11220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-31 10:14:24.893 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-31 10:14:24.893 11157 11220 I jxcore-log: 
,03-31 10:14:24.893 11157 11220 I jxcore-log: ok 227 discoveryActive matches
03-31 10:14:24.893 11157 11220 I jxcore-log: 
,03-31 10:14:24.898 11157 11220 I jxcore-log: not ok 228 advertisingActive matches
03-31 10:14:24.898 11157 11220 I jxcore-log: 
,03-31 10:14:24.898 11157 11220 I jxcore-log:   ---
03-31 10:14:24.898 11157 11220 I jxcore-log: 
03-31 10:14:24.898 11157 11220 I jxcore-log:     operator: equal
03-31 10:14:24.898 11157 11220 I jxcore-log: 
03-31 10:14:24.898 11157 11220 I jxcore-log:     expected: false
03-31 10:14:24.898 11157 11220 I jxcore-log: 
03-31 10:14:24.898 11157 11220 I jxcore-log:     actual:   true
03-31 10:14:24.898 11157 11220 I jxcore-log: 
03-31 10:14:24.898 11157 11220 I jxcore-log:   ...
03-31 10:14:24.898 11157 11220 I jxcore-log: 
,03-31 10:14:24.903 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.903 11157 11220 I jxcore-log: 
,03-31 10:14:24.903 11157 11220 I jxcore-log: ok 229 discoveryActive matches
03-31 10:14:24.903 11157 11220 I jxcore-log: 
,03-31 10:14:24.903 11157 11220 I jxcore-log: ok 230 advertisingActive matches
03-31 10:14:24.903 11157 11220 I jxcore-log: 
,03-31 10:14:24.908 11157 11220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-31 10:14:24.908 11157 11220 I jxcore-log: 
,03-31 10:14:24.918 11157 11220 I jxcore-log: DEBUG createNativeListener: creating native server
03-31 10:14:24.918 11157 11220 I jxcore-log: 
,03-31 10:14:24.923 11157 11220 I jxcore-log: DEBUG createNativeListener: listening 44268
03-31 10:14:24.923 11157 11220 I jxcore-log: 
,03-31 10:14:24.933 11157 11220 I jxcore-log: Uncaught Promise Rejection: {}
03-31 10:14:24.933 11157 11220 I jxcore-log: 
,03-31 10:14:24.938 11157 11220 E jxcore-log: Trace: [Error: Call Stop!]
03-31 10:14:24.938 11157 11220 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-31 10:14:24.938 11157 11220 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-31 10:14:24.938 11157 11220 E jxcore-log:     at emit@events.js:98:1
03-31 10:14:24.938 11157 11220 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-31 10:14:24.938 11157 11220 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-31 10:14:24.938 11157 11220 E jxcore-log:     at $0a@node.js:917:1
03-31 10:14:24.938 11157 11220 E jxcore-log: 
,03-31 10:14:24.938 11157 11220 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-31 10:14:24.938 11157 11220 I jxcore-log: 
,03-31 10:14:24.938 11157 11220 I jxcore-log: # teardown
03-31 10:14:24.938 11157 11220 I jxcore-log: 
,03-31 10:14:25.403 12071 12071 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 10:14:25.408 12071 12071 D AndroidRuntime: CheckJNI is OFF
,03-31 10:14:25.408 12071 12071 D AndroidRuntime: readGMSProperty: start
03-31 10:14:25.408 12071 12071 D AndroidRuntime: readGMSProperty: already setted!!
03-31 10:14:25.408 12071 12071 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 10:14:25.408 12071 12071 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 10:14:25.408 12071 12071 D AndroidRuntime: readGMSProperty: end
03-31 10:14:25.408 12071 12071 D AndroidRuntime: addProductProperty: start
,03-31 10:14:25.503 12071 12071 E AffinityControl: AffinityControl: registerfunction enter
,03-31 10:14:25.523 12071 12071 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 10:14:25.533  3420  4361 D PackageManager: START PACKAGE DELETE: observer{306149961}
03-31 10:14:25.533  3420  4361 D PackageManager: pkg{<packageName>}
03-31 10:14:25.533  3420  4361 D PackageManager: user{0}
03-31 10:14:25.533  3420  4361 D PackageManager: caller{2000}
03-31 10:14:25.533  3420  4361 D PackageManager: flags{2}
,03-31 10:14:25.533  3420  4361 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-31 10:14:25.533  3420  4361 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-31 10:14:25.538  3420  3592 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-31 10:14:25.533  3420  4361 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-31 10:14:25.533  3420  4361 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 10:14:25.533  3420  4361 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 10:14:25.538  3420  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-31 10:14:25.538  3420  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-31 10:14:25.538  3420  3592 D ApplicationPolicy: getApplicationUninstallationEnabled
03-31 10:14:25.538  3420  3592 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-31 10:14:25.538  3420  3592 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-31 10:14:25.543  3420  3574 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-31 10:14:25.543  3420  3574 I ActivityManager: Killing 11157:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-31 10:14:25.553  3420  3574 I ActivityManager:   Force finishing activity 3 ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42}
,03-31 10:14:25.558  3420  3574 W ActivityManager: mDVFSHelper.acquire()
,03-31 10:14:25.653  3420  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-31 10:14:25.658  3420  3592 W PackageSettings: Skipping PackageSetting{190f2fcf com.example.hello/10691} due to missing metadata
,03-31 10:14:25.678  3420  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 10:14:25.678  3420  3574 D PowerManagerService: setKeyboardVisibility: false
,03-31 10:14:25.678  3420  3574 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{2bc04b3f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-31 10:14:25.693  3420  3592 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-31 10:14:25.693  6551  6551 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-31 10:14:25.698  3420  3592 I ActivityManager:   Force finishing activity 3 ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42 f}
,03-31 10:14:25.698  3420  3592 W ActivityManager: Duplicate finish request for ActivityRecord{1f77eb9c u0 com.test.thalitest/.MainActivity t42 f}
,03-31 10:14:25.703  3420  3460 I WindowState: WIN DEATH: Window{2413bd0b u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 10:14:25.703  2860  3591 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,03-31 10:14:25.703  2860  4627 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-31 10:14:25.708  3420  3460 D InputDispatcher: Focus left window: 11157
,03-31 10:14:25.708  3420  3460 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 10:14:25.708  2860  4626 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-31 10:14:25.713  3420  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3420 uid:1000
03-31 10:14:25.713  3420  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:14:25.713  3420  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3420 uid:1000
03-31 10:14:25.718  3420  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 10:14:25.723  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 10:14:25.738  3420  3592 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-31 10:14:25.748  3420  3692 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-31 10:14:25.748  3420  3692 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
,03-31 10:14:25.748  3420  3574 D InputDispatcher: Focused application released
,03-31 10:14:25.758  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 10:14:25.763  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 10:14:25.763  9145  9145 I art     : Explicit concurrent mark sweep GC freed 21961(1221KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 483us total 24.540ms
,03-31 10:14:25.763  6551  6551 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
03-31 10:14:25.768  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-31 10:14:25.778  4686  4686 I art     : Explicit concurrent mark sweep GC freed 3200(195KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 733us total 65.118ms
,03-31 10:14:25.783  3420  3632 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 10:14:25.783  3939  3939 I art     : Explicit concurrent mark sweep GC freed 1664(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 651us total 40.626ms
,03-31 10:14:25.788  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-31 10:14:25.788  4541  4541 E SamsungIME: mOCRHelper is null
,03-31 10:14:25.798  4686  4703 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 10:14:25.803  4388  4771 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 10:14:25.803 10637 10637 D LWLocationManager: getDeviceLocationId :  id = -100
03-31 10:14:25.803 10637 10637 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-31 10:14:25.808  4129  4129 I art     : Explicit concurrent mark sweep GC freed 22101(1237KB) AllocSpace objects, 2(32KB) LOS objects, 26% free, 5MB/7MB, paused 845us total 107.811ms
,03-31 10:14:25.813  4012  4012 I art     : Explicit concurrent mark sweep GC freed 15981(918KB) AllocSpace objects, 10(1506KB) LOS objects, 12% free, 56MB/64MB, paused 407us total 55.087ms
,03-31 10:14:25.823  3420  3653 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-31 10:14:25.823  3420  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:14:25.823  3420  3653 V NetworkStats: performPollLocked(flags=0x3)
,03-31 10:14:25.833  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.833  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.833  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.833  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:25.833  3420  3653 V NetworkStats: performPollLocked() took 12ms
03-31 10:14:25.833  3420  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-31 10:14:25.843  5671  5689 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-31 10:14:25.843  5671  5689 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-31 10:14:25.843 12096 12096 E Zygote  : MountEmulatedStorage()
03-31 10:14:25.843 12096 12096 E Zygote  : v2
03-31 10:14:25.843 12096 12096 I libpersona: KNOX_SDCARD checking this for 10063
03-31 10:14:25.843 12096 12096 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:25.848 12096 12096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:25.853 12096 12096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:14:25.853  3420  3574 I ActivityManager: Start proc 12096:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-31 10:14:25.853  3420  3567 D EnterpriseDeviceManagerService: Package has changed for user 0
03-31 10:14:25.853  3420  3567 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-31 10:14:25.853  3420  3567 W TextServicesManagerService: no available spell checker services found
03-31 10:14:25.853  6551  6551 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-31 10:14:25.853 12096 12096 E Zygote  : accessInfo : 0
03-31 10:14:25.853  6551  6551 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-31 10:14:25.853 12096 12096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 10:14:25.873  3420  3592 I art     : Explicit concurrent mark sweep GC freed 26568(1843KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 7.442ms total 124.307ms
,03-31 10:14:25.883  3978  3978 D RegisteredServicesCache: empty dynamic service
,03-31 10:14:25.888  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-31 10:14:25.903  3978  3978 D RegisteredComponentCache: Collect Tech packages for Knox
,03-31 10:14:25.908 12096 12096 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:25.908 12096 12096 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:25.918  3420  3463 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{72cfe7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{11d40498 12096:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-31 10:14:25.928  3420  4361 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-31 10:14:25.928  3420  4361 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-31 10:14:25.943 12096 12096 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-31 10:14:25.943 12096 12096 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-31 10:14:25.943 12096 12096 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-31 10:14:25.943  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-31 10:14:25.943  3420  3833 I ActivityManager: Killing 10042:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-31 10:14:25.948  3420  4008 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-31 10:14:25.948  3420  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:14:25.948  3420  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 10:14:25.948  3420  3833 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{72cfe7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2a3a42d1 7171:com.samsung.klmsagent/u0a21}
,03-31 10:14:25.948  7171  7171 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 31 10:14:25 GMT+02:00 2016
,03-31 10:14:25.948  3420  3977 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-31 10:14:25.953  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-31 10:14:25.958  6551  6551 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-31 10:14:25.963  6551  6551 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-31 10:14:25.963  6551  6551 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-31 10:14:25.963  6551  6551 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-31 10:14:25.963  7171  7171 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-31 10:14:25.963  3420  3651 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 10:14:25.963  3420  3651 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 10:14:25.963  3420  3651 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-31 10:14:25.968  2860  2860 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-31 10:14:25.968  3420  4339 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-31 10:14:25.968  3420  4339 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-31 10:14:25.968  3420  4361 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 10:14:25.968  3420  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{145d7706 u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-31 10:14:25.968  3420  4361 D InputDispatcher: Focus entered window: 6551
,03-31 10:14:25.973  3420  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3420 uid:1000
03-31 10:14:25.973  3420  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 10:14:25.973  3420  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3420 uid:1000
03-31 10:14:25.973  3420  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 10:14:25.973  6551  6551 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-31 10:14:25.973  6551  9161 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-31 10:14:25.973  3420  4339 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{72cfe7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1670085c 6841:com.samsung.aasaservice/1000}
,03-31 10:14:25.978  6841  6841 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-31 10:14:25.978  6551  6551 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-31 10:14:25.978  6841  6841 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-31 10:14:25.978  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.978  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.978  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.978  6841  6841 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-31 10:14:25.978  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:25.978  6841  6841 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:25.978  6841  6841 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:25.978  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:25.978  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:25.978  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:25.978  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:25.978  7171  7171 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-31 10:14:25.978  7171  7171 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-31 10:14:25.978  7171  7171 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
,03-31 10:14:25.983  7171 12112 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : MDMBridge.getInstance()
03-31 10:14:25.983  7171 12112 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-31 10:14:25.988  7171 12112 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-31 10:14:25.988  7171 12112 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-31 10:14:25.988  7171 12112 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-31 10:14:25.993  7171 12112 E KLMS-2.5.262: : arr si null
,03-31 10:14:25.993 12113 12113 E Zygote  : MountEmulatedStorage()
03-31 10:14:25.993 12113 12113 E Zygote  : v2
03-31 10:14:25.993 12113 12113 I libpersona: KNOX_SDCARD checking this for 10042
03-31 10:14:25.993 12113 12113 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:25.993 12113 12113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:25.998  3420  3574 I ActivityManager: Start proc 12113:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-31 10:14:25.998 12113 12113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:25.998 12113 12113 E Zygote  : accessInfo : 0
,03-31 10:14:25.998 12113 12113 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-31 10:14:26.003  7171 12112 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-31 10:14:26.003  7171 12112 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
,03-31 10:14:26.003  7171 12112 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-31 10:14:26.003  7171 12112 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-31 10:14:26.013  3420  3463 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 10:14:26.018  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.018  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.018  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.018  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.018  3420  3463 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11157 uid 10011
,03-31 10:14:26.038 12130 12130 E Zygote  : MountEmulatedStorage()
,03-31 10:14:26.038 12130 12130 E Zygote  : v2
03-31 10:14:26.038 12130 12130 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:14:26.038 12130 12130 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.038  4541  4541 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-31 10:14:26.038 12130 12130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:26.043 12130 12130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:14:26.043  3420  3574 I ActivityManager: Start proc 12130:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
03-31 10:14:26.048 12113 12113 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:14:26.048 12130 12130 E Zygote  : accessInfo : 0
03-31 10:14:26.048 12113 12113 D ActivityThread: Added TimaKeyStore provider
03-31 10:14:26.048 12130 12130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:14:26.048  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.048  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.048  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.048  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.053  3420  3592 D PackageManager: delete codoeFile: 
03-31 10:14:26.053  3420  3592 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
,03-31 10:14:26.058  6551  6551 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@132af37f time:295651
03-31 10:14:26.058  3420  3592 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
,03-31 10:14:26.063  3420  3592 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-31 10:14:26.063  3420  3592 D PackageManager: result of delete: 1{306149961}
,03-31 10:14:26.068  3420  3592 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-31 10:14:26.068  3420  3592 D PackageManager: userId{-1}
03-31 10:14:26.068  3420  3592 D PackageManager: andCode{true}
,03-31 10:14:26.068 12071 12071 I art     : System.exit called, status: 0
03-31 10:14:26.068 12071 12071 I AndroidRuntime: VM exiting with result code 0.
,03-31 10:14:26.078  2901  2901 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 442us total 21.797ms
,03-31 10:14:26.083 12130 12130 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:26.083 12130 12130 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.083  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 300us total 9.023ms
,03-31 10:14:26.093 10637 12102 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 10:14:26.093  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 299us total 8.141ms
,03-31 10:14:26.108 12146 12146 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.108 12146 12146 E Zygote  : v2
03-31 10:14:26.108 12146 12146 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:14:26.108 12146 12146 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.108 12146 12146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:26.108  3420  3574 I ActivityManager: Start proc 12146:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-31 10:14:26.113 12146 12146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:26.113 12146 12146 E Zygote  : accessInfo : 0
03-31 10:14:26.113 12146 12146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 10:14:26.113  3420  4339 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{72cfe7b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{191e4caf 3420:system/1000}
,03-31 10:14:26.118  7171 12112 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-31 10:14:26.118  7171 12112 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-31 10:14:26.118  7171 12112 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-31 10:14:26.118  7171 12112 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-31 10:14:26.123  7171 12112 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 10:14:26.123  7171 12112 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-31 10:14:26.123  7171 12112 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-31 10:14:26.123  7171 12112 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-31 10:14:26.128  3420  4360 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1221c23c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{37f62bc5 12113:com.samsung.android.sdk.samsunglink/u0a42}
,03-31 10:14:26.133 12146 12146 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:26.133 12146 12146 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.138  9812 12162 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-31 10:14:26.138  3420  3460 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1ad28c4b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f66c628 12130:com.samsung.android.sm/1000}
03-31 10:14:26.138  9812 12162 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-31 10:14:26.138  6551  6551 V ActivityThread: updateVisibility : ActivityRecord{13372791 token=android.os.BinderProxy@132af37f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-31 10:14:26.143 12113 12113 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 10:14:26.143  9812 12162 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-31 10:14:26.143  9812 12162 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-31 10:14:26.143  9812 12162 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-31 10:14:26.143  9812 12162 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-31 10:14:26.148 12113 12113 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-31 10:14:26.148  7171  7171 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-31 10:14:26.148  3420  3583 W ActivityManager: mDVFSHelper.release()
03-31 10:14:26.148  3420  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2bc04b3f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:295741
,03-31 10:14:26.158  3420  3748 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a12bf41 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3d876ce6 12146:com.sec.android.app.popupuireceiver/1000}
,03-31 10:14:26.163 10637 12102 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 10:14:26.163 10637 12102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 10:14:26.163 10637 12102 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 10:14:26.163 10637 12102 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-31 10:14:26.168 12130 12130 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 10:14:26.178 12146 12146 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-31 10:14:26.183  3420  3836 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-31 10:14:26.183  3420  3748 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-31 10:14:26.188 12146 12146 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-31 10:14:26.188  3420  4011 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-31 10:14:26.188 12146 12146 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-31 10:14:26.188 12146 12146 D PopupuiReceiver: Action package removed
,03-31 10:14:26.188  3420  3567 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-31 10:14:26.193  3420  3460 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a12bf41 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2d333fba 10563:com.samsung.android.snote/u0a160}
03-31 10:14:26.198  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.198  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.198  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.198  3420  3833 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.213 12130 12130 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/sm.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-31 10:14:26.218 12163 12163 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.218  3420  3567 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 10:14:26.218  3420  3567 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 10:14:26.218  3420  3567 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 10:14:26.218  3420  3567 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-31 10:14:26.218 12163 12163 E Zygote  : v2
03-31 10:14:26.218 12163 12163 I libpersona: KNOX_SDCARD checking this for 10183
03-31 10:14:26.218 12163 12163 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.218  3420  3833 I ActivityManager: Start proc 12163:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-31 10:14:26.223 12163 12163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:26.223  3420  3833 I ActivityManager: Killing 10276:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-31 10:14:26.233 12130 12130 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 10:14:26.233 12163 12163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:26.233 12163 12163 E Zygote  : accessInfo : 0
03-31 10:14:26.233 12163 12163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 10:14:26.238 12130 12130 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: #################################################################
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: #################################################################
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.238 12130 12130 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.ja,va:1199)
03-31 10:14:26.238 12130 12130 D AndroidRuntime: Shutting down VM
03-31 10:14:26.238 12130 12130 E AndroidRuntime: FATAL EXCEPTION: main
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Process: com.samsung.android.sm, PID: 12130
03-31 10:14:26.238 12130 12130 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E AndroidRuntime: #################################################################
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E AndroidRuntime: #################################################################
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3516)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E AndroidRuntime: #################################################################
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.238 12130 12130 E AndroidRuntime: #################################################################
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 10:14:26.238 12130 12130 E AndroidRuntime: 	... 9 more
03-31 10:14:26.243  3420  3651 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1ad28c4b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f66c628 12130:com.samsung.android.sm/1000}
03-31 10:14:26.243  3420  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
03-31 10:14:26.248 12113 12113 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: #################################################################
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: #################################################################
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.253 12113 12113 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.253 12113 12113 D AndroidRuntime: Shutting down VM
03-31 10:14:26.253 12113 12113 E AndroidRuntime: FATAL EXCEPTION: main
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 12113
03-31 10:14:26.253 12113 12113 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E AndroidRuntime: #################################################################
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E AndroidRuntime: #################################################################
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E AndroidRuntime: #################################################################
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.253 12113 12113 E AndroidRuntime: #################################################################
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.253 12113 12113 E AndroidRuntime: 	... 11 more
03-31 10:14:26.253  3420 12175 W System.err: remove failed: EROFS (Read-only file system) : /data/system/dropbox/event_data@1459152819205.txt
03-31 10:14:26.253  3420  4339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
03-31 10:14:26.253  3420 12175 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop225.tmp
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.253  3420 12175 E DropBoxManagerService: 	... 5 more
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.258  3420 12179 E DropBoxManagerService: 	... 5 more
03-31 10:14:26.258  3420 12179 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop226.tmp
03-31 10:14:26.263  3420  3574 I ActivityManager: Killing 10293:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
03-31 10:14:26.263  3420  3574 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1ad28c4b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1f66c628 12130:com.samsung.android.sm/1000}
03-31 10:14:26.268  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.268  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.268  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.268  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.268 12163 12163 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:14:26.268  3420  3420 D RCPManagerService: PackageReceiver onReceive()
03-31 10:14:26.268  3420  3420 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-31 10:14:26.273 12163 12163 D ActivityThread: Added TimaKeyStore provider
03-31 10:14:26.273  3420  3420 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-31 10:14:26.273  3420  3420 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-31 10:14:26.273  3420  3420 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-31 10:14:26.278  3420  3420 I OTPFW   : ProvisionData::getAllEntries Enter
03-31 10:14:26.278  3420  3420 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-31 10:14:26.283 12181 12181 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.283 12181 12181 E Zygote  : v2
03-31 10:14:26.283 12181 12181 I libpersona: KNOX_SDCARD checking this for 10045
03-31 10:14:26.283 12181 12181 I libpersona: KNOX_SDCARD not a persona
03-31 10:14:26.283 12181 12181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:14:26.288  3420  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-31 10:14:26.288  3420  3604 D UsbHostManager: displayNotification : [02h,02h,01h]
03-31 10:14:26.288  3420  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-31 10:14:26.288  3420  3604 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-31 10:14:26.288  3420  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-31 10:14:26.288  3420  3604 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-31 10:14:26.288  3420  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-31 10:14:26.288 12181 12181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:14:26.288  3420  3604 D UsbHostManager: displayNotification : [0ah,00h,01h]
03-31 10:14:26.288 12181 12181 E Zygote  : accessInfo : 0
03-31 10:14:26.293 12181 12181 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 10:14:26.293  3420  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-31 10:14:26.293  3420  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-31 10:14:26.293  3420  3694 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-31 10:14:26.293  3420  3574 I ActivityManager: Start proc 12181:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
03-31 10:14:26.298 12130 12130 I Process : Sending signal. PID: 12130 SIG: 9
03-31 10:14:26.298  3420  3567 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-31 10:14:26.298  3420  3567 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-31 10:14:26.298  3420  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-31 10:14:26.298 12113 12113 I Process : Sending signal. PID: 12113 SIG: 9
03-31 10:14:26.298  3420  3604 D UsbHostManager: displayNotification : [09h,00h,00h]
03-31 10:14:26.298  4012  4012 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-31 10:14:26.303  3420  3836 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a12bf41 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{19ba1501 12163:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-31 10:14:26.303  4012  4079 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 10:14:26.303  4012  4079 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-31 10:14:26.318  4012  4079 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
03-31 10:14:26.318  4012  4079 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4012
03-31 10:14:26.318  4012  4079 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:488)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:586)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:590)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:533)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2432)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.318  4012  4079 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 10:14:26.318  3420  3748 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-31 10:14:26.318  3420  3748 W ActivityManager:   Force finishing activity 1 com.sec.android.app.launcher/com.android.launcher2.Launcher
,03-31 10:14:26.323  4012  4012 D MenuAppsGridFragment: onDestroyView
,03-31 10:14:26.323  4012  4012 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
,03-31 10:14:26.328  3420 12201 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.328  3420 12201 E DropBoxManagerService: 	... 5 more
03-31 10:14:26.328 12181 12181 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 10:14:26.328  3420 12201 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
,03-31 10:14:26.328 12181 12181 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.333  3420  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-31 10:14:26.333  3420  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
03-31 10:14:26.333  4012  4079 I Process : Sending signal. PID: 4012 SIG: 9
,03-31 10:14:26.358  3420  4361 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1221c23c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{26676fa6 12181:com.osp.app.signin/u0a45}
,03-31 10:14:26.378  3420  3632 I EventHub: Removing device '/dev/input/event10' due to inotify event
,03-31 10:14:26.383  3420  3460 I ActivityManager: Process com.samsung.android.sm (pid 12130)(adj 0) has died(276,1466)
,03-31 10:14:26.393 12163 12163 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 10:14:26.398  3420  3651 I ActivityManager: Process com.samsung.android.sdk.samsunglink (pid 12113)(adj 11) has died(288,1466)
,03-31 10:14:26.398 12163 12163 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: #################################################################
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: #################################################################
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at java.lang.reflect.Meth,od.invoke(Native Method)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.398 12163 12163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.398 12163 12163 D AndroidRuntime: Shutting down VM
03-31 10:14:26.398 12163 12163 E AndroidRuntime: FATAL EXCEPTION: main
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 12163
03-31 10:14:26.398 12163 12163 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E AndroidRuntime: #################################################################
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E AndroidRuntime: #################################################################
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-3,1 10:14:26.398 12163 12163 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E AndroidRuntime: #################################################################
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.398 12163 12163 E AndroidRuntime: #################################################################
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.398 12163 12163 E AndroidRuntime: 	... 11 more
,03-31 10:14:26.423  3420  3632 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-31 10:14:26.423  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.423  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.423  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.423  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.453 12181 12181 I SA      : [SSP] onCreated
,03-31 10:14:26.458 12204 12204 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.458 12204 12204 E Zygote  : v2
03-31 10:14:26.458 12204 12204 I libpersona: KNOX_SDCARD checking this for 1000
03-31 10:14:26.458 12181 12181 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/samsungaccount.db" with flag (131138) and mode_t (0) due to error (30)
03-31 10:14:26.458 12204 12204 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.463 12204 12204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/samsungaccount.db'.
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: #################################################################
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: #################################################################
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at com.msc.contentprovider.SamsungServiceProvider.onCreate(SamsungServiceProvider.java:575)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at java.lang.reflect.Method.,invoke(Method.java:372)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 10:14:26.463 12181 12181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-31 10:14:26.463 12181 12181 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/openData.db" with flag (131138) and mode_t (0) due to error (30)
,03-31 10:14:26.468 12181 12181 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/openData.db'.
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: #################################################################
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: #################################################################
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at com.msc.openprovider.OpenContentProvider.onCreate(OpenContentProvider.java:214)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java,:1404)
03-31 10:14:26.468 12181 12181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 10:14:26.468 12204 12204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 10:14:26.468 12204 12204 E Zygote  : accessInfo : 0
,03-31 10:14:26.468  3420  3574 I ActivityManager: Start proc 12204:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-31 10:14:26.468 12204 12204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 10:14:26.473  3420  4011 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,03-31 10:14:26.483  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.483  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.483  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.483  3420  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.488 12181 12181 I SA      : [TPM] There is no property file
,03-31 10:14:26.493 12181 12181 I SA      : [SCU] isHaveSA() - false
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: Can't write: system_app_crash
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 10:14:26.493  3420 12210 E DropBoxManagerService: 	... 5 more
03-31 10:14:26.493  3420 12210 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop228.tmp
,03-31 10:14:26.498 12181 12181 I SA      : [TPM] getModelProperty : null,
,03-31 10:14:26.498 12181 12181 I SA      : [TPM] getCSCProperty : null
03-31 10:14:26.503  3420  3632 I EventHub: Removing device '/dev/input/event8' due to inotify event
,03-31 10:14:26.503 12181 12181 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-31 10:14:26.503 12181 12181 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-31 10:14:26.503 12181 12181 I SA      : [DM] TFT FEATURE: false
03-31 10:14:26.503 12181 12181 I SA      : [SUR] onReceive called
,03-31 10:14:26.503 12181 12181 I SA      : [SUR] Not SA Package.. finish
,03-31 10:14:26.523 12222 12222 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.523 12222 12222 E Zygote  : v2
03-31 10:14:26.523 12222 12222 I libpersona: KNOX_SDCARD checking this for 10190
03-31 10:14:26.523 12222 12222 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.528 12204 12204 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:26.528 12222 12222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:14:26.528 12204 12204 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.538 12222 12222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:26.538  3420  3574 I ActivityManager: Start proc 12222:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-31 10:14:26.538 12222 12222 E Zygote  : accessInfo : 0
,03-31 10:14:26.538 12222 12222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-31 10:14:26.543  3420  3632 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-31 10:14:26.563  3420  3651 I WindowState: WIN DEATH: Window{90dae98 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
,03-31 10:14:26.568  3420  4340 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{1ad28c4b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{832003d 12204:com.samsung.android.app.assistantmenu/1000}
,03-31 10:14:26.578 12222 12222 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:26.583  3420  4360 I ActivityManager: Killing 10401:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-31 10:14:26.583 12222 12222 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.588  3420  3632 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-31 10:14:26.593  3420  4360 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1221c23c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2a8f8d68 4330:android.process.acore/u0a23}
,03-31 10:14:26.603  3420  3977 I ActivityManager: Process com.sec.android.app.launcher (pid 4012)(adj 6) has died(338,1466)
,03-31 10:14:26.618  3420  3632 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-31 10:14:26.623 12163 12163 I Process : Sending signal. PID: 12163 SIG: 9
,03-31 10:14:26.638  3420  3748 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a12bf41 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{258ae032 12222:com.sec.android.widgetapp.tapandpay/u0a190}
,03-31 10:14:26.648  3420  4340 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,03-31 10:14:26.663  3420  3632 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-31 10:14:26.683  3420  4008 D AudioService: getStreamVolume 3 index 0
,03-31 10:14:26.688  3420  4360 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1221c23c u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{38fb0f7f 5671:com.android.contacts/u0a23}
,03-31 10:14:26.703  3420  3748 I ActivityManager: Process com.samsung.android.provider.shootingmodeprovider (pid 12163)(adj 9) has died(384,1466)
,03-31 10:14:26.713 12222 12222 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-31 10:14:26.713 12222 12222 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,03-31 10:14:26.728 10637 10652 W art     : Suspending all threads took: 5.441ms
,03-31 10:14:26.728  3420  3632 I EventHub: Removing device '/dev/input/event14' due to inotify event
,03-31 10:14:26.733 12222 12222 I TapandpayWidget:Utils: Clear T&P info.
,03-31 10:14:26.733 12204 12204 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-31 10:14:26.738  3420  4340 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-31 10:14:26.743 12222 12222 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-31 10:14:26.753  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.758  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.758  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 10:14:26.758  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.763 12204 12240 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-31 10:14:26.768 12204 12240 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: #################################################################
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: #################################################################
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.768 12204 12240 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 10:14:26.768 12204 12240 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.768 12204 12240 W System.err: #################################################################
03-31 10:14:26.768 12204 12240 W System.err: Error Code : 0 (SQLITE_OK)
03-31 10:14:26.768 12204 12240 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-31 10:14:26.768 12204 12240 W System.err: #################################################################
,03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
,03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-31 10:14:26.768 12204 12240 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-31 10:14:26.768 12204 12240 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
,03-31 10:14:26.768 12204 12240 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 10:14:26.768 12204 12240 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 10:14:26.783 12241 12241 E Zygote  : MountEmulatedStorage()
,03-31 10:14:26.783 12241 12241 E Zygote  : v2
,03-31 10:14:26.783 12241 12241 I libpersona: KNOX_SDCARD checking this for 10050
03-31 10:14:26.783 12241 12241 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.788 12241 12241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 10:14:26.793  3420  4360 I ActivityManager: Start proc 12241:com.sec.android.gallery3d/u0a50 for broadcast-4 com.sec.android.gallery3d/.app.PackagesMonitor
03-31 10:14:26.798 12241 12241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:26.798 12241 12241 E Zygote  : accessInfo : 0
03-31 10:14:26.798 12241 12241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 10:14:26.818  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.823  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.823  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.823  3420  4360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 10:14:26.858 12256 12256 E Zygote  : MountEmulatedStorage()
03-31 10:14:26.858 12256 12256 E Zygote  : v2
03-31 10:14:26.858 12256 12256 I libpersona: KNOX_SDCARD checking this for 10193
03-31 10:14:26.858 12256 12256 I libpersona: KNOX_SDCARD not a persona
,03-31 10:14:26.858 12241 12241 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 10:14:26.858 12256 12256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 10:14:26.863 12241 12241 D ActivityThread: Added TimaKeyStore provider
,03-31 10:14:26.868  3420  4360 I ActivityManager: Start proc 12256:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
,03-31 10:14:26.873 12256 12256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 10:14:26.873 12256 12256 E Zygote  : accessInfo : 0
,03-31 10:14:26.883 12256 12256 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
